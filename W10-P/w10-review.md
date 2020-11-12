<h2>#새로 배운 내용</h2>
    Oracle의 버전이 19C까지 나왔는데, 우리가 사용한 것은 11g의 익스프레스 에디션을 사용했다.<br/><br/>
    오라클 설치를 확인하기 위해 Run SQL CommandLine을 실행하고 CONNECT SYSTEM 명령어로 시스템과 연결한 뒤 SHOW USER을 입력하니 SYSTEM 유저가 잘 나왔다.<br/><br/>
    호스트 컴퓨터가 아닌 외부에서도 접속할 수 있도록 설정을 변경하는 법을 배웠다. CONNECT SYSTEM을 한 뒤 EXEC DBMS_XDB.SETLISTENERLOCALACCESS(FALSE);를 입력하는 것이다.<br/><br/>
    그리고 심플 데이터를 사용 하기 위해 ALTER USER HR ACCOUNT UNLOCK IDENTIFIED BY 비번;<br/>
    명령어를 sqldeveloper에서 사용해서 hr을 잠금을 해제했고, 그다음 local-hr을 만들어서 HR계정 접속 환경을 조성했다.<br/><br/>
    이클립스의 실행 단축키는 ctrl + F11이다.<br/><br/>
    JDBC는 각자 다른 SQL을 가진 여러 DB의 sql문을 알아서 통일시켜서 자바 애플리케이션에서 다룰 수 있도록 도와준다. <br/>
    사용법은, 오라클 폴더 하위경로에 있다. 이것을 복사해서 java폴더 내에 두고, 이클립스에서 추가하면 사용할 수 있다.<br/><br/>
    이클립스에서 자바로 오라클을 접속할 때, try catch문을 사용한다.<br/><br/>


<h2>#문제가 발생하거나 고민한 내용 + 해결과정</h2>
    이미 안드로이드 수업에서 한창 사용 중인 자바 1.14버전이 있기때문에 1.8을 설치하는 과정에서 문제가 생길까봐 수업 화면을 중간에 멈추고, 여러가지 자바 버전을 함께 사용할 때 어떻게 하는지 조금 검색해보았다. 툴을 사용해서 하는 경우도 있었는데, 일단 좀 더 강의를 보자싶어서 다시 틀어보니, 교수님도 1.14버전이 이미 깔려있는 상태에서 그걸 바꿔가며 진행하셨기 때문에 전혀 문제가 없어서 다행이었다.

<h2>#참고할만한 내용</h2>
     특별히 없다.
<h2>#회고 (+-!)</h2>
+: 주로 설치만 했기 때문에 특별한 기억은 없다.<br/><br/>

-: 학교에서 java수업을 들은 적은 없고 예전에 학원다니면서 한달 반 동안 속성 벼락치기를 한 적이 있어서  이번 학기 내내 그것으로 버티고 있어서 크게 자신은 없다. 그래도 계속 쳐다보면 이해는 가니 기말 팀과제가 끝날 때 까지 자바를 이용한 실습을 잘 해나갈 수  있었으면 좋겠다.<br/><br/>

!:  
    이클립스의 버전이 너무 최신이면 자바 이전버전을 잘 사용할 수 없었다. 혼자 독학하다가 이런 문제가 생기면<br/> 두 프로그램 중에서 최신 프로그램을 지우고 이전버전을 깔면 좀 더 쉽게 해결된다는 사실을 알게되었다.<br/>
    호스트 컴퓨터가 아닌 외부에서도 접속할 수 있도록 설정을 변경하는 법을 배웠다.<br/> 윈도우에 깔았는데 어떻게 다루게 될까?<br/> 윈도우에서 방화벽의 어떤 포트를 내리고 telnet같은 무언가를 깔아서 할까?<br/> 전에 컴퓨터시스템관리에서 했던 실습이 떠오른다. 앞으로의 수업이 궁금하다.<br/><br/>
    이클립스의 실행 단축키는 ctrl + F11이고 안드로이드는 ctrl + F10이다. 헷갈리지 않도록 주의해야겠다.<br/><br/>
    이클립스에서 자바로 오라클에 접속할 때, try catch문을 사용한다.<br/> try catch문은 오류를 잡아내기 위해 쓴다고 기억하는데 오라클에 접속하려고 사용되기도 해서 놀라웠다.<br/>
