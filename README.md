# LINE BOT 教學倉庫

這個倉庫包含了一系列的 Jupyter Notebook 文件，旨在教導如何使用 Python 開發 LINE BOT。透過這些練習，您將學會如何建立並串接 LINE BOT，並且能夠實現各種有趣的應用，如自動回覆訊息、儲存圖片或影片、串接 OpenAI ChatGPT 等。

## 目錄

### 0-LINE BOT 教學.ipynb
介紹整個教學系列的目標和內容，包含環境安裝與設定、解析與傳送 LINE 訊息、訊息類型與圖文選單、實戰 LINE BOT、串接 Google 雲端硬碟、串接 Dialogflow、串接 OpenAI ChatGPT 等。

### 1-發送 LINE Notify 通知.ipynb
教學如何使用 LINE Notify API 發送通知訊息到指定的 LINE 群組或個人。

### 2-建立 LINE Channel.ipynb
介紹如何在 LINE Developers 平台上建立一個新的 LINE Channel，並獲取必要的 Channel ID、Channel Secret 和 Access Token。

### 3-建立基本的 LINE BOT.ipynb
教學如何建立一個基本的 LINE BOT，並實現簡單的回覆功能。

### 4-建立並串接 Webhook.ipynb
介紹如何建立並串接 Webhook，讓 LINE BOT 能夠接收並處理來自使用者的訊息。

### 5-解析 LINE 的訊息.ipynb
教學如何解析來自 LINE 的訊息，並提取其中的有用資訊。

### 6-自動回覆訊息.ipynb
介紹如何實現 LINE BOT 自動回覆使用者訊息的功能，設定回覆的邏輯和訊息處理流程。

### 7-主動推播訊息.ipynb
教學如何使用 LINE Messaging API 主動推送訊息給使用者，而非僅回覆使用者的輸入訊息。

### 8-建立圖文選單.ipynb
介紹如何建立圖文選單，讓使用者能夠透過選單進行互動，實現更豐富的 LINE BOT 互動體驗。

### 9-切換圖文選單.ipynb
教學如何實現圖文選單的動態切換功能，根據不同情境或使用者操作提供不同的選單介面。

### 10-發送樣板訊息.ipynb
教學如何使用 LINE Message API 發送樣板訊息，包含按鈕樣板、確認樣板、輪播樣板等。

### 11-發送 Flex Message.ipynb
介紹如何使用 Flex Message API 發送自定義的訊息格式，讓訊息內容更加豐富和靈活。

### 12-使用 Requests 傳送訊息.ipynb
教學如何使用 Python 的 Requests 函式庫來傳送 HTTP 請求，實現與 LINE Message API 的互動。

### 13-使用 LINE URL Scheme.ipynb
介紹如何使用 LINE URL Scheme 來實現一些特殊功能，如打開 LINE 聊天、加入好友等。

### 14-儲存使用者傳送的圖片或影片.ipynb
教學如何接收並儲存使用者透過 LINE BOT 傳送的圖片或影片，並將其保存到伺服器上。

### 15-串接 Email，寄送使用者的圖片或影片.ipynb
介紹如何將儲存的圖片或影片透過 Email 寄送給指定的收件人。

### 16-透過 LINE 上傳圖片到 Google 雲端硬碟.ipynb
教學如何將使用者透過 LINE BOT 傳送的圖片上傳到 Google 雲端硬碟，實現雲端備份。

### 17-氣象機器人 (1) - 雷達回波與地震資訊.ipynb
介紹如何開發一個氣象機器人，能夠提供雷達回波和地震資訊。

### 18-氣象機器人 (2) - 目前氣象資訊.ipynb
教學如何讓氣象機器人提供目前的氣象資訊，如溫度、濕度等。

### 19-氣象機器人 (3) - 天氣預報和空氣品質.ipynb
介紹如何讓氣象機器人提供天氣預報和空氣品質資訊。

### 20-氣象機器人 (4) - 加入圖文選單和部署程式.ipynb
教學如何為氣象機器人加入圖文選單，並將程式部署到伺服器上。

### 21-LINE BOT 串接 Dialogflow ( 基本串接 ).ipynb
介紹如何將 LINE BOT 串接到 Google Dialogflow，實現基本的自然語言處理功能。

### 22-LINE BOT 串接 Dialogflow ( 搭配外部 Webhook ).ipynb
教學如何搭配外部 Webhook，讓 Dialogflow 能夠處理更複雜的邏輯和回應。

### 23-LINE BOT 串接 Dialogflow ( 氣象聊天機器人 ).ipynb
教學如何建立一個氣象聊天機器人，透過串接 Dialogflow 讓使用者能查詢天氣預報，並接收自然語言的天氣查詢回應。

### 24-LINE BOT 串接 Dialogflow ( 接收表情貼圖 )
介紹如何設定 LINE BOT 來接收並處理使用者傳送的表情貼圖，並根據貼圖的種類進行自動回覆。

### 25-LINE BOT 串接 OpenAI ChatGPT ( 讓 AI 回覆訊息 ).ipynb
介紹如何將 LINE BOT 串接到 OpenAI ChatGPT，讓 AI 能夠自動回覆訊息。

### 26-LINE BOT 串接 OpenAI ChatGPT ( 翻譯機器人 ).ipynb
教學如何讓使用者透過自訂指令來控制 ChatGPT 的回應。

### 27-LINE BOT 串接 OpenAI ChatGPT ( 上下文歷史紀錄 ).ipynb
教學如何使用 Firebase Realtime Database 儲存聊天歷史紀錄，讓 ChatGPT 能夠根據上下文進行回應。

## 如何開始

1. 克隆這個倉庫到本地端：
    ```sh
    git clone <倉庫網址>
    ```
2. 安裝所需的 Python 函式庫：
    ```sh
    pip install -r requirements.txt
    ```
3. 按照每個 Notebook 的教學步驟進行操作。
