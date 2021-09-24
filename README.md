## 2021-Summer-Internship
### :car: 에이스랩(2021.07.01~2021.08.31)
  - ### :mag_right: Document(주차별로 정리 in Notion)
    - [**AVS data server with ROS**](https://www.notion.so/AVS-data-server-with-ROS-d1976521c98e487da58c063514f30d95)
    - [**최종 발표 자료(ppt)**](https://gyeongukseo.notion.site/document-7b906092bbc241d28b765f8eba02f2f1)
  - ### :clipboard: Description
    자율주행 스타트업에서 **AVS(automobile visualization system) data server 구조 개선을 통한 bandwidth 향상**을 목표로 한 프로젝트를 수행했습니다.  
    
    Extra work로 Web server의 좌표 설정, map 띄우기를 저장된 파일을 읽어오는 것에서 실시간으로 개선했습니다
  - ### 🛠 Experience
    - 책에서의 간단한 예제들만 수행해본 **NodeJS**를 이용하여 **따로 공부를 계속하며** 프로젝트를 수행했습니다.
    - babel, webpack, lint, prettier과 같은 JS build tool들의 설치, configuration을 해주는 [Ocular](https://github.com/uber-web/ocular)를 이용해서 진행해 **build system**을 익혔습니다.
    - [XVIZ(data server)](https://github.com/uber/xviz),  [streetscape.gl(web server)](https://github.com/uber/streetscape.gl)이라는 **큰 구조의 오픈소스**를 customizing한 형태의 기존 서버를 바꾸기 위해 data flow를 따라가거나, github readme를 따라가는 등 직접 분석을 통해 익혀보았습니다.
    - 구현에 필요한 라이브러리가 **JavaScript**에서 제공하지 않는 경우 직접 다른 언어의 코드를 동일한 로직으로 구현하였습니다.
    - 주차별 과제를 수행하며 구현을 마친 뒤 Log를 이용한 Lab에서의 test(with wireshark), 실제 현장에서의 자율주행 test를 진행했습니다.
    - **다양한 환경에서 test**하며 bottleneck지점이 어딘지를 확인했고 개선한 system에서 visualize할 수 있는 한계까지 test해보았습니다.
    - 자동차와 서버의 통신을 위해 **ROS**(중 rosnodejs)를 처음 배우고 개발을 진행했습니다.
    - ROS외의 bridge를 이용하는 경우를 위해 customize가 용이한 core기반으로 **NodeJS template**을 작성했습니다.
