---
icon: material/library
---

# 服务器简介
 我们致力于发展一个和谐共建的MC社区，打造一个特色原创的MC服务器，在这里你可以体验原版生存内容，并且我们将尽量保持与原版的版本进行同步，腐竹经过多年的研发已经全面完成服务器基本建设，开发了领地系统、菜单系统、经济系统、脚本引擎等多种自研系统，拥有完善的交互系统，无需命令即可畅玩各种内容。服务器不仅有生存服，还有小游戏，空岛服 等特色服务器，后续也将一起同步更新。我们后续还会研发更多功能给大家，欢迎大家进入光梦尽情探索！
# 基本信息

=== "服务器IP"

    ```
    herra.fun
    ```
=== "官方网站"

    ```
    https://www.herra.fun
    ```
=== "论坛网站"

    ```
    https://bbs.herra.fun
    ```
=== "文档网站"

    ```
    https://wiki.herra.fun
    ```
=== "QQ群"

    ```
    936893336
    ```



# 核心玩法
| 玩法 | 描述 |
|:----:|:----:|
| 生存 | 分为生存一区和生存二区，一区为原版生存，二区引入多种新元素，轻量向RPG |
| 空岛 | 有经典的空岛生存，单方块空岛，海岛生存，矿洞生存，支持多人同岛，<span class="heimu" title="你知道的太多了">俗称和好友一块岛doge</span> |
| 副本 | 单人独闯或和好友一起围殴Boss，获得丰厚战利品 |
| 创造 | 领取无限的地皮，发挥自己的创造力，成为创世神 |
| 小游戏 | 生存太无聊了副本太肝了创造不会，那就来玩玩小游戏吧!  |



<head>
<body>
<div id="tcomment"></div>
<!-- 引入VUE -->
<script src="https://unpkg.com/vue@2.6.14/dist/vue.min.js"></script>
<!-- 引入样式 -->
<script src="https://unpkg.com/element-ui@2.15.6/lib/index.js"></script>
<!-- 引入组件库 -->
<link rel="stylesheet" href="https://unpkg.com/element-ui@2.15.6/packages/theme-chalk/lib/index.css">
<script src="https://cdn.jsdelivr.net/npm/twikoo@1.6.44/dist/twikoo.min.js"></script>
<script>
twikoo.init({
  envId: 'https://twikoo-theta-one-49.vercel.app', // 腾讯云环境填 envId；Vercel 环境填地址（https://xxx.vercel.app）
  el: '#tcomment', // 容器元素
  // region: 'ap-guangzhou', // 环境地域，默认为 ap-shanghai，腾讯云环境填 ap-shanghai 或 ap-guangzhou；Vercel 环境不填
  // path: location.pathname, // 用于区分不同文章的自定义 js 路径，如果您的文章路径不是 location.pathname，需传此参数
  // lang: 'zh-CN', // 用于手动设定评论区语言，支持的语言列表 https://github.com/twikoojs/twikoo/blob/main/src/client/utils/i18n/index.js
})
</script>  
<script>
    /* 复制提醒 */
document.addEventListener("copy",function(e){
    new Vue({
        data:function(){
            this.$notify({
                title:"嘿！复制成功",
                message:"若要转载请务必保留原文链接！爱你呦~",
                position: 'bottom-right',
                offset: 50,
                showClose: false,
                type:"success"
            });
            return{visible:false}
        }
    })
})
</script>
</body>
</head>