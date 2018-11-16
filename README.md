# django를 사용해보자

## 1.장고 가상환경 만들기
     ※왜 가상환경인가? 한 PC로 여러가지 프로젝트를 빌드할때 필요한 패키지의 버전이 달라, 매번 패키지를 재설치해야하는 어려움이 있을 수 있다.(최신버전이 항상 옳은게 아니다...때에 따라 하위호환이 안되는 케이스 다수 있음) 따라서 고립된 개발환경을 구축하기 위해 virtualenv라는 가상환경 패키지가 존재한다. 오늘은 윈도우 환경에서 이걸 설치해보자.
###   -PowerShell 관리자모드에서 디렉토리 생성
      'mkdir 디렉토리명'
###   -해당 디렉토리에서 가상환경 설정
      'python -m venv 가상환경명'


