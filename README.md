# 📸 WhereCamFrom

2018 Klaytn horizen Project



#### 📒 개요


>감시 카메라의 영상은 범죄 및 사고 사건 조사의 주요 증거 자료로 자주 사용됩니다. <br>
이때 동영상 파일은 원본이어야만 의미가 있습니다. <br>
또한 최근 딥페이크 영상은 가짜뉴스로 만들어져 사회적으로 큰 혼란을 야기하기도 합니다.<br>
‘WhereCamFrom’은 동영상 파일이 감시 카메라(스마트폰, 블랙박스, CCTV 등)로 녹화된 원본인지 아니면 동영상 편집 도구(Sony Vegas, Windows Movie Maker 등)에 의해 편집되었는지 여부를 쉽고 빠르게 확인 가능하고, 결과를 블록체인에 저장해줌으로써 영상의 무결성을 검증할 수 있습니다.




#### 📒 LANGUAGE

> #JAVASCRIPT #HTML #SOLIDITY


<br>


#### 📒 흐름
>![흐름 사진](https://user-images.githubusercontent.com/57470848/146899468-583102a0-abfe-4cc0-b2f5-3b9653812f71.png)


<br>


#### 📒 데모영상
> https://drive.google.com/file/d/1MxRIqifn_XCB2ge5gfoSKRy52d1DU5X4/view?usp=sharing


<br>


#### 📒 프로그램 동작


#### 로그인
+ 로그인페이지<br>
  -Klaytn Wallet 계정의 private key를 입력하여 로그인한다.
>![로그인](https://user-images.githubusercontent.com/57470848/146634149-a354026a-7dd8-48dc-a445-fd037660a24a.PNG)
***

<br>

#### 분석
+ 분석 전<br>
    -영상의 정보와 편집여부를 분석하고자 하는 영상을 입력한다.
>![분석전](https://user-images.githubusercontent.com/57470848/146725042-6f2f2ee4-bc0e-4132-bc38-2a579896265b.PNG)
***

<br>

  + 분석결과(원본영상)<br>
    -원본 영상의 경우, 영상을 촬영한 기기 정보가 출력된다.
>![분석결과](https://user-images.githubusercontent.com/57470848/146725108-2faad490-9bed-4fd0-810d-12d76a4607a7.PNG)
***

<br>


  + 분석결과(편집영상)<br>
      -편집된 영상의 경우, 영상을 편집하는데 쓰인 도구 정보가 출력된다.
>![분석결과(수정)](https://user-images.githubusercontent.com/57470848/146725119-76106ca0-a434-4eef-b0cd-d413e999a806.PNG)
***

<br>
 

+ 분석&저장<br>
  -영상을 분석하고 그 결과를 블록체인에 저장하여, 같은 영상이라면 재분석할 필요 없이 분석 결과를 열람할 수 있다.
>![분석 저장](https://user-images.githubusercontent.com/57470848/146727659-cf8c5f0f-1650-48c4-8dd7-2b7488b65f2b.PNG)
***

<br>


+ 분석결과 검색<br>
  -블록체인에 저장된 영상 파일 정보와 사용자가 입력한 파일이 같다면 이전의 분석결과를 출력한다.
>![분석검색](https://user-images.githubusercontent.com/57470848/146727683-853a05e5-4639-4a1c-b9d7-07e7f4558f96.PNG)
***

<br>

#### 비교

+ 비교 전<br>
  -원래의 영상에서 편집된 영상인지 확인하고 싶은 영상과 비교할 영상을 넣어준다.
>![비교](https://user-images.githubusercontent.com/57470848/146728023-7400f594-91c4-4965-9352-dd5ae916ec16.PNG)
***

<br>

+ 비교 결과(편집영상)<br>
  - 두 영상의 분석결과와 1초마다 두 영상의 rgba값의 차이를 비교하여 편집된 부분의 시간과 화면을 출력한다
>![비교결과](https://user-images.githubusercontent.com/57470848/146728030-b830ed32-6fc2-43ad-bd43-e72584031da9.PNG)
***

<br>

+ 비교 결과(원본영상)<br>
  -두 영상의 분석결과와 1초마다 두 영상의 rgba값의 차이를 비교하여 차이가 없다면 두 영상은 같은 영상이라고 출력한다.
>![비교결과원본](https://user-images.githubusercontent.com/57470848/146728019-de106f5f-b02a-4780-91a9-4afc8b101c34.PNG)
***

<br>

+ 비교결과저장<br>
  -영상의 해시값과 저장시간, 파일명, 편집유무, 사용자계정 을 블록체인에 저장한다.
>![비교결과저장](https://user-images.githubusercontent.com/57470848/146729673-6eb20b1d-8a49-4375-b932-1ae0beac19fa.PNG)
***

<br>

+ 비교결과검색<br>
  -영상의 해시값과 저장시간, 파일명, 편집유무, 사용자계정 을 블록체인에 저장한다.
>![비교검색결과](https://user-images.githubusercontent.com/57470848/146728028-15f39697-84db-41f0-aa93-d82df5d41097.PNG)
***

<br>



