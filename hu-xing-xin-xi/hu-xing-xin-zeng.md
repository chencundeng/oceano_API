### 概述

```
户型信息新增
```

### 服务全类名

```
com.oceano.center.building.serviceimpl.buildingmodel.BuildingModelService.save
```

### 请求参数

| 参数 | 必填 | 说明 | 示例 |
| :--- | :--- | :--- | :--- |
| images | 是 | 户型图片实体类 |  |
| buildingModel | 是 | 户型信息 |  |
| labels | 否 | 户型标签 |  |

### 响应结果

| 名称 | 类型 | 必填 | 说明 |
| :--- | :--- | :--- | :--- |
| boolean | 布尔类型 | 是 | true:成功 false:失败 |

### 调用示例

```
Boolean Re=
buildingmodelService.save(BuildingModel buildingmodel,List<Label> label,List<Image> images);
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



