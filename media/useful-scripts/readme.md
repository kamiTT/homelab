# scripts
Helpful scripts for formatting media files downloaded via yt-dlp

Converting all mkv files in a directory to mp4

`for f in *.mkv; do ffmpeg -i "$f" -c:v libx264 -crf 23 -preset fast -movflags +faststart -c:a aac -b:a 192k "${f%.*}.mp4"; done`