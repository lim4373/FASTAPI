# FastAPI

## 프로젝트 전체 구조

![image](https://github.com/lim4373/FASTAPI/assets/114973162/472690a1-e412-43a9-86eb-14cd1fb6bc5c)

* main.py
  * main.py 파일에 생성한 app 객체는 FastAPI의 핵심 객체이다.
* 데이터베이스를 설정하는 database.py 파일
* 모델을 관리하는 models.py 파일 (파이썬 데이터베이스 도구인 SQLAlchemy, mysql)
* API를 구성하는 domain 디렉터리
  * 질문 (question)
  * 답변(answer)
  * 사용자(user)  
