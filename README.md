# Python-SDP
Primative library to generate SDP data for automated calls.

How to use the library.

You can generate basic SDP data for audio calls by calling generate_sdp and passing the port audio RTP will be sent to, you also pass a list of support rtp profiles see https://en.wikipedia.org/wiki/RTP_audio_video_profile for a full list
call_sdp = sdp.generate_sdp(self, local_ip, audio_media_port, [rtp_profile])