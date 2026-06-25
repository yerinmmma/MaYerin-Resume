# 마예린 (Ma Yerin)

| | |
|---|---|
| **GitHub** | https://github.com/yerinmmma |
| **E-mail** | yelinma66@gmail.com |

---

# Education

## 단국대학교

| | |
|---|---|
| **period** | 2024.03 ~ 재학 중 |
| **major** | 사이버보안학과 |
| **GPA** | 3.6 / 4.5 |

---

# Projects

## 바이너리 취약점 분석 및 익스플로잇 구현

| | |
|---|---|
| **period** | 2026.04 ~ 2026.06 |
| **stack** | C, Python, pwntools, GDB, OllyDbg, x64dbg |

- 버퍼 오버플로우, 포맷 스트링 취약점을 분석하고 `%lx`, `%s`를 활용해 스택 메모리를 리킹
- 카나리 값을 먼저 리킹한 뒤 오버플로우를 시도하는 2단계 스택 카나리 우회 기법 구현
- ROP(Return Oriented Programming) 체인 및 Return-to-libc 익스플로잇 구성

## CPU 스케줄러 시뮬레이터 (OS Lab 1)

| | |
|---|---|
| **period** | 2026.04 |
| **stack** | C |

- FCFS, SPN, Round-Robin, MLFQ 4종 구현 및 Turnaround Time / Response Time 비교 분석
- `Scheduler` 부모 클래스 → 각 알고리즘 자식 클래스 구조로 설계해 코드 재사용성 확보
- (보너스) Lottery, Stride 스케줄링 추가 구현, 티켓 기반 스케줄링 정책 분석

## 멀티스레드 해시테이블 동시성 제어 (OS Lab 2)

| | |
|---|---|
| **period** | 2026.04 |
| **stack** | C, pthread |

- Without Lock / Coarse-grained Lock / Fine-grained Lock 3가지 방식 구현
- 스레드 수(1, 2, 4, 8) × 워크로드(Insert/Lookup/Delete 비율) 조합으로 처리 시간 측정
- Bucket 단위 Fine-grained Lock이 Coarse-grained Lock 대비 우수한 성능임을 실험으로 검증

## EXT2 파일시스템 디지털 포렌식 (OS Lab 3)

| | |
|---|---|
| **period** | 2026.05 |
| **stack** | C, Linux, xxd |

- RAM Disk 위 EXT2를 `xxd`로 hex 단위 분석: Superblock → GDT → Inode Table → Data Block 구조 추적
- Direct / Single Indirect Pointer 구조 분석으로 Target File의 실제 Data Block 위치 역추적
- (보너스) EXT2 커널 모듈 소스 수정 → 마운트 시 커스텀 로그 출력 구현

## 식당 추천 프로그램

| | |
|---|---|
| **period** | 2024.10 ~ 2024.11 |
| **stack** | Python |
| **code** | [보기](https://github.com/yerinmmma/Yerin-File/blob/main/main.py) |

- 클래스 상속과 다형성을 활용한 콘솔 기반 추천 프로그램
- `restaurant.py` / `main.py` 모듈 분리로 코드 재사용성 강화

---

# Skills

| 분야 | 기술 |
|---|---|
| Language | C, Python, x86 Assembly |
| Tools | GDB, OllyDbg, x64dbg, pwntools |
| Environment | Linux (Ubuntu), Git |
| Database | SQL |

---

# Activities

## 한국장학재단 사회리더 대학생 멘토링 제17기

| | |
|---|---|
| **period** | 2026.04 ~ 2026.11 |

보안 분야 멘토와 매칭, 진로 및 역량개발 멘토링 진행 중





