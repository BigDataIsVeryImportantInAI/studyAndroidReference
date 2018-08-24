
안드로이드 래퍼런스 스터디
=

안드로이드 래퍼런스를 공부하기 위해 결성된 스터디입니다. 부천~서울에서 매주 일요일에 모임을 가지고 있습니다.

개인마다 공부하고 싶은 부분을 정해 스터디에 공고 한 뒤 그 부분을 공부하고 요약하여 정리 문서 작성, 토이 프로잭트를 만들어 격주마다 스터디원들에게 발표를 합니다.

현제 인원을 더 받고 있으므로 znfks8819@naver.com 으로 간단한 소개와 연락처를 적어 메일주세요.

* 현제 인원: 4명
* 첫번째 발표: YTY, KTY
* 두번째 발표: SHC, KEG


# Git hube 작업 방법
git bash 를 사용한다는 전체하에 작성하였습니다.
>다운로드 : https://gitforwindows.org/

## 1. 클론 받기

레포지토리로 이동하여 좌측 상단에 있는 초록색 Clone or download 버튼을 클릭합니다.

나와있는 url 을 통해 clone 을 받거나 집으로 받아 압축을 풀어주세요.

git bash 에서 해당 디렉토리로 이동 바랍니다.

![클론 버튼 이미지](/README.img/imgCloneBtn.jpg)


## 2. 브런치 관리

브런치 관리는 상용 브런치인 master, 개발 브런치인 dev, 개인 브런치인 dev-myname 을 사용합니다.

git bash 에서 브런치를 생성해주세요.

>git branch dev-myname

브런치로 이동합니다.

>git checkout dev-myname

한번에 하는 방법
>git checkout -b dev-myname

[브런치 도식도 이미지]

## 3. 작업

해당 브런치에서 각자 자기가 공고한 공부할 부분의 디렉토리를 생성합니다.

>\studyAndroidReference\docs\guides\activities\fragment

