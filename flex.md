#flex弹性布局盒模型
##设置弹性盒模型
1. display:flex(新版)
2. display:-webikit-box; (旧版)
##flex容器
1. 项目排列的方向
  1.1 row从左到右排列（默认）
  1.2 row-reverse 从右到左
  1.3 column 从上到下
  1.4 column-reverse 从下到上

       flex-direction:row | row-reverse |column |column-reverse

  * horizontal 水平方向
  * vertical 垂直方向

        -webkit-box-orient:horizontal | vertical

  * normal 顺序正常
  * reverse 反向

        -weblit-box-direction:normal | reverse

2. 项目包裹方式
  2.1 nowrap 不换行（默认）
  2.2 wrap容器如果不足以放下项目，自动换行到下行
  2.3 wrap-reverse 容器如果不足以放下项目,自动换到上一行

        flex-wrap:nowrap | wrap | wrap-reverse

3. 项目水平对齐方式
  3.1 flex-strat 左对齐
  3.2 flex-end 右对齐
  3.3 center 中对齐
  3.4 space-between 两端对齐
  3.5 space-around 每个项目两侧的间隔相等

        justify-content:flex-start | flex-end |

