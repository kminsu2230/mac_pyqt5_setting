### repo info

    linux에서 사용하는 pyqt5d의 Designer 가 mac에서는 제대로 작동하지않아, QtCreator를 이용하여 사용하는 방법이다.


#### setup info

    * 첨부 된 이미지 파일을 순서대로 보면서 하면 하기 쉽습니다. *

    1. pyqt5의 스크립트를 설치
     ㄴ pip install PyQt5
     ㄴ brew install pyqt5
    
    2. 실행 툴인 QtCreator 설치 - url : (https://download.qt.io/)
    
    3. 설치 후 QtCreator 실행
    
    4. 'Command + ,' 또는 맥 메뉴/Preferences 를 클릭
    
    5. kit 탭에서 QtVersions를 클릭 후 add 클릭
    
    6. 설치된 qt의 qmake를 넣기위해 'Command + shift + g' 를 눌러서 경로를 입력 후 추가 (* qmake 의 위치는 작성자 기준 : /usr/local/Cellar/qt

    7. version에 qmake를 추가 햇다면 kit탭에서 default를 눌러서 version에 추가된 pyqt5(버전)을 선택
    
    8. 새프로젝트 생성 
    
    9. 상단의 파일탭을 눌러 파일 프로젝트 추가
    
    10. Qt탭에서 .ui파일을 생성하는 Qt Designer From 을 생성
    
    11. pyqt5 Desinger 형태로 사용가능

#### OS / Version

     Mac / 5.11

#### content

     install 하는 pyqt5는 최신으로 되기때문에 버전에는 큰 의미는 없음, 원한다면 구글링으로 이전 버전의 qt도 받을 수 있음

#### etc

     pyqt5 를 python2.7에서 세팅을하고 사용하려햇으나 모듈이 같은 장소에 있어도 에러가남 
     (import PyQt5를 불러와지나, qt파일을 컨파일 후 .py파일의 모듈을 불러 오려니 에러 발생)
     현재 python3으로 실행중
