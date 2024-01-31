# ChipPlacement
Chip placement by Reinforcement learning

## Mask Place

### 1. Why MaskPlace?
* HPWL: 
* Congestion: 
* Overlap: 많은 경우 0%
* 

[질문]
- 

---
### 2. Dataset
* adaptec1
  * Macro: 543
  * Hard Macro: 63 (이미 배치된 마크로)
  * Standard cell: 210,904
* .

---
### 3. 
* 

---
### 4. How can we calculate HPWL?
* comp_res.py에서 이를 구할 수 있다.
*  Step
    1. 각 넷의 모든 핀의 위치를 파악
    2. 각 넷의 바운딩 박스를 계산
    3. 각 넷의 바운딩 박스의 반 둘레를 계산
    4. 모든 넷의 반 둘레를 합해 HPWL을 계산
*  .




---
### 참조
* 마크다운 문법: <https://backendcode.tistory.com/165>
* DQN 논문: <https://ropiens.tistory.com/75>
