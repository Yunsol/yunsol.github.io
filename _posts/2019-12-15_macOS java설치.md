터미널에서 작업
<h1>jdk macOS 설치</h1>
<h2>jdk6이하</h2>
<br>
$ brew tap homebrew/cask-versions<br>
$ brew cask install java6

<h2>jdk7이상</h2>
<br>
$ brew tap AdoptOpenJdk/openjdk<br>
$ brew cask install adoptopenjdk8
<br><br>
'/Library/Java/JavaVirtualMachines/' 하위에 생성


<h1>Tomcat설치</h1>
$ brew search tomcat<br>
==> Formulae<br>
tomcat ✔            tomcat-native       tomcat@7            tomcat@8<br>
<h3>최신버전 설치</h3><br>
$ brew install tomcat<br>
