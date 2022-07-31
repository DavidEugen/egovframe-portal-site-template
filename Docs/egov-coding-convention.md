# Egov Coding Convention

이 문서는 [캠퍼스 핵데이 Java 코딩 컨벤션][캠퍼스 핵데이 Java 코딩 컨벤션] 참고하여 작성되었음.

## 1. .editorconfig 적용
다양한 에디터와 IDE에서 공통적으로 지원하는 코드 스타일에 대한 설정 파일이다.
자세한 스펙은 [editorconfig 페이지][editorconfig]에서 파악할 수 있다.
다양한 에디터로 파일을 고칠 때 같은 규칙을 참조할수 있도록 가급적 이 파일을 소스 저장소에서 올려서 공유하는 것을 권장한다.

## 2. .gitattributes 적용
Unix 형식의 새줄 문자(newline)인 LF(Line Feed, 0x0A)을 사용한다.
Windows 형식인 CRLF가 섞이지 않도록 편집기와 GIT 설정 등을 확인한다.
파일은 디렉토리별로 지정할 수 있다. 전체 프로젝트에 적용한다면 최상위 디렉토리에 둔다.


---
참고.
1. [캠퍼스 핵데이 Java 코딩 컨벤션]: https://naver.github.io/hackday-conventions-java/
2. [editorconfig]: https://editorconfig.org/
