# myseasonclinic-ulsaninfo — 보호 목록 (홈 대표 콘텐츠)

확인일: 2026-10-16. 홈(`index.html`)을 직접 읽어 확인한 연결 관계만 적었다. 자동 발행 작업은 아래 항목을 **수정하지 않는다**.

## 확인됨: 홈 대표 카드 6개 (class="card")
홈의 대표 카드는 `/journal/` 글이 아니라 `/treatments/` 진료 안내 페이지로 연결된다. 카드·이미지·연결 페이지·페이지 안의 이미지를 그대로 둔다.

| # | 카드 | 연결 페이지 | 카드 이미지 |
|---|---|---|---|
| 1 | 01 · 울쎄라피 프라임 | `/treatments/ulsan-ultherapy/` | `/images/ultherapy-doctor-1000.webp` |
| 2 | 02 · 리프팅필러 울산리프팅필러, | `/treatments/ulsan-lifting-filler/` | `/images/lifting-filler-1-1000.webp` |
| 3 | 03 · 입술필러 울산입술필러, | `/treatments/ulsan-lip-filler/` | `/images/lip-filler-doctor-1000.webp` |
| 4 | 04 · 이마필러 울산이마필러, | `/treatments/ulsan-forehead-filler/` | `/images/forehead-filler-doctor-1000.webp` |
| 5 | 05 · 쥬베룩 울산쥬베룩, | `/treatments/ulsan-juvelook/` | `/images/juvelook-1-860.webp` |
| 6 | 06 · 기미·색소레이저 울산기미레이저, | `/treatments/ulsan-pigment-laser/` | `/images/pigment-laser-1-1000.webp` |

## 확인됨: 홈의 기타 이미지
`/images/clinic-intro-1000.webp` — 유지.

## 미확인
- 홈에서 `/journal/` 글로 직접 연결되는 "대표 글"은 현재 `index.html`에서 발견되지 않았다(홈에는 journal 링크 없음, 별도 JS/JSON 데이터 없음). 과거 구축 때 연결했던 글이 있었다면 지금 구조에서는 확인되지 않으므로 **'미확인'**으로 둔다. 임의로 6편을 지정하지 않는다.
- `/treatments/*` 페이지 안의 이미지·설명 본문: 자동 발행 작업은 이 페이지에서 **건강정보 글 목록 블록만** 갱신하고(목록이 있을 때), 나머지 내용과 이미지는 건드리지 않는다.

## 적용 범위
이번 제작·검수 기준은 예약 대기 원고, 미발행 재고, 앞으로 생성할 원고에 적용한다. 기존 공개 글과 홈 구성은 수정 대상이 아니다.
