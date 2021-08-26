# WebMailSystem
JamesWebMail을 기반으로 웹메일 시스템 만들기

|역할|학과|학번|이름|
|---|---|---|---|
팀 장	|소프트웨어공학과	|20173179	|심지훈|
팀원1	|소프트웨어공학과	|20173184	|김주의|
팀원2	|소프트웨어공학과	|20153263	|박민철|
팀원3	|소프트웨어공학과	|20173165	|신희원|
팀원4	|소프트웨어공학과	|20143227	|이동준|

## 분류
- 1_REPORT

    프로젝트 계획서, 결과 보고서, PPT

- 2_ MEETING

    주차별 회의록

- 3_ PROJECT

     소스코드

## 개요
JamesWebMail을 기반으로 하여 기존의 웹메일 시스템을 유지보수해서 완성도가 보다 높은 프로그램 제작

## 목표
- JSP 기반 프로그램 개발 능력 향상
- SMTP, POP3 시스템 이해
- 유지보수 개념 이해
- 요구사항 위주의 프로그램 개발 능력 향상

## 구현
### 0. 프로그램 시퀀스 다이어그램
![image](https://user-images.githubusercontent.com/49029096/130941898-0c1fd8a6-0ca1-4990-87ea-8671b38b543d.png)


### 1. 교정 유지보수
유지 보수 목록 나열 후 기존의 불필요한 코드 제거 및 가독성이 떨어지는 코드 수정
![image](https://user-images.githubusercontent.com/49029096/130942021-ff0fe236-f984-42cd-8b17-0f02dd09e385.png)

수정 전

![image](https://user-images.githubusercontent.com/49029096/130942266-af333e5e-c823-4f7c-8c54-d01858810b56.png)

수정 후

![image](https://user-images.githubusercontent.com/49029096/130942381-f41527f8-afd8-4f3c-8a05-b4ef68f01a42.png)
![image](https://user-images.githubusercontent.com/49029096/130942288-677e9e9f-c302-4641-93b5-262b0b75dbe9.png)

### 2. 적응 유지보수
기존 웹에서 미티리얼 디자인 적용으로 반응형 웹 구현

기존 웹 디자인
![image](https://user-images.githubusercontent.com/49029096/130942651-1d3016f9-3c82-4668-94d3-4bfa60ab1716.png)

수정 후 웹 디자인
![image](https://user-images.githubusercontent.com/49029096/130942668-22987898-3e3b-4ab5-b408-d4a3a8cfbabc.png)




### 3. 완전화 유지보수
기존 웹메일 기능에서 새로운 기능을 추가함
- 1. 주소록 관리
현재 등록된 연락처들(현재 등록된 연락처 없음)

![image](https://user-images.githubusercontent.com/49029096/130943028-36e708a2-f534-4cc8-ae7a-c615723ca292.png)

연락처 등록 화면

![image](https://user-images.githubusercontent.com/49029096/130943035-d15b84d0-1544-4bb2-9f82-2730918ad47b.png)

연락처 추가 후 화면

![image](https://user-images.githubusercontent.com/49029096/130943120-9181106a-cc2f-43ed-aabe-34129b22b9c2.png)



- 2. 내게 쓰기
내게쓰기 버튼을 추가하여 간단히 내게 쓰기 기능을 사용할 수 있음
![image](https://user-images.githubusercontent.com/49029096/130943149-38b05c06-cda4-4965-9952-1d9610891b91.png)

- 3. 정렬, 검색 기능

검색 전 화면
![image](https://user-images.githubusercontent.com/49029096/130943281-f8ac7a82-edae-4366-aa0f-9c9a03d09368.png)
검색 후 화면
![image](https://user-images.githubusercontent.com/49029096/130943295-cc435c0a-8f1f-4c63-8804-df7fd209b01e.png)


### 4. 예방 유지보수
오류 방지를 위해 친구 추가 시 DB 유효성 확인, 회원탈퇴 시 암호 입력 등 기존의 코드 수정

![image](https://user-images.githubusercontent.com/49029096/130935679-b11c923e-7b7b-46a3-9c95-27858d5ad169.png)
![image](https://user-images.githubusercontent.com/49029096/130935823-e1bc4f51-7754-4f07-9cbe-bbd0a96e0137.png)
![image](https://user-images.githubusercontent.com/49029096/130935825-a25063d7-54d1-4028-8e45-7a68e9d146ba.png)

회원 탈퇴 시 암호 입력 화면
![image](https://user-images.githubusercontent.com/49029096/130943664-7612f8c7-6427-407f-a51c-493ef62d9e11.png)
