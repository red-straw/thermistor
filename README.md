# thermistor

이 프로젝트는 아두이노로 온도를 측정하고, 온도를 서버로 보내고, 화면에 표시하는 프로젝트이다.
먼저 아두이노코드는 adc를 통해 받은 데이터를 실제 온도 값으로 변환하여 최종적으로 섭씨온도로 나타내어 시리얼 포트에 출력한다.
processing 코드는 데이터를 받아와 화면에 출력하고, 초기화하는 과정을 반복함으로써 현재온도를 보여주는 역할을 한다.
