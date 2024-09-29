Lab4_shell commands notes
202331858 안솔비

LINUX
1. 오픈 소스 유닉스와 유사한 OS (1991년 출시)
2. 임베디드 시스템 및 모바일 시스템(안드로이드)에서도 실행 가능
3. 오픈 소스 소프트웨어 개발에 가장 널리 사용되는 플랫폼

Kernel : 하드웨어 리소스를 제어하고 통신하는 OS의 핵심
Shell : 사용자가 커널과 통신할 수 있는 인터페이스

CLC(키보드)
1. 텍스트 기반 명령
2. GUI보다 속도가 빠르다
3. 스크립트를 통해 자동화 및 기록 지원
4. 개발자를 위한 기본 환경
5. 명령어를 기억해야 한다

GUI(키보드+마우스)
대부분 마우스 입력(+일부 키보드 입력)
1. 반복 작업에 필요한 수작업
2. 더 쉽고 직관적인 서비스
3. CLI보다 느림
4. 반복 작업에 필요한 수작업
5. 일일 사용자

**SHELL COMMANDS**
1. pwd : 현재 작업중인 디렉토리의 경로 알림
2. cd(change directory) : 현재 작업중인 디렉토리를 변경 (원하는 디렉토리로 이동 가능)
*cd/ : 루트 디렉토
*cd. : 현재 디렉토리
*cd.. : 상위 디렉토리
*cd~ : 홈 디렉토리
*cd/[directory name] : 절대 경로
*cd./[directory name] : 상대 경로
*cd../[directory name] : 상위 디렉토리에 대한 상대 경로
3. ls(list files and directories) : 현재 작업 중인 디렉토리의 파일 표시
*lsl : 자세한 정보를 긴 형식으로 표시
*lslh : 위와 동일 하지만, 단위 크기
*lsla : 모든 파일 표시
4. clear : 터미널 화면 초기화
5. cp : 파일과 디렉토리를 복사
*cp file1 file2 : file1을 file2로 덮어씌우기, file2 없으면 생성
*cp file1 dir1 : file1을 같은 이름으로 다른 dir1 디렉토리에 복사
*cp -r dir1 dir2 : 디렉토리 dir1을 dir2로 덮어씌우기, dir2 없으면 생성
6. mv : 파일과 디렉토리를 이동하거나 이름  변경
*mv file1 file2 : file1을 file2로 이름 변경, file2 있으면 file1의 내용으로 대체
*mv file1 dir1 : file1을 다른 dir1 디렉토리로 이동
*mv dir1 dir2 : dir1을 dir2로 이름 변경, dir2 있으면 dir1의 내용으로 대체
7. rm : 파일과 디렉토리를 영구적으로 삭제
*rm file1 : file1을 삭제
*rm -r dir1 : 디렉토리 dir1을 삭제
8. mkdir : 새로운 디렉토리 생성
*mkdir dir1 : 디렉토리 dir1을 생성
9. Wildcards : 특정 파일 이름 선택
* : 모든파일
h* : 문자 "h"로 시작하는 모든 파일 이름
a*.txt : 문자 "a"로 시작하여 문자로 끝나는 모든 파일 이름 "*.txt”
Data?? : "Data"로 시작하여 다음과 같은 문자로 시작되는 모든 파일 이름 정확히 두글자 
10. hlep : 도움말, man : 메뉴얼
*help cd : cd명령어에 대한 도움말
11. exit : 터미널 종료
