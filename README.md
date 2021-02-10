# Reat-Springboot Book 프로젝트

### 스프링부트

- Springboot ^2.0
- JPA
- MySQL (H2)
- Maven
- Lombok

### React

- yarn add react-router-dom
- yarn add redux react-redux
- yarn add react-bootstrap bootstrap

```txt
import 'bootstrap/dist/css/bootstrap.min.css';
```

### 프로젝트 세팅

```json
{
  "singleQuote": true,
  "semi": true,
  "tabWidth": 2,
  "trailingComma": "all",
  "printWidth": 80
}
```

## AWS 배포하려면

root 접속 -> sudo passwd root -> su root 접속
apt update
apt install git (설치 되어있음)
apt install maven
apt install docker.io
apt install docker-compose

### 배포 명령

- mvn compile
- mvn clean package
- docker-compose up --build -d (백그라운드 실행)

### React와 Springboot 역방향 연결 link 걸기 (localhost로 같이 사용가능)

https://xiaolishen.medium.com/develop-in-docker-a-node-backend-and-a-react-front-end-talking-to-each-other-5c522156f634

### 도커 명령어

- docker volume ls
- docker volume prune
- docker stop $(docker ps -aq)
- docker rm $(docker ps -aq)
- docker rmi $(docker images -aq)
