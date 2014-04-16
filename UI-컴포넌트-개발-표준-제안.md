## 개요
UI 컴포넌트를 개발할 때의 표준을 제안한다. 가령 서비스에서는 어떻게 호출해야 하는지 UI 컴포넌트 명은 어떻게 만들어야 하는지에 관하여 이다.

## 컴포넌트 명명 규칙
모든 컴포넌트의 접두어는 egov로 시작한다.
예) egovGrid, egovTab

## 컴포넌트 JavaScript API 규칭
모든 컴포넌트는 컨트롤러에서 다음과 같이 컴포넌트 자바스크립트 인스턴스를 가지고 올 수 있다.

    controller('sampleCtrl',function(componetQuery){
     var componentInstance = componetQuery('#componentId');
     componentInstance.methoA();
     componentInstance.methoB();
    }

componentId는 아래와 같이 지시자를 템플릿에서 선언할 때 id태그로 작성해야 한다.

<egov-grid id="componentId"></egov-grid>

