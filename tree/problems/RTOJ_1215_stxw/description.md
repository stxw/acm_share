### RTOJ_1215 - 查找二叉树

#### 题目描述

&emsp;&emsp;已知一棵二叉树用邻接表结构存储，中序查找二叉树中值为 x 的结点，并指出该节点是中序遍历里的第几个查找的结点。

#### 输入

&emsp;&emsp;第一行一个正整数n，为二叉树的结点个树，n<=100。

&emsp;&emsp;第二行 x 表示要查找的结点的值；

&emsp;&emsp;接下来n行，第i+2行描述了编号为i+2的节点的信息，每行三个整数，第一个整数表示该结点的值，第二个整数表示该节点的左孩子结点编号，第三个整数表示该节点的右孩子结点编号。如果左右孩子节点编号为0，表示该节点没有左孩子或右孩子，编号为1的节点为该树的根节点。

#### 输出

&emsp;&emsp;输出一个数，即值为x的节点是中序遍历里的第几个查找的结点。

#### 样例输入

>7
15
5 2 3
12 4 5
10 0 0
29 0 0
15 6 7
8 0 0
23 0 0

#### 样例输出

>4

[去看题目解析](./analysis.md)

[去看参考代码](./main.cpp)