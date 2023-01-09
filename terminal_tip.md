# 개발환경 : Spring/Tomcat 

# log 확인하는 방법
1. terminal 접속
2. ssh 계정@IP -p 포트 (ssh id@127.0.0.1 -p 2022) 입력
3. password 입력 
4. 이동 : cd /usr/local/share/apache-tomcat-8.0.22/logs/
5. 실시간 로그확인
  : tail -f catalina.out 또는 tail -f -c 20000 catalina.out
6. 날짜에 따른 로그확인 
  : cat catalina.out 2020-11-04.log
7. 당일 
  : vim catalina.out 
  * 최신 기록 shift gg 
  * 검색 / 
  * 검색 후 이동 : 아래(n) (위) shift + n 
  * 다음 페이지 이동 :  Ctrl + f 
  * 이전 페이지 이동 : Ctrl + b 
  * 문서 맨 앞으로 이동 : gg
  *  문서 맨끝으로 이동 : G

