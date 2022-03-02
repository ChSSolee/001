## 📌 신문사별 실시간 뉴스의 단어 출현 빈도 시각화
> #### 개요 : 웹 크롤링 (web crawling), 스크래핑 (scraping), 파싱 (parsing) 방법을 활용하여, 6개 신문사의 실시간 뉴스를 수집하고 전처리를 거쳐서 상위 50개 단어의 출현 빈도를 시각화 및 비교.
<img width="300" height="300" src="https://user-images.githubusercontent.com/100699925/156298018-5df5d3fe-d266-47c7-a63f-c90586159dd7.png">

#

### 1. 제작 기간 & 참여 인원
> #### 2020.11 ~ 2020.12
> #### 3인
> #### 수행 역할 
>> 2020년 12월 4일 20시 15분을 기준, 할당된 언론사 포털의 실시간 뉴스에 대한 웹 크롤링  
>> 스크래핑, HTML 파싱, 전처리, TermDocumentMatrix 생성, Word Cloud 생성 
>> 분석 결과 취합 및 보고서 작성

> #### 배운점
>> #### 처음으로 비정형 데이터에 대한 수집과, 전처리, 분석 및 시각화를 수행하였고, R 프로그램 코딩 당시 에러가 잦게 발생하는 등의 어려움이 있었습니다. 
>> #### 하지만 프로젝트를 진행하면서 자연어 처리를 비롯하여, 텍스트 마이닝을 구성하는 Dictionary, Corpus, TDM등의 절차와 개념을 학습하며 실습할 수 있었던 좋은 기회 였습니다.

#

### 2. 사용 프로그램 : R 3.6.0
#### 사용 라이브러리 : 
> library(RSQLite)  
> library(KoNLP)  
> library(tm)  
> library(wordcloud)  
> library(httr)  
> library(rvest)  
> library(XML)  

#

### 3. 제출물 : https://docsconv.malangmalang.com/hermes/resource/store/c9/9b/43c3cc24d4d3d458de5d9a2939c82da72635/hview.html
> #### R 코드 : https://github.com/ChSSolee/001/blob/main/%EC%9B%B9%20%ED%81%AC%EB%A1%A4%EB%A7%81%20%26%20%EC%9B%8C%EB%93%9C%20%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C.R
