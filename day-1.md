# Daily Learning
## Morning Planning
- [ ] Check out the [github blog](http://github.com/blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post to an actual webpage
## Review
Convert an image or video from dark mode to light mode using [ffmpeg]9http://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2;saturation=1.1" output.mp4
```
