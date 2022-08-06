# GIT

## 파일 브랜치관리
- 같은 폴더내 브랜치별로 파일의 version다르게 관리가능
- gut branch [브랜치이름] : 브랜치생성
- git branch : 현재 branch 목록 보여줌
## ![image](https://user-images.githubusercontent.com/54635552/182181143-a3903b7b-04fc-4fef-9fbd-91418dffb25c.png)

- git checkout [브랜치이름] : 해당 브랜치로 전환
## ![image](https://user-images.githubusercontent.com/54635552/182181331-cd0d4676-0a05-48ef-9689-947889c4e05f.png)

- git checkout -b <branch> : 해당 브랜치생성한뒤 브랜치로 전환
## ![image](https://user-images.githubusercontent.com/54635552/182181420-38b0254f-5207-45f3-8c50-6b2698dff011.png)

- git merge : 브랜치 병합
- 병합할 대상 브랜치로 이동한뒤에 해당 브랜치에서 git merge [병합할 브랜치이름] 입력시 
## ![image](https://user-images.githubusercontent.com/54635552/182181826-3c4d188e-4fd8-498a-bb68-9da3d49088ad.png)
## ![image](https://user-images.githubusercontent.com/54635552/182181842-fe78a296-afa1-44de-a842-dd00427ef963.png)
## ![image](https://user-images.githubusercontent.com/54635552/182182159-3cddb221-f902-4343-a6ba-a0056d929f23.png)
 
- git branch -d [브랜치이름] : 해당 브랜치 삭제하기

- git pull : 원격 저장소의 데이터를 로컬 저장소에 가져와 병합하기
- git fetch : 원격 저장소의 내용만 확인하고, 로컬 데이터와 병합하고싶지않은경우에 사용
- git push : 로컬 저장소의 데이터를 원격 저장소로 넣을떄

## git 처음 시작
- git init : 깃 파일생성
- git add . : 현재 경로 파일 local repository 추가
- git commit -m "커밋 메세지" : add 한 파일 commit 하기
- git remote add origin [깃허브주소] : local repository와 remote github repository 연동
- git push origin master : master branch에 파일 업로드 하기


- git checkout -b [브랜치이름] : 해당 브랜치생성하고 branch 변경
- git add . -> git commit -m "test" -> git push origin [branch] : branch 이름으로 git push
- 이후 관리자가 해당 branch를 보고 pull request를 받을지 여부 판단 
- pull request 받을경우 master branch에 변경사항 적용
- merge : 파일 병합

- git pull origin [브랜치이름] : 해당 브랜치이름의 내용 가져오기

## 파일 불러오기
- git init
- git remote add origin [깃허브주소] : 원격 repository와 연결
- git fetch : 원격 repository 데이터 가져오기
- git checkout -t [원격 repository branch이름] : 해당 브랜치생성후 이동
- git pull : 해당 브랜치 데이터 가져오기
