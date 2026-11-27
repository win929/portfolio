# Hi, I'm Leo — 백엔드 개발자 이어진 포트폴리오

브라우저에서 넘겨 보는 인터랙티브 HTML 슬라이드 포트폴리오입니다.

**바로 보기:** https://win929.github.io/portfolio/

## 보는 방법

- `←` `→` 키 또는 아래 버튼으로 슬라이드를 넘깁니다. `G` 키를 누르면 전체 목차가 열립니다.
- 모든 도식은 정적이라 처음 화면과 PDF에서 그대로 읽힙니다.
- 트러블슈팅 페이지는 문제 · 해결 과정 · 결과를 한 장에 모두 보여 줍니다. 더 눌러 들어가야 보이는 내용은 없습니다.
- 화면 폭이 900px보다 좁으면 스크롤형으로 바뀝니다. 데스크톱에서도 **스크롤로 보기** 버튼으로 바꿀 수 있습니다.

## 구성 (21장)

각 프로젝트는 **소개 페이지**(무엇을 만들었는지, 기술 스택, 내 역할, 실제 화면)와 **내 역할·트러블슈팅 페이지**로 이어집니다.

| 구간 | 내용 |
| --- | --- |
| 소개 | 표지, 기술 스택(주요 기술 8개 · 5단계 자기 평가), 일하는 기준 4가지, 프로젝트 타임라인 |
| SHERLOG | SEMES 기업연계 · 반도체 설비 로그 사후 분석 · 팀장 / 백엔드 · SSAFY 2학기 자율 프로젝트 우수상 → 6주 개발 과정, 공정 목록 503 해결, 동시 분석·재시작 시간 단축 |
| 콜미베이비 | 가족 영상통화 · 백엔드 테크 리더 → 재접속 유예, AI 그림일기 파이프라인 |
| 책추책책추 | 도서 추천 · AI 담당 → 오프라인 색인부터 온라인 추천까지 AI 파이프라인 한 장 |
| 무쉼사 | 무더위쉼터 찾기 · 백엔드 테크 리더 → 공공데이터 동기화와 CI/CD |
| 수어프라이즈 | 드라이브스루 온디바이스 수어 통역 앱 · 팀장 · 학사 학위 논문 → 수집 앱부터 LSTM 학습, TFLite 탑재까지 |
| 그 외 | 이전 프로젝트(선물하기 클론 포함), 교육·활동, 수상·자격·논문, 연락처 |

## 파일

| 경로 | 설명 |
| --- | --- |
| `index.html` | 포트폴리오 본문 (GitHub Pages 진입점) |
| `assets/` | 프로필 사진, 기술 로고(`assets/logos/`), 프로젝트 로고·실제 화면(`assets/projects/`) |
| `fonts/` | Paperlogy 웹폰트 4종과 라이선스 |
| `leo-portfolio.html` | 이미지와 폰트를 모두 담은 단일 파일. 내려받아 더블클릭하면 브라우저에서 열리고, 크롬 인쇄 → PDF로 저장하면 슬라이드 한 장이 한 페이지가 됩니다. |

## 폰트와 로고

본문과 제목에는 [Paperlogy](https://www.sandollcloud.com/free-font/21071/Paperlogy)(디자인 이주임·김도균)를 사용했고, 코드·수치 표기에는 Google Fonts의 IBM Plex Mono를 사용했습니다. Paperlogy는 SIL Open Font License 1.1로 배포되며, 라이선스 전문은 [`fonts/OFL.txt`](fonts/OFL.txt)에 있습니다.

기술 스택 로고는 [Devicon](https://devicon.dev/) 2.16.0(MIT License)의 SVG를 그대로 사용했습니다. 각 로고는 해당 기술 소유자의 상표입니다.

프로젝트 로고와 화면은 각 팀 저장소의 자료를 크기만 줄여 사용했습니다: [SHERLOG](https://github.com/win929/SHERLOG), [콜미베이비](https://github.com/ssafy-call-me-baby), [책추책책추](https://github.com/chackchu), [무쉼사](https://github.com/kakao-tech-campus-3rd-step3/Team19_FE), [수어프라이즈](https://github.com/CD03-01/SueoPrize). 수어프라이즈의 시스템 구조 그림과 앱 화면은 학사 학위 논문에서 가져왔습니다.

## 연락처

- Email: win929@naver.com
- GitHub: https://github.com/win929
- LinkedIn: https://www.linkedin.com/in/cnu-cse-eojin-lee/
