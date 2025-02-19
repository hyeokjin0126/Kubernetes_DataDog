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

[##_Image|kage@bw9xzg/btsMmIT7OoG/KoDQVYFDPCkBONrEJv9011/img.png|CDM|1.3|{"originWidth":736,"originHeight":381,"style":"widthContent"}_##][##_Image|kage@bsNNIf/btsMm4CApJ6/okaKW7k5ywskfeeHuV6w11/img.png|CDM|1.3|{"originWidth":911,"originHeight":236,"style":"widthContent"}_##]

4\. 설치를 완료하고 DataDog 콘솔에서 아래로 내려가보면 아래처럼 메시지가 뜨는데 **Finish** 를 눌러줍니다.

[##_Image|kage@xhjvJ/btsMnSBq9ED/WfKKtVZ4AWRmaDAtZn1WCK/img.png|CDM|1.3|{"originWidth":583,"originHeight":73,"style":"alignCenter"}_##]

5\. Dashboard로 이동하여 New Dashboard를 눌러 대시보드를 만들어주겠습니다.

[##_Image|kage@m49FW/btsMnnaYYrX/d7hkZAGEBQzOWn1FmPnLZ0/img.png|CDM|1.3|{"originWidth":2510,"originHeight":521,"style":"widthContent"}_##][##_Image|kage@erVpzD/btsMmLccOPj/OZPuy4vGiiXiq41IjaifXK/img.png|CDM|1.3|{"originWidth":808,"originHeight":483,"style":"widthContent"}_##]

6\. 적절한 위젯을 선택한 뒤에 특정 EC2를 지정해보겠습니다.

from 옆에 select를 보면 2개의 선택지가 있는데 각각 EC2 인스턴스 프라이빗 ipv4 주소를 나타냅니다.

[##_Image|kage@daZ9Z6/btsMoz860zv/lCfxoVD4rGLn9KF98gKwQ1/img.png|CDM|1.3|{"originWidth":1238,"originHeight":377,"style":"widthContent"}_##]

7\. 이렇게 각각의 EC2 인스턴스의 CPU 사용량을 대시보드로 볼 수 있게 되었습니다.

[##_Image|kage@ccX8V5/btsMnrRPgyF/o3tGMgk56J0X5AC5ybLQGK/img.png|CDM|1.3|{"originWidth":1551,"originHeight":331,"style":"widthContent"}_##]
