### PCB(Process Control Block)란?
![[Pasted image 20251204202031.png]]
프로세스 관련 모든 정보를 담고 있는 운영체제의 핵심 자료구조.
**✔ PCB에 저장되는 정보**
- **프로세스 ID (PID)**
- **프로세스 상태** (Ready / Running / Blocked …)
- **Program Counter** (다음 수행 명령어 위치)
- **CPU 레지스터 정보**
- **메모리 구조 정보** (Code / Data / Heap / Stack)
- **열린 파일 / 리소스 핸들**
- **스케줄링 정보** (우선순위 등)

> PCB는 운영체제 커널 영역에 존재하며, 프로세스 문맥(context)을 관리하는 데 사용된다.