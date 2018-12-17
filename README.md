### repo info

    linux에서 사용하는 pyqt5가 mac에서는 제대로 작동하지않아, Qtcreator를 이용하여 사용하는 방법이다.


#### setup info

    * 첨부 된 이미지 파일을 순서대로 보면서 하면 하기 쉽습니다. *

    1. pyqt5의 스크립트를 설치
     ㄴ pip install PyQt5
     ㄴ brew install pyqt5
    
    2. 실행 툴인 QtCreator 설치 - url : (https://download.qt.io/)
    
    3. 설치 후 QtCreator 실행
    
    4. 'Command + ,' 또는 맥 메뉴/Preferences 를 클릭
    
    5. kit 탭에서 QtVersions를 클릭 후 add 클릭
    
    6. 설치된 qt의 qmake를 넣기위해 'Command + shift + g' 를 눌러서 경로를 입력 후 추가 (* qmake 의 위치는 작성자 기준 :  )
    
    
    
    



#### OS / Version

     Mac / 5.11

#### content

     install 하는 pyqt5는 최신으로 되기때문에 버전에는 큰 의미는 없음, 원한다면 구글링으로 이전 버전의 qt도 받을 수 있음

#### etc

     pyqt5 를 python2.7에서 세팅을하고 사용하려햇으나 모듈이 같은 장소에 있어도 에러가남
     현재 python3으로 실행중
