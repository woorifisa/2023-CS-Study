# Quick Sort - 퀵정렬

## 목차
1. 퀵 정렬(Quick Sort) 개념
2. 정렬 방법
3. 구현
4. 장단점
5. 면접질문
6. 참고자료




## 1. 개념

`**퀵 정렬(Quick Sort)**` 
: `분할 정복(Divide and Conquer)` 알고리즘을 기반으로 정렬되는 방식


- `비교정렬` : 데이터를 '비교'하면서 찾는다

- `제자리정렬(in-place sort)` : 정렬의 대상이 되는 데이터 외에 추가적인 공간을 필요로 하지 않는다

- `불안정 정렬(Unstable Sort)` : 하나의 피벗을 두고 두개의 부분리스트를 만들 때, 서로 떨어진 원소끼리 교환이 일어나는 알고리즘



병합정렬(Merge Sort) : 하나의 리스트를 '절반'으로 나누어 분할 정복
vs.
퀵정렬 : 피벗(pivot)의 값에 따라 피벗보다 작은 값을 갖는 부분리스트


> 퀵 정렬에서 가장 중요한 부분
> **: 피벗을 무엇으로 잡느냐**



## 면접질문

Q1. 퀵 정렬(Quick Sort)에 대해 설명해주세요.

A1 : 퀵 정렬은 빠른 정렬 속도를 자랑하는 분할 정복 알고리즘 중 하나로 피봇을 설정하고 피봇보다 큰 값과 작은 값으로 분할하여 정렬 합니다.
병합정렬과 달리 리스트를 비균등하게 분할합니다.
시간 복잡도는 O(nlogn)이며 worst case 경우 O(n^2)까지 나빠질 수 있습니다.





## 참고자료

- [퀵 정렬 전반적인 개념](https://st-lab.tistory.com/250)


- [면접질문](https://dev-coco.tistory.com/160)