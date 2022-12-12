# 프로젝트 요약

```
검색창 구현 +  DB에 담긴 데이터를 불러와 검색어 추천 기능 구현을 합니다. typeScript를 연습해보기 위해 써보았습니다.
```



### 📆 기간

#### 22년 11월 05일 ~ 22년 11월 07일

---

### 🔧 기술 스택

<div align=center> 
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"/> 
  <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=black"/>   
 <img src="https://img.shields.io/badge/styled_components-3U7U2U?style=for-the-badge&logoColor=black"/> 
  <img src="https://img.shields.io/badge/react_router-FFAA04?style=for-the-badge&logo=css&logoColor=black"/> 
</div>

---

### 💻 실행 방법

1.  라이브러리를 설치합니다.

```
npm install
```

2. 클라이언트 폴더로 이동합니다. (/pre-onboarding-7th-3-1-10 )

```
 npm start
```
3. 서버 폴더로 이동합니다 (/assignment-api_7th)

```
 npm start
```

## 프로젝트 설명

<details>
<summary>  📂 디렉토리 구조</summary>
<div markdown="1">

```
 업데이트 예정입니다.
```

</div>
</details>

<details>
<summary>🧻 요구사항</summary>
<div markdown="1">

- 질환명 검색시 API 호출 통해서 검색어 추천 기능 구현
    
   - 사용자가 입력한 텍스트와 일치하는 부분 볼드처리
        - 예)
            - 사용자 입력: 담낭
            추천 검색어:  **담낭**의 악성 신생물, **담낭**염, **담낭**의 기타 질환, 달리 분류된 질환에서의 **담낭**, 담도 및 췌장의 장애
    - 검색어가 없을 시 “검색어 없음” 표출
- API 호출 최적화
    - API 호출별로 로컬 캐싱 구현
        - 캐싱 기능을 제공하는 라이브러리 사용 금지(React-Query 등)
        - 캐싱을 어떻게 기술했는지에 대한 내용 README에 기술
    - 입력마다 API 호출하지 않도록 API 호출 횟수를 줄이는 전략 수립 및 실행
        - README에 전략에 대한 설명 기술
    - API를 호출할 때 마다 `console.info("calling api")` 출력을 통해 콘솔창에서 API 호출 횟수 확인이 가능하도록 설정
- 키보드만으로 추천 검색어들로 이동 가능하도록 구현
    - 사용법 README에 기술

### 요구 사항

</div>
</details>

<details>
<summary>❓ 해결 중인 오류</summary>
<div markdown="1">

```
- 검색 시, 키워드만 강조를 해야하는데, 전체 글이 전부 강조가 되고있습니다.

- 이벤트 리스너안에, useState값을 변경하다 생긴 에러가 있습니다.  
```

</div>
</details>



### 사용한 라이브러리 및 API, CDN 등
- axios
- styled-components
- react-router
- typescript
---






