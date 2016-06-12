밑바닥부터 시작하는 데이터 사이언스
===================================

"밑바닥부터 시작하는 데이터 사이언스"의 코드 저장소입니다.
이곳에는 책에 수록된 예시 코드와 링크 정보가 담겨 있습니다.

책에 오타나 오류가 있는 경우, [우측의 위키(Wiki)](https://github.com/e9t/data-science-from-scratch/wiki/Errata)에 해당 내용을 기록해주시기 바랍니다.

## 예시 코드

각 예시 코드는 다음의 두 가지 방법으로 사용할 수 있습니다.

1. 같이 `/code` 디렉토리에서 모듈로 불러 사용한다.

    ```python
    from ch4_linear_algebra import distance, vector_mean
    v = [1, 2, 3]
    w = [4, 5, 6]
    print distance(v, w)
    print vector_mean([v, w])
    ```
  
1. 명령줄에서 책의 데모를 직접 실행한다.

    ```bat
    python ch22_recommender_systems.py
    ```

## 링크 정보

추가적으로, [links.md](links.md) 파일에는 책에 실린 모든 유용한 링크 정보가 담겨 있다.


## 책의 목차

1. [들어가기](code/ch01_introduction.py)
2. 파이썬 집중강좌
3. 데이터 시각화 - [py](code/ch03_visualizing_data.py), [ipynb](notebook/ch03_visualizing_data.ipynb)
4. 선형대수 - [py](code/ch04_linear_algebra.py), [ipynb](notebook/ch04_linear_algebra.ipynb) 
5. [통계](code/ch05_statistics.py)
6. [확률](code/ch06_probability.py)
7. [가설과 추론](code/ch07_hypothesis_and_inference.py)
8. [경사 하강법](code/ch08_gradient_descent.py)
9. [데이터 수집하기](code/ch09_getting_data.py)
10. [데이터 다루기](code/ch10_working_with_data.py)
11. [기계학습](code/ch11_machine_learning.py)
12. [k-근접이웃](code/ch12_nearest_neighbors.py)
13. [나이브 베이즈](code/ch13_naive_bayes.py)
14. [단순 선형회귀](code/ch14_simple_linear_regression.py)
15. [다중 선형회귀](code/ch15_multiple_regression.py)
16. [로지스틱 회귀](code/ch16_logistic_regression.py)
17. [의사결정나무](code/ch17_decision_trees.py)
18. [신경망](code/ch18_neural_networks.py)
19. [군집화](code/ch19_clustering.py)
20. [자연어 처리](code/ch20_natural_language_processing.py)
21. [네트워크 분석](code/ch21_network_analysis.py)
22. [추천 시스템](code/ch22_recommender_systems.py)
23. [데이터베이스와 SQL](code/ch23_databases.py)
24. [맵리듀스](code/ch24_mapreduce.py)
25. 본격적으로 데이터 사이언스하기

> ipynb 파일은 python3+ 으로 기준으로 작성됨