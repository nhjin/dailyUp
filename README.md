# dailyUp

| **프로젝트 개발환경⚙** |  |
| --- | --- |
| 개발언어  | Java(JDK1.8) |
| DB & Server | Oracle 11g Express Edition |
| 개발 Tools | Eclipse (eGovFrameDev-3.9.0-64bit) |
| OS | Windows 10 |

어떤 프로젝트든 관리자 페이지를 꼭 만들어야 합니다.

제가 배웠던 곳의 강사님은 관리자 페이지의 중요성을 자주 말씀하셨어요.

새로 배웠던 곳에서 한 마지막 프로젝트에서 시간 관계상 관리자 페이지를 만들지 못해서 

혼자 영화관 예매 사이트를 만들어보기 전에 관리자 페이지를 먼저 만들어보고 넘어가려고 해요. 

어차피 영화관에서도 관리자 페이지를 만드는 건 필수니까요! 🤣 

그러면 한 번 시작해보겠습니다.

## **START💥**

이전 프로젝트에 이어서 작업합니다. 제가 지난 번에 환경 설정한 프로젝트에 만들어도 됩니다. home.jsp 파일을 수정해서 하면 됩니다. 구성 방식을 먼저 보여드리겠습니다.

[##_Image|kage@brlCkt/btrqTZOB1UH/QnzDJsVBqlkQAwnb6ZdWtK/img.png|CDM|1.3|{"originWidth":387,"originHeight":59,"style":"alignCenter"}_##]

로컬호스트로 접속합니다. 

[##_Image|kage@mhV4Y/btrqMvuY1Sc/np8Kj0kCSW78ZwZmFBipTk/img.png|CDM|1.3|{"originWidth":535,"originHeight":57,"style":"alignCenter"}_##]

관리자 아이디를 미리 생성해두었습니다. 관리자 아이디로 로그인을 하면 보이는 ADMIN PAGE를 만들었습니다. 

여기까지 진행된 상태였고 ADMIN PAGE는 눌러도 깡통이었습니다. 일단 jsp에서 세션을 통해 작업해둔 상태입니다.

먼저 간단하게 가입된 회원수와 회원들의 정보를 목록으로 불러오겠습니다. 

1\. DB 테이블을 생성합니다. DB테이블 생성이 귀찮거나 어렵다면 오라클 DB에 미리 제공되어 있는 EMPLOYEE 테이블을 활용하셔도 됩니다.
