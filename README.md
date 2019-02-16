# photoTool
照片工具
/**
 保存图片到 以当前App名称命名的自定义相册中
 @param image 要保存的图片
 */
+(void)saveImageIntoCustomAlbumWithImage:(UIImage *)image;
/**
 保存图片到 相机胶卷
 @param image 要保存的图片
 */
+(void)saveImageIntoAlbumWithImage:(UIImage *)image;
