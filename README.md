<h1>20243073 신희성 오픈소스SW개론</h1>

*<h2>명령어 top</h2>*

<h3>CPU 사용량을 체크해주는 도구</h3><br>

<p>-b : 배치모드로 정보를 출력한다. 실시간 상화 대화형모드로 정보를 화면에 일렬로 출력한다.</p>
<p>-d delay : 지정한 시간(delay 초)의 간격으로 정보를 업데이트하여 출력한다.</p>
<p>-i idle : 토글값이 off일 때, idle 프로세스나 좀비 프로세스 정보를 출력하지 않는다.</p>
<p>-n num : 지정한 시간(num)만큼 업데이트 정보를 출력한다.</p>
<p>-p pid : 지정한 프로세스 ID(pid)의 정보만을 출력한다.</p>
<p>-q : 시간의 간격 없이 계속하여 업데이트 정보를 출력한다.</p>
<p>-s : 몇 개의 대화식 명령을 비활성화한다(시큐어 모드).</p>
<p>-S : 누적된 정보를 출력한다(cumulative 모드).</p>


*<h2>명령어 ps</h2>*

<h3>프로세스 상태 등을 확인</h3><br>

<p>-A : 모든 프로세스를 출력한다.</p>
<p>-N : -A 옵션과 비슷하나 ps 프로세스를 제외하고 출력한다.</p>
<p>-a : 세션 리더 및 터미널에 속하지 않는 프로세스를 제외하고 출력한다.</p>
<p>-d : 세션 리더를 제외한 모든 프로세스를 출력한다.</p>
<p>-e : 커널 프로세스를 제외한 모든 프로세스를 출력한다.</p>

<p>T : 현재 터미널에서의 모든 프로세스를 출력한다.</p>
<p>a : 현재 터미널의 사용자 고유 프로세스를 출력한다.</p>
<p>r : 현재 실행 중인 프로세스를 출력한다.</p>
<p>x : 터미널이 없는 프로세스를 출력한다.</p>
<p>--deselect : -N 옵션과 같다.</p>


*<h2>명령어 jobs</h2>*

<h3>작업이 중지된 상태, 백그라운드로 진행 중인 작업 상태, 변경되었지만 보고되지 않은 상태 등을 표시</h3><br>

<img src=https://github.com/woefuler/woefuler/assets/166924557/cd1033bb-b732-473e-8389-79763aa1658e alt="1"></img>

<p>-l : 프로세스 그룹 ID를 state 필드 앞에 출력한다.</p>
<p>-n : 프로세스 그룹 중에 대표 프로세스 ID를 출력한다.</p>
<p>-p : 각 프로세스 ID에 대해 한 행씩 출력한다.</p>
<p>command : 지정한 명령어를 실행한다.</p>


*<h2>명령어 kill</h2>*

<h3>프로세스에 종료 시그널을 전송</h3><br>

<p>pid ··· : 종료시킬 프로세스 ID나 프로세스 이름을 지정한다.</p>
<p>-s : 전달할 시그널의 종류를 지정한다. 여기에는 시그널 이름이나 번호를 써준다.</p>
<p>-l : 시그널로 사용할 수 있는 시그널 이름들을 보여준다.</p>
<img src=https://github.com/woefuler/woefuler/assets/166924557/df6249db-6e65-4249-8060-6d5baaeef6ee alt="1"></img>


<p>-1, : -HUP 프로세스를 재활성화한다.</p>
<p>-9 : 프로세스를 강제로 종료시킨다.</p>

<!---
woefuler/woefuler is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
