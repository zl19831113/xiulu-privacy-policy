# 眼控打字板（第一版）

浏览器里运行的眼动选字工具：前置摄像头 + MediaPipe 人脸关键点，眼睛在格子上停留即选中。

- 在线地址（合并到 main 后生效）：https://zl19831113.github.io/xiulu-privacy-policy/eye-typer/
- 必须用 https 打开，否则浏览器不给摄像头权限。
- 所有计算在本机完成，不上传任何画面。
- `vendor/` 里是 MediaPipe 0.10.14 运行时和 face_landmarker 模型，自带是为了国内能直接加载。

改板面内容：编辑 `index.html` 顶部的 `BOARD` 数组。
