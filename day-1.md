# Daily Learning

## Morning Planning
![Cloudy morning](https://octodex.github.com/images/cloud.jpg)
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.






## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```


- Item 1
- Item 2
- Item 3

1. Step 1
1. Step 2
1. Step 3

- [x] This task is complete
- [ ] This task is not complete


仓库中图片的相对网址：
![Mona the Octocat](myrepo/original.png)

互联网图片的绝对链接：
![Mona the Octocat](https://octodex.github.com/images/original.png)


- 字段指定了备选文本。`alt`  
- 字段指定图片的来源网址。`src`
- 可以使用 and/or 字段来指定像素大小。`width` `height`
- 该字段允许设置位置（`align` `leftright`)
<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="right">
