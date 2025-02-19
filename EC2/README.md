\# EC2 인스턴스 생성하기

1\. Aws 콘솔로 접속하여 EC2 인스턴스 2개를 만들어줍니다.

\# DataDog 설치 및 모니터링 작업

1\. DataDog 사이트로 접속합니다.

[https://app.datadoghq.com](https://app.datadoghq.com)

2\. 로그인을 합니다. 로그인 후 에는 아래처럼 OS 가 뜨는데 선택한 OS에 따라 설치 명령어를 제공해줍니다.

저는 AmazonLinux로 선택하였습니다.

3\. 설치 명령어를 복사하고 아까 만들어둔 Ec2 인스턴스에 접속해서 설치를 진행합니다.

설치가 완료되면 아래와 같이 뜨게 됩니다.

[https://us5.datadoghq.com/signup/agent?platform=overview](https://us5.datadoghq.com/signup/agent?platform=overview)
![image](https://github.com/user-attachments/assets/a31f0abe-421b-497f-b13d-7a9a62855585)
![image](https://github.com/user-attachments/assets/79fe6c0a-7cc9-4b76-bdb4-9dcfc41566c6)

4\. 설치를 완료하고 DataDog 콘솔에서 아래로 내려가보면 아래처럼 메시지가 뜨는데 **Finish** 를 눌러줍니다.
![image](https://github.com/user-attachments/assets/ce0a1914-bfdb-475d-9fec-0b663daa6c18)

5\. Dashboard로 이동하여 New Dashboard를 눌러 대시보드를 만들어주겠습니다.

![image](https://github.com/user-attachments/assets/91280940-242b-4357-9d2e-24d373f436b2)
![image](https://github.com/user-attachments/assets/016c796e-c785-428e-a5cc-9b9e940c7fe5)


6\. 적절한 위젯을 선택한 뒤에 특정 EC2를 지정해보겠습니다.

from 옆에 select를 보면 2개의 선택지가 있는데 각각 EC2 인스턴스 프라이빗 ipv4 주소를 나타냅니다.

![image](https://github.com/user-attachments/assets/9646f2ed-ab51-4290-80cb-2571b577f789)


7\. 이렇게 각각의 EC2 인스턴스의 CPU 사용량을 대시보드로 볼 수 있게 되었습니다.

![image](https://github.com/user-attachments/assets/dddd08f1-b8ae-41a8-af51-82d61b63a8e3)
