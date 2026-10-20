<h1 align="center">NOAHSOFT</h1>

<p align="center">
  <strong>아이디어를 코드로. 일상에는 여유를.</strong><br />
  <sub>Independent software development · Products, infrastructure, and automation</sub>
</p>

<p align="center">
  <a href="https://noahsoft.kr">Website</a> ·
  <a href="https://github.com/NOAHSOFTKR?tab=repositories">Repositories</a> ·
  <a href="https://noahsoft.kr/security">Security</a>
</p>

---

## About NOAHSOFT

**NOAHSOFT(노아소프트)**는 대한민국을 기반으로 자체 소프트웨어를 기획·개발·운영하는 소프트웨어 개발 조직입니다.

Discord 서비스부터 인증·보안, 재무 관리, 개발 자동화, 게임 서버에 이르기까지 실사용 환경에서 발생하는 문제를 제품과 시스템으로 해결합니다. 단순히 기능을 구현하는 데 그치지 않고, **안정적으로 운영하고 지속적으로 개선할 수 있는 소프트웨어**를 지향합니다.

> We build software — and take responsibility for running it.

## Featured Products

| Product | Area | Description |
| :-- | :-- | :-- |
| **[Nia](https://github.com/NOAHSOFTKR/ttsbot)** | Voice · Discord | Discord 음성 채널에서 텍스트 메시지를 음성으로 전달하는 TTS 서비스 |
| **[Sentinel](https://github.com/NOAHSOFTKR/Sentinel)** | Security | Discord 서버 위협 탐지, 사건 기록, 정책 기반 대응 및 복구를 위한 보안 플랫폼 |
| **[Ledger](https://github.com/NOAHSOFTKR/Ledger)** | Finance | 거래·정산·비용 기록의 일관성과 추적 가능성을 중시하는 중앙 재무 원장 |
| **[NS Account](https://github.com/NOAHSOFTKR/oauth2)** | Identity | NOAHSOFT 서비스 전반의 통합 계정 및 인증 연동 시스템 |
| **[NS-STORE](https://github.com/NOAHSOFTKR/ns-store)** | Commerce | 디지털 상품과 서비스 멤버십을 위한 상거래·결제 시스템 프로젝트 |
| **[Arcana](https://github.com/NOAHSOFTKR/arcana)** | Gaming | Minecraft 기반 게임 서버 및 관련 시스템 개발 프로젝트 |

> 각 프로젝트의 개발·배포 상태와 사용 방법은 해당 저장소의 문서를 참고해 주세요.

## Developer Tools & Infrastructure

제품을 뒷받침하는 공통 기반 기술과 자동화 도구도 개발합니다.

| Project | Purpose |
| :-- | :-- |
| **[Pernorama](https://github.com/NOAHSOFTKR/pernorama)** | 선언형 권한 노드를 사용하는 Java 권한 관리 라이브러리 |
| **[Sentinel Edge](https://github.com/NOAHSOFTKR/Sentinel-Edge)** | Sentinel Core 장애 중에도 보안 이벤트 기록과 최소한의 방어 기능을 유지하도록 설계된 독립 실행 계층 |
| **[NOAHSOFT Sign](https://github.com/NOAHSOFTKR/noahsoft-sign)** | 전자서명, 문서 무결성 검증, 서명 증빙 관리를 위한 공통 플랫폼 |
| **[Biseo](https://github.com/NOAHSOFTKR/biseo)** | 사람과 AI 작업자의 계획·배정·승인·검증을 조정하는 작업 오케스트레이션 시스템 |
| **[Remedy](https://github.com/NOAHSOFTKR/Remedy)** | 오류 수집·분석과 격리된 환경의 수정·검증·PR 생성 자동화를 위한 프로젝트 |

## Engineering Principles

- **Reliability first** — 장애를 감지하고 원인을 추적하며 복구할 수 있도록 설계합니다.
- **Security by design** — 최소 권한, 안전한 기본값, 명시적 승인과 감사 기록을 중요하게 생각합니다.
- **Automation with control** — 반복 작업은 자동화하되, 위험한 변경에는 검증과 통제를 둡니다.
- **Maintainability** — 명확한 모듈 경계, 테스트, 문서화, 코드 리뷰를 중시합니다.
- **Operational feedback** — 실제 운영 중 발견한 문제를 다음 개선의 출발점으로 삼습니다.

## Technology

프로젝트에 따라 다음 기술을 사용합니다.

`TypeScript` · `Node.js` · `Java` · `Kotlin` · `Python` · `React` · `Spring Boot` · `MySQL` · `Docker` · `GitHub Actions`

기술 선택은 유행보다 요구사항, 운영 환경, 유지보수 비용을 기준으로 판단합니다.

## Community & Contributions

NOAHSOFT는 공개 저장소에서의 이슈 제보, 버그 재현, 문서 개선, 코드 기여와 기술 교류를 중요하게 생각합니다.

- 기여하기 전 해당 저장소의 README, 라이선스와 기여 안내를 확인해 주세요.
- 버그 제보 시 재현 절차, 기대 동작, 실제 동작, 관련 로그를 남겨주면 도움이 됩니다.
- Pull Request는 변경 목적, 검증 방법, 영향 범위를 함께 설명해 주세요.

**NOAHSOFT Developers**는 NOAHSOFT가 별도로 운영하는 학생 개발자 커뮤니티입니다. 자율적인 기술 교류와 공개 프로젝트 기여를 위한 공간이며, 참여 자체가 고용 또는 근로계약을 의미하지 않습니다.

> 공개 저장소라는 사실만으로 모든 코드에 자유로운 재사용·재배포 권한이 부여되는 것은 아닙니다. 각 프로젝트의 라이선스를 확인해 주세요.

## Security

보안 문제는 공개 Issue에 공격 절차, 토큰, 개인정보, 민감한 로그를 게시하지 말아 주세요.

취약점 제보 및 보안 관련 연락 방법은 **[NOAHSOFT Security](https://noahsoft.kr/security)**에서 확인해 주세요. 보안 보고에는 영향을 받는 서비스, 재현에 필요한 최소 정보, 예상되는 영향 범위를 포함하는 것이 좋습니다.

## Links

- **Website:** https://noahsoft.kr
- **GitHub:** https://github.com/NOAHSOFTKR
- **Security:** https://noahsoft.kr/security

---

<p align="center"><strong>아이디어를 코드로. 일상에는 여유를.</strong></p>
