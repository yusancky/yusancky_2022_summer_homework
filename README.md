# Basic Introduction

A presentation slide made with [Slidev](https://sli.dev) about some characters in the Chinese novels [_Water Margin_](https://en.wikipedia.org/wiki/Water_Margin) _(also known as "_Shui Hu Zhuan_", "_Outlaws of the Marsh_" and "_All Men are Brothers_")_. 

# Sort of releases

```mermaid
graph LR;
    1.0.0-beta-1.0-.->1.0.0-beta-1.1;
    1.0.0-beta-1.0-->1.0.0-beta-2.0;
    1.0.0-beta-1.1-.->1.0.0-beta-2.0;
    1.0.0-beta-2.0-->1.0.0;
    1.0.0-->1.0.1;
    
    subgraph 1.0.0-beta-1.x
    1.0.0-beta-1.0;
    1.0.0-beta-1.1;
    end
    subgraph 1.0.0-beta-2.x
    1.0.0-beta-2.0;
    end
    subgraph 1.0.x
    1.0.0;
    1.0.1;
    end
```
