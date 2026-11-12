<h1 align="center">공유 캔버스 서버</h1>

<p align="center">
  <b>작은 그리기 명령과 큰 화면 데이터가 섞일 때, 어떤 IPC가 언제 빠른가</b><br/>
  같은 응용을 pipe · message queue · shared memory로 구현해 측정으로 비교하는 팀 프로젝트
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/GNU%20Make-A42E2B?style=for-the-badge&logo=gnu&logoColor=white" alt="GNU Make"/>
</p>

<p align="center">
  <a href="https://github.com/unix-ipc-canvas/canvas">canvas</a> (팀 비공개 저장소)
</p>

---

UNIX 시스템 프로그래밍 2팀 · 2026년 2학기 설계과제

여러 클라이언트가 하나의 캔버스에 동시에 그리고, 캔버스의 일부나 전체를 받아 가는 서버입니다. 서버와 클라이언트의 로직은 한 벌로 두고 프로세스 사이의 전달 방법만 세 가지로 바꿔, 지연시간과 처리량을 같은 컴퓨터에서 측정합니다.

문서와 코드는 [canvas](https://github.com/unix-ipc-canvas/canvas) 저장소에서 관리합니다.
