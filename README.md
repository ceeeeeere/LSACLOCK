睿智縫合鬧鐘
===============

動機與目的
---------------
我們覺得鬧鐘只能發出「鈴鈴鈴」的聲音覺得很單調，為什麼不能語音說出現在時間呢？為什麼不能跟我們玩一些遊戲呢？



功能
---------------
* 溫溼度檢測
* 猜數字遊戲
* telegram bot控制&聊天


使用資源
---------------

|      設備名稱      | 數量 |  來源  |
|      :-----:      | :--: |  :--: |
|  Raspberry pi 3   |  1   |  moli |
|      DHT22        |  1   |  冠鈞  |


python
telegram
* 以下指令請在虛擬機上執行
* (tlelgram bot，不確定有沒有漏)\
sudo apt install python\
sudo apt install git\
sudo apt install make\
git clone https://github.com/pyenv/pyenv.git ~/.pyenv
* (聲控環境，不確定有沒有漏)
pip3 install SpeechRecognition\
pip install gtts\
pip install googletrans==3.1.0a0\
pip install pygame\
pip install pyaudio


實作過程
---------------
* 天氣預報
* 報時
* 猜數字\
* telegram bot
    1.申請telegram bot
    2.申請openai key
    3.取得telegram user id
    4.找到可以運行在telegram bot上的ai程式碼(耗時15小時以上)
    5.修改並添加內容到自己的bot上(尚未完工)

使用方法
---------------
* telegram bot
    1.取得自己的bot(使用以下連結向BOT Father申請)
    https://t.me/BotFather
    2.取得自己的bot token id(向BOT Father申請)
    3.取得自己的user id
    https://telegram.me/getidsbot
    5.申辦openai帳號並取得openai key
    https://beta.openai.com/account/api-keys
    6.將這個git上的檔案抓下來
    7.修改.py檔案，將註解中寫的需要openai key、user id、bot token填入
遇到問題
---------------

分工表
---------------
* 陳彥豪
* 蔡鎮洋
* 張翌然
* 陳冠鈞
* 吳健瑋

Reference
---------------

https://opendata.cwb.gov.tw/index
