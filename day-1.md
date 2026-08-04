# Daily Learning

<img alt = "Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width = "100" align = "right" >

## Morning Planning

- [ ] 查看 [GitHub Blog](https://github.blog/) 获取选题灵感  
- [ ] 学习 [GitHub Pages](https://skills.github.com/#first-day-on-github) 的使用方法  
- [ ] 将我的第一篇博客转换为网页形式  

## Review
## 使用仓库内相对路径插入图片：
![Mona the Octocat](https://raw.githubusercontent.com/gitcn-org/communicate-using-markdown/main/.github/steps/myrepo/original.png)

## 使用外部URL，绝对路径接插入图片：
![Mona the Octocat](https://octodex.github.com/images/original.png)


使用 [ffmpeg](https://www.ffmpeg.org) 将图片或视频从深色模式转换为浅色模式

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```


# HTML 写法

### 在实际使用中，经常需要控制图片大小或排版（比如和文字并排）。这时可以使用 HTML 语法获得更高的灵活性。

- alt：图片无法显示时的替代文本
- src：图片来源地址
- width / height：控制尺寸（像素）
- align：控制对齐方式（left / right）
