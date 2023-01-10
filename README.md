# Terminal

## -  Tomcat 확인/죽이기
1. 확인 
```terminal
lsof -i tcp:8080
```
2. 죽이기 
```terminal
kill $(lsof -t -i:8080)
```
