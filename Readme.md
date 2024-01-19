# ViChat

Vichat is a Vim plugin for predicting text with OpenAI's GPT-4 model.

## Installation

1. Download the latest version of the plugin from the [GitHub repository](https://github.com/zetier/vichat).
2. Unzip the downloaded file.
3. Copy the `vichat.vim` file into your `~/.vim/plugin` folder.
4. Set the `OPENAI_API_TOKEN` environment variable with your OpenAI API token.

## Usage

Once the plugin is installed, you can use the `gpt` command to predict text with GPT-4.

To use the command, highlight the text you want to use as the prompt, then enter `gpt`. You will then be asked to enter some additional optional text for GPT-4.

Once you enter the additional text, GPT-4 will generate the predicted text and you will be asked if you want to replace or insert the output.

## OpenAI setup

The plugin accesses OpenAI's API. Note that this is different than ChatGPT. Goto openai.com and select API:
![image](https://github.com/zetierminat0r/ViChat/assets/157128602/447686b9-3e32-494b-9a40-765c202a1181)

Click on the logo and you can find the API keys there:
![image](https://github.com/zetierminat0r/ViChat/assets/157128602/dce4e242-2d37-4ae7-bed8-463ca2301508)

Setup billing. With each access to the API, they will charge your account depending on which model you select. As of this writing it is aroun 10 cents per request. YMMV. 
![image](https://github.com/zetierminat0r/ViChat/assets/157128602/8b4c7dd4-543f-4418-8561-7e89d920e1f1)

## License

This plugin is released under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for details.

