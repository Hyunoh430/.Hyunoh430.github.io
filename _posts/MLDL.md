---
layout: post
title:  "ML/DL"
---

# 지도 학습
- **정답**을 알고 있다!

- 지도 학습의 예)
  - **회귀 (regression)**
  - **분류 (classification)**

# 비지도 학습
- **정답**을 모른다

- 지도 학습의 예)
  - **군집화 (K-means, DBSCAN)**
  - **차원 축소 (데이터 전처리: PCA, SVD)**
  - **GAN**




# 자기지도 학습
- 정답을 알고 있는 데이터가 너무 적다
- 진짜 풀려고 했던 문제 말고 다른 문제를 새롭게 정의해서 먼저 풀어본다!
#### 순서
- 1.pretext task 학습으로 pre-training<br>
  2.downstream task(분류)를 풀기 위해 transfer learning함


# 강화학습
- Agent : 강아지, 흑돌
- Reward : 간식, 승리
- Environment : 보호자, 흰돌
- Action : 손, 수
- State : 바둑판, 위치
- Q-function : Q(s, q) 입력이 두개다 : 어떻게 했을때 얼마나 좋다 저장
- Episode : 판, 시도
- Q-learning : 
- Exploration : discount factor을 곱해줘서 최적의 길을 찾는다


```python

```
