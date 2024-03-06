# IEX_historical-prices

IEX 에서 미국 개별 주식의 분봉 데이터를 받아오는 프로그램입니다.
가져온 데이터는 .csv파일로 저장됩니다.

This repo contains a script for downloading historic intraday OHCL data from IEX: with Python, asynchronously, via API and for free. 
Please see the following *Towards Data Science* post for set up instructions: 

https://towardsdatascience.com/how-to-download-all-historic-intraday-ohcl-data-from-iex-with-python-asynchronously-via-api-b5b04a31b187

## config.json
```
{
"TOKEN": "sk_3dlafjdslfjeuroiewursdlkjf85428bdee5"
}
```
- IEX 회원가입 후 token 생성필요

## 실행
- python download_IEX.py
