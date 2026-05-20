# AlterRe — 알타리 팀 포트폴리오

KOSMO 서초 2기 팀프로젝트 1 결과물 사이트.  
배추·무·고추의 기후·가격·출하량 데이터를 분석하고 시각화한 프로젝트입니다.

🔗 **배포 주소:** https://kosmoalterre.netlify.app

---

## 기술 스택

| 구분 | 기술 |
|------|------|
| 데이터 분석 | Python, Pandas, NumPy |
| 시각화 | Matplotlib, Folium (지도) |
| DB | MySQL, SQLAlchemy |
| 웹 | HTML, CSS, JavaScript |
| 배포 | Netlify |

---

## 팀원

| 이름 | 역할 |
|------|------|
| 강경연 | 기후 분석 시각화, 농산물 분석 시각화, 발표자료 |
| 이원재 | 소비문화 분석 시각화, 웹 개발(HTML/CSS/JS), Netlify 배포 |
| 최정우 | 기후 분석 시각화, 발표자료 |

---

## 분석 코드

`analysis/` 폴더에 데이터 분석 및 시각화에 사용한 Jupyter Notebook이 포함되어 있습니다.

| 파일 | 내용 |
|------|------|
| `eatout_analysis.ipynb` | 식문화 분석 — MySQL에서 데이터 조회 후 가공식품 구매량, 외식 매출, 가구 세대 구성 시각화 |
| `household_analysis.ipynb` | 가구원 분석 — Excel 데이터 기반 세대별·가구원 수별 비율 변화 시각화 |

---

## 프로젝트 구조

```
AlterRe/
├── index.html                  # 메인 페이지
├── team.html                   # 팀 소개
├── climate0~3.html             # 기후 분석
├── price1~3.html               # 농산 가격 분석
├── eatout1.html                # 식문화 분석
├── styles.css                  # 공통 스타일 (반응형 포함)
├── *_production_map.html       # 지역별 생산지도 (Folium)
├── analysis/                   # 데이터 분석 코드
│   ├── eatout_analysis.ipynb
│   └── household_analysis.ipynb
├── assets/images/              # 분석 차트 이미지
└── netlify.toml                # Netlify 배포 설정
```

---

## 로컬 실행

별도 빌드 없이 HTML 파일을 브라우저에서 직접 열거나,  
VS Code Live Server 확장을 사용하면 됩니다.
