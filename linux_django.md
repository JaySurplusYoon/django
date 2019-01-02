# 리눅스에서 장고 실행하기

## 1)virtual lenv 실행 
- myvenv/bin/ 경로에서 activate 실행해주자
   ```{.no-highlight}
   경로$ source activate
- 이제 경로앞에 (myvenv)가 붙은 것을 확인할 수 있다.
  
## 2)장고 서버 실행
- manage.py가 있는 폴더에서 해당 파일을 실행하자. 필자의 경우 djangogirls에 해당 파일이 있다.
   ```{.no-highlight}
   djangogirls$ python manage.py runserver 0:8000
- 서버를 종료하려면 Cntrl +C ~!
