https://blog.csdn.net/javaniceyou/article/details/107714732?utm_medium=distribute.pc_relevant_bbs_down.none-task-blog-baidujs-2.nonecase&depth_1-utm_source=distribute.pc_relevant_bbs_down.none-task-blog-baidujs-2.nonecase
下载 bundletool

如果您还没有下载 bundletool，请从 GitHub https://github.com/google/bundletool/releases 代码库下载
。
 bundletool build-apks --bundle=/MyApp/my_app.aab --output=/MyApp/my_app.apks
    --ks=/MyApp/keystore.jks
    --ks-pass=file:/MyApp/keystore.pwd
    --ks-key-alias=MyKeyAlias
    --key-pass=file:/MyApp/key.pwd
    

命令行构建 app bundle 并使用 jarsigner 为其签名。
https://developer.android.google.cn/studio/build/building-cmdline#build_bundle