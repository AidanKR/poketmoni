# poketmoni 🃏

아빠표 포켓몬 카드 시세 비교 웹앱. 국내 vs 해외직구 총비용(관세·물류비 포함)을 한눈에.

## 무료 데이터 스택
- 해외 시세·이미지·추이: [pokemontcg.io](https://pokemontcg.io/) (무료, 키 불필요)
- 환율: [exchangerate-api](https://www.exchangerate-api.com/) (무료, 키 불필요)
- 국내 시세: 직접 입력 → 브라우저 localStorage에 저장
- 가격 히스토리: 앱 열 때마다 그날 시세 누적 (서버 0원)

## 기능
- 실시간 카드 검색 (영문명)
- 국내/해외 총비용 비교 + 관세 면세한도($150/$200) 자동 반영
- 관심목록(⭐), 박스·미개봉 수동 등록(＋)
- 가격 변동 그래프 (교차점 = 이득 전환 타이밍)

## 배포 (GitHub Pages)
1. 이 폴더의 `index.html`을 레포 루트에 올린다
2. Settings → Pages → Source: `main` 브랜치 / `/root`
3. 몇 분 뒤 `https://aidankr.github.io/poketmoni/` 접속
4. 아이폰 사파리에서 열고 공유 → "홈 화면에 추가"

## 한계
- 국내 자동 시세 없음(무료 API 부재) → 수동 입력
- 관세 계산은 참고용, 실제 통관과 다를 수 있음
