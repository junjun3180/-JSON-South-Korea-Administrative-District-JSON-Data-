# 대한민국 행정구역 JSON 데이터 (South Korea Administrative District JSON Data)

이 저장소는 대한민국의 행정구역 정보를 시도, 시군구, 읍면동 단위로 정리한 JSON 데이터를 제공합니다.

This repository provides JSON data for the administrative districts of South Korea, organized by metropolitan cities/provinces, cities/counties/districts, and towns/townships/neighborhoods.

[한국어 설명 바로가기](#-한국어-설명) | [English Description](#-English-Description)

<br>

---

## 🇰🇷 한국어 설명

### 소개

이 프로젝트는 2025년 8월 기준 대한민국의 행정구역 체계를 JSON 형식으로 정리한 데이터입니다. 개발자, 연구자, 학생 등 누구나 자유롭게 활용할 수 있도록 제작되었습니다.

### 특징

- **전국 단위:** 대한민국 17개 시도 및 하위 행정구역 전체를 포함합니다.
- **표준화된 형식:** 일관된 JSON 구조로 데이터를 쉽게 파싱하고 활용할 수 있습니다.
- **최신 정보:** 2025년 8월 기준 최신 행정구역 코드를 반영했습니다.
- **오픈 라이선스:** 별도의 저작권 표기 없이 상업적, 비상업적 용도로 자유롭게 사용 가능합니다.

### 데이터 구조 예시

```json
{
  "timestamp": "YYYY-MM-DDTHH:MM:SSZ",
  "adm_nm": "시도명",
  "adm_cd": "시도코드",
  "districts": [
    {
      "adm_nm": "시군구명",
      "adm_cd": "시군구코드",
      "towns": [
        { "adm_nm": "읍면동명", "adm_cd": "읍면동코드" }
      ]
    }
  ]
}
```

## 🇺🇸 English Description
### Introduction
This project provides JSON data of the administrative district system of the Republic of Korea as of August 2025. It is designed for free use by developers, researchers, students, and anyone interested.

### Features
Nationwide Coverage: Includes all 17 metropolitan cities and provinces of South Korea and their sub-districts.

Standardized Format: Consistent JSON structure allows for easy parsing and utilization of the data.

Up-to-Date Information: Reflects the latest administrative district codes as of August 2025.

Open License: Freely available for commercial and non-commercial use without any copyright attribution required.

### Data Structure Example
JSON
```
{
  "timestamp": "YYYY-MM-DDTHH:MM:SSZ",
  "adm_nm": "Province/Metropolitan City Name",
  "adm_cd": "Province/Metropolitan City Code",
  "districts": [
    {
      "adm_nm": "City/County/District Name",
      "adm_cd": "City/County/District Code",
      "towns": [
        { "adm_nm": "Town/Township/Neighborhood Name", "adm_cd": "Town/Township/Neighborhood Code" }
      ]
    }
  ]
}
```
### Usage Guide
This data was created for the public good and can be freely copied, modified, and distributed by anyone. You do not need to provide copyright attribution.
