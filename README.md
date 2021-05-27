# Cover-Song Identifier
> Program that determines whether two different sound sources are in a cover relationship



## Introduction

> 본 directory 학습내용의 출처는 [FutureSkill](https://futureskill.io/)의 [Contents](https://futureskill.io/content/02a953a4-e401-4539-b518-f0a7bd7d67c6)입니다.



우리에게 서로 다른 두 노래의 비슷한 정도를 구별하는 것은 자연스럽고 간단한 일이지만 기계에게는 쉽지만은 않은 일이다. 단순히 음압의 변화 양상만을 바탕으로 곡 전체의 컨텍스트를 이해하기는 쉽지 않기 때문이다.

이번 컨텐츠의 목표는 서로 다른 두 음원이 서로 커버 관계에 있는지를 판단할 수 있는 방법에 대해 고민하는 과정을 포함한다.

여러가지 악기와 가창이 존재하는 **음악**이라는 복잡한 신호 속에서, 그것이 다른 아티스트에 의해 커버 되었을 때 변하는 것과 변하지 않는것을 파악하고, 변하지 않는 요소를 추출하여 비교해낼 수 있는 방법에 대해 생각해볼 기회를 가져보자.

본 컨텐츠를 통해서 우리는 음원으로부터 추출할 수 있는 정보에는 어떤 것들이 있으며, 서로 다른 두 음원에 대해 해당 정보들을 비교하는 방법에 대해 이해한다.



#### 학습 목표

- **[최종] 서로 다른 두 음원간의 cross-similarity matrix 분석**
- *(목표 1) 음원으로부터 멜로디 정보 추출하기*
- *(목표 2) 서로 다른 두 음원의 키 차이를 파악하고 보정하기*
- *(목표 3) 유사도의 정의에 대해 생각하기*
- *(목표 4) Invariant 개념에 대해 이해하기*



## Contents



1. 직접 식별해보기
2. 음원 살펴보기
3. 멜로디 Feature 살펴보기
4. Optimal Transposition Index
5. Cross Similarity Matrix
6. tempo invariant
7. 마무리 - 1
8. 마무리 - 2
