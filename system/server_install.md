1. Ethernet 설정
> sudo ifconfig <eth name> up|down

2. vi /etc/network/interfaces 설정

3. openssl-server & openssh
> apt install openssh-server
> apt install openssh-client

4. vi /etc/ssh/sshd_config 수정
> $ sudo systemctl restart sshd

- Slip 모드 수정
- /etc/hosts 파일

      $ sftp <IP ADDRESS>
      $ cd /etc
      $ get power-management
      $ get rc.local // 리부팅 시 마다 네트워크 새로 가져옴
      $ get hosts


