# 공주대학교 컴퓨터공학부 소프트웨어전공 캡스톤디자인 프로젝트입니다.

# 기능 구현

>서버
>>OS : Ubuntu Linux 16.04 LTS
>>개발 언어 : Python
>>이용 SW : MySQL, Hadoop, Keras, Tensorflow, Apache Zeppelin, Spark

>어플리케이션
>>OS : Windows 10 Home
>>개발 언어 : Java
>>이용 SW : Android Studio, Tensorflow Lite

>진행과정
>>1. 전문 광계측장비(분광복사계, CAS 140 CT)를 통해 실측한 자연광 데이터를 분석하여 딥러닝을 위한 데이터 셋을 도출
>>2. 딥러닝 서버에서 DNN(Deep Neural Network) 모델의 구축 및 학습을 수행한 후 Tensorflow Lite Converter를 통해 모바일용 딥러닝 모델(tflite)로 변환하고, 이를 딥러닝 서버를 통해 사용자의 스마트폰으로 배포
>>3. 스마트폰의 조도 센싱 값과 GPS 센서 기반의 위치 정보를 함께 입력하여 자외선(UVI)정보를 산출
>>4. 산출된 자외선 정보를 바탕으로 UVI 단계 설정 및 단계별 주의사항 출력
