#Lab 6 202331858 안솔비

__Version Control and Collaboration__

*소프트웨어 개발 뿐만 아니라 다큐멘테이션 작업에서도 필수적 이다.

*시간이 지남에 따라 버전을 기록하는 방식 사용

방법 1) 기본 파일에서 변화된 부분만 기록

방법 2) 각각의 버전마다 스냅샷으로 저장

Local > 여러 버전에 대한 기록이 컴퓨터에만 저장 (혼자 사용하기 위한 방법)

Centralized > 중앙서버에서 버전에 대한 데이터 베이스를 저장 (중앙서버가 다운이 되면 다운로드나 없로드 불가능 하다는 단점이 있다)

Distributed > 중앙서버와 각각의 유저의 컴퓨터에도 버전에 대한 데이터 베이스를 저장 (중앙서버에 문제가 생겨도 쉽게 복구 가능)


__Three States in Git__

1. Modified : 변경되었지만 다음 커밋을 위해 아직 준비되지 않은 파일입니다. 이러한 변경 사항은 워킹 디렉토리에 있습니다.

2. Staged : 다음 커밋으로 이동하도록 표시된 파일입니다. 이 파일은 스테이징에 저장됩니다

3. committed : Git 디렉토리에 저장된 파일이다. 파일은 Git 디렉토리의 프로젝트 기록의 부분다.


__Installing Git__

Git은 각 OS에 대한 특정 지침에 따라 Linux, Windows 및 Mac에 설치할 수 있다

Git config : First-time setup

1. System level : --system option. 시스템의 모든 사용 및 저장소에 영향을 미칩니다 (관리상의)

2. Global (user) level : --global option. 현재 사용자의 모든 저장소에 영향을 미칩니다

3. local level : --local option. 현재 저장소에만 적용됨

*각 레벨은 이전 레벨의 값을 재정의합니다 : system -> global -> local


__Git Commands__

- git init: 프로젝트 디렉토리에서 새 Git 저장소를 초기화합니다.

- git status: 작업 디렉토리 및 스테이징 영역의 상태를 표시합니다. 수정, 스테이징 또는 커밋되었습니다.

- git add [filename]: 지정한 파일을 준비하여 커밋합니다.

- git commit -m "message": 변경 사항을 설명하는 메시지로 단계적 변경을 커밋합니다

- `git add .`: 추적할 모든 파일을 준비합니다.

- `git rm --cached [file_name]`: 파일 준비 해제

* tip : 만약 윈도우에 있는 나노에 문제가 있다면 모든 다른 문서 편집기를 사용하여 편집할 수 있다. (e.g., 메모장)
