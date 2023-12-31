# :love_letter: Team project : Ah-oh

### 웹사이트 리디자인, 사이트 구현을 목표로 한다 (반응형 웹사이트 제작) <br> Making homepage(neo digital group)

> TEAM PROJECT site: [click🌐](https://ah-oh-team-project.github.io/make_neoDG/index-ah-oh.html)<br>
> git hub site: [click🌐](https://ah-oh-team-project.github.io/make_neoDG/) <br>
> notion site: [click🌐](https://www.notion.so/Team-Project-Ah-oh-d201d4fcb7a749b3a4d7d144dc31513b) <br>
> google-sheet site: [click🌐](https://docs.google.com/spreadsheets/d/1yiq65yUBoeE5xjIBpyG7Syw865Bxr23vybb4IEW3J3o/edit?hl=ko#gid=2040591431)<br>
> google-slides site: [click🌐](https://docs.google.com/presentation/d/1hNUKbtyGXCIqX4KJQZ0BC7rGdM36yLEDdiOziVsSQqk/edit#slide=id.p) <br>
> NEO Digital Group: [click🌐](http://neodigitalgroup.co.kr/)

# :boom: Project Timeline

## 23.11.13 [발표 및 보고서 제출]

## 23.11.10 [작업 마무리 및 발표 준비]

## 23.11.08 [작업 중간점검]

###### j(재영)

- **어바웃**
  - 헤더에서 넘어올때 배경 자연스럽게 만들기
  - 배경 원 등장 애니메이션 적용하기
- **컨텍트**
  - pc버전 효과 다시 수정하기
  - 버튼 안눌리는 것 수정하기

###### K(민재)

- **헤더**
  - 메뉴 고정?(모바일+중간값)
  - 헤더 메뉴바 fix 고정으로 미디어쿼리 적용 필요 (px)
- **솔루션**
  - 중간값 미디어쿼리 작업
  - 핀 고정
  - 넘버(지구) 주황 선

###### M(지민)

- **왓위두**
  - 페이지 넘침 해결하기
- **워크**
  - 터치 슬라이드 선택 영역 넓히기
  - pc 이미지 사진 줄이기
  - 모바일 이미지 여백값 줄이기

## 23.11.06

###### j

- 미디어 쿼리 적용 시, flex 정렬이 제대로 인식되지 않아 컨텐츠 정렬에 문제가 생김.
- 그리드로 변경하여 정렬 시도.

###### K

- 배경의 circle 블러 효과 처리에 어려움이 있었으나 필터 효과를 적용하여 해결.
- 애니메이션으로 컨텐츠 움직임 해결.

###### M

- what we do 컨텐츠 고정되지 않음.

## 23.11.05 미팅 [14:00 오산대역 할리스 DT점]

- [x] html, 모바일버전 css 작업 완료.
- [x] 파비콘, og 적용 완료.
- [x] html, 모바일버전 css 파일 하나로 정리 == index-m.css
- 미디어쿼리 작업 진행 시 파일명 : index-pc\_$.css ($ == 본인 이름 대문자명)
- 미디어쿼리 작업 M-T-PC 무조건 오늘 안에 마무리 (내일 수업 전까지 꼭!!)
- 내일 오후 팀 작업 시간부터 JS, GSAP(마우스이벤트) 어떻게든 작업해보기.
- 각자 맡은 영역 화요일까지 해보고, 안되는 부분은 다같이 수요일부터 작업해보기.
- 목요일은 발표준비까지 생각하고 작업해야 할 듯.

#### 23.11.05 [작업 중간점검 수정사항]

###### 헤더

- 로고 이미지 추가 필요
- 로고 텍스트 크기 조절 필요할것같아요
- 메뉴바 누르면 서브메뉴 없음
- 공통 서체 적용 안됨
- 배경 circle 그라데이션 다시
- menu 아이콘 메뉴 선택 시 화면이 유지되지 않고 깜빡거리며 사라짐
- menu 아이콘 메뉴 선택 시 검은 background 슬라이드가 내려와야함

###### 메인 1-1

- pc 사이즈 작업 필요

###### 메인 1-2

- 배경 circle 사이즈 줄여서 넘치지 않게 하기

###### 메인 2-1

- 공통 서체 적용 안됨
- 라인 각도가 다 같아서 서로 다르게 적용 필요
- 라인이 이미지 밑으로 갈수 있게 z-idex 정리
- 모바일이상 사이즈에서 정렬이 안맞음

###### 메인 2-2

- 공통 서체 적용 안됨
- 모바일이상 사이즈에서 정렬이 안맞음

###### 메인 3

- 모바일이상 사이즈에서 정렬이 안맞음

###### 메인 4

- 모바일이상 사이즈에서 롤링 이미지 사이즈 크기 작음

###### 메인 5

- 모바일이상 사이즈에서 푸터랑 영역 겹침
- pc 사이즈 작업 필요

###### 푸터

- adress 정렬이 안맞음
- p margin left 값 없애기

###### 클래스명 가이드라인과 다르게 정리가 잘 되지 않음.

###### _css 공통으로 맞춰야하는 사항_

###### j

- 제목 및 텍스트 요소 width: 90vw;/ margin: 0 auto;

###### K

- 제목 및 텍스트 요소 width: 80% / margin: 0 auto;
- solution section 제목요소 margin-left 20px

###### M

- 제목 및 텍스트 요소

## 23.11.01~04

#### 문제점 발생

1. 각자 작업한 부분 중 일부 js가 제대로 작동하지 않음.
2. 폰트가 연결되지 않아 디자인적으로 다소 부족함.
3. 현재까지 작업 파일 합친 후, 레이아웃 규격이 넘치고 정렬이 흐트러짐.
4. 헤더가 보였다 숨겼다 하는 문제가 발생.
5. 가이드라인으로 맞추기로한 클래스명이 생각보다 정리가 되지 않음.

#### 해결 방법

1. - [x] 누락된 외부 링크 찾아 다시 연결.
2. - [x] variable.css 사용해서 폰트 연결 및 코드 정리.
3. - [x] 넘치는 이유 찾아서 수정 진행.
4. - [ ] z-index를 이용하여 정리해보았으나, GSAP와 충돌로 해결이 안됨.
5. - [ ] 다시 정리해보려고 했는데 이미 작업 진행중인 상태에서 해보려니 코드가 너무 꼬여서 수정없이 진행하기로 함.

#### ~11/4까지

- 모바일버전 css 각자 최대한 완벽하게 작업 완성
- variable.css 사용해서 폰트 정리
- PC까지 css 미디어쿼리 완성
- 사이즈는 vw -left, right / vh - top,buttom 같은 단위로 작업
- 큰 영역에 px 같은 고정 값 없애기
- 나눠서 작업한 파일이 있으면 합치기(1인당 css, js 파일 1개씩)
- 개인 파트에 맞춰서 필요한 gsap 찾아서 공유&공부해오기

#### 11/5 [팀 미팅]

- 각자 설정되어있는 z-index 순서 정리하기
- 합친 파일에서 문제생기는 오류 찾아서 코드 정리 및 수정
- js 작업 진행. 플러그인 gsap 스크롤 이벤트 추가 작업

#### 다음주차부터 각 파트 부족한 JS 작업 진행 할 예정

- 각자 섹션별 css, javascript 작업 진행.
- 맡은 영역 최대한 웹사이트와 동일하게 구현 완성 목표로 작업.

## 23.10.31

- 각자 섹션별 css 작업 진행
  - css 작업 마무리 되는대로 모여서 정리 진행하기로 결정.
- index.html 각자 파트 작업 병합 및 index 큰섹션 (header/main/footer) 이용해서 정리하기.
- html W3 유효성 검사 완료.
- 퍼블리싱 가이드 작성 수정사항 -> develop 완료.

- assets 폴더 정리하기
  - font.css : font는 총 3개로 정리.
    - 영문 폰트 : ① 'Archivo', sans-serif / ② 'Playfair Display', serif
    - 한글 폰트 : ③ 'Pretendard Variable', sans-serif
  - variable.css
    - 23.10.31 : 폰트만 설정
- variable.css 같이 의논해서 정리하기 -> 현재 섹션마다 사이즈가 너무 상이해서, 추후 각자 css 작업 완료 후 병합 시 변수로 사이즈 통일 정리하기로 함.

## 23.10.30

- index.html 작업 진행.
- 퍼블리싱 가이드 작성.
  [231030\_코딩가이드\_ah-oh.pdf](https://ah-oh-team-project.github.io/make_neoDG/%EC%9E%91%EC%97%85%20%EC%9E%90%EB%A3%8C/231031_%EC%BD%94%EB%94%A9%EA%B0%80%EC%9D%B4%EB%93%9C_ah-oh.pdf)

## 23.10.27

- 퍼블리싱 사이트 구조 분석.
- 사이트 구축 요구사항 정리.
  [231026\_요구사항+구조분석.pdf](https://ah-oh-team-project.github.io/make_neoDG/%EC%9E%91%EC%97%85%20%EC%9E%90%EB%A3%8C/231026_%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD+%EA%B5%AC%EC%A1%B0%EB%B6%84%EC%84%9D_ah-oh.pdf)

## 23.10.26

- 팀 프로젝트 목표 설정.
- 사이트 구조 분석 및 작업 역할 분담.
- 팀원별 맡은 영역에 대한 퍼블리싱 가이드 분석.

### 목표

1. 플러그인 GSAP를 공부하여 최대한 기존 사이트와 유사하게 구현 할 수 있도록 한다.
2. git organization을 이용한 협업을 통해 팀원들과의 협업이 문제없이 이루어지도록 하는 것을 목표로 한다.
3. 팀 프로젝트 경험을 통해 원활한 커뮤니케이션 능력을 키운다.

### 선정 사이트

[NEO Digital Group](http://neodigitalgroup.co.kr/)

### 사이트 선정 이유

- 이번 팀 프로젝트를 통해 수업 외 새로운 플러그인을 추가로 공부하며 작업하고 싶었다.

### TEAM: ah-oh

- 팀장: 한재영
- 팀원: 김민재, 권지민

- 역할분담

  - Github 관리: 한재영
  - notion 관리: 권지민
  - 자료(site text&img) 관리: 김민재

- 웹사이트 제작 역할 분담
  - 메인페이지 총 6개의 섹션을 난이도별로 나눠, 상-중, 하 순으로 2part씩 작업 분담.
    - 한재영: about / contact
    - 김민재: header+footer / solution
    - 권지민: what we do / our work
