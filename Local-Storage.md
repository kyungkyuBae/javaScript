
# Local-Storage 
## LocalStorage 를 사용 하는 이유
* 데이터를 어딘가에 저장해야하는 일이 생긴다면, 데이터베이스에 저장해야 합니다.  
하지만 저장해야할 데이터가 별로 중요하지 않거나, 유실되도 무방할 데이터라면,  
간단하게 LocalStorage에 간단하게 데이터를 저장할 수 있습니다.


---
## LocalStorage 사용법


        // 키에 데이터 쓰기
        localStorage.setItem("key", value);

        // 키로 부터 데이터 읽기
        localStorage.getItem("key");

        // 키의 데이터 삭제
        localStorage.removeItem("key");

        // 모든 키의 데이터 삭제
        localStorage.clear();

        // 저장된 키/값 쌍의 개수
        localStorage.length;





    
