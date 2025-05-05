# minebot
이건 디스코드봇인 minebot의 주식 파일 및 모듈입니다.

# 사용법
import asyncio
import minebot

data = asyncio.run(minebot.getapi())
print(data) #현재 주식 가격을 출력함
