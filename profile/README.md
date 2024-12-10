# Mockin

## KIS API를 활용한 모의투자 서비스

## 목차

- [프로젝트 소개](#프로젝트-소개)
- [팀원 소개](#팀원-소개)
- [리포지토리](#리포지토리)
- [API 명세](#API-명세)

## 프로젝트 소개

Mockin은 [한국투자증권에서 제공하는 오픈 API](https://apiportal.koreainvestment.com/about)를 활용해 만든 모의투자 서비스입니다.

핵심 기능은 아래와 같습니다.

1. 주식 정보 검색 및 조회
2. 주식 매매
3. 주문 내역 조회

이외에도 뉴스 헤드라인 및 주식 즐겨찾기 등록 등의 기능을 제공해줍니다.

앱을 활용해보고 싶으신 분은 [다음 링크](https://github.com/Mockin-2024/frontend/releases)에서 다운받으시거나,
[이 사이트](https://mockin-2024.github.io/frontend/)에서 이용 가능합니다. 앱의 경우 현재는 안드로이드만 지원합니다.<br/>

이용 시 KIS API에서 모의투자 및 실전 투자용 API 키를 발급받아 등록하는 과정이 필요하니,
[이 페이지](https://apiportal.koreainvestment.com/howto-use)를 참고해주세요.<br/>
등록하지 않을 경우 서비스 이용이 어렵습니다.

로그인 시 KIS API에 등록된 SNS로 OpenAPI 접근 토큰 발급 메세지를 받을 수 있습니다.<br/>
오픈API 접근 토큰의 경우 '현재가 10호가'와 같이 실전 도메인에서만 활용가능한 API를 위한 것으로,<br/>
이외의 목적으로는 사용되지 않으니 걱정하지 않으셔도 됩니다.

## 팀원 소개

|                                             강현수                                             |                                              김혁민                                              |                                         최수영                                         |
| :--------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: |
| [<img src="https://github.com/Richter3766.png" width="100px">](https://github.com/Richter3766) | [<img src="https://github.com/KimHyeokMin0.png" width="100px">](https://github.com/KimHyeokMin0) | [<img src="https://github.com/suy0594.png" width="100px">](https://github.com/suy0594) |
|                                             백엔드                                             |                                            프론트엔드                                            |                                         백엔드                                         |

## 리포지토리

**백엔드**: [<img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white">](https://github.com/Mockin-2024/backend)

**프론트엔드**: [<img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white">](https://github.com/Mockin-2024/frontend)

## API 명세

[<img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white">](https://api.mockin2024.com/docs/index.html)
