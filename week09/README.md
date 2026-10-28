# week09

## 무엇을 하는 코드인가
영화진흥위원회(KOBIS) 오픈 API로 특정 날짜의 일별 박스오피스 목록을 조회하고, 첫 번째 영화의 제목을 출력합니다.

## 설치
```
pip install -r week09/requirements.txt
```
그리고 저장소 루트에 `secret.py` 파일을 만들고 KOBIS API 키를 넣습니다.
```python
API_KEY = "발급받은_키"
```

## 실행
저장소 루트에서 실행합니다.
```
python -m week09.main
```
