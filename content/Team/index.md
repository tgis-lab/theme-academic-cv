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
        <img src="/team_images/Lan Hu.jpg" alt="hulang" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Lang Hu</strong>
            <strong>Postgraduate</strong>
            <strong>Research Interests:</strong> 3D spatio-temporal foundation；Path planning
        </div>
    </div>
     <div class="teamMember"> 
        <img src="/team_images/Zhendong Wu" alt="wuzhendong" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Zhendong Wu</strong>
            <strong>Postgraduate</strong>
            <strong>Research Interests:</strong> UAV path planning; Convolutional Neural Network
        </div>
    </div>
     <div class="teamMember">
        <img src="/team_images/xiangZiWei.jpg" alt="xiangZiWei" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Ziwei Xiang</strong>
            <strong>Postgraduate</strong>
            <strong>Research Interests:</strong>  Analysis of the causes of traffic accidents; Path planning; IndoorGML
        </div>
    </div>
     <div class="teamMember">
        <img src="/team_images/Zhuojian Li.jpg" alt="lizhuojian" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Zhuojian Li</strong>
            <strong>Undergraduate</strong>
            <strong>Research Interests:</strong> Intelligent scheduling; Path planning
        </div>
    </div>
      <div class="teamMember">
        <img src="/team_images/Chenzong Liu.jpg" alt="chenzongliu" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Chenzhong Liu</strong>
            <strong>Undergraduate</strong>
            <strong>Research Interests:</strong> Intelligent transportation systems and urban data analysis
        </div>
    </div>
      <div class="teamMember">
        <img src="/team_images/Chenzong Liu.jpg" alt="chenzongliu" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Chenzhong Liu</strong>
            <strong>Undergraduate</strong>
            <strong>Research Interests:</strong> Intelligent transportation systems and urban data analysis
        </div>
    </div>
     <div class="teamMember">
        <img src="/team_images/Jianing Zhao.jpg" alt="zhaojianing" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Jianing Zhao</strong>
            <strong>Undergraduate</strong>
            <strong>Research Interests:</strong>  Path planning; Data visualization processing; Intelligent transportation research
        </div>
    </div>
    </div>
     <div class="teamMember">
        <img src="/team_images/Yichen Wu.jpg" alt="wuyichen" class="img-zoom">
        <div style="margin-top: 15px; text-align: left;">
            <strong>Yichen Wu</strong>
            <strong>Undergraduate</strong>
            <strong>Research Interests:</strong>  3D modeling and processing in architecture
        </div>
    </div>
</div>

</body>
</html>






