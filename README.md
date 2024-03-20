# ✒️서울 지역구별 범죄건수와 경찰서 또는 CCTV의 상관관계 분석
## 👥 Team
- Team name : HEE
- Team members : 함은규, 이수현, 이지우
- * :clock1:시작일 : 2024.02.26(월)
  * ⏰목표일 : 2023.12.11(월)
## :books: skill
- **Programming** <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> <img src=https://simpleicons.org/icons/pandas.svg>
- **Tools** <img src="https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"> <img src="https://img.shields.io/badge/googlecolab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white">
- **Git** <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=jupyter&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">

## 목차(INDEX)
&emsp;&ensp;Ⅰ. 주제 선정</br>&emsp;&ensp;Ⅱ. Data preprocessing</br>&emsp;&ensp;Ⅲ. 시각화</br>&emsp;&ensp;Ⅳ. 결론</br>&emsp;&ensp;

## Ⅰ. 주제선정
  **1. 대화형 AI Chatbot 서비스 구현**</br>
       &nbsp;&nbsp;&nbsp; 1) 관련된 다양한 질문과 상황을 제공함으로써 정확하고 신속한 응답을 제공하는게 목표</br>
       &nbsp;&nbsp;&nbsp; 2) 고객의 문의에 신속, 정확하게 답변할 수 있는 시스템 구축</br>
       
  **2. 자료출처**</br>
       &nbsp;&nbsp;&nbsp; Dacon https://dacon.io/competitions/official/236216/overview/description/

## Ⅱ. Data preprocessing & Modeling
**1. 데이터 전처리**</br>
       &nbsp;&nbsp;&nbsp; 1) DataFrame 변경 (id, category 삭제)</br>
       &nbsp;&nbsp;&nbsp; 2) Dataset 증강 (기존 카테고리를 제외하고 다른 카테고리 질문을 추가)</br>
       &nbsp;&nbsp;&nbsp; 3) Tokenizer</br>
       
**2. 모델 학습**</br>
       &nbsp;&nbsp;&nbsp; 1) skt, kykim, kakao : Fine-tuning</br>
       &nbsp;&nbsp;&nbsp; 2) edentns, LDCC : QLoRA</br>
       &nbsp;&nbsp;&nbsp; 3) RAG</br>

  - 최종 모델 SKT 사용

## Ⅲ. Chatbot 구현
**1. 챗봇 서비스**</br>
       &nbsp;&nbsp;&nbsp; 1) Streamlit 사용</br>
       &nbsp;&nbsp;&nbsp; 2) speech_recognition 모듈 사용으로 대화형 챗봇 서비스 구현</br>
       &nbsp;&nbsp;&nbsp; 3) 웹 배포</br>
