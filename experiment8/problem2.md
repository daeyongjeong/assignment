# Problem 2

Ripple carry adder의 delay를 4d라고 하면 앞에서 만든 carry lookahead adder의 delay는 3d임을 설명하시오. 단 d는 two-level network의 delay이다.

## Answer

Full adder의 delay를 d라고 했을 때, RCA는 4개의 full adder를 거쳐야 하므로 delay는 4d라고 할 수 있다.

우리가 만든 CLA는 변형된 full adder를 거쳐 P와 G를 만드는데 d, LCU에서 carry를 계산하는데 two-level만이 필요하므로 여기서 d, 그리고 다시 carry를 이용해 S를 계산하는데 d가 걸린다. 따라서 CLA의 delay는 3d라고 할 수 있다.
