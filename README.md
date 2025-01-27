# Dr.Mozzarella🧀


## 프로젝트 소개

- Dr.Jart(US) 클론 프로젝트로써 기존의 사이트의 디자인을 참고하되 치즈를 파는 커머스 사이트로 기획하여 만들었습니다.
- 약 2주 간의 짧은 프로젝트 기간으로 인해 필수 기능과 빠른 시일 내에 구현 가능한 기능에 초점을 맞췄습니다. 
- 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 프론트엔드와 백엔드가 연결하여 사용할 수 있는 서비스 수준으로 개발했습니다.

### 개발 인원 및 기간

- 개발기간 : 2021년 7월 5일 ~ 7월 16일
- 개발 인원 총 6명
   -  프론트엔드 : 이종민, 박정훈, 황소미
   -  백엔드 : 이동명, 김한준, 안희수

### 데모 영상

<a href="https://youtu.be/lqHxD3Zq770">Dr.Mozzarella 시연 영상 클릭</a>

<br>

## 적용 기술 및 구현 기능

### 적용 기술

> - Front-End : React, SASS
> - Back-End : Python, Django
> - Common : AWS(EC2,RDS)

### 협업 도구
Slack / Git + GitHub / Notion를 이용해 일정관리 하였습니다. 


### 프로젝트 후기
https://velog.io/@sui3422/Dr.Mozza-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-Dr.Jart-%ED%81%B4%EB%A1%A0-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8


### Front-End 구현 기능

**<이종민>**
- 로그인 / 회원가입
- 장바구니 페이지
- 결제 페이지

**<박정훈>**
- 메인페이지
- Nav바

**<황소미>**
- 상품페이지
- 디테일페이지
<br>

## 작업페이지 설명

## 장바구니 페이지

-장바구니 구현 기능 목록-
1. '+' / '-' 버튼으로 수량 증가/감소
2. 직접 수량을 입력 해서 수량 변경 가능
3. reduce 를 이용한 Subtotal 계산
4. 재고 이상 수량 입력 불가 및 alert 으로 재고부족 경고
5. 수량입력창은 max 99, min 1

![cart](https://user-images.githubusercontent.com/80690729/129880846-e3383fc4-2bc9-45c0-bdd0-29172d75c681.gif)


## 결제 페이지

-결제페이지 구현 기능 목록-
1. '%' 쿠폰 / '가격감소 쿠폰' 적용가능
2. 주소API 를 통한 주소입력

![check](https://user-images.githubusercontent.com/80690729/129880919-cf79dde8-47dd-4bec-afd2-30a2bfa5f747.gif)

## 주소 API 개선 (결제 페이지에 사용)
사용 라이브러리 : https://www.npmjs.com/package/react-daum-postcode

1. 내부의 함수가 직관적이지 못하여 코드 개선
2. 개선사항 Detail: https://velog.io/@sui3422/react-daum-postcode-%EC%BD%94%EB%93%9C-%EA%B0%9C%EC%84%A0

![postcode](https://user-images.githubusercontent.com/80690729/129881106-00aef003-9820-4e35-b21d-cfb64aefbd9b.jpg)

## 회원가입

![signup](https://user-images.githubusercontent.com/80690729/129881170-ddfd3c0f-3ddf-4917-944d-6174d26dcf88.gif)

## 로그인

![signin](https://user-images.githubusercontent.com/80690729/129881185-96dd6005-aa4f-458b-bdea-1355eba892fa.gif)

## Reference

- 이 프로젝트는 [Dr.Jart](https://https://us.drjart.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
  
  
