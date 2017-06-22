#bbs

###文件存放位置
1. 静态文件 ---js，image放在 upload/static/;
2. 样式文件 ---公用css 放在  upload/data/cache/;
3. 公共部分 ---头部尾部 放在 upload/template/default/common/;


###样式
1. id="um" 头部信息-头像、设置之类的 路经 upload/data/cache/style_1_common.css 目前设为display:none;
2. id="ft" foot部分 路经 upload/data/cache/style_1_common.css  目前设为diaplay:none;
3. id="category_lk"  官方论坛  路径：upload/data/emplate/1_diy_forum_discuz.tpl.php  line:440-454;


###文件更改记录
1. upload/data/emplate/1_diy_forum_discuz.tpl.php //隐藏了官方论坛那一列
2. upload/data/cache/style_1_common.css   /*公共样式*/
3. upload/static/image  /*图片修改，可以整个目录传*/
4. upload/template/default /*头部尾部一些页面dom修改*/

