# kibana-visualize-sankey
a sankey diagram use kibana vega，and data source from suricata \n
因为官方只有2node的例子，3node以上正确运行的例子似乎并不多


## 效果
4 node 桑基图效果

![](/sankey-2.gif)

## 数据
来源于suricata，并通过filebeat module suricata格式化后写入elasticsearch
也适用于其他场景


## 兼容性
仅在kibana 7.17.15测试

## 使用
From kibana
1. Analytics -> Visualize Library -> Add New
2. Vega visualizations
3. Copy the json file to the right
4. Modify the “data” section,"index"、“sources” value to fit your own data
5. Enjoy!!










