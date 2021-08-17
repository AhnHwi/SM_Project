프로젝트 : Object Detection 모델을 API 형식으로 제공하여, 딥러닝 모델 예측 결과를 보여줄 수 있는 Web 화면 개발

목표 : 자율주행에서 가장 많이쓰이는 Object Detection과 Semantic Segmentation을 이해하고 해당 모델을 API 형태로 제공하는 방법을 습득

1) server.py 실행후, 크롬에서 http://localhost:5001/ URL 접속 후 아래 화면 구동 되는지 확인

2) Server.py에 있는 result 결과물이, HTML에서 보일 수 있도록 개발
 - result 결과물은 첨부파일안에 있는 model/YOLO_v3.py 파일을 실행시켜 보면 알 수 있음

3) Opencv 라이브러리가 아닌 tensorflow 혹은 pytorch를 통해 Semantic Segmentation 모델로 변경

 - Semantic Segmentation 모델 중 UNet 사용 추천

심화과정 : Probablity Threshold Bar를 이용하여 Object Detection 모델의 결과 값을 유동적으로 변경할 수 있도록 개발
