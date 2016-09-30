# ml-jukebox
Jukebox powered by NodeJS, MarkLogic, and VLC

##### Notes
```vlc -I http --http-port 8080 --http-password "password" -vvv --sout-keep --sout "#transcode{acodec=vorb,ab=128,channels=2,samplerate=44100}:gather:std{access=http,mux=ogg,dst=:8999}"```