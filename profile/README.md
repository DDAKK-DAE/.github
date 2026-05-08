# 딱대 🎬

> **숏폼 챌린지를 같이 찍을 사람을 찾아주는 오프라인 모임 앱**

"장원영 Magnetic 챌린지 같이 찍을 사람 구해요" — 인스타 스토리에 올리는 대신, 딱대에서 바로 모집하세요.

숏폼 소비를 죄책감의 대상이 아닌 **오프라인 여가의 트리거**로 바꿉니다.

---

## 서비스 플로우

```
챌린지 개설 → 참여 신청 → AI 케미 분석 → 크루 결성 → 오프라인 촬영 → 릴스 업로드 → 다음 챌린지 추천
```

1. 챌린지 모집 글 개설 (AI가 모집 글 자동 작성)
2. 신청자의 참여 이력 + 현재 멤버 조합을 AI가 분석해 **그룹 케미 점수** 제공
3. 수락 완료 시 크루 자동 결성 → 채팅방 오픈
4. 오프라인 촬영 후 릴스 업로드 → 같은 음원으로 몰아보기
5. 크루 채팅방에 **AI 다음 챌린지 추천** 카드 → 다시 모임으로 루프

---

## AI 기능 3종

| 기능 | 설명 |
|------|------|
| 챌린지 글 자동작성 | 제목·장소·인원 입력 → LLM이 MZ 감성 모집 글 + 해시태그 생성 |
| 그룹 케미 분석 | 현재 멤버 + 신청자 이력 조합 분석 → 적합도 점수 & 코멘트 |
| 크루 챌린지 추천 | 크루 참여 이력 × 트렌딩 챌린지 → 다음 챌린지 3개 추천 |

---

## 기술 스택

| 파트 | 기술 |
|------|------|
| Frontend | Next.js 16, TypeScript, TailwindCSS, TanStack Query |
| Backend | Spring Boot 4.0, Java 21, JPA, Flyway, JWT |
| AI Server | FastAPI, OpenAI GPT-4o |
| DB | PostgreSQL |
| Infra | AWS EC2, Docker Compose, GitHub Actions |

---

## 레포지토리

| 레포 | 설명 |
|------|------|
| [DDAK-DAE-BE](https://github.com/DDAKK-DAE/DDAK-DAE-BE) | Spring Boot 백엔드 |
| [DDAK-DAE-Front](https://github.com/DDAKK-DAE/DDAK-DAE-Front) | Next.js 프론트엔드 |
| [DDAK-DAE-AI](https://github.com/DDAKK-DAE/DDAK-DAE-AI) | FastAPI AI 서버 |

---

> 2026 해커톤 — **자극콘텐츠와 여가생활** 트랙
