# Daily Learning
## Morning Planning

<img alt="cat saying good morning"
src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExdWx2Zmd6djRibjU5emJycWljZGFwMHRqa2E3d3NpM3YzMW9jaHA2aiZlcD12MV9naWZzX3NlYXJjaCZjdD1n/fwQs1TWZVo7y6wMf3e/giphy.gif"
     width="140" align="right">

- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [Github Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.

## Review
Convert an image or video from dark mode to liht mode using [ffmpeg](https://ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
