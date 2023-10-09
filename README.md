# Machine-Learning / DeepLearning-small-project
- 개념정리는 노션에 잘 정리해 두었습니다.

- 활용 툴
- [![YOLOv5](https://img.shields.io/badge/YOLOv5-FF6384?style=flat&logo=pytorch&logoColor=white)](https://github.com/ultralytics/yolov5)

## DeepLearning
- CNN : https://www.notion.so/CNN-Convolution-Neutral-Network-db80b1c7d27d4d42a98a5e01cb47bb56
- 자연어: https://www.notion.so/1ff3a0c19ca54372a91a85e25b509b00



# ※ 실습은 코랩과 주피터 노트북을 통해 진행하였습니다. 
- 이를 구분하기 위해 (코랩) 혹은 (주피터) 로 이름을 지어두겠습니다.
- 폴더별로 코드 파일을 잘 정리해 두었습니다.
- 실습에 사용되었던 이미지, csv파일 등은 Data 폴더 내부에 코드 제목으로 두었습니다.
  - ex) TransferLearning에 사용된 이미지 파일은 -> Data -> TransferLearning 폴더에 있습니다.
- 실습 결과로 형성된 모델은 h5파일로 save하여 다운 받을 수 있는 링크를 Model 폴더에 적어 두었습니다.
- 저장된 모델의 로드 방법은, 모델을 다운 받은 이후
    - from tensorflow.keras.models import load_model
    - model = load_model('모델이 저장된 경로/모델 파일의 이름.h5') 으로 load 가능합니다. <br>
<br>
<br>



## 코랩 실습 코드 이용시 참고하면 좋을 점
- 코랩의 목차 기능을 이용하며, step 별 소제목을 적어 두었기 때문에 따라가면서 공부하면 좋을 것 같습니다.
- ![image](https://github.com/thumbs-js/DeepLearning-small-project/assets/127809974/a87a6b0a-a942-4f3c-b3de-f938c426b337)

