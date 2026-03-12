<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>在线视频预览 | 鼎铭科技九周年</title>
    <!-- 美化样式，适配手机+电脑 -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft YaHei", sans-serif;
        }
        body {
            background-color: #f5f5f5;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px 20px;
        }
        .container {
            max-width: 1000px;
            width: 100%;
            background: white;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
            padding: 30px;
        }
        h1 {
            color: #333;
            text-align: center;
            margin-bottom: 30px;
            font-size: 28px;
        }
        /* 视频播放器样式 */
        .video-player {
            width: 100%;
            aspect-ratio: 16/9;
            border-radius: 8px;
            overflow: hidden;
            background: #000;
        }
        video {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
        .video-info {
            margin-top: 20px;
            color: #666;
            line-height: 1.6;
        }
        .tips {
            margin-top: 30px;
            padding: 15px;
            background: #f8f9fa;
            border-left: 4px solid #007bff;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>鼎铭科技九周年纪念视频</h1>
        
        <!-- 核心视频播放区域 -->
        <div class="video-player">
            <video controls preload="metadata">
                <!-- 替换成你的视频链接 -->
                <source src="https://www.w3school.com.cn/i/movie.mp4" type="video/mp4">
                你的浏览器不支持HTML5视频播放，请升级浏览器！
            </video>
        </div>

        <!-- 视频说明（可自定义） -->
        <div class="video-info">
            <h3>视频介绍</h3>
            <p>这是鼎铭科技九周年纪念视频，感谢所有同事的付出与陪伴！</p>
        </div>

        <!-- 提示信息 -->
        <div class="tips">
            <strong>使用提示：</strong><br>
            1. 点击视频画面可暂停/播放<br>
            2. 拖动进度条可快进/快退<br>
            3. 支持全屏播放（点击右下角全屏按钮）
        </div>
    </div>
</body>
</html>
