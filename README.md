# Prometheus_Grafana_Tutorial_with_Docker

follow docker tutorial https://docs.docker.com/get-started/

Prometheus: 웹 브라우저에서 http://localhost:9090으로 접속합니다.
Grafana: 웹 브라우저에서 http://localhost:3000으로 접속합니다. 기본 로그인 정보는 사용자 이름 admin, 비밀번호 admin입니다.

Grafana
Grafana에서 Prometheus를 데이터 소스로 추가:
    Grafana에 로그인한 후, 데이터 소스를 추가합니다.
        1. Grafana UI에서 "Configuration" > "Data Sources" > "Add data source"로 이동합니다.
        2. "Prometheus"를 선택합니다.
        3. URL에 http://prometheus:9090을 입력하고 "Save & Test" 버튼을 클릭합니다.
Grafana 대시보드 설정:
    이제 Prometheus의 데이터를 시각화하기 위한 대시보드를 설정할 수 있습니다.
        1. "Create" > "Dashboard" > "Add new panel"로 이동합니다.
        2. 원하는 메트릭을 선택하고 그래프를 설정합니다.