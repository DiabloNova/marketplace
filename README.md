# Fonoster Marketplace

Find the integrations and VoIP providers that suit you, then use them in your Voice Applications with a single easy-to-use API.

Go to the [Marketplace](https://marketplace.fonoster.com)

## Partner Program

With our partner program, you can publish your API in the Fonoster Marketplace, and gain visibility with all new and existing users of Fonoster products.

By partnering with Fonoster Marketplace, you can leverage our ecosystem to your benefit. In Marketplace, you can publish plugins and extensions for Fonoster products.

**Already got an API to publish?** Simply submit a PR to the [item.json](https://github.com/fonoster/marketplace/blob/main/items.json) document.

We are accepting items in the following categories:

1. `nlu` - Natural Language Understanding
2. `tts` - Text to Speech APIs
4. `asr` - Automatic Speech Recognition
5. `cli` - Plugins or extension to Fonoster command-line interface
6. `provider` - VoIP Service Provider (coming soon)

**Example of Marketplace item**

```json
{
  "id": "dialogflow-es",
  "description": "Lifelike conversational AI with a state-of-the-art virtual agent, ES edition (standard)",
  "changelog": "https://raw.githubusercontent.com/fonoster/rox/main/CHANGELOG.md",
  "homepage": "https://cloud.google.com/dialogflow",
  "icon": "https://raw.githubusercontent.com/fonoster/rox/main/assets/es_logo.png",
  "issues": "https://github.com/fonoster/rox/issues",
  "license": "MIT",
  "name": "Dialogflow Connector (ES)",
  "org": "Fonoster",
  "picture": "/brand-assets/fonoster.svg",
  "readme": "https://raw.githubusercontent.com/fonoster/rox/main/MKPLACE.md",
  "related": [
    "dialogflow-cx"
  ],
  "categories": [
    "nlu"
  ],
  "repository": "https://github.com/fonoster/rox",
  "sponsored": false,
  "certified": false
}
```

The **sponsored** and **certified** entries are managed by Fonoster Inc. Leave them as `false`. If you wish to have a certified and or sponsored item, please contact us at [fonosterteam@fonoster.com](mailto:fonosterteam@fonoster.com)

> Sponsored and certified items are subject to a monthly or yearly fee.

