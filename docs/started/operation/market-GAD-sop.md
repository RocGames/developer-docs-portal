# 投放SOP三（GAD部分） #
    工作说明：
    	投放的操作标准步骤和要求以统一的格式描述出来，用来指导和规范日常工作，投放SOP的最佳效果是随便一个运营投放参照文档做，减少减少出错率

####1. GAD上线前准备####

| 子类              | 工作内容                                                     | 对应部门  | 完成时间点 | 状态  | 负责人 | 主投确认 | 验收人 （负责同学填入） | 验收时间 （负责同学填入） | 备注                                                         |
| ----------------- | :----------------------------------------------------------- | --------- | ---------- | ----- | ------ | -------- | ----------------------- | ------------------------- | ------------------------------------------------------------ |
| 开设账号          | [广告账号须于开广告                    前三周或更早即送出                     账号申请，分产品、                         地区、投放目的(事预                                                                                                                                                                     、上线)分别开广告账         号。 账号申请步骤如                     右： 以上开设完成后，在"UA-标准模版>> 广                 告帐号使用状况"填入                         申请完后同步google                     官方 | 投放      | 上线前3周  | FALSE |        |          |                         |                           | 由于白名单是一周一次，事预发布又要1-3天才抓得到。 需要更提早准备好  [账号申请步骤] 1. 事预UAC账号/GAD账号(联播网 关键字)/OB用的账号 2. 检测应用程序广告是否抓得到包 3. 建立广告(不用开跑) 申请UAC事预白名单 4. 其他白名单申请 (OB用的账号 UAC可以使用bumper)  针对上述第三点补充： GP发布后 GAD广告后台同步会有时间差 统一更新商店所有APP到广告后台的时间是每周1~2的00：00，其余时间为部分更新 也就是APP上去后最好是抓一周的时间 白名单申请后又要一周 (一周一次) 如加上创建时间，按照这情况最好三周前GAD广告就要开始准备 商店页发布后 48小时后在广告后台仍无看到，可向google提供商店页截图以及包名，进行手动申请统计表如下     https://docs.google.com/spreadsheets/d/1c868lF68NZsPSWFZVwAgryJRXwMEojx9f8wpzv8wT50/edit#gid=0 |
| 转换设置          | 工具>转换>纳入第三方转换，value设置为0。                     | 投放      | 上线前1周  | FALSE |        |          |                         |                           |                                                              |
| 文案云端记录      | 1. 根据不同主题设计文案，并且同步云端 "UA-标准模版>>广告文案" 2. 提交本地化送审，检查文案与素材 | 投放      | 上线前1周  | Done  |        |          |                         | 1月15日                   |                                                              |
| google广告建立    | 完成广告建立并审核，若超过24小时未通过，则通知人工审核。 广告命名方式如右： | 投放      | 上线前1天  | FALSE |        |          |                         |                           | GAD广告命名逻辑(建议)  [格式] 游戏代称_产品_地区_广告类型_广告方式_优化师_建立日期 UAC_PRE/NOR = UAC 1.0/2.0 UAC AEO = UAC 2.5 UAC VO = UAC 3.0 (FIREBASE 才有） Youtube = YT  YT_Form （此为买量广告-名单型） YT_Branding （此为曝光广告） 例如  DM_UAC_TW_UAC_PRE_lica_1015 DM_UAC_HK_UAC_1.0_lica_1015 DM_YT_HK_UAC_YT_lica_1015  [事件类别] 新手/付费/创角 ..其他 注: 1.0 即是安装，不用另外加注   转换(事件)命名方式 事件名称_平台_游戏名(账号别)_AF/ADJ/Firebase  In-app purchase_AND_MD_Firebase ecommerce_purchase_AND_MD_Firebase begin_checkout_AND_MD_Firebase add_to_wishlist_AND_MD_Firebase First open_AND_MD_Firebase  In-app purchase_AND_MD_af ecommerce_purchase_AND_MD_af begin_checkout_AND_MD_af add_to_wishlist_AND_MD_af First open_AND_MD_af |
| GAD游戏上线检查表 | GAD游戏上线检查表，包含短秒数白名单申请等，各项项目填写，并通知google窗口，参阅备注连结。 | 投放      | 上线前1周  | Done  |        |          |                         | 11月中                    | https://docs.google.com/spreadsheets/d/1c868lF68NZsPSWFZVwAgryJRXwMEojx9f8wpzv8wT50/edit#gid=0 |
| ADJ串接设定       | 产品商店生效后，于GAD后台生成连结ID， [工具]→[已连结账户]→[第三方应用程序分析]→[+]→[第三方分析]→[+]→[设定相关信息]→[建立连结ID]，再将连结ID复制到AppsFlyer上设定。双端确认开启。 | 投放      | 上线前1周  | Done  |        |          |                         | 11月中                    |                                                              |
| firebase设定      | 与技术确认是否有firebase设定。在google firebase检查串接。 ua共享一个账号，该账号需拥有mcc管理员＋firebase管理员权限，才可在ga汇入事件 | 投放/技术 | 上线前1周  | Doing |        |          |                         |                           | Firebase授权流程 1.Firebase、GAME项目授权给mcc的mail(ua统一一个） 2.GAD账户存取权加入该mail>收mail>接受邀请 3.GAD>已连结的账户>google firebase[详情]>连结所属的game 4.GAD转换>[+]>应用程序(purchase纳入转换，改成[否]。转换命名。)>firebase |
| 素材制作时程      | 与美术确定素材制作进度，确认有无短秒数影片                   | 美术      | 上线前1周  | FALSE |        |          |                         |                           | 短秒数影片使用时机                                           |
| 代操offer         | 1.给予代投相关产品信息：新闻稿,applink, APK,粉丝团 2.投放内容会议：广告架构, KPI, 素材方向与数量产出 3. offer信件确认：开启前与小路/sansa确认完毕。模版见"UA-标准模版>>代投信件模版" | 投放      | 上线前3天  | FALSE |        |          |                         |                           |                                                              |
| 运营确认信件      | 广告开启前，CB/OB都需给运营发「广告设定」内容信件，模版请见"UA-标准模版>>公版-与运营确认广告开启内容" | 投放/运营 | 上线前3天  | FALSE |        |          |                         |                           |                                                              |

####2. 投放期间####

| 子类         | 工作内容                                                     | 对应部门 | 完成时间点 | 状态  | 负责人 | 主投确认 | 验收人 （负责同学填入） | 验收时间 （负责同学填入） | 备注 |
| ------------ | ------------------------------------------------------------ | -------- | ---------- | ----- | ------ | -------- | ----------------------- | ------------------------- | ---- |
| 出价建议表   | 对出价事件进行试算 试算方式： 事件成本出价（install/ 购买事件成本等) 换算方式UA统一逻辑 | 投放     | 投放一周后 | FALSE |        |          |                         |                           |      |
| 次月投放确认 | 于25号确定下月是否投放。                                     | 投放     | 每月25号   | Done  |        |          |                         |                           |      |



####3. 结算####

| 子类       | 工作内容                 | 对应部门 | 完成时间点 | 状态 | 负责人 | 主投确认 | 验收人 （负责同学填入） | 验收时间 （负责同学填入） | 备注 |
| ---------- | ------------------------ | -------- | ---------- | ---- | ------ | -------- | ----------------------- | ------------------------- | ---- |
| 结算       | 于次月10日前完成结算。   | 投放     | 次月10号   | Done |        |          |                         |                           |      |
| 总计表确认 | 核实总计表数据填写确认。 | 投放     | 次月10号   | Done |        |          |                         |                           |      |
| 数据回填   | 次月10日前完成回流回填。 | 投放     | 次月10号   | Done |        |          |                         |                           |      |


