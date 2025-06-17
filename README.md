# electric-violin
ardour

- qjackctl
- executer un script apres le demarrage
- pactl load-module module-jack-sink channels=2; pactl load-module module-jack-source channels=2; pacmd set-default-sink jack_out
<image 111>
- alsamixer
- pavucontrol
- apres executer un script : pactl load-module module-jack-sink channels=2; pactl load-module module-jack-source channels=2; pacmd set-default-sink jack_out
puis il faut remplir : xrun of at least ([0-9|\.]+) msecs
