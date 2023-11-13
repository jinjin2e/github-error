# github-error
> ##  LF will be replaced by CRLF the next time Git touches it  
> 유닉스 시스템의 줄 끝은 LF(Line Feed)로 이루어진다. 하지만 윈도우에서는 LF와 CR(Carrige Return) 그러니까 CRLF로 이루어져 깃에서 무엇을 사용할 지 하나를 선택해줘야한다.  
> 해결 - 윈도우 -> git config --global core.autocrlf true  
>      - 리눅스, 맥 -> git config --global core.autocrlf true input  
     
