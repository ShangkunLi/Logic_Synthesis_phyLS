# Documentation
Student: Shangkun LI
Student ID: 20307130125
Department of Physics

Repository: https://github.com/ShangkunLi/Logic_Synthesis_phyLS.git

本Project主要通过调用phyLS逻辑综合框架进行逻辑综合。

## 目录

## 1 项目说明
### 1.1 功能说明
本项目利用phyLS提供的逻辑综合工具代码框架，完善其中的balance和rewrite功能。然后利用该工具对10个benchmarks进行逻辑综合，并记录结果。

### 1.2 文件结构
```
Logic_Synthesis_phyLS   # 项目文件夹
├── phyLS   # 子项目文件夹（phyLS文件夹）
│   ├── benchmarks  # 测试用例
│   ├── build   # 编译文件夹
│   ├── CMakeLists.txt  # CMake文件，用于生成Makefile
│   ├── docs    # Documentation
│   ├── lib # 依赖的library
│   ├── LICENSE
│   ├── README.md   # 说明文档
│   └── src # 源文件
└── README.md   # 说明文档（本文）
```

## 2 代码说明
本项目主要基于已有的phyLS架构实现了balance和rewrite的功能。该部分可分为两部分构成：
1. 介绍balance算法的实现思路
2. 介绍rewrite算法的实现思路

### 2.1 Balance算法实现思路

### 2.2 Rewrite算法实现思路


## 3 编译及运行