
# 👗 Cloth-Cast
## 프로젝트 소개 
**"해외 여행 가는데, 뭐 입어야하지?"**  
Cloth-Cast는 `사용자의 옷장 데이터`, `원하는 분위기`, `위치 기반의 현재 날씨`를 조합해 AI가 옷차림을 추천해주는 서비스입니다.

## 개발 기간 및 팀원

카카오테크 부트캠프 해커톤 팀 프로젝트

2025/02/26 ~ 2025/02/28 (백엔드1, 프론트엔드 및 디자인1(본인), AI 엔지니어2, 클라우드 엔지니어2) 

## 🛠 기술 스택

- **Frontend**: React, TypeScript, styled-components, @react-three/fiber, @react-three/drei
- **Backend**: Java 21, Spring Boot 
- **Database**: MySQL  
- **AI**: FastAPI, ChromaDB / FAISS, OpenAI GPT-4, LangChain

## 아키텍처
<img width="809" alt="스크린샷 2025-02-28 오전 1 16 14" src="https://github.com/user-attachments/assets/bae2b380-3655-4c2a-97e3-48a08ca95f33" />

## ✨ 기능
- (MVP) 사용자 데이터 수집 후 AI 기반 옷차림 추천

## 🚀 서비스 플로우
1. 사용자가 원하는 **스타일링 컨셉**과 **보유한 옷 종류** 입력
   
    ![image (20)](https://github.com/user-attachments/assets/11bf5818-d3a1-410e-baf8-67f5eae3070a)


2. 구글 지도를 통해 사용자가 가고자 하는 위치 정보 입력
   
   ![image 137 (1)](https://github.com/user-attachments/assets/a69cf4d6-d33e-483b-b553-6585e6850eb4)

3. 사용자가 선택한 스타일링 컨셉, 보유한 옷 종류와 위치 정보를 기반으로 조회한 실시간 날씨 정보 조회,
이후 AI는 입력받은 4가지 데이터(스타일링 컨셉, 보유한 옷 종류, 위치 정보, 실시간 날씨 정보)를 기반으로 맞춤형 스타일링 추천 로직 실행

![3-1](https://github.com/user-attachments/assets/9603b8d0-1e73-43d3-95d3-fd57067a70b3)
![image (20)](https://github.com/user-attachments/assets/fa66926e-ee67-4f33-bbae-e98cbf7b274b)


## 🎥 시연 영상

👉 [Cloth-Cast 시연 영상 보러가기](https://youtu.be/2PhzlGpM4A8?feature=shared)

## ⚙️ 프로젝트 시작 방법

1. 클론
```bash
git clone https://github.com/hyemimi/clothcast-frontend
```
2. 파일 이동
```bash
cd clothcast-frontend
```
3. 의존성 설치
```bash
npm install
```
4. 개발 서버 시작
```bash
npm run dev
```



