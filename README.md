# 2020_fall_db_project
- 데이터베이스 프로젝트
---------------------------------------
## About
#### 안심식당 및 지역화폐 가맹점 정보 제공 서비스
- 최근 코로나 확산이 여전히 지속되고 있지만, 기본적인 위생 규칙을 지키지 않는 식당들로 인해 고객들은 안심하고 식당을 이용하지 못하는 상황에 놓이게 되었다. 따라서 사용자의 조건에 맞는 안심식당 정보와 더불어 지역화폐 가맹점 정보까지 함께 제공하는 서비스를 개발하게 되었다.
---------------------------------------
## Authors & Role (가나다 순)
- [송지연](https://github.com/Song-JiYeon): 안심식당 OpenAPI, 지역 및 음식 카테고리 별 안심식당 검색 기능
- [우나영](https://github.com/WooNaYoung22): 지역화폐가맹점 데이터, 안심식당 검색 기능
- [최진영](https://github.com/jinyoung0612): 안심식당 OpenAPI, 안심식당 정보 제공 기능
---------------------------------------
## 제공 기능
- 사용자의 지역 선택에 따른 안심식당 정보 제공
- 안심식당 검색 기능 제공
- 안심식당 상세정보 및 경기도 내 지역화폐 가맹점 정보 제공
---------------------------------------
## 시스템구조
<img width="579" alt="시스템구조" src="https://user-images.githubusercontent.com/32068745/103401878-1da93600-4b8e-11eb-9fca-d7b6cbf4a1a0.png">

---------------------------------------
## 개발환경
- DBMS: PostgreSQL
- 언어: Java
- 데이터
    - 안심식당 정보 (공공데이터 포털 농림축산식품부 제공 )
    - 지역화폐 가맹점 현황 (경기도 제공)
