# これはなに？

motion (WebCam server) on Docker on Hypriot on Raspberry Pi

# 起動方法

```bash
$ git clone https://github.com/taturou/raspi-hypriot-motion.git
$ cd raspi-hypriot-motion
$ docker-compose up -d
```

# アクセス方法

Webブラウザで以下にアクセス。
* `http://{raspi-ip-address}:8080` : motion設定ページ
* `http://{raspi-ip-address}:8081` : ストリーミングページ
