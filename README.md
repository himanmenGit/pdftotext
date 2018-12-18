# PDF파일 텍스트 변환 패지키 비교 (2개)

## `pdftotext` 

* [링크](https://github.com/jalan/pdftotext)

> 상당히 빠르다 `cpp`로 코드를 작성한것 같다. 1.9M pdf파일 기준 약 3.5~ 4.5 초 정도 걸린다.
> 스타가 100개 정도. 

* os별 Dependencies를 설치하자.

## `pdfminer`

* [링크1](https://github.com/pdfminer/pdfminer.six)
* [링크2](https://lsjsj92.tistory.com/304)

> 매우 느리다. 1.9M pdf파일 기준 약 387초가 걸린다..
> 결과값은 뭔가 좀 깔끔하게 나온다..
> star가 3000천개가 넘는다. 뭔가 이유가 있을것 같다.

* 코드 실행이 안될 경우 `chardet`관련 에러가 날 경우 `pip install chardet` 실행