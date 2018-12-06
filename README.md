# MeiTuanCinemaSmartChoose
模拟美团app推荐座位算法.
# 使用
clone本项目，然后npm install后直接npm start启动开发服务器即可
# 简介
![操作界面](https://github.com/houzisbw/MeiTuanCinemaSmartChoose/blob/master/img/1.png)
# 算法流程
(1)推荐算法首先从影院中间排数的后一排的正中间开始搜索<br>
(2)优先向后排方向进行搜索，后排搜索完成后再从中间起始位置向前排搜索 <br>
(3)后排搜索完成后，每一行都会有一个结果(每一行的结果是最靠近中轴线的那一组座位)，取这些结果中距离中轴线最小的那个结果作为最终结果，而不是距离屏幕越近的<br>
(4)只考虑并排且连续的座位，不能不在一排或者一排中间有分隔，比如过道之类的 
(5)一组选定的座位左右2侧不能留下单个空座位



