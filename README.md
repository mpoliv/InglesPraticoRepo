# InglesPraticoRepo

## About This Repository

This repository is for learning and practicing English. It does not provide API keys or AI services.

## Getting API Keys for Raycast

If you're looking to use AI features in Raycast, you'll need to obtain API keys from the official AI providers. Here's how:

### Supported AI Providers

Raycast supports the following AI providers through their "Bring Your Own Key" (BYOK) feature:

#### 1. OpenAI
- **Models**: GPT-4, GPT-4 Turbo, GPT-3.5 Turbo
- **How to get your API key**:
  1. Visit [platform.openai.com](https://platform.openai.com)
  2. Sign up or log in to your account
  3. Go to API Keys section
  4. Create a new API key
  5. Copy the key (you won't be able to see it again)
- **Pricing**: Pay-as-you-go based on usage

#### 2. Anthropic (Claude)
- **Models**: Claude 3.5 Sonnet, Claude 3 Opus, Claude 3 Haiku
- **How to get your API key**:
  1. Visit [console.anthropic.com](https://console.anthropic.com)
  2. Sign up or log in to your account
  3. Go to API Keys section
  4. Create a new API key
  5. Copy the key securely
- **Pricing**: Pay-as-you-go based on usage

#### 3. Google AI (Gemini)
- **Models**: Gemini Pro, Gemini Ultra
- **How to get your API key**:
  1. Visit [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
  2. Sign in with your Google account
  3. Create a new API key
  4. Copy the key
- **Pricing**: Free tier available, then pay-as-you-go

### Setting Up API Keys in Raycast

Once you have your API key(s):

1. Open Raycast
2. Go to **Settings** → **AI** → **Custom API Keys**
3. Select your provider (OpenAI, Anthropic, or Google)
4. Paste your API key
5. Choose which models you want to enable
6. Save your settings

### Benefits of Using Your Own API Keys

- ✅ **Unlimited Usage**: Use as many prompts as your quota allows
- ✅ **No Raycast Pro Required**: Access AI features without a Raycast subscription
- ✅ **Privacy**: Your API keys are stored locally on your device
- ✅ **Choice**: Select from multiple AI providers and models
- ✅ **Cost Control**: Pay only for what you use directly to the provider

### Advanced: Custom OpenAI-Compatible Endpoints

Raycast also supports custom OpenAI-compatible APIs. You can configure these by editing the `providers.yaml` file located in Raycast's configuration directory (`~/.config/raycast/ai/providers.yaml` on macOS). This allows you to use:
- Local LLMs (via Ollama, LM Studio, etc.)
- Aggregated AI services (OpenRouter, CometAPI, etc.)
- Self-hosted AI models

For detailed instructions, refer to [Raycast's custom AI provider documentation](https://developers.raycast.com/api-reference/ai).

### Important Notes

⚠️ **Security**: Never share your API keys publicly or commit them to repositories. Keep them secure and rotate them regularly.

⚠️ **Costs**: While some providers offer free tiers, API usage can incur costs. Monitor your usage in each provider's dashboard.

⚠️ **This Repository**: This repository does NOT provide API keys or AI services. You must obtain keys from the official providers listed above.

## Resources

- [Raycast Official Website](https://www.raycast.com)
- [Raycast AI Documentation](https://www.raycast.com/core-features/ai)
- [Raycast Changelog - BYOK Feature](https://www.raycast.com/changelog/1-100-0)
- [OpenAI Platform](https://platform.openai.com)
- [Anthropic Console](https://console.anthropic.com)
- [Google AI Studio](https://aistudio.google.com)

## Questions?

If you have questions about:
- **Getting API keys**: Contact the respective AI provider's support
- **Raycast setup**: Visit [Raycast Support](https://www.raycast.com/support)
- **This repository**: Open an issue in this repository for questions about its content
