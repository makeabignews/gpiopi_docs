###wave

1)mp3 3 pcw wave

```
apt install ffmpeg
```

```
ffmpeg -i input.mp3 -acodec pcm_s16le -ar 44100 -ac 1 output.wav
```
