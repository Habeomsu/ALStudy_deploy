# 알고리즘 스터디 다양한 배포 방식입니다.

## 애플리케이션 구성
Spring + React + Flask + Mysql + RabbitMq


## 1. 가장 기본적인 배포
1. **EC2에 Java, Node.js, Python 설치**
2. **Spring, Flask, React를 배포**
3. **AWS RDS(MySQL) 사용**
4. **EC2 내부에서  RabbitMQ 설치**
5. **Nginx 설정 및 리버스 프록시 적용**
6. **도메인 및 HTTPS 적용 (선택, Let's Encrypt 가능)**
- [v1 배포 바로가기](https://github.com/Habeomsu/ALStudy_deploy/tree/main/v1)
  
## 2. Docker를 사용한 배포
- [v2 배포 바로가기](https://github.com/Habeomsu/ALStudy_deploy/tree/main/v2)
## 3. CI/CD를 사용한 배포
- [v3 배포 바로가기] (https://github.com/Habeomsu/alstudy_v3)
