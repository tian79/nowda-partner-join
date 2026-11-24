# 나우다 제휴사 모집 안내 사이트

정적 사이트(HTML/CSS/JS)입니다. 서버와 데이터베이스가 없고, 개인정보 입력칸도 없습니다.
신청과 문의는 모두 nowda@ijto.or.kr 이메일로 받습니다.

## 구성

```
index.html            제휴 제안 페이지 (한 페이지, 제안서 PPT 구성·디자인 기반)
assets/nowda/         제안서 PPT에서 가져온 나우다 캐릭터·로고·배지·화면 이미지
_v2/index.html        이전 안내 페이지 (사진 버전, 참고용)
credits.html          이전 버전 사진 출처 목록 (지금 페이지는 사진을 쓰지 않음)
favicon.svg, share.jpg  탭 아이콘, 링크 공유 이미지
assets/               이전 버전의 디자인 키트와 사진 (지금 페이지는 assets/nowda만 씀)
downloads/            신청 서식 (PDF, DOCX; HWPX는 아직 없음)
_v1/                  이전 버전 (참고용, 공개 전 삭제)
site-plan.html        기획안 (참고용, 공개 전 삭제)
```

색은 `index.html` 맨 위 `:root`의 `--yellow`, `--green`, `--red`, `--ink` 값에서 바꿉니다 (제안서 PPT의 나우다 색).
가입자·제휴사 수(37만 명, 295곳)는 2026년 11월 기준이니, 바뀌면 히어로 말풍선·성장 그래프·제휴사 수 문구를 함께 고치세요.

## 해야 할 일

1. **HWPX 서식**: `downloads/nowda-partner-form.docx`를 한글에서 열어 HWPX로 `downloads/nowda-partner-form.hwpx`에 저장한 뒤, `index.html`에서 "한글 서식 받기" 줄의 주석을 푸세요.
2. **확인 필요**: 검토 기간, 제휴 확정 뒤 QR 전달 방식, 받은 서류의 보관·파기 안내.

## 공개 전 정리 (권장)

- `_v1/`, `_v2/`, `site-plan.html`, `credits.html`, `참고파일/`, `.claude/`, `.taste-skill/`, `shots/` 폴더는 올리지 마세요.
- 지금 페이지는 `assets/nowda/`만 씁니다. `_v2/`를 함께 올리지 않는다면 `assets/` 안의 나머지 폴더는 지워도 됩니다. 지운 뒤 페이지가 똑같이 보이는지 한 번 확인하세요.

## GitHub Pages로 공개하기

1. 이 폴더를 GitHub 저장소로 올립니다.
2. 저장소 Settings > Pages > Branch를 `main`, 폴더를 `/ (root)`로 선택합니다.
3. 몇 분 뒤 `https://<계정>.github.io/<저장소>/` 주소로 열립니다.
