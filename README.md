# YouTube Chat Render
This utility allows you to get YouTube chat in video format

# Chat Render Example
![Sample result](https://github.com/Osnova-Osnov/YouTube-Chat-Render/blob/master/example/result.gif)

# Installation
1. Unzip `emotes.zip` into the same folder as the project
2. Install [Node.js](https://nodejs.org/) v20 or newer.
3. Download the repository:
```bash
git clone https://github.com/Osnova-Osnov/YouTube-Chat-Render.git
cd YouTube-Chat-Render
```
4. Open a terminal or command prompt and install `express` if it is not already installed:
```bash
npm install express
```
5. Start the server:
```bash
node server.js
```

# Usage

![image](https://github.com/user-attachments/assets/f35f91a2-1efb-42f6-b143-130968618d3b)

1. Prepare a file with messages from the chat. (csv file with timestamp,author,message fields).<br>
   [Sample file](https://github.com/Osnova-Osnov/YouTube-Chat-Render/blob/master/example/yt-messages.csv).<br>
   
   If you are using [chat-downloader](https://github.com/xenova/chat-downloader), you can download this Python script that will help you convert the JSON file from chat-downloader to a compatible CSV format
   
3. Open in browser:
```bash
http://localhost:8080
```
3. Fill in the fields, upload the prepared files (for **emotes** field use `yt-emotes_local.txt`), and click render
