# #AIForCause
### Empowering everyone with free-to-use API for ChatGPT.
## AIForCause is a step that DEEPNIGHT takes towards advancing and democratizing the world of Artificial Intelligence.
![AIForCause Banner](https://github.com/deepnight-ai/aiforcause---FREE-APIs-to-AI-MODELS/blob/main/%23aiforcause.png?raw=true)

# !!!UPDATES!!!
<ul>
  <li>Feb 11th, 2024: We are bringing in <b>GPT-4-Turbo</b> for all!</li>
  <li>Nov 3rd, 2023: We are upgrading the API from <b>GPT-3.5 4k</b> to <b>GPT-3.5 16k + Function Calling</b></li>
</ul>

---

Hello, we are [DEEPNIGHT](https://deepnight.tech), we are thrilled to introduce you to the **#aiforcause API**. We've got something special to share with the AI community.

## Our Mission

At DEEPNIGHT, we believe in pushing the boundaries of AI. We're on a mission to make AI accessible to everyone, regardless of their financial resources. We understand that not everyone can afford expensive AI services, and we're here to change that. With the #aiforcause API, you can access powerful AI tools to drive innovation, enhance your applications, and bring your ideas to life.

## What's the Deal?

We're providing the ChatGPT API for free! Yes, you read it right—absolutely free of cost. Our aim is to empower developers, innovators, and dreamers with the AI tools they need to build a brighter future. To get started, explore our user-friendly API, and see how it can elevate your projects and enable new possibilities in AI-driven innovation.

## The API

- **Endpoint:** [https://aiforcause.deepnight.tech](https://aiforcause.deepnight.tech)

## Privacy Matters

Your privacy is important to us. That's why we've made sure our API comes with no strings attached. We won't ask for your personal information, track your usage, or log your data. We're in the business of providing AI, not collecting your info, so no data-stealing shenanigans here!

## How You Can Help

We're in this together, and we're counting on your support to keep this API free. If you find value in what we're offering, we'd greatly appreciate any contributions or donations you can make to help us sustain this mission. Your generosity will enable us to continue providing this service and expand our offerings, including adding more features and capabilities to the API.

**Donate Now:** [https://donate.deepnight.tech/aiforcause](https://donate.deepnight.tech/)

## What's Available Now

We're starting with the GPT-3.5 4k API Endpoint, and it's just the beginning. With your support, we aim to bring you even more models, including GPT-4, unlocking a world of AI possibilities.

## Usage Guidelines

- **Rate Limit:** Unfortunately, the API does have a rate limit. The current rate limit is set to 240k tokens per minute and 1440 requests per minute.

- **Please use responsibly!** We are doing this for a good cause! Please use it for the same reason. This effort is not going to be worth a single penny if we end up revoking the endpoint. Your responsible usage ensures that this valuable resource remains available to all.

- **API Key:** The endpoint for OpenAI models is: ```https://aiforcause.deepnight.tech/openai/``` and for the API Key, just pass anything... seriously doesn't matter.

- **Models:** To find the active models, ping on ```https://aiforcause.deepnight.tech/models``` and use the  ```model_id``` as the model to be mentioned in the OpenAI client.

- ~**No Streaming Support:** It doesn't currently have streaming support, please don't use stream with this. If you encounter any issues or have questions about the API's usage, feel free to reach out to us at [hello@deepnight.tech](mailto:hello@deepnight.tech).~

- **Streaming Support:** We are finally bringing in streaming support over the API.

- **Response:** The response is going to be an OpenAI API response with just a couple of things masked. Rest everything is exactly the same!

## Example Code:
```python
from openai import OpenAI
client = OpenAI(
  api_key="<BLAH__BLAH__BLAH>",
  base_url="https://aiforcause.deepnight.tech/openai/"
)

response = client.chat.completion.create(
  model="gpt-35-turbo",   # gpt-35-turbo (GPT-3.5 Turbo - 4k) || gpt-35-turbo-16k (GPT-3.5 Turbo 16k) || gpt-4-turbo (GPT-4 Turbo)
  messages=[...your_messages...],
  stream=False # or True
)

print(response.choices[0].message.content)
```

## Join the Movement

Whether you're a seasoned AI professional or just getting started, DEEPNIGHT's AI for Cause API is here for you. Let's build a more inclusive AI community, break the barriers, and explore the limitless possibilities of AI together.

Get started now: [https://aiforcause.deepnight.tech](https://aiforcause.deepnight.tech)

Your contribution can help us bring AI to those who need it most and expand the horizons of what's possible with AI. Together, we can make AI a force for good.

Cheers to AI without limits! 🚀

— Team [DEEPNIGHT](https://deepnight.tech)

*Note: DEEPNIGHT is an independent organization and not affiliated with OpenAI. This API is provided free of charge by DEEPNIGHT to support the AI community.*
