## 鲁虺图尺匠（PicSizer）图片尺寸调整器

http://picsizer.luhui.net


免费的在线图片尺寸调整工具，专为需要快速处理图片的用户设计。无需下载安装任何软件，直接在浏览器中即可完成所有操作。


# 图尺匠（PicSizer）演示截图

![演示截图](http://picsizer.luhui.net/screenshots.jpg)

图尺匠（PicSizer）是一款免费的在线图片尺寸调整工具，专为需要快速处理图片的用户设计。无需下载安装任何软件，直接在浏览器中即可完成所有操作。

## 功能特点

- 免费在线使用，无需安装软件
- 支持图片尺寸调整、大小调整
- 支持批量处理图片
- 适配各种社交媒体常见尺寸
- 无需注册，保护用户隐私
- 全浏览器兼容，操作简单直观

## 在线体验

官方网站：[https://picsizer.luhui.net](https://picsizer.luhui.net)

## 部署指南

### 1. 一键部署

#### Netlify 部署

1. 点击下方按钮一键部署到 Netlify：

   [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/kugeceo/picsizer.luhui.net)

2. 按照提示完成授权和配置
3. 部署完成后，Netlify 会自动分配一个域名，您也可以绑定自定义域名

#### Vercel 部署

1. 点击下方按钮一键部署到 Vercel：

   [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/kugeceo/picsizer.luhui.net)

2. 按照提示完成授权和配置
3. 部署完成后，Vercel 会自动分配一个域名，您也可以绑定自定义域名

#### GitHub Pages 部署

1. Fork 本仓库到您的 GitHub 账号
2. 进入仓库设置（Settings）
3. 找到 "Pages" 选项
4. 在 "Source" 部分，选择分支（通常为 main 或 master）和根目录（/）
5. 点击 "Save" 保存设置
6. 等待几分钟，您的网站将部署在 `https://<您的用户名>.github.io/picsizer.luhui.net`

#### Cloudflare Pages 部署

1. 登录 Cloudflare 账号，进入 Pages 服务
2. 点击 "Create a project"
3. 选择 "Connect to Git"，授权访问您的 GitHub 账号
4. 选择 `picsizer.luhui.net` 仓库
5. 配置构建设置：
   - 框架预设：None
   - 构建命令：无需填写
   - 构建输出目录：/
6. 点击 "Deploy site" 开始部署
7. 部署完成后，可以绑定自定义域名

### 2. 其他服务器部署

#### 前提条件

- 已安装 Node.js (v14+) 和 npm
- 或任何可托管静态文件的 Web 服务器（如 Nginx, Apache 等）

#### 方法一：使用 Node.js 本地运行

1. 克隆仓库：
   ```bash
   git clone https://github.com/kugeceo/picsizer.luhui.net.git
   cd picsizer.luhui.net
   ```

2. 安装依赖：
   ```bash
   npm install
   ```

3. 本地运行：
   ```bash
   npm run dev
   ```

4. 打开浏览器访问 `http://localhost:3000`（端口可能因配置而异）

#### 方法二：静态文件部署

1. 构建项目（如果需要）：
   ```bash
   npm run build
   ```

2. 将生成的静态文件（通常在 `dist` 或项目根目录）上传到您的 Web 服务器
3. 配置 Web 服务器指向该目录
   - Nginx 示例配置：
     ```nginx
     server {
         listen 80;
         server_name picsizer.yourdomain.com;
         root /path/to/picsizer.luhui.net;
         index index.html;

         location / {
             try_files $uri $uri/ /index.html;
         }
     }
     ```

## 技术栈

- HTML5 / CSS3
- JavaScript
- 图片处理相关库
- 响应式设计

## 隐私说明

图尺匠（PicSizer）重视用户隐私，所有图片处理均在浏览器本地完成，不会上传到服务器，确保您的图片安全。

## 许可证

本项目采用 MIT 许可证开源，详情请查看 [LICENSE](LICENSE) 文件。


## 捐助打赏作者

手机如何扫码：

![打赏作者](http://flash.luhui.net/images/zhifu.png)

① 保存上面二维码图片　② 打开微信、支付宝、手机qq、“扫一扫”　③ 点击右下脚图标　④ 选择刚才保存的图片

感谢每一位捐赠者，我一直在坚持不懈地努力和创新，不断精心打磨产品，并坚持完全免费，我走过的每一步、开发的每一个功能，离不开那些默默支持我的热心用户，
大家的每一份捐赠和建议，都是我做的更好、走的更远最大的支持和动力！感谢大家，感谢有你，与你相遇好幸运！

您的捐赠将会用于：

①  支付服务器、域名费用，有时候百分之九十的问题是没钱烧了。
②  软件测试更新，分享更丰富的源码数据、工具，推荐更友好的用户界面设计。
③  撰写发布更多文章，保证作者的官网一直免费为大家提供服务。


## 联系方式

如有任何问题或建议，请联系：[info@mail.luhui.net](mailto:info@mail.luhui.net)



