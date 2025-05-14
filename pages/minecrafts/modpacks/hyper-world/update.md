# DaoKongOS

## Pages

[(Home)](/)

[(Minecraft)](/pages/minecraft)

[(..)](./../hyper-world)

---

## Hyper World 整合包更新日志

### **V1.13.0 & UI UPDATE：**
> 2025/05/15

![图片](assets/update/images/IMG001.png)

- 将核心模组 Big Globe 更新到最新版本 (v5.0.1)
- 完全移除失落城市及方尖碑
- 添加 BiomesOPlenty 模组 (暂未实现任何生成兼容)
- 移除 Big Globe - Universal Ores Compatibility 模组
- 移除 Big Globe - Mythic Metals Compatibility 模组

本次更新删除了不兼容最新版 Big Globe 模组的两个兼容性模组，并添加了全局数据包 (强制/默认启用) 以替代原模组功能；

由于服务器端无法使用全局数据包模组，因此**请服务器端在创建/重新创建存档之前，复制`global_packs\required_data\`下所有文件到`world\datapacks\`下(根据实际存档路径修改)**，
否则服务器世界将不会生成部分模组的建筑、矿石等。

**!!! 升级时请注意备份存档 !!!**

由于 Big Globe v5.0.0 官方更新日志中提到 `Not backwards-compatible with existing worlds` (不兼容现有世界)，
因此在升级存档时**务必做好存档备份** (实际测试发现仅有部分世界会出现卡安全模式界面的问题)！


### **V1.12.5 & UI UPDATE：**
> 2025/04/11

- 将遥远地平线模组更新到最新版本 (2.3.2-b)
- 新增Universal Ores模组及其生成兼容
- 新增Towns and Towers模组及其生成兼容
- 新增When Dungeons Arise模组及其生成兼容
- 新增When Dungeons Arise Seven Sea模组
- 新增Unwrecked Ships模组及其生成兼容
- 新增Antique Trading Ship模组及其生成兼容
- 新增Create Structures模组及其生成兼容
- 新增Create Structures Arise模组
- (当前版本还没有制作任务线)

由于 Big Globe 模组 v1.12.0 版本改动大且不兼容任何已有数据包/兼容性模组，因此本版本暂不更新此模组。

### **V1.12.4 & UI UPDATE：**
> 2025/03/23

- 将部分模组更新到最新版本
- (当前版本还没有制作任务线)

### **V1.12.3 & UI UPDATE：**
> 2025/03/12

- 新增Carry On模组
- 新增First-person Model模组（默认禁用）
- (当前版本还没有制作任务线)

### **V1.12.2 & UI UPDATE：**
> 2025/03/12

- 修复启动游戏时因主菜单UI数组异常导致的游戏崩溃问题
- 默认禁用IPN模组的物品高亮
- 修改部分默认键位
- 更新遥远地平线模组至最新版（2.3.0-b）
- 深度清理Config文件夹下某些模组的残余数据文件
- (当前版本还没有制作任务线)

### **V1.12.1 UPDATE：**
> 2025/03/10

- 小优化

### **V1.12.0 & UI UPDATE：**
> 2025/03/08

- 主界面及UI优化
- (当前版本还没有制作任务线)

### **V1.12.0 UPDATE：**
> 2025/03/02

- 新增Chipped及ChippedExpress模组
- 正式公开发布


### **OLDER UPDATE：**
> 2025/01/??

更老的更新日志不再展示；

---

<script src="https://giscus.app/client.js"
        data-repo="YELANDAOKONG/DaoKongOS"
        data-repo-id="R_kgDOOCWX7g"
        data-category="Announcements"
        data-category-id="DIC_kwDOOCWX7s4CngzH"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="top"
        data-theme="preferred_color_scheme"
        data-lang="zh-CN"
        crossorigin="anonymous"
        async>
</script>

<script>
    var _hmt = _hmt || [];
    (function() {
        var hm = document.createElement("script");
        hm.src = "https://hm.baidu.com/hm.js?e467154e934c2dc14879fbb2df219013";
        var s = document.getElementsByTagName("script")[0];
        s.parentNode.insertBefore(hm, s);
    })();
</script>
