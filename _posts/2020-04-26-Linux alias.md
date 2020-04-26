## alias

> alias 리스트 확인

    $ alias

> alias 등록

    $ alias greptomcat='ps -ef|grep tomcat'

> alias 해제

    $ unalias greptomcat

> alias 영구등록

홈 디렉토리의 .bashrc파일 마지막에 추가

    $ vi ~/.bashrc
    
    ~~파일 수정~~
    alias greptomcat='ps -ef|grep tomcat'
    ~~파일 저장~~
    $ source ~/.bashrc