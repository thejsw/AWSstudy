## 📘 Amazon EKS란?

> 🧠 **한 줄 요약**:  
> "Kubernetes를 AWS에서 쉽게 사용할 수 있도록 도와주는 완전관리형 서비스"

---

### ✅ 주요 개념 요약

| 항목 | 설명 |
|------|------|
| Kubernetes란? | 컨테이너(예: Docker)를 자동으로 배포, 관리, 확장해주는 오픈소스 플랫폼 |
| EKS란? | AWS가 Kubernetes를 자동으로 설치, 운영, 관리해주는 서비스 |
| 특징 | 고가용성, 보안, 자동 패치 제공. AWS 서비스(예: IAM, ELB 등)와 통합됨 |
| 사용 이유 | 직접 Kubernetes를 설치·관리하지 않고도 안정적으로 컨테이너 오케스트레이션 가능 |

---

### 📦 비유로 이해하기

> 여러 개의 컨테이너(Docker)를 실행하고 싶어요.  
> 그런데 직접 Kubernetes를 설치해서 사용하려면… 복잡하고 귀찮아요.

그래서 AWS가 말해요:

> "내가 Kubernetes 서버랑 설정은 다 해줄게.  
> 너는 그냥 컨테이너만 올려!"

그게 바로 **Amazon EKS**입니다.

---

### ✅ 언제 사용하면 좋을까?

- 🧱 **컨테이너(Docker)** 를 대규모로 운영하고 싶을 때  
- 🔧 **마이크로서비스 아키텍처**를 사용하는 프로젝트  
- 🙅‍♂️ Kubernetes는 쓰고 싶은데, **운영은 직접 하고 싶지 않을 때**

---

## 📝 Cloud Practitioner 스타일 문제 예제

### ✅ 문제 1: 개념 이해

**Q1. Amazon EKS는 어떤 AWS 서비스인가요?**

- A. AWS에서 가상 서버를 제공하는 서비스  
- B. AWS에서 자동화된 기계학습 모델을 운영하는 서비스  
- C. AWS에서 Kubernetes 기반 컨테이너를 실행하고 관리하는 서비스 ✅  
- D. AWS에서 SQL 데이터베이스를 호스팅하는 서비스  

**🟢 정답: C**

💬 **해설**:  
EKS는 Kubernetes를 AWS에서 쉽게 운영할 수 있도록 도와주는 **완전관리형 컨테이너 관리 서비스**입니다.

---

### ✅ 문제 2: 특징 파악

**Q2. Amazon EKS의 주요 특징으로 올바르지 않은 것은 무엇인가요?**

- A. Kubernetes 클러스터의 설치와 관리를 자동으로 수행한다  
- B. AWS의 보안 서비스(IAM 등)와 통합된다  
- C. 컨테이너를 위한 서버리스 환경으로 실행된다 ❌  
- D. 고가용성과 확장성을 지원한다  

**🟢 정답: C**

💬 **해설**:  
EKS는 EC2 또는 Fargate 위에서 Kubernetes를 실행하지만, 자체가 완전한 **서버리스 서비스는 아닙니다** (예: Lambda처럼).

---

### ✅ 문제 3: 사용 사례

**Q3. 한 회사가 여러 개의 마이크로서비스를 Docker 컨테이너로 운영하려고 합니다. 이 컨테이너들을 효율적으로 관리하고 싶고, Kubernetes를 사용하고 싶지만 인프라 관리에는 시간을 쓰고 싶지 않습니다. 어떤 AWS 서비스가 가장 적합할까요?**

- A. Amazon ECS  
- B. AWS Lambda  
- C. Amazon EKS ✅  
- D. AWS Batch  

**🟢 정답: C**

💬 **해설**:  
EKS는 Kubernetes를 AWS에서 쉽게 사용하고 관리할 수 있게 해주는 서비스이므로 가장 적합합니다.

---
