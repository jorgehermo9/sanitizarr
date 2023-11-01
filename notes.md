# FFMPEG QSV

see https://forum.jellyfin.org/t-arc-a380-qsv-hwa?pid=3372#pid3372

example command: `/usr/lib/jellyfin-ffmpeg/ffmpeg -qsv_device /dev/dri/renderD128 -hwaccel qsv -hwaccel_output_format qsv -i Rick\ and\ Morty\ -\ S01E02\ -\ Lawnmower\ Dog\ -\ Bluray-1080p.mp4 -c:v h264_qsv -c:a copy -c:s copy -vf "scale_qsv=format=nv12" output.mkv`
