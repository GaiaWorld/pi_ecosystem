# [pi库 生态](https://github.com/GaiaWorld/pi_ecosystem)

## [crates.io 的 pi库](https://crates.io/teams/github:gaiaworld:dev)

### 前端相关

|链接|维护者|概述|说明|
|--|--|--|--|
|[pi_ecs](https://github.com/GaiaWorld/pi_ecs)|wzjsun(suncy)|ECS 框架||
|[pi_render](https://github.com/GaiaWorld/pi_render)|moyy|新渲染|没推到 crates.io|
|[pi_path_finding](https://github.com/GaiaWorld/pi_path_finding)|baip|寻路算法：A*，JPS||
|[pi_spatialtree](https://github.com/GaiaWorld/pi_spatialtree)|wzjsun(suncy)|四叉、八叉树||
|[pi_math](https://github.com/GaiaWorld/pi_math)|wzjsun(suncy)|旧 数学库，逐渐 放弃 维护|没推到 crates.io|
|[pi_show](https://github.com/GaiaWorld/pi_show)|wzjsun(suncy)|旧 GUI，项目一直会用|没推到 crates.io|

### 后端相关

|链接|维护者|概述|说明|
|--|--|--|--|
|[pi_crypto](https://github.com/GaiaWorld/pi_crypto)|zuon|加密解密 & 数据签名|没推到 crates.io|
|[pi_vm](https://github.com/GaiaWorld/pi_vm)|zuon||没推到 crates.io|
|[pi_store](https://github.com/GaiaWorld/pi_store)|zuon|数据存储|没推到 crates.io|
|[pi_db](https://github.com/GaiaWorld/pi_db)|zuon|数据库|没推到 crates.io|
|[pi_net](https://github.com/GaiaWorld/pi_net)|zuon|网络 `mqtt` & `rpc` & `httpc`|没推到 crates.io|
|[pi_async](https://github.com/GaiaWorld/pi_async)|zuon|||
|[pi_async_file](https://github.com/GaiaWorld/pi_async_file)|zuon|||
|[pi_async_macro](https://github.com/GaiaWorld/pi_async_macro)|zuon|||
|[pi_lfstack](https://github.com/GaiaWorld/pi_lfstack)|zuon|||
|[pi_time](https://github.com/GaiaWorld/pi_time)|luob|||
|[pi_gray](https://github.com/GaiaWorld/pi_gray)|luob|||
|[pi_guid](https://github.com/GaiaWorld/pi_guid)|luob|基于时间的全局唯一id||
|[pi_guid64](https://github.com/GaiaWorld/pi_guid64)|luob|基于时间的全局唯一id||
|[pi_compress](https://github.com/GaiaWorld/pi_compress)|luob|封装各种压缩库|目前只封装了：`lz4`|
|[pi_timer](https://github.com/GaiaWorld/pi_timer)|baip|基于wheel的定时轮 实现的 定时器||
|[pi_rt_file](https://github.com/GaiaWorld/pi_rt_file)|zhuyijiang(zhuy)||
|[pi_rt_store](https://github.com/GaiaWorld/pi_rt_store)|zhuyijiang(zhuy)||
|[pi_file](https://github.com/GaiaWorld/pi_file)|zhuyijiang(zhuy)||
|[pi_weight_task](https://github.com/GaiaWorld/pi_weight_task)|zhuyijiang(zhuy)|任务池||

## 基础库

|链接|维护者|概述|说明|
|--|--|--|--|
|[pi_js_proxy_gen](https://github.com/GaiaWorld/pi_js_proxy_gen)|zuon|rust和js的自动生成代码库|之后不开源，没推到 crates.io|
|[pi_js_proxy_gen_macro](https://github.com/GaiaWorld/pi_js_proxy_gen_macro)|zuon|rust和js的自动生成代码库|之后不开源，没推到 crates.io|
|[pi_graph](https://github.com/GaiaWorld/pi_graph)|moyy||
|[pi_async_graph](https://github.com/GaiaWorld/pi_async_graph)|moyy||
|[pi_densevec](https://github.com/GaiaWorld/pi_densevec)|wzjsun(suncy)|管理slab分配id的数据结构，当id稀疏时候使用|配套 slab一起使用|
|[pi_ordmap](https://github.com/GaiaWorld/pi_ordmap)|wzjsun(suncy)|||
|[pi_any](https://github.com/GaiaWorld/pi_any)|wzjsun(suncy)|Trait Object的向下造型|当参数是多态，但是某种场景有需要具体类型的时候|
|[pi_atom](https://github.com/GaiaWorld/pi_atom)|wzjsun(suncy)|字符串原子|有很多相同字符串拷来拷去，比如CSS和语言关键字|
|[pi_base58](https://github.com/GaiaWorld/pi_base58)|wzjsun(suncy)|||
|[pi_bon](https://github.com/GaiaWorld/pi_bon)|wzjsun(suncy)|||
|[pi_cancel_timer](https://github.com/GaiaWorld/pi_cancel_timer)|wzjsun(suncy)|||
|[pi_cowlist](https://github.com/GaiaWorld/pi_cowlist)|wzjsun(suncy)|||
|[pi_cross_performance](https://github.com/GaiaWorld/pi_cross_performance)|wzjsun(suncy)|||
|[pi_debug_info](https://github.com/GaiaWorld/pi_debug_info)|wzjsun(suncy)|||
|[pi_deque](https://github.com/GaiaWorld/pi_deque)|wzjsun(suncy)|支持 从 中间 快速 插删 的 双端队列|如果不需要从中间插入和删除，可以考虑用`std`|
|[pi_dirty](https://github.com/GaiaWorld/pi_dirty)|wzjsun(suncy)|可以设置脏，查询脏的容器||
|[pi_dyn_uint](https://github.com/GaiaWorld/pi_dyn_uint)|wzjsun(suncy)|定义了一个分配id的工厂||
|[pi_enum_default_macro](https://github.com/GaiaWorld/pi_enum_default_macro)|wzjsun(suncy)|为枚举定义了Default trait的宏||
|[pi_ext_heap](https://github.com/GaiaWorld/pi_ext_heap)|wzjsun(suncy)|||
|[pi_flex_layout](https://github.com/GaiaWorld/pi_flex_layout)|wzjsun(suncy)|GUI-Flex布局||
|[pi_hash](https://github.com/GaiaWorld/pi_hash)|wzjsun(suncy)|Hash & 哈希表|内部实现已经封装了`std`的哈希表，并且内置高效的hash算法，并且做了x86和x64平台的开关|
|[pi_hash_value](https://github.com/GaiaWorld/pi_hash_value)|wzjsun(suncy)|||
|[pi_heap](https://github.com/GaiaWorld/pi_heap)|wzjsun(suncy)|支持 删除 和 更新 的 二叉堆|如果没有 删除 和 更新操作，可以考虑用`std`|
|[pi_idtree](https://github.com/GaiaWorld/pi_idtree)|wzjsun(suncy)|||
|[pi_listener](https://github.com/GaiaWorld/pi_listener)|wzjsun(suncy)|||
|[pi_local_timer](https://github.com/GaiaWorld/pi_local_timer)|wzjsun(suncy)|||
|[pi_lru](https://github.com/GaiaWorld/pi_lru)|wzjsun(suncy)|||
|[pi_map](https://github.com/GaiaWorld/pi_map)|wzjsun(suncy)|||
|[pi_null](https://github.com/GaiaWorld/pi_null)|wzjsun(suncy)|||
|[pi_pointer](https://github.com/GaiaWorld/pi_pointer)|wzjsun(suncy)|||
|[pi_res](https://github.com/GaiaWorld/pi_res)|wzjsun(suncy)|资源管理||
|[pi_res_mgr](https://github.com/GaiaWorld/pi_res_mgr)|wzjsun(suncy)|同类型数据管理|需要自己管理空闲块 & 绕过rust引用|
|[pi_rsync](https://github.com/GaiaWorld/pi_rsync)|wzjsun(suncy)|||
|[pi_share](https://github.com/GaiaWorld/pi_share)|wzjsun(suncy)|rc & arc 封装|需要统一封装场景：单线程 & 多线程|
|[pi_sinfo](https://github.com/GaiaWorld/pi_sinfo)|wzjsun(suncy)|||
|[pi_slab](https://github.com/GaiaWorld/pi_slab)|wzjsun(suncy)|||
|[pi_slot_deque](https://github.com/GaiaWorld/pi_slot_deque)|wzjsun(suncy)|||
|[pi_slot_wheel](https://github.com/GaiaWorld/pi_slot_wheel)|wzjsun(suncy)|||
|[pi_static_map](https://github.com/GaiaWorld/pi_static_map)|wzjsun(suncy)|||
|[pi_ucd](https://github.com/GaiaWorld/pi_ucd)|wzjsun(suncy)|unicode快速查询的函数|比如可以查询某个point是不是中文
|[pi_util](https://github.com/GaiaWorld/pi_util)|wzjsun(suncy)|||
|[pi_weight](https://github.com/GaiaWorld/pi_weight)|wzjsun(suncy)|||
|[pi_wheel](https://github.com/GaiaWorld/pi_wheel)|wzjsun(suncy)|||
|[pi_wtree](https://github.com/GaiaWorld/pi_wtree)|wzjsun(suncy)|||
|[pi_wy_rng](https://github.com/GaiaWorld/pi_wy_rng)|wzjsun(suncy)|||

## 不计划 维护

|链接|维护者|说明|
|--|--|--|
|[pi_apm](https://github.com/GaiaWorld/pi_apm)|zuon|没人使用，没推到 crates.io|
|[pi_future](https://github.com/GaiaWorld/pi_future)|zuon|没人使用，没推到 crates.io|
|[pi_handler](https://github.com/GaiaWorld/pi_handler)|zuon|没人使用，没推到 crates.io|
|[pi_worker](https://github.com/GaiaWorld/pi_worker)|zuon|没人使用，没推到 crates.io|
|[pi_ecs_derive_old](https://github.com/GaiaWorld/pi_ecs_derive_old)|wzjsun(suncy)|暂时维护，pi_show还在使用|
|[pi_ecs_old](https://github.com/GaiaWorld/pi_ecs_old)|wzjsun(suncy)|暂时维护，pi_show还在使用|
|[pi_flex_layout_old](https://github.com/GaiaWorld/pi_flex_layout_old)|wzjsun(suncy)|暂时维护，pi_show 还在使用|
|[pi_data_view](https://github.com/GaiaWorld/pi_data_view)|wzjsun(suncy)|暂时维护，pi_show 还在使用|
|[pi_adler32](https://github.com/GaiaWorld/pi_adler32)|不维护||
|[pi_bincode](https://github.com/GaiaWorld/pi_bincode)|不维护||
|[pi_hashmap](https://github.com/GaiaWorld/pi_hashmap)|不维护|没推到 crates.io|
|[pi_idtree_old](https://github.com/GaiaWorld/pi_idtree_old)|不维护|没推到 crates.io|
|[pi_map_old](https://github.com/GaiaWorld/pi_map_old)|不维护|没推到 crates.io|
|[pi_slab_old](https://github.com/GaiaWorld/pi_slab_old)|不维护|没推到 crates.io|
|[pi_fx_hashmap](https://github.com/GaiaWorld/pi_fx_hashmap)|不维护|没推到 crates.io|
|[pi_wy_hash](https://github.com/GaiaWorld/pi_wy_hash)|不维护|没推到 crates.io|
|[pi_task_pool](https://github.com/GaiaWorld/pi_task_pool)|不维护|没推到 crates.io|
|[pi_lib](https://github.com/GaiaWorld/pi_lib)|废弃|js项目|
|[pi_sys](https://github.com/GaiaWorld/pi_sys)|废弃|js项目|
|[pi_p2p](https://github.com/GaiaWorld/pi_p2p)|废弃|rust项目|
|[pi_base](https://github.com/GaiaWorld/pi_base)|废弃|js项目|
|[pi_front](https://github.com/GaiaWorld/pi_front)|废弃|js项目|
|[pi_tools](https://github.com/GaiaWorld/pi_tools)|废弃|js项目|
|[pi_serv](https://github.com/GaiaWorld/pi_serv)|废弃|rust项目，已经移到 Github|
|[pi_msdf_tool](https://github.com/GaiaWorld/pi_msdf_tool)|废弃|js项目|

## 附录：内网 GitLab 项目，不会 发布到 npm 或 crates.io

#### 游戏

|链接|维护者|概述|说明|
|--|--|--|--|
|[pi_demo](http://192.168.31.241:10082/tech/pi_demo)|limh||js项目|
|[pi_build](http://192.168.31.241:10082/tech/pi_build)|yuq||js项目|
|[pi_sys](http://192.168.31.241:10082/tech/pi_sys)|yuq||js项目|
|[pi_utils](http://192.168.31.241:10082/tech/pi_utils)|limh||js项目|
|[pi_commom](http://192.168.31.241:10082/tech/pi_common)|limh||js项目|
|[pi_pt](http://192.168.31.241:10082/tech/pi_pt)|luob||js项目|

#### 服务器端

|链接|维护者|概述|说明|
|--|--|--|--|
|[pi_logger](http://192.168.31.241:10082/tech//pi_logger)|luob||rust项目|
|[pi_v8](http://192.168.31.241:10082/tech/pi_v8)|zuon||rust项目|
|[pi_serv](http://192.168.31.241:10082/tech/pi_serv)|zuon||rust项目|
|[pi_serv_lib](http://192.168.31.241:10082/tech/pi_serv_lib)|zuon||rust项目|
|[pi_serv_builtin](http://192.168.31.241:10082/tech/pi_serv_builtin)|zuon||rust项目|
|[pi_serv_ext](http://192.168.31.241:10082/tech/pi_serv_ext)|zuon||rust项目|
|[pi_core](http://192.168.31.241:10082/tech/pi_core)|zuon||rust项目|
|[pi_core_lib](http://192.168.31.241:10082/tech/pi_core_lib)|zuon||rust项目|
|[pi_core_builtin](http://192.168.31.241:10082/tech/pi_core_builtin)|zuon||rust项目|

#### 渲染 & 游戏底层

|链接|维护者|概述|说明|
|--|--|--|--|
|[babylon](http://192.168.31.241:10082/tech/babylon)|baip|对 Babylon 官网的 Clone 和 修改|js项目，包括 6边形网格 和 Unity导出插件|
|[pi_babylon](http://192.168.31.241:10082/tech/pi_babylon)|baip||js项目|
|[pi_babylon_demo](http://192.168.31.241:10082/tech/pi_babylon_demo)|baip|pi_babylon 和 Babylon 的 Demo|js项目|
|[pi_spine](http://192.168.31.241:10082/tech/pi_spine)|baip||js项目|
|[pi_animation](http://192.168.31.241:10082/tech/pi_animation)|baip|动画模块|js项目|
|[pi_animation_rust](http://192.168.31.241:10082/tech/pi_animation_rust)|baip|动画模块|rust项目|

#### 平台：Android & iOS & Windows

|链接|维护者|概述|说明|
|--|--|--|--|
|[pi_packer](http://192.168.31.241:10082/tech/pi_packer)|yuq||js项目|
|[pi_app](http://192.168.31.241:10082/tech/pi_core_app)|zhuy||rust项目|
|[app_start](http://192.168.31.241:10082/tech/app_start)|zhuy||rust项目|
|[pi_android](http://192.168.31.241:10082/tech/pi_android)|moyy||Java项目|
|[pi_ios](http://192.168.31.241:10082/tech/pi_ios)|moyy||Swift项目|[surfman](http://192.168.31.241:10082/tech/surfman)|zhuy|网上对应库的维护，跨平台的egl 绑定|android 添加 swappy，添加ios eagl 绑定

#### 修改的 第三方库

处于某些原因，需要 fork 一份 第三方库的源码 过来，自己维护

|链接|维护者|概述|说明|
|--|--|--|--|
|[rusty_v8](http://192.168.31.241:10082/tech/rusty_v8)|zhuy|v8库的rust封装|之所以自己维护，是为了构建iOS平台，以及 解决 Android 平台的构建错误|
|[winit](http://192.168.31.241:10082/tech/winit)|zhuy|跨平台的窗口和事件提供|Android 添加虚拟键盘唤起和隐藏； exe添加自定义光标，iOS适配数据缓存，绕过某些接口必须在主线程上调用||
|[minstant](http://192.168.31.241:10082/tech/minstant)|zhuy|获取时间|适配iOS无法编译问题|
|[rodio](http://192.168.31.241:10082/tech/rodio)|zhuy|音频播放库|适配 Android 播放切换问题|
|[rust-crypto](http://192.168.31.241:10082/tech/rust-crypto)|zhuy|加密库|适配iOS无法编译链接问题||
|[font_kit](http://192.168.31.241:10082/tech/font_kit)|zhuy|字体库|freetype_sys 的 canvas2d 封装|
|[freetype_sys](http://192.168.31.241:10082/tech/freetype_sys)|zhuy|C代码的Rust绑定|从官网的2.6.5升级到2.10.4 & 添加了更多的Rust接口||
