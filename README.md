<a href="https://gola.apimart.ai/k-pa9znm"><img src="https://raw.githubusercontent.com/fujc683/awesome-gpt-image-2-6-prompts/main/banner.jpg" width="100%" /></a>

# GPT Image 2.6 提示词库

> 252 条精选提示词，附预览图，按使用场景分类。Flare 与 Sunburst 两个变体。

**[👉 在 APIMart 上使用 GPT Image 2.6](https://gola.apimart.ai/k-pa9znm)**

`https://gola.apimart.ai/k-pa9znm`

[💰 价格](https://gola.apimart.ai/k-vVM7rK) · [🔑 获取 API Key](https://gola.apimart.ai/k-0dHVNL)

---

## Endpoint

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H "Authorization: Bearer $APIMART_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model":"gpt-image-2.6-flare","prompt":"a red apple","n":1,"size":"1024x1024"}'
```

## Models

| ID | Variant |
|---|---|
| `gpt-image-2.6-flare` | Flare |
| `gpt-image-2.6-sunburst` | Sunburst |

## Parameters

| Field | Type | Description |
|---|---|---|
| `model` | string | model id |
| `prompt` | string | text prompt |
| `n` | int | 1-4 |
| `size` | string | `1024x1024` / `1536x1024` / `1024x1536` |

## Poll

```bash
curl https://api.apimart.ai/v1/tasks/<task_id> -H "Authorization: Bearer $APIMART_API_KEY"
```

---

## License

CC BY 4.0
