### 概述

```
楼盘信息展示，提供属性搜索，排序，分页
```

### 服务全类名

```
com.oceano.web.serviceimpl.building.BuildingService.find
```

### 请求参数

| 参数 | 必填 | 说明 | 示例 |
| :--- | :--- | :--- | :--- |
| building | 否 | 楼盘信息属实体 |  |
| pageInfo | 是 | pageSize:当前显示条数       pageNum:当前页数              total:总条数 |  |
| createDesc | 否 | 创建时间排序 |  |
| newDesc | 否 | 开盘时间排序 |  |
| priceDesc | 否 | 均价排序 |  |

### 响应结果

| 名称 | 类型 | 必填 | 说明 |
| :--- | :--- | :--- | :--- |
| building | 实体 | 是 | 楼盘信息 |
| image | 实体 | 是 | 楼盘图片信息 |
| label | 实体 | 否 | 楼盘标签信息 |

### 调用示例

```
buildingService.find(building,pageInfo,createDesc,newDesc,priceDesc);
```

### 响应结果备注

```
[
{
building_id:楼盘id主键
building_name:楼盘名称
building_code:    楼盘编码
province_code    :省份编码
city_code    :市编码
area_code    区编码
source_name    来源名称 3d云设计;手工;八爪鱼
opening_time    开盘时间
building_time    交房时间
average_price    均价
building_place    楼盘地址
property_type    物业类型
project_features    项目特色
decoration_status    装修状况
building_developers    开发商
sales_status    销售状态
sales_place    售楼地址
saleing_model    在售户型
building_phone    售楼热线
building_priority    优先级
building_longitude    楼盘经度
building_latitude    楼盘纬度
building_label    标签id
greening_rate    绿化率
building_type    建筑类型
room_num    户数
elevator_num    电梯数
floor_status    楼层状况
traffic_status    交通状况
property_years    产权年限
building_area    建筑面积
creater_id    创建人id
create_date    创建时间
creater    创建人
modifier_id    修改人id
modifier    修改人
modify_date    修改时间
recent_opened    近期开盘
flats_desc    楼盘特点
province_name    省名
city_name    市名
area_name    区名

image:图片{
image_id图片id主键
image_name图片名称
image_cname图片原名
image_url图片url
source_id源id
source_type源类型 表名,如楼盘图片传入:t_building
image_size图片大小
image_type图片类型
creater_id创建人id
creater创建人
create_date创建时间
remark图片备注
}

Labels：标签{
label_id    标签id主键
label_name    标签名称
label_remark    标签备注
label_status    标签状态
source_type    标签源类型 表名,如楼盘图片传入:t_building
source_id    标签源id
source_parent_id    楼盘名称id
create_date    创建时间
}

}
]
```



