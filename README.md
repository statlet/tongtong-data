# 통통한 데이터 분석 — 온라인 부록과 실습 데이터

이 저장소는 도서 **『통통한 데이터 분석』**의 온라인 부록 PDF와 예제 데이터를 제공합니다.

부록에는 파이썬과 R 입문 및 본문 1부부터 5부까지의 실습 코드가 수록되어 있습니다.

## 온라인 자료

| 자료 | 내용 |
|---|---|
| [온라인 데이터 가이드](./온라인_데이터_가이드.pdf) | 예제 데이터의 출처, 구축 방법, 선정 기준과 주요 변수 설명 |
| [온라인부록 파이썬](./온라인부록_파이썬.pdf) | 파이썬 소개와 입문, 본문 1부부터 5부까지의 파이썬 실습 |
| [온라인부록 R](./온라인부록_R.pdf) | R 소개와 입문, 본문 1부부터 5부까지의 R 실습 |

## 폴더 구성

PDF와 README는 저장소의 최상위 폴더에, CSV 파일은 `데이터` 폴더에 있습니다.

```text
.
├── README.md
├── 온라인_데이터_가이드.pdf
├── 온라인부록_파이썬.pdf
├── 온라인부록_R.pdf
└── 데이터/
    ├── movie_data.csv
    ├── seoul_cultural_events.csv
    ├── seoul_apt_transactions.csv
    ├── reliever_data.csv
    ├── hn19.csv
    ├── boston_marathon_2023.csv
    ├── seoul_apt_dong_model.csv
    ├── seoul_subway_hourly_2024.csv
    ├── k_corporation_reward_survey.csv
    ├── mtcars.csv
    └── iris.csv
```

## 실습 방법

저장소 전체를 내려받고 **저장소의 최상위 폴더를 작업 폴더로 지정한 뒤**, PDF에 실린 코드를 파이썬 또는 R 환경에서 실행해 주세요. 데이터 파일은 `데이터/파일명.csv` 형식의 상대 경로로 불러옵니다.

## 데이터 이용 안내

최종 배포 데이터 10종의 원출처, 수집·가공 방법, 포함 기준과 변수 설명은 [온라인 데이터 가이드](./온라인_데이터_가이드.pdf)를 확인해 주세요. 데이터는 도서의 설명과 실습을 재현하기 위한 형태로 정리되어 있습니다.

`iris.csv`는 R 입문 예제에서 사용하는 파일이며 [Rdatasets의 iris 데이터](https://raw.githubusercontent.com/vincentarelbundock/Rdatasets/master/csv/datasets/iris.csv)에서 가져왔습니다.

© 2026 정성규 외 5인. All rights reserved.
