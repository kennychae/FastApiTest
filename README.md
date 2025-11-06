# FastApiTest
fastapi를 활용한 간단 웹

ttot = text to text
텍스트를 입력해서 텍스트를 출력하기 위한 도구

atot = audio to text
오디오를 입력해서 텍스트를 출력하기 위한 도구

ttoa = text to audio
텍스트를 입력해서 오디오를 출력하기 위한 도구

------------------------------------------------
# 사용법
## <가상환경 설정>
python -m venv <가상환경 이름>

가상환경에 내용물을 집어넣기 (static, templates, main.py, model.py, test.py)

*개발 환경 python 3.9.8

## <필요 라이브러리>
pip install fastapi[all] uvicorn

------------------------------------------------
### test.py를 용도에 맞춰 수정하기
------------------------------------------------
#### <웹서버 실행>
uvicorn main:app --reload
#### <포트가 사용중일때>
uvicorn main:app --port <다른 포트번호>
