# 라즈베리파이3 안드로이드 OS 설치
> 안드로이드 OS를 설치해보자

![](../header.png)
## 사전준비

Raspberry pi 3 Model B
Android OS Download : https://konstakang.com/devices/rpi3/

How to install:

Follow the official Raspberry Pi instructions for writing the image to the SD card.
  └ https://www.raspberrypi.org/documentation/installation/installing-images/windows.md


```sh
윈도우키 + R > systdm.cpl ,3
```
![image](https://user-images.githubusercontent.com/16375921/121686096-b52a9180-cafb-11eb-9cab-2ee8eb1e72f1.png)

vscode framework 설치:

```sh
go get -u github.com/labstack/echo/...
```

## Troubleshooting

"github.com/... " 패키지 import 에러 발생
```sh
go env -w GO111MODULE=auto
```

## vscode 플러그인
```sh
GitLens : git 관리
Git History : commit/push 이력 관리
```
