---
title: "1회차 Part2: 데이터 수집 및 처리 시스템 소개"
layout: post
author: songhunhwa
---

### 목적
- 1강 Part1(분석실무에 대한 이해) 내용중 분석 시스템 환경/툴 및 개념에 대해 학습한다.
- JSON 형태의 로그 데이터를 Parsing 및 전처리하는 실습을 진행한다.

### Apache Spark & Modules 소개
분석 환경은 주로 엔지니어 및 회사의 고유 상황에 따라 결정된다. 분석가는 환경적/구조적 특성과 제한점 등 여러 사항을 고려하여 분석을 진행한다. 물론, 분석가가 주도적으로 처음부터 환경을 설정하고 구조를 쌓아올라가는 경우도 있다. 하지만 이는 일반적인 상황이라고 보기 어렵다. 분석가가 좋은 성과를 내기 위해서는 **분석 환경을 잘 이해하고 때로는 개선점을 엔지니어에게 전달**하는 등 환경/시스템적 요소에 대해 지속적인 관심을 가지는 것이 필요하다.   
일반적으로 

[Source](https://www.slideshare.net/databricks/building-a-modern-application-with-dataframes-52776940)