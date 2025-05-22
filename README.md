구동 테스트 안된 ver

SYNflood 공격코드 PRANG 활용(OpenSSL - RAND_bytes())

동작 방식
attack syn <타겟IP> <타겟PORT> <bot_count>
(ex: attack syn 192.168.0.10 80 2)

봇은 해당 타겟으로 stop 명령 받을 때까지 SYN Flood를 지속합니다.
stop <bot_count>로 종료

sudo 해결 안됨. 공격 실행시 서버측에서 PASSWD입력해줘야함
