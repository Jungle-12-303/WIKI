# Jungle 12-303 WIKI

크래프톤 정글 12기 303호의 공동 학습 기록 저장소입니다.

> 매일 새벽 자동 인덱싱 작업으로 갱신됩니다. 대시보드와 최근 업데이트는 `git log` 기반으로 다시 작성됩니다.
>
> **오늘의 업데이트 (2026-05-14):** Week 11 팀장 회의록 1건(`2026-05-12`)이 추가되어 회의록 카테고리가 9 → 10건으로 늘었습니다. 페이지 **102 → 103**, 작성완료 **16 → 17(17%)**. 다만 같은 커밋(`a52759a`)에서 `docs/발표 ppt 공유/week9/9주차-6팀.pptx`가 **NFC 인코딩으로 재업로드**되며 기존 NFD 파일과 **동일 내용(MD5: `2e6a1f92…`) 중복이 재발**했습니다. 인덱스에서는 단일 항목으로 병합해 노출하되, 정리 권고를 본문 하단에 기록합니다.
>
> **직전 업데이트 (2026-05-13):** 직전 인덱싱(`2026-05-12`) 이후 신규 콘텐츠 커밋이 감지되지 않아 수치를 유지했습니다(페이지 102 · 작성완료 16).
>
> **직전 업데이트 (2026-05-12):** Week 11 팀장 회의록 2건(`2026-05-08`, `2026-05-11`)이 추가되었고, 발표 자료 아카이브가 `docs/발표 ppt 공유/`로 일원화되었습니다. 9주차 발표자료 3건(3팀·5팀·6팀)과 10주차 발표자료 2건(3팀·5팀), 업로드 가이드 1건이 인덱스에 반영되었습니다. 페이지 **94 → 102**, 작성완료 **8 → 16(16%)**. 직전 인덱싱(2026-05-11) 이후 감지되었던 `ppt_template/` vs `발표 ppt 공유/` 경로 중복은 팀이 `발표 ppt 공유/`로 통일하면서 **해소**되었습니다.

---

## 목차

- [대시보드](#대시보드)
- [작성 완료된 문서](#작성-완료된-문서)
- [최근 업데이트](#최근-업데이트)
- [카테고리별 인덱스](#카테고리별-인덱스)
- [관련 주제 매핑](#관련-주제-매핑)
- [중복 정리 권고](#중복-정리-권고)
- [빠른 시작 (온보딩)](#빠른-시작-온보딩)
- [기여 규칙 요약](#기여-규칙-요약)
- [커밋 컨벤션](#커밋-컨벤션)
- [관련 저장소](#관련-저장소)

---

## 대시보드

> 전체 **103개** 페이지 · 작성완료 **17개** · 미작성 **86개** · 마지막 인덱싱 **2026-05-14** · 마지막 콘텐츠 커밋 **2026-05-13**

### 카테고리별 현황

| 카테고리 | 페이지 수 | 작성완료 | 진행률 | 바로가기 |
|----------|:---------:|:--------:|:------:|----------|
| OS | 17 | 0 | 0% | [docs/os/](docs/os/) |
| Pintos — Project 0 | 3 | 0 | 0% | [docs/pintos/project0/](docs/pintos/project0/) |
| Pintos — Project 1 Threads | 5 | 0 | 0% | [docs/pintos/project1-threads/](docs/pintos/project1-threads/) |
| Pintos — Project 2 Userprog | 6 | 0 | 0% | [docs/pintos/project2-userprog/](docs/pintos/project2-userprog/) |
| Pintos — Project 3 VM | 5 | 0 | 0% | [docs/pintos/project3-vm/](docs/pintos/project3-vm/) |
| Pintos — Project 4 Filesys | 5 | 0 | 0% | [docs/pintos/project4-filesys/](docs/pintos/project4-filesys/) |
| CS 기초 | 10 | 0 | 0% | [docs/cs-기초/](docs/cs-기초/) |
| 알고리즘 | 10 | 0 | 0% | [docs/algorithm/](docs/algorithm/) |
| 네트워크 | 7 | 0 | 0% | [docs/네트워크/](docs/네트워크/) |
| 웹 보안 | 4 | 0 | 0% | [docs/web-security/](docs/web-security/) |
| DB | 3 | 0 | 0% | [docs/db/](docs/db/) |
| AI | 3 | 0 | 0% | [docs/ai/](docs/ai/) |
| Malloc Lab | 2 | 0 | 0% | [docs/malloc-lab/](docs/malloc-lab/) |
| 회의록 | 10 | 10 | 100% | [docs/meeting-minutes/](docs/meeting-minutes/) |
| 팀운영 | 7 | 1 | 14% | [docs/팀운영/](docs/팀운영/) |
| 발표 자료 | 6 | 6 | 100% | [docs/발표 ppt 공유/](docs/발표%20ppt%20공유/) |
| **합계** | **103** | **17** | **17%** | — |

> **작성완료** 기준: `_작성 필요_`/`_링크 추가_` 플레이스홀더가 모두 제거되고 본문이 채워진 페이지. 발표 자료는 업로드된 `.pptx` 및 가이드 문서를 기준으로 합니다. NFC/NFD 인코딩이 중복된 `9주차-6팀.pptx`는 동일 콘텐츠이므로 **1건으로 합산**합니다.

---

## 작성 완료된 문서

지금 바로 읽을 수 있는, 본문이 채워진 페이지들입니다.

### 회의록 (10)

| 일자 | 제목 | 키워드 |
|:----:|------|--------|
| 2026-04-25 | [팀장 회의록 — 2026-04-25 (토)](docs/meeting-minutes/week9/2026-04-25.md) | 협업 방식, 실력차 극복, AI 활용, 코어타임, 디버깅 공유 |
| 2026-04-27 | [팀 회의록 — 2026-04-27](docs/meeting-minutes/week9/2026-04-27.md) | 팀 운영 방침, Pintos 방향성 |
| 2026-04-29 | [팀장 회의록 — 2026-04-29](docs/meeting-minutes/week9/2026-04-28.md) | 발표자료 준비, 반 컨벤션 정렬, 위키 정리 |
| 2026-04-30 | [회의록 — 2026-04-30 (Week 10)](docs/meeting-minutes/week9/2026-04-30.md) | 팀별 진행 현황, 코드 리뷰/머지, 다음 주 방식 |
| 2026-05-01 | [회의록 — 2026-05-01](docs/meeting-minutes/week10/2026-05-01.md) | Wiki 업로드 협조, 6조 Notion 토글 활용 |
| 2026-05-02 | [팀장 회의록 — 2026-05-02 (토)](docs/meeting-minutes/week10/2026-05-02.md) | 반 전체 커밋 컨벤션 합의, argument passing 진척, 팀별 협업 방식 |
| 2026-05-04 | [팀장 회의록 — 2026-05-04 (월)](docs/meeting-minutes/week10/2026-05-04.md) | argument passing 이후 역할 분담, file descriptor 설계, 코치 질의 정리, Extension publish |
| 2026-05-08 | [팀장 회의록 — 2026-05-08 (금)](docs/meeting-minutes/week11/2026-05-08.md) | 진행 상황 공유 방식 변경 (회의실 → Google Sheet) |
| 2026-05-11 | [팀장 회의록 — 2026-05-11 (월)](docs/meeting-minutes/week11/2026-05-11.md) | WIKI 회의록 정착, 발표자료 아카이빙, 반장/MC 운영, 팀장 인수인계 |
| 2026-05-12 | [팀장 회의록 — 2026-05-12 (화)](docs/meeting-minutes/week11/2026-05-12.md) | 중요 안건 결정 방식 (팀 의견 → 팀장 회의 → 다수결), 반회의 운영(반회고 폐지), 자율 안건은 Slack 공유, 반장 역할 범위 |

### 팀 운영 (1)

| 문서 | 요약 |
|------|------|
| [Week 10 팀 레포 현황](docs/팀운영/주차별-팀레포/week10.md) | 1~7조 Pintos Project 2 레포 링크 모음과 코드 리뷰 협업 방법 |

### 발표 자료 (6)

| 자료 | 형식 | 설명 |
|------|:----:|------|
| [발표 자료 업로드 안내](docs/발표%20ppt%20공유/presentation-upload-guide.md) | `.md` | 주차별 폴더 구성, `.pptx` 형식 권장, 폰트 공유 방침 |
| [9주차 3팀 발표 자료](docs/발표%20ppt%20공유/week9/9주차-3팀.pptx) | `.pptx` | Week 9 정기 발표 (3팀) |
| [9주차 5팀 발표 자료](docs/발표%20ppt%20공유/week9/9주차-5팀.pptx) | `.pptx` | Week 9 정기 발표 (5팀) |
| [9주차 6팀 발표 자료](docs/발표%20ppt%20공유/week9/9주차-6팀.pptx) | `.pptx` | Week 9 정기 발표 (6팀) · ⚠ NFC/NFD 동일 파일 2종이 함께 트래킹 중 (아래 [중복 정리 권고](#중복-정리-권고) 참고) |
| [10주차 3팀 발표 자료](docs/발표%20ppt%20공유/week10/10주차-3팀.pptx) | `.pptx` | Week 10 정기 발표 (3팀) |
| [10주차 5팀 발표 자료](docs/발표%20ppt%20공유/week10/10주차-5팀.pptx) | `.pptx` | Week 10 정기 발표 (5팀) |

> 회의록의 파일명(`2026-04-28.md`)과 본문 일자(`2026-04-29`)가 다른 경우가 있습니다. 본 인덱스에서는 본문 일자를 기준으로 표기했습니다.

---

## 최근 업데이트

`git log` 기준 가장 최근에 수정/추가된 30개 항목입니다.

| # | 페이지 | 카테고리 | 상태 | 최종 수정일 |
|:--:|--------|----------|:----:|:-----------:|
| 1  | [팀장 회의록 — 2026-05-12 (화)](docs/meeting-minutes/week11/2026-05-12.md) | 회의록 | 완료 | 2026-05-13 |
| 2  | [9주차 6팀 발표 자료 (NFC 재업로드)](docs/발표%20ppt%20공유/week9/9주차-6팀.pptx) | 발표 자료 | 중복 | 2026-05-13 |
| 3  | [9주차 6팀 발표 자료 (NFD 원본)](docs/발표%20ppt%20공유/week9/9%E1%84%8C%E1%85%AE%E1%84%8E%E1%85%A1-6%E1%84%90%E1%85%B5%E1%86%B7.pptx) | 발표 자료 | 완료 | 2026-05-12 |
| 4  | [10주차 3팀 발표 자료](docs/발표%20ppt%20공유/week10/10주차-3팀.pptx) | 발표 자료 | 완료 | 2026-05-12 |
| 5  | [9주차 3팀 발표 자료](docs/발표%20ppt%20공유/week9/9주차-3팀.pptx) | 발표 자료 | 완료 | 2026-05-12 |
| 6  | [발표 자료 업로드 안내](docs/발표%20ppt%20공유/presentation-upload-guide.md) | 발표 자료 | 완료 | 2026-05-12 |
| 7  | [10주차 5팀 발표 자료](docs/발표%20ppt%20공유/week10/10주차-5팀.pptx) | 발표 자료 | 완료 | 2026-05-12 |
| 8  | [9주차 5팀 발표 자료](docs/발표%20ppt%20공유/week9/9주차-5팀.pptx) | 발표 자료 | 완료 | 2026-05-12 |
| 9  | [팀장 회의록 — 2026-05-11 (월)](docs/meeting-minutes/week11/2026-05-11.md) | 회의록 | 완료 | 2026-05-11 |
| 10 | [팀장 회의록 — 2026-05-08 (금)](docs/meeting-minutes/week11/2026-05-08.md) | 회의록 | 완료 | 2026-05-11 |
| 11 | [팀장 회의록 — 2026-05-04 (월)](docs/meeting-minutes/week10/2026-05-04.md) | 회의록 | 완료 | 2026-05-05 |
| 12 | [팀장 회의록 — 2026-05-02](docs/meeting-minutes/week10/2026-05-02.md) | 회의록 | 완료 | 2026-05-03 |
| 13 | [회의록 — 2026-05-01](docs/meeting-minutes/week10/2026-05-01.md) | 회의록 | 완료 | 2026-05-03 |
| 14 | [Week 10 팀 레포 현황](docs/팀운영/주차별-팀레포/week10.md) | 팀운영 | 완료 | 2026-05-02 |
| 15 | [회의록 — 2026-04-30](docs/meeting-minutes/week9/2026-04-30.md) | 회의록 | 완료 | 2026-04-30 |
| 16 | [팀장 회의록 — 2026-04-29](docs/meeting-minutes/week9/2026-04-28.md) | 회의록 | 완료 | 2026-04-29 |
| 17 | [팀 회의록 — 2026-04-27](docs/meeting-minutes/week9/2026-04-27.md) | 회의록 | 완료 | 2026-04-28 |
| 18 | [REST API](docs/네트워크/rest-api.md) | 네트워크 | 스텁 | 2026-04-27 |
| 19 | [프록시 서버](docs/네트워크/proxy.md) | 네트워크 | 스텁 | 2026-04-27 |
| 20 | [TCP/IP, UDP, HTTP, DNS](docs/네트워크/protocols.md) | 네트워크 | 스텁 | 2026-04-27 |
| 21 | [OSI 7계층](docs/네트워크/osi-7-layer.md) | 네트워크 | 스텁 | 2026-04-27 |
| 22 | [HTTP Methods](docs/네트워크/http-methods.md) | 네트워크 | 스텁 | 2026-04-27 |
| 23 | [CDN](docs/네트워크/cdn.md) | 네트워크 | 스텁 | 2026-04-27 |
| 24 | [BSD 소켓](docs/네트워크/bsd-socket.md) | 네트워크 | 스텁 | 2026-04-27 |
| 25 | [JavaScript](docs/web-security/javascript.md) | 웹 보안 | 스텁 | 2026-04-27 |
| 26 | [HTTP & Security](docs/web-security/http-security.md) | 웹 보안 | 스텁 | 2026-04-27 |
| 27 | [암호 보안](docs/web-security/cryptography.md) | 웹 보안 | 스텁 | 2026-04-27 |
| 28 | [회원관리 (OAuth2)](docs/web-security/authentication.md) | 웹 보안 | 스텁 | 2026-04-27 |
| 29 | [LLM](docs/ai/llm.md) | AI | 스텁 | 2026-04-27 |
| 30 | [신경망](docs/ai/neural-network.md) | AI | 스텁 | 2026-04-27 |

> 범례: `완료` 본문 작성 완료 · `스텁` 작성 필요 · `작성중` 작성 진행 중 · `중복` 동일 콘텐츠가 두 경로로 트래킹 중

---

## 카테고리별 인덱스

각 카테고리 폴더의 `README.md`가 해당 카테고리의 정식 목차입니다. 아래는 한눈에 보는 키워드 맵입니다.

### [CS 기초](docs/cs-기초/) — 10개

32/64bit · 보수 표현 · 부동소수점 · 메모리 구조(Stack/Heap) · 포인터/배열 · Call by Value/Reference · Garbage Collection · CPU vs GPU · SSD vs HDD · 이미지 포맷

### [알고리즘](docs/algorithm/) — 10개

Big-O · 정렬 · 해시테이블 · DFS/BFS · DP/Greedy · 재귀/반복 · 그래프/트리 · 균형 이진 트리 · 깊은/얕은 복사 · 기본 자료구조

### [Malloc Lab](docs/malloc-lab/) — 2개

Implicit/Explicit/Seglist/Buddy · Fragmentation

### [OS](docs/os/) — 17개

OS 정의 · Process/Thread · CPU 스케줄링 · Semaphore/Mutex · Race Condition · Deadlock · Context Switching · System Call · Kernel · Atomic Operation · Interrupt · 가상 메모리 · 페이징 · Cache · TLB · Page Fault · Linux Redirection/Pipe

### [Pintos](docs/pintos/) — 24개

| 프로젝트 | 키워드 |
|----------|--------|
| [Project 0 — Get Started](docs/pintos/project0/) | QEMU · 가상 머신 · Common Bugs |
| [Project 1 — Threads](docs/pintos/project1-threads/) | Thread · Scheduler · Synchronization · Timer · Time Sharing |
| [Project 2 — User Programs](docs/pintos/project2-userprog/) | Process · Syscall · ELF Loader · File Descriptor · User Stack · User/Kernel Mode |
| [Project 3 — Virtual Memory](docs/pintos/project3-vm/) | Paging · Page Types · MMU/TLB · Swap · Copy-on-Write |
| [Project 4 — File System](docs/pintos/project4-filesys/) | FS Components · FS Implementation · FS Types · Buffer Cache · Mount/Journaling |

### [네트워크](docs/네트워크/) — 7개

OSI 7계층 · TCP/IP, UDP, HTTP, DNS · HTTP Methods · REST API · BSD 소켓 · 프록시 · CDN

### [웹 보안](docs/web-security/) — 4개

JavaScript 비동기 · HTTP & Security (XSS/CORS) · 암호 보안 · 회원관리 (OAuth2)

### [DB](docs/db/) — 3개

RDBMS vs NoSQL · Index · B-Tree / B+ Tree

### [AI](docs/ai/) — 3개

신경망 (퍼셉트론, MLP, 활성화/손실/역전파) · LLM (Transformer, GPT, Attention, Fine-tuning) · AI 응용기술 (RAG, MCP, AI Agent)

### [회의록](docs/meeting-minutes/) — 10개 (전부 작성완료)

Week 9 (4/25, 4/27, 4/29, 4/30) · Week 10 (5/01, 5/02, 5/04) · Week 11 (5/08, 5/11, 5/12)

### [팀 운영](docs/팀운영/) — 7개

[컨벤션](docs/팀운영/컨벤션/) (Git · 코드 · PR/리뷰) · [외부 리소스](docs/팀운영/외부리소스/) (개발 환경 · 학습 자료 · Pintos 도구) · [주차별 팀 레포](docs/팀운영/주차별-팀레포/) (Week 10 작성완료)

### [발표 자료](docs/발표%20ppt%20공유/) — 6개 (전부 작성완료)

[업로드 가이드](docs/발표%20ppt%20공유/presentation-upload-guide.md) · Week 9 발표자료 3건([3팀](docs/발표%20ppt%20공유/week9/9주차-3팀.pptx) · [5팀](docs/발표%20ppt%20공유/week9/9주차-5팀.pptx) · [6팀](docs/발표%20ppt%20공유/week9/9주차-6팀.pptx)) · Week 10 발표자료 2건([3팀](docs/발표%20ppt%20공유/week10/10주차-3팀.pptx) · [5팀](docs/발표%20ppt%20공유/week10/10주차-5팀.pptx))

---

## 관련 주제 매핑

여러 카테고리에 걸쳐 있는 주제는 의도적으로 별도의 페이지로 분리되어 있습니다. 학습 시 함께 보면 좋습니다.

| 핵심 개념 | 일반 OS 관점 | Pintos 구현 관점 |
|-----------|--------------|-------------------|
| 페이징 | [os/paging.md](docs/os/paging.md) | [pintos/project3-vm/paging.md](docs/pintos/project3-vm/paging.md) |
| 가상 메모리 | [os/virtual-memory.md](docs/os/virtual-memory.md) | [pintos/project3-vm/](docs/pintos/project3-vm/) |
| TLB / MMU | [os/tlb.md](docs/os/tlb.md) | [pintos/project3-vm/mmu-tlb.md](docs/pintos/project3-vm/mmu-tlb.md) |
| 컨텍스트 스위칭 / 스레드 | [os/context-switching.md](docs/os/context-switching.md) · [os/process-thread.md](docs/os/process-thread.md) | [pintos/project1-threads/thread.md](docs/pintos/project1-threads/thread.md) · [pintos/project1-threads/scheduler.md](docs/pintos/project1-threads/scheduler.md) |
| 시스템 콜 | [os/system-call.md](docs/os/system-call.md) | [pintos/project2-userprog/syscall.md](docs/pintos/project2-userprog/syscall.md) |
| 캐시 | [os/cache.md](docs/os/cache.md) | [pintos/project4-filesys/buffer-cache.md](docs/pintos/project4-filesys/buffer-cache.md) |
| 메모리 구조 | [cs-기초/memory-structure.md](docs/cs-기초/memory-structure.md) | [malloc-lab/](docs/malloc-lab/) · [pintos/project2-userprog/user-stack.md](docs/pintos/project2-userprog/user-stack.md) |

---

## 중복 정리 권고

자동 인덱싱이 중복으로 의심한 항목입니다. 인덱스에서는 단일 항목으로 병합해 노출했으나, 저장소 정리가 필요합니다.

### 9주차 6팀 발표자료 — NFC/NFD 동일 파일 2개

- `docs/발표 ppt 공유/week9/9주차-6팀.pptx` (한글 자모 NFD, 9bb86bc에서 추가) · 7,676,304 B
- `docs/발표 ppt 공유/week9/9주차-6팀.pptx` (한글 자모 NFC, a52759a에서 재추가) · 7,676,304 B
- 두 파일은 **MD5 일치(`2e6a1f9237a4906f4877d124c2850173`)**, 동일 콘텐츠입니다.
- 권고: 둘 중 한 파일만 남기고 다른 하나를 `git rm` 처리. macOS에서 업로드된 파일은 한글이 NFD로 저장되는 경향이 있고, 다른 OS에서 만든 파일은 NFC로 들어옵니다. 어느 쪽을 정본으로 둘지 팀장 회의에서 1회 합의 후 `.gitattributes` 또는 업로드 가이드에 표준 인코딩을 명시해두면 재발을 막을 수 있습니다.

> 직전 인덱싱(2026-05-12)에서 "해소"로 보고했던 항목이 신규 커밋(`a52759a`)에서 재발생했습니다.

---

## 빠른 시작 (온보딩)

### 1. 레포 클론

```bash
git clone https://github.com/Jungle-12-303/WIKI.git
cd WIKI
```

### 2. 구조 파악

```
docs/
  cs-기초/             CS 기본 개념 (메모리, 포인터, 보수 표현 등)
  algorithm/           알고리즘 및 자료구조
  malloc-lab/          동적 메모리 할당기 구현
  네트워크/             TCP/IP, HTTP, REST API, OSI 7계층
  os/                  운영체제 핵심 개념
  pintos/              Pintos 프로젝트 (Project 0~4)
  ai/                  신경망, LLM, AI 응용기술
  db/                  데이터베이스
  web-security/        웹 개발 & 보안
  팀운영/               컨벤션, 외부리소스, 주차별 팀레포
  meeting-minutes/     팀장 회의록 (Week 9 ~ Week 11)
  발표 ppt 공유/        업로드 가이드 + 주차별 팀 발표 자료(.pptx)
```

각 폴더의 `README.md`가 해당 카테고리의 목차입니다.

### 3. 키워드 작성 흐름

1. 카테고리 폴더의 `README.md`에서 `작성 필요` 상태인 키워드를 선택합니다.
2. 해당 키워드의 `README.md` 상태를 `작성 중 (@이름)`으로 변경 후 커밋합니다.
3. 키워드 파일에 내용을 작성합니다.
4. 완료 후 상태를 `완료`로 변경하고 커밋합니다.

### 4. 발표 자료 업로드

`docs/발표 ppt 공유/presentation-upload-guide.md`의 안내에 따라 `docs/발표 ppt 공유/week{N}/<주차>-<팀>.pptx` 형식으로 업로드합니다.

---

## 기여 규칙 요약

자세한 규칙은 [CONTRIBUTING.md](CONTRIBUTING.md)를 참고하세요.

| 규칙 | 내용 |
|------|------|
| 하나의 파일, 한 사람 | 같은 키워드 파일을 두 사람이 동시에 수정하지 않습니다. |
| 상태 먼저 변경 | 작성 시작 전 README.md 상태를 `작성 중 (@이름)`으로 바꾸고 커밋합니다. |
| 커밋 메시지 | `docs: <한국어 제목>` 형식 ([Conventional Commits](https://www.conventionalcommits.org/)) |
| 파일명 | 영문 소문자 + 하이픈, 공백 금지. |
| 키워드 템플릿 | `# 제목` → `> 요약` → `## 개요` → `## 상세 설명` → `## 참고 자료` |

---

## 커밋 컨벤션

| 타입 | 용도 |
|------|------|
| `docs` | 키워드 작성, 문서 변경 (가장 많이 사용) |
| `feat` | 새로운 스크립트나 도구 추가 |
| `fix` | 오류 수정 |
| `chore` | 폴더 구조 변경, 설정 변경 |

---

## 관련 저장소

| 저장소 | 역할 |
|--------|------|
| [Team-Template](https://github.com/Jungle-12-303/Team-Template) | 공용 개발 환경, 유틸리티, 컨벤션, 스킬 |
| 이 저장소 (WIKI) | 공동 학습 기록, 키워드 정리 |
