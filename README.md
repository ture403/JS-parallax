# JS-parallax

<img src="img/parallax.jpg"  width="1000" height="500">

자바스크립트로 작성한 마우스 이펙트 입니다. 

******

📓 사용 스택 및 함수(메서드)
---

➡️ HTML: 웹 페이지의 구조를 정의하는 데 사용됩니다.<br><br>
➡️ CSS : 웹 페이지와 애플리케이션의 시각적 디자인과 레이아웃을 제어하여 사용자 경험을 향상시키는 스타일링 언어입니다 <br><br>
➡️ javascript : 
 + setActive(link): setActive() 함수는 링크가 활성화되었을 때 호출되는 함수로서, 메뉴 링크의 활성화 상태를 변경합니다. 모든 메뉴 링크에서 "active" 클래스를 제거하고, 클릭된 링크의 부모 요소에 "active" 클래스를 추가합니다.
➡️ GSAP :
gsap.utils.toArray(): GSAP의 유틸리티 메서드로서, 선택자를 기준으로 해당 요소들을 배열로 반환합니다. 이 코드에서는 ".parallax__nav ul li a" 선택자에 해당하는 링크들을 배열로 가져옵니다.
gsap.to(): GSAP 라이브러리의 메서드로, DOM 요소를 애니메이션하는데 사용됩니다. 해당 메서드를 통해 커서의 위치를 사용자의 마우스 위치에 맞게 업데이트하는 기능이 구현되었습니다.
ScrollTrigger.create(): GSAP의 ScrollTrigger 플러그인을 사용하여 스크롤 이벤트를 관리하고, 특정 요소들을 트리거로 설정합니다. 이 코드에서는 ScrollTrigger를 사용하여 특정 요소들이 스크롤되면 특정 애니메이션 효과를 적용하도록 설정합니다.

# 프로젝트 목적

---

📕  addEventListener 이해 <br>
📕  getAttribute 이해 <br>
📕  e.client 이해 <br>










