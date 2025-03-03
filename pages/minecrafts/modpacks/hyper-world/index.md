# DaoKongOS

## Pages

[(Home)](/)

[(Minecraft)](/pages/minecraft)

---

## Hyper World 整合包

这是一个基于Big Globe模组的水槽包；

```text
核心模组Big Globe将世界高度更改为2048，因此可以生成非常震撼的地形；

添加了沉浸飞行和指路石模组以便在如此大的世界中快速移动；

添加了遥远地平线和优化全家桶；

以及一系列装饰性的模组和农业相关的模组；

...
```

> 由于本整合包同时包含来自Modrinth和CurseForge的模组，因此无法在这两个平台上发布；
> 
> 如果发现网盘链接失效请到Github发起Issues。

~~MC百科(还没提交收录)~~ 

[下载](./downloads)

[更新日志](./update)

[问题反馈(Github)](https://github.com/YELANDAOKONG/McPackHyperWorld/)

~~更多内容请前往MC百科获取（还没提交收录~~

### 温馨提示&推荐配置

#### 服务器
1. 如果是面板服开服的话，建议服务器**使用4个及以上的CPU核心**以及**8GB及以上**的内存
2. 跑图和生成区块**很吃CPU**，建议提前使用Chunky命令预生成区块
3. Java 21

#### 客户端
1. 建议为MC分配12GB及以上内存（开DH的话需要更多）
2. 推荐光影Bliss
3. 在个人游玩过程中偶尔（一个月里面出现了四次）会出现因渲染器NULL导致的JVM崩溃，请注意存档备份
4. 存档有亿点点大，特别是开了DH的时候，**请注意磁盘空间**

### TODO List

- [ ] 为AE2添加配方兼容（现在加了模组但是没法获得模组物品）

### 已知不兼容&问题

#### 已知不兼容
- [格雷科技现代版](https://www.mcmod.cn/class/12850.html)

~~其他忘了（~~

#### 已知问题

- **机械动力的液态经验相关物品在思索时会引发游戏客户端崩溃，请注意。**
- 精妙模组的合成升级和REI的一键填充有小概率因为数组索引异常导致客户端游戏崩溃
- 建议使用默认的Big Globe生成器，Big Globe提供的Island生成器（“大地球：群岛”）可能不会生成模组的矿物

### 已修改的配方

#### 如何获得模组农作物/种子？

由于Big Globe大改了地形生成，很多模组的野生作物及种子无法通过正常方式获取；

~~做数据包添加生成兼容挺麻烦而且游戏里难找（~~

因此配方修改为：

- 种子可以通过机械动力的石磨磨草（包括模组中的）获得
- 野生农作物系列可以通过磨高草（包括模组中的）获得
- 高草现在可以用草（包括模组中的）合成

### Q&A

暂无

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
