# Neural-Network
📒 신경망 공부(Neural Network Study)

# Neural Network - Single layer perceptron
## 1. 단층 퍼셉트론
### 1. 학습 계획
1. **Neural networks applications**
2. **Biological fundamentals**
3. **Artificial neuron (perceptron)**
4. **Implementation of a perceptron from scratch using Python and Numpy**

### 2. 인공 신경망 애플리케이션

- Face Reconition
- 자율주행
- 주식거래
- 번역
- 딥 페이크

### 3. 생물학적 기초
![image](https://github.com/junzer0/Neural-Network/assets/110384101/386f30b9-da36-4ca7-b3da-8db37eb32b74)
- Dendrites(수상돌기) - 다른 뉴런들로부터 데이터를 받는다.
- Cell body(신경세포) - 받은 데이터를 처리
- Axon(축삭) - Axon terminal(축산 말단)을 사용하여 다른 뉴런으로 신호를 전송
- Synapse - 정보전달, 뉴런의 전위 또는 힘을 변화시킴

### 4. 인공 신경
![image](https://github.com/junzer0/Neural-Network/assets/110384101/4fa8dd4b-ec0c-4cb3-9792-e951cdc12b35)
ex) perceptron - 25살, 학력 15년 입력 → 급여 예측: 240만원
- Black box - Information processing(정보처리) → Black box Algorithm
![image](https://github.com/junzer0/Neural-Network/assets/110384101/f654eb1c-333e-4b57-8099-33bc02915f8f)
- input(입력) : x
- weight(가중치): w

Black box area
- Sum function
- Activation function(활성화 함수)

### 5. 퍼셉트론
![image](https://github.com/junzer0/Neural-Network/assets/110384101/e1dc93f2-943d-4d7f-9991-d08816acb826)
ex) 급여 인상의 자격 여부를 예측하기
- input : 35, 25
- weight : 0.8, 0.1
- Sum function : (35*0.8)+(25*0.1) = 30.5
- Activation function → Step function
- Step function
    - Greater or equal to 1 = 1 → 뉴런 활성화
    - Otherwise = 0 → 뉴런 비활성

- Perceptron
    - Positive weight – exciting synapse → 전위 증가
    - Negative weight – inhibitory synapse → 전위 감소
    - Weights are the synapses → 가중치 = 시냅스
    - Weights amplify or reduce the input signal → 가중치가 신호를 증가시키거나 감소시킴
    - The knowledge of a neural network is the weights(신경망에 대한 지식은 가중치이다.)
        - 신경망의 목적 → 데이터 셋에 가장 적합한 가중치를 찾는 것
