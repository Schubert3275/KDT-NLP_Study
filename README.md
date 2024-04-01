## Natural Language Processing

<details>
<summary>사용 교재</summary>

![](./images/파이토치%20트랜스포머를%20활용한%20자연어%20처리와%20컴퓨터비전%20심층학습.png)

</details>

### DAY01

---

<details>
<summary> 자연어 처리 </summary>

> -   사람들의 의사소통에 사용되는 언어를 자연어라고 칭함
> -   기계에서 자연어를 분석&이해&생성&처리하는 기술이 NLP
> -   1960년 말뭉치(Corpus) 데이터 활용 통계적 자연어 처리
> -   최근 Deep Learning 기술로 번역&자연어 생성

</details>
<details>
<summary> 자연어 처리 영역 </summary>

> -   번역
> -   감정분석
> -   스팸 분류
> -   이미지 설명
> -   텍스트 요약
> -   질문에 대한 응답
> -   챗봇 텍스트 생성

</details>
<details>
<summary> 자연어 처리 프로세스 </summary>

> -   자연어 데이터 수집
> -   형태소 분석
> -   구분 분석
> -   의미 분석
> -   화용 분석

</details>
<details>
<summary> 형태소 분석 </summary>

> -   자연어를 문장의 최소 단위인 형태소 단위로 분할, 품사 판별
> -   분석 : 어간 추출, 원형 복원, 품사 부착
> -   활용 : 기계 번역, 텍스트 마이닝 등
> -   영어권 분석 방법 -> 띄어쓰기(공백) 기준 구분
> -   아시아권 분석 방법 -> 문법 규칙 방법, 확률적 언어 모델 방법
> -   코퍼스(Corpus) -> 자연어처리 위해 모아놓은 텍스트 묶음
> -   토큰
> -   어휘 집합

</details>
<details>
<summary> 전처리 단계 </summary>

> -   토큰화 : 말뭉치에서 의미있는 단위(토큰)로 분리
> -   정제 : 토큰화 작업 전/후 작업에 방해되는 부분을 배제
> -   정규화 : 표현 방법이 다른 단어 통합하여 같은 단어 생성
> -   벡터화/수치화 : 컴퓨터가 처리할 수 있는 수치 형태로 변환
> -   패딩 : 동일한 길이로 문장/문서를 맞추는 작업

</details>
<details>
<summary> 언어 모델 </summary>

> -   단어 시퀀스(문장)에 확률을 할당하는 모델
> -   통계를 이용한 통계적 언어 모델(Statistical Language Model)
> -   기계학습을 이용한 인공 신경망 언어 모델(RNN, LSTM, ...)

</details>
<details>
<summary> 통계적 언어 모델 </summary>

> -   전통적인 접근 방법 언어 모델
> -   조건부 확률 기반 -> 희소 문제 해결 불가능

</details>
<details>
<summary> N-gram </summary>

> -   전체 문장에서 단어를 N개수만큼 묶은 것
> -   카운트에 기반한 통계적 접근 사용
> -   N개의 단어만 고려하여 판단 -> 조합의 경우의 수가 엄청나게 많기에 희소 문제 해결 한계 존재

</details>

---

| 파일명                  | 내용              |
| ----------------------- | ----------------- |
| `DAY_01\ex_bow.ipynb`   | sklearn 언어 모델 |
| `DAY_01\ex_token.ipynb` | 토큰화            |

### DAY02

---

<details>
<summary> 전처리 및 토큰화 </summary>

> -   말뭉치 전처리
> -   토큰화

</details>

---

| 파일명                         | 내용                   |
| ------------------------------ | ---------------------- |
| `DAY_02\ex_korpora.ipynb`      | 자연어 데이터셋 전처리 |
| `DAY_02\ex_naver_review.ipynb` | 영화 리뷰 토큰화       |

### DAY03

---

<details>
<summary> 토크나이저 </summary>

> -   soynlp
> -   ckonlpy

</details>

---

| 파일명                       | 내용                         |
| ---------------------------- | ---------------------------- |
| `DAY_03\ex_soynlp.ipynb`     | 학습 기반 토크나이저 soynlp  |
| `DAY_03\ex_similarity.ipynb` | TF-IDF 기반 추천 시스템 구현 |

#### DAY03 실습과제

---

    1.
