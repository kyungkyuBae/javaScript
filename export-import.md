# export / import 
## export / import를 사용해야하는 이유
* export 문은 JavaScript 모듈에서 함수, 객체, 원시 값을 내보낼 때 사용합니다.
* 내보낸 값은 다른 프로그램에서 import 문으로 가져가 사용할 수 있습니다.


---
## export / import 사용법
* 우선 export(내보내기) 에는 named,default두가지 유형이 있습니다.  

        export { 변수명 }
        import 변수명 from '경로'


- named export 는 여러 값을 내보낼 때 유용하고, import 할때는 동일한 변수명을 사용해야 합니다.

        export default 변수명
        import 받아오고싶은 변수명 from '경로'

- export default는 어떤 이름으로도 받아올 수 있습니다.


    
