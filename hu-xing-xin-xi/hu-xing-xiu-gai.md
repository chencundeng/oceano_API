### 概述

```
户型信息修改
```

### 服务全类名

```
com.oceano.center.building.serviceimpl.buildingmodel.BuildingModelService.update
```

### 请求参数

| 参数 | 必填 | 说明 | 示例 |
| :--- | :--- | :--- | :--- |
| buildingModel | 是 | 楼盘户型实体信息 |  |
| images | 是 | 户型图实体集合 |  |
| label | 否 | 户型标签实体集合 |  |

### 响应结果

| 名称 | 类型 | 必填 | 说明 |
| :--- | :--- | :--- | :--- |
| boolean | 布尔类型 | 是 | true ：成功 false:失败 |

### 调用示例

```
boolean Re=
buildingmodelService.update(BuildingModel buildingmodel,List<Image> images,List<Label> label);
```

### 响应结果备注

```
[
  {
    True    正确
    false    错误
 }
]
```



