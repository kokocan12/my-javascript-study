<h2>정리</h2>
<p>
  1. 맵은 String Integer 말고도 다른 데이터타입을 key로 지정할 수 있음.<br>
  2. has와 같은 key를 탐색할 수 있는 함수가 내장되어 있음.
  3. map.delete(key)를 통해 하나씩 삭제 가능하고 clear를 통해 한번에 삭제 가능
  4. 이외에도 map.size를 통해 크기를 알 수 있음
  5. 삭제가 빈번히 발생하는 경우 object는 delete 연산자를 사용하는데 ex) delete obj.key 성능 이슈가 있기 때문에 Map이 좋은 선택
  6. Map 자체가 Iterable하므로 forEach등과 같이 사용하기 용이함.
  7. object는 내부에 함수를 저장하여 내부 value에 로직이 적용 가능함.
</p>

<h2>결론</h2>
<p>
  단순 데이터 쌍 저장용이라면 Map이 낫다. 그러나 Map은 Object를 대체하지 못한다.
</p>


## [참고 자료]
1. (https://medium.com/front-end-weekly/es6-map-vs-object-what-and-when-b80621932373)


