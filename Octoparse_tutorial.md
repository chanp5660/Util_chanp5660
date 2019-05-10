# Octoparse 를 사용해서 크롤링

굉장히 간단한 예제로서 흐름만 잡아주는 정도의 도움이 될 것이다.
나머지는 프로그램화면에 뜨는 [Action Tips]부분에서 많은 도움을 얻었습니다.

## 설치 방법

### 1. 공식사이트에서 [다운로드](https://www.octoparse.com/download)
### 2. 알집 압출풀기 

![압축풀기](https://user-images.githubusercontent.com/46266247/57507069-a4196000-7338-11e9-8d59-e0c4b8390efc.png)

### 3. 바탕화면에 생기는 Octoparse 아이콘을 실행

![첫 실행화면](https://user-images.githubusercontent.com/46266247/57507345-74b72300-7339-11e9-9375-481e3840c1bb.png)

### 4. 우리가 실행해야 하는 모드는 Advanced Moded이다. 위에 그림에서 아래 빨간색 네모를 클릭[+task].

### 5. 그럼 화면에  Website의 URL을 입력할 수 있게 되어 있는데 http://www.itemmania.com/ 를 입력해본다. Save URL 클릭

![URL입력](https://user-images.githubusercontent.com/46266247/57510184-12622080-7341-11e9-92aa-02d1fccdf6d9.png)

### 6. 이제부터는 활용이다. 
- 1번 화면은 실제로 돌아가는 코드를 시각화로 보여준다.
- 2번 사용자가 하는 행동의 정보들을 알려준다.(여러가지라서 한가지로 정하기 힘들다.)
- 3번 실제 사용자가 클릭이나 행동을 화면을 통해서 할 수 있다.
> 3번 부분에서 Action Tips이 행동을 할때 어떤 것을 할 수 있는지 도움을 준다. 1번을 바로 하기에는 힘들다. 3번에서 클릭을 통해서 많이 해본 다음에 해보도록 하자.

![실행화면](https://user-images.githubusercontent.com/46266247/57510626-425df380-7342-11e9-98d2-e41adf2d782e.png)

### 7. 목적과 해야할 순서

- 목적 : 메이플스토리의 서버의 리스트를 얻고 싶다.

#### A. 아이템매니아 홈페이지를 들어간다. <- 위에 단계들을 했다면 이미 들어와 있다.

#### B. 게임명을 입력한다. [메이플스토리]

![게임명을 입력하세요](https://user-images.githubusercontent.com/46266247/57511680-c74a0c80-7344-11e9-8600-ec9580be0bd4.png)

![메이플스토리](https://user-images.githubusercontent.com/46266247/57511765-f82a4180-7344-11e9-9fa1-e4edc855ed9c.png)

![메이플클릭](https://user-images.githubusercontent.com/46266247/57511872-37f12900-7345-11e9-9269-302722b12421.png)

##### B 결과

![결과](https://user-images.githubusercontent.com/46266247/57512466-b0a4b500-7346-11e9-921c-13a874a36d34.JPG)

C. 서버명을 얻는다. 위에 단계에서 넘어오면 실제와는 다르게 서버전체가 자동으로 선택되면서 선택지가 사라진다.(직접 사이트에서 비교)

##### 실제 사이트

![캡처5](https://user-images.githubusercontent.com/46266247/57512846-c797d700-7347-11e9-8a1e-e3b7136c3b74.JPG)

##### Octoparse에서 해결방법

![서버1](https://user-images.githubusercontent.com/46266247/57512909-f150fe00-7347-11e9-9618-b650fee4b05d.png)

![서버2](https://user-images.githubusercontent.com/46266247/57513046-442ab580-7348-11e9-8b91-d318fd4a066f.png)

#### C 결과

![결과2](https://user-images.githubusercontent.com/46266247/57513100-645a7480-7348-11e9-8637-bc914855dc5d.JPG)

### 8. 데이터 추출

- 위 사진에서 10시 방향에 Save를 한번 눌러 저장하고 그 옆의 **Start extraction**을 클릭. 
- 무료 이용자이므로 **Local extracion**을 클릭.
- #------ 자동으로 크롤링을 해준다-------# 

# 음...안되는데... 다른 것은 되는데 아직 정리하지 못했다.
