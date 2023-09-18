# var, let, const 차이를 설명해주세요.
ES6 전까지 변수를 선언할 수 있는 방법은 var를 사용하는 것이었습니다.  
하지만 var는 변수를 중복으로 사용하여도 에러가 나지 않고, 오로지 함수 코드 블록만을 지역 스코프로 인정하여 전역 변수를 남발할 가능성을 높입니다.  
이후 이러한 단점을 보완하기 위한 let과 const 가 나왔습니다.  
let은 변수를 중복 선언하면 에러가 발생하고 블록 레벨 스코프를 따릅니다.  
const는 const로 선언한 변수는 반드시 선언과 동시에 초기화를 해야 합니다.  
이후 재할당이 되지 않아 변수나 상수를 선언할 때 사용됩니다.