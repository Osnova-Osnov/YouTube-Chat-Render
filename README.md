# YouTube Chat Render
This utility allows you to get YouTube chat in video format

# Chat Render Example
![Sample result](https://github.com/Osnova-Osnov/YouTube-Chat-Render/blob/master/example/result.gif)

# Installation
1. Install [Node.js](https://nodejs.org/) v20 or newer.
2. Download the repository:
```bash
git clone https://github.com/Osnova-Osnov/YouTube-Chat-Render.git
cd YouTube-Chat-Render
```
3. Open a terminal or command prompt and install `express` if it is not already installed:
```bash
npm install express
```
4. Start the server:
```bash
node server.js
```

# Usage

![image](https://github.com/user-attachments/assets/f35f91a2-1efb-42f6-b143-130968618d3b)

1. Unzip `emotes.zip` into the same folder as the project
2. Prepare a file with messages from the chat. (csv file with timestamp,author,message fields).<br>
   [Sample file](https://github.com/Osnova-Osnov/YouTube-Chat-Render/blob/master/example/yt-messages.csv).
   
4. Open in browser:
```bash
http://localhost:8080
```
4. Fill in the fields, upload the prepared files (for **emotes** field use `yt-emotes_local.txt`), and click render
