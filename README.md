# 표준 프레임 워크 Enterprise Business
내부어무 기능 구현시 필수적인 부분만 사용 가능하도록 경량화 된 실행환경 제공

## 환경 설정
프로젝트에서 사용된 환경 프로그램 정보는 다음과 같다.

| 프로그램 명 | 버전 명   |
| :--------- |:-------|
| java       | 1.8    |
| maven      | 3.12.0 |

## 구동방법

### 1. 구동 전 구동 환경 확인 사항 - globals.properties 설정 확인 사항 확인

`src/main/resources/egovframework/egovProps/globals.properties` 에서
`Globals.DbType` 과 그에 따른 섹션의
```
Globals.UserName
Globals.Password
Globals.DriverClassName
Globals.Url
```
이 현재 개발(테스트)환경에 맞춰져 있는지 확인한다. 자세한 사항은 [개발자 가이드 - 환경 설정][환경설정]를 확인한다.

### 2. IDE 구동 방법

개발환경에서 프로젝트 우클릭 > Run As > Run On Server를 통해 구동한다.

상세 구동 방법은 [개발자 가이드 - 시작하기][시작하기]를 참고한다.

---
참고

세부 참고 사항은 [개발자 가이드][개발자가이드]를 확인한다.

[환경설정]: https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:com:v4.0:init_configration

[시작하기]: https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:dev4.0:gettingstarted

[개발자가이드]: https://www.egovframe.go.kr/wiki/doku.php?id=egovframework:%EC%8B%A4%ED%96%89%ED%99%98%EA%B2%BD%EA%B0%80%EC%9D%B4%EB%93%9C

