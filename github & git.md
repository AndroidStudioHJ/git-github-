---


---

<h1 id="git-시작하는-방법">git 시작하는 방법</h1>
<p>git init: git 을 시작한다<br>
git add .: 모든 변경 사항을 추가<br>
git commit -m ‘커밋 메세지’: 커밋 메세지 필수</p>
<h2 id="git-로그-확인하는-2가지-방법">git 로그 확인하는 2가지 방법</h2>
<p>git log: 커밋 히스토리 확인<br>
git log --oneline: 커밋 히스토리를 한 줄에 필요한 것만 표시</p>
<h2 id="브랜치를-만드는-3가지-방법">브랜치를 만드는 3가지 방법</h2>
<p>git branch &lt;브랜치 이름&gt;: 만들기만 한다<br>
git switch -c &lt;브랜치 이름&gt;: 만들면서 그 브랜치로 이동<br>
<s>git checkout -b &lt;브랜치 이름&gt;</s></p>
<h2 id="브렌치-이동">브렌치 이동</h2>
<p>git switch &lt;브랜치 이름&gt;: 브랜치 이동<br>
git branch -d &lt;브랜치 이름&gt;: 브랜치 지우기</p>
<pre><code>새로운 브랜치에서 작업한다.
master 에 합친다. : merge 명령을 내리는 브랜치가 기준
git merge &lt;브랜치 이름&gt;
</code></pre>
<h2 id="github">github</h2>
<ol>
<li>git 하고 다른 회사다</li>
<li>SEttings 가 여러 개다</li>
<li>한개라도 파일이 있으면 뜨는 화면, 하나도 없을때</li>
<li>remote 레포지토리(= 원격 저장소) 만들고, 삭제하기</li>
<li>브랜치가 msater 가 아니라 main 이다.</li>
<li>브랜치 만들기</li>
</ol>
<hr>
<ol>
<li>원격저장소 test 를 만든다</li>
<li>브랜치 branch1 를 만든다</li>
<li><a href="http://README.md">README.md</a> 파일을 수정한다.</li>
<li>main 에 merge 한다.</li>
<li>브랜치 branch1 를 삭제한다.</li>
</ol>
<h2 id="인증">인증</h2>
<ol>
<li>ssh-keygen -t ed25519 -C ‘your_email@example.com’ 로 키쌍을 만든다.</li>
<li><a href="http://github.com">github.com</a> 에 가서 ed25519.pub 파일 안의 key 값을 등록</li>
<li>git remote set-url origin <a href="mailto:git@github.com">git@github.com</a>:AndroidStudioHJ/my_rep.git 실행</li>
</ol>
<h2 id="windows-git">windows git</h2>
<ol>
<li>명령창 CLI 모드</li>
<li>vscode</li>
<li>sourcetree, github Desktop</li>
</ol>

