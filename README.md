# django를 사용해보자


## 1.장고 가상환경 만들기
### 1)왜 가상환경이 필요할까?
한 PC로 여러가지 프로젝트를 빌드할때 필요한 패키지의 버전이 달라, 매번 패키지를 재설치해야하는 어려움이 있을 수 있다.

*(최신버전이 항상 옳은게 아니다...때에 따라 하위호환이 안되는 케이스 다수 있음)*

따라서 **고립된 개발환경**을 구축하기 위해 **virtualenv**라는 가상환경 패키지가 존재한다. 

본 튜토리얼에서는, 리눅스를 잘 활용할 수 없는 필자와 같은 컴알못을 위해 **윈도우 환경**에서 구축해보도록 하겠다.


### 2)파이썬 가상환경은 어떻게 설치할까?
####   -PowerShell로 필요한 위치에 디렉토리 생성
      mkdir 디렉토리명
####   -해당 디렉토리에서 가상환경 설정
      python -m venv 가상환경명
####   -가상환경 실행해보기
      virtualenv설치경로\가상환경명\Scripts>activate
            
어떤가, 실행이 잘 되었는가?

그렇다면 이 가상환경에 장고를 설치하기 위해 activate된 가상환경을 종료해보도록 하겠다.

      virtualenv설치경로\가상환경명\Scripts>deactivate
     
     
### 3)이제 장고를 설치해보자!

      virtualenv설치경로\가상환경명>pip3 install django
      
만약에 설치가 안된다면,, pip버전을 업데이트하고 다시 시도해보자.
      
      virtualenv설치경로\가상환경명>pip3 install --upgrade pip
     
자 이제 설치가 완료되었다.
이것으로 무엇을 할수있을까는 다음편을 기대하시라 
