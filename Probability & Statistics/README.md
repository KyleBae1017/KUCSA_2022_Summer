# Probability & Statistics

## Logistics
- Tutor: [Minseong Bae](https://github.com/KyleBae1017) (bms2002@korea.ac.kr)
- Time: TBD
- Location: TBD (대면 희망)

## Abstract

## References
- [Essentials of Programming Languages](https://www.amazon.com/gp/product/0262062798?ie=UTF8&tag=ucmbread-20&linkCode=as2&camp=1789&creative=9325&creativeASIN=0262062798)
- [Notes on Programming Languages (in Korean)](http://prl.korea.ac.kr/~pronto/home/courses/cose212/2019/pl-book-draft.pdf)

## Goal & Topics
프로그래밍 언어의 가장 기본적인 요소들에 대해 이해하는 것을 목표로 한다.
특히 프로그래밍 언어의 인터프리터를 설계하고 구현하는 과정을 공부함으로써 프로그래밍 언어를 구성하는 문법(syntax)과 의미(semantics)가 무엇이며, 정해진 규칙대로 작성된 코드가 컴퓨터에서 실행될 수 있게 되는 과정을 이해하고자 한다.
자세한 주제는 다음과 같다:

- **Preliminaries:** Inductive definition, Rule of inference, Functional programming
- **Basic Concepts:** Syntax, Semantics, Naming, Binding, Scoping, Environment, Interpreters, States, Reference, Parameter passing
- **Advanced Concepts:** Type system, Typing rules, Type checking, Soundness/completeness, Type inference, Polymorphism, Objects, Classes, Methods, Inheritance, Typed object-oriented languages

## Prerequisties
본 스터디의 내용과 과제에서는 함수형 프로그래밍을 주로 다루지만, C나 Python과 같은 언어의 기본적인 프로그래밍 스킬을 자연스럽게 할 수 있는 수준이면 좋다.

프로그래밍 과제는 모두 Ocaml을 활용할 예정이다.
대표적인 함수형 프로그래밍 언어이자 선언형 프로그래밍 언어이기 때문에 공부해 두면 인생에 큰 도움이 될 것이다.

또 아주 약간의 계산이론 내용과 이산수학 내용을 알고 있으면 도움되지만, 모르는 사람을 위해 첫시간에 관련 스터디를 진행할 예정이다.

## Assignments
본 스터디의 과제는 GitHub Classroom으로 진행될 예정이다.
이에 약간의 Git, GitHub 스킬을 가지고 있으면 좋으나 이 역시 스터디에서 충분히 따라올 수 있도록 설명할 예정이다.

구체적인 과제 내용 및 제출 방식은 스터디 첫 시간에 공지하도록 하겠다.

## Schedule (Tentative)
|Weeks|Topics|Assignments|
|:---:|:---:|:---:|
|Week 1|귀납적 구조를 정의하는 법, Ocaml 기초|[Assignment 1](https://classroom.github.com/a/-ZucFpOD)|
|Week 2|OCaml을 활용한 함수형 프로그래밍|[Assignment 2](https://classroom.github.com/a/m7O-j0zq)|
|Week 3|인터프리터 만들기: 식(Expressions), 함수(Procedures)||
|Week 4|인터프리터 만들기: 재귀함수(Recursion), 유효범위 규칙(Scoping Rules)|Assignment 3|
|Week 5|인터프리터 만들기: 상태(States), 포인터(Pointers)|Assignment 4|
|Week 6|더 나은 인터프리터 만들기: 간단한 타입 체계(Type System)||
|Week 7|더 나은 인터프리터 만들기: 타입 추론(Type Inference)|Assignment 5|
|Week 8|마무리: 람다 칼큘러스(Lambda Calculus), 그래서 왜 PL인가?||
