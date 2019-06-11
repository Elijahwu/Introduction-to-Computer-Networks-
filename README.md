# chat-room

Chat-Room Use Python Socket.IO

* [Youtube Demo](https://youtu.be/l53-K03hIXs)
* [線上 Demo](http://chatflask.herokuapp.com/)

P.S
目前佈署在 [heroku](https://dashboard.heroku.com/) 上，因為免費版有24小時一定要休息6小時的規定，所以比較慢請多多包涵。

Heroku 上 database 是使用 Heroku Postgres，本地端測試可以直接使用SQLITE，

如果 server (demo) 自動重啟，圖片可以會遺失。

聊天室，相信大家一定經常看到，今天教你使用 [python-socketio](https://github.com/miguelgrinberg/python-socketio) 打造一個簡易的聊天室。

使用 Python [Flask](http://flask.pocoo.org/) 搭配 [python-socketio](https://github.com/miguelgrinberg/python-socketio) 建立聊天室

## 特色

* [python-socketio](https://github.com/miguelgrinberg/python-socketio) 即時聊天室。
* 透過 [flask-login](https://github.com/maxcountryman/flask-login) 實現簡易登入、註冊。

## 安裝套件

確定電腦有安裝 [Python](https://www.python.org/) 之後

請在  cmd (命令提示字元) 輸入以下指令

``` cmd
pip install -r requirements.txt
```

## 執行畫面

簡單的登入、註冊
![alt tag](http://i.imgur.com/XiNxpEQ.jpg)
![alt tag](http://i.imgur.com/4FoQskT.jpg)

聊天室

![alt tag](http://i.imgur.com/ghdeqF7.jpg)

點選照片下方的齒輪，可以上傳自己的照片
![alt tag](http://i.imgur.com/316KdGN.jpg)

## video streaming
簡單的串流視訊

## record
按下視訊上方的 record 鍵，即可開始錄影
按下視訊上方的 Stop 鍵，則結束錄影
旁邊會跳出影片的下載連結
server 端也會保留 此影片

## 執行環境

* Python 3.4.3

## Reference

* [python-socketio](https://github.com/miguelgrinberg/python-socketio)
* [flask-login](https://github.com/maxcountryman/flask-login)
* [pillow](https://pillow.readthedocs.io/en/4.0.x/)
* [croppic](http://www.croppic.net/)
* [聊天室版型](http://www.bypeople.com/minimal-css-chat-ui/)

## License

MIT license
