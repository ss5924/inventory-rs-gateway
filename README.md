# Inventory System

### 개요
이 시스템은 재고 관리를 위한 MSA 기반의 통합 솔루션이다.

### Machine Service
- **역할**: 기계 정보 관리
- **기능**:
    - **GET**: 기계 정보 조회
      ```bash
      curl -X GET http://domain:30001/machine/id/3
      ```
    - **POST**: 기계 정보 생성
    - **PUT**: 기계 정보 수정
    - **DELETE**: 기계 정보 삭제
- [Repository URL](https://github.com/ss5924/inventory-rs-machine-service)

### Location Service
- **역할**: 위치 정보 관리
- **기능**:
    - **GET**: 위치 정보 조회
    - **POST**: 위치 정보 생성
    - **PUT**: 위치 정보 수정
    - **DELETE**: 위치 정보 삭제
- [Repository URL](https://github.com/ss5924/inventory-rs-loc-service)