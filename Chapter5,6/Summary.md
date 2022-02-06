# T**hree-dimensional linear transformations | Chapter 5, Essence of linear algebra**
- [영상](https://www.youtube.com/watch?v=rHLEWRxRGiM&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=5)

### 요약
- 행렬의 각 행은 x, y, z축 에서의  (x,y,z)로 표현되는 화살표의 종점(원점에서 해당점까지 벡터)를 의미한다.

# **The determinant | Chapter 6, Essence of linear algebra**
- [영상](https://www.youtube.com/watch?v=Ip3X9LOh2dk&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=6)
- determinant: 2D에선 벡터들이 이루는 영역의 넓이, 3D에선 3차원 물체의 부피(volume). 음수인경우 flipping되었음을 의미
    - 2D에서 determinant 가 0으로 수렴하도로고 하면 점이 되고 3D에선 parallelepiped의 volumn을 의미
- 계산방법
    - 2 x 2 matrix
    
      \begin{bmatrix}
      a & b\\
       c & d
      \end{bmatrix} = ad - bc    
    - b,c가 0일 때 a는 원점에서 x 축에서 벡터의 마지막 위치까지의 길이, d는 y축 에서 벡터의 마지막 위치까지의 길이를 의미한다. 즉 넓이는 ad 가 됨
    - bc를 빼는 이유
        ![https://www.youtube.com/watch?v=Ip3X9LOh2dk&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=6](https://user-images.githubusercontent.com/34529917/152679133-684673c2-83ad-4c81-82a6-13a06b3806a9.png)
    
    - 3 x 3 matrix
    
    $\begin{bmatrix}
    a & b &c\\
     d & e & f \\
    g & h & i
    \end{bmatrix} = aei +bfg + cdh - ceg - bdi - afh$
    
    ### 퀴즈
    ![Screen Shot 2022-02-06 at 19 50 29](https://user-images.githubusercontent.com/34529917/152679326-44b4ecd6-091d-426e-a3cb-9d998dc5674e.png)

    이 수식을 한 문장으로 설명하기
