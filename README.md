# SecurePi_File-system-Integrity

1. root계정 로그인
2. 디렉토리 생성 및 이동
	- mkdir /root/securepi (이미 존재한다면 생략)
	- cd /root/securepi
3. Filesystem Integrity 파일 다운
	- git clone https://github.com/khu-mesl-348/SecurePi_File-system-Integrity.git
4. EVM Key 설정
	4.1 첫 실행 시
		- cd /root/securepi/SecurePi_File-system-Integrity
		- sh ./keygen.sh
		- sh ./keyrege.sh
	4.2 첫 실행 이후부터
		- cd /root/securepi/SecurePi_File-system-Integrity
		- sh ./keyrege.sh
