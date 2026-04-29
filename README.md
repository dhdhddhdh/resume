# Public Assets

这个目录用于存放会被直接部署的静态资源。

## 推荐目录

```text
public/
  images/      项目截图、头像、证书图片、封面图
  videos/      项目演示视频
  documents/   PDF 简历、证书 PDF、作品说明文档
```

## 引用方式

```jsx
<img src="/images/project-cover.png" alt="项目封面" />

<video controls src="/videos/project-demo.mp4" />

<a href="/documents/resume.pdf">下载简历</a>
```

`public` 下的文件会在 `npm run build` 时原样复制到 `dist` 中。
