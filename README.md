# 한지찬 · Backend Engineer

차량 보안 도메인의 백엔드 시스템을 만들고 있습니다. 트랜잭션 스크립트 패턴 보다는 풍부한 도메인과 도메인 모델 패턴, 의존성 분리, 테스트 전략에 관심을 두고 개발하고 있습니다.

강의나 책으로 감이 잘 오지 않는 개념은 작은 예제를 만들어 직접 돌려보는 편입니다. 그렇게 확인한 코드는 [deep-dive](https://github.com/HJC96/deep-dive)에 모아두고 있습니다.

새롭게 알게 된 내용이나 개발하면서 고민했던 일은 [블로그](https://blog.naver.com/gkswlcjs2)에 정리하는 습관이 있습니다.

---

## Deep Dive

### [deep-dive](https://github.com/HJC96/deep-dive)

백엔드 주제를 직접 실행해보기 위해 만든 코드들을 모아둔 저장소입니다. `labs/` 아래에 주제별 모듈을 두고 있으며, 비교가 필요한 주제는 같은 시나리오를 여러 방식으로 구현했습니다.

- **동시성 제어** — 락 없는 구현부터 원자적 UPDATE, 비관적·낙관적 락, 네임드 락, Redis 분산 락과 Lua까지 9가지 방식을 같은 쿠폰 발급 시나리오에서 비교
- **분산 트랜잭션** — Monolith·MSA 기준선을 두고 부분 커밋을 재현한 뒤 2PC와 TCC를 실행
- **캐시** — Cache Aside, Null Caching, TTL Jitter, Hot Key 방어 구현
- **테스트 인프라** — Testcontainers 기반 동적 DB 설정과 ArchUnit 아키텍처 의존성 규칙 검증

[deep-dive](https://github.com/HJC96/deep-dive)

---

## Writing

새롭게 알게 된 내용과 개발하며 고민했던 일을 정리한 글들입니다.

### [재고 감소부터 분산 트랜잭션까지](https://blog.naver.com/gkswlcjs2/224369322094)

재고 차감에서 시작해 쿠폰 발급과 분산 트랜잭션까지 이어지는 동시성 문제를 세 가지 관점으로 정리했습니다. 관련 코드는 [deep-dive](https://github.com/HJC96/deep-dive)에 있습니다.

### [편집 충돌을 감지해서 Lost Update 막기](https://blog.naver.com/gkswlcjs2/224386963301)

여러 담당자가 같은 문서를 수정하는 기능을 개발하면서 고민했던 동시 수정 처리 방법을 정리했습니다.

### [2025년, 만 2년차 백엔드 개발자 회고](https://blog.naver.com/gkswlcjs2/224130531699)

백엔드 직무로 옮긴 뒤 테스트 코드와 프로세스 설계를 공부하고, 스터디 리딩과 멘토 역할을 경험한 한 해를 돌아봤습니다.

[블로그 전체 글 보기](https://blog.naver.com/gkswlcjs2)

---

## Timeline

- **Backend Software Engineer** `(2023.11.17 ~ Present)` · 현대오토에버  
  차량 보안 도메인의 백엔드 시스템 개발

- **Embedded Software Engineer** `(2021.10 ~ 2023.11.16)` · 현대오토에버  
  임베디드 소프트웨어 개발 후 2023년 백엔드 개발 직무로 전환

---

## Certifications

- [Confluent Apache Kafka Fundamentals Accreditation](https://certificates.confluent.io/5469f32a-2817-4885-ae5c-5a4bf3f60b90) `(2026.04)`
- [AWS Certified Solutions Architect – Associate](https://www.credly.com/badges/bbe2fad2-8edc-4fb5-8cd9-20b87d02aeb9/linked_in_profile) `(2026.03)`
- [MongoDB Associate Developer](https://learn.mongodb.com/c/p27Rqg76SrCOVIbwaxkmDw) `(2025.10)`
