# Typescript 개발에 관한 기록

## Typescript
- MS가 만들었으며, javascript에 data type을 추가한 super-set language.
- Compile 단계에서 명환한 type check를 통해 type이 모호한 이유에 의해 발생하는 error를 사전 검출 가능

### Node.js에서 typescript 사용
- Node.js는 기본적으로 javascirpt를 구동하기 위한 engine이므로 typescript를 직접 지원지 않음
- Typescript는 javascipt의 super-set이므로 typescript에서 javascript로 transcimpile이 가능함
- Transcomple을 통해 node.js에서 typescript를 사용할 수 있음
### 필요 package
    - typescript
    - tsc-watch
