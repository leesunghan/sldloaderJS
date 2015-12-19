# sldloaderJS
AutoCAD SLD파일을 Canvas에 그려주는 JavaScript Viewer

[사용방법]
//
//@param contents : FileReader로 읽은  자바스크립트 객체
//@param   canvas : HTML5 의 canvas element 요소
var result = new LEE.SLDLoader().draw( contents, canvas );
