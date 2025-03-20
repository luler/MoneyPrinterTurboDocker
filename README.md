# MoneyPrinterTurboDocker

利用AI大模型，一键生成高清短视频

## 源码参考

- https://github.com/harry0703/MoneyPrinterTurbo

## 配置

- 复制 `config.example.toml` 为 `config.toml`
- 编辑 `config.toml` 文件，配置 `pexels_api_keys` 和 `llm_provider` 
```
video_source = "pexels"
#这里填写你的pexels api key
pexels_api_keys = [ "xxxxxxx"]

#此处省略其他配置......

llm_provider="openai"
#这里填写你的openai api key
openai_api_key = "sk-xxxxxx" 
#openai api url
openai_base_url = "https://api.openai.com/v1"
#openai模型名称
openai_model_name = "gpt-4o"

#此处省略其他配置......
```
## 运行应用

```bash
docker-compose up -d
```

## 使用

访问页面：http://localhost:8501




