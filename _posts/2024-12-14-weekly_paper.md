---
title: "장바구니 분석과 지지도, 신뢰도, 향상도"
author : Myeong Jin Ko
date : 2024-12-14 08:00:00 UTC+9
tags: [Codeit_WeeklyPaper]
---

## Weekly-Paper with odeit Data_Analyst_4
---
### 1. 장바구니 분석 활용 사례, 활용에 따른 비지니스 인사이트 도출

**장바구니 분석 활용 사례** 
- 마켓에서 손님이 물건을 구매한 기록을 통해 각 물건들이 서로 어떤 연관성을 갖고 있는지 확인할 수 있다.
- 대표적인 사례로 '맥주와 기저귀'는 서로 연관성이 높은 물품이다.
- 대형마트나 서점에 갔을 경우 저렴한 가격에 활용성이 비슷한 물품을 묶어서 판매하는 경우가 많다.

**비지니스 인사이트 도출**
- 기저귀를 구매하는 손님들은 힘든 육아에 지쳐 맥주를 자주 마시는 경향이 있다.
- 활용성이 비슷한 물품을 묶어서 판매할 경우, 손님이 한번에 여러가지 물품을 구매하도록 유도할 수 있다.
---
### 2. 지지도, 신뢰도, 향상도

**지지도**
- 지지도는 연관 규칙의 중요성에 대한 척도이다, 예를 들어 맥주와 기저귀를 동시에 구매할 확률 또는 특정 상품 조합의 구매 건수가 전체 상품 구매 건수에서 차지하는 비율을 나타낸다. 즉 맥주와 기저귀를 동시에 구매하는 교집합을 말한다.

**신뢰도**
- 신뢰도는 연관 규칙의 정확도에 대한 척도이다. 최소신뢰도를 통해 연관 규칙의 정확도를 설정할 수 있다.
- A를 구매한 후 B를 구매할지에 대한 조건부 확률이다.
- A에서 A와 B의 교집합이 차지하는 비율이다.

**향상도**
- 향상도는 A를 구매할 경우 B를 구매할 확률이 얼마나 높아지는지르 나타낸다.
- 향상도가 1보다 크면 양의 관계가 있다고 볼 수 있으며
- 향상도가 1보다 낮으면 관계가 없다고 볼 수 있다.