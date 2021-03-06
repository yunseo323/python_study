# 리스트 자료형
*리스트 함수 적극적으로 활용하기*

---

# 튜플 자료형
```
score = ( ('A', 100),
       ('B', 84),
       ('C', 72))

print(score[0]) -> ('A', 100)
print(score[1][1]) -> 84
```
## 특징
- 소괄호 사용
- 수정 불가능한 참조 데이터 : 읽기만 가능한 리스트(요소를 실수로 변경하는 것을 방지함)
- 리스트에 비해 메모리를 효율적으로 사용

## 사용하는 경우
- 서로 다른 성질의 데이터를 관리해야할때 : 최단 경로 알고리즘
- 데이터 나열을 해싱 키 값으로 사용(변경 불가능하기에 키값으로 사용 가능)

---

# 딕셔너리 자료형

## 특징
- key(변경 불가능&고유)와 value를 쌍으로 가짐
- 순서가 없기 때문에 인덱싱 기능을 사용할 수 없다
- Hash Table을 이용, 데이터 조회 수정이 O(1) 시간에 조회 가능
- keys 함수(키 데이터만 뽑아 리스트로 이용), values 함수(값 데이터만 뽑아 리스트로 이용)

---

# 집합 자료형

## 특징
- 원소를 중복적으로 저장하지 않음(중복되지 않는 요소값의 모임)
- 원소에 순서 없음