========================接口
以下参照天津============ 

api/property/real-survey-photos

----
图片
api/property/detail-edit

----编辑房源 


新增字段（跟天津字段名称相同）：
PropertyAttributeKeyIds---房源属性
HouseType---房型：室-厅-卫-阳台
PropertyAssess--出租点评
PropertySaleAssess--出售点评

房源点评对应权限：

    房源点评 新增 - 无          Property.Expand.Set-None
    房源点评 新增 - 全部        Property.Expand.Set-All
    房源点评 新增 - 本人        Property.Expand.Set-MySelf
    房源点评 新增 - 本部        Property.Expand.Set-MyDepartment

    房源点评 修改 - 无          Property.Expand.Update-None
    房源点评 修改 - 全部        Property.Expand.Update-All
    房源点评 修改 - 本人        Property.Expand.Update-MySelf
    房源点评 修改 - 本部        Property.Expand.Update-MyDepartment

    房源点评 删除 - 无          Property.Expand.Delete-None
    房源点评 删除 - 全部        Property.Expand.Delete-All
    房源点评 删除 - 本人        Property.Expand.Delete-MySelf
    房源点评 删除 - 本部        Property.Expand.Delete-MyDepartment

实勘权限：


      实勘-编辑-无      Property.RealSurvey.Modify-None
       
      实勘-编辑-本人    Property.RealSurvey.Modify-MySelf
      
      实勘-编辑-本部    Property.RealSurvey.Modify-MyDepartment

      实勘-编辑-全部    Property.RealSurvey.Modify-All


      实勘-删除-无      Property.RealSurvey.Delete-None

      实勘-删除-本人    Property.RealSurvey.Delete-MySelf

      实勘-删除-本部    Property.RealSurvey.Delete-MyDepartment

      实勘-删除-全部    Property.RealSurvey.Delete-All



api/property/property-edit---

修改房源

api/advert/online-permissions---



判断发布房源权限

api/external/exist-property-advert

---

验证是否发布过广告
 

api/External/batch-create-property-advert

--发布房源
api/property/real-survey-rule---获取实勘图片规则
api/property/delete-realSurvey-by-keyId---

删除实勘
api/property/upload-real-survey---



上传实勘

         请求参数（新增字段）：

        /// 家电详细信息列表---Electrics （数组）
         数组元素字段：
        /// 家电KeyId  ---- ElectricKeyId
        /// 家电名称   ---- ElectricName
        /// 家电数量   ---- ElectricCount
        /// 家电品牌   ---- ElectricBrand 

      
        /// 家具详细信息列表---Furnitures（数组）
         数组元素字段：
        /// 家具KeyId  ---- FurnitureKeyId
        /// 家具名称   ---- FurnitureName
        /// 家具数量   ---- FurnitureCount
        /// 家具品牌   ---- FurnitureBrand

        /// 实勘点评---RealSurveyComment


api/customer/takesees---

带看列表

api/property/war-zone
---房源列表


请求参数：

HasPropertyExands--房源点评
HasNoPropertyExands--暂无房源点评
HasMyAdm--我的放盘
HasMyNoAdm--未放盘

  

========================系统参数（参照天津）
房源属性：107 

房型:125(几室几厅几卫) --房源格局                                                     
                                                              

家具:37


家电:36

========ADM接口=========

接口名称	描述
api/external/advert-photos	获取广告管理中图片列表
api/external/batch-set-hot	设置笋盘
api/external/batch-cancel-hot	取消笋盘
api/advert/property-detail	获取广告详情
api/external/batch-create-property-advert	创建广告
api/external/batch-modify-property-advert	编辑广告
api/external/get-estate-names	获取广告管理列表所有楼盘
api/external/exist-register-trust-property	获取业主委托
api/advert/properties	获取广告管理广告列表
api/advert/online-permissions	获取上架权限
api/advert/batch-online	批量上架
api/advert/batch-offline	批量下架
api/advert/batch-remove	批量删除
api/advert/batch-refresh	批量刷新


   




