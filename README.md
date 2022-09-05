# M5Stack-Remote-Ctrl-Sample

* ソースの「mqtt-config.h」を適切なものに書き換えます
* 「M5Stack-Remote-Ctrl-Sample」をM5Stackに書き込みます
* サーバーにてServer/main.pyを以下のコマンドで実行します
```
uvicorn main:app --port=8000 --host=0.0.0.0 --reload
```
* postmanなどでwebAPIを発行します
```
http://iot-tech-lab.com:8000/
```
* servoが動けばOKです