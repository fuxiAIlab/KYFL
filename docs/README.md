# MVAN
The paper is accepted by the 25th International Conference on Database Systems for Advanced Applications (DASFAA 2020).

# Authors
Angyu Zheng (Sun Yat-sen University); Liang Chen (Sun Yat-sen University); Fenfang Xie (Sun Yat-sen University); Jianrong Tao (NetEase Fuxi AI Lab); Changjie Fan (NetEase Fuxi AI Lab) and Zibin Zheng (Sun Yat-sen University)

# Abstract
Customer retention is a crucial problem for game companies since the revenue is heavily inﬂuenced by the size of their user bases. Previous studies have reached a consensus that the cost of attracting a new player can be six times than retaining the players, which indicates an accurate churn prediction model is essential and critical for the strategy making of customer retention. Existing works more focus on studying login information(e.g. login activity traits of users) ignoring the rich ingame behaviors(e.g. upgrading, trading supplies) which could implicitly reﬂect user’s preference from their inter-dependencies. In this paper, we propose a novel end-to-end neural network, named ChurnPred, for churn prediction problem. In particular, we not only consider the login behaviors but also in-game behaviors to model user behavior patterns more comprehensively. For time series of login activities, we leverage a LSTMbased structure to learn intrinsic temporal dependencies so as to capture the evolution of activity sequences. For in-game behaviors, we develop a time-aware ﬁltering component to better distinguish the behavior patterns occurring in a speciﬁc period and a multi-view mechanism to automatically extract the multiple combinations of these behaviors from various perspectives. Comprehensive experiments conducted on real-world data demonstrate the eﬀectiveness of the proposed model compared with state-of-the-art methods.

# Datasets
todo