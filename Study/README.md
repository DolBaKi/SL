# Study
### RLHF(Reinforcement Learning with Human Feedback)
    인간이 Stable-Diffusion이 낸 2개 중 더 나은 결과를 선택하는 피드백으로 학습
    그러나... 이를 통해 학습한 결과가 좀... 처참(하다못해 보기 좀 불쾌)하다
    인간 피드백을 통해 더 좋은 결과값을 원했지만 하.. 왜이렇게 된거지

### YOLO_v8_Detection.ipynb
    현존하는 강력한 이미지 분류 모델 중 하나인 YOLO v8을 통해 사고 영상을 분류하는 모델을 만들기로 함
    이미지를 RLHF를 통해 Stable-Diffusion을 학습시켜서 이미지를 겁나게 뽑아내고
    이를 YOLO에 학습(아 근데 이미지 라벨링 언제 다하지)시킨다
    그러면 끝. 일단 이미 있는 데이터로 학습
