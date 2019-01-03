# Study_PyTorch

PyTorch 홈페이지를 참고하여 PyTorch 학습
https://pytorch.kr/beginner/pytorch_with_examples.html

PyTorch의 핵심에는 2가지 주요한 특징이 있습니다.
-NumPy와 유사하지만 GPU 상에서 실행 가능한 N차원 Tensor
-신경망을 구성하고 학습하는 과정에서의 자동 미분

완전히 연결된 ReLU 신경망을 예제로 사용할 것입니다. 이 신경망은 하나의 은닉 계층(Hidden Layer)을 갖고 있으며, 신경망의 출력과 정답 사이의 유클리드 거리(Euclidean Distance)를 최소화하는 식으로 경사하강법(Gradient Descent)을 사용하여 무작위의 데이터를 맞추도록 학습할 것입니다.

## 목차
*Tensor
**준비 운동: NumPy
**PyTorch: Tensor
*Autograd
**PyTorch: Tensor와 autograd
**PyTorch: 새 autograd 함수 정의하기
**TensorFlow: 정적 그래프(Static Graph)
*nn 모듈
**PyTorch: nn
**PyTorch: optim
**PyTorch: 사용자 정의 nn 모듈
**PyTorch: 제어 흐름(Control Flow) + 가중치 공유(Weight Sharing)
*예제 코드
**Tensor
**Autograd
**nn 모듈
