# `django-auth`

Django, DRF, dj-rest-auth, django-allauth를 활용하여 로그인과 회원가입 구현
User Model의 username 대신 email을 사용하도록 변경

## 실행 방법

```
git clone https://github.com/lyikyk/DRF_test.git
cd DRF_test\django-auth
py -m venv venv
cd venv\Script
activate.bat
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

위와 같이 입력하고 http://localhost:8000/ 으로 접속하면 된다.
아래의 URL들 사용하여 api 확인 가능
http://localhost:8000/api/accounts/v1/registration/

http://localhost:8000/api/accounts/v1/password/reset/
http://localhost:8000/api/accounts/v1/password/reset/confirm/
http://localhost:8000/api/accounts/v1/login/
http://localhost:8000/api/accounts/v1/logout/
http://localhost:8000/api/accounts/v1/user/
http://localhost:8000/api/accounts/v1/password/change/
http://localhost:8000/api/accounts/v1/token/verify/
http://localhost:8000/api/accounts/v1/token/refresh/
