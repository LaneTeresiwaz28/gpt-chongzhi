# GPT代充与 ChatGPT Plus 国内充值指南（2026 年 10 月更新）

本文是一份写给中文用户的 ChatGPT 付费会员说明，内容包括：Plus、Pro 100 / 200 / 500 的官方美元价格和区别，国内为什么无法直接付款，"代充（订阅代付）"该怎么挑选，以及付款被拒、付款后仍显示免费版、续费失败、重复扣费等问题的排查方法。报错部分逐条对照 OpenAI 官方帮助中心整理，并附上官方链接。最后核对日期：2026-10-17（官方价格与报错说明），2026-10-24 补充付款前自查清单。本仓库为非官方整理，与 OpenAI 不存在隶属关系，文中出现的品牌名称仅用于说明。

**直接回答：** ChatGPT 官网只接受 OpenAI 支持地区发行的银行卡等付款方式，国内银行卡和支付宝都无法直接付款。没有海外银行卡的用户，比较常见的做法是"代充"（订阅代付）：由卖家代为付款，把正规订阅的 ChatGPT Plus / Pro 开通到你自己的账号上。

**怎么挑代充：** 重点看 6 件事：价格是否合理、是否索要密码、到账时间是否说得清楚、失败后怎么退、中途掉订阅管不管、售后能否找到人。具体判断方法见下文。

**官方价格：** Free $0、Go $8/月、Plus $20/月，Pro 分为 $100 / $200 / $500 三档，全部只能按月付款（2026-10-17 对照 OpenAI 官方定价页和帮助中心核对，详见下表）。

## 目录

- [使用前先读：关于地区](#使用前先读关于地区)
- [ChatGPT 官方价格表](#chatgpt-官方价格表2026-10-17-核对)
- [Plus 和 Pro 怎么选](#plus-和-pro-怎么选)
- [为什么国内开通 ChatGPT Plus 很难](#为什么国内开通-chatgpt-plus-很难)
- [几种开通方式对比](#几种开通方式对比)
- [挑选代充的 6 个判断点](#挑选代充的-6-个判断点)
- [付款前 1 分钟自查清单](#付款前-1-分钟自查清单)
- [报错 / 常见问题大全](#报错--常见问题大全)
- [降低被封风险的使用习惯](#降低被封风险的使用习惯)
- [常见问题](#常见问题)
- [国内开通参考](#国内开通参考)
- [参考资料](#参考资料)
- [English summary](#english-summary)
- [来源与许可](#来源与许可)

## 使用前先读：关于地区

OpenAI 官方公布了支持的国家和地区列表（[Supported countries and territories](https://platform.openai.com/docs/supported-countries)）。2026-10-17 查看时，中国大陆、香港、澳门均不在列表内（台湾在列表内）。该页面写明：在列表以外的地区访问服务或提供访问服务，账号可能被封禁或停用。本仓库只整理官方公布的价格、订阅规则和报错说明，不提供任何绕过地区限制或支付限制的方法；请在遵守 OpenAI 使用条款的前提下使用。

## ChatGPT 官方价格表（2026-10-17 核对）

| 档位 | 官方价（美元） | 说明 |
|---|---|---|
| Free | $0 | 体验用，额度最少 |
| Go | $8/月 | 适合轻度使用；官方页面注明可能含广告 |
| Plus | $20/月 | 适合大多数每天使用的人；Codex 额度按每 5 小时估算 |
| Pro 100 | $100/月 | Pro 三档中最低的一档，不含 Ultrafast |
| Pro 200 | $200/月 | 用量高于 Pro 100，不含 Ultrafast |
| Pro 500 | $500/月 | 三档中用量最高，含 GPT-6 Astra / GPT-6.1 Sol 的 Ultrafast |
| Business / Enterprise | 定价页未直接标价，按每人每月计费；Enterprise 需联系销售 | 团队、企业 |

来源：[OpenAI 定价页](https://openai.com/chatgpt/pricing/)（Free、Go、Plus 价格；Pro 显示"From $100"和"3 档用量供选择"）、[About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)（Pro 三档的价格和区别）、[What is ChatGPT Plus?](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)（Plus $20/月，按月计费）。价格和权益随时可能调整，一切以官方页面为准。

补充说明（均出自上述官方页面）：

- Plus 和 Pro 都只能按月付款，官方写明不提供年付，也不支持一次预付多个月。
- Pro 200 目前可以重新订阅，价格不变，但新订阅的用量额度比以前低。2026-09-22 至 09-29（太平洋时间上午 10 点）期间持有有效 Pro 200 订阅的老用户，旧额度保留到 2026-10-29，之后同样按新额度计算。
- 会员与 API 分开计费，开通会员并不等于拥有 API 额度。
- Codex：Plus 的额度按每 5 小时估算，Pro 目前没有 5 小时限制，两者都可能另有每周上限；额度用完后可以单独购买 credits，价格因套餐而异（[Codex 定价页](https://developers.openai.com/codex/pricing)）。

## Plus 和 Pro 怎么选

- 第一次开通会员：先选 **Plus**。日常问答、写作、偶尔写代码都够用。
- 用 Plus 时一周里有好几天碰到上限，或者每天要用 Codex 写好几个小时代码：选 **Pro 100**。
- 几乎整天都在写代码、做研究：选 **Pro 200**；需要 Ultrafast 或对额度要求很高：选 **Pro 500**。
- 官方对三档只描述了"用量高低"，并没有给出具体倍数；网上流传的"5X / 10X / 25X"属于第三方说法，以官方为准。

## 为什么国内开通 ChatGPT Plus 很难

- OpenAI 官方不面向中国大陆提供服务（见上文地区说明），使用时需要保持网络环境稳定。
- 官网结算一般只接受支持地区发行的银行卡，支付宝和银联卡无法使用；国内发行的双币卡也经常被拒（card declined）。
- 账单地址与卡片信息不一致、同一张卡反复尝试付款，都会让付款越来越难通过。

## 几种开通方式对比

| 方式 | 优点 | 缺点 |
|---|---|---|
| 自己用海外卡订阅 | 官方价格，完全自己掌控 | 国内的卡基本无法支付，被拒很常见 |
| 虚拟信用卡 | 按官方价付款 | 有开卡费、手续费和汇率差，经常被拒，平台存在跑路风险 |
| 外区 Apple ID + 礼品卡 | 不需要信用卡 | 需要外区账号，步骤繁琐，订阅由 App Store 管理 |
| 合租 / 拼车 | 单价低 | 通常违反服务条款，聊天记录不私密，额度被他人分走，容易触发风控 |
| 代充（订阅代付） | 可以用支付宝下单，不用自己的卡 | 需要挑选靠谱的卖家 |

## 挑选代充的 6 个判断点

代充的本质就是"别人替你付款，把订阅开通到你自己的账号上"。各家页面看起来大同小异，真正的区别在于下面 6 件事。

1. **价格是否合理。** 官方 Plus 为 $20/月，代充价格由平台自行定价，一般会比官方美元价折算后略高（包含海外付款渠道成本和售后成本）。如果价格远低于官方美元价折算（比如几十元一个月），一定要问清原因，常见情况是退款单、漏洞单，订阅过几天就会被收回。另外留意价格旁的"起"字，以及服务费、发票费是否另算。
2. **是否索要账号密码。** 正规代充不需要密码。靠谱的自助开通只会让你复制一段登录信息，不要密码，不要你转发手机或邮箱验证码，也不要求安装软件或插件。凡是索要密码、验证码，或让你关闭两步验证的，直接换一家。
3. **多久到账。** 问清楚是自助开通还是人工开通，页面上标注的到账时间是否说明了统计口径。只写"秒到"却不说明如何统计的，只能当作宣传语看待。
4. **失败了怎么退。** 付款前问清开通失败后钱或卡密如何处理：是自动退回还是需要申请，重试是否有次数限制。
5. **中途掉订阅管不管。** 问清质保覆盖多长时间、掉订阅后怎么处理（补开、补时长还是退款），并要求对方以文字形式答复。
6. **售后找谁。** 是否有能联系上的真人客服、是否有订单查询入口、平台背后是谁、域名能否在其他地方核实。

## 付款前 1 分钟自查清单

不管在哪家购买，付款前都可以对照下面 6 条：

- [ ] 页面价格就是需要支付的全部金额，没有"起"字，也不另收服务费
- [ ] 不要我的密码、短信或邮箱验证码，也不要求我安装软件或插件
- [ ] 写明是自助还是人工开通，以及大致多久到账
- [ ] 写明开通失败后钱或卡密如何处理
- [ ] 写明当期会员中途掉了怎么补、补多久
- [ ] 有能找到真人的售后和订单查询入口，域名可以在别处核实

只要有一条答不上来，就先不要付款。

## 报错 / 常见问题大全

每一条都按"现象 → 原因 → 怎么处理"的顺序编写，处理办法来自 OpenAI 官方帮助中心并附官方链接；官方没有提到的地方会注明"以官方说明为准"。

### 1. 付款时提示"请核对账单信息后重试"（英文界面类似 Your card was declined）

- **现象：** 在 chatgpt.com 升级 Plus / Pro，填好卡片信息点击付款后，页面提示"请核对账单信息后重试"，或者英文提示卡片被拒。
- **原因：** 这是付款被拒后的统一提示。官方列出的常见原因有：卡号、有效期、账单地址填写错误，或与发卡行登记的信息不一致；银行出于安全考虑拦截了交易，或余额不足；你本人或发卡行所在地不在 OpenAI 支持地区内（官方原话：如果任何一方位于支持地区之外，付款可能被拒）。官方页面没有逐字解释这条中文提示，以官方说明为准。
- **怎么处理：** 按官方建议：① 核对卡号、有效期和账单地址，账单地址填写发卡行登记的真实地址；② 清除浏览器缓存和 Cookie 后再试一次；③ 联系银行，确认交易是否被拦截、余额是否充足；④ 确认你本人和发卡行都在支持地区内；⑤ 以上都无效时，通过帮助中心右下角的聊天窗口联系 OpenAI 支持。不要在短时间内反复点击付款，连续被拒会让后续付款更难通过。
- **官方出处：** [Why did my ChatGPT Plus or ChatGPT Pro renewal transaction fail?](https://help.openai.com/en/articles/7242622-why-did-my-chatgpt-plus-or-chatgpt-pro-renewal-transaction-fail)、[Supported countries and territories](https://platform.openai.com/docs/supported-countries)

### 2. 卡被拒（card declined），国内银行卡 / 支付宝无法付款

- **现象：** 国内发行的信用卡、借记卡、双币卡被拒；付款页面没有支付宝等国内支付选项。
- **原因：** 官方定价页写明 Go / Plus / Pro / Business 接受主流信用卡；结算以支持地区为前提，国内发行的银联卡和支付宝不在支持范围内，双币卡也常因发卡行所在地而被拒。
- **怎么处理：** 换用支持地区发行的银行卡，或者改用代充（由卖家付款，会员开通到你自己的账号）。
- **官方出处：** [OpenAI 定价页 FAQ](https://openai.com/chatgpt/pricing/)、[续费失败说明](https://help.openai.com/en/articles/7242622-why-did-my-chatgpt-plus-or-chatgpt-pro-renewal-transaction-fail)

### 3. 已有订阅，想升级到 Pro 或更换档位，找不到入口 / 提示账号已有订阅

- **现象：** 账号已经是 Plus，想换成 Pro，或者想从 Pro 100 换到 Pro 200，页面上没有想要的选项；在代充平台提交时提示"该账号已有订阅或近期付款记录"。
- **原因：** ChatGPT 的订阅由购买渠道各自管理：网页（chatgpt.com）、Apple App Store、Google Play 互相独立。官方说明：更换方案需使用现有账号，在 **Settings → My Plan** 中查看当前订阅和可切换的方案；通过 App Store / Google Play 订阅的，网页端无法管理，需要先在对应商店中处理。同一账号在两个渠道各订一份，会被重复扣费。代充平台出现"已有订阅"一类提示，通常是因为账号当前已有生效中的订阅或刚刚付过款，通道不会重复开通。
- **怎么处理：** 网页订阅：在 Settings → My Plan 查看可用的升级 / 切换选项；App 内订阅：先到 App Store / Google Play 管理。降级或取消会在当前账期结束时生效，在此之前可以撤回。
- **官方出处：** [About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)、[How do I avoid being charged twice](https://help.openai.com/en/articles/20001043-how-do-i-avoid-being-charged-twice-if-i-subscribe-to-chatgpt-on-ios-android-and-the-web)

### 4. Plus 到期 / 续费扣款失败，账号变回免费版

- **现象：** 到了续费日没有扣款成功，收到付款失败的邮件，账号变回 Free。
- **原因：** 官方说明，续费偶尔会因为安全措施或支付方式本身的问题而失败，常见原因有银行拦截、卡片过期或余额不足、浏览器缓存干扰、你本人或发卡行不在支持地区。取消订阅或续费失败后，付费功能可用到当前账期结束，之后恢复为免费版。
- **怎么处理：** 自己绑卡的：按官方建议清除缓存、核对卡片信息和账单地址、联系银行，然后在 Settings → Billing 重新订阅；通过代充开通的：不经过你的银行卡，到期前重新下单一次即可。
- **官方出处：** [续费失败说明](https://help.openai.com/en/articles/7242622-why-did-my-chatgpt-plus-or-chatgpt-pro-renewal-transaction-fail)、[Canceling your ChatGPT subscription](https://help.openai.com/en/articles/7232927-how-do-i-cancel-my-chatgpt-plus-subscription)

### 5. 付了钱（或代充显示成功），账号却还是 Free

- **现象：** 扣款成功、也收到了收据，登录后仍是免费版；或者代充页面显示成功，但在 ChatGPT 里看不到 Plus。
- **原因：** 官方列出的原因：当前登录的邮箱或登录方式（Google / Apple / 邮箱密码）与付款时的账号不一致；手机 App 内的购买没有同步到账号；页面没有刷新。
- **怎么处理：** 官方建议：① 确认当前登录的就是付款时使用的账号和登录方式；② 在手机 App 里点击"Restore purchases（恢复购买）"；③ 退出后重新登录；④ 仍然不行的，带上收据或卡号后 4 位联系 OpenAI 支持。通过代充开通的应找卖家处理，因为付款不是你本人完成的，官方查不到你的付款记录。
- **官方出处：** [What is ChatGPT Plus?](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)

### 6. 被扣了两次钱

- **现象：** 信用卡和 App Store（或 Google Play）同时出现 ChatGPT 的扣款记录。
- **原因：** 网页端和应用商店各自独立计费，在一边订阅后另一边没有取消，就会扣两份。官方特别提醒：Apple 续费失败并不会自动取消订阅，Apple 会持续重试，你更新 Apple 付款方式后可能又把它续上了。
- **怎么处理：** 按官方步骤检查三个地方：iPhone 设置 → 你的姓名 → 订阅；Google Play → 订阅；chatgpt.com 的 Settings → Account / Billing。只保留一份，其余在对应渠道取消。通过 Apple 购买的退款找 Apple；通过 Google Play 购买的通过 OpenAI 支持申请；两份订阅不会自动退款，重复扣费的错误可以申请复核。
- **官方出处：** [How do I avoid being charged twice](https://help.openai.com/en/articles/20001043-how-do-i-avoid-being-charged-twice-if-i-subscribe-to-chatgpt-on-ios-android-and-the-web)

### 7. 想取消自动续费 / 想申请退款

- **现象：** 不想下个月继续扣费，或者刚付完款就想退。
- **原因 / 规则：** 取消只会停止之后的续费，不会自动退还已支付的费用；付费功能保留到当前账期结束。退款资格会根据购买情况和所在地法规另行评估，获批后通常在 5–10 个工作日内到账。
- **怎么处理：** 网页端：Settings → Billing → Cancel plan；iPhone：设置 → 姓名 → 订阅 → ChatGPT → 取消订阅；安卓：Play 商店 → 订阅 → ChatGPT → 取消。官方建议在下次扣款日之前至少 24 小时取消。代充开通的会员不经过你的银行卡，不会自动续费，无需取消。
- **官方出处：** [Canceling your ChatGPT subscription](https://help.openai.com/en/articles/7232927-how-do-i-cancel-my-chatgpt-plus-subscription)、[What is ChatGPT Plus?](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)

### 8. Pro 100 / 200 / 500 有什么区别？Pro 200 的额度为什么变了？

- **现象：** 升级页面只写了 Pro "From $100"和"3 档用量"，看不出差别；有人说 Pro 200 的额度被削减了。
- **说明（官方）：** 三档都包含 Pro 模型、Codex、深度研究、图像生成、记忆和文件上传，区别在于"包含的用量"多少以及是否有 Ultrafast：只有 Pro 500 提供 Ultrafast（GPT-6 Astra、GPT-6.1 Sol，按标准速率的 8 倍扣减用量）；Pro 100 / 200 即使购买 credits 也无法解锁 Ultrafast。Pro 200 的新订阅自 2026 年 9 月底起用量低于以前，价格不变；老用户过渡期截至 2026-10-29。额度用完后，对应模型需要等待重置，官方支持无法帮你提前重置。
- **怎么处理：** 按实际用量选择档位；拿不准时先买低一档用一周。三档都只能按月付款。
- **官方出处：** [About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)

### 9. 使用中提示达到用量上限，某个模型暂时不可用

- **现象：** 对话中提示已达上限，某个模型在重置时间之前无法使用。
- **原因：** Plus / Pro 没有固定的每日条数限制，额度会按模型、上下文长度、推理和工具调用等因素折算，并按滚动时间窗口计算；达到上限后，该模型在重置前不可用。
- **怎么处理：** 等待提示中给出的重置时间；换用轻量模型继续；如果经常碰到上限，就升级一档。Codex 用量到顶后，Plus / Pro 用户可以购买 credits 继续使用。
- **官方出处：** [About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)、[Codex 定价页](https://developers.openai.com/codex/pricing)

### 10. 开通了 Plus，API 仍然没有额度 / Codex 提示需要升级

- **现象：** platform.openai.com 显示余额为 0；登录 Codex 后提示升级套餐。
- **原因：** 会员与 API 分开计费（Plus 帮助文章原文：API 用量单独计费）。Codex 需要用 **Sign in with ChatGPT** 登录已开通会员的账号，用量才会计入会员；用 API Key 登录则按 API 价格扣费；如果登录的是另一个没有会员的邮箱，同样会提示升级。
- **怎么处理：** 需要 API 的，到 platform.openai.com 单独充值；在 Codex 中执行 `codex logout` 后重新选择 Sign in with ChatGPT，用已开通会员的账号登录。
- **官方出处：** [What is ChatGPT Plus?](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)、[Codex 定价页](https://developers.openai.com/codex/pricing)

### 11. 账号被停用（Deactivated）

- **现象：** 登录时提示账号已被停用，并收到 OpenAI 的通知邮件。
- **原因：** 官方会在邮件中说明原因；OpenAI 支持地区页面写明，在不支持的地区访问可能导致账号被封禁或停用，其他常见原因是违反使用政策（多人共用、脚本批量调用等）。
- **怎么处理：** 先查看邮箱里的通知，按邮件指引提出申诉；能否恢复、订阅费是否退还，以官方处理结果为准。通过代充开通的订单，请找卖家确认质保范围。
- **官方出处：** [Supported countries and territories](https://platform.openai.com/docs/supported-countries)、[OpenAI 使用政策](https://openai.com/policies/usage-policies/)

### 12. 自助开通（卡密方式）的常见提示

以下提示来自自助充值页面的实际使用经验，并非 OpenAI 官方报错：

| 提示或情况 | 原因 | 怎么办 |
|---|---|---|
| accessToken 已过期 | 复制的登录信息放置太久 | 用无痕窗口重新登录 ChatGPT，打开 chatgpt.com/api/auth/session，复制后 1 分钟内提交 |
| 登录凭证无效 / 格式不对 | 没有复制完整 | 在该页面全选后再复制，内容应以 { 开头、以 } 结尾 |
| 识别到的邮箱不是要充值的账号 | 无痕窗口里登录了别的账号 | 退出后换成要开通的账号重新登录，再复制 |
| 银行卡支付未获通过 | 充值通道付款时被支付风控拦截 | 卡密会自动退回，隔一段时间再试，连续重复提交容易触发暂停 |
| 充值通道暂时不可用 | 通道正在补充额度 | 卡密不会被扣，稍后再试 |
| 一直转圈 | 上游仍在处理 | 不要重复提交，等 3 分钟后刷新 ChatGPT |
| 显示成功但看不到 Plus | 页面没有刷新 | 退出后重新登录，App 内下拉刷新 |

手机端操作失败，多数是因为：用了 ChatGPT App（应改用手机浏览器）、在 App 内置浏览器中打开（应换成系统浏览器）、没有开启无痕模式、长按时只选中了部分文字。条件允许的话，尽量用电脑浏览器操作。

安全提醒：这段登录信息相当于临时登录凭证，只粘贴到你信任的充值页面，不要发到群里；开通完成后，在 ChatGPT「设置 → 安全」中退出所有设备，它就会失效。

## 降低被封风险的使用习惯

- 保持网络稳定，不要频繁切换国家或地区。
- 一个账号只给自己使用。
- 不要用脚本批量调用网页版。
- 账号被停用时，先查看邮箱通知并按官方指引申诉；订阅费是否退还以官方结果为准。

## 常见问题

**Q：取消自动续费后，会员会立刻失效吗？**
A：不会，已付费的周期可以用到结束日（官方说明见上文第 7 条）。

**Q：ChatGPT 可以用支付宝付款吗？**
A：官网不能直接使用支付宝。可以在代充平台用支付宝下单，由卖家开通到你自己的账号。

**Q：通过代充开通的会员，能找 OpenAI 退款吗？**
A：不能。付款不是你本人完成的，官方查不到你的付款记录，出了问题只能找卖家，所以一定要选能找到人的卖家。

**Q：代充会从我的银行卡自动续费吗？**
A：不会。付款不经过你的银行卡，用一个月买一个月。

**Q：一个 Plus 能几个人共用吗？**
A：不建议。多人会互相抢占额度，多地同时登录容易触发风控，而且通常违反服务条款。

**Q：Go 和 Plus 有什么区别？**
A：Go 为 $8/月，面向轻度使用，官方页面注明可能含广告；Plus 为 $20/月，额度更高，Codex 用量也更多。

**Q：ChatGPT 和 Claude 该买哪个？**
A：写作、搜索、画图偏向 ChatGPT；长文本和写代码，很多人更偏向 Claude，两家的入门价都是 $20/月。

## 国内开通参考

没有海外银行卡，想了解国内如何开通 ChatGPT Plus / Pro，以及代充的流程和注意事项，可以参考：[ChatGPT Plus / Pro 国内开通](https://t.3ms.run/chatgpt-ai)。下单前建议先对照上文的 [6 个判断点](#挑选代充的-6-个判断点) 和 [付款前自查清单](#付款前-1-分钟自查清单)。

## 参考资料

- [OpenAI 定价页](https://openai.com/chatgpt/pricing/)
- [What is ChatGPT Plus?](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)
- [About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)
- [Why did my ChatGPT Plus or ChatGPT Pro renewal transaction fail?](https://help.openai.com/en/articles/7242622-why-did-my-chatgpt-plus-or-chatgpt-pro-renewal-transaction-fail)
- [Canceling your ChatGPT subscription](https://help.openai.com/en/articles/7232927-how-do-i-cancel-my-chatgpt-plus-subscription)
- [How do I avoid being charged twice if I subscribe on iOS, Android, and the web?](https://help.openai.com/en/articles/20001043-how-do-i-avoid-being-charged-twice-if-i-subscribe-to-chatgpt-on-ios-android-and-the-web)
- [Codex 定价页](https://developers.openai.com/codex/pricing)
- [Supported countries and territories](https://platform.openai.com/docs/supported-countries)
- [OpenAI 使用政策](https://openai.com/policies/usage-policies/)
- [OpenAI 帮助中心：账号、登录与账单](https://help.openai.com/en/collections/3943089-account-login-and-billing)

## English summary

This repository is a Chinese-language guide to paying for ChatGPT Plus/Pro from mainland China, where OpenAI does not offer service and domestic bank cards and Alipay are not accepted. It lists official prices (checked 2026-10-17 against OpenAI's pricing and help pages), explains "daichong" (third-party subscription payment: a seller pays and the subscription is activated on *your own* account), gives a 6-point checklist for choosing a seller (reasonable price, no password required, clear delivery time, refunds on failure, mid-term warranty, reachable support), and troubleshoots common payment errors with links to the OpenAI Help Center. Not affiliated with or authorized by OpenAI.

## 来源与许可

本文改编自"瑶瑶ai训练师"整理的《GPT代充 / ChatGPT Plus 国内充值指南》，原文采用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.zh-hans) 许可。本版本对文字进行了改写，删除了原作者的个人介绍、店铺信息与价格快照，并替换了部分外部链接；改动内容不代表原作者立场。本文同样以 CC BY 4.0 许可发布。本仓库为非官方教程，与 OpenAI 没有隶属关系，品牌名称仅用于说明，官方价格和权益以 OpenAI 官网为准。
