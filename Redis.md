#### Redis

​	工作中解决大文件断点续传、秒传的功能，要使用到Redis数据库，主要是后端存储工具是FastDFS，截至2020年11月20日09点23分，没有找到较合理的FastDFS异步存储文件的解决方案。大文件上传的后端代码是网上抄下来了，就是我Repositories里面的[renew-upload](https://github.com/SennerMing/renew-upload)，该项目的登录功能在校验与上传功能都使用上了，目的主要应该是为了解决多用户并发上传冲突。

