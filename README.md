# vue-drawer

#### 介绍
vue组件：抽屉

#### 软件架构
软件架构说明


#### 安装教程

1. xxxx
2. xxxx
3. xxxx

#### 使用说明

/**
* @title 原生vue抽屉组件
* @author 易建伟
* @time 2019-07-04
*
* ------------使用-------------
* 全局注册
* import drawer from './drawer'
* Vue.component('drawer', drawer)
*
* 方法或属性
*  Attributes || Events || slot       说明                                   类型                   可选值                    默认值
* ------------------------------------------------------ Attributes -------------------------------------------
*     visible.sync            是否显示 Dialog，支持 .sync 修饰符            boolean                   ——                      false
*      title                         标题名称                              string                                            标题
*      headerShow                标题头部是否显示                          boolean                    ——                      true
*   header-background            标题头部背景颜色                          string                     ——                       #fff
*     closeBtnShow                关闭按钮是否显示                          boolean                     ——                    true
*     title-color                 标题头部标题                             string                    ——                        #000
*   main-background               内容背景颜色                             string                    ——                       #fff
*   footerShow                    底部是否显示                             boolean                    ——                       false
*   footer-height                   底部高度                               string                    ——                        60px
*   footer-background            底部背景颜色                              string                     ——                        #fff
*       width                       侧栏宽度                               string                    ——                       500px
*       align                      侧栏位置                               string                  right,left                 right
*   close-on-click-modal       点击遮罩层是否关闭                           boolean                   ——                       false
* ------------------------------------------------------ Events -------------------------------------------
*      open                    Dialog 打开的回调
*      opened                  Dialog 打开动画结束时的回调
*      close                 Dialog 关闭的回调
*      closed                  Dialog 关闭动画结束时的回调
* ------------------------------------------------------ slot  -------------------------------------------
*      footer                  Dialog 按钮操作区的内容
* 例子 (简单）
* <drawer
*   title="测试"
*   :visible.sync='dialogVisible'
*   width="500px"
*   close-on-click-modal
* >
* </drawer>
* 例子（完整属性）
* <drawer
*   :visible.sync='dialogVisible'
*   :headerShow="true"
*   header-background="#f5f5f5"
*   title-color="#000"
*   main-background="#EBEEF5"
*   :footerShow="true"
*   footer-height="60px"
*   footer-background="#f5f5f5"
*   width="500px"
*   align="right"
*   close-on-click-modal
*   @close="ce"
*   @closed="ce"
*   @open="ce"
*   @opend="ce"
*    >
*   <!--内容区-->
*   <div>
*     <p>内容</p>
*   </div>
*
*   <!--这里是底部-->
*   <div slot="footer">
*     <p>底部</p>
*   </div>
* </drawer>
*/
#### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request

