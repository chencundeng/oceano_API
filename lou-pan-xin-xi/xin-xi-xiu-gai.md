### 概述

```
楼盘基础信息 图片信息 标签信息 修改
```

### 服务全类名

```
com.oceano.web.serviceimpl.building.BuildingService.update
```

### 请求参数

| 参数 | 必填 | 说明 | 示例 |
| :--- | :--- | :--- | :--- |
| Building | 是 | 楼盘信息实体类 |  |
| Image | 是 | 楼盘图片信息实体类 |  |
| Label | 否 | 楼盘标签实体类 |  |

### 响应结果

| 名称 | 类型 | 必填 | 说明 |
| :--- | :--- | :--- | :--- |
| boolean | 布尔类型 | 是 | true:成功 false:失败 |

### 调用示例

```
buildingService.update(building,image,label.getLables());
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



