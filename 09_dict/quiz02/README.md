## 문제) Dict 심화

* 장르:{책-저자} 형태로 이루어진 dict가 있습니다.
* 아래 dict를 이용하여 문제를 푸세요.
```
{장르1:{책제목1:작가1, 책제목2:작가2}, 장르2:{책제목1:작가1, 책제목2:작가2}}

books_dict = {'자기계발':{'말 그릇':'김윤나', '메모의 마법':'마에다 유지'}, '소설':{'아몬드':'손원평', '나미야 잡화점의 기적':'히가시노 게이고', '어린왕자':'생텍쥐페리'}, '과학':{'마음의 미래':'미치오 카쿠', '시간은 흐르지 않는다':'카를로 로벨리', '평행우주':'미치오 카쿠'}}
```

### 1. 장르 별 책 목록 출력하기
* 장르가 소설인 책들의 목록을 list로 출력하세요.

> 출력 예시

```
['아몬드', '나미야 잡화점의 기적', '어린왕자']
```

### 2. 책이 존재하는지 여부
* 책을 검색해서 있으면 "'책 이름' 책이 있습니다." 없으면 "'책 이름' 책이 없습니다." 출력하세요.
* 과학 장르에 '코스모스' 책이 있는지 여부를 출력하세요. 
* 소설 장르에 '나미야 잡화점의 기적' 책이 있는지 여부를 출력하세요.

> 출력 예시
```
'코스모스' 책이 있습니다.
'나미야 잡화점의 기적' 책이 없습니다.
```

### 3. 책 이름으로 저자 찾기 - 어려운 문제
* '메모의 마법' 책의 저자가 누구인지 출력하세요.

> 출력 예시

```
마에다 유지
```

[정답 보기](quiz02.py)
