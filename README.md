# AlterRe — 알타리 팀 포트폴리오

KOSMO 서초 2기 팀프로젝트 1 결과물 사이트.  
배추·무·고추의 기후·가격·출하량 데이터를 분석하고 시각화한 프로젝트입니다.

🔗 **배포 주소:** https://kosmoalterre.netlify.app

---

## 팀원

| 이름 | 역할 |
|------|------|
| 강경연 | 기후 분석 시각화, 농산물 분석 시각화, 발표자료 |
| 이원재 | 소비문화 분석 시각화, 웹 개발(HTML/CSS/JS), Netlify 배포 |
| 최정우 | 기후 분석 시각화, 발표자료 |

---

## 구조

```
AlterRe/
├── index.html                  # 메인 페이지
├── team.html                   # 팀 소개
├── climate0~3.html             # 기후 분석
├── price1~3.html               # 농산 가격 분석
├── eatout1.html                # 식문화 분석
├── *_production_map.html       # 지역별 생산지도 (지도 시각화)
├── assets/
│   └── images/                 # 차트 및 팀원 사진
├── netlify.toml                # Netlify 배포 설정
└── .gitignore
```

---

## 브랜치 전략

- `main` — 배포 브랜치 (Netlify 연결)
- `dev` — 개발 브랜치 (작업 후 main에 merge)

---

## 로컬 실행

별도 빌드 없이 HTML 파일을 브라우저에서 직접 열거나,  
VS Code Live Server 확장을 사용하면 됩니다.
