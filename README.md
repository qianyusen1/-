天气api使用的是和风天气api,目前仅能显示3日内的天气(开发者正在认证中，可显示7日内天气)

步骤：1. 修改Page->index->index.js
```
wx.request({
           url: 'https://free-api.heweather.com/s6/weather/now?location=' + data.longitude + ',' + data.latitude + '&key=xxx',
            success:function(res){}
```
2. 将xxx改为你的和风天气的key即可使用

##天气图标

   - 晴
   - 多云
   - 阴
   - 阵雨
   - 雷阵雨	
   - 小雨
   - 中雨	
   - 大雨	
   - 暴雨
   - 大暴雨	
   - 小雪	
   - 中雪	
   - 大雪
   - 暴雪
   - 雨夹雪	
   - 雾
   - 霾
   - 沙尘暴	
