# 🐾 OpenClaw Skills Collection

因为养了一只约克夏小狗，发现自己总是记不住该什么时候驱虫、打疫苗、洗澡……索性写了一个专门的 Skill 来帮自己管这些事。顺手也把平时出行规划用的旅行助手一起整理进来了。

两个都是我自己在用的，不是为了上架而做的模板，拿去直接用就行。

---

## 📦 Skills

### 🐶 约克夏小狗养育助手
[yorkshire-puppy-care](https://github.com/heidi1998/openclaw-skills/tree/main/yorkshire-puppy-care)

养约克夏之前没想到这个品种需要这么细心——洗澡频率、换牙期、驱虫周期、疫苗时间，每一件单独拎出来都不难，但加在一起真的容易忘。这个 Skill 就是帮我把这些事情都管起来的。

第一次用的时候告诉它狗狗的基本情况，它会帮你生成一张护理时间表，之后每次聊天都会根据当前时间提醒你有没有事项要到期。狗狗行为异常的时候也可以直接描述给它，它会帮你分析可能的原因。

**主要功能：**
- 根据狗狗年龄和上次护理时间，自动生成喂食、洗澡、驱虫、疫苗的个性化时间表
- 主动提醒即将到期的护理事项
- 分析异常行为（不吃饭、一直叫、舔爪子、精神萎靡）背后的原因
- 联网搜索最新的宠物医学和养护知识

```bash
openclaw skill install https://github.com/heidi1998/openclaw-skills/tree/main/yorkshire-puppy-care
```

---

### ✈️ 旅行助手
[travel-assistant](https://github.com/heidi1998/openclaw-skills/tree/main/travel-assistant)

出门旅行最怕的不是行程没排好，是到了才发现护照快过期、当地是雨季衣服带错了、热门景点要提前预约……这个 Skill 就是专门帮你在出发前把这些坑都排查一遍的。

告诉它你的旅行计划，它会整理出一张总览表，然后主动帮你检查容易忽略的细节——签证、时差、插头规格、信用卡境外使用、紧急联系方式这些。有新问题就联网查，不靠记忆瞎说。

**主要功能：**
- 整理旅行信息，生成已确认事项 + 待办清单
- 主动检查护照有效期、签证、时差、货币、插头等常见遗漏
- 联网查询目的地实时天气和注意事项
- 根据目的地和天数生成个性化行李清单
- 检查行程时间安排是否合理

```bash
openclaw skill install https://github.com/heidi1998/openclaw-skills/tree/main/travel-assistant
```

---

> 两个 Skill 都用了 web_search，建议配合 DeepSeek API 使用效果更好。
> 宠物健康问题以专业兽医诊断为准，旅行签证政策以官方渠道为准。

有问题欢迎提 [Issue](https://github.com/heidi1998/openclaw-skills/issues)。
