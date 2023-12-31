# A simple python wrapper to test mbti
### 모듈 설치
```python
pip install requests bs4 lxml pandas
```
### 함수 목록
```python
from mbti import *

print(get_relationship("ENTP","ENFJ")) # mbti 궁합 출력
>> 아주 좋은 관계가 될 수 있음!
print(get_test(0)) # mbti 지문 출력 (0~59)
>> 주기적으로 새로운 친구를 만든다.
print(get_info("INFP")) # mbti 정보 출력
>> {'mbti': 'INFP', 'nickname': '중재자', 'description': (유형 해설문), 'avatar': (아바타 이미지링크)}
print(get_avatar("ISTJ")) # 아바타 이미지 url출력
>> https://i.ibb.co/bH0q8vb/istj.png
print(get_result(-3,3,0,2·····) #mbti 검사 결과 출력 (동의 -3 ~ 3 비동의)
>> {"mbti": "ENFP-T","nickname":활동가,"description":(유형 해설문),"url":(공유 url),"avatar":(아바타 링크)}
```
