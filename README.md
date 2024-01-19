# gan-cifar10-training
잠재 변수 차원을 32로 설정한 discriminator와 함께 generator 모형을 이용해 50 epoch을 학습하고,
학습된 generator로부터 생성된 이미지 64개를 하나의 plot에 표현.

(참고) CIFAR10 dataset은 RGB image이므로 discriminator의 입력값 차원과 generator의 출력값 차원이 32x32x3이어야 한다.
