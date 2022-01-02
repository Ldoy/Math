# 변환과 선형변환

### 학습영상

[3Brouns1BlueChapter3](https://www.youtube.com/watch?v=kYB8IZa5AuE&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=3)
</br>
[칸아카데미 - 변환](https://ko.khanacademy.org/math/linear-algebra/matrix-transformations/linear-transformations/v/vector-transformations)

### 요약
벡터의 변환이라는 것은 함수와 동일한 의미이다. 함수라는 것은 하나의 집합에서 다른 하나의 집합에 대응하도록 하는 규칙이라고 할 수 있다. 다만 벡터에선 n-tuples이 m-tuples에 대응하는 것이 조금 다른 점이라고 할 수 있다. 

- $ex ) f([x1,x3, x2])  = [ x1 + 2x2, 3x3]$

벡터의 함수를 다룰 때 변환이라고 한다. 선형대수학에서 변환은 정말 벡터의 연산과 동일하다. 변환을 표현할 때  대문자 T 를 많이 사용 

# Liear Transformation

### 정의

- 선형변환은 함수의 다른 표현
    - 함수라고 안하고 선형변환이라고 한 이유 :  함수와는 달리 인풋-아웃풋 관계를 Visual로 보여주기 때문
- 선형변환이란 격자 라인들이 변형 이후에도 parallel하고 evenly spaced 형태를 가지게 하는 것이라고 생각하면 됨(grid lines remain parallel and evenly spaced)
- 벡터를 점으로 본다면 포인트에서 포인트로의 이동

### 선형변환에서 Linear의 의미

1. 모든 선들은 변환 후에도 라인(직선)이어야함. 
2. 오리진은 고정되어야 한다. 

### 선현변환을 수식으로 쓰면 어떻게 표현할까?

- 두개의 베이스 벡터만 있으면 된다. 그러면 선형변환을 통해 어느곳으로든 이동할 수 있다.
<img width="535" alt="Screen Shot 2022-01-02 at 14 51 45" src="https://user-images.githubusercontent.com/34529917/147867898-bfea4f7a-1f11-477e-a7b9-909f539cdee8.png">
