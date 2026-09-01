# AGENTS.md — media

## What this is
Collection of shell scripts for media manipulation using command-line tools (extracting audio from YouTube, adding MP3 to MP4, looping MP4s).

## Stack
- Shell (Bash)
- ffmpeg / youtube-dl family (command-line media tools)

## Run
Each script is a standalone CLI helper, e.g.:
```bash
./get_audio_from_youtube.sh
./add_mp3_to_mp4.sh
./loop_mp4.sh
./tim_audio.sh
```

## Structure
- `get_audio_from_youtube.sh` — download audio from YouTube
- `add_mp3_to_mp4.sh` — mux MP3 into MP4
- `loop_mp4.sh` — loop MP4 videos
- `tim_audio.sh` — audio timing helper

## Conventions
- No comments in code unless asked.
- Verify: `bash -n <script>`.
