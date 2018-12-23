# pytorch-GraphNet

본 튜토리얼은 그래프 네트워크를 pytorch로 구현하고, 
예시와 함께 이해하기 쉽도록 한국어로 제작될 예정입니다. 

            Current github page is to review Deepmind's Graph network and re-implement it in pytorch. 
            Tutorial will be largely changed and would be explained in Korean.


주요 콘텐츠는 다음과 같음 
1. Graph network 의 전반적인 이해와 응용 및 확장 가능성 시사
2. 리뷰할 논문
- [Relational inductive biased, deep learning, and graph networks](https://arxiv.org/abs/1806.01261)
- [A simple neural network module for relational reasoning](https://arxiv.org/abs/1706.01427)
3. Graphnet Shortest-path demo pytorch 구현 & 설명/ relational reasoning 핵심 network dynamics 구현 & 설명



## What are Graph Networks?
그래프 네트워크는 그래프를 입력 값과 출력값으로 갖는다.
- 그래프는 엣지(E)와 노드(V), 그리고 해당 그래프의 전체적인 속성(global-level attribute)을 변수로 둔다. 
- 반환되는 그래프는 입력되는 그래프와 동일한 구조를 가지고 있으나, 업데이트 된 속성(attribute) 값을 가진다. 

## Why Graph Networks?


## Possible Applications


## Demos
1. Shortest path
2. Relational reasoning with CNN and NLP


## References
    
    Pytorch implementation of Deepmind's Graph network. Original repo: https://github.com/deepmind/graph_nets.git.
    Original paper: https://arxiv.org/abs/1806.01261
    
    Battaglia, Peter W., et al. "Relational inductive biases, deep learning, and graph networks." arXiv preprint arXiv:1806.01261 (2018).
    Santoro, Adam, et al. "A simple neural network module for relational reasoning." Advances in neural information processing systems. 2017.
