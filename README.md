# getPicture
从相册中获取图片，针对android4.4 不同版本的适配。通过startActivityForResult启动活动在onActivityResult回调中显示图片
Build.VERSION.SDK_INT判断系统版本，如果是4.4以上的版本需要对uri进行解析
