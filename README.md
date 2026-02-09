# Distributed System Health Prediction

As more apps get deployed, how will their developers know how their systems are holding up?

## Problem Statement

Distributed systems for companies deploying applications can fail unexpectedly, causing financial and reputational damage to them. This system will serve to predict the health of system health states prior to failure, enabling positive server health to be ensured for high reliability.

## Dataset overview

Source: [Kaggle](https://www.kaggle.com/datasets/niladriroy0/distributed-system-architecture-stress-and-failure)

Description: Each record captures a snapshot of a distributed system's performance metrics and configuration

Statistics:
    - 21 Columns
    - 200,000 Records
    - Target Variable : `system_state` with 4 classes

Challenge: Class imbalance with 2 states containing over 99% of the data