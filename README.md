# Decision tree on Golang


## Usage
```
import (
  . "github.com/zoh/decision-tree/tree"
)
tree := DecisionTree{CategoryAttr: "param", ignoredAttribute: []string{}}
TrainingTree(&tree, trainingSet)

//...
// category item
var item TrainingItem
category := tree.Predict(item)
```

## Test
```
go test
```

- 决策树, 专家系统, 特大树, 随机森林, 梯度提升树, 层次聚类, 自适应提升树, 权重树, 绝对偏差决策树, Hellinger距离树.
- Ref: https://github.com/blockgraph/CloudForest
