
# 개발환경
+ node(22.19.0)
+ npm(10.9.3)
<br/><br/>
- - -
# 개발 환경구성
### node 및 npm 설치
+ https://nodejs.org/en 링크를 통해 설치
<pre><code>다음 명령어를 통해 nodejs 및 npm 설치 확인
> node -v
> npm -v</code></pre>

### react 설치
+ 설치 디렉토리로 이동후 npm create-react-app [프로젝트명] 로 프로젝트 생성
<pre><code>> npm create-react-app react-project</code></pre>
+ 명령어 실행시 UnauthorizedAccess 오류 발생하면 윈도우 기준 PowerShell > run as Administator(관리자로 실행)에서 아래 명령어 실행
<pre><code>> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned</code></pre>
+ 프로젝트 생성후 생성 프로젝트 폴더에 들어가서 테스트로 react 서버 실행
<pre><code>> npm start
http://localhost:3000 에서 확인</code></pre>
- - -

# 리액트 문법
### 컴포넌트 사용
<pre><code>import React from "react";

function Header() {
  return &lt;h1&gt;Heager 입니다.&lt;/h1&gt;
}

export default Header;
</code></pre>

### style

### 이벤트

### useState

### useEffect

### props

### 반복


