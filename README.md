# JAVA-GUI-PROJECT
자바 GUI를 이용한 프로그래밍 

## 외계인을 잡아라! 
### 게임 설명
 - '외계인을 잡아라!'는 플레이어가 화살을 쏘아, 지구를 침략해오는 외계인을 죽이는 게임이다. 
 - 게임 이용 방법은 키보드 방향키(← ↑ ↓ →)를 이용해 플레이어의 캐릭터를 양 옆, 위 아래로 움직이고, 스페이스 바를 이용해 화살을 쏜다. 
### 게임 규칙
 - 외계인은 화살에 맞으면 죽는다. 
 - 외계인 한 마리를 죽일 때마다 SCORE는 10점씩 오른다. 
 - 일정 점수(100점, 250점, 350점, 450점)에 도달할 때마다 외계인의 속도가 한 단계씩 빨라진다. 
   5라운드까지 있으며 그 이후 속도는 동일하게 유지된다. 
 - 생명은 5개가 주어지고, 날아오는 외계인을 피하지 못하고 충돌할 경우 생명은 하나씩 줄어든다. 
 - 생명 5개가 다 떨어지면 GAME OVER와 함께 화면에 점수가 출력되고 게임은 끝이 난다. 
 - 화면 왼쪽과 오른쪽 상단에서 게임 이용 방법과 라운드, 점수, 남은 생명 수를 확인할 수 있다. 
   
### 실행 화면
 - 플레이어가 화살을 쏠 때 
  
     ![화살 쏠 때 ](https://user-images.githubusercontent.com/52234053/92622929-97c45f00-f300-11ea-901c-4fe336038db2.png)
  　　
  
  
 - 플레이어가 화살을 연속으로 쏠 때 (연속으로 누르면 화살이 일정한 간격을 두고 날아가도록 설정) 
  
     ![연속으로 쏠 때](https://user-images.githubusercontent.com/52234053/92622937-998e2280-f300-11ea-8e93-69d1e3215c37.png)
  　
  
  
 - 외계인이 화살에 맞았을 때 
 
     ![외계인이 화살에 맞았을 때](https://user-images.githubusercontent.com/52234053/92622938-9a26b900-f300-11ea-8bd0-e9a3867064ec.png)
  　
  　
  
 - 플레이어와 외계인이 충돌했을 때 (외계인이 화살에 맞았을 경우와 차이를 두기 위해 충돌 효과가 두 개 나타나도록 설정) 
 
     ![플레이어와 외계인이 충돌했을 때](https://user-images.githubusercontent.com/52234053/92622939-9abf4f80-f300-11ea-90c3-642dbb3f0470.png)
  　
  
  
 - 게임이 끝났을 때 (GAME OVER와 SCORE를 출력) 
 
     ![GAME OVER](https://user-images.githubusercontent.com/52234053/92622941-9abf4f80-f300-11ea-9c39-819ba5aa86cc.png)
