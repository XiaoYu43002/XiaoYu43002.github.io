---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: 首页

---

<div class="container">
    <a href="/blog/" class="post">
        <div class="content">
            <h2>我的博客</h2>
            <p>欢迎来到我的博客！在这里，我将分享在生信学习过程中的点滴、记录一些常见的软件或者R包等的使用、以及分享一些必要的例子供大家学习和参考，并防止自己忘记一些知识点。</p>
        </div>
    </a>
    <a href="/learning/" class="post">
        <div class="content">
            <h2>学习心得</h2>
            <p>我将分享我在学习过程中积累的经验与心得，包括编程技巧、工具使用过程中的难点和不理解的地方，希望能够帮助大家在生信学习过程中理解一些必要的信息和解决一些在学习和使用过程中遇到的难题和难点。</p>
        </div>
    </a>
    <a href="/systematic-learning/" class="post">
        <div class="content">
            <h2>系统学习</h2>
            <p>系统学习是我提升自己的方法之一。我会将我的学习方法、学习资源整理在这里供大家参考。</p>
        </div>
    </a>
    <a href="/about/" class="post">
        <div class="content">
            <h2>关于我</h2>
            <p>我是一个热爱编程和旅行的开发者。我喜欢探索新技术，也喜欢在旅途中寻找灵感。</p>
        </div>
    </a>
</div>

<style>

/* 容器样式 */
.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 20px;
    box-sizing: border-box;
    background: linear-gradient(to bottom right, #FFFACD, #FFFFFF); /* 浅黄色到白色的渐进背景 */
    border-radius: 15px; /* 确保容器本身也有圆角效果 */
}

/* 模块样式 */
.post {
    background: #fff;
    margin: 10px;
    flex: 1 1 calc(48% - 20px); /* 每个模块占据48%宽度，减去margin */
    border-radius: 15px; /* 四角半圆 */
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    box-sizing: border-box;
    text-align: center;
    text-decoration: none; /* 移除默认链接下划线 */
    color: inherit;
    display: block;
    overflow: hidden; /* 确保内容被正确裁剪 */
}

/* 模块内的内容样式 */
.post .content {
    padding: 20px;
}

/* 保证等高 */
.container .post {
    min-height: 200px; /* 根据需要调整高度 */
}

@media (max-width: 768px) {
    .post {
        flex: 1 1 calc(100% - 20px); /* 移动设备上模块占据全宽 */
        margin-bottom: 20px;
    }
}
</style>
