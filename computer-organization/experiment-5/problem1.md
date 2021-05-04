# Problem 1

1. 2개의 open-collector buffer만을 연결하여 ![equation1](img/equation1.png)가 되도록 해 보시오.
2. 2개의 open-collector NAND gate와 NOT gate 하나를 이용하여 ![equation2](img/equation2.png)가 되도록 연결해 보시오.
3. 2개의 tri-state buffer와 하나의 NOT gate를 이용하여 2 × 1 multiplexer를 만들어 보시오.
4. 3을 수정하여 E (Enable) input이 있는 2 × 1 multiplexer를 만들어 library 형태로 저장하시오. 단 E = 0이면 정상적인 multiplexer로 동작하나 E = 1이면 출력은 high impedance state (끊어진 것처럼 동작하는 상태)가 된다.
5. 4에서 만든 multiplexer library를 여러 개 이용하여 8 × 1의 multiplexer를 만들어 보시오. 단 주어진 multiplexer 외에 필요하다면 다른 소자(예를 들면 decoder, gate 등)를 사용해도 무방함.

## Answer

### 1.

![problem1_1](img/problem1_1.png)

### 2.

![problem1_2](img/problem1_2.png)

### 3.

![problem1_3](img/problem1_3.png)

### 4.

![multiplexer](img/multiplexer.png)
![problem1_4](img/problem1_4.png)

### 5.

![problem1_5](img/problem1_5.png)
