---
title: Plantshower
date: 2024-04-17 08:01:35 +0300
subtitle: UX/UI, BI, WEB DESIGN, FRONTEND, BACKEND 2023~
image: '/images/plantshower-cover.png'
---

## CHALLENGE

건강 문제로 일을 쉬게 되면서, 식물을 기르기 시작했습니다. 
원예용으로 길러지는 식물이라도 개체의 특성별로 돌봄 방법 및 물주기 주기가 다르기 때문에, 너무 많아진 식물을 효율적으로 관리하기 위한 기록 도구가 필요하게 되었습니다.
이전에는 같은 용도로 Notion을 사용했지만, 다루는 정보가 복잡해지고 테이블 연동이 늘어나면서, 또는 서비스 장애에 따라 매일 사용하기에 어려울 정도로 속도 저하가 있었습니다. 
기본적으로 식물을 많이 기르는 식집사(본인)가 식물 물주기 및 영양제, 방제, 살균 등의 활동을 빠르고 편리하게 기록하는 데 초점을 맞추되, 식물 초보자에게도 개방하여 물주기에 대한 '감각'을 보조하고자 하였습니다.

<img src = "/images/plantshower_challenge.jpeg" loading="lazy">
<em>일반가정 치고는 식물이 좀 많은 편</em>

## MY ROLE
설계 및 디자인과 개발을 혼자 맡은 1인 개발 프로덕트입니다.

* System & DB Design
* UX/UI Design
* BI Design
* Backend Development (Python/Flask) - w/ChatGPT
* Frondend Development (Html/Css/Javascript) - w/ChatGPT

## USER FLOW

### DB에서 식물을 매칭해 등록합니다.
식물을 찾아서 등록하면 식물의 입양/구매 정보와 함께, 식물에게 갖춰주어야 할 환경에 대한 기본정보를 함께 표시해줍니다.
<div class="gallery-box">
  <div class="gallery">
    <img src="/images/plantshower_addplant_1.png" loading="lazy" alt="새 식물 등록" style="border:1px solid #efefef;">
    <img src="/images/plantshower_addplant_2.png" loading="lazy" alt="식물 정보가 함께 입력" style="border:1px solid #efefef;">
  </div>
  <em>자동 완성 검색 기능을 통해 식물을 등록하면 사용자의 식물에 대한 정보가 함께 표시됩니다.</em>
</div>

### 상단의 날씨를 참고하여, 식물의 물주기를 기록합니다.
실내 가드너라 해도, 바깥의 날씨에 큰 영향을 받습니다. 맑고 따뜻한 날을 참고해서 물을 주기도 하고, 너무 기온이 떨어지면 베란다나 발코니에서 실내로 들여오기도 해야 합니다. 그러한 한국의 실내 가드너의 상황에 맞추어 한국의 기상청 날씨를 참조할 수 있게 하였으며, 리스트에서 한꺼번에 물주기를 입력할 수 있게 했습니다. 또한 사계절에 맞게 최근 7번, 즉 7-10일에 한 번 물을 주었을 때 한 계절을 넘지 않는 선의 비슷한 날씨 텀 안에서 물주기 텀을 평균내 식물별 다음 물주기를 예측해 표시합니다. 상세 페이지에서는 최근의 물주기 기간 경향을 자세히 볼 수 있으며, 깜빡 잊고 지나간 지나간 날짜의 물주기를 입력할 수도 있습니다.
<div class="gallery-box">
  <div class="gallery">
    <img src="/images/plantshower_watering_3.png" loading="lazy" alt="상단의 날씨 확인" style="border:1px solid #efefef;">
    <img src="/images/plantshower_watering_1.png" loading="lazy" alt="리스트에서 바로 오늘 날짜로 한꺼번에 입력">
    <img src="/images/plantshower_watering_2.png" loading="lazy" alt="상세 페이지에서 개별로 입력" style="border:1px solid #efefef;">
  </div>
  <em>상단의 날씨 확인 -> 선택 후 물주기 완료 / 상세페이지의 개별 물주기 입력</em>
</div>
<img src = "/images/plantshower_watering_4.png" loading="lazy">
<em>날씨 - 낮/밤 8가지 타입 디자인</em>

### 분갈이, 영양공급, 해충방제, 살균 등의 돌봄 활동을 기록합니다.
분갈이를 한 뒤에는 2~3주 후 비료를 줄 수 있고, 영양제 급여도 7~10일 정도의 간격이 필요합니다. 또한 해충방제 또한 같은 약을 쓰면 내성이 생겨서 듣지 않는 경우가 있기 때문에 그런 경우 별도의 표시를 하는 시스템을 만들었습니다.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/plantshower_manage_1.png" loading="lazy" alt="사진첩에 저장할 수 있는 이미지 교환권" style="border:1px solid #efefef;">
    <img src="/images/plantshower_manage_2.png" loading="lazy" alt="살충제 내성 표시" style="border:1px solid #efefef;">
  </div>
  <em>분갈이, 영양공급, 해충방제, 살균 기록 및 살충제 내성 표시</em>
</div>

## BI
한국의 실내 가드너는 샤워기나 물조리개로 물을 식물에 뿌려, 뿌리에 물을 공급하는 이외에도 식물을 씻기고 병충해를 방지하기도 합니다. 그런 모습을 심볼마크와 로고타입을 통하여 표현하고자 했습니다.

<img src = "/images/plantshower_bi.png" loading="lazy">
<em>플랜트샤워 BI</em>

## LANDING PAGE
플랜트샤워의 특징적 기능들을 소개하고, 어떤 해상도에서도 최적화되어 보일 수 있게끔 반응형으로 디자인하였습니다.

### Mobile View
<img src = "/images/plantshower_landing_mobile.png" loading="lazy">

### PC View
<img src = "/images/plantshower_landing_pc.png" loading="lazy">

## RESULT

2023년 8월에 첫 배포 후 지속적인 업데이트와 유지보수가 이루어지고 있습니다. 온라인 지인과 함께 사용하는 소규모 프로덕트로 사용되고 있으며, 하루에 3~5분 정도의 시간을 사용하는 것만으로 식물의 상태를 좀 더 예측 가능하게 되었습니다.
또한 ChatGPT를 통한 초심자의 개발에 대해서 회고하여 후원 및 유료 컨텐츠로서의 가능성을 시험해보고 있습니다.

## PRODUCT LINK

* <a href="https://plantshower.xyz">Plantshower </a>
* <a href="https://plantshower.xyz/about/">Plantshower 소개 랜딩 페이지 </a>
* <a href="https://plantshower.postype.com/">Plantshower 개발 블로그 - 디자인 15년차, 개발 1년차</a>
* <a href="https://plantshower.xyz/hyerim/">직접 기르고 있는 식물 목록</a>