## EC2 인스턴스 생성하기

1\. Aws 콘솔로 접속하여 EC2 인스턴스 2개를 만들어줍니다.

<br>

## DataDog 설치 및 모니터링 작업

1\. DataDog 사이트로 접속합니다.
### [https://app.datadoghq.com](https://app.datadoghq.com)

<br>

2\. 로그인을 합니다. 로그인 후 에는 아래처럼 OS 가 뜨는데 선택한 OS에 따라 설치 명령어를 제공해줍니다.
저는 AmazonLinux로 선택하였습니다.

<br>

3\. 설치 명령어를 복사하고 아까 만들어둔 Ec2 인스턴스에 접속해서 설치를 진행합니다.
설치가 완료되면 아래와 같이 뜨게 됩니다.

### [https://us5.datadoghq.com/signup/agent?platform=overview](https://us5.datadoghq.com/signup/agent?platform=overview)

<br>

![image](https://github.com/user-attachments/assets/eacf6dee-ebd5-4cde-bb00-37f7de8f4eb2)
![image](https://github.com/user-attachments/assets/e000817c-2220-430a-8f26-bc1c2c32dcc0)

<br>

4\. 설치를 완료하고 DataDog 콘솔에서 아래로 내려가보면 아래처럼 메시지가 뜨는데 **Finish** 를 눌러줍니다.
![image](https://github.com/user-attachments/assets/67db7de9-1ccd-40ef-983d-04b2818e1ea4)

<br>

5\. Dashboard로 이동하여 New Dashboard를 눌러 대시보드를 만들어주겠습니다.
![image](https://github.com/user-attachments/assets/36fbf35e-3c9b-4218-99d1-789ec558cc3e)
![image](https://github.com/user-attachments/assets/c2668403-5d16-41d0-818e-051eeab7a1fd)

<br>

6\. 적절한 위젯을 선택한 뒤에 특정 EC2를 지정해보겠습니다. from 옆에 select를 보면 2개의 선택지가 있는데 각각 

EC2 인스턴스 프라이빗 ipv4 주소를 나타냅니다.
![image](https://github.com/user-attachments/assets/942ef558-5725-41bb-9d27-f66012ccaaa2)


<br>

7\. 이렇게 각각의 EC2 인스턴스의 CPU 사용량을 대시보드로 볼 수 있게 되었습니다.
![image](https://github.com/user-attachments/assets/cbf5560c-9826-43f1-845e-a3a0684d5bb3)
