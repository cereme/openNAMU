## 개요
오픈나무 정식 버전 입니다. 파이썬 Bottle 기반으로 돌아 갑니다.

## 수정된 기능
 * [recent_changes] 로 최근 수정된 문서목록 table추가가능
 * 연달아 같은 문서가 수정된 경우 생략 기능...은 나중에 시간나면
 * [imglink(링크)]로 img src 삽입가능
 * 추적 삭제

## 설치법
밑의 의존성을 설치하고 app.py를 파이썬 3.5 이상 버전으로 실행하세요.

첫 번째 가입자에게 소유자 권한이 부여됩니다.

## 기타
 * [테스트 서버](http://namu.ml/)
 
## 클론하는 방법
### 일반
 * git clone https://github.com/2DU/openNAMU.git

### 베타
 * git clone -b beta https://github.com/2DU/openNAMU.git 
 
## 의존성
 * [파이썬](https://www.python.org/downloads/) 3.5 이상
 
### 윈도우
 * pip install -r requirements.txt
 
cmd에 치면 됩니다.
### 우분투
 * sudo apt-get install python3-pip
 * pip3 install -r requirements.txt
 * 참고 sudo apt-get install libffi-dev (cffi 설치오류)
터미널에 치면 됩니다.
### 자세한 설명
 * [참조](http://namu.ml/w/오픈나무%2F설치법)
 
## set.json 설명
 * db = 데이터베이스 이름
 * port = 위키 열 포트 (기본 : 3000)

set.json를 삭제하면 다시 새로 만들 수 있습니다.
