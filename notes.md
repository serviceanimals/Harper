ffmpeg -i ../20200809_202745.mp4 -r 1/1 MQS%03d.jpg

ffmpeg -i ../20200809_202745.mp4 -r 15 -vf scale=512:-1 -ss 00:00:03 -to 00:00:06 MQSHarper.gif
