# Video Builder

This small tool was written to create talk videos from the Swiss Python Summit.

## 2016

Input is an audio file with the recorded audio for a single talk, as well as a
video for a whole block of talks.

Operations done by this script:

- Take the input video
- Apply offset and duration
- Combine with separately recorded audio, discard video audio
- Apply noise removal filter
- Re-encode video as x264 / 8000 kbps
- Re-encode audio as aac / 384 kbps

The conversion is handled by ffmpeg.
