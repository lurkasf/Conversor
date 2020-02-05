run "cd ENTRADA"

run "for i in *.gif;  do ffmpeg -i "$i" "./SAIDA/${i%.*}.webp"; done"
or
run "./run.sh"
