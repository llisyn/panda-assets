# panda-assets

판다맘(`@ourdays.edition`) 툰 이미지 호스팅 + OAuth 콜백.

| 경로 | 용도 |
|---|---|
| `assets/<회차ID>/cut-NN.png` | 툰 컷. Threads/Instagram API가 **공개 URL**을 요구해서 여기 push한다 |
| `callback/` | Meta OAuth 리디렉션 대상. 인증 코드를 화면에 띄워준다 |

`config.yaml`의 `host.repo_dir`가 이 폴더를 가리킨다.
