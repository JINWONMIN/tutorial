## PyTorch
- 페이스북이 초기 Lua 언어로 개발된 Torch를 파이썬 버전으로 개발하여 2017년도에 공개
- 초기 Torch는 NumPy 라이브러리처럼 과학 연산을 위한 라이브러리로 공개
- 이후 GPU를 이용한 텐서 조작 및 동적 신경망 구축이 가능하도록 딥러닝 프레임워크로 발전 시킴
- 파이썬답게 만들어졌고, 유연하면서도 가속화된 계산 속도를 제공

### PyTorch Module Structure
![화면 캡처 2022-05-17 215427](https://user-images.githubusercontent.com/94345086/168815517-bb453e00-c89c-46a1-bde7-b5c4bb85abbc.png)
<https://livebook.manning.com/#!/book/deep-learning-with-pytorch/welcome/v-7/>

### 구성요소
- `torch`: 메인 네임스페이스, 텐서 등의 다양한 수학 함수가 포함
- `torch.autograd`: 자동 미분 기능을 제공하는 라이브러리
- `torch.nn`: 신경망 구축을 위한 데이터 구조나 레이어 등의 라이브러리
- `torch.multiprocessing`: 병럴처리 기능을 제공하는 라이브러리
- `torch.optim`: SGD(Stochastic Gradient Descent)를 중심으로 한 파라미터 최적화 알고리즘 제공
- `torch.utils`: 데이터 조작 등 유틸리티 기능 제공
- `torch.onnx`: ONNX(Open Neural Network Exchange), 서로 다른 프레임워크 간의 모델을 공유할 때 사용

##### Ref
<https://www.youtube.com/c/%EC%9D%B4%EC%88%98%EC%95%88%EC%BB%B4%ED%93%A8%ED%84%B0%EC%97%B0%EA%B5%AC%EC%86%8C>
