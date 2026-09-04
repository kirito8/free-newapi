# Free NewAPI · 免费 API 中转站导航

> 一份持续维护的「免费 / 公益 AI 大模型 API 中转站与免费额度平台」清单。
> 收录社区公益中转站、官方免费额度平台，以及可自建中转站的开源工具。

[![License](https://img.shields.io/github/license/kirito8/free-newapi)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kirito8/free-newapi?style=social)](https://github.com/kirito8/free-newapi)

---

## ⚠️ 免责声明（务必先读）

1. **免费额度随时变化**：本清单中的额度、价格、可用性均以各站点实时页面为准，可能在数天内失效或调整。
2. **公益站 / 中转站存在风险**：社区维护的中转站普遍存在「掺水」「跑路」「降级」风险，**请勿传入个人隐私、客户数据或敏感内容**，更不要绑定主账号、不要充值大额资金。
3. **优先选择有官方背书的渠道**：稳定性排序大致为「官方免费额度 > 知名开源聚合工具 > 社区公益中转站」。
4. **本清单仅供学习、研究与个人实验用途**，使用过程中请遵守各平台服务条款与当地法律法规。

> 📅 本清单核验时间：**2026-09-04**。欢迎提 Issue / PR 更新失效信息。

---

## 目录

- [一、社区公益中转站](#一社区公益中转站)
- [二、官方免费额度平台（最稳定）](#二官方免费额度平台最稳定)
- [三、开源聚合 / 自建中转工具](#三开源聚合--自建中转工具)
- [四、快速接入（OpenAI 兼容格式）](#四快速接入openai-兼容格式)
- [五、使用建议与避坑](#五使用建议与避坑)
- [六、贡献指南](#六贡献指南)

---

## 一、社区公益中转站

> 社区维护、注册即配发免费额度。**风险较高，仅建议测试用**。

| 名称 | 地址 | 免费额度（示例） | 覆盖模型 | 备注 |
| --- | --- | --- | --- | --- |
| 幻城网安公益 API | `https://api.iamhc.cn` | 完全免费 | 195+ 模型（千问 / DeepSeek / GLM / Kimi / 豆包等） | 支持 `auto` 自动路由模型 |
| 路由公园 RouterPark | `https://routerpark.com` | 新用户注册赠 $100 | Claude / GPT / Gemini 等 30+ 模型 | 支持 Google/GitHub 一键注册 |
| MegaLLM | `https://megallm.io` | 邀请注册赠 $125 | Claude Sonnet / Codex 等 | 仅支持 Google 账号注册 |
| DMXAPI | LangChain 中文网 | 22+ 款全免费模型 | 300+ 模型聚合 | OpenAI 兼容 |
| aiping.cn | `https://aiping.cn` | 轻量试用额度 | MiniMax / GLM 等 | 适合短期体验 |

> 💡 上述站点信息来自公开资料整理，请以站点实际页面为准，注册前自行甄别。

---

## 二、官方免费额度平台（最稳定）

> 有官方背书，免费额度相对长期、稳定，**日常开发首选**。

### 国内平台

| 平台 | 地址 | 免费额度（示例） | 亮点 |
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

| 平台 | 地址 | 免费额度（示例） | 亮点 |
| --- | --- | --- | --- |
| Google Gemini AI Studio | `https://aistudio.google.com` | Gemini 2.5 Flash 免费层 | 免费额度慷慨，多模态强 |
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
3. 公益中转站请标注风险等级，避免误导。

提交方式：Fork → 修改 `README.md` → 提交 Pull Request，或直接提 Issue。

---

## License

[MIT](LICENSE) © free-newapi contributors
