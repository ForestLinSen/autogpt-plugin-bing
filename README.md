# Auto-GPT Bing Search Plugin: Extend Your Search Options with Auto-GPT

Language: [English](https://github.com/ForestLinSen/autogpt-plugin-bing/blob/master/README.md) | [中文](https://github.com/ForestLinSen/autogpt-plugin-bing/blob/master/README.zh.md)

The Auto-GPT Bing Search Plugin is a useful plugin for the base project, Auto-GPT. With the aim of expand the search experience, this search plugin integrates Bing search engines into Auto-GPT, complementing the existing support for Google Search and DuckDuckGo Search provided by the main repository.

## Key Features:
- Bing Search: Perform search queries using the Bing search engine.

## How it works
If the environment variables for the search engine (`SEARCH_ENGINE`) and the Azure API key (`AZURE_API_KEY`) are set, the search engine will be set to Bing.

## Installation:
1. Download the Auto-GPT Bing Search Plugin repository as a ZIP file.
2. Copy the ZIP file into the "plugins" folder of your Auto-GPT project.

### Azure API Key and Bing Search Configuration:
1. Go to the [Bing Web Search API](https://www.microsoft.com/en-us/bing/apis/bing-web-search-api) website.
2. Sign into your Microsoft Azure account or create a new account if you don't have one.
3. After setting up your account, go to the "Keys and Endpoint" section.
4. Copy the key from there and add it to the `.env` file in your project directory.
5. Name the environment variable `AZURE_API_KEY`.

Example of the `.env` file:
```
SEARCH_ENGINE=bing
AZURE_API_KEY=your_azure_api_key
```

Remember to replace `your_azure_api_key` with the actual API key you obtained from the Microsoft Azure portal.

