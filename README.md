# 인공지능 API 소개
## [목차]
[1. 개요](#1-개요)

[2. 대표적인 인공지능 API](#2-대표적인-인공지능-api)

- [2.1 구글](#21-구글)
- [2.2 네이버](#22-네이버)
- [2.3 카카오톡](#23-카카오톡)

[3. 프로젝트 1에서 활용해 볼 API 선정 및 설명](#3-프로젝트-1에서-활용해-볼-api-선정-및-설명)

***

## 1. 개요
인공지능 API란 특정 기업이나 단체가 제공하는 인공지능 기술을 사용할 수 있는 폴랫폼이다.
***
- a
  - aa
    - aaa
- b
  - bb
    - bbb

- 스타일 적용하기
- **진하게** (`Ctrl + B`)
- *기울이기* (`Ctrl + I`)
- <s>취소선</s> (`Ctrl + D`)
- <u>밑줄</u> 

> 인용문

<details><summary>접고 펴기</summary>
내용 작성하기</details>

***
### 소스코드 넣기
```
#include<stdio.h>
int main()
{
  float a = 1.0;
  float b = 2.0;
  c = a + b;
  print("%d\n", c);
  }
```
```python
sum = 0
for j in range(10):
  sum += 1
print("sum from 1 to 10 : ", sum)
```
```python
import pandas as pd
file_path = "Enter your file path"
df = pd.read_csv(file_path)
df.head()
```
***

## 2. 대표적인 인공지능 API

### 2.1 구글
[Vision API](https://cloud.google.com/vision?utm_source=google&utm_medium=cpc&utm_campaign=japac-KR-all-en-dr-BKWS-all-hv-trial-PHR-dr-1605216&utm_content=text-ad-none-none-DEV_c-CRE_631194514224-ADGP_Hybrid%20%7C%20BKWS%20-%20BRO%20%7C%20Txt%20~%20AI%20&%20ML_Vision%20AI_google%20vision%20api_main-KWID_43700076510377423-aud-1644542956228%3Akwd-151378238431&userloc_1009875-network_g&utm_term=KW_google%20vision%20api&gclid=EAIaIQobChMIzIuDirGSgQMVqwh7Bx052QIHEAAYASAAEgKuwfD_BwE&gclsrc=aw.ds&hl=ko)
- 이미지 크기 조정 불가
![vision_api logo](https://community.appinventor.mit.edu/uploads/default/optimized/3X/2/a/2ad031bc25a55c4d3f55ff5ead8b2de63cdf28bf_2_200x178.png)
- 이미지 크기 조정 가능
<p align="center">
<img src="./vision_api_logo.png" width="200">
</p>

Vision API는 특정 이미지를 인식하여 분류기능을 하는 인공지능 API이다.

[Maps API](https://developers.google.com/maps?hl=ko)

![maps_api_logo](https://play-lh.googleusercontent.com/Kf8WTct65hFJxBUDm5E-EpYsiDoLQiGGbnuyP6HBNax43YShXti9THPon1YKB6zPYpA=w240-h480-rw)

지도를 표시하고 위치 관련 정보를 사용할 수 있는 인공지능 API이다.

### 2.2 네이버
- [papago 번역 API](https://papago.naver.com/)

![papago_api logo](https://cdn-1.webcatalog.io/catalog/naver-papago/naver-papago-icon-filled-256.webp?v=1675613729920)

텍스트 번역을 자동화하고 언어 간 번역을 수행하는 인공지능 API이다.

- [SmartLens API](https://help.naver.com/service/18159/contents/7414?osType=MOBILE&lang=ko)

![smart_lens_api logo](https://blogfiles.pstatic.net/MjAxOTA0MDVfMjE0/MDAxNTU0NDQ0MTY5NzM3.4He4O9Ov2jhCXjfNhSserIcmXLoqTjQJNq6qHZEW0mog.aHj7JeQW_UcMgQuXkn804pEIIVSyRJEw1q3qFqxkrXEg.JPEG.rnjsrldnd123/SE-3cdacde0-a488-4824-8f21-93f5f0929ff2.jpg)

카메라로 대상을 인식하고 그에 대한 정보를 제공하는 인공지능 API이다.

### 2.3 카카오톡
- [텍스트 기반 챗봇 개발 API](https://business.kakao.com/info/chatbot/)

![kakao_api logo](https://www.koreatechtoday.com/wp-content/uploads/2019/03/Screen-Shot-2019-03-21-at-3.14.45-PM-768x562.png)

사용자의 질문에 응답하고 정보를 제공하는 등 다양한 대화 기능을 구현하는 인공지능 API이다.

- [음성 처리 API](https://cs.kakao.com/helps?service=106&category=896&locale=ko)

![kakao1_api logo](https://t1.daumcdn.net/cfile/tistory/99FF8C455C99952627?original)

음성 메시지를 텍스트로 변환하거나 텍스트를 음성으로 변환하는 작업을 수행하는 인공지능 API이다.
***

## 3. 프로젝트 1에서 활용해 볼 API 선정 및 설명

### 선정한 API : 강력한 대화 기능을 구현하고, 사용자와 실시간 상호 작용할 수 있는 챗봇 인공지능 API
- **대화 인터페이스**
  - 사용자와의 자연스러운 대화를 구축하고 유지할 수 있는 인터페이스를 제공하여 이를 통해 사용자의 질문에 응답하고 정보를 제공
- **자연어 처리 (NLP)**
  - 텍스트를 이해하고 분석할 수 있는 자연어 처리 기술을 활용하여 이를 통해 사용자의 입력을 해석하고 의미 있는 답변을 생성
- **기계 학습**
  - 기계 학습 알고리즘을 사용하여 자동으로 학습하며, 대화 데이터를 기반으로 자신을 개선하고, 이는 챗봇이 시간이 지남에 따라 더 나은 대화를 제공할 수 있도록 도움
- **사용자 지정 가능**
  - 개발자가 자신의 요구에 맞게 챗봇을 사용자 정의하고 훈련하여 이는 특정 도메인, 업종 또는 사용 사례에 맞게 챗봇을 개발하는 데 유용
- **멀티모달 지원**
  - 텍스트뿐만 아니라 음성, 이미지, 비디오 등 다양한 형식의 데이터와 상호 작용할 수 있는 기능을 제공
- 보안 및 데이터 프라이버시
  - 사용자 데이터 보안과 프라이버시를 중요하게 생각하며, 데이터 보호에 대한 강력한 보안 기능을 제공
- 비용 및 이용 정책
  - 사용량 또는 구독 모델에 따라 가격이 책정
