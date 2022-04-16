# Instagram HashCrawler
2019-2 소프트웨어융합개론 프로젝트

## 1.	사용자 입력
1)	ID & Password 입력
없이는 홈페이지에 접근 불가.
2)	검색하고자 하는 HashTag or 계정 입력
3)	원하는 정보 선택
a.	프로필 
프로필 페이지 상단에서 게시글 수, 팔로워 수, 팔로잉 수를 순서대로 확인가능
b.	게시글
그 아래에 게시글을 클릭함으로써 게시글별로 정보를 얻을 수 있음.
       정보선택을 분리함으로써 원하는 정보만을 선택해서 각각을 엑셀파일로 정리할 수 있게 하기 위함.

## 2.	Crawler 작동
1)	Open
2)	ID & Password 입력
3)	홈페이지 접근
검색창을 찾고 입력 받았던 Hashtag 또는 계정 입력
검색어와 일치하는 것이 주로 첫번째에 뜨므로 첫번째 클릭
(이후 오류수정과정에서 간혹 아닌 경우 발생 따라서 뜨는 입력창에서 일치하는 것을 클릭하는 과정 필요)
4)	Profile 페이지
a.	Profile 정보 찾기
b.	게시글 정보 찾기
5)	반복과정
원하는 정보의 유형에 따라 반복위치기 달라짐
a.	계정이 여러 개일 때
입력으로 검색어를 하나 받았기 때문에 이 경우 프로그램을 여러 번 돌려야 함.
(수정하려면 검색어를 하나인 경우와 여러 개인 경우를 나눠서 입력을 받아야함.)
b.	게시글이 여러 개일 때
게시글 하나 클릭 후 다음버튼을 통해서 여러 개의 게시글의 정보를 읽어올 수 있음.


## <해본 결과>
작년에 프로그램을 만들 때 중구난방으로 프로그래밍한 것보다 훨씬 더 정리가 잘 된다. 노트에 과정을 쓰면서 만들었었지만 체계화되지 않았고 생각의 흐름대로 끄적이다 보니 정돈이 잘 되지 않았었다. 그에 비해 알고리즘에 맞는 순서도의 모양을 쓰진 못했지만 이동, 페이지, 질문, 입력 등으로 상자를 구분해서 그리고 선을 연결하다 보니 어디에서 무슨 정보를 받아 어떻게 작동을 해야 하는 지가 잘 보였다. 그러면서 수정을 해야 하는 부분이 좀 더 명확해졌다.

 ![image](https://user-images.githubusercontent.com/51522587/163665396-53f98503-d7f9-4af2-99bc-4938ebe30d5a.png)

