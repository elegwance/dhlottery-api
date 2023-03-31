# DongHaeng Lottery API (Unofficial)

[동행복권](https://dhlottery.co.kr/) 사이트를 터미널에서 이용할 수 있게 랩핑한 API입니다.

## 구현된 기능

- [로또 6/45](https://dhlottery.co.kr/gameInfo.do?method=gameMethod&wiselog=H_B_1_1)
  - 자동 구매 1 ~ 5장

## 설치 및 사용법

```sh
pip install dhapi
dhapi -U $YOUR_ID -P -K lotto645 -T buy -M auto -C 5  # 로또645를 - 산다 - 자동발급으로 - 5장 
```

## 기여하기

기여는 대환영입니다! [CONTRIBUTING.md](/docs/CONTRIBUTING.md) 파일을 참고해주세요.
