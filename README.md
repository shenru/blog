# blog
博客hexo
-------------------------------------------------------------------
git:
git  clone  https://github.com/shenru/blog.git
git add *
git commit -m "备注"
git push  





hexo: 
hexo new "postName"      #新建文章
hexo new page "about"    #创建about目录，并在about目录下生成index.md .在hexo\source\手工新建about和index.md也是完全等价的
hexo generate            #生成静态页面至public目录
hexo server              #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy               #将.deploy目录部署到GitHub
常用复合命令：
hexo deploy -g
hexo server -g
简写：
hexo n == hexo new
hexo g == hexo generate
hexo s == hexo server
hexo d == hexo deploy










----------------------------------------------------------------------
hexo: https://hexo.io/zh-cn/
主题: https://www.haomwei.com/technology/maupassant-hexo.html
hexo 帮助: http://ibruce.info/2013/11/22/hexo-your-blog/
