---
title: Weddingbook App
date: 2022-01-02 08:01:35 +0300
subtitle: UX/UI, 2017
image: '/images/wdgbook-cover.jpg'
---

## CHALLENGE

웨딩북은 예비부부의 결혼준비를 돕는 커뮤니티 서비스입니다.

애자일 프로세스에 따라 점진적 업데이트를 하는 프로덕트였으나, 각 기능의 완성도가 떨어지는 상태로 너무 많은 기능이 붙어 있어 실제로 활성화된 기능은 타임라인 형태의 커뮤니티밖에 없는 상황이었습니다. 당시 서비스가 꾀하던 수익모델은 한국식 결혼식 절차에 필요한 많은 항목들을 기존의 오프라인 웨딩 플래너보다 좋은 조건으로 중개해주는 것이었지만, 상품 자체는 경쟁력이 있음에도 UI가 너무 복잡하고 완성도가 낮아 비즈니스를 위해 전면적인 UI 개편이 필요했습니다. 다만 실제 업데이트는 점진적인 방식으로 이루어졌습니다.

## MY ROLE

* UX/UI Design

## ISSUE & SOLUTION

### 1. 디자인 부채 해결하기

200개가 넘는 화면에 요소간의 정렬이 맞지 않고, 메인 컬러는 모두 제각각으로 사용되고 있었으며, 아이콘은 비뚤게 그려져 있는 상황이었습니다. 안드로이드 앱도 OS별 차이를 무시하고 iOS와 동일하게 디자인되어 있어 개발 효율도 떨어졌습니다. 우선 스케치 심볼을 통해 기초적인 디자인 시스템을 만들고, 돈을 써도 되는 서비스로 최소한의 완성도와 신뢰감을 확보하기 위해 기존의 톤을 유지하면서 그리드와 컬러 톤, 아이콘 작업을 새로 했습니다. 또한, 앱 개발과의 밀착된 협업과 디자인 QA를 통해 개선한 디자인을 꼼꼼하게 적용했습니다.

<img src="/images/howtomarry_before.png" loading="lazy" alt="Project">
<em>이전 - 기본적 그리드가 맞지 않고, 아이콘의 픽셀과 비율이 깨져있고, 안드로이드 앱도 iOS와 동일한 형태로 가이드되어 있었고, 디자인 시스템은커녕 레이어 정리도 안되어 있어 최초 작업자 이외 접근이 힘든 상황이었습니다.</em>

<img src="/images/howtomarry_after.png" loading="lazy" alt="Project">
<em>개선 - 8-px 그리드 단위로 정렬을 맞추고, 아이콘을 pixel-perfect로 새로 그리고, OS에 맞게 디자인 가이드를 새로 맞추고, 기초적인 디자인 시스템을 제작했습니다.</em>

### 2. 홈 화면 변경

첫 화면이지만 잡다한 정보와 결혼 관련 사진이 롤링되고 있을 뿐, 웨딩 관련 상품과 가게들을 비교하고 중개해준다는 것을 알기 어려운 형태로 운영되고 있었습니다. 과감하게 잡다한 요소를 없애고, 각 카테고리의 제품들을 비교할 수 있게끔 단순하게 재구성했습니다. 또한 최상단에는 가게와 예약한 스케쥴이 있을 경우 알림을 주거나, 복잡한 온보딩 대신 서비스 주체가 원하는 특정 미션을 수행했을 경우 포인트를 주는 식으로 알림 화면으로도 사용할 수 있게 하였습니다.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/wdgbook-home-before.png" loading="lazy" alt="Project">
    <img src="/images/wdgbook-home-after.png" loading="lazy" alt="Project">
  </div>
  <em>홈 화면. 이전 버전(왼쪽)과 개선 이후(오른쪽)</em>
</div>


### 3. 업체비교 화면 리디자인


기존에는 예식장/예물/예단 등의 업체 정보 페이지에서 실제로 판매하고 있는 상품의 구체적 정보가 나타나있지 않았고, 업체에 직접 전화 연결만 하는 형태가 많았습니다. 좀 더 자세한 정보를 정리되어 있는 형태로 보여주고, 온라인에서 직접 예약할 수 있게끔 리디자인하였습니다.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/wdgbook-info-before.png" loading="lazy" alt="Project">
    <img src="/images/wdgbook-info-after.png" loading="lazy" alt="Project">
  </div>
  <em>웨딩 관련 업체 정보 화면. 이전 버전(왼쪽)과 개선 이후(오른쪽)</em>
</div>

## PRODUCT LINK

* <a href="https://play.google.com/store/apps/details?id=com.how2marry.weddingbell&hl=ko&gl=US">Weddingbook for Android</a>
* <a href="https://itunes.apple.com/kr/app/id1294957719">Weddingbook for iOS</a>