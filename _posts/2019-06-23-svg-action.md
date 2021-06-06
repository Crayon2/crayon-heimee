---
tags:
    - svg
title: svg动态图-跳动的闪球
date: 2019-6-22
categories:
     - svg制作
      
---

### 跳动的闪球，边跳动边闪烁

<section>

    <svg width="400" height="400">
    <circle cx="200" cy="200" r="100" style="fill:#CFCA6D" >
        <animate attributeName="cy" attributeType="XML" values="300;10;300" begin="0s" dur="1s" repeatCount="indefinite"/>
        <animate attributeName="fill-opacity" attributeType="CSS" values="1;0.2;1" begin="0s" dur="1s" repeatCount="indefinite"/>
    </circle>
</svg>

</section>

球上下跳动，并伴随着颜色的改变

##### 使球动起来的代码：
   
   <img src="/assets/images/tiaodong.png">
   
   
##### 上下两行代码分别控制不同的动画，上面一行是球的跳动，下面一行是球的变色。其中attributeName="cy"控制的是球跳动的方向，即在y轴上运动。