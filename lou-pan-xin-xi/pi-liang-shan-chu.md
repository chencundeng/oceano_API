### 概述

```
楼盘基础信息及对应的图片信息、标签信息删除服务
```

### 服务全类名

```
com.oceano.center.building.serviceimpl.building.BuildingService.deleteAll
```

### 请求参数

| 参数 | 必填 | 说明 | 示例 |
| :--- | :--- | :--- | :--- |
| buildingIds | 是 | 楼盘ID用逗号隔开 | 1,2,3,4 |

### 响应结果

| 名称 | 类型 | 必填 | 说明 |
| :--- | :--- | :--- | :--- |
| boolean | 布尔类型 | 是 | true:成功 false:失败 |

### 调用示例

```
Boolean re=buildingService. deleteAll (String buildingIds);
```

### 响应结果备注

```
如
  [
     {
        True    正确
        false    错误
     }
 ]
```



