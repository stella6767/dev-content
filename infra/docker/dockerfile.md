

## RUN vs CMD vs ENTRYPOINT in Dockerfile

https://blog.leocat.kr/notes/2017/01/08/docker-run-vs-cmd-vs-entrypoint

- RUN. 새로운 레이어에서 명령어를 실행하고, 새로운 이미지를 생성한다. 보통 패키지 설치 등에 사용된다. e.g. apt-get
- CMD. default 명령이나 파라미터를 설정한다. docker run 실행 시 실행할 커맨드를 주지 않으면 이 default 명령이 실행된다. 그리고 ENTRYPOINT의 파라미터를 설정할 수도 있다. CMD의 주용도는 컨테이너를 실행할 때 사용할 default를 설정하는 것이다.
- ENTRYPOINT. 컨테이너를 실행할 수 있게 설정한다.