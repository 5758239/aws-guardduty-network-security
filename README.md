### 프로젝트 주제

AWS 네트워크 보안 탐지 구축


### 프로젝트 개요

이 프로젝트는 AWS 클라우드 환경의 보안을 강화하기 위해 적절한 아키텍처를 설계하고 Amazon Guardduty를 활용하여 침해 사고를 탐지 및 분석하는 것을 목표로 합니다.


#### 프로젝트 요약

1. **AWS 아키텍처**:
   - 서울 리전에 VPC 생성, 퍼블릭 및 프라이빗 서브넷 구성, OpenVPN, ALB, NAT Gateway, 도커, 웹서버, 데이터베이스 배치.

2. **보안 설정**:
   - OpenVPN, 보안 그룹 설정을 통해 안전한 접근 관리.

3. **침해 탐지**:
   - Amazon CloudFormation으로 Amazon Guardduty 테스트 환경 구축.
   - Amazon GuardDuty를 이용해 로그 분석 및 위협 탐지.
   - FireHOL 오픈소스 위협 IP 목록 등록 및 Amazon Lambda를 활용한 자동 업데이트.

4. **모의 공격 및 대응**:
   - Shell 스크립트를 활용한 포트 스캔, 브루트 포스, 암호화폐 채굴 등 다양한 공격 시뮬레이션.
   - GuardDuty를 통한 실시간 탐지 및 위협도 평가.
   - Amazon SNS로 위협 감지 시 보안 관계자에게 이메일 알림.
