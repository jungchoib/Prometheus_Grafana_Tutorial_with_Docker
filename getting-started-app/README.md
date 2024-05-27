# Getting started

This repository is a sample application for users following the getting started guide at https://docs.docker.com/get-started/.

The application is based on the application from the getting started tutorial at https://github.com/docker/getting-started

<!-- docker build -t getting-started .로 build
이 docker build명령은 Dockerfile을 사용하여 새 이미지를 빌드합니다. Docker가 많은 "레이어"를 다운로드했다는 사실을 눈치채셨을 것입니다. 이는 빌더에게 이미지에서 시작하고 싶다고 지시했기 때문입니다 node:18-alpine. 그러나 컴퓨터에 해당 이미지가 없었기 때문에 Docker는 이미지를 다운로드해야 했습니다.

Docker가 이미지를 다운로드한 후 Dockerfile의 지침이 애플리케이션에 복사되어 yarn애플리케이션의 종속성을 설치하는 데 사용됩니다. 지시문은 CMD이 이미지에서 컨테이너를 시작할 때 실행할 기본 명령을 지정합니다.

마지막으로 -t플래그는 이미지에 태그를 지정합니다. 사람이 읽을 수 있는 최종 이미지 이름이라고 생각하세요. image라는 이름을 지정했기 때문에 getting-started컨테이너 실행 시 해당 이미지를 참조할 수 있습니다.

.명령 끝에 있는 는 Docker에게 현재 디렉터리에서 docker build를 찾아야 함을 알려줍니다 .Dockerfile
즉 이미지가 생성되었다. -->