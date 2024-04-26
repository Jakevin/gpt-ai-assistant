# GPT AI Assistant

<div align="center">

[![license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE)

</div>

這是fork [memochou1993](https://github.com/memochou1993/gpt-ai-assistant)的專案，並加上新的功能

1. 可用其他的AI Saas廠商的 API接口，如 groq、deepinfra、openrouter、自架Ollama
2. 產圖模型從 `dall-e-2` 改成 `dall-e-3`，並可設定畫質
3. `gpt-4` 也換成 `gpt-4-turbo` 
4. 增加 `gpt-4-vision` 圖片識別功能 

新增環境變數

```
PROVIDER_BASE_URL //供應商API網址
PROVIDER_BASE_TOKEN //供應商API金鑰
PROVIDER_BASE_MODEL //供應商模型名稱 ex：llama3-70b-8192

OPENAI_IMAGE_GENERATION_MODEL //使用的產圖模型，預設 dall-e-2
OPENAI_IMAGE_GENERATION_QUALITY //使用的產圖尺吋，預設 256*256
```

實測
![截圖 2024-04-26 凌晨1 54 01](https://github.com/memochou1993/gpt-ai-assistant/assets/4224127/b28b2d2a-3f5c-4c1f-bf48-f5abda6bd7c7)

![505383787631476931](https://github.com/memochou1993/gpt-ai-assistant/assets/4224127/dd364b20-2bda-40fa-8ace-092d8089b408)

![截圖 2024-04-26 下午2 47 55](https://github.com/memochou1993/gpt-ai-assistant/assets/4224127/a73be10c-f7db-42d0-bd69-4cc89ce03055)


## memochou1993 gpt-ai-assistant
GPT AI Assistant is an application that is implemented using the OpenAI API and LINE Messaging API. Through the installation process, you can start chatting with your own AI assistant using the LINE mobile app.

## News

- 2023-05-03: The `4.6` version now support `gpt-4` OpenAI model. :fire:
- 2023-03-05: The `4.1` version now support the audio message of LINE and  `whisper-1` OpenAI model. :fire:
- 2023-03-02: The `4.0` version now support `gpt-3.5-turbo` OpenAI model. :fire:

## Documentations

- <a href="https://memochou1993.github.io/gpt-ai-assistant-docs/" target="_blank">中文</a>
- <a href="https://memochou1993.github.io/gpt-ai-assistant-docs/en" target="_blank">English</a>

## Credits

- [jayer95](https://github.com/jayer95) - Debugging and testing
- [kkdai](https://github.com/kkdai) - Idea of `sum` command
- [Dayu0815](https://github.com/Dayu0815) - Idea of `search` command
- [mics8128](https://github.com/mics8128) - Implementing new features
- [All other contributors](https://github.com/memochou1993/gpt-ai-assistant/graphs/contributors)

## Contact

If there is any question, please contact me at memochou1993@gmail.com. Thank you.

## Changelog

Detailed changes for each release are documented in the [release notes](https://github.com/memochou1993/gpt-ai-assistant/releases).

## License

[MIT](LICENSE)
