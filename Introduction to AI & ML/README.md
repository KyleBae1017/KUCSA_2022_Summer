# Introduction to Artificial Intelligence & Machine Learning

본 스터디의 계획서 및 내용, 과제는 [고려대학교 컴퓨터학과 김현우 교수님](https://www.hyunwoojkim.com/)의 COSE361 인공지능 수업 및 [Berkeley CS188 : Introduction to Artificial Intelligence](https://inst.eecs.berkeley.edu/~cs188/sp22/)를 바탕으로 하고 있음을 밝힙니다. 

## Logistics
- Tutor: [Minseong Bae](https://github.com/KyleBae1017) (bms2002@korea.ac.kr)
- Time: TBD
- Location: TBD (대면 희망)

## Abstract

This course will introduce the basic ideas and techniques underlying the design of intelligent computer systems. A specific emphasis will be on the statistical and decision-theoretic modeling paradigm.

By the end of this course, you will have built autonomous agents that efficiently make decisions in fully informed, partially observable and adversarial settings. Your agents will draw inferences in uncertain environments and optimize actions for arbitrary reward structures. Your machine learning algorithms will classify handwritten digits and photographs. The techniques you learn in this course apply to a wide variety of artificial intelligence problems and will serve as the foundation for further study in any application area you choose to pursue.

([Berkeley CS188 : Introduction to Artificial Intelligence](https://inst.eecs.berkeley.edu/~cs188/sp22/) Description에서 발췌)

기본적으로 Pacman 게임을 위한 AI를 설계하는 것을 바탕으로 하여 기초적인 Search Algorithm부터 Markov Decision Process, Reinforcement Learning 등의 초중급 단계의 심화 인공지능 알고리즘을 학습합니다. 후반부에는 Naive Bayes, Decision Tree, Clustering 등의 Maching Learning 알고리즘들도 다뤄볼 예정입니다.

## References
- [Lecture Notes from Berkeley CS188](https://inst.eecs.berkeley.edu/~cs188/sp22/)
- [Artificial Intelligence : A Modern Approach, 4th Edition](https://www.pearson.com/us/higher-education/program/Russell-Artificial-Intelligence-A-Modern-Approach-4th-Edition/PGM1263338.html)

## Goal & Topics
Pacman 게임의 개념을 기반으로 하여 인공지능의 개념과 고전적인 인공지능 알고리즘, 확률적 접근을 통한 심화 인공지능 알고리즘 및 기초 강화 학습 알고리즘을 학습하며 머신 러닝 분야에서 많이 사용되는 일부 알고리즘들에 대해 알아보고 실습해 보는것을 목표로 합니다.

자세한 주제는 다음과 같습니다:

- **Introduction to AI & ML:** Definition of AI & ML and Its Applications
- **Search Algorithm:** Uninformed Search & Informed Search - BFS, DFS, UCS, A-star and Heuristics
- **Game Tree:** Adversarial Search, Adversarial Game Trees - Minimax, Alpha-Beta Pruning
- **Algorithms Based on Uncertainty:** Expectimax Game Tree, Utilities, Markov Decision Process
- **Reinforcement Learning:** Bellman Equations, Q-learning, Approximate Q-learning, Numerical Optimization and Gradient Descent Algorithm
- **Basic Machine Learning:** Naive Bayes Classifier, Decision Tree, Clustering

## Prerequisties
- 과제를 위한 프로그래밍 언어로 Python을 이용하기 떄문에 Python 프로그래밍 및 Python 내 객체지향 프로그래밍 기능에 대한 이해가 있어야만 과제 수행이 가능합니다. 현재는 과제를 선택 사항으로 생각하고 있긴 하나 과제를 수행하신다면 스터디를 더 재밌게 들으실 수 있을 것 같습니다. 만약 과제가 필수가 된다면 과제 수행을 위한 Python 프로그래밍 관련 보충 수업 및 추가 자료를 제공해드릴 예정이니 너무 걱정하지 않으셔도 될 것 같습니다.
- Graph Search 관련 알고리즘에 대한 이해도가 어느 정도 있다면 더 쉽게 스터디를 들으실 수 있을 것 같습니다.

## Assignments (Optional)
Pacman AI 개발과 관련된 4개의 과제 + Machine Learning 과제 1개가 주어질 예정입니다.
과제3과 과제4는 스터디원들끼리 Competition을 진행해 Ranking을 매겨, 우수 스터디원에게 Benefit을 제공할 예정입니다.

- Assignment 1 : Search 알고리즘 구현 (BFS, DFS, UCS, A-star)
- Assignment 2 : Alpha-Beta Pruning 기반 Minimax Game Tree 구현
- Assignment 3 : Pacman AI (1) - 맵 위의 모든 음식을 먹는 Pacman Agent 구현
- Assignment 4 : Pacman AI (2) - Capture-The-Flag 게임 기반 Pacman 게임 Agent 구현
- Assignment 5 : Machine Learning - 스팸 메일 분류기 (미확정, 변경 가능)

## Schedule (Tentative)
|Weeks|Topics|Assignments
|:---:|:---:|:---:|
|Week 1|Introduction to AI & ML + Search Algorithms (1)||
|Week 2|Search Algorithms (2) + Game Tree (1)|Assignment 1|
|Week 3|Game Tree (2) + Algorithms Based on Uncertainty (1) : Expectimax Game Tree||
|Week 4|Algorithms Based on Uncertainty (2) : Markov Decision Process (1)|Assignment 2|
|Week 5|Algorithms Based on Uncertainty (3) : Markov Decision Process (2) + Reinforcement Learning (1)|Assignment 3|
|Week 6|Reinforcement Learning (2)|Assignment 4|
|Week 7|Machine Learning (1)||
|Week 8|Machine Learning (2)|Assignment 5|
