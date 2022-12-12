# Telegram Message Analysis
The analysis of messages from telegram

ipython notebook has all analyses.

It is can be run via Jupiter Notebook or imported into Google Colab

In order to get messages from Telegram
Please follow these steps:

1. Install a tool (download, go through the steps in the How to run section)
https://github.com/SanGreel/telegram-data-collection

2. Get Telegram API credentials
https://my.telegram.org/apps

3. Set credentials (api_id, api_hash) in config/config.json (should be based on the
config_example.json)

4. Download all dialogues, save the time spent on this activity.
`python 0_download_dialogs_list.py --dialogs_limit -1`

5. Download dialogues data, save the time spent on this activity.
`python 1_download_dialogs_data.py --dialogs_ids -1 --dialog_msg_limit -1
