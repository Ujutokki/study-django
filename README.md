# study-django
References: Django 한그릇 뚝딱 책 리뷰, [점프 투 장고](https://wikidocs.net/book/4223)

# Chapter 1
- 튜플 자료형
  - 리스트 자료형과 달리 내부 요소에 대한 추가, 수정, 삭제가 불가능
- 딕셔너리 자료형
  - key-value 쌍으로 이루어진 자료형

```python
# key 접근, 'key'가 존재하지 않을경우 에러
dic1['key'] 
# 에러 발생 없이 'key' 접근, 'key'가 존재하지 않더라도 에러 발생 없음
dic1.get('key')
# 'key'가 존재하지 않는 경우 'default'값을 리턴하게 할 수 있음
dic1.get('key','default')
```
