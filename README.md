# 뚜벅여지도


## How to Contribute
### Fork

#### 1. 기여하려는 저장소 Fork 하기

![K-032](https://user-images.githubusercontent.com/54658745/173409182-42cc5448-22cc-4a3a-8a35-7cf107174016.png)
![K-033](https://user-images.githubusercontent.com/54658745/173409193-4aafd430-2b2a-4227-8d1a-aed9758a6885.png)
![K-034](https://user-images.githubusercontent.com/54658745/173409196-f0204266-7444-4418-8f38-63502419e36b.png)


- 기여하고자 하는 저장소를 나의 저장소로 fork 하기
- 나의 Repositories 에서 자신의 저장소로 이동하기
- 내 컴퓨터에 저장소를 clone 하기


#### 2. 원격 저장소 Remote 설정하기
```
$ git clone https://github.com/자기github아이디/CatchCatch.git
$ cd 내려받은 폴더
$ git init
$ git remote add upstream https://github.com/Succe22/CatchCatch.git
```


#### 3. PR용 branch 생성하기
1. Fetch the latest code from the main branch

```
$ git fetch upstream
```

2. Create a new branch or Using an existing branch
```
$ git checkout -b 자신의 브랜치 이름
```

or 

```
$ git checkout 기존 자신의 브랜치 이름
```

3. 코드 변경 진행
```
$ git add .
$ git commit -s -m "커밋 메시지"
```

4. Pull the latest code
```
$ git pull upstream
```

5. Pull the latest code
```
$ git push -u origin 현재 자신이 작업한 브랜치 이름
```


#### 4. fork한 github 사이트에 들어가서 PR 올리기
<img width="746" alt="스크린샷 2022-05-15 오후 5 18 58" src="https://user-images.githubusercontent.com/54658745/168463834-03a9dd15-ea86-4f99-b6f5-931bb260d62d.png">  

![K-028](https://user-images.githubusercontent.com/54658745/173409655-dc6c9b5a-c088-4430-b243-ebd9bc2cd4d1.png)

![K-030](https://user-images.githubusercontent.com/54658745/173409723-3b0af1a2-a2ed-45a8-8bd4-ccad78a19a15.png)



  
  
  
### 5. Label
- feat: 새로운 기능
- fix : 버그 수정
- docs : 문서만 변경
- style : 코드의 의미에 영향을 주지 않는 변경사항 (공백 , 서식 , 세미콜론 누락 등)
- refactor : 버그를 수정하거나 기능을 추가하지 않는 코드 변경
- test : 누락된 테스트 추가 또는 기존 테스트 수정
- chore : 문서 생성과 같은 빌드 프로세스 또는 보조 두구 및 라이브러리 변경
- rename : 파일 및 폴더 수정 및 디렉토리 작업 이동
