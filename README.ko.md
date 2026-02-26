# AWS DevOps Professional (DOP-C02) 학습 노트

<img src="image.png" alt="대표 이미지" width="100"/>

> **DOP-C02 시험 도메인 비중**
>
> | 도메인 | 비중 |
> |---|---|
> | 1. SDLC 자동화 | 22% |
> | 2. 구성 관리 및 IaC | 17% |
> | 3. 복원력 있는 클라우드 솔루션 | 15% |
> | 4. 모니터링 및 로깅 | 15% |
> | 5. 인시던트 및 이벤트 대응 | 15% |
> | 6. 보안 및 규정 준수 | 16% |

---

## 학습 노트 목차

| 섹션 | 설명 | 링크 |
|---|---|---|
| **1. SDLC 자동화** | CI/CD 파이프라인, 배포 전략, Code 서비스 | [바로가기](/1.SDLC%20Automation.ko.md) |
| **2. 구성 관리 및 IaC** | CloudFormation, CDK, SAM, OpsWorks | [바로가기](/2.Configuration%20Management%20and%20IaC.ko.md) |
| **3. 복원력 있는 클라우드 솔루션** | HA/FT, DR 전략, Route 53, Auto Scaling | [바로가기](/3.Resilient%20Cloud%20Solutions.ko.md) |
| **4. 모니터링 및 로깅** | CloudWatch, CloudTrail, Config, Trusted Advisor | [바로가기](/4.Monitoring%20and%20Logging.ko.md) |
| **5. 인시던트 및 이벤트 대응** | EventBridge, 이벤트 기반 자동화, ADOT | [바로가기](/5.Incident%20and%20event%20response.ko.md) |
| **6. 보안 및 규정 준수** | IAM, Organizations, Control Tower, WAF | [바로가기](/6.Security%20and%20Compliance.ko.md) |
| **7. 추가 AWS 서비스** | EMR, DMS, FSx, EKS, 2025 신규 서비스 | [바로가기](/7.More%20AWS%20Services%20to%20Focus.ko.md) |
| **8. AWS 치트시트** | 핵심 서비스 한눈에 보기 | [바로가기](/8.%20AWS%20Cheatsheet.ko.md) |

---

## 시험 준비 핵심 팁

1. **핵심 서비스 우선 학습** — 컴퓨팅(EC2, Lambda), 스토리지(S3, DynamoDB), 네트워킹(VPC, Route 53)
2. **IAM 완벽 이해** — 정책 평가 로직(명시적 거부 우선), 역할 위임, 교차 계정 액세스
3. **Well-Architected Framework** — 특히 운영 우수성 / 보안 / 신뢰성 관점의 시나리오 연습
4. **실습 필수** — 프리 티어 또는 샌드박스 계정으로 CI/CD 파이프라인을 직접 구축
5. **공식 문서 기준** — AWS 문서와 화이트페이퍼를 기준으로 개념 정리

> **주의**: 시험 덤프(Exam Dump)에 의존하지 마세요.

---

## 추천 학습 리소스

### 강의

| 리소스 | 플랫폼 | 비용 |
|---|---|---|
| Stephane Maarek — AWS DevOps Engineer Professional | [Udemy](https://www.udemy.com/course/aws-certified-devops-engineer-professional-hands-on/) | 유료 |
| Pluralsight — DOP-C02 | [Pluralsight](https://www.pluralsight.com/cloud-guru/courses/aws-certified-devops-engineer-professional-dop-c02) | 유료 |
| Whizlabs — DOP-C02 | [Whizlabs](https://www.whizlabs.com/aws-devops-certification-training/) | 유료 |
| Coursera — DevOps on AWS Specialization | [Coursera](https://www.coursera.org/specializations/aws-devops) | 유료 |
| AWS Skill Builder — Exam Readiness | [AWS Skill Builder](https://aws.amazon.com/skillbuilder/courses/exam-readiness-aws-certified-devops-engineer-professional) | 무료 |
| AWS Learning Plans — DevOps Engineering on AWS | [AWS Learning Plans](https://aws.amazon.com/learning-plans/) | 무료 |

### 실습 & 모의고사

| 리소스 | 설명 | 비용 | 링크 |
|---|---|---|---|
| CloudAcademy Labs | DOP-C02 특화 실습 랩 | 유료 | [바로가기](https://cloudacademy.com/learning-paths/aws-devops-engineer-professional-dop-c02-certification-preparation-for-aws-1-9637/?program=1acec0f4-f7a7-44b8-9768-ad8792c9ba6d) |
| Tutorials Dojo | 실전 난이도 모의고사 | 유료 | [바로가기](https://portal.tutorialsdojo.com/courses/aws-certified-devops-engineer-professional-practice-exams/) |
| ExamTopics | 무료 연습 문제 | 무료 | [바로가기](https://www.examtopics.com/exams/amazon/aws-certified-devops-engineer-professional-dop-c02/) |
| AWS 공식 모의고사 | Skill Builder 내 제공 | 구독 | [바로가기](https://aws.amazon.com/skillbuilder/) |

### 공식 리소스 & 커뮤니티

| 유형 | 리소스 | 링크 |
|---|---|---|
| 공식 | 시험 가이드 | [AWS Certification](https://aws.amazon.com/certification/certified-devops-engineer-professional/) |
| 공식 | AWS 문서 | [docs.aws.amazon.com](https://docs.aws.amazon.com/) |
| 공식 | AWS 화이트페이퍼 | [aws.amazon.com/whitepapers](https://aws.amazon.com/whitepapers/) |
| 블로그 | AWS DevOps Blog | [aws.amazon.com/blogs/devops](https://aws.amazon.com/blogs/devops/) |
| 커뮤니티 | Reddit r/AWSCertification | [Reddit](https://www.reddit.com/r/awscertification/) |
| 커뮤니티 | AWS Developer Community | [developer.aws/community](https://developer.aws/community/) |
| 학습 후기 | 60일 합격 후기 (Damien Burks) | [바로가기](https://damienjburks.com/how-i-conquered-the-aws-devops-professional-exam-in-60-days) |
| 학습 후기 | Associate → Professional 여정 | [Medium](https://medium.com/@Amet13/aws-devops-certification-ea08b0b69a7c) |
| 치트시트 | Spacelift Cheat Sheet | [바로가기](https://spacelift.io/blog/aws-certified-devops-engineer-professional) |

---

## FAQ

**Q: 시험 준비에 얼마나 걸리나요?**
A: 이전 경험에 따라 다르지만, 평균 **2~3개월**의 꾸준한 학습이 권장됩니다.

**Q: 실습 랩이 꼭 필요한가요?**
A: 네. AWS는 실무 기반 지식을 강조하며, 랩은 실제 서비스 경험을 쌓는 가장 좋은 방법입니다.

---

## 기여
오탈자 수정, 최신 서비스 반영, 시나리오 추가 등 PR 기여를 환영합니다.
