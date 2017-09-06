### 概述

```
楼盘详细信息展示
```

### 服务全类名

```
com.oceano.center.building.serviceimpl.building.BuildingService.select
```

### 请求参数

| 参数 | 必填 | 说明 | 示例 |
| :--- | :--- | :--- | :--- |
| buildingId | 是 | 楼盘ID | buildingId=1 |

### 响应结果

| 名称 | 类型 | 必填 | 说明 |
| :--- | :--- | :--- | :--- |
| Building | 实体 | 是 |  |

### 调用示例

```
Building  build=buildingmodelService.select(String  buildingId);
```

### 响应结果备注

```
[
     {
     buildingId:楼盘id主键
     buildingName:楼盘名称
     buildingCode:    楼盘编码
     provinceCode    :省份编码
     cityCode    :市编码
     areaCode    区编码
     sourceName    来源名称 3d云设计;手工;八爪鱼
     openingTime    开盘时间
     buildingTime    交房时间
     averagePrice    均价
     buildingPlace    楼盘地址
     propertyType    物业类型
     projectFeatures    项目特色
     decorationStatus    装修状况
     buildingDevelopers    开发商
     salesStatus    销售状态
     salesPlace    售楼地址
     saleingModel    在售户型
     buildingPhone    售楼热线
     buildingPriority    优先级
     buildingLongitude    楼盘经度
     buildingLatitude    楼盘纬度
     buildingLabel    标签id
     greeningRate    绿化率
     buildingType    建筑类型
     roomNum    户数
     elevatorNum    电梯数
     floorStatus    楼层状况
     trafficStatus    交通状况
     propertyYears    产权年限
     buildingArea    建筑面积
     createrId    创建人id
     createDate    创建时间
     creater    创建人
     modifierId    修改人id
     modifier    修改人
     modifyDate    修改时间
     recentOpened    近期开盘
     flatsDesc    楼盘特点
     provinceName    省名
     cityName    市名
     areaName    区名
     image:图片{
     imageId图片id主键
     imageName图片名称
     imageCname图片原名
     imageUrl图片url
     sourceId源id
     sourceType源类型 表名,如楼盘图片传入:t_building
     imageSize图片大小
     imageType图片类型
     createrId创建人id
     creater创建人
     createDate创建时间
     remark图片备注
     }
     Labels：标签{
     labelId    标签id主键
     labelName    标签名称
     labelRemark    标签备注
     labelStatus    标签状态
     sourceType    标签源类型 表名,如楼盘图片传入:t_building
     sourceId    标签源id
     sourceParent_id    楼盘名称id
     createDate    创建时间
}
}
]
```



