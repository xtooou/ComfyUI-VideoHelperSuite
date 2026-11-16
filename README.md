🎬 优化播放体验：调整了视频预览逻辑，不再默认“无脑循环播放”。

🚀 新增控制按键：加入了视频“播放/暂停”按键，方便控制预览。

📊 新增信息显示：增加了视频分辨率信息显示，方便查看生成结果。

🐛 修复opencv-python库与opencv-contrib-python导致的文件文件互相覆盖BUG

🔧 修复日志：新版前端走 comfyAPI 分支、完全不加载 legacy 文件，警告消失；老版本整合包仍能正常工作。
    COMFYUI，Detected import of deprecated legacy 
    API: /extensions/core/widgetInputs.js. This is likely caused by a custom node extension using outdated 
    APIs. Please update your extensions or contact the extension author for an updated version.
