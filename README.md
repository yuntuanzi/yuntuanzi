<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>云团子 (yuntuanzi) - GitHub个人主页</title>
    <style>
        :root {
            --github-black: #24292e;
            --github-blue: #0366d6;
            --github-gray: #f6f8fa;
            --github-border: #e1e4e8;
            --card-shadow: 0 3px 6px rgba(0,0,0,0.1);
            --card-hover-shadow: 0 5px 15px rgba(0,0,0,0.15);
        }
        
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
        }
        
        body {
            background-color: var(--github-gray);
            color: var(--github-black);
            line-height: 1.5;
            padding: 20px;
            max-width: 1280px;
            margin: 0 auto;
        }
        
        .container {
            background: white;
            border-radius: 6px;
            border: 1px solid var(--github-border);
            padding: 30px;
            margin-bottom: 20px;
        }
        
        header {
            text-align: center;
            margin-bottom: 30px;
        }
        
        h1 {
            font-size: 28px;
            margin-bottom: 10px;
        }
        
        h2 {
            font-size: 22px;
            margin: 25px 0 15px;
            padding-bottom: 10px;
            border-bottom: 1px solid var(--github-border);
        }
        
        .badges {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
        }
        
        .badge {
            background: var(--github-gray);
            border: 1px solid var(--github-border);
            border-radius: 4px;
            padding: 5px 10px;
            font-size: 14px;
            display: inline-flex;
            align-items: center;
        }
        
        .badge img {
            margin-right: 5px;
            height: 20px;
        }
        
        .stats {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 30px 0;
        }
        
        .stats img {
            border-radius: 6px;
            border: 1px solid var(--github-border);
        }
        
        .contact-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        
        .contact-table th, .contact-table td {
            border: 1px solid var(--github-border);
            padding: 12px;
            text-align: left;
        }
        
        .contact-table th {
            background-color: var(--github-gray);
        }
        
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .project-card {
            background: white;
            border: 1px solid var(--github-border);
            border-radius: 6px;
            overflow: hidden;
            transition: all 0.3s ease;
            box-shadow: var(--card-shadow);
        }
        
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: var(--card-hover-shadow);
        }
        
        .project-card-header {
            padding: 15px;
            border-bottom: 1px solid var(--github-border);
            background-color: var(--github-gray);
        }
        
        .project-card-body {
            padding: 15px;
        }
        
        .project-card-title {
            font-size: 18px;
            font-weight: 600;
            margin-bottom: 10px;
            color: var(--github-blue);
        }
        
        .project-card-desc {
            font-size: 14px;
            color: #586069;
            margin-bottom: 15px;
        }
        
        .project-card-footer {
            padding: 10px 15px;
            background-color: var(--github-gray);
            border-top: 1px solid var(--github-border);
            font-size: 13px;
        }
        
        @media (max-width: 768px) {
            .projects-grid {
                grid-template-columns: 1fr;
            }
            
            .stats {
                flex-direction: column;
                align-items: center;
            }
            
            .stats img {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>👋 你好，我是云团子 (yuntuanzi)</h1>
            <p>💻 Web开发者 | 🐘 PHP 开发者 | 🎨 HTML/CSS 爱好者</p>
        </header>

        <section>
            <h2>🚀 技术栈</h2>
            <div class="badges">
                <span class="badge">PHP</span>
                <span class="badge">HTML5</span>
                <span class="badge">CSS3</span>
                <span class="badge">JavaScript</span>
            </div>
        </section>

        <section>
            <h2>📊 我的统计</h2>
            <div class="stats">
                
                
            </div>
            <div class="stats">
                
            </div>
        </section>

        <section>
            <h2>📫 联系方式</h2>
            <table class="contact-table">
                <tr>
                    <th>邮箱</th>
                    <th>站长交流群</th>
                </tr>
                <tr>
                    <td>ccssna@qq.com</td>
                    <td>884503935</td>
                </tr>
            </table>
        </section>

        <section>
            <h2>🎯 代表作</h2>
            <div class="projects-grid">
                <!-- TuanICP项目卡片 -->
                <div class="project-card">
                    <div class="project-card-header">
                        <div class="project-card-title">TuanICP二次元虚拟备案系统</div>
                    </div>
                    <div class="project-card-body">
                        <p class="project-card-desc">开源、UI可爱、界面美观的第三方icp虚拟备案系统，适合作为博客页脚装饰。</p>
                    </div>
                    <div class="project-card-footer">
                        链接: <a href="链接5">项目详情</a>
                    </div>
                </div>
                
                <!-- TuanBBS项目卡片 -->
                <div class="project-card">
                    <div class="project-card-header">
                        <div class="project-card-title">TuanBBS喜灰论坛</div>
                    </div>
                    <div class="project-card-body">
                        <p class="project-card-desc">基于喜羊羊与灰太狼主题的论坛系统，提供社区交流功能。</p>
                    </div>
                    <div class="project-card-footer">
                        链接: <a href="https://github.com/yuntuanzi/TuanBBS">GitHub仓库</a>
                    </div>
                </div>
                
                <!-- 域名停靠页卡片 -->
                <div class="project-card">
                    <div class="project-card-header">
                        <div class="project-card-title">精美域名停靠页</div>
                    </div>
                    <div class="project-card-body">
                        <p class="project-card-desc">优雅的域名停放页面设计，展示域名信息并提供联系方式。</p>
                    </div>
                    <div class="project-card-footer">
                        链接: <a href="https://github.com/yuntuanzi/Domain-Parking">GitHub仓库</a>
                    </div>
                </div>
                
                <!-- TuanPIC项目卡片 -->
                <div class="project-card">
                    <div class="project-card-header">
                        <div class="project-card-title">TuanPIC个人相册</div>
                    </div>
                    <div class="project-card-body">
                        <p class="project-card-desc">轻量级、好看、实用美观的个人相册，支持自动分类和一键同步。</p>
                    </div>
                    <div class="project-card-footer">
                        链接: <a href="链接6">项目详情</a>
                    </div>
                </div>
                
                <!-- YinghuoICP项目卡片 -->
                <div class="project-card">
                    <div class="project-card-header">
                        <div class="project-card-title">YinghuoICP萤火备案系统</div>
                    </div>
                    <div class="project-card-body">
                        <p class="project-card-desc">基于TuanICP开发的二次元主题虚拟备案系统，全新动漫视觉体验。</p>
                    </div>
                    <div class="project-card-footer">
                        链接: <a href="链接4">项目详情</a>
                    </div>
                </div>
                
                <!-- 18+网页恶搞卡片 -->
                <div class="project-card">
                    <div class="project-card-header">
                        <div class="project-card-title">18+网页恶搞提示</div>
                    </div>
                    <div class="project-card-body">
                        <p class="project-card-desc">炫酷的年龄验证页面，带有粒子动画和Cookie存储功能。</p>
                    </div>
                    <div class="project-card-footer">
                        链接: <a href="链接1">项目详情</a>
                    </div>
                </div>
            </div>
        </section>
    </div>
</body>
</html>
