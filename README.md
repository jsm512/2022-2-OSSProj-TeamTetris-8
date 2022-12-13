# 2022-2-OSSProj-TeamTetris-8
<img alt="MIT" src ="https://img.shields.io/badge/license-MIT-salmon"> <img alt="" src ="https://img.shields.io/badge/pygame-2.1.2-lightsalmon"> <img alt="" src ="https://img.shields.io/badge/OS-ubuntu-coral"> <img alt="" src ="https://img.shields.io/badge/IDE-VSCode-indianred"><br>

<br>

 👿 [한규민](https://github.com/han-gyumin)    
 👾 [진승민](https://github.com/jsm512)    
 🤖 [임지훈](https://github.com/zhoon95)

<br>

# INTRODUCE

### [프로젝트 목표]
__오픈소스로 가져온 TETRIS_GAME에 다양한 기능과 이벤트를 추가한 재밌는 TETRIS_GAME을 만들자!__<br>

<br>

### [개선 사항]

#### - UI 개선
<img src="https://user-images.githubusercontent.com/93397687/207307164-4fa9c30f-9a67-4fe1-9b71-ca6009381945.png" width="600" height="300" >

#### - 모드 간결화
<img src="https://user-images.githubusercontent.com/93397687/207307584-d888c5ea-afce-47dc-bcb2-887658d42186.png" width="600" height="300" >

#### - PvP모드 승리 조건 변경
<img src="https://user-images.githubusercontent.com/93397687/207309257-b4bc002f-b331-4ab9-86ff-b832baaea480.png" width="800" height="300" >

#### - 기능적 개선 사항
- 블록 하강 시 렉 걸리는 현상 
- Score_board 활성화



### [추가한 기능]

#### - 해상도에 따른 보드 칸 변경
- 초기(기본) 해상도 800 x 450 게임 진행 시 10 x 20 
<img src="https://user-images.githubusercontent.com/93397687/207304572-ad38731d-ec1f-4c48-8297-d517911dd602.png" width="600" height="300" >
- 작은 해상도 board_width <= 600 게임 진행 시 7 x 14
<img src="https://user-images.githubusercontent.com/93397687/207303082-03d54ffe-7a05-45d6-84dc-dd458d8871e9.png" width="600" height="300" >
- 큰 해상도 board_width > 1200 게임 진행 시 14 x 28
<img src="https://user-images.githubusercontent.com/93397687/207305485-35eaaa23-0dde-4a12-aa75-a7e9911734d6.png" width="600" height="300" >


#### - PvP 모드 상하 반전
<img src="https://user-images.githubusercontent.com/93397687/207309912-4825a0f5-da66-4faf-8b95-cad7e127aa02.png" width="600" height="300" >

#### - 방해 블록 생성
<img src="https://user-images.githubusercontent.com/93397687/207310112-e9c9b4ea-efba-4547-b45e-79abe245e7df.png" width="300" height="
300" >


#### - 그 외 추가 기능
- 하드모드 & PvP모드 변종 블록 추가
- 모든 모드에 피버타임 추가
<br>


## TO RUN THIS GAME
```
sudo apt install python3-pip
pip3 install pygame
cd 2022-2-OSSProj-TeamTetris-8/Tetris_Game
python3 Tetris.py
```
<br>

## Development Environment
- Linux/Window
- Visual studio code
- Version Control : Git/Github
<br>


<br>

## Credits:
- __Base Source__ (MIT License): https://github.com/CSID-DGU/2022-1-OSSProj-FourGenius-6
- __Background images__ (Pixabay License): https://pixabay.com/ko/photos/%EA%B1%B4%EB%AC%BC-%EC%A7%80%ED%8F%89%EC%84%A0-%EB%8F%84%EC%8B%9C-%EB%8F%84%EC%8B%9C-%ED%92%8D%EA%B2%BD-1850129/
- __Sounds__ (Free License): https://www.bensound.com/

<br>

## References:
- http://www.pygame.org/docs
- https://github.com/CSID-DGU/2021-1-OSSPC-Pint-9
- https://github.com/CSID-DGU/2021-2-OSSProj-Kkanbu-5
- https://github.com/hbseo/OSD_game
