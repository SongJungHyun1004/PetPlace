# PetPlace
### 우리동네 펫 커뮤니티

---

# 프로젝트 개요
<img src="docu/webp/주요기능1.png" width="800" height="430" />
<img src="docu/webp/주요기능2.png" width="800" height="430" />
<img src="docu/webp/주요기능3.png" width="800" height="430" />
<img src="docu/webp/주요기능4.png" width="800" height="430" />
<img src="docu/webp/주요기능5.png" width="800" height="430" />
<img src="docu/webp/주요기능6.png" width="800" height="430" />
<img src="docu/webp/주요기능7.png" width="800" height="430" />
<img src="docu/webp/주요기능8.png" width="800" height="430" />
<img src="docu/webp/주요기능9.png" width="800" height="430" />
<img src="docu/webp/주요기능10.png" width="800" height="430" />
<img src="docu/webp/주요기능11.png" width="800" height="430" />
<img src="docu/webp/주요기능12.png" width="800" height="430" />

# 스플래쉬 화면
<img src="docu/webp/loading.webp" height="430" />

# 피드 페이지
- TopHeader의 부드러운 숨김처리 구현
- 피드 5개씩 페이지네이션 구현
- 글 작성 화면 구현
- 개인 추천 알고리즘 적용  
- 좋아요, 댓글 FCM 알람 연동

<img src="docu/webp/_MConverter.eu_feed.webp" height="430" />
<img src="docu/webp/_MConverter.eu_KakaoTalk_20250902_153732630.webp" height="430" />
<a href="docu/webp/KakaoTalk_20250902_171833606_17.png"><img src="docu/webp/KakaoTalk_20250902_171833606_17.png" width="200" /></a>

# 우리동네 페이지
- 바텀시트 구현
- 카카오맵 API 연동하여 위치 마커 표시

<img src="docu/webp/Screenshot_20250815_144836_PetPlace.jpg" height="430" />

# 산책/돌봄 페이지
- 게시판 리스트 구현
- 글 작성 화면 구현

<img src="docu/webp/_MConverter.eu_KakaoTalk_20250902_154047838.webp" height="430" />
<img src="docu/webp/_MConverter.eu_KakaoTalk_20250902_153738954.webp" height="430" />

# 실종 신고/등록 페이지
- 실종신고 페이지 구현(잃어버렸어요)
- 실종등록 페이지 구현(목격했어요)
- 실종매칭 FCM 알람 연동

<img src="docu/webp/missingregister.webp" height="430" />
<a href="docu/webp/KakaoTalk_20250902_171833606_15.png"><img src="docu/webp/KakaoTalk_20250902_171833606_15.png" height="430" /></a>
<img src="docu/webp/matching.webp" height="430" />

# 채팅페이지
<img src="docu/webp/chat.webp" height="430" />

# 마이페이지
- 꼬순내 로직 구현
- 마이 프로필 수정
- 내 가족(펫) 등록 및 추가
- 신뢰기반 내 용품 등록 구현
- 마이피드, 댓글, 찜한피드 조회 구현

<img src="docu/webp/mypage.webp" height="430" />
<img src="docu/webp/petadd.webp" height="430" />


# 영상포트폴리오
<a href="https://www.youtube.com/watch?v=vrb4LYhehxQ"><img src="https://img.youtube.com/vi/vrb4LYhehxQ/0.jpg" width="800" height="430" /></a>

# 시스템 아키텍처
<img src="docu/webp/PetPlace아키텍처.png" />

# ERD
<img src="docu/webp/PetPlace_ERD.png" />

# Role
<table>
  <tr>
    <td align="center">오승연</td>
    <td align="center">김민</td>
    <td align="center">조경호</td>
  </tr>
  <tr>
    <td align="center">모바일</td>
    <td align="center">백엔드</td>
    <td align="center">인프라, AI</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/syeony"><img src="docu/webp/승연이.png" width="150" height="150" /></a></td>
    <td align="center"><a href="https://github.com/ZeppIine"><img src="docu/webp/민.jpg" width="150" height="150" /></a></td>
    <td align="center"><a href="https://github.com/Alien-kh"><img src="docu/webp/경호.png" width="150" height="150" /></a></td>
  </tr>
</table>

<table>
  <tr>
    <td align="center">이도형</td>
    <td align="center">송정현</td>
    <td align="center">정유진</td>
  </tr>
  <tr>
    <td align="center">모바일</td>
    <td align="center">모바일</td>
    <td align="center">백엔드</td>
  </tr>
  <tr>
    <td align="center"><img src="docu/webp/도형.png" width="150" height="150" /></td>
    <td align="center"><img src="docu/webp/정현.png" width="150" height="150" /></td>
    <td align="center"><img src="docu/webp/유진.png" width="150" height="150" /></td>
  </tr>
</table>

# 상세 역할분담

- 오승연: 디자인, 피드, 글쓰기, 댓글, 산책/돌봄, 실종 페이지 및 기능 연결

- 김민: 피드, 댓글, 좋아요, 마이페이지, 펫, 꼬순내, FCM 기능 구현 및 DB 설계

- 조경호: AI 모델 연구 및 최적화, 빅데이터 추천 로직 구현, 인프라 구축, 채팅 기능 구현

- 이도형: 로그인, 소셜로그인, 호텔 페이지 기능 연결, 카카오맵 API 연결, 온디바이스 AI 적용

- 송정현: 채팅, 마이페이지, 펫 페이지 기능 연결, FCM 딥링크 구현

- 정유진: 디자인, 로그인, JWT, 호텔, 산책/돌봄 기능 구현 및 DB 설계

