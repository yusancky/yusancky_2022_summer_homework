# 简介

一个通过 [Slidev](https://cn.sli.dev) 制作的、关于中国小说《水浒传》主要人物的演示文稿。

# 发行版本迭代顺序

```mermaid
graph LR;
    subgraph 1.0.0-beta
    id1(1.0.0-beta-1.0);
    id2(1.0.0-beta-1.1);
    id3(1.0.0-beta-2.0);
    end
    subgraph 1.0.x
    id4(1.0.0);
    id5(1.0.1);
    end
    subgraph 1.1.x
    id6(1.1.0);
    end
    
    id1-.->id2;
    id1-->id3;
    id3==>id4;
    id4-->id5;
    id5==>id6;
```