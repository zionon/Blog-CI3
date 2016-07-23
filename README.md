# Blog-CI3

PHP初学者，用CodeIgniter3开发的小型blog系统。基本实现了文章的发布，评论的管理，会员的注册，登录，根据权限显示功能。

前台方面基本都是AJAX。AJAX获取文章，发表评论，获取评论，发表回复。后台是传统的获取文章，评论，回复之类的。

下载后先创建数据库blog_ci，然后载入blog_ci_2016-07-11.sql文件。然后修改配置文件/application/config/database.php连接数据库的的信息以及config.php上的基础配置。

感谢[yii2]()，感谢[CodeIgniter3]()