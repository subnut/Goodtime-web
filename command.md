### Command that I used to generate the blank.mp4

```sh
ffmpeg -f lavfi -i color=size=2x2:rate=1:color=black -f lavfi -i anullsrc=channel_layout=mono:sample_rate=1 -t 1 vid2.mp4
```
