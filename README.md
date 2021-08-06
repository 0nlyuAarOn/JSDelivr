# JSDelivr
JSDelivr
添加 DNS 服务器
DNS 服务器添加 8.8.8.8（不加也可以）。当我们添加 DNS 服务器时，可能会看到 DNS 配置里已经有了 114.114.114.114。有人可能会问这两个 DNS 有什么区别？

114.114.114.114：是国内移动、电信和联通通用的 DNS，手机和电脑端都可以使用，干净无广告，解析成功率相对来说更高，国内用户使用的比较多，而且速度相对快、稳定，是国内用户上网常用的 DNS。
8.8.8.8：是 GOOGLE 公司提供的 DNS，该地址是全球通用的，相对来说，更适合国外以及访问国外网站的用户使用。
刷新 DNS
Windows：ipconfig /flushdns
Mac：sudo dscacheutil -flushcache
免费 CDN 提速 Github 静态资源访问
JSDelivr 是一个免费开源的 CDN 解决方案，用于帮助开发者和站长。包含 JavaScript 库、jQuery 插件、CSS 框架、字体等等 Web 上常用的静态资源。我们来到其官网，可以看到它的介绍 Open Source CDN free, fast, and reliable。（免费、快速、可靠，不过据说可能会投毒广告，表示目前还没见过广告）

上篇文章 Four Ways to Deploy Hexo 中 提到过，用 Github Pages 部署 Hexo，用户体验一直不是很好。为了提高用户体验，不妨结合 JSDelivr 来搭建我的个人博客。下面我就来看看 JSDeliver + Github 如何是实现静态资源加速。
https://v-vincen.life/en/Github-%E5%8A%A0%E9%80%9F%E4%BC%98%E5%8C%96/#%E5%85%8D%E8%B4%B9-CDN-%E6%8F%90%E9%80%9F-Github-%E9%9D%99%E6%80%81%E8%B5%84%E6%BA%90%E8%AE%BF%E9%97%AE
