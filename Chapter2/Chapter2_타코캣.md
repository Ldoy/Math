# Chapter2 Essence of linear algebra
[Linear combinations, span, and basis vectors | Chapter 2, Essence of linear algebra](https://www.youtube.com/watch?v=k7RM-ot2NWY&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=2)

### Linear Combination(선형조합)
<img width="140" alt="Screen Shot 2021-12-20 at 15 23 00" src="https://user-images.githubusercontent.com/34529917/146721168-d7b09913-e8b4-4a66-9851-5532eec402dd.png">

- 두개의 벡터를 이용해서 새로운 좌표를 얻을 수 있다. ⇒ 두 개의 벡터만 있으면 어떤 좌표로든 갈 수 있다.
    - 단 벡터의 origin이 같은경우, 원점인 경우 제외
- 벡터의 연산에선 베이스벡터가 무엇인지가 중요. `Scalars`가 같더라도 (베이스벡터가 다르면 완전 다른 좌표를 나타냄)
- 왜 linea인가?
    - 스칼라중 하나를 고정하고 다른 스칼라(이 경우 `b`)를 조정하면 선을 그릴 수 있기 때문
- `span` of two vectors
    - 벡터가 다다를 수 있는 공간
        
        = 두 가지 기본 연산을 가지고 도달 가능한 벡터들의 집합은 어떠한가 라고 묻는 것과 동일하다 
        
    - span이 특정 선 위로 제한 되는 경우
        - 벡터의 origin이 같은경우, 원점인 경우

### Vectors vs Points

벡터가 가리키는 곳이 포인트 

백터의 집합은 포인트로 생각하는게 좋음.

### Linearly Dependent

단 벡터가 같은 선상에 있어서 span에 영향을 주지 않는 경우

### Linearly Independent

각각의 벡터가 기존 스팬에 또다른 차원을 추가해 주는 경우

# 퀴즈

> The basis of a vector space is a set of linealry independent vectors that span the full space
> 

위의 말이 왜 맞나?

같은 선상에 있지 않는 linearly independent관계의 벡터가 만들어내는 span을 통해 vector space 의 basis를 모두 표현할 수 있기 때문. 만약 같은 선상에 있다면 2차원, 3차원의 모든 공간에 다다를 수 없다. (벡터의 point가 무한할 수 없다. )
