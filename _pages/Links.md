---
layout: archive
title: "Links"
permalink: /Links/
author_profile: true
---

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Friendlinks</title>
  <style>
    /* 好友链接列表样式 */
    .friend-links-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 20px;
    }
    /* 每个好友的卡片样式 */
    .friend-card {
      background-color: #f0f0f0;
      border-radius: 10px;
      padding: 15px;
      width: 200px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      cursor: pointer;
      transition: transform 0.2s ease;
    }
    .friend-card:hover {
      transform: translateY(-5px);
    }
    /* 好友头像样式 */
    .avatar {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 10px;
    }
    /* 好友名字样式 */
    .friend-name {
      font-size: 18px;
      font-weight: bold;
      color: #333;
    }
    /* 好友介绍样式 */
    .friend-intro {
      font-size: 14px;
      color: #777;
    }
  </style>
</head>
<body>


<h2>下载专区</h2>
<ul>
  <li><a href="../files/test.pdf">机器人学</a></li>
</ul>

<h2>友链</h2>

<br/><br/>
<div class="friend-links-container">
    <!-- 每个好友卡片 -->
    <div class="friend-card" style="background-color: #f0f0f0;">
      <a href="https://satopikac.github.io" target="_blank">
        <img src="../images/mqy.jpg" alt="Satopikac's Blog" class="avatar" onerror="this.onerror=null;this.src='../images/default-avatar.jpg';">
        <div class="friend-name">Satopikac's Blog</div>
        <div class="friend-intro">上士闻道, 勤而行之</div>
      </a>
    </div>
  </div>
<br/><br/><br/>




<br/>

<!-- Giscus 评论系统嵌入 -->
<script src="https://giscus.app/client.js"
        data-repo="qy-mei/portal"
        data-repo-id="R_kgDOOzyKNg"
        data-category="Announcements"
        data-category-id="DIC_kwDOOzyKNs4Cq4J3"
        data-mapping="url"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="1"
        data-input-position="top"
        data-theme="light"
        data-lang="zh-CN"
        data-loading="lazy"
        crossorigin="anonymous"
        async>
</script>
