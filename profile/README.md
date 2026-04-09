<div align="center">

<img src="https://github.com/user-attachments/assets/670b447f-8916-4166-a9c5-79f6145d94ea" width="160" alt="STalk Logo"/>

# STalk

**실시간 주식 정보와 종목별 채팅을 한 곳에서**

[![STalk](https://img.shields.io/badge/주소-s--talk.vercel.app-0d835c?style=flat)](https://s-talk.vercel.app/)
&nbsp;
![기간](https://img.shields.io/badge/기간-2026.03.01_~_2026.03.31-0d835c?style=flat)

</div>

<br>

## 서비스 소개

STalk은 실시간 주식 시세와 시장 지수를 확인하고, 관심 종목을 관리하며 같은 종목에 관심 있는 사용자들과 실시간으로 소통할 수 있는 주식 커뮤니티 플랫폼입니다.

카카오 소셜 로그인으로 간편하게 시작할 수 있으며, 한국투자증권 API를 통해 국내 주요 종목의 실시간 시세를 제공합니다.

<br>

## 팀원

<div align="center">
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Lseojeong">
        <img src="https://avatars.githubusercontent.com/u/112802701?v=4" width="80" style="border-radius:50%"/><br/>
        <b>이서정</b><br/>
        <sub>Frontend</sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/yong203">
        <img src="https://avatars.githubusercontent.com/u/183721396?v=4" width="80" style="border-radius:50%"/><br/>
        <b>이한용</b><br/>
        <sub>Backend</sub>
      </a>
    </td>
  </tr>
</table>
</div>

<br>

## 주요 기능

| 기능 | 설명 |
|------|------|
| 실시간 시세 | 한국투자증권 API 연동, 30초 간격으로 주가 갱신 |
| 시장 지수 | KOSPI, NASDAQ, S&P 500, USD/KRW 실시간 현황 |
| 종목 랭킹 | 등락률 기준 상위 종목 카드 형태로 제공 |
| 관심 종목 | 로그인 후 종목 즐겨찾기 등록·해제 |
| 종목별 채팅 | 종목 단위 실시간 채팅방, 접속자 수 표시 |
| 카카오 로그인 | OAuth 2.0 소셜 인증 |

<br>

## 화면

### 메인
> 시장 지수 · 종목 랭킹 한눈에 확인

<img alt="메인" src="https://github.com/user-attachments/assets/4b991b0c-5f43-4136-b7e2-d45cd687880c"/>

---

### 전체 종목
> 국내 주요 종목 전체 목록 조회

<img alt="전체 종목" src="https://github.com/user-attachments/assets/0642f785-da47-4cc1-8986-f9b1eeec120a"/>

---

### 관심 종목
> 즐겨찾기한 종목만 모아보기

<img alt="관심 종목" src="https://github.com/user-attachments/assets/b11e82b2-2b21-4514-872f-3de22ce4e6cd"/>

### 채팅방
> 종목별 실시간 채팅 · 접속자 수 표시

<!-- 추후 추가 예정 -->

<br>

## 기술 스택

<table>
  <tr>
    <th>영역</th>
    <th>분류</th>
    <th>기술</th>
  </tr>
  <tr>
    <td rowspan="4"><b>Frontend</b></td>
    <td>Core</td>
    <td>
      <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black"/>
      <img src="https://img.shields.io/badge/TypeScript_5.9-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/Vite_7-646CFF?style=flat-square&logo=vite&logoColor=white"/>
      <img src="https://img.shields.io/badge/React_Router_6-CA4245?style=flat-square&logo=reactrouter&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td>Styling</td>
    <td>
      <img src="https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td>통신</td>
    <td>
      <img src="https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white"/>
      <img src="https://img.shields.io/badge/STOMP.js-010101?style=flat-square&logo=socket.io&logoColor=white"/>
      <img src="https://img.shields.io/badge/SockJS-010101?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td>UI</td>
    <td>
      <img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/Swiper-6332F6?style=flat-square&logo=swiper&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td rowspan="5"><b>Backend</b></td>
    <td>Core</td>
    <td>
      <img src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring_Boot_3.5-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td>보안 / 인증</td>
    <td>
      <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
      <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
      <img src="https://img.shields.io/badge/Kakao_OAuth-FFCD00?style=flat-square&logo=kakao&logoColor=black"/>
    </td>
  </tr>
  <tr>
    <td>데이터</td>
    <td>
      <img src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/H2-4479A1?style=flat-square&logo=h2&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td>실시간 통신</td>
    <td>
      <img src="https://img.shields.io/badge/WebSocket_STOMP-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td>문서 / 모니터링</td>
    <td>
      <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black"/>
      <img src="https://img.shields.io/badge/Spring_Actuator-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
      <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td rowspan="3"><b>Infra</b></td>
    <td>컨테이너 / 배포</td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker_Hub-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white"/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td>DB 호스팅</td>
    <td>
      <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td>CI·CD</td>
    <td>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
    </td>
  </tr>
</table>

