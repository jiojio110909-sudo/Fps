# 미니 배틀로얄

배틀그라운드 스타일의 3인칭 배틀로얄 FPS 웹 게임입니다. 봇 24명과 함께 낙하해서 마지막 1인이 되세요.

- 단일 파일(`index.html`)로 동작하고, three.js는 CDN(cdnjs)에서 불러옵니다.
- 데스크톱(키보드+마우스)과 모바일(터치) 모두 지원합니다.

## GitHub Pages로 배포하기

1. GitHub에서 새 저장소를 만듭니다. (예: `mini-battle-royale`, Public)
2. 이 폴더의 `index.html`, `README.md`, `.nojekyll` 을 저장소에 업로드합니다. (Add file → Upload files)
3. 저장소의 **Settings → Pages** 로 이동합니다.
4. **Source** 를 `Deploy from a branch`, Branch 를 `main` / `/ (root)` 로 선택하고 Save 합니다.
5. 1~2분 뒤 `https://<내 아이디>.github.io/<저장소 이름>/` 에서 플레이할 수 있습니다.

## 조작법

| 동작 | PC | 모바일 |
|---|---|---|
| 이동 / 달리기 | WASD / Shift | 왼쪽 조이스틱 / 달리기 버튼 |
| 시점 | 마우스 | 화면 드래그 |
| 발사 / 조준(줌) | 좌클릭 / 우클릭 | 발사 버튼 / 조준 버튼 |
| 점프 | Space | 점프 버튼 |
| 재장전 | R | 장전 버튼 |
| 줍기 / 의료키트 | F / H | 줍기 / 치료 버튼 |
| 무기 교체 | 1, 2, Q | 교체 버튼 |
| 근접 / 투척 | 4 / 5 (G) | 근접 / 투척 버튼 |
| 인벤토리 | Tab 또는 I | 가방 버튼 |
| 낙하산 | Space | 낙하산 버튼 |

## 로컬에서 실행하기

`index.html`을 브라우저로 열면 바로 실행됩니다. (인터넷 연결 필요: three.js CDN)
