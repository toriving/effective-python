# effective-python

챕터별 jupyter notebook 정리

## Chapter 1.
1. [사용중인 파이썬 버전을 알아두라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter1/better_way_1.ipynb)
2. [PEP 8 스타일 가이드를 따르라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter1/better_way_2.ipynb) 🔥
3. [bytes와 str의 차이를 알아두라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter1/better_way_3.ipynb)
4. [C 스타일 형식 문자열을 str.format과 쓰기보다는 f-문자열을 통한 인터폴레이션을 사용하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter1/better_way_4.ipynb)
5. [복잡한 식을 쓰는 대신 도우미 함수를 작성하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter1/better_way_5.ipynb)
6. [인덱스를 사용하는 대신 대입을 사용해 데이터를 언패킹하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter1/better_way_6.ipynb)
7. [range보다는 enumerate를 사용하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter1/better_way_7.ipynb)
8. [여러 이터레이터에 대해 나란히 루프를 수행하려면 zip을 사용하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter1/better_way_8.ipynb)
9. [for나 while 루프 뒤에 else 블록을 사용하지 말라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter1/better_way_9.ipynb)
10. [대입식(:=)을 사용해 반복을 피하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter1/better_way_10.ipynb) 🔥

## Chapter 2.
11. [시퀀스를 슬라이싱하는 방법을 익혀라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter2/better_way_11.ipynb)
12. [스트라이드와 슬라이스를 한 식에 함께 사용하지 말라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter2/better_way_12.ipynb)
13. [슬라이싱보다는 나머지를 모두 잡아내는 언패킹을 사용하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter2/better_way_13.ipynb) 🔥
14. [복잡한 기준을 사용해 정렬할 때는 key 파라미터를 사용하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter2/better_way_14.ipynb) 🔥
15. [딕셔너리 삽입 순서에 의존할 떄는 조심하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter2/better_way_15.ipynb)
16. [in을 사용하고 딕셔너리 키가 없을 때 KeyError를 처리하기보다는 get을 사용하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter2/better_way_16.ipynb) 🔥
17. [내부 상태에서 원소가 없는 경우를 처리할 때는 setdefault보다 defaultdict을 사용하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter2/better_way_17.ipynb)
18. [\_\_missing\_\_ 을 사용해 키에 따라 다른 디폴트 값을 생성하는 방법을 알아두라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter2/better_way_18.ipynb) 🔥

## Chapter 3.
19. [함수가 여러 값을 반환하는 경우 절대로 네 값 이상을 언패킹하지 말라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter3/better_way_19.ipynb)
20. [None을 반환하기보다는 예외를 발생시켜라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter3/better_way_20.ipynb) 🔥
21. [변수 영역과 클로저의 상호작용 방식을 이해하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter3/better_way_21.ipynb) 🔥
22. [변수 위치 인자를 사용해 시각적인 잡음을 줄여라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter3/better_way_22.ipynb)
23. [키워드 인자로 선택적인 기능을 제공하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter3/better_way_23.ipynb)
24. [None과 독스트링을 사용해 동적인 디폴트 인자를 지정하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter3/better_way_24.ipynb)
25. [위치로만 인자를 지정하게 하거나 키워드로만 인자를 지정하게 해서 함수 호출을 명확하게 만들라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter3/better_way_25.ipynb) 🔥
26. [functools.wrap을 사용해 함수 데코레이터를 정의하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter3/better_way_26.ipynb) 🔥

## Chapter 4.
27. [map과 filter 대신 컴프리헨션을 사용하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter4/better_way_27.ipynb)
28. [컴프리헨션 내부에 제어 하위 식을 세개 이상 사용하지 말라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter4/better_way_28.ipynb)
29. [대입식을 사용해 컴프리헨션 안에서 반복 작업을 피하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter4/better_way_29.ipynb)
30. [리스트를 반환하기보다는 제너레이터를 사용하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter4/better_way_30.ipynb) 🔥
31. [인자에 대해 이터레이션할 떄는 방어적이 돼라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter4/better_way_31.ipynb) 🔥
31. [인자에 대해 이터레이션할 때는 방어적이 돼라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter4/better_way_31.ipynb) 🔥
32. [긴 리스트 컴프리헨션보다는 제너레이터 식을 사용하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter4/better_way_32.ipynb) 🔥
33. [yield from을 사용해 여러 제너레이터를 합성하라](https://nbviewer.jupyter.org/github/toriving/effective-python/blob/main/chapter4/better_way_33.ipynb) 🔥

## Reference
https://github.com/bslatkin/effectivepython  
https://github.com/gilbutITbook/080235
