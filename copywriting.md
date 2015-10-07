# 文案排版规范

统一中文文案、排版的相关用法，降低团队成员之间的沟通成本，增强网站气质。

## 题外话

- 打字时，中英混排时，中文和英文之间应该空一格，这一格，就是逼格。——[@朱萧木](http://www.weibo.com/1842158375/AEWZGogNT)

- 如果真正在意 typography，那么汉字与西文之间应该插入一个半角空格。Adobe In Design、Microsoft Word 等对中文与西文混合排版支持较好的软件，都默认增大汉字和西文的间距。——[中英文混排时中文与英文之间是否要有空格？](http://www.zhihu.com/question/19587406/answer/12298128)

- 漢學家稱這個空白字元為「盤古之白」，因為它劈開了全形字和半形字之間的混沌，增加了文字的 readability。另有研究顯示，打字的時候不喜歡在中文和英文之間加空格的人，感情路都走得很辛苦，有七成的比例會在 34 歲的時候跟自己不愛的人結婚，而其餘三成的人最後只能把遺產留給自己的貓。畢竟愛情跟書寫都需要適時地留白。——[為什麼你們就是不能加個空格呢？](https://github.com/vinta/paranoid-auto-spacing)

## 空格

「有研究显示，打字的时候不喜欢在中文和英文之间加空格的人，感情路都走得很辛苦，有七成的比例会在34 岁的时候跟自己不爱的人结婚，而其余三成的人最后只能把遗产留给自己的猫。毕竟爱情跟书写都需要适时地留白。」

### 中英文之间需要增加空格

正确：

> 在 LeanCloud 上，数据储存是围绕 `AVObject` 进行的。

错误：

> 在LeanCloud上，数据储存是围绕`AVObject`进行的。

> 在 LeanCloud上，数据储存是围绕`AVObject` 进行的。

完整的正确用法：

> 在 LeanCloud 上，数据存储是围绕 `AVObject` 进行的。每个 `AVObject` 都包含了与 JSON 兼容的 key-value 对应的数据。数据是 schema-free 的，你不需要在每个 `AVObject` 上提前指定存在哪些键，只要直接设定对应的 key-value 即可。

例外：「豆瓣FM」等产品名词，按照官方所定义的格式书写。

### 中文与数字之间需要增加空格

正确：

> 今天出去买菜花了 5000 元。

错误：

> 今天出去买菜花了 5000元。

> 今天出去买菜花了5000元。

### 数字与单位之间需要增加空格

正确：

> 我家的宽带有 1 Gbps，硬盘一共有 10 TB。

错误：

> 我家的宽带有 1Gbps，硬盘一共有 10TB。

### 全角标点与其他字符之间不加空格

正确：

> 刚刚买了一部 iPhone，好开心！

错误：

> 刚刚买了一部 iPhone ，好开心！

## 标点符号

### 全角和半角

注意：标点符号分为「全角标点符号」和「半角标点符号」，不明白什么是全角与半角符号？请查看维基百科词条「[全角和半角](http://zh.wikipedia.org/wiki/%E5%85%A8%E8%A7%92%E5%92%8C%E5%8D%8A%E8%A7%92)」。

#### 中文或中英文混排时使用全角中文标点

正确：

> 嗨！你知道嘛？今天前台的小妹跟我说「喵」了哎！

> 核磁共振成像（NMRI）是什么原理都不知道？JFGI！

错误：

> 嗨! 你知道嘛? 今天前台的小妹跟我说 "喵" 了哎!

> 嗨!你知道嘛?今天前台的小妹跟我说"喵"了哎!

> 核磁共振成像 (NMRI) 是什么原理都不知道? JFGI!

> 核磁共振成像(NMRI)是什么原理都不知道?JFGI!

#### 完整的英文整句、特殊名词，其内容使用半角标点

正确：

> 乔帮主那句话是怎么说的？「Stay hungry, stay foolish.」。

> 推荐你阅读『Hackers & Painters: Big Ideas from the Computer Age』，非常的有趣。

错误：

> 乔帮主那句话是怎么说的？「Stay hungry，stay foolish。」。

> 推荐你阅读『Hackers＆Painters：Big Ideas from the Computer Age』，非常的有趣。

#### 全角标点与其他字符之间不加空格

正确：

> 刚刚买了一部 iPhone，好开心！

错误：

> 刚刚买了一部 iPhone ，好开心！

#### 半角标点后加空格

正确：

> Stay hungry, stay foolish.

错误：

> Stay hungry,stay foolish.> 

#### 字母和数字使用半角字符

正确：

> 这件 NIKE 的上衣只卖 1000 元。

错误：

> 这件 ＮＩＫＥ　的上衣只卖 １０００ 元。

例外：在设计稿、宣传海报中如出现极少量字母或数字的情形时，为方便文字对齐，是可以使用全形数字的。

### 不重复使用标点符号

正确：

> 德国队竟然战胜了巴西队！

> 她竟然对你说「喵」？！

错误：

> 德国队竟然战胜了巴西队！！

> 德国队竟然战胜了巴西队！！！！！！！！

> 她竟然对你说「喵」？？！！

> 她竟然对你说「喵」？！？！？？！！

### 无序列表和有序列表的标点符号

#### 无序列表

无序列表的每个条目相互为独立并列的关系，因此，在每个条目结束时，应该用句号。

正确：

> - 一流的酒店。
> - 一流的航班。
> - 一流的行程。

错误：

> - 一流的酒店；
> - 一流的航班，
> - 一流的行程。

#### 有序列表

有序列表的每个条目之间相互为上下文关系，因此，在每个条目结束时，应该用分号，在列表最后一行结束时才用句号。

正确：

> 1. 这是第一条；
> 2. 这是第二条；
> 3. 这是第最后一条。

错误：

> 1. 这是第一条，
> 2. 这是第二条。
> 3. 这是第三条；

## 段落

- 段落的开头不需要留出空白字符。
- 如果是纯文本，段落之间使用一个空行隔开。

## 大小写

大小写相关用法原属于英文书写范畴，不属于本 wiki 讨论内容，在这里只对部分易错用法进行简述。

### 专有名词使用正确的大小写

正确：

> 使用 GitHub 登录

> 我们的客户有 GitHub、Foursquare、Microsoft Corporation、Google、Facebook, Inc.。

> 苹果在第三季度发布了最新的 iPhone 产品，命名为 iPhone 6 和 iPhone 6 Plus，暂时没有发布新的 iPad 和新的 MacBook。

错误：

> 使用 github 登录

> 使用 GITHUB 登录

> 使用 Github 登录

> 我们的客户有 github、foursquare、microsoft corporation、google、facebook, inc.。

> 我们的客户有 GITHUB、FOURSQUARE、MICROSOFT CORPORATION、GOOGLE、FACEBOOK, INC.。

> 我们的客户有 Github、FourSquare、MicroSoft Corporation、Google、FaceBook, Inc.。

> 苹果在第三季度发布了最新的 iphone 产品，命名为 iphone 6 和 iphone 6 plus，暂时没有发布新的 ipad 和新的 macbook。

> 苹果在第三季度发布了最新的 IPHONE 产品，命名为 IPHONE 6 和 IPHONE 6 PLUS，暂时没有发布新的 IPAD 和新的 MACBOOK。

> 苹果在第三季度发布了最新的 Iphone 产品，命名为 Iphone 6 和 Iphone 6 plus，暂时没有发布新的 Ipad 和新的 Macbook。


## 争议

注意：以下用法略带有个人色彩，既：无论是否遵循下述规则，从语法的角度来讲都是**正确**的。但无论采用哪种，从团队统一规范及文案气质的角度考虑，都应该**保持一致**。

### 中文链接之间增加空格

用法：

> 请 [提交一个 issue](#) 并分配给相关同事。

> 访问我们网站的最新动态，请 [点击这里](#) 进行订阅！

對比用法：

> 请[提交一个 issue](#) 并分配给相关同事。

> 访问我们网站的最新动态，请[点击这里](#)进行订阅！

### 简体中文使用直角引号

简体中文使用「」和『』作为引号，其中「」为外层引号，『』为内层引号。

用法：

> 「老师，『有条不紊』的『紊』是什么意思？」

对比用法：

> “老师，‘有条不紊’的‘紊’是什么意思？”

## 谁在这样做？

网站 | 文案 | UGC
--- | --- | ---
[Apple 中国](http://www.apple.com/cn/) | Yes | N/A
[Apple 香港](http://www.apple.com/hk/) | Yes | N/A
[Apple 台湾](http://www.apple.com/tw/) | Yes | N/A
[Microsoft 中国](http://www.microsoft.com/zh-cn/) | Yes | N/A
[Microsoft 香港](http://www.microsoft.com/zh-hk/) | Yes | N/A
[Microsoft 台湾](http://www.microsoft.com/zh-tw/) | Yes | N/A
[LeanCloud](http://leancloud.cn/) | Yes | N/A
[知乎](http://www.zhihu.com/) | Yes | 部分用户达成
[爱范儿](www.ifanr.com/) | Yes | N/A
[V2EX](http://www.v2ex.com/) | Yes | 标题达成
[SegmentFault](http://segmentfault.com/) | Yes | 部分用户达成
[Apple4us](http://apple4us.com/) | Yes | N/A
[豌豆荚](http://www.wandoujia.com/) | Yes | N/A
[Ruby China](http://ruby-china.org/) | Yes | 标题达成
[PHPHub](http://phphub.org/) | Yes | 标题达成

## 参考文献

- [来自 About.com 的大小写用法（英文）](http://grammar.about.com/od/punctuationandmechanics/a/Guidelines-For-Using-Capital-Letters.htm)
- [来自维基百科的关于大小写字符的相关条目（英文）](http://en.wikipedia.org/wiki/Letter_case)
- [來自 Oxford Dictionaries 的标点用法（英文）](http://www.oxforddictionaries.com/us/words/punctuation)
- [來自普渡大学的标点符号用法（英文）](https://owl.english.purdue.edu/owl/section/1/6/)
- [來自 wikiHow 的英文标点符号用法 wiki（英文）](http://www.wikihow.com/Use-English-Punctuation-Correctly)
- [格式－openSUSE](https://zh.opensuse.org/index.php?title=Help:%E6%A0%BC%E5%BC%8F)
- [全角和半角 - 维基百科](http://zh.wikipedia.org/wiki/%E5%85%A8%E8%A7%92%E5%92%8C%E5%8D%8A%E8%A7%92)
- [引号 - 维基百科](http://zh.wikipedia.org/wiki/%E5%BC%95%E5%8F%B7)
- [疑问惊叹号 - 維基百科](http://zh.wikipedia.org/wiki/%E7%96%91%E9%97%AE%E6%83%8A%E5%8F%B9%E5%8F%B7)
