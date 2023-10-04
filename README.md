# Quantified ChatGPT

### Dialogue Repository, Data Analysis and Data Visualization for ChatGPT Export

"Quantified ChatGPT" is an open-source Jupyter Notebook tool designed to help you gain insights into your interactions with ChatGPT. Convert your ChatGPT conversation history into human-readable exports (in markdown), structured data (i.e. csv). Then analyze and visualize your chat data for a better understanding of your dialogues and a repository for quantifying your interactions with ChatGPT over time. 

### Code / Dependencies: 

* The code is written in Python 3. 
* Shared and distributed via Jupyter Notebooks. 
* View detailed [Installation Notes on QS Ledger Github project](https://github.com/markwk/qs_ledger).
* Note: There are a few added libraries you should `pip install` - Additional Docs/Help 😈 COMING SOON 🎉


### Basic Usage / Quickstart

- Export your ChatGPT history and data following OpenAI's documentation [here](https://help.openai.com/en/articles/7260999-how-do-i-export-my-chatgpt-history-and-data).
- Extract ZIP. 
- Place the file `conversations.json` into `data` directory such that the file is available at `data/conversations.json`
- First run `chatpt_data_parser.ipynb` using either jupyter notebook or jupyter lab which will convert your raw JSON file into a simple CSV/spreadsheet. [Markdown converter coming soon]
- Second run `chatpt_data_analysis.ipynb` for data analysis, data visualization and some charts on your ChatGPT utilization. 

### Sample Outputs

![](https://raw.githubusercontent.com/markwk/quantified_chatgpt/master/output/chatgpt-messages-wordcloud.png)

![](https://raw.githubusercontent.com/markwk/quantified_chatgpt/master/output/chatgpt-most-messaged-conversations.png)

![](https://raw.githubusercontent.com/markwk/quantified_chatgpt/master/output/chatgpt-messages-per-month.png)

![](https://raw.githubusercontent.com/markwk/quantified_chatgpt/master/output/chatgpt-messages-per-day.png)

#### Creators and Contributors: 

* [Mark Koester](https://github.com/markwk/) - blogs about tech and data-driven life at [www.markwk.com](http://www.markwk.com)

**Want to help?** Fork the project and provide your own data analysis, integration, etc.   

## Questions? Bugs? Feature Requests? Need Support?

Post a ticket in the [Quantified ChatGPT Issue Queue](https://github.com/markwk/quantified_chatgpt/issues) 