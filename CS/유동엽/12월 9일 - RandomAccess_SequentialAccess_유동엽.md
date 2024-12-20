# TIL - [12월 9일 - RandomAccess_SequentialAccess]

## 📅 날짜
[2024-12-09]

---

## 📌 학습 키워드
- [RandomAccess]
- [SequentialAccess]

---

## 📖 오늘 배운 내용


#### Random Access ####

- 정의 : 데이터의 저장 위치가 고유하게 식별 가능하고, 언제든지 특정 위치에 있는 데이터를 직접 접근할 수 있는 방식. 특정 수조를 기준으로 바로 접근 가능
- 특징
  1. 빠른접근
     - 장점 : 데이터의 순차적인 읽기, 쓰기와 상관없이 데이터를 효율적으로 탐색, 수정 가능
     - 단점 : 파일 크기가 커질수록 관리가 복잡해진다.
  2. 예시 
     1. HDD(하드 드라이브) : 하드 드라이브는 데이터를 블록 단위로 저장하고, 커서를 이동시켜 원하는 블록에 바로 접근한다.
     2. RAM(램) : 메모리 주소를 기반으로 데이터를 빠르게 읽고 쓸 수 있다.


#### Sequential Access ####

- 정의 : 데이터를 순차적으로 읽고 쓰는 방식이며 데이터를 처음부터 끝까지 순차적으로 처리해야한다. 특정 위치에 있는 데이터에 바로 접근 불가
- 특징
    1. 처음부터 끝까지 순차적으로 접근해야하므로 임의 접근이 필요한 경우엔 불편
        - 장점 : 구현이 간단하고 대량의 데이터를 순차적으로 읽는 작업에서는 성능이 우수
        - 단점 : 데이터가 특정 위치에 있을 때, 해당 위치를 찾기 위해 처음부터 끝까지 읽어야하기 때문에 효율성이 떨어진다.
    2. 예시
        1. 테이프 드라이브
        2. CD
        3. DVD
        4. 스트리밍 서비스 
    

---
