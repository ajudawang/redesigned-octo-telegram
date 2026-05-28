<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>操作证办证记录查询</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: "微软雅黑", sans-serif; }
        body { background: #f5f5f5; padding: 15px; }
        .header { text-align: center; font-size: 18px; font-weight: bold; margin-bottom: 20px; }
        .user-card { background: #fff; padding: 15px; border-radius: 8px; margin-bottom: 20px; display: flex; align-items: center; }
        .user-card img { width: 80px; height: 80px; border-radius: 4px; margin-right: 15px; }
        .user-info p { margin: 5px 0; }
        .info-list { background: #fff; padding: 15px; border-radius: 8px; margin-bottom: 20px; }
        .info-item { display: flex; justify-content: space-between; padding: 10px 0; border-bottom: 1px solid #eee; }
        .info-item:last-child { border-bottom: none; }
        .photo-section { background: #fff; padding: 15px; border-radius: 8px; }
        .photo-section h3 { margin-bottom: 10px; font-size: 16px; }
        .photo-section img { width: 100%; max-width: 500px; border-radius: 4px; }
    </style>
</head>
<body>
    <div class="header">操作证办证记录</div>
    <!-- 用户信息卡片 -->
    <div class="user-card">
        <img src="曹来成照片.jpg" alt="曹来成照片">
        <div class="user-info">
            <p><strong>曹来成</strong></p >
            <p>371728200403192710</p >
            <p>广西建和升建筑工程机械租赁有限公司</p >
        </div>
    </div>
    <!-- 证件信息列表 -->
    <div class="info-list">
        <div class="info-item">
            <span>培训日期</span>
            <span>2026-05-20</span>
        </div>
        <div class="info-item">
            <span>操作证有效期</span>
            <span>2027-05-19</span>
        </div>
        <div class="info-item">
            <span>操作证编号</span>
            <span>No.GKPX2026051901877</span>
        </div>
        <div class="info-item">
            <span>操作机型</span>
            <span>电动臂车</span>
        </div>
    </div>
    <!-- 签字照片区域 -->
    <div class="photo-section">
        <h3>签字照片——操作培训单签字照片</h3>
        <img src="曲臂车.jpg" alt="操作培训单签字照片">
    </div>
</body>
</html>
