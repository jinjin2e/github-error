# github-error
 ##  LF will be replaced by CRLF the next time Git touches it  
> 유닉스 시스템의 줄 끝은 LF(Line Feed)로 이루어짐. 하지만 윈도우에서는 LF와 CR(Carrige Return) 그러니까 CRLF로 이루어져 깃에서 무엇을 사용할 지 하나를 선택해줘야해서 발생하는 오류.  
> 해결 - 윈도우 -> git config --global core.autocrlf true  
>      - 리눅스, 맥 -> git config --global core.autocrlf true input  
     
## failed to push some refs to '레퍼지토리 주소'  
> 이는 원격저장소(github)에 내 로컬(내컴퓨터)에는 없는 파일이 있을 때 내 파일을 push 할 면 발생하는 오류임.
> 원격저장소에서 내 로컬에 저장하지 않은 파일을 pull한 후 원격저장소에 다시 push.  
> 해결 - git pull origin master(또는 main) -> git push origin master(또는 main)  

## Everything up-to-date
> push했지만 원격저장소에 올라가지 않고 Everything up-to-date 문구만 출력됨  
> 여러 블로그 들을 찾아봤지만 본인과 문제 발생 원인이 다름 -> 해결 안됨  
> 해결 - git commit -m "commit massage"  본래 협업을 할 때 커밋 메세지를 작성해서 가독성을 높이고 협업을 보다 쉽게해주는 코드임. 하지만 이 과정을 거치지 않고 push를 했을 때 Everything up-to-date 문구가 출력되는 것을 확인함.  
