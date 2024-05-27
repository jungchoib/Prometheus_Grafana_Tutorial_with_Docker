# Docker 튜토리얼 따라하기

https://docs.docker.com/get-started/

## Prometheus 설정

Prometheus를 설정한 후 웹 브라우저에서 다음 주소로 접속합니다:
- [http://localhost:9090](http://localhost:9090)

## Grafana 설정

Grafana를 설정한 후 웹 브라우저에서 다음 주소로 접속합니다:
- [http://localhost:3000](http://localhost:3000)

기본 로그인 정보는 다음과 같습니다:
- 사용자 이름: `admin`
- 비밀번호: `admin`

### Grafana에 Prometheus를 데이터 소스로 추가

1. Grafana에 로그인합니다.
2. Grafana UI에서 "Configuration" > "Data Sources" > "Add data source"로 이동합니다.
3. "Prometheus"를 선택합니다.
4. URL에 `http://prometheus:9090`을 입력하고 "Save & Test" 버튼을 클릭합니다.

### Grafana 대시보드 설정

Prometheus의 데이터를 시각화하기 위해 대시보드를 설정합니다.

1. Grafana UI에서 "Create" > "Dashboard" > "Add new panel"로 이동합니다.
2. 원하는 메트릭을 선택하고 그래프를 설정합니다.