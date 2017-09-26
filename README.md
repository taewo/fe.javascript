FE개발
======================
FE개발랩에서 프로젝트 및 내부 과제를 수행하면서 생산한 기술 산출물로, 공통 모듈 및 컴포넌트와 개발 가이드 등을 포함합니다.<br>
배포되는 산출물은 FE개발랩에서 개발/관리하며 [MIT 라이선스](LICENSE)로 자유롭게 사용할 수 있습니다.<br>
단, FE개발랩의 동의 없이 임의로 수정하여 사용된 코드에 대해서는 유지보수 및 산출물의 품질을 보증을 할 수 없으니,<br>
추가/수정 요청 및 문의, 버그 신고는 [[Issues]](https://github.com/nhnent/fe.javascript/issues) 또는 [[FE개발랩 DL]](mailto:dl_javascript@nhnent.com)을 이용해주세요.<br>

<br>

## 자바스크립트 개발 가이드

자바스크립트 개발 시 필요한 내용들을 가이드 합니다.<br>
본 문서는 코딩컨벤션, 디버깅, 테스트 등과 같이 기본적인 내용부터 의존성 관리 및 압축까지의 개발 전반에 대한 내용을 다룹니다.

> [자바스크립트 개발 가이드](https://github.com/nhnent/fe.javascript/wiki) 바로가기

<br>

## Application

|Name|Description|Documentation|
| ---- | ---- | ---- |
|[Chart](https://github.com/nhnent/tui.chart)|차트|[[API]](https://nhnent.github.io/tui.chart/latest), [[Example]](https://nhnent.github.io/tui.chart/latest/tutorial-sample01-01-bar-chart.html), [[Tutorial]](https://github.com/nhnent/tui.chart/wiki/getting-started)|
|[Editor](https://github.com/nhnent/tui.editor)|에디터|[[API]](https://nhnent.github.io/tui.editor/api/latest/), [[Example]](https://nhnent.github.io/tui.editor/),[[Tutorial]](https://github.com/nhnent/tui.editor/wiki/Getting-Started)|
|[Grid](https://github.com/nhnent/tui.grid)|그리드|[[API]](https://nhnent.github.io/tui.grid/api), [[Example]](http://nhnent.github.io/tui.grid/api/tutorial-example01.html), [[Tutorial]](https://github.com/nhnent/tui.grid/wiki/Getting-Started)|
 
<br>

## Component

|Name|Description|Documentation|
| ---- | ---- | ---- |
|[Animation](https://github.com/nhnent/tui.component.animation)|애니메이션 효과 컴포넌트| [[API]](https://nhnent.github.io/tui.component.animation/latest/), [[Example]](https://nhnent.github.io/tui.component.animation/latest/tutorial-example1.html)|
|[AutoComplete](https://github.com/nhnent/tui.component.auto-complete)|검색어 자동완성 컴포넌트|[[API]](https://nhnent.github.io/tui.component.auto-complete/latest/), [[Example]](https://nhnent.github.io/tui.component.auto-complete/latest/tutorial-sample1.html), [[Tutorial]](https://github.com/nhnent/tui.component.auto-complete/wiki/Auto-Complete-Tutorial)|
|[Calendar](https://github.com/nhnent/tui.component.calendar/) (Deprecated)|캘린더 컴포넌트|[[API]](http://nhnent.github.io/tui.component.calendar/latest/), [[Example]](http://nhnent.github.io/tui.component.calendar/latest/tutorial-sample1.html), [[Tutorial]](https://github.com/nhnent/tui.component.calendar/wiki/Calendar-Tutorial)|
|[ColorPicker](https://github.com/nhnent/tui.component.colorpicker/)|컬러 피커 컴포넌트|[[API]](http://nhnent.github.io/tui.component.colorpicker/latest/), [[Example]](http://nhnent.github.io/tui.component.colorpicker/latest/tutorial-sample1.html), [[Tutorial]](https://github.nhnent.com/fe/tui.component-colorpicker/wiki/API-Documentation)|
|[ContextMenu](https://github.com/nhnent/tui.component.contextmenu/)|컨텍스트 메뉴 컴포넌트|[[API]](https://nhnent.github.io/tui.component.contextmenu/latest/), [[Example]](https://nhnent.github.io/tui.component.contextmenu/latest/tutorial-default.html), [[Tutorial]](https://github.com/nhnent/tui.component.contextmenu/wiki/English-Version)|
|[DatePicker](https://github.com/nhnent/tui.date-picker/)|데이트 피커 컴포넌트|[[API]](http://nhnent.github.io/tui.date-picker/latest/), [[Example]](https://nhnent.github.io/tui.date-picker/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.date-picker/wiki)|
|[FileUploader](https://github.com/nhnent/tui.component.file-uploader/)|파일  업로더|[[API]](https://nhnent.github.io/tui.component.file-uploader/latest/), [[Example]](http://nhnent.github.io/tui.component.file-uploader/latest/tutorial-example1.html), [[Tutorial]](https://github.com/nhnent/tui.component.file-uploader/wiki/Tutorial)|
|[FloatingLayer](https://github.com/nhnent/tui.component.floatinglayer/)|플로팅 레이어 컴포넌트|[[API]](https://nhnent.github.io/tui.component.floatinglayer/latest/), [[Example]](https://nhnent.github.io/tui.component.floatinglayer/latest/tutorial-default.html), [[Tutorial]](https://github.com/nhnent/tui.component.floatinglayer/wiki/FloatingLayer-Tutorial)|
|[GestureReader](https://github.com/nhnent/tui.component.gesture-reader/)|제스처 리더 컴포넌트|[[API]](https://nhnent.github.io/tui.component.gesture-reader/latest/), [[Example]](https://nhnent.github.io/tui.component.gesture-reader/latest/tutorial-sample1.html), [[Tutorial]](https://github.com/nhnent/tui.component.gesture-reader/wiki/Gesture-Reader-Tutorial)|
|[ImageEditor](https://github.com/nhnent/tui.component.image-editor)|이미지 에디터 컴포넌트|[[API]](https://nhnent.github.io/tui.component.image-editor/latest/), [[Example]](https://nhnent.github.io/tui.component.image-editor/latest/tutorial-basic.html), [[Tutorial]](https://github.com/nhnent/tui.component.image-editor/wiki/Basic-Tutorial)|
|[Layout](https://github.com/nhnent/tui.component.layout)|레이아웃 컴포넌트|[[API]](https://nhnent.github.io/tui.component.layout/latest/), [[Example]](https://nhnent.github.io/tui.component.layout/latest/tutorial-auto.html), [[Tutorial]](https://github.com/nhnent/tui.component.layout/wiki/Layout-Tutorial)|
|[Pagination](https://github.com/nhnent/tui.pagination/)|페이지네이션 컴포넌트|[[API]](https://nhnent.github.io/tui.pagination/latest/), [[Example]](https://nhnent.github.io/tui.pagination/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.pagination/wiki)|
|[Placeholder](https://github.com/nhnent/tui.component.placeholder)|플레이스홀더 컴포넌트|[[API]](https://nhnent.github.io/tui.component.placeholder/latest/), [[Example]](https://nhnent.github.io/tui.component.placeholder/latest/tutorial-sample1.html), [[Tutorial]](https://github.com/nhnent/tui.component.placeholder/wiki/Placeholder-Tutorial)|
|[Rolling](https://github.com/nhnent/tui.component.rolling/)|롤링 컴포넌트|[[API]](https://nhnent.github.io/tui.component.rolling/latest/), [[Example]](https://nhnent.github.io/tui.component.rolling/latest/tutorial-sample1.html), [[Tutorial]](https://github.com/nhnent/tui.component.rolling/wiki/Rolling-Tutorial)|
|[ScrollEnd](https://github.com/nhnent/tui.component.scrollend) (Deprecated)|스크롤엔드 컴포넌트| [[API]](https://nhnent.github.io/tui.component.scrollend/latest/), [[Example]](https://nhnent.github.io/tui.component.scrollend/latest/tutorial-sample1.html), [[Tutorial]](https://github.com/nhnent/tui.component.scrollend/wiki/how-to-use-Scrollend)|
|[SimpleGrid](https://github.com/nhnent/tui.component.simple-grid/) (Deprecated)|심플 그리드 컴포넌트|[[API]](https://nhnent.github.io/tui.component.simple-grid/latest/), [[Example]](https://nhnent.github.io/tui.component.simple-grid/latest/tutorial-sample1.html), [[Tutorial]](https://github.com/nhnent/tui.component.simple-grid/wiki/Simple-Grid-Tutorial)|
|[TimePicker](https://github.com/nhnent/tui.time-picker/)|타임 피커 컴포넌트|[[API]](http://nhnent.github.io/tui.time-picker/latest/), [[Example]](https://nhnent.github.io/tui.time-picker/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.time-picker/wiki)|
|[Tree](https://github.com/nhnent/tui.component.tree/)|트리 컴포넌트|[[API]](https://nhnent.github.io/tui.component.tree/latest/), [[Example]](https://nhnent.github.io/tui.component.tree/latest/tutorial-example1.html), [[Tutorial]](https://github.com/nhnent/tui.component.tree/wiki/Tutorial)|
|[VirtualKeyboard](https://github.com/nhnent/tui.component.virtual-keyboard/)|가상키보드 컴포넌트|[[API]](https://nhnent.github.io/tui.component.virtual-keyboard/latest/), [[Example]](https://nhnent.github.io/tui.component.virtual-keyboard/latest/tutorial-desktop.html), [[Tutorial]](https://github.com/nhnent/tui.component.virtual-keyboard/wiki/Virtual-Keyboard-Tutorial)|
|[VirtualScroll](https://github.com/nhnent/tui.component.virtual-scroll)|가상스크롤 컴포넌트|[[API]](https://nhnent.github.io/tui.component.virtual-scroll/latest/), [[Example]](https://nhnent.github.io/tui.component.virtual-scroll/latest/tutorial-example.html), [[Tutorial]](https://github.com/nhnent/tui.component.virtual-scroll/wiki/getting-started)|

<br>

## Mobile Component

|Name|Description|Documentation|
| ---- | ---- | ---- |
|[AppLoader](https://github.com/nhnent/tui.app-loader)|앱로더 컴포넌트|[[API]](https://nhnent.github.io/tui.app-loader/latest/), [[Example]](https://nhnent.github.io/tui.app-loader/latest/tutorial-tutorial.html), [[Tutorial]](https://github.com/nhnent/tui.app-loader/wiki/AppLoader-Tutorial)|
|[Flicking](https://github.com/nhnent/tui.component.m-flicking/)|플리킹 컴포넌트|[[API]](https://nhnent.github.io/tui.component.m-flicking/latest/), [[Example]](https://nhnent.github.io/tui.component.m-flicking/latest/tutorial-sample1.html), [[Tutorial]](https://github.com/nhnent/tui.component.m-flicking/wiki/Mobile-Flicking-Tutorial)|

<br>

## CodeSnippet

|Name|Category|Description|Documentation|
| ---- | ---- | ---- | ---- |
|[CodeSnippet](https://github.com/nhnent/tui.code-snippet/)||코드 스니펫<br>(자주 사용되는 코드 모음)|[[API]](https://nhnent.github.io/tui.code-snippet/latest/index.html), [[Tutorial]](https://github.com/nhnent/fe.javascript/wiki/Toast-UI-CodeSnippet)|
| |browser.js|브라우저 검출하는 모듈||
| |collection.js|콜렉션 관련 모듈||
| |customEvent.js|커스텀이벤트 모듈||
| |defineClass.js|클래스 관련 모듈||
| |defineNamespace.js|네임스페이스 관련 모듈||
| |enum.js|상수 관련 모듈||
| |exMap.js|맵 관련 모듈||
| |func.js|함수 관련 모듈||
| |hashMap.js|해시맵 관련 모듈|deprecate 예정|
| |inheritance.js|간단한 상속 모듈||
| |object.js|객체 관련 모듈||
| |string.js|문자열 관련 모듈||
| |type.js|타입 체크 모듈||
| |window.js|윈도우 객체 관련 모듈||

## Library

|Name|Description| Documentation |
| ---- | ---- | ---- |
|[Dom](https://github.com/nhnent/tui.dom)|DOM 유틸<br>(DOM 관련 클래스 지정 및 이벤트 바인딩 함수 모음)|[[API]](https://nhnent.github.io/tui.dom/latest/)|
|[TUI JSDoc Template](https://github.com/nhnent/tui.jsdoc-template)|JSDoc Template (JS API 문서화 템플릿) | [[Demo]](https://nhnent.github.io/tui.jsdoc-template/latest/), [[Npm]](https://www.npmjs.com/package/tui-jsdoc-template)|

## License

[MIT 라이선스](LICENSE)로 자유롭게 사용할 수 있습니다.
