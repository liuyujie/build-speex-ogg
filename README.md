# iOS音频开源库编译脚本

现有 **speex**     **ogg**   **lame**  **Opus** 等开源库 iOS 编译脚本；


### Opus [官网](http://www.opus-codec.org/)

Opus是一款开源、免费、自由度高的有损音频编解码器，融合了Skype的SILK和XVID的CELT 技术，拥有比AAC、OGG等其它有损格式更大的压缩率。它已经被标准化互联网组织IETF认证通过，是AAC后新一代的编码格式，目前处在开放阶段就已经获得foobar、Skype、Firefox等的大力支持和推广，并且为HTML5标准加入了一股重要力量。扩展名是". opus"。

### Ogg

Ogg 全称是 OGGVobis(oggVorbis) 是一种音频压缩格式，类似于MP3等的音乐格式。Ogg是完全免费、开放和没有专利限制的。OggVorbis文件的扩展名是".ogg"。Ogg文件格式可以不断地进行大小和音质的改良，而不影响旧有的编码器或播放器。

### speex

Speex 工程着力于通过提供一个可以替代高性能语音编解码来降低语音应用输入门槛 。另外，相对于其它编解码器，Speex也很适合网络应用，在网络应用上有着自己独特的优势。同时，Speex还是GNU工程的一部分，在改版的BSD协议中得到了很好的支持。


## 编译 **speex** 和 **ogg** 的 `shell` 脚本

可以编译成 iOS 和 OS X 两个平台

[speex](https://www.xiph.org/downloads/) 和 [ogg](https://www.xiph.org/downloads/) 的下载地址：https://www.xiph.org/downloads/


## 注意点
speex 是依赖于 ogg; 请编译 speex 之前先下载好 ogg。


## 编译

需要本地安装 `Xcode` 和 `command line tool`。

执行如下脚本：

```sh
./build_libogg.sh

./build_speex.sh

```

### 相关资源连接
[音视频开发概念篇 https://www.jianshu.com/p/4ec2081798a2](https://www.jianshu.com/p/4ec2081798a2)

[https://github.com/ElfSundae/build-speex-ogg](https://github.com/ElfSundae/build-speex-ogg)

[ogg官网: http://www.xiph.org/ogg/](http://www.xiph.org/ogg/)

[speex官网: http://www.speex.org/](http://www.speex.org/)

[https://github.com/chrisballinger/Opus-iOS](https://github.com/chrisballinger/Opus-iOS)

[https://www.jianshu.com/p/be8d40b61171](https://www.jianshu.com/p/be8d40b61171)