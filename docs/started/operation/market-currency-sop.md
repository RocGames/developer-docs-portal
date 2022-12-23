# 投放SOP一（主流程部分） #
    工作说明：
    	投放的操作标准步骤和要求以统一的格式描述出来，用来指导和规范日常工作，投放SOP的最佳效果是随便一个运营投放参照文档做，减少减少出错率

####1. APP上线前准备####

| 分类                            | 工作内容                                                     | 对应部门  | 完成时间点                  | 状态 | 负责人         | 主投确认 | 验收人 （负责同学填入） | 验收时间 （负责同学填入） | 备注 |
| ------------------------------- | ------------------------------------------------------------ | --------- | --------------------------- | ---- | -------------- | -------- | ----------------------- | ------------------------- | ---- |
| 预算及导量规划                  | 拟定预算版本和各媒体规划。                                                                                           1.尚无营运数据指标下，可先以游戏评级投做为导量模拟。（评级标准询问运营） A级：美金 B级：美金                                                                                                          2.后续仍须跟进运营端/策划端，目标取得营运对产品的营收预估、营运数据预估等，以便规划市场预算以及UA预算。                                                                                                      3.使用脑图作广告架构规划/预算/受众/素材规划，做出对应媒体计划方案及导量规划                                                                                              4.素材规划与**首席文化官**开会确认。确认内容：素材规划方向/未来预计的产出数量 | 投放      | 提案后一周完成              |      | **首席营销官** | 投放     |                         | 2022/5/31                 |      |
| ADJ 包名建立                    | ADJ管理员账号：数据同学操作建立ADJ包名                       | 投放      | SDK测试前一周               |      |                |          |                         | 2022/6/30                 |      |
| ADJ/ firebase权限索取           | UA共享账号，绑定GA ADMIN/ FIREBASE管理员。事件引入用该账号操作，不申请其他账号。 | 投放/项管 | SDK测试前一周               |      |                |          |                         | 2022/7/5                  |      |
| ADJ/firebase事件确认/SDK产出    | 1. 确认事件点位与名称。注意需要与第三方命名区分。如ADJ_login/ G_login                                                                                                                   2. sdk产出时间与权限在项管。需在运营SDK包入时接入。投放端需积极追踪包的进度。                                                                                                  3. 基本事件点位 sdk包内建事件： ◆ login ◆ complete_registration ◆ tutorial_completion ◆ purchase ◆ level_up | 投放/技术 | 通常在上线前三个月          |      |                |          |                         | 2022/6/24                 |      |
| 送包前：ADJ Event测试（双端）   | 1. 跟进运营端包的节点，预先提醒运营送包前做ADJ测试。提醒QA联系双端(and/ios)测试                                                                                              2. 明确：测试游戏，设备白名单，测试OS（安卓还是IOS或者双端）                                                                                         3. 储值务必每个档次都要测试(要提醒QA) 测试事件的正确性 *特别注意币别/币值                                                                                                      4. 群内与QA对接，给到excel事件表，核对事件时间，事件类型与金额                                                                                                                               5.确认无误后，请QA给到验收信件 | 投放/运营 | 正式出包前， 约OB前两周进行 |      |                |          |                         | 2022/8/2                  |      |
| 正式上线：ADJ Event测试（双端） | 1. 确认实际上线ADJ点位与事件是否正常回传                                                 2. 确认ADJ流水与运营数据相符                                                                                3. 「成本」=花费，嵌入主投账号（该主投账号需有操作广告账号权限才可全数拉入）                                                                                                    4. 渠道设定对接开启 | 投放      | 开广告前一天                |      |                |          |                         | 2022/8/12                 |      |

####2. 事前预约上线前准备####

| 分类                     | 工作内容                                                     | 对应部门  | 完成时间点     | 状态 | 负责人 | 主投确认 | 验收人 （负责同学填入） | 验收时间 （负责同学填入） | 备注 |
| ------------------------ | ------------------------------------------------------------ | --------- | -------------- | ---- | ------ | -------- | ----------------------- | ------------------------- | ---- |
| 商店预注册数据           | ios和Google play的商店预约数同步 预注册商店数据表：预约数据（运营填写）、投放数据（投放填写）、汇总以及分析 *注意运营端和广告端数据均分地区 | 投放/运营 | 预注册投放期间 |      |        |          |                         |                           |      |
| nft用户导量计划          | 结合产品针对gamefi活动节奏的导量计划以及素材                                   1.nft用户导量预算与计划结合nft活动                                                            2.素材参考以及素材制作 |           |                |      |        |          |                         |                           |      |
| 预算及导量规划           | 拟定事前预约的预算版本和各媒体规划。                                                        1.事前预约量级预估。尚无营运数据指标下，可先以游戏评级投做为导量模拟。（评级标准询问运营）           2.使用脑图作广告架构规划/预算/受众/素材规划，做出对应媒体计划方案及导量规划                                                                                                           3.素材规划与**首席文化官**开会确认。确认内容：素材规划方向/未来预计的产出数量 | 投放      | 开广告前一个月 |      |        |          |                         | 2022/7/16                 |      |
| 网页埋点(Facebook)       | 产出以下点位给到策划埋入事前预约网页                                                                1. 必埋点位：（标准事件）pageview, （标准事件）注册; （自定义事件）iOSdownload, （自定义事件）Androiddownload。                                                                                            2. （必做） （自定义事件）在『事件管理工具』，选择『自定义转化事件』，选择下拉事件， iOSdownload指定命名为iOSdownload，Androiddownload指定命名为Androiddownload。                                               3.测试：检查像素的CHROME插件 https://chrome.google.com/webstore/detail/facebook-pixel-helper/fdgfkebogiimcoedlicjlajpkdmockpc?hl=zh-TW                                                                                                                         4.(DOUBLE CHECK)查看『事件管理工具』面板是否有数据回传。 以上见右 | 投放      | 开广告前一个月 |      |        |          |                         | 2022/7/16                 |      |
| 网页埋点(Google)         | 产出以下点位给到策划埋入事前预约网页                                                                 1. 必埋点位：pageview, 注册; iOSdownload, Androiddownload。                           2. 测试：检查像素的CHROME插件 https://chrome.google.com/webstore/detail/tag-assistant-by-google/kejbdjndbnbjgmefkgdddjlbokphdefk?linkrate=1&hl=zh-TW                                                                                                    3. (DOUBLE CHECK)查看Google转换面板是否有事件述记录。 | 投放      | 开广告前一个月 |      |        |          |                         | 2022/7/16                 |      |
| 双商店后台查看预约量权限 | 向项管申请双商店预约数据查看权限，模版请见"公版-双商店预约后台权限申请" | 投放/项管 | 预约开启前     |      |        |          |                         |                           |      |
| 代投                     | 1. 代投账号绑定至BM，由管理员账号将ua同学的操作账号绑入该代投广告账户。                                                                                                                    2. 像素转至代投账户。                                                                                               3. offer信件发送，见模版"代投信件模版"。确认kpi等，与**首席营销官**同步。 | 投放      | 开广告前一个月 |      |        |          |                         |                           |      |





####3. 旧品重启####

| 分类                  | 工作内容                                                     | 对应部门  | 完成时间点          | 状态 | 负责人 | 主投确认 | 验收人 （负责同学填入） | 验收时间 （负责同学填入） | 备注 |
| --------------------- | ------------------------------------------------------------ | --------- | ------------------- | ---- | ------ | -------- | ----------------------- | ------------------------- | ---- |
| 五星评价检查          | 检查商店首页有负评或低于4.2分，**首席营销官**安排市场人员进场维护 *因GP商店有更新规则，评分会24~48小时更新一次，故五星维护需开启前72小时前执行。 | 市场/投放 | 开启前3天           |      |        |          |                         |                           |      |
| 旧产品投放确认        | 1.确认需重启投放的原因、营运数据。                                                                           2. 确认预算、金额、量级。                                                                                            3. 确认重启时间。                                                                                                    4. ADJ串接状况、ADJ事件确认(创角、付费)                                                                   5.素材确认 (确认数量、题材) | 投放      | 每月25号or重启前2周 |      |        |          |                         |                           |      |
| ADJ Event测试         | 旧游戏重启                                                                                                                可能因更新或热更导致事件异常，广告重启前一周需确认事件正常。 检查创角和付费事件。  需要的信息: (向QA确认) 请QA要提供测试设备加入白名单 原厂已完成的串接的事件检测 每个储值档次都需要测试  sdk包内建事件： ◆ login ◆ complete_registration ◆ tutorial_completion ◆ purchase ◆ level_up | 投放/QA   | 重启前1周           |      |        |          |                         |                           |      |
| 填写 在线广告账号表单 | 如有新增广告账号账户，则须更新表单（UA-标准模版-FB广告帐号使用状况/GOOGLE广告帐号) 由主投通知 **首席营销官**安排市场人员负责 | 投放      | 上线前3天           |      |        |          |                         |                           |      |





####4. 投放期间####

| 分类                            | 工作内容                                                     | 对应部门 | 完成时间点 | 状态 | 负责人 | 主投确认 | 验收人 （负责同学填入） | 验收时间 （负责同学填入） | 备注                                     |
| ------------------------------- | ------------------------------------------------------------ | -------- | ---------- | ---- | ------ | -------- | ----------------------- | ------------------------- | ---------------------------------------- |
| 次月投放确认                    | 每月第三周确定下月投放预算                                   | 投放     | 每月25号   |      |        |          |                         |                           |                                          |
| 正式上线：ADJ Event测试（双端） | 1. 确认实际上线ADJ点位与事件是否正常回传 2. 确认ADJ流水与运营数据相符 3. 渠道设定对接开启：FB/GOOGLE/LINE/Qoo/以及其他渠道。fb/google需打开「成本」，即是渠道花费，嵌入主投账号（该主投账号需有操作广告账号权限才可全数拉入） | 投放     | OB当天     |      |        |          |                         |                           | 如产品的第三方是套用adjsut时则需参考此项 |



####5. 代投 ####

| 分类      | 工作内容                                                     | 对应部门 | 完成时间点   | 状态 | 负责人 | 主投确认 | 验收人 （负责同学填入） | 验收时间 （负责同学填入） | 备注 |
| --------- | ------------------------------------------------------------ | -------- | ------------ | ---- | ------ | -------- | ----------------------- | ------------------------- | ---- |
| 代投offer | 1.给予代投相关产品信息：新闻稿,applink, APK,粉丝团                                         2.投放内容会议：广告架构, KPI, 素材方向与数量产出                                                              3. offer信件确认：开启前与 **首席营销官** 确认完毕。模版见"UA-标准模版>>代投信件模版" | 投放     | 开广告前一周 |      |        |          |                         |                           |      |



####6. 结案####

| 分类     | 工作内容                       | 对应部门 | 完成时间点   | 状态 | 负责人 | 主投确认 | 验收人 （负责同学填入） | 验收时间 （负责同学填入） | 备注 |
| -------- | ------------------------------ | -------- | ------------ | ---- | ------ | -------- | ----------------------- | ------------------------- | ---- |
| 上月结案 | 次月1日前整理给 **首席营销官** | 投放     | 次月首周三前 |      |        |          |                         |                           |      |
