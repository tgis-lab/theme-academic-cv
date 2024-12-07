---
title: ''
date: 2022-10-24
share: false   
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <style>
        body, html {
            height: 100%;
            margin: 0;
            padding: 0;
        }
        .teamBox {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(calc(25% - 22.5px), 1fr)); /* 每行四个成员，自适应宽度 */
            gap: 22.5px;
            padding: 20px;
            background: linear-gradient(to right, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.8)); /* 背景色 */
            border-radius: 10px;
        }
        .teamMember {
            text-align: center;
            position: relative;
            height: 100%; /* 让每个成员容器占满高度 */
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            padding: 20px;
            box-sizing: border-box;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
            overflow: hidden;
        }
        .teamMember img {
            width: 65%;
            height: auto;
            border-radius: 50%;
            margin-bottom: 15px;
        }
        .teamMember .text-container {
            overflow-y: auto;
        }
        .teamMember strong {
            display: block;
            margin-bottom: 10px;
        }
    </style>
    <title>Team Members</title>
</head>
<body>

<div class="teamBox">
    <!-- 按照这个模板 -->
    <div class="teamMember">
        <img src="/team_images/wangzhiyong.jpg" alt="wangzhiyong">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Dr. Zhiyong Wang</strong>
            <strong>Associate Professor</strong>
            <strong>Research Interests:</strong> Multi agent systems; 3D spatial modeling; Path planning; Built environment
        </div>
    </div>
    <!-- 按照这个模板 -->

 <div class="teamMember">
        <img src="/team_images/zhangyueying.png" alt="Yueying Zhang" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Yueying Zhang</strong>
            <strong>PhD candidate</strong>
            <strong>Research Interests:</strong> Traffic noise modeling; Optimization method
        </div>
    </div>
     <div class="teamMember">
        <img src="/team_images/Weidong Xie.jpg" alt="weidongxie" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Weidong Xie</strong>
            <strong>PhD candidate</strong>
            <strong>Research Interests:</strong> Machine learning; Path planning; Navigation
        </div>
    </div>
     <div class="teamMember">
        <img src="/team_images/linZhaoYu.jpg" alt="linZhaoYu" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Zhaoyu Lin</strong>
            <strong>Postgraduate</strong>
            <strong>Research Interests:</strong> Path planning; 3D spatial modeling
        </div>
    </div>
      <div class="teamMember">
        <img src="/team_images/huangRunZe.jpg" alt="huangRunZe" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Runze Huang</strong>
            <strong>Postgraduate</strong>
            <strong>Research Interests:</strong> Travel and health; Travel data analysis
        </div>
    </div>
     <div class="teamMember">
        <img src="/team_images/yangJinYan.jpg" alt="yangJinYan" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Jinyan Yang</strong>
            <strong>Undergraduate</strong>
            <strong>Research Interests:</strong> shared e-bike and built environment
        </div>
    </div>
     <div class="teamMember"> 
        <img src="/team_images/kongSiKai.jpg" alt="kongSiKai" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Sikai Kong</strong>
            <strong>Undergraduate</strong>
            <strong>Research Interests:</strong> Traffic monitoring based on computer vision
        </div>
    </div>
     <div class="teamMember">
        <img src="/team_images/xiangZiWei.jpg" alt="xiangZiWei" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Ziwei Xiang</strong>
            <strong>Undergraduate</strong>
            <strong>Research Interests:</strong>  Analysis of the causes of traffic accidents; Path planning; IndoorGML
        </div>
    </div>
     <div class="teamMember">
        <img src="/team_images/gongTaiLin.jpg" alt="gongTaiLin" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Tailin Gong</strong>
            <strong>Undergraduate</strong>
            <strong>Research Interests:</strong> Simultaneous Localization and Mapping, path planning
        </div>
    </div>
      <div class="teamMember">
        <img src="/team_images/chenNianRu.jpg" alt="chenNianRu" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Nianru Chen</strong>
            <strong>Undergraduate</strong>
            <strong>Research Interests:</strong> Indoor and outdoor integrated navigation
        </div>
    </div>
     <div class="teamMember">
        <img src="/team_images/wangYiPing.jpg" alt="wangYiPing" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Yiping Wang</strong>
            <strong>Undergraduate</strong>
            <strong>Research Interests:</strong>  UVA path planning
        </div>
    </div>
</div>

</body>
</html>






