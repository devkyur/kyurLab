# kyurLab - Developer Utility Tool

네트워크 연결 없이 브라우저에서 바로 사용할 수 있는 **웹 개발자용 유틸리티 도구**입니다.

보안 정책이나 네트워크 제한이 있는 환경에서도 소스코드 비교, JSON 정렬·검증 작업을 **클라이언트 사이드에서 즉시 처리**할 수 있습니다.

> 💡 **Why?**  
> 외부 서비스에 민감한 코드를 붙여넣기 꺼려지거나, 오프라인 환경에서 빠르게 작업해야 할 때 사용합니다.

---

##  Features

### 1. Code Diff
두 코드의 차이점을 한눈에 비교

- 추가 / 삭제 / 수정 라인별 하이라이트
- 문자 단위 변경점 표시
- `Alt + ↑↓` 변경점 간 이동
- `Alt + ←→` 선택한 변경점 병합
- 공백 무시, 대소문자 무시 옵션

### 2. JSON Formatter
JSON 데이터 정렬, 검증, 압축

- Pretty Print (들여쓰기 2/4/Tab 선택)
- Minify (한 줄 압축)
- 문법 검증 + 에러 위치(행/열) 표시
- Syntax Highlight
- Tree View (접기/펼치기 지원)

---

##  Usage

**별도 설치 없이** `kyurlab.html` 파일을 브라우저에서 열면 바로 사용할 수 있습니다.

---

##  Shortcuts

| 단축키 | 기능 |
|--------|------|
| `Ctrl + Enter` | 비교 실행 / Format 실행 |
| `Alt + ↑` | 이전 변경점으로 이동 |
| `Alt + ↓` | 다음 변경점으로 이동 |
| `Alt + ←` | 수정본 → 원본으로 병합 |
| `Alt + →` | 원본 → 수정본으로 병합 |

---

##  Tech Stack

- **Vanilla JavaScript** (No Framework)
- **Single HTML File** (의존성 없음)
- **100% Client-side** (서버 통신 없음)

---
