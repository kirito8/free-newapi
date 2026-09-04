# Free NewAPI · 免费 API 中转站导航

> 一份持续维护的「免费 / 公益 AI 大模型 API 中转站与免费额度平台」清单。
> 收录社区公益中转站、官方免费额度平台，以及可自建中转站的开源工具。
> 如果觉得好用，还请麻烦点个免费的小星星⭐哦~。

[![License](https://img.shields.io/github/license/kirito8/free-newapi)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kirito8/free-newapi?style=social)](https://github.com/kirito8/free-newapi)

---

## ⚠️ 免责声明（务必先读）

1. **免费额度随时变化**：本清单中的额度、价格、可用性均以各站点实时页面为准，可能在数天内失效或调整。
2. **公益站 / 中转站存在风险**：社区维护的中转站可能存在「掺水」「跑路」「降级」风险，**请勿传入个人隐私、客户数据或敏感内容**，更不要绑定主账号、不要充值大额资金。
3. **本清单仅供学习、研究与个人实验用途**，使用过程中请遵守各平台服务条款与当地法律法规。

> 📅 本清单核验时间：**2026-09-04**。欢迎提 Issue / PR 更新失效信息。也欢迎提供未收录的公益站点~

---

## 目录

- [一、公益中转站](#一公益中转站)
- [二、官方免费额度平台](#二官方免费额度平台)
- [三、开源聚合 / 自建中转工具](#三开源聚合--自建中转工具)
- [四、快速接入（OpenAI 兼容格式）](#四快速接入openai-兼容格式)
- [五、使用建议与避坑](#五使用建议与避坑)
- [六、贡献指南](#六贡献指南)

---

## 一、公益中转站


| 名称 | 地址 | 免费额度 | 覆盖模型 | 备注 |
| --- | --- | --- | --- | --- |
| Any Router | https://anyrouter.top/register?aff=pG9m | 完全免费，新用户注册赠 $100，签到送 $25 | 10+ 模型（主要为Claude） | Linux Do信任等级需≥2方可注册 |
| Agent Router | https://agentrouter.org/register?aff=jnrM | 完全免费，新用户注册赠 $100，签到送 $25 | Claude / GPT / Glm / Deepseek | github注册满5年可注册 |
| 维云模型开放平台 | https://vsllm.cc/i/z2IN | 每日任务获取免费额度 | Claude / GPT / Glm / Deepseek 等69个模型 | 注册无限制 |


---

## 二、官方免费额度平台


### 国内平台

| 平台 | 地址 | 免费额度 | 亮点 |
| --- | --- | --- | --- |
| 智谱 BigModel | `https://open.bigmodel.cn` | GLM-4-Flash **永久免费**（30 并发） | 中文代码能力强 |
| 美团 LongCat | 美团 AI 开放平台 | Chat 系列 500 万 Token/天 | 额度按天刷新 |
| 硅基流动 SiliconFlow | `https://cloud.siliconflow.cn` | 部分模型永久免费 + 新户赠额 | 国内直连海外模型，OpenAI 兼容 |
| 阿里云百炼 | `https://bailian.aliyun.com` | 新用户 7000 万 Token | 千问全系，长上下文 |
| 百度千帆 | `https://qianfan.cloud.baidu.com` | 每模型 100 万 Token/3 个月 | 多模态覆盖 |
| 火山方舟（豆包） | 火山引擎 | 每模型 50 万 Token | 推理成本极低 |
| 中国移动 MoMA | 移动云 | 9000 万 Token 体验包 | 300+ 模型智能路由 |
| DeepSeek 官方 | `https://platform.deepseek.com` | 新用户 100 万 Token | 性价比高 |
| 商汤日日新 | `https://platform.sensenova.cn` | 公测期间免费 | OpenAI 兼容，支持 20 个 Key |
| 魔搭社区 ModelScope | `https://modelscope.cn` | 每天 2000 次调用 | 3000+ 模型，适合横评 |

### 海外平台

| 平台 | 地址 | 免费额度 | 亮点 |
| --- | --- | --- | --- |
| Google Gemini AI Studio | `https://aistudio.google.com` | Gemini 2.5 Flash 免费用 | 免费额度慷慨，多模态强 |
| GitHub Models | `https://github.com/marketplace/models` | 用 GitHub 账号 Token 免费用 | 无需绑卡 |
| OpenRouter | `https://openrouter.ai` | 28+ 免费模型（搜索 `free`） | 一个 Key 调用全网模型 |
| NVIDIA NIM | `https://build.nvidia.com` | 无额度限制，100+ 模型 | 免信用卡 |
| Groq | `https://groq.com` | 免费 tier | 极低延迟 |
| SambaNova | `https://sambanova.ai` | 新户赠 $5 | 额度充足 |
| Cerebras | `https://cerebras.ai` | 免费 tier | 推理速度极快 |
| Mistral | `https://mistral.ai` | 免费 tier | Codestral 可用 |
| Cohere | `https://cohere.com` | Trial 1000 次/月 | 仅小模型 |
| Cloudflare Workers AI | `https://developers.cloudflare.com` | 免费 tier | 边缘推理 |
| HuggingFace | `https://huggingface.co` | Inference Providers 免费额度 | 模型生态最全 |

---

## 三、开源聚合 / 自建中转工具

> 不想依赖第三方中转站？可以自建一个属于自己的「中转站」。

| 项目 | 地址 | 说明 |
| --- | --- | --- |
| New-API | `github.com/QuantumNous/new-api` | 国内社区热门，统一转 OpenAI / Claude / Gemini 格式，带额度分配与用量看板 |
| One API | `github.com/songquanpeng/one-api` | 中文圈最火的中转站，38k+ Star，支持 100+ 渠道 |
| FreeLLMAPI | `github.com/Alvaro-Cintas/freellmapi` | 聚合 14+ 家免费额度为单一 OpenAI 端点，自动故障转移 |
| AI Proxy | `github.com/labring/aiproxy` | 企业级生产网关，多租户、负载均衡、自动重试 |

**New-API 快速部署（Docker）：**

```bash
docker run -d --name new-api \
  -p 3000:3000 \
  -v $(pwd)/data:/data \
  --restart always \
  quantumuons/new-api:latest
```

---

## 四、快速接入（OpenAI 兼容格式）

绝大多数平台 / 中转站都兼容 OpenAI 格式，只需替换 `base_url` 与 `api_key`。

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://你的中转站地址/v1",   # 例如 https://api.iamhc.cn/v1
    api_key="你的 sk- 开头的密钥",
)

resp = client.chat.completions.create(
    model="gpt-4o-mini",                     # 换成你需要的模型名
    messages=[{"role": "user", "content": "你好"}],
)
print(resp.choices[0].message.content)
```

**Claude Code / Anthropic 兼容配置示例：**

```json
{
  "env": {
    "ANTHROPIC_API_KEY": "你的 sk- 开头密钥",
    "ANTHROPIC_AUTH_TOKEN": "你的 sk- 开头密钥",
    "ANTHROPIC_BASE_URL": "https://你的中转站地址"
  }
}
```

---

## 五、使用建议与避坑

1. **开「用完即停」**：很多平台免费额度用完后会从绑定的卡扣费，务必关闭自动续费。
2. **免费额度有期限**：赠送 Token 常有 30 / 90 天有效期，领取后尽快使用。
3. **速率限制是隐形成本**：免费层普遍有 RPM / TPM 限制，高并发场景用多个平台组合，或自建 One API / New-API 做多渠道调度。
4. **国内 + 国际组合**：国内平台中文强、延迟低；国际平台模型新、选择多，按场景切换。
5. **Key 安全**：不要泄露 Key，中转站场景尽量用「专用子账号」，并在各平台设置单日消费上限。

---

## 六、贡献指南

欢迎补充新站点、修正失效信息。请遵循：

1. **一个站点一个条目**，提供名称、地址、免费额度、覆盖模型。
2. 提交时注明你的**核验日期**。

提交方式：直接提 Issue。

---

## License

[MIT](LICENSE) © free-newapi contributors
