### align_aframes
Align frames when converting from low-resolution formats to
high-resolution formats. Primarily used with audio streams.

### flv_copyts
Implements ATC (absolute timecode) when publishing RTMP stream with ffmpeg.
Do not forget to add `publish_time_fix off` in nginx-rtmp configuration.
FFmpeg encodes big RTMP timestamps in a different way than Adobe software.

### flv_discont
Adds DISCONT flag to flv demuxer to enable timestamp discontinuities in RTMP.

### h264_pps_no_profile_check
Removes h264 error complains.

### mpegts-33bit
Implements smooth 33-bit mpeg-ts timestamp overflow in mpegts muxer.
