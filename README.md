# unity_uluaProject
unity项目下引入ulua实现热更（android and ios）

pc上：打开该unity项目后，在pc上运行点击2个按钮会打印log的是由lua调用的

android和ios和自行测试

在实际开发中会把lua文件导出txt文件（BundleDownloadable文件中的一样），然后打成assetbundle资源包，然后放在StreamingAssets或者持久化缓存目录下，以便热更

在示例工程中，直接放到了Resources文件中。
