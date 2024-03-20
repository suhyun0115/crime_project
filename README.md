# ✒️서울 지역구별 범죄건수와 경찰서 또는 CCTV의 상관관계 분석
## 👥 Team
- Team name : HEE
- Team members : 함은규, 이수현, 이지우
- * :clock1:시작일 : 2024.02.26(월)
  * ⏰목표일 : 2023.12.11(월)
## :books: skill
- **Programming** <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"><img src="https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=Matplotlib&logoColor=white"><img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=Seaborn&logoColor=white"><img src="https://img.shields.io/badge/Folium-3776AB?style=for-the-badge&logo=Folium&logoColor=white">
- **Tools** <img src="https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"> <img src="https://img.shields.io/badge/googlecolab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white">
- **Git** <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=jupyter&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">

## 목차(INDEX)
&emsp;&ensp;Ⅰ. 주제 선정</br>&emsp;&ensp;Ⅱ. Data preprocessing</br>&emsp;&ensp;Ⅲ. 시각화</br>&emsp;&ensp;Ⅳ. 결론</br>&emsp;&ensp;

## Ⅰ. 주제선정
  **1. 서울지도에 구별 범죄율과 경찰서 위치, CCTV비율을 표기**</br>
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

## Ⅲ. 최종결론
**1. 챗봇 서비스**</br>
       &nbsp;&nbsp;&nbsp; 1) Streamlit 사용</br>
       &nbsp;&nbsp;&nbsp; 2) speech_recognition 모듈 사용으로 대화형 챗봇 서비스 구현</br>
       &nbsp;&nbsp;&nbsp; 3) 웹 배포</br>

## IV. 자료출처
 &nbsp;&nbsp;&nbsp; 1) 범죄율 : https://data.seoul.go.kr/dataList/316/S/2/datasetView.do</br>
 &nbsp;&nbsp;&nbsp; 2) 경찰서 : https://www.data.go.kr/data/15054711/fileData.do</br>
 &nbsp;&nbsp;&nbsp; 3) 주소 GPS 변경 : 카카오API (https://developers.kakao.com/)</br>
 &nbsp;&nbsp;&nbsp; 4) CCTV위치 : https://www.bigdata-policing.kr/product/view?product_id=PRDT_468</br>
 &nbsp;&nbsp;&nbsp; 5) 서울 지역구별 지방세 : https://data.seoul.go.kr/dataList/DT201004O140020/S/2/datasetView.do</br>
 &nbsp;&nbsp;&nbsp; 6) 서울 지역구별 인구 : https://data.seoul.go.kr/dataList/419/S/2/datasetView.do</br>
      
