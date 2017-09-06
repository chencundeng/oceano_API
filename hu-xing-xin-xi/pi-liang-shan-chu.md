### 概述

```
户型信息批量删除
```

### 服务全类名

```
com.oceano. center.build.serviceimpl.buildingmodel.BuildingModelService.deleteAll
```

### 请求参数

| 参数 | 必填 | 说明 | 示例 |
| :--- | :--- | :--- | :--- |
| modelIds | 是 | 户型id字符串 | 1,2,3 |

### 响应结果

| 名称 | 类型 | 必填 | 说明 |
| :--- | :--- | :--- | :--- |
| boolean | 布尔类型 | 是 | true:成功 false:失败 |

### 调用示例

```
Boolean Re= 
buildingmodelService.deleteAll(String modelIds);
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



