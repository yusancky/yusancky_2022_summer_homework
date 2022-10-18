# 简介

一个通过 [Slidev](https://cn.sli.dev) 制作的、关于中国小说《水浒传》主要人物的演示文稿。

# 发行版本迭代顺序

```mermaid
graph LR;
    subgraph 1.0.0-beta
    1.0.0-beta-1.0;
    1.0.0-beta-1.1;
    1.0.0-beta-2.0;
    end
    subgraph 1.0.x
    1.0.0;
    1.0.1;
    end
    
    1.0.0-beta-1.0-.->1.0.0-beta-1.1;
    1.0.0-beta-1.0-->1.0.0-beta-2.0;
    1.0.0-beta-1.1-.->1.0.0-beta-2.0;
    1.0.0-beta-2.0-->1.0.0;
    1.0.0-->1.0.1;
```
