![image](https://github.com/Marrymo-s/Marrymo/assets/84389492/786361a6-e018-4692-8cb0-44e41c68c73c)# 🥉 Marrymo (모바일 청첩장 제작 및 축의금 내역 문서화 서비스)
### SSAFY 10기 특화 프로젝트(핀테크) 4반 3위 :v: 팀 했다치고 :v: <br /> (2024.02.26 ~ 2024.04.04)![marrymo introduction](https://github.com/Marrymo-s/Marrymo/assets/84389492/0c4e1f82-39a7-40bb-95e3-6b828b36be1e)

## :notebook_with_decorative_cover: 목차 :notebook_with_decorative_cover:
:one: [프로젝트 소개](#1-프로젝트-소개) <br/>
:two: [개발 환경](#2-개발-환경)<br/>
:three: [기술을 채택한 이유](#3-기술을-채택한-이유) <br/>
:four: [브랜치 전략](#4-브랜치-전략) <br/>
:five: [기능별 페이지](#5-기능별-페이지) <br/>
:six: [핀테크 프로젝트 특징 기술 소개](#6-핀테크-프로젝트-특징-기술-소개) <br/>
:seven: [트러블 슈팅](#7-트러블-슈팅) <br/>
:eight: [설계 문서](#8-설계-문서) <br />
:nine: [팀원 소개 및 역할](#9-팀원-소개-및-역할) <br />

## 1. 프로젝트 소개
### :ring: Overview :ring:
#### "결혼 준비 생각하면 머리 아프신가요? 걱정마세요. 저희 Marrymo가 도와드립니다!"
##### 안녕하세요. 결혼 준비를 간편하고 편리하게 만들어줄 모바일 청첩장 제작 및 축의금 송금 서비스를 제공하는 marrymo입니다.<br /><br /> 예비 부부들은 marrymo를 통하여 모바일 청첩장을 제작해볼 수 있고 정산된 축의금은 marrymo에서 등록한 계좌로 받아볼 수 있습니다. 또한 정산된 축의금 내역 정보를 메일을 통해 엑셀로 받아 보실 수 있습니다.

## 2. 개발 환경
### :books: Tech Stack :books:
#### Backend
- common <br />
![SpringBoot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white)
![SpringSecurity](https://img.shields.io/badge/spring_security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white) 
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![JAVAAZUL](https://img.shields.io/badge/JAVA_AZUL-blue?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAAh1BMVEXe5uzAztqxwtHc4OT09PT19fXw8PCqu8rn5+f8/Pzs0Lf6+vrnrXrleiugscLk5OT39/fs7OzkcR7lx6zh4eHhr4LhZRLhpW+Vp7fd3d3gYA6Knq3W1tbbbhzXoW1cepV6jZ6EmKdIZoJWc4vQ0NB8kJ6otb3Ly8twhZV1jqW5vcK9yM9ofY52NCXaAAAAr0lEQVR4AU3KhUIDMQwA0BwrWWftZWQSLrDq/P+/jxPsVaIAzcs/TV/PzOsI+2dmDcztYoTLVf/bed9YDXC9MX3oG863PVpv6c20rXfg2BiDuz0ftmgMOzgKItKe9nsiRDn2DSKyG3m3Vpj6RqfWq+rHp8opiHYQ1XNKub8dp1Ai1MIi554rJYVLhXAR0Zz6DU1BLwGCsmqZMGuAq7K7nSbe6hXqnf/4e4VHfP4TH1/dVRTdLcfq+gAAAABJRU5ErkJggg==)
![SWAGGER](https://img.shields.io/badge/SWAGGER-85EA2D?style=for-the-badge&logo=swagger&logoColor=white)
![LOMBOK](https://img.shields.io/badge/LOMBOK-red?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAtFBMVEVHcEygNR+VOx6KRSKfNiCjOCDBXEmnOCCNMxx+LBpiZTKYNB2QOCI8GRSKMhyfNx5fHBNteRFyig50hBF5MySVNB0/FAamQS1dIhWMOB2PKR+ZMR+0VEKUKBxwgAx0hA92gxaLMx+lQCywTDmPMx+qOSKfSDaNQS62WUd5hxapPSuNTBtvahB2hg+NnSazOyOwOiKxOSCxNh+rNSJ7aRS8TzqVVBp9jRrHbFxlexK2RS90ehMTEzKlAAAAL3RSTlMA3YkY7PX++Wo5A3xQDEX9JTYpVk7+F7hRwi6l15T+7pdy5+FljaFp6IbOsqXbdAzO+/0AAAC5SURBVCiR7ZBXDoJAFACXsixNOtIRe3fpRe9/LxdMbAkXMM7fy7wOwB8CY4ijzkySvT4mz6ZuGkBzXUu2hMmXnAGgBYdwx7LsYhk6m+30XV7EqK4LjFN85bi25RAVPb0eN03T3XJMyLI8xxVXVTbNPLY0TmXclUVKagl9RpZhjGh/WIA5lmVNVKHaKkQIQlSQGSmkhd76tEexVCBJc75nxUtrh4JI9YbOoiYon2cwgiLLyise/9PPcwfMqhMIsZ8FSwAAAABJRU5ErkJggg==)
- marrymo <br />
![SpringDataJpa](https://img.shields.io/badge/Spring_Data_Jpa-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
- bank <br />
![Mybatis](https://img.shields.io/badge/Mybatis_Spring_Boot_Starter-orange?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAwFBMVEVHcEwEBAQSDg4YEA0GBQUekP8FBAQcSnwfGBgekP8UCAMOCwsLBwcnHx89MDAekP8iZKkAAAADAgIekP9EODkekf8bjPk0KSk+MTEekP8ekP8ekP8rIiIhW5YUEBAoYqMhf90givMBAQEOCwspIB8HBgYWEBAgGRgjHBw7Li0bFRUbkf8uJCQ0KCdCNjhKPj0Vi/lVQ0MmieovHhIjcsQtO1IpSHAyV4Vttf9Lpf+o0vxNaodUgLKEp85gWlCnrrXJ7Ah8AAAAInRSTlMA1cFypbPhCx5KkFE/Odd1/u9hHHTIk6ac56Q75tXsedryFhyypAAAAUlJREFUKJGt0clygkAQBmBAQAYUUOOeFWYF2QSX7O//VmlkFGOsVA7pA5ev+u+eRlH+VN3fzFhehxGCj2csDHQF0XzURd7EmxiHjO73CYsxQktkzAH7U9d1Z/0f26B4rNhlIoRI05tz7QwtRRnHj5W/227SNMvOVSf3Wuchj6HyPF/v/KeRzIRQh9AIl9san/f5y2fmew32BqqmM8Yxo5sqjveA2cfbRHaaQRjxFawhGN9WkP38/rr27eZFw4BQhhORFRku8WZXraHuesd1ZGtWpBzj8vCcdl09rFsBC8DVKgG12iOYsGwi0gKmgiZJ4p7M0khI61zBmGydnc4zCAhoxBmNGG+0SbWGagAFGoaURlKnzQXMIGiQSKyDb+U6dnDUsFXnONEZXCrvtH/E0slJKei51YMPLMdqPeWiLMdWVdNUNbt/Sf9eX9pxNOWr5VNzAAAAAElFTkSuQmCC)
#### Frontend
![Next13](https://img.shields.io/badge/Next13-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAAAe1BMVEVHcEwdGhYdGhcODAuabFoAAAAREg8PDQrEfGgiHhrSiXUGBQSLXEokIh+wc18dGBR8XlJbVktURTtdWlFEPjhCPDY5NS89OTMtKiVJQTpxYlczMCt1ZlokIBxPRj9hVUtZT0UTExFoXFJ9UUCSg3N/dWqeYEbOVyqlPB4jT27bAAAAFHRSTlMAqIox/gk+cvrp+lj+zPoe4Oa0gtfDlpAAAAGJSURBVCiRlZLXcuMwDEXVbBU7tpMFUdglueT/v3BJKbGc2bws+KABz6DwXhXFf8ZHiPVLWu9eEsEZ37b0oqXK3/O+PhcVdcORn+xPYKa2evcxChk3d12zwXdz6tBEUeIViBi8H7e26IehQyUCIOABwPBhg3HojgogVQIQKQXUPmFJ3T3dKA/KhNvNenRm/w17mhHACwhdb1prO7Hgbr88r/JEsIS56knfQ6bmOlwyXQmNooLV8fEIqVbFrjslmQ5rlTJA6VpP0Vqtg+uGS15nLUz1OGlrbQhutNqZj9z1LTNsGgIzWTfyOI5sJ7e+ps89Q3M6GoraJTR6rSPjBudT0xgiO8lnuFptDeIi0tKWmqOA4mjDY07LeofmnGH7XAjIxekz2MywX/TZmfUtWXRiTs44RjRf6pYqG5VYmk1o0lGI7kvaHSe6hleSDFAK3VP4AyefIDsp2RkhdJtlRetQKBtJiiDNe2Xp7+sZ0zxIB4H7ffEzKueY2TC7/lD8G3VblWXZ1r+gX+MvRD0sQ1ZcHdsAAAAASUVORK5CYII=)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![vanillaextract](https://img.shields.io/badge/vanilla_extract-orange?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAMAAABF0y+mAAABF1BMVEX////57fH04ef8+PnYapDjrL3kssLyhar0fqbfl67rydPfdpnyd6D4kLP4g7DvcJvcfJz0bpr6h633lLb3kK77um75earreqHfn7T8fKW+qMvnnL3oqb3crbniucb4mbj3ob7xpr/mUYXchqP7fJn/apn/YJbt1t3zrrvmubH7k4Xuc67Oasj/rcryus3tTITZmXnA19phiJjxX5DkcYfKWH9bp619sLZFS0diQC7BaHnDVXGK3etKmKRYYV9lMQNxQRSVSzW3U1bLWWvWWnWARi5hNxNXTEVLeoHS7fJO3fJM2O1glZtsfXh3Yk+CQg+BQQd2Vz1ghYZIxNZL1OhJ0ON7y9lI1+1LzeBJyNpbwdHi8POUz9qVjxuOAAABE0lEQVR4AbzQQwIDQRBA0XhsxrY1tu9/odha5m9fs1L/KJ35gdlc/jsWABD6QjCCYjgBfzySpGiG5XhB/IBIsVTGMJyuVCtv+2oAw9Qbh5pAK/uCbZqmwWKnWCx2e0T/2TLMYMhg9Agsjicg+nJubTptNGZ1BsMAAOzOn7fCh0PpQyBYpHqL1tOglqviKYqadLvrzVZ6fJKsqNpB1ud0VZEf0DAt23E9PwgC3wujODEecF+bHBwhDMNAAFRLKcMSwYBPti5O/3WgGT5x/ux3i6o99met9fXeP021yAVcf0yTQ666JaiZwlJfsowwR77BNUaRBWmEwx1Uhqw6RwM9iDZ4yH0bncH8dky5m9vZ07lN+bMv8cY4pdW3UHwAAAAASUVORK5CYII=)

#### Infra(CI/CD)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/docker_compose-blue?style=for-the-badge&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)
![EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)

#### DB
- RDBMS <br />
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
- NO SQL <br />
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
#### Management Tool
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)
![GitLab](https://img.shields.io/badge/gitlab-orange.svg?style=for-the-badge&logo=gitlab&logoColor=white)
![Mattermost](https://img.shields.io/badge/Mattermost-blue?style=for-the-badge&logo=Mattermost)
#### UI/UX
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Canva](https://img.shields.io/badge/canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white)
#### IDE
![IntellijIDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![WebStorm](https://img.shields.io/badge/WebStorm-000000?style=for-the-badge&logo=webstorm&logoColor=white)
![MySQLWorkbench](https://img.shields.io/badge/MYSQL_WORKBENCH-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)

## 3. 기술을 채택한 이유
#### Backend
- <b>Spring boot</b> <br />
  1. 스프링 부트는 내장된 서버를 제공하여 별도의 서버 설정 없이 애플리케이션 실행 가능
  2. 3rd party 라이브러리를 사용하여 starter라는 묶음 의존성 라이브러리 패키지를 이용
  따라서 maven/gradle에서 버전 관리를 하여 별도의 버전 관리가 필요 없고 간편하게 의존성 지정 가능
  3. 애플리케이션의 상태 모니터링, 로깅, 보안 설정 등 운영에 필요한 기능들을 제공
  이를 통해 애플리케이션 운영과 관리가 편리해지고 안정성이 향상

- <b>Spring Data JPA(JPA)</b> <br />
  1. SQL 중심적인 개발에서 객체 중심적인 개발이 가능
  2. 상속 / 연관 관계 / 객체-RDB 패러다임 불일치를 해결

#### Frontend
- <b>next13 fetch</b> <br />
  ssr을 포함한 ssg를 사용할 수 있는 함수들이 next13 기준으로 fetch 함수 안에 내장 되었기 때문에, fetch 함수를 씀으로써 ssg를 사용하여 렌더링 시간을 줄이고, SEO도 향상되는 효과를 가짐
- <b>zustand</b> <br />
  다른 상태관리 라이브러리에 비해 모듈 크기가 작고, 속도고 빨라 프론트엔드에서 가장 중요한 사용자 화면 렌더링 시간을 줄임
- <b>Typescript</b> <br />
  타입을 지정함으로써 타입 추론에 의한 정확한 데이터 전달이 가능하며 객체 접근에 대한 정확성을 가짐

## 4. 브랜치 전략
:pushpin: <b>Deploy 브랜치에서 E2E 테스트 수행</b> <br />
:pushpin: <b>Deploy의 하위 브랜치 dep/FE와 dep/BE에서 CI/CD 수행</b>
#### marrymo 
![marrymo branch](https://github.com/Marrymo-s/Marrymo/assets/84389492/d5d1fae9-9fec-4e69-aa8b-91532d5d5bfe)

#### bank
![bank branch](https://github.com/Marrymo-s/Marrymo/assets/84389492/08b68f11-0b35-4f12-a080-97f5efe5af24)

## 5. 기능별 페이지
## 부부
#### 카카오 로그인 완료
<b>예비 부부가 카카오 로그인을 통해 로그인에 성공 했을 경우 모바일 청첩장 정보를 등록 했을 때는 모바일 청첩장을 보여주고</b><br />
<b>모바일 청첩장 정보를 등록 하지 않았을 때는 모바일 청첩장 정보를 등록할 수 있도록 해당 페이지로 이동 시킴</b><br />
<b>청첩장 정보 등록 시 축의금 정산 내역을 메일로 수신 받기 위해 메일 인증을 해야 함</b>
|청첩장 정보를 등록하지 않았을 경우|
|:---:|
|![청첩장 등록](https://github.com/Marrymo-s/Marrymo/assets/93860089/76b9e935-6b43-418b-ac9c-7ae0e2b4844f)|

|청첩장 정보를 등록 했을 경우|
|:---:|
|![로그인 시 청첩장 등록 되었음](https://github.com/Marrymo-s/Marrymo/assets/84389492/516c7cf5-0ccc-41d1-8dbd-fe11183f8eac)|


#### 위시리스트 검색 및 등록
<b>예비 부부는 네이버 검색 API를 통해서 위시 리스트를 검색 할 수 있고 펀딩 받고 싶은 위시 리스트 등록 가능</b>
|위시리스트 검색 및 등록 화면|
|:---:|
|![위시리스트 검색 및 등록](https://github.com/Marrymo-s/Marrymo/assets/84389492/5320db00-ca0b-4733-b2ee-9664e32ebf0a)|

#### 위시리스트 상세 조회
<b>예비 부부는 등록한 위시리스트 상세 정보를 조회 가능(위시 아이템 제품명, 현재까지 모인 펀딩 금액, 모금 마감일, 펀딩 인원수)</b>
|위시리스트 상세 조회 화면|
|:---:|
|![위시리스트 상세 조회]((https://github.com/Marrymo-s/Marrymo/assets/84389492/6baa944e-8f0b-48ab-8403-7f5ea7ba293a)|

#### 축의금 내역 조회
<b>예비 부부는 하객들로부터 받은 축의금 내역을 조회 가능</b>
|축의금 내역 조회 화면|
|:---:|
|![축의금 내역 조회](https://github.com/Marrymo-s/Marrymo/assets/84389492/53ae19fb-6196-4a9d-aabd-c3f05ef35edb)|


#### 축의금 정산 내역 메일로 수신
<b>예비 부부는 모바일 청첩장을 최종 발급한 바로 다음 날 새벽 3시에 인증한 메일로 축의금 정산 내역을 엑셀 파일로 수신 받음</b>
|축의금 정산 내역 메일로 수신|
|:---:|
|![축의금 정산 내역 엑셀](https://github.com/Marrymo-s/Marrymo/assets/84389492/1bed041e-87ad-457e-9851-87b30c663311)|

## 하객
#### 모바일 청첩장 조회
<b>하객은 예비 부부가 보낸 링크를 통해 로그인 없이 모바일 청첩장을 조회할 수 있음</b>
|모바일 청첩장 조회 화면|
|:---:|
|![모바일 청첩장 조회 화](https://github.com/Marrymo-s/Marrymo/assets/84389492/ffbf859b-9e2a-4f11-80f0-966cf594ae35)|


#### 위시 리스트 펀딩
<b>하객은 예비 부부가 등록 해놓은 위시 리스트 펀딩 가능</b>
|위시리스트 펀딩 화면|
|:---:|
|![위시리스트 펀딩](https://github.com/Marrymo-s/Marrymo/assets/84389492/882928ea-7aa9-4e0d-9abe-ef77602d97a8)|

#### 축의금 송금
<b>하객은 신랑, 신부 중 누구에게 축의금을 송금할지 고른 후 카카오 페이를 통하여 송금 가능</b>
|축의금 송금 화면|
|:---:|
|![축의금 송금](https://github.com/Marrymo-s/Marrymo/assets/84389492/d19da8a1-7d97-4282-8daf-bac1754f0aed)|

## 6. 핀테크 프로젝트 특징 기술 소개
#### 계좌 등록
오픈 뱅킹 API : 사용자 인증 API -> 토큰 발급 API -> 등록 계좌 조회 API <br />
![오픈뱅킹API 로직](https://github.com/Marrymo-s/Marrymo/assets/84389492/a496bd02-0005-4a81-b3d1-422302df11bb)

#### 송금
카카오 페이 단건 결제 API <br />
![카카오 단건 결제 API 로직](https://github.com/Marrymo-s/Marrymo/assets/84389492/ccb735de-6be7-445f-8bf1-969c59b9c3f1)

## 7. 트러블 슈팅
#### Backend
#### Open Banking API(토큰 발급 API) Web Client를 통해 호출
![토큰 발급 api-1](https://github.com/Marrymo-s/Marrymo/assets/84389492/fa5e9652-5b5a-4bce-a58a-097935490aae)

![토큰 발급 api-1](https://github.com/Marrymo-s/Marrymo/assets/84389492/124e147b-1735-40e0-82cf-3847dc59df1e)

- <b>문제 원인</b> <br />
request body에 Map이 아닌 객체의 형태로 보내려고 해서 발생한 문제

- <b>해결 방법</b> <br />
토큰 발급 API 요청 Content-Type이 application/x-www-form-urlencoded; 이기 때문에 텍스트 데이터를 key-value 쌍으로 인코딩 함.<br /> 특수한 상황의 경우 키가 중복될 수 있고 그에 따라 여러 값이 하나의 키에 매핑될 수 있음<br />
따라서 하나의 키에 여러 개의 값을 가질 수 있는 MultiValueMap Collection을 채택하여 보내야 했음
```
public MultiValueMap<String, String> toMultiValueMap() {
        MultiValueMap<String, String> parameters = new LinkedMultiValueMap<>();

        parameters.add("code", this.code);
        parameters.add("client_id", this.client_id);
        parameters.add("client_secret", this.client_secret);
        parameters.add("redirect_uri", this.redirect_uri);
        parameters.add("grant_type", this.grant_type);

        return parameters;
    }
```
```
return openBankingWebClient
                .post()
                .uri("/oauth/2.0/token")
                .headers(httpHeaders -> httpHeaders.putAll(headers))
                .body(BodyInserters.fromFormData(openBankingTokenApiRequest.toMultiValueMap()))
                .retrieve()
                .bodyToMono(OpenBankingTokenApiResponse.class)
                .block();
```

#### Frontend 
#### next.js CSR에서 CORS 에러 처리
- <b>문제 원인</b> <br />
  next의 app router는 기본적으로 서버 컴포넌트로 구성되어 있어 SSR 페이지에서만 api 호출하거나 SSG로 도메인이 같기 때문에 CORS 에러 날 일이 없음<br /> 하지만 use client를 쓴 CSR 페이지에서는 localhost로 요청이 가기 때문에 CORS 에러가 날 수 있음
- <b>해결 방법</b> <br />
  proxy 우회 방법을 쓴 것처럼 next.config.js에서 rewrites()를 이용해 요청 url을 우회할 수 있음
  - source : 클라이언트에서의 요청 경로
  - destination : 해당 요청이 재작성될 목적지 URL 지정
  ```
    async rewrites() {
    return [
      {
        source: '/users',
        destination: 'https://spring.marrymo.site/users',
      },

  ```
#### 카카오 맵이 next.js 화면에 띄워지지 않는 에러 처리(window is not defined)
- <b>문제 원인</b><br />
  app router 내에 있는 컴포넌트는 기본 서버 컴포넌트로, SSR을 디폴트로 하기 때문에 서버에서 렌더링 하는 시점에서는 브라우저 안의 모든 요소들이 소속된 객체인 window 전역 객체에 대한 접근이 불가함
- <b>해결 방법</b><br />
  dynamic 사용 -> import() 안에 원하는 컴포넌트를 넣고 ssr:false를 처리하면 클라이언트에서 렌더링 되기 때문에 window 객체에도 접근 가능

## 8. 설계 문서
#### API
![UserController](https://github.com/Marrymo-s/Marrymo/assets/84389492/b0097b74-fa24-45cd-8443-f3ed2e680076)

![WishItemController](https://github.com/Marrymo-s/Marrymo/assets/84389492/2c0ed86c-09fd-4f86-9d56-7d67cc754602)

![SmtpController](https://github.com/Marrymo-s/Marrymo/assets/84389492/24eb3a2d-7596-4ffb-9501-6d598cd72261)

![OpenBankingController](https://github.com/Marrymo-s/Marrymo/assets/84389492/1bb306c4-a416-4e00-a1a0-44e7593c831b)

![MoneyGiftController](https://github.com/Marrymo-s/Marrymo/assets/84389492/b3abe1b0-042f-4c02-a4f0-23d35285cae8)

#### ERD
![Marrymo](https://github.com/Marrymo-s/Marrymo/assets/84389492/ce663312-ee84-49d3-a3e4-ab540383e65e)

#### Architecture Structure
![Architecture Structure](https://github.com/Marrymo-s/Marrymo/assets/84389492/6e450a59-0051-4278-a026-7b3141506337)

## 9. 팀원 소개 및 역할
#### :cherry_blossom: 김재윤 (Team Leader)
- Infra, Backend
- 인프라, CI/CD, 카카오페이 API, 축의금 내역 문서화, 인증/인가(은행)
#### :tulip: 김하연
- Infra, Backend
- 인프라, CI/CD, 송금 API, Marrymo와 송금 및 계좌 등록 은행 API 통신(WebClient)

#### :four_leaf_clover: 류승광
- Frontend
- 유저 정보 관리 로직 구성
#### :rose: 박도연
- Backend
- 카카오 소셜 로그인(JWT), 금융결제원 API 연동, 인증/인가(Marrymo), SMTP

#### :sunflower: 정일규
- Frontend
- 청첩장, 위시아이템 데이터 관리

#### :hibiscus: 정지원
- Frontend, Backend
- Frontend : 송금, 오픈뱅킹 계좌 연결, 축의금 내역 구성
- Backend : Redis, REST API 구현, SMTP
