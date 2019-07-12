Este vídeo foi obtido originalmente em:
https://www.youtube.com/watch?v=FgwW-TjSyxg

editado utilizando o comando ffmpeg do linux:

# recorte do vídeo
feito com:

ffmpeg -ss 00:00:49 -i Slocum_Glider_2016_Animation.mp4 -t 00:00:48 -vcodec copy -acodec copy teste.mp4

# remoção do audio
feito com:

ffmpeg -i teste.mp4 -vcodec copy -an glider_edited_mute.mp4
