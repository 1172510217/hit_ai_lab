# 实验二：搜索策略
## 环境说明
- python版本：2.7
- 运行须知
    - 需要将下面两个文件替换到实验给的目录中
    - 需要将lab2作为工作目录，否则需修改各模块之间的导入信息
## 文件说明
- [search.py](search.py)
    - 实验中需要修改的第一个文件，包括问题1-4
    - 该模块实现的算法具有较好的简洁性，且注释规范
    - 搜索策略的差别仅仅在于Open表的不同，为了实现push参数的一致性，使用了PriorityQueueWithFunction
- [searchAgent.py](searchAgents.py)
    - 实验中需要修改的第二个文件，包括问题5-8
    - 该部分在报告中进行了详细的分析和证明