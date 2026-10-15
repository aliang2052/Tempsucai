# Tempsucai 素材库

用于集中存放可复用的素材。

## 目录

- `materials/videos/`：视频素材，目前包含 `sdf.mp4`。
- `materials/audio/音乐素材/`：音乐和音效素材，保留 `音乐/`、`音效/` 分类，共 28 个音频文件。

后续可按需要在 `materials/` 下添加 `images/`、`audio/` 等目录。

## 添加素材

视频使用 Git LFS 保存。克隆和上传前请安装 Git LFS，并运行 `git lfs install`。

将新视频放入 `materials/videos/`，再执行：

```bash
git add materials/videos/
git commit -m "添加视频素材"
git push
```

已配置 MP4、MOV、MKV、WEBM 和 M4V 格式由 Git LFS 管理。
克隆后如需补全视频文件，可运行 `git lfs pull`。
