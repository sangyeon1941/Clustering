# Clustering
군집화(Clustering)는 비지도학습의 한 예시로, 어떠한 label 없이 데이터 내에서 거리가 가까운 것들끼리 각 군집들로 분류하는 것임.
즉 데이터 내에 숨어있는 패턴, 그룹을 파악하여 서로 묶는 것이라고 할 수 있음. 만약 라벨값이 존재하는 데이터라고 하더라도, 같은 라벨 내에서도 얼마든지 다른 군집으로 묶일 가능성이 있다.

# K-Means
K-Means 클러스터링은 클러스터링에서 가장 일반적으로 사용되는 알고리즘으로, 군집 중심점(centroid)이라는 특정한 임의의 지점을 선택해 해당 중심에 가장 가까운 포인트들을 선택하는 군집화 기법임. 
K-Means이므로 K개의 centroid를 지정하며 이때 가장 가까운 포인트를 선택한다는 점에서 K-Means는 거리 기반 군집화 방법임을 알 수 있음
![image](https://github.com/sangyeon1941/Clustering/assets/170851785/da5402d5-a254-4275-bd2d-8a94d4e2f608)



# DBSCAN
DBSCAN은 밀도 기반 클러스터링 방법임. 보다 기하학적으로 복잡하게 분포된 데이터셋에도 효과적인 군집화가 가능함. 
DBSCAN을 구성하는 가장 중요한 두 가지 파라미터는 epsilon으로 표기하는 주변 영역과 epsilon 주변 영역에 포함되는 최소 데이터의 개수 min_points임.
![image](https://github.com/sangyeon1941/Clustering/assets/170851785/ce3be5bb-cd87-4c3e-8006-d3d2342b956b)
