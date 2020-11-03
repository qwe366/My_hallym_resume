# Hi there :blue_heart:

## welcome :exclamation: I'm So young.... :wink:

---
- __Name__ : Yoon So young (20175321)
- __Age__ : 23 (Korean age)
- __Email__ : wowgoodbetter@gmail.com
- __Hobby__ : 음악듣기:headphones:

    - **My Play List** :star:


    | Singer | Song |
    | -------------| --------|
    | _죠지_ | _boat_ |
    | _lany_ | _Malibu Nights_|
    | _안다, 프라이머리(Primary)_ | _The open boat (feat.colde)_|

- __Major__ : 빅데이터전공 
  - _`What to learn..`_:thought_balloon:

    - If you get more information, 'click this  <u>[_link_](https://www.hallym.ac.kr/hallym_univ/sub01/cP14/sCP11.html)</u>'

- __Available Languages__
   - JAVA

     ```java
     System.out.println("Hello Java");
     ```
   - C

     ```c
     printf("Hello C");
     ```

  - C++

     ```c++
     cout << "Hello C++!" << endl; 
     ```

  - Python

     ```python
     print("Hello Python")
     ``` 
  - C#

     ```cs
     Debug.WriteLine("Hello C#");
     ```

- __I interested in..__
   - `Linux` , `Unity`,  `Machine Learning .. Deep Learning` :computer:





---

## My Projects.. :books:

- ### __'Dodge'__ (VR/AR/게임제작기초)

   - 프로젝트 설명

     ```
     사방에서 날아오는 탄알을 가능한 한 오랫동안 피하는 탄막 슈팅 게임
     ```
  - 프로젝트 과정
     1. 씬 구성하기
     3. 플레이어 제작
    
     5. 입력매니저
      ```cs
        void Update(){

            float XInput = Input.GetAxis("Horizontal");
            float zInput = Input.GetAxis("Vertical");

            float xSpeed = XInput * speed;
            ....
        }
    ```
     6. 탄알 제작

     5. 탄알 생성기 제작
     6. 게임 매니저 제작

  - 프로젝트 중요 내용
    ```
    - Trigger Colliider 
       : 충돌한 물체를 밀어내는 물리적인 표면이 없음, 충돌자체는 감지
    - Prefab
       : 여러 컴포넌트로 이미 구성이 완성 된, 재사용 가능한 게임 오브젝트
    - Instantiate
       : 게임 도중에 실시간으로 오브젝트를 생성할 때 사용
    - ...
  - 프로젝트 결과  

    ![dodge1](dodge1.png)
    ![dodge2](dodge2.png)

---

- ### __'Fashion Mnist'__ (머신러닝)
  - 프로젝트 목적
     ```
     Fashion Mnist 데이터를 사용해서  SGDClassifier, SVC, RandomForestClassifier 의
    분류기들의 성능을 계산 후, 가장 성능이 좋은 분류기 분석
    ```

  - 데이터 분석 

     ![data_anayl](data.png)
      ![dodge1](dodge1.png)

  - 모델

    > [Stochastic Gradient Descent(SGD)](https://go-hard.tistory.com/11
)
   _확률적 경사하강법_

    > [support vector machine (SVM)](https://m.blog.naver.com/PostView.nhn?blogId=slykid&logNo=221630584607&proxyReferer=https:%2F%2Fwww.google.com%2F
)
        _서포트 벡터 머신_
    > [RandomForestClassifier](https://eunsukimme.github.io/ml/2019/11/26/Random-Forest/) _랜덤포레스트_
    
 
  - 성능 평가 정확도 비교
  

    | MODEL | SCORES | MEAN    |
    | -------------| --------|--------|
    | _SGD_ | _0.7844_ / 0.7897 / 0.7987  | __0.7910__
    | _SVC_ | _0.7844_ / 0.8168/ 0.8198 |__0.8070__
    | _RANDOM FOREST_ |0.8113/ 0.8108/0.8108|__0.8109__



    `" RANDOM FOREST CLASSIFIER 가 가장 평균이 높게 나옴"` 


  - ERROR ANALYSIS (RANDOM FOREST CLASSIFIER 로 한 결과)


     ![random_anal](analy1.png)

