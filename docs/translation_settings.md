趣卡翻译的文本翻译服务内置了3个公有翻译器和6个私有翻译器，共用于三个任务：PDF文档翻译、WPS(docx、pptx、excel<xlsx>)文档翻译和快捷翻译，你可以根据自己的喜好自由选择。

## 翻译器说明
* 内置翻译器可能会因网络问题出现波动导致翻译异常。如果使用**内置翻译器**异常请更换相关线路或尝试更换其他公有翻译器。
* 趣卡翻译中的**除Deepl以外的其他内置翻译器无限制免费使用**。**其他的私有翻译器(火山、腾讯、彩云、小牛、Deepl、百度等)在超出每月免费额度的情况下**，可能需要向火山、腾讯、彩云、小牛、百度和Deepl服务商支付一定费用。
* 私有翻译器需要点击**「点此申请」**教程后，将申请的相关密钥填入翻译器设置的页面里（所有私有密钥仅在本地加密保存，仅限您本人使用），**所有私有翻译器提供的每月免费字符数基本上用不完**。
* 相关私有翻译器可以设置每月流量预警（类似手机里的联网控制），当`使用量`要超过`允许量`的时候，该翻译服务即停止，可一定程度在**超出免费额度之前**停止该私有翻译器的使用，避免欠费。**流量预警**需要每月1号在您使用之前将相关私有翻译器`使用量`进行**手动清零**，目前还无法自动清零。

如果以上翻译器都无法满足您的需求，您可通过`配置中心`底部的`问题反馈`按钮联系开发者**免费自定义其他翻译器**。

| 服务 | 免费额度 | 超出免费额度 | 翻译速度 | 说明 |
| :-- | :-- | :-- | :-- | :-- |
| 内置通用 | 不限 | 0元  | 3-5s/页 | 共有很多个 |
| 内置谷歌 | 不限 | 0元  | 1.5s/页 | 所有用户均可 |
| 内置快速 | 不限 | 0元  | 3-5s/页 | 所有用户均可 |
| 私有火山| 每月200万字符 | 49元/100万字符 | 1s/页 | 翻译结果精准，[点此申请](service/translate/huoshan.md) |
| 私有腾讯| 每月500万字符 | 58元/100万字符 | 1.5s/页 | 翻译结果精准，[点此申请](service/translate/tencent.md) |
| 私有彩云 | 每月100万字符 | 20元/100万字符 | 2s/页 | 翻译结果准确，[点此申请](service/translate/caiyun.md) |
| 私有小牛 | 每日20万字符 | 50元/100万字符 | 2-3s/页  | 翻译结果准确，[点此申请](service/translate/niu.md) |
| 私有Deepl | 每月50万字符 | 20美元/100万字符 | 2-4s/页  |翻译结果精准，[点此申请](service/translate/deepl.md) |
| 私有百度（高级版） | （`8月1后`）每月100万字符 | 49元/100万字符 | 2s/页  | 翻译结果准确，[点此申请](service/translate/baidu.md) |
|  更多教程 | 待发布 | ...... | ......  | ...... |
## 语言设置
为了最大限度的支持任意一种语言，趣卡翻译尽可能放开了当前所有文本翻译器允许的语言。

* 由于每个翻译器支持的语言种类不同，因此在设置PDF翻译、WPS翻译和快捷翻译`源语`和`目标语`的时候需要参考选择的翻译器对应的`语言简称`。
* `源语`表示文本翻译前的所属语言，可设置为自动识别`auto`。
* `目标语`表示要翻译的目标语言，每个翻译器同一语言的`目标语`简称可能不同，在更改翻译器的同时也需要根据翻译器对应的目标语言简称修改`目标语`。

**这里`源语`和`目标语`都需填写所选应翻译器允许的`语言简称`。**

## 设置语料库

语料库的作用：纠正专业词汇翻译不准确问题，你让专业名词翻译成什么它就翻译成什么。语料库可能在公有翻译器下效果并不理想，配合私有翻译器小牛或者腾讯效果是最佳的。

语料库包含`查询`、`新增`、`删除`和`加载`功能。

* 执行`查询`**XXX**将会加载本地的名为**XXX**的语料库，如果该名称不 u存在将会提示创建。
* 执行`新增`**X**行，将会自动创建**X**行空白记录，用于用户填写和增加。
* 执行`加载`远程**key_id**，将会加载远程的语料库到本地名为**XXX**的语料库中，会自动去重，远程语料库的创建教程可参考[如下链接](https://xuexi.qukaa.com/publish/1.html)。
<div align='center'><img  style="width:300px;" src="https://zanzhu.malizheng.com/manual/docs/oss/gif/jiazai_corpus.gif" /></div> 
* `删除`可以多选或者全选行数，鼠标右键执行删除操作，将会从**XXX**语料库删除对应的选中词汇。

## 通用设置
如果你选择了通用的公有翻译器作为文本翻译器：

* 需要设置该翻译器对应的PDF翻译、WPS翻译和快捷翻译`源语`和`目标语`。

当前通用公有翻译器允许的`源语`和`目标语`语言简称和语言全称如下，共计11种语言。

| 语言全称 | 语言简称 |
| :-- | :-- |
|自动语言|auto|
|中文简体|zh|
|英语|en|
|日语|ja|
|韩语|ko|
|葡萄牙语|pt|
|西班牙语|es|
|德语|de|
|俄语|ru|
|法语|fr|
|意大利语|it|
|阿拉伯语|ar|

## 海外设置
如果你选择了海外的公有翻译器作为文本翻译器：
* 该公有翻译器适用于出国的用户使用，国内目前无法使用。
* 需要设置该翻译器对应的PDF翻译、WPS翻译和快捷翻译`源语`和`目标语`。

当前海外的公有翻译器允许的`源语`和`目标语`语言简称和语言全称如下，共计22种语言。

| 语言全称 | 语言简称 |
| :-- | :-- | 
|自动语言|auto|
|中文简体|zh|
|中文(繁体)|zh-TW|
|英语|en|
|日语|ja|
|韩语|ko|
|葡萄牙语|pt|
|土耳其语|tr|
|西班牙语|es|
|德语|de|
|俄语|ru|
|法语|fr|
|泰语|th|
|意大利语|it|
|越南语|vi|
|菲律宾语|tl|
|印地语|hi|
|印尼语|id|
|蒙古语|mn|
|马来西亚语|ms|
|孟加拉语|bn|
|缅甸语|my|
|阿拉伯语|ar|

* 需要设置该翻译器对应的PDF翻译、WPS翻译和快捷翻译`源语`和`目标语`。

当前极速公有翻译器允许的`源语`和`目标语`语言简称和语言全称如下，共计96种语言。

## 其他或自定义设置
如果你选择了其他或自定义公有翻译器作为文本翻译器：

* 需要设置该翻译器对应的PDF翻译、WPS翻译和快捷翻译`源语`和`目标语`。

当前其他或自定义公有翻译器允许的`源语`和`目标语`语言简称和语言全称如下，共计9种语言。

| 语言全称 | 语言简称 |
| :-- | :-- | 
|自动识别|auto|
|中文|zh|
|英语|en|
|日语|ja|
|意大利语|it|
|西班牙语|es|
|德语|de|
|法语|fr|
|葡萄牙语|pt|
|俄语|ru|

## 百度设置
如果你选择了百度私有翻译器作为文本翻译器：

* 需要设置该翻译器对应的PDF翻译、WPS翻译和快捷翻译`源语`和`目标语`。
* 需要设置百度私有翻译器对应的相关密钥。

> **为了尽可能保证语言简称和先前翻译器的一致性，百度翻译器的`源语`和`目标语`部分简称这里做了修改，可能与官方文档有所区别，请以下面表格为准。**

<table><thead><tr><th>语言全称</th><th>语言简称</th><th>语言全称</th><th>语言简称</th><th>语言全称</th><th>语言简称</th></tr></thead><tbody><tr><td>自动检测</td><td>auto</td><td>简体中文</td><td>zh</td><td>英语</td><td>en</td></tr><tr><td>粤语</td><td>yue</td><td>文言文</td><td>wyw</td><td>日语</td><td>ja</td></tr><tr><td>韩语</td><td>ko</td><td>法语</td><td>fr</td><td>西班牙语</td><td>es</td></tr><tr><td>泰语</td><td>th</td><td>阿拉伯语</td><td>ara</td><td>俄语</td><td>ru</td></tr><tr><td>葡萄牙语</td><td>pt</td><td>德语</td><td>de</td><td>意大利语</td><td>it</td></tr><tr><td>希腊语</td><td>el</td><td>荷兰语</td><td>nl</td><td>波兰语</td><td>pl</td></tr><tr><td>保加利亚语</td><td>bul</td><td>爱沙尼亚语</td><td>est</td><td>丹麦语</td><td>dan</td></tr><tr><td>芬兰语</td><td>fin</td><td>捷克语</td><td>cs</td><td>罗马尼亚语</td><td>rom</td></tr><tr><td>斯洛文尼亚语</td><td>slo</td><td>瑞典语</td><td>swe</td><td>匈牙利语</td><td>hu</td></tr><tr><td>繁体中文</td><td>zh-TW</td><td>越南语</td><td>vi</td><td>&nbsp;</td><td>&nbsp;</td></tr></tbody></table>

## 腾讯设置
如果你选择了腾讯私有翻译器作为文本翻译器：

* 需要设置该翻译器对应的PDF翻译、WPS翻译和快捷翻译`源语`和`目标语`。
* 需要设置腾讯私有翻译器对应的相关密钥。

当前腾讯私有翻译器允许的`源语`和`目标语`语言简称和语言全称如下，共计18种语言。

| 语言全称 | 语言简称 |
| :-- | :-- | 
|自动语言|auto|
|中文简体|zh|
|中文(繁体)|zh-TW|
|英语|en|
|日语|ja|
|韩语|ko|
|葡萄牙语|pt|
|土耳其语|tr|
|西班牙语|es|
|德语|de|
|俄语|ru|
|法语|fr|
|泰语|th|
|意大利语|it|
|越南语|vi|
|印地语|hi|
|印尼语|id|
|马来西亚语|ms|
|阿拉伯语|ar|

各源语言的目标语言支持列表如下：

* zh（简体中文）：en（英语）、ja（日语）、ko（韩语）、fr（法语）、es（西班牙语）、it（意大利语）、de（德语）、tr（土耳其语）、ru（俄语）、pt（葡萄牙语）、vi（越南语）、id（印尼语）、th（泰语）、ms（马来语）
* zh-TW（繁体中文）：en（英语）、ja（日语）、ko（韩语）、fr（法语）、es（西班牙语）、it（意大利语）、de（德语）、tr（土耳其语）、ru（俄语）、pt（葡萄牙语）、vi（越南语）、id（印尼语）、th（泰语）、ms（马来语）
* en（英语）：zh（中文）、ja（日语）、ko（韩语）、fr（法语）、es（西班牙语）、it（意大利语）、de（德语）、tr（土耳其语）、ru（俄语）、pt（葡萄牙语）、vi（越南语）、id（印尼语）、th（泰语）、ms（马来语）、ar（阿拉伯语）、hi（印地语）
* ja（日语）：zh（中文）、en（英语）、ko（韩语）
* ko（韩语）：zh（中文）、en（英语）、ja（日语）
* fr（法语）：zh（中文）、en（英语）、es（西班牙语）、it（意大利语）、de（德语）、tr（土耳其语）、ru（俄语）、pt（葡萄牙语）
* es（西班牙语）：zh（中文）、en（英语）、fr（法语）、it（意大利语）、de（德语）、tr（土耳其语）、ru（俄语）、pt（葡萄牙语）
* it（意大利语）：zh（中文）、en（英语）、fr（法语）、es（西班牙语）、de（德语）、tr（土耳其语）、ru（俄语）、pt（葡萄牙语）
* de（德语）：zh（中文）、en（英语）、fr（法语）、es（西班牙语）、it（意大利语）、tr（土耳其语）、ru（俄语）、pt（葡萄牙语）
* tr（土耳其语）：zh（中文）、en（英语）、fr（法语）、es（西班牙语）、it（意大利语）、de（德语）、ru（俄语）、pt（葡萄牙语）
* ru（俄语）：zh（中文）、en（英语）、fr（法语）、es（西班牙语）、it（意大利语）、de（德语）、tr（土耳其语）、pt（葡萄牙语）
* pt（葡萄牙语）：zh（中文）、en（英语）、fr（法语）、es（西班牙语）、it（意大利语）、de（德语）、tr（土耳其语）、ru（俄语）
* vi（越南语）：zh（中文）、en（英语）
* id（印尼语）：zh（中文）、en（英语）
* th（泰语）：zh（中文）、en（英语）
* ms（马来语）：zh（中文）、en（英语）
* ar（阿拉伯语）：en（英语）
* hi（印地语）：en（英语）

## 彩云设置
如果你选择了彩云私有翻译器作为文本翻译器：

* 需要设置该翻译器对应的PDF翻译、WPS翻译和快捷翻译`源语`和`目标语`。
* 需要设置彩云私有翻译器对应的令牌，第二个令牌为官方测试令牌，若第一个令牌为空，将会使用官方测试令牌。

当前彩云私有翻译器允许的`源语`和`目标语`语言简称和语言全称如下，共计3种语言。

| 语言全称 | 语言简称 |
| :-- | :-- | 
|自动语言|auto|
|中文简体|zh|
|英语|en|
|日语|ja|

具体允许的翻译走向如下：
<table><thead><tr><th>From-to</th><th>中文 zh</th><th>英语 en</th><th>日文 ja</th></tr></thead><tbody><tr><td>中文 zh</td><td>-</td><td>zh2en</td><td>zh2ja</td></tr><tr><td>英语 en</td><td>en2zh</td><td>-</td><td>-</td></tr><tr><td>日文 ja</td><td>ja2zh</td><td>-</td><td>-</td></tr></tbody></table>

## 小牛设置
如果你选择了彩云私有翻译器作为文本翻译器：

* 需要设置该翻译器对应的PDF翻译、WPS翻译和快捷翻译`源语`和`目标语`。
* 小牛的`术语词典子库`会和自带的`语料库`发生冲突，只能二选一，如果你填写了小牛的术语词典子库，将会去取消自带的术语语料库。

当前小牛私有翻译器允许的`源语`和`目标语`语言简称和语言全称如下，共计302种语言。

<table><thead><tr><th>中文全称</th> <th>英文全称</th> <th>语言简称</th></tr></thead> <tbody><tr><td>自动识别</td> <td>auto</td> <td> auto</td></tr><tr><td>阿多拉语</td> <td>Adhola</td> <td>adh</td></tr><tr><td>阿尔巴尼亚语</td> <td>Albanian</td> <td>sq</td></tr><tr><td>阿格尼桑维语</td> <td>Agni Sanvi</td> <td>any</td></tr><tr><td>阿瓜鲁纳语</td> <td>Aguaruna</td> <td>agr</td></tr><tr style=""><td>阿卡特克语</td> <td>Acateco</td> <td>knj</td></tr><tr style=""><td>阿卡瓦伊语</td> <td>Akawaio</td> <td>ake</td></tr><tr style=""><td>阿拉伯语</td> <td>Arabic</td> <td>ar</td></tr><tr style=""><td>阿姆哈拉语</td> <td>Amharic</td> <td>am</td></tr><tr style=""><td>阿穆斯戈语</td> <td>Amuzgo</td> <td>amu</td></tr><tr style=""><td>阿奇语</td> <td>Achi</td> <td>acr</td></tr><tr style=""><td>阿丘雅语</td> <td>Achuar</td> <td>acu</td></tr><tr style=""><td>阿塞拜疆语</td> <td>Azerbaijani</td> <td>az</td></tr><tr style=""><td>阿舍宁卡语</td> <td>Ashéninka</td> <td>cpb</td></tr><tr style=""><td>阿雅安伊富高语</td> <td>Ayangan Ifugao</td> <td>ifb</td></tr><tr style=""><td>埃维语</td> <td>Ewe</td> <td>ee</td></tr><tr style=""><td>艾马拉语</td> <td>Aymara</td> <td>aym</td></tr><tr style=""><td>爱尔兰语</td> <td>Irish</td> <td>ga</td></tr><tr style=""><td>爱沙尼亚语</td> <td>Estonian</td> <td>et</td></tr><tr style=""><td>安拜语</td> <td>Ambai</td> <td>amk</td></tr><tr style=""><td>安蒂波洛伊富高语</td> <td>Antipolo Ifugao</td> <td>ify</td></tr><tr style=""><td>奥吉布瓦语</td> <td>Ojibwa</td> <td>ojb</td></tr><tr style=""><td>奥利亚语</td> <td>Oriya</td> <td>or</td></tr><tr style=""><td>奥罗科语</td> <td>Oroko</td> <td>bdu</td></tr><tr style=""><td>奥罗莫语</td> <td>Oromoo</td> <td>om</td></tr><tr style=""><td>奥赛梯语</td> <td>Ossetic</td> <td>os</td></tr><tr style=""><td>巴布亚皮钦语</td> <td>Tok Pisin</td> <td>tpi</td></tr><tr style=""><td>巴卡语</td> <td>Baka</td> <td>bdh</td></tr><tr style=""><td>巴拉萨纳语</td> <td>Barasana</td> <td>bsn</td></tr><tr style=""><td>巴里巴语</td> <td>Bariba</td> <td>bba</td></tr><tr style=""><td>巴里亚语</td> <td>Bariai</td> <td>bch</td></tr><tr style=""><td>巴里语</td> <td>Bari</td> <td>bfa</td></tr><tr style=""><td>巴什基尔语</td> <td>Bashkir</td> <td>ba</td></tr><tr style=""><td>巴斯克语</td> <td>Basque</td> <td>eu</td></tr><tr style=""><td>白俄罗斯语</td> <td>Belarusian</td> <td>be</td></tr><tr style=""><td>白苗文</td> <td>Hmong</td> <td>mww</td></tr><tr style=""><td>柏柏尔语</td> <td>Berber</td> <td>ber</td></tr><tr style=""><td>班巴拉语</td> <td>Bambara</td> <td>bam</td></tr><tr style=""><td>班迪亚勒语</td> <td>Bandial</td> <td>bqj</td></tr><tr style=""><td>班通安隆语</td> <td>Bantoanon</td> <td>bno</td></tr><tr style=""><td>邦邦语</td> <td>Bambam</td> <td>ptu</td></tr><tr style=""><td>保加利亚语</td> <td>Bulgarian</td> <td>bg</td></tr><tr style=""><td>北部格雷博语</td> <td>Northern Grebo</td> <td>gbo</td></tr><tr style=""><td>北部马姆语</td> <td>Northern Mam</td> <td>map</td></tr><tr style=""><td>比斯拉马语</td> <td>Bislama</td> <td>bi</td></tr><tr style=""><td>别姆巴语</td> <td>Bemba</td> <td>bem</td></tr><tr style=""><td>冰岛语</td> <td>Icelandic</td> <td>is</td></tr><tr style=""><td>波孔奇语</td> <td>Poqomchi’</td> <td>poh</td></tr><tr style=""><td>波拉语</td> <td>Bola</td> <td>bnp</td></tr><tr style=""><td>波兰语</td> <td>Polish</td> <td>pl</td></tr><tr style=""><td>波斯尼亚语</td> <td>Bosnian</td> <td>bs</td></tr><tr style=""><td>波斯语</td> <td>Persian</td> <td>fa</td></tr><tr style=""><td>波塔瓦托米语</td> <td>Potawatomi</td> <td>pot</td></tr><tr style=""><td>博科巴鲁语</td> <td>Bokobaru</td> <td>bus</td></tr><tr style=""><td>布阿尔考钦语</td> <td>Bualkhaw Chin</td> <td>cbl</td></tr><tr style=""><td>布列塔尼语</td> <td>Brezhoneg</td> <td>br</td></tr><tr style=""><td>布萨语</td> <td>Busa</td> <td>bqp</td></tr><tr style=""><td>藏语</td> <td>Tibetan</td> <td>ti</td></tr><tr style=""><td>查克玛语</td> <td>Chakma</td> <td>ccp</td></tr><tr style=""><td>查莫罗语</td> <td>Chamorro</td> <td>cha</td></tr><tr style=""><td>车臣语</td> <td>Chechen</td> <td>che</td></tr><tr style=""><td>楚瓦什语</td> <td>Chuvash</td> <td>cv</td></tr><tr style=""><td>茨鲁语</td> <td>Chiru</td> <td>cdf</td></tr><tr style=""><td>茨瓦纳语</td> <td>Tswana</td> <td>tn</td></tr><tr style=""><td>聪加语</td> <td>Xitsonga</td> <td>ts</td></tr><tr style=""><td>达迪比语</td> <td>Dadibi</td> <td>mps</td></tr><tr style=""><td>鞑靼语</td> <td>Tatar</td> <td>tt</td></tr><tr style=""><td>丹麦语</td> <td>Danish</td> <td>da</td></tr><tr style=""><td>德顿语</td> <td>Tetun</td> <td>tet</td></tr><tr style=""><td>德语</td> <td>German</td> <td>de</td></tr><tr style=""><td>迪塔马利语</td> <td>Ditammari</td> <td>tbz</td></tr><tr style=""><td>迪维希语</td> <td>Divehi</td> <td>dv</td></tr><tr style=""><td>迪尤拉语</td> <td>Dyula</td> <td>dyu</td></tr><tr style=""><td>蒂穆贡-穆鲁特语</td> <td>Timugon Murut</td> <td>tih</td></tr><tr style=""><td>丁卡语</td> <td>Dinka</td> <td>dik</td></tr><tr style=""><td>东部卡加延-阿格塔语</td> <td>Eastern Cagayan Agta</td> <td>duo</td></tr><tr style=""><td>俄语</td> <td>Russian</td> <td>ru</td></tr><tr style=""><td>恩都卡语</td> <td>Ndyuka</td> <td>djk</td></tr><tr style=""><td>恩舍特语</td> <td>Enxet</td> <td>enx</td></tr><tr style=""><td>法拉法拉语</td> <td>Frafra</td> <td>gur</td></tr><tr style=""><td>法兰钦语</td> <td>Falam Chin</td> <td>cfm</td></tr><tr style=""><td>法罗语</td> <td>Faroese</td> <td>fo</td></tr><tr style=""><td>法语</td> <td>French</td> <td>fr</td></tr><tr style=""><td>菲律宾语</td> <td>Filipino</td> <td>fil</td></tr><tr style=""><td>斐济语</td> <td>Fijian</td> <td>fj</td></tr><tr style=""><td>芬兰语</td> <td>Finnish</td> <td>fi</td></tr><tr style=""><td>弗里西语</td> <td>Frisian</td> <td>fy</td></tr><tr style=""><td>盖丘亚语</td> <td>Quichua</td> <td>quw</td></tr><tr style=""><td>刚果语</td> <td>Kikongo</td> <td>kg</td></tr><tr style=""><td>高棉语</td> <td>Khmer</td> <td>km</td></tr><tr style=""><td>格巴亚语</td> <td>Gbaya</td> <td>krs</td></tr><tr style=""><td>格鲁吉亚语</td> <td>Georgian</td> <td>jy</td></tr><tr style=""><td>格森语</td> <td>Kasem</td> <td>xsm</td></tr><tr style=""><td>古吉拉特语</td> <td>Gujarati</td> <td>gu</td></tr><tr style=""><td>瓜哈哈拉语</td> <td>Guajajára</td> <td>gub</td></tr><tr style=""><td>果发语</td> <td>Goffa</td> <td>gof</td></tr><tr style=""><td>哈卡钦语</td> <td>Hakha Chin</td> <td>cnh</td></tr><tr style=""><td>哈萨克语</td> <td>Kazakh</td> <td>ka</td></tr><tr style=""><td>哈萨克语（西里尔）</td> <td>Kazakh(Cyrillic)</td> <td>kk</td></tr><tr style=""><td>海地克里奥尔语</td> <td>Haitian Creole</td> <td>ht</td></tr><tr style=""><td>亥比语</td> <td>Halbi</td> <td>hlb</td></tr><tr style=""><td>韩语</td> <td>Korean</td> <td>ko</td></tr><tr style=""><td>豪萨语</td> <td>Hausa</td> <td>ha</td></tr><tr style=""><td>荷兰语</td> <td>Dutch</td> <td>nl</td></tr><tr style=""><td>黑山语</td> <td>Montenegrin</td> <td>me</td></tr><tr style=""><td>胡里语</td> <td>Huli</td> <td>hui</td></tr><tr style=""><td>基里巴斯语</td> <td>Kiribati</td> <td>gil</td></tr><tr style=""><td>基切语</td> <td>Kiche</td> <td>quc</td></tr><tr style=""><td>吉尔吉斯语</td> <td>Kyrgyz</td> <td>ky</td></tr><tr style=""><td>加莱拉语</td> <td>Galela</td> <td>gbi</td></tr><tr style=""><td>加利西亚语</td> <td>Galician</td> <td>gl</td></tr><tr style=""><td>加泰罗尼亚语</td> <td>Catalan</td> <td>ca</td></tr><tr style=""><td>捷克语</td> <td>Czech</td> <td>cs</td></tr><tr style=""><td>景颇语</td> <td>Jingpho</td> <td>kac</td></tr><tr style=""><td>喀克其奎语</td> <td>Kaqchikel</td> <td>cki</td></tr><tr style=""><td>卡拜尔语</td> <td>Kabyle</td> <td>kab</td></tr><tr style=""><td>卡尔梅克卫拉特语</td> <td>Kalmyk-Oirat</td> <td>xal</td></tr><tr style=""><td>卡克奇克尔语</td> <td>Cakchiquel</td> <td>cak</td></tr><tr style=""><td>卡库瓦语</td> <td>Kakwa</td> <td>keo</td></tr><tr style=""><td>卡纳达语</td> <td>Kannada</td> <td>kn</td></tr><tr style=""><td>卡纳尔高地-基丘亚语</td> <td>Cañar Highland Quichua</td> <td>qxr</td></tr><tr style=""><td>卡平阿马朗伊语</td> <td>Kapingamarangi</td> <td>kpg</td></tr><tr style=""><td>卡韦卡尔语</td> <td>Cabecar</td> <td>cjp</td></tr><tr style=""><td>卡乌龙语</td> <td>Kaulong</td> <td>pss</td></tr><tr style=""><td>凯克其语</td> <td>Qeqchi</td> <td>kek</td></tr><tr style=""><td>坎帕语</td> <td>Campa</td> <td>cni</td></tr><tr style=""><td>科普特语</td> <td>Coptic</td> <td>cop</td></tr><tr style=""><td>科奇语</td> <td>Camsa</td> <td>kbh</td></tr><tr style=""><td>科西嘉语</td> <td>Corsican</td> <td>co</td></tr><tr style=""><td>克雷塔罗奥托米语</td> <td>Queretaro Otomi</td> <td>otq</td></tr><tr style=""><td>克里米亚鞑靼语</td> <td>Crimean Tatar</td> <td>crh</td></tr><tr style=""><td>克利科语</td> <td>Keliko</td> <td>kbo</td></tr><tr style=""><td>克罗地亚语</td> <td>Croatian</td> <td>hr</td></tr><tr style=""><td>库阿努阿语</td> <td>Kuanua</td> <td>ksd</td></tr><tr style=""><td>库尔德语（库尔曼奇语）</td> <td>Kurdish(Kurmanji)</td> <td>ku</td></tr><tr style=""><td>库尔德语（索拉尼语）</td> <td>Kurdish(Sorani)</td> <td>ckb</td></tr><tr style=""><td>库隆语</td> <td>Kulung</td> <td>kle</td></tr><tr style=""><td>库斯科克丘亚语</td> <td>Cusco Quechua</td> <td>quz</td></tr><tr style=""><td>拉丁语</td> <td>Latin</td> <td>la</td></tr><tr style=""><td>拉脱维亚语</td> <td>Latvian</td> <td>lv</td></tr><tr style=""><td>老挝语</td> <td>Lao</td> <td>lo</td></tr><tr style=""><td>勒期语</td> <td>Lacid</td> <td>lsi</td></tr><tr style=""><td>立陶宛语</td> <td>Lithuanian</td> <td>lt</td></tr><tr style=""><td>林加拉语</td> <td>Lingala</td> <td>ln</td></tr><tr style=""><td>临高语</td> <td>Lingao</td> <td>ond</td></tr><tr style=""><td>隆迪语</td> <td>Kirundi</td> <td>rn</td></tr><tr style=""><td>隆韦语</td> <td>Lomwe</td> <td>ngl</td></tr><tr style=""><td>卢干达语</td> <td>Luganda</td> <td>lg</td></tr><tr style=""><td>卢克帕语</td> <td>Lukpa</td> <td>dop</td></tr><tr style=""><td>卢森堡语</td> <td>Luxembourgish</td> <td>lb</td></tr><tr style=""><td>卢旺达语</td> <td>Kinyarwanda</td> <td>rw</td></tr><tr style=""><td>罗马尼亚语</td> <td>Romanian</td> <td>ro</td></tr><tr style=""><td>罗姆语</td> <td>Romani</td> <td>rmn</td></tr><tr style=""><td>罗维那语</td> <td>Roviana</td> <td>rug</td></tr><tr style=""><td>马都拉语</td> <td>Madurese</td> <td>mad</td></tr><tr style=""><td>马恩岛语</td> <td>Manx</td> <td>gv</td></tr><tr style=""><td>马尔加什语</td> <td>Malagasy</td> <td>mg</td></tr><tr style=""><td>马耳他语</td> <td>Maltese</td> <td>mt</td></tr><tr style=""><td>马拉地语</td> <td>Marathi</td> <td>mr</td></tr><tr style=""><td>马拉瑙语</td> <td>Maranao</td> <td>mrw</td></tr><tr style=""><td>马拉雅拉姆语</td> <td>Malayalam</td> <td>ml</td></tr><tr style=""><td>马来语</td> <td>Malay</td> <td>ms</td></tr><tr style=""><td>马勒语</td> <td>Maale</td> <td>mdy</td></tr><tr style=""><td>马里语</td> <td>Mari</td> <td>mhr</td></tr><tr style=""><td>马姆语</td> <td>Mam</td> <td>mam</td></tr><tr style=""><td>马其顿语</td> <td>Macedonian</td> <td>mk</td></tr><tr style=""><td>马绍尔语</td> <td>Marshallese</td> <td>mah</td></tr><tr style=""><td>曼尼普尔语</td> <td>Manipuri</td> <td>mni</td></tr><tr style=""><td>毛利语</td> <td>Maori</td> <td>mi</td></tr><tr style=""><td>蒙古语</td> <td>Mongolian</td> <td>mo</td></tr><tr style=""><td>蒙古语（西里尔）</td> <td>Mongolian(Cyrillic)</td> <td>mn</td></tr><tr style=""><td>孟加拉语</td> <td>Bengali</td> <td>bn</td></tr><tr style=""><td>缅甸语</td> <td>Burmese</td> <td>my</td></tr><tr style=""><td>摩图语</td> <td>Motu</td> <td>meu</td></tr><tr style=""><td>莫西语</td> <td>Mossi</td> <td>mos</td></tr><tr style=""><td>穆图凡语</td> <td>Muthuvan</td> <td>muv</td></tr><tr style=""><td>纳特尼语</td> <td>Nateni</td> <td>ntm</td></tr><tr style=""><td>纳瓦特尔语</td> <td>Nahuatl</td> <td>nhg</td></tr><tr style=""><td>南阿塞拜疆语</td> <td>South Azerbaijani</td> <td>azb</td></tr><tr style=""><td>南玻利维亚克丘亚语</td> <td>South Bolivian Quechua</td> <td>quh</td></tr><tr style=""><td>南非荷兰语</td> <td>Afrikaans</td> <td>af</td></tr><tr style=""><td>南非科萨语</td> <td>Xhosa</td> <td>xh</td></tr><tr style=""><td>南非祖鲁语</td> <td>Zulu</td> <td>zu</td></tr><tr style=""><td>尼泊尔语</td> <td>Nepali</td> <td>ne</td></tr><tr style=""><td>尼日利亚富拉语</td> <td>Nigerian Fulfulde</td> <td>fuv</td></tr><tr style=""><td>尼亚库萨语</td> <td>Nyakyusa</td> <td>nyy</td></tr><tr style=""><td>弄巴湾语</td> <td>Lun Bawang</td> <td>lnd</td></tr><tr style=""><td>努曼干语</td> <td>Numanggang</td> <td>nop</td></tr><tr style=""><td>挪威语</td> <td>Norwegian</td> <td>no</td></tr><tr style=""><td>帕皮阿门托语</td> <td>Papiamento</td> <td>pap</td></tr><tr style=""><td>派特语</td> <td>Paite</td> <td>pck</td></tr><tr style=""><td>旁遮普语</td> <td>Punjabi</td> <td>pa</td></tr><tr style=""><td>佩勒-阿塔语</td> <td>Pele-Ata</td> <td>ata</td></tr><tr style=""><td>葡萄牙语</td> <td>Portuguese</td> <td>pt</td></tr><tr style=""><td>普什图语</td> <td>Pashto</td> <td>ps</td></tr><tr style=""><td>齐马内语</td> <td>Tsimané</td> <td>cas</td></tr><tr style=""><td>齐切瓦语</td> <td>Chewa</td> <td>ny</td></tr><tr style=""><td>契维语</td> <td>Twi</td> <td>tw</td></tr><tr style=""><td>切诺基语</td> <td>Cherokee</td> <td>chr</td></tr><tr style=""><td>日语</td> <td>Japanese</td> <td>ja</td></tr><tr style=""><td>瑞典语</td> <td>Swedish</td> <td>sv</td></tr><tr style=""><td>萨鲍特语</td> <td>Sabaot</td> <td>spy</td></tr><tr style=""><td>萨摩亚语</td> <td>Samoan</td> <td>sm</td></tr><tr style=""><td>塞尔维亚语</td> <td>Serbian</td> <td>sr</td></tr><tr style=""><td>塞舌尔克里奥尔语</td> <td>Seychelles Creole</td> <td>crs</td></tr><tr style=""><td>塞索托语</td> <td>Sesotho</td> <td>st</td></tr><tr style=""><td>桑贝里吉语</td> <td>Samberigi</td> <td>ssx</td></tr><tr style=""><td>桑戈语</td> <td>Sango</td> <td>sg</td></tr><tr style=""><td>僧伽罗语</td> <td>Sinhalese</td> <td>si</td></tr><tr style=""><td>山地马里语</td> <td>Hill Mari</td> <td>mrj</td></tr><tr style=""><td>圣马特奥德马尔-瓦维语</td> <td>San Mateo del Mar Huave</td> <td>huv</td></tr><tr style=""><td>世界语</td> <td>Esperanto</td> <td>eo</td></tr><tr style=""><td>舒阿尔语</td> <td>Shuar</td> <td>jiv</td></tr><tr style=""><td>斯哈语</td> <td>Kisiha</td> <td>jmc</td></tr><tr style=""><td>斯洛伐克语</td> <td>Slovak</td> <td>sk</td></tr><tr style=""><td>斯洛文尼亚语</td> <td>Slovenian</td> <td>sl</td></tr><tr style=""><td>斯瓦希里语</td> <td>Swahili</td> <td>sw</td></tr><tr style=""><td>苏奥语</td> <td>Suau</td> <td>swp</td></tr><tr style=""><td>苏格兰盖尔语</td> <td>Scottish Gaelic</td> <td>gd</td></tr><tr style=""><td>宿务语</td> <td>Cebuano</td> <td>ceb</td></tr><tr style=""><td>索马里语</td> <td>Somali</td> <td>so</td></tr><tr style=""><td>塔吉克语</td> <td>Tajik</td> <td>tg</td></tr><tr style=""><td>塔希提语</td> <td>Tahitian</td> <td>ty</td></tr><tr style=""><td>泰卢固语</td> <td>Telugu</td> <td>te</td></tr><tr style=""><td>泰米尔语</td> <td>Tamil</td> <td>ta</td></tr><tr style=""><td>泰语</td> <td>Thai</td> <td>th</td></tr><tr style=""><td>坦普尔马语</td> <td>Tampulma</td> <td>tpm</td></tr><tr style=""><td>汤加语</td> <td>Tongan</td> <td>to</td></tr><tr style=""><td>特丁钦语</td> <td>Tedim Chin</td> <td>ctd</td></tr><tr style=""><td>特索语</td> <td>Teso</td> <td>teo</td></tr><tr style=""><td>腾内特语</td> <td>Tennet</td> <td>tex</td></tr><tr style=""><td>提格雷语</td> <td>Tigre</td> <td>tig</td></tr><tr style=""><td>通加格语</td> <td>Tungag</td> <td>lcm</td></tr><tr style=""><td>图阿雷格语</td> <td>Tamajaq</td> <td>tmh</td></tr><tr style=""><td>图马伊鲁穆语</td> <td>Tuma-Irumu</td> <td>iou</td></tr><tr style=""><td>图瓦语</td> <td>Tuvan</td> <td>tyv</td></tr><tr style=""><td>土耳其语</td> <td>Turkish</td> <td>tr</td></tr><tr style=""><td>土库曼语</td> <td>Turkmen</td> <td>tk</td></tr><tr style=""><td>奇南特克语</td> <td>Chinantec</td> <td>chq</td></tr><tr style=""><td>瓦吉语</td> <td>Waskia</td> <td>wsk</td></tr><tr style=""><td>瓦拉莫语</td> <td>Wolaytta</td> <td>wal</td></tr><tr style=""><td>瓦里斯语</td> <td>Waris</td> <td>wrs</td></tr><tr style=""><td>瓦利语</td> <td>Wali</td> <td>wlx</td></tr><tr style=""><td>瓦瑞语</td> <td>Waray</td> <td>war</td></tr><tr style=""><td>佤语</td> <td>Wa</td> <td>prk</td></tr><tr style=""><td>威尔士语</td> <td>Welsh</td> <td>cy</td></tr><tr style=""><td>维吾尔语</td> <td>Uyghur</td> <td>uy</td></tr><tr style=""><td>文达语</td> <td>Venda</td> <td>ve</td></tr><tr style=""><td>文约语</td> <td>Vunjo</td> <td>vun</td></tr><tr style=""><td>沃洛夫语</td> <td>Wolof</td> <td>wol</td></tr><tr style=""><td>乌德穆尔特语</td> <td>Udmurt</td> <td>udm</td></tr><tr style=""><td>乌尔都语</td> <td>Urdu</td> <td>ur</td></tr><tr style=""><td>乌克兰语</td> <td>Ukrainian</td> <td>uk</td></tr><tr style=""><td>乌玛语</td> <td>Uma</td> <td>ppk</td></tr><tr style=""><td>乌斯潘坦语</td> <td>Uspanteco</td> <td>usp</td></tr><tr style=""><td>乌兹别克语</td> <td>Uzbek</td> <td>uz</td></tr><tr style=""><td>西班牙语</td> <td>Spanish</td> <td>es</td></tr><tr style=""><td>西布基农马诺布语</td> <td>Western Bukidnon Manobo</td> <td>mbb</td></tr><tr style=""><td>西部玻利维亚瓜拉尼语</td> <td>Western Bolivian Guarani</td> <td>gnw</td></tr><tr style=""><td>西部克耶语</td> <td>Western Kayah</td> <td>kyu</td></tr><tr style=""><td>西部拉威语</td> <td>Western Lawa</td> <td>lcp</td></tr><tr style=""><td>西罗伊语</td> <td>Siroi</td> <td>ssd</td></tr><tr style=""><td>西皮沃语</td> <td>Shipibo</td> <td>shp</td></tr><tr style=""><td>希伯来语</td> <td>Hebrew</td> <td>he</td></tr><tr style=""><td>希尔哈语</td> <td>Tachelhit</td> <td>shi</td></tr><tr style=""><td>希腊语</td> <td>Greek</td> <td>el</td></tr><tr style=""><td>希里莫图语</td> <td>Hiri Motu</td> <td>hmo</td></tr><tr style=""><td>锡达莫语</td> <td>Sidamo</td> <td>sid</td></tr><tr style=""><td>夏威夷克里奥尔英语</td> <td>Hawaiian Creole English</td> <td>hwc</td></tr><tr style=""><td>夏威夷语</td> <td>Hawaiian</td> <td>haw</td></tr><tr style=""><td>信德语</td> <td>Sindhi</td> <td>sd</td></tr><tr style=""><td>匈牙利语</td> <td>Hungarian</td> <td>hu</td></tr><tr style=""><td>修纳语</td> <td>Shona</td> <td>sn</td></tr><tr style=""><td>叙利亚语</td> <td>Syriac</td> <td>syc</td></tr><tr style=""><td>雅比姆语</td> <td>Yabem</td> <td>jae</td></tr><tr style=""><td>雅加达语</td> <td>Jakalteko</td> <td>jac</td></tr><tr style=""><td>亚美尼亚语</td> <td>Armenian</td> <td>hy</td></tr><tr style=""><td>亚齐语</td> <td>Aceh</td> <td>ace</td></tr><tr style=""><td>伊博语</td> <td>Igbo</td> <td>ig</td></tr><tr style=""><td>伊卡语</td> <td>Ika</td> <td>ikk</td></tr><tr style=""><td>伊普马语</td> <td>Yipma</td> <td>byr</td></tr><tr style=""><td>伊兹语</td> <td>Izi</td> <td>izz</td></tr><tr style=""><td>意大利语</td> <td>Italian</td> <td>it</td></tr><tr style=""><td>意第绪语</td> <td>Yiddish</td> <td>yi</td></tr><tr style=""><td>印地语</td> <td>Hindi</td> <td>hi</td></tr><tr style=""><td>印尼巽他语</td> <td>Sundanese</td> <td>su</td></tr><tr style=""><td>印尼语</td> <td>Indonesian</td> <td>id</td></tr><tr style=""><td>印尼爪哇语</td> <td>Javanese</td> <td>jv</td></tr><tr style=""><td>英语</td> <td>English</td> <td>en</td></tr><tr style=""><td>邕北壮语</td> <td>Yongbei Zhuang</td> <td>zyb</td></tr><tr style=""><td>永贡语</td> <td>Yongkom</td> <td>yon</td></tr><tr style=""><td>尤卡坦玛雅语</td> <td>Yucatec Maya</td> <td>yua</td></tr><tr style=""><td>约鲁巴语</td> <td>Yoruba</td> <td>yo</td></tr><tr style=""><td>约姆语</td> <td>Yom</td> <td>pil</td></tr><tr style=""><td>粤语</td> <td>Cantonese</td> <td>yue</td></tr><tr style=""><td>越南语</td> <td>Vietnamese</td> <td>vi</td></tr><tr style=""><td>哲尔马语</td> <td>Zarma</td> <td>dje</td></tr><tr style=""><td>中部杜顺语</td> <td>Central Dusun</td> <td>dtp</td></tr><tr style=""><td>中部伊富高语</td> <td>Central Ifugao</td> <td>ifa</td></tr><tr style=""><td>中文（繁体）</td> <td>Chinese (Traditional)</td> <td>cht</td></tr><tr style=""><td>中文（简体）</td> <td>Chinese (Simplified)</td> <td>zh</td></tr><tr style=""><td>宗喀语</td> <td>Dzongkha</td> <td>dz</td></tr><tr style=""><td>佐通钦语</td> <td>Zotung Chin</td> <td>czt</td></tr></tbody></table>


## Deepl设置

如果你选择了Deepl私有翻译器作为文本翻译器：

* 需要设置该翻译器对应的PDF翻译、WPS翻译和快捷翻译`源语`和`目标语`。
* 需要选择Deepl私有翻译器是免费试用版本还是收费版本。

当前Deepl私有翻译器允许的`源语`和`目标语`语言简称和语言全称如下，共计21种语言。

| 语言全称 | 语言简称 |
| :-- | :-- | 
|自动识别|auto|
|英语|en|
|中文|zh|
|爱沙尼亚语|et|
|保加利亚语|bg|
|波兰语|pl|
|丹麦语|da|
|德语|de|
|俄语|ru|
|法语|fr|
|芬兰语|fi|
|荷兰语|nl|
|捷克语|cs|
|拉脱维亚语|lv|
|立陶宛语|lt|
|罗马尼亚语|ro|
|葡萄牙语|pt|
|日语|ja|
|西班牙语|es|
|希腊语|el|
|匈牙利语|hu|
|意大利语|it|
