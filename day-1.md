# Daily Learning

## Morning Planning

- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.

## Review

Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
Don't type the extra backticks shown around the outside of my example—they are only being used here to display the Markdown correctly.

### 3. Preview

Click **Preview**.

You should see:

**Review**

Convert an image or video from dark mode to light mode using ffmpeg

and underneath it, a formatted code block containing:

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
