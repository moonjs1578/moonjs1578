# 리눅스 명령어
### top : top 명령어는 시스템의 프로세스/메모리 사용 상태를 5초의 간격으로 업데이트하여 출력한다. 화면에 출력되는 기본값은 현재시간, 시스템 업데이트 시간, 시스템에 로그인한 사용자 수, 지난 1분, 지난 5분, 지난 15분간의 시스템 평균 부하를 출력한다.<br>아래는 top명령어를 실행한 예시이다.
![top예시](https://dbscthumb-phinf.pstatic.net/4938_000_1/20170705212456131_V9D3Q4JJL.jpg/ka38_331_i1.jpg?type=w575_fst_n&wm=Y)
### ps : ps 명령어는 프로세스의 현재 상태를 출력한다. ps로 현재 사용하는 프로세스의 상태를 살펴보자.<br> 아래는 PID, TTY, TIME, CMD 헤더의 필드와 내용을 출력한다.
![ps예시](https://dbscthumb-phinf.pstatic.net/4938_000_1/20170705210350328_XVD2UXMLY.jpg/ka38_241_i1.jpg?type=w575_fst_n&wm=Y)
### jobs : job 명렬어는 obs는 작업이 중지된 상태, 백그라운드로 진행 중인 작업 상태, 변경되었지만 보고되지 않은 상태 등을 표시한다.<br>현재 환경의 작업 상태를 아래와 같이 확인할 수 있다.
![job예시](https://dbscthumb-phinf.pstatic.net/4938_000_1/20170710154910976_RX87MMBQ3.jpg/ka38_149_i2.jpg?type=w575_fst_n&wm=Y)
### kill :kill 명령어는 프로세스에 종료 시그널을 보낸다. 시스템에 얘기치 않은 문제가 생긴 프로세스를 종료시킬 수 있다. 만일 kill 명령으로 종료되지 않는 프로세스는 -9 옵션을 사용해서 강제로 종료하면 된다.<br>아래와 같이 ps 명령어로 sshd 프로세스를 확인할 수 있다.
![kill에시](https://dbscthumb-phinf.pstatic.net/4938_000_1/20170705204102763_BIV3YDDFB.jpg/ka38_154_i2.jpg?type=w575_fst_n&wm=Y)
