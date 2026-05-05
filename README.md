# jin-marketplace

jin의 로컬 Claude Code / Cowork 플러그인 마켓플레이스.

## 포함된 플러그인

| 이름 | 설명 |
|---|---|
| `stock-market-research` | 한·미 증시를 한국경제(Chrome) + 네이버 뉴스(MCP)에서 병렬 조사 → docx 보고서 자동 생성 |

## 설치 방법

Claude Code / Cowork에서 다음 두 줄을 차례로 실행:

```
/plugin marketplace add /Users/jinwoo/Desktop/Agent/Claude/jin-marketplace
/plugin install stock-market-research@jin-marketplace
```

## 사용

설치 후 다음 슬래시 커맨드를 사용:

```
/stock-research            # 오늘 기준
/stock-research 2026-05-05 # 특정일 기준
```

## 제거

```
/plugin uninstall stock-market-research@jin-marketplace
/plugin marketplace remove jin-marketplace
```
