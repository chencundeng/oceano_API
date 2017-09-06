### 概述

```
户型信息、户型图片、户型标签删除
```

### 服务全类名

```
com.oceano.center.building.serviceimpl.buildingmodel.BuildingModelService.delete
```

### 请求参数

| 参数 | 必填 | 说明 | 示例 |
| :--- | :--- | :--- | :--- |
| modelId | 是 | 户型ID |  |

### 响应结果

| 名称 | 类型 | 必填 | 说明 |
| :--- | :--- | :--- | :--- |
| boolean | 布尔类型 | 是 | true:成功 false:失败 |

### 调用示例

```
Boolean re =buildingmodelService.delete(String modelId);
```

### 响应结果备注

```
 [
   {
     True    正确
     false   错误
   }
]
```



