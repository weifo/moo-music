## react hooks+redux仿网易云音乐

对移动端更加友好

打开方式:
1. 将项目 clone 下来
```shell
$ git clone https://github.com/sanyuan0704/cloud-music.git
$ cd cloud-music
$ npm install

// 下载子模块
$ git submodule update --init --recursive
$ cd NeteaseCloudMusicApi
$ npm install 
$ cd ../  (注意: 一定要返回到上一层)
```

2. 运行
```shell
$ npm run start
```

现在就在本地的3002端口访问了。如果要打包到线上，执行`npm run build`即可。

### 项目预览
- 首页

![home](https://weifo-blog.oss-cn-shanghai.aliyuncs.com/music/home.JPG?Expires=1575734152&OSSAccessKeyId=TMP.hjbRdy1m5yjzKKtqFQyPcp5BCX34JiBxzqrTBJ9bgKH8xTRF2hDD1KxU7Ejrb6A8Ehk8e1F31Kej3VPU9gKMLx8B1FkxkZE4d9o9FZYGDrL8uHbTkXxZuPVHoN3t9x.tmp&Signature=4y4BjhvAQtrtPioaMnSRKTE%2FHMU%3D)

- 歌手页面

![singer](https://weifo-blog.oss-cn-shanghai.aliyuncs.com/music/singer.JPG?Expires=1575734320&OSSAccessKeyId=TMP.hjbRdy1m5yjzKKtqFQyPcp5BCX34JiBxzqrTBJ9bgKH8xTRF2hDD1KxU7Ejrb6A8Ehk8e1F31Kej3VPU9gKMLx8B1FkxkZE4d9o9FZYGDrL8uHbTkXxZuPVHoN3t9x.tmp&Signature=KXJqtdPmiXMuqGt96kMzVeQYYLA%3D)

- 播放页面

![playing](https://weifo-blog.oss-cn-shanghai.aliyuncs.com/music/play.JPG?Expires=1575734299&OSSAccessKeyId=TMP.hjbRdy1m5yjzKKtqFQyPcp5BCX34JiBxzqrTBJ9bgKH8xTRF2hDD1KxU7Ejrb6A8Ehk8e1F31Kej3VPU9gKMLx8B1FkxkZE4d9o9FZYGDrL8uHbTkXxZuPVHoN3t9x.tmp&Signature=IViblWSEuSds3jMs324pawIQGz8%3D)

- 歌单详情

![](https://weifo-blog.oss-cn-shanghai.aliyuncs.com/music/gedan.JPG?Expires=1575735979&OSSAccessKeyId=TMP.hjbRdy1m5yjzKKtqFQyPcp5BCX34JiBxzqrTBJ9bgKH8xTRF2hDD1KxU7Ejrb6A8Ehk8e1F31Kej3VPU9gKMLx8B1FkxkZE4d9o9FZYGDrL8uHbTkXxZuPVHoN3t9x.tmp&Signature=o4g3RA6Z4DpbTL6A292DS2d8pD8%3D)






