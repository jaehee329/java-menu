# 구현 기능 목록

- 도메인
  - 메뉴
  - 코치
  - 카테고리 => enum


- 입력 기능
  - [ ] 코치 리스트 입력 기능
  - [ ] 못 먹는 메뉴 리스트 입력 기능


- 출력 기능
  - [ ] 프로그램 시작 메시지 출력 기능
  - [ ] 결과 반환 기능


- DB
  - 메뉴 저장소 (hashMap<카테고리, List<메뉴>>)
    - [X] 메뉴 초기화 기능 
    - [X] 카테고리에 따른 메뉴 리스트 반환 기능
  - 코치 저장소
    - [X] 코치 추가 기능
    - [X] 이름을 통한 조회 기능
  - 카테고리 저장소 -> 카테고리 자체가 enum이므로 필요 X
  - 코치 불가능 음식 저장소 (hashMap)
    - [X] 코치에 따른 조회 기능
    - [X] 코치에 따른 메뉴 추가 기능
  - 메뉴 추천 결과 저장소 (1. 요일 - 카테고리 저장, 2. Map<요일, Map<코치, 음식> 저장)
    - [X] 카테고리 초기화 기능 (Randoms로 시작 시 저장, 2회 중복까지 허용)
    - [X] 요일과 코치에 따른 메뉴 입력 기능


- 서비스
  - 음식 추천 서비스


- 컨트롤러
  - [ ] 이름 입력, 결과 반환 컨트롤러
  - [ ] 입력된 이름 당 못 먹는 메뉴 입력 컨트롤러



아예 추천이 불가능한 경우?
