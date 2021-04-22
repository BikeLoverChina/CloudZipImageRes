# CloudZipImageRes
云端图片测试数据

> 说明:
>
> 1.main.bundle 压缩后的archivebundle.zip放到你自己的服务器上
>
> 2.json/info.json中的url:为压缩包地址, md5为本次压缩包的md5
>
> 3.archivebundle.zip的名称可以随便定义,eg: aa.zip bb.zip但info.json中的url一定要能下载到对应的zip包
>
> 4.res里的图片只是测试使用,你的图片资源可能放在不同的服务器,则传给sdk正确的图片路径即可
>
> Eg.https://raw.githubusercontent.com/BikeLoverChina/CloudZipImageRes/main/res/
>
> https://cloundimage.oss-cn-beijing.aliyuncs.com/res/
>
> https://cloundimage.oss-cn-beijing.aliyuncs.com/xx/
>
> 只需要保证这个路径+图片名称能访问到图片即可
>
> 5.搜索图片根据[UIScreen mainScreen].scale来决定加载2x图还是3x图,所以要保证图片必须有2x和3x
>
> 6.demo为在ipad上验证,如需使用请自行验证