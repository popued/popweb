title: 关于我们
date: 2014-07-30 13:30:09
---
#我们是popued团队

我们来自hznu，我们热爱编程，喜欢折腾各种技术，专注web，ued开发。

###成立于2014,3月份
<script type="text/javascript" src="http://api.map.baidu.com/api?v=2.0&ak=FFff772938d158843021666960b2a4ed"></script>
<style type="text/css">
#allmap {width: 700px;height: 500px;overflow: hidden;margin:0;}
</style>
<div id="allmap"></div>
<em>hznu's map</em>
<script type="text/javascript">
// 百度地图API功能
var map = new BMap.Map("allmap");            // 创建Map实例
map.centerAndZoom(new BMap.Point(120.015798,30.293694), 13);
var local = new BMap.LocalSearch(map, {
  renderOptions:{map: map}
});
local.search("杭州师范大学仓前校区");
//map.addControl(new BMap.NavigationControl());  //添加默认缩放平移控件
map.addControl(new BMap.NavigationControl({anchor: BMAP_ANCHOR_BOTTOM_LEFT, type: BMAP_NAVIGATION_CONTROL_PAN}));  //左下角，仅包含平移按钮
map.addControl(new BMap.NavigationControl({anchor: BMAP_ANCHOR_BOTTOM_RIGHT, type: BMAP_NAVIGATION_CONTROL_ZOOM}));  //右下角，仅包含缩放按钮
map.addControl(new BMap.MapTypeControl({mapTypes: [BMAP_NORMAL_MAP,BMAP_HYBRID_MAP]}));     //2D图，卫星图

map.addControl(new BMap.MapTypeControl({anchor: BMAP_ANCHOR_TOP_LEFT}));    //左上角，默认地图控件
map.setCurrentCity("杭州");   //由于有3D图，需要设置城市哦
</script>