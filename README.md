# github-error
 ##  LF will be replaced by CRLF the next time Git touches it  
> 유닉스 시스템의 줄 끝은 LF(Line Feed)로 이루어진다. 하지만 윈도우에서는 LF와 CR(Carrige Return) 그러니까 CRLF로 이루어져 깃에서 무엇을 사용할 지 하나를 선택해줘야해서 발생하는 오류.  
> 해결 - 윈도우 -> git config --global core.autocrlf true  
>      - 리눅스, 맥 -> git config --global core.autocrlf true input  
     
## failed to push some refs to '레퍼지토리 주소'  
> 이는 원격저장소(github)에 내 로컬(내컴퓨터)에는 없는 파일이 있을 때 내 파일을 push 할 면 발생하는 오류이다.
> 원격저장소에서 내 로컬에 저장하지 않은 파일을 pull한 후 원격저장소에 다시 push를 해야한다.
> 해결 - git pull origin master(또는 main) -> git push origin master(또는 main)

