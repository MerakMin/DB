SQLD

chapter 01. 데이터 모델링의 이해

2. 속성
(1) 속성의 개념 및 특징
□ 속성의 개념
- 속성은 업무에서 필요한 데이터로, 의미상 더는 분리할 수 없는 최소의 테이블 단위
- 속성은 엔티티를 설명하는 역할을 하고 인스턴스의 구성 요소

□ 속성의 특징
- 업무 정보 → 해당 업무에서 필요하고 관리하고자 하는 정보
- 함수적 종속성 → 데이터가 가지고 있는 속성간의 관계에 의해 결정되고 종속되는 현상 + 정규화 이론에 근간하여 정해진 주 식별자에 함수적 종속성을 가져야 함 + 데이터의 기준값을 결정자라고 하고, 종속되는 값을 종속자라고 함
- 유일 값 → 하나의 속성은 하나의 값만 소유 + 하나의 속성에 여러 개의 값이 있는 경우, 별도의 엔티티를 이용하여 분리

(2) 엔티티, ㅇ니스턴스, 속성, 속성값 간의 관계 및 표기법
□ 