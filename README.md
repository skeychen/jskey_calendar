jskey_calendar
==============
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

html日历选择控件

==============
$jskey.calendar.show({param}) 好用的html日历选择控件

各种参数简介如下：
```html
/**
 * 调用方法：$jskey.calendar
 * 调用方式：$jskey.calendar.show(args1, args2);
 * 1、参数args1：目前支持参数：input对象 或 'input的ID'
 * 2、参数args2：默认为{}
 * 目前支持参数：
 * 其中日历类中的参数与其默认值：{skin:"default",min:"yyyy-MM-dd HH:mm:ss",max:"yyyy-MM-dd HH:mm:ss",lang:0,format:"yyyy-MM-dd HH:mm:ss",left:0,top:0,simple:"yyyy-MM-dd HH:mm:ss"}
 * 日期选择显示格式：yyyy→年，MM→月，dd→天，HH→24小时制，mm→分钟，ss→秒
 * @param object/id args1替代参数：{object:input对象} 或 {id:'input的ID'}上面未列出
 * @param skin String "default" 值为themes/calendar目录中对应的样式文件夹
 * @param show String 取值 "yyyy-MM-dd HH:mm:ss" 或 "yyyy-MM-dd HH:mm" 或 "yyyy-MM-dd HH" 或 "yyyy-MM-dd" 或 "yyyy-MM" 或 "yyyy"
 * @param min String "yyyy-MM-dd HH:mm:ss"，可选最小值，默认"0100-01-01 00:00:00"
 * @param max String "yyyy-MM-dd HH:mm:ss"，可选最大值，默认"9999-12-31 23:59:59"
 * @param lang Integer "zh-CN"(简体中文)|"en-US"(英语) 可自由扩充，参考源码中的$jskey.$CalendarLang["zh-CN"]属性
 * @param left Integer 相对X坐标,相对于文本框的横向偏移量
 * @param top Integer 相对Y坐标,相对于文本框的纵向偏移量
 * @param format String "yyyy-MM-dd HH:mm:ss w W" 格式（区分大小写）：yyyy→年，MM→月，dd→天，HH→24小时制，mm→分钟，ss→秒，w→周几，W→当年的第几周(第一周不足七天时也当第一周，计算方式目前为1月1日为第一周开始，且周日为新的一周开始，即一年首尾两周可能不是全周)
 */
```


下面是比较全面的演示及说明，相关使用请点击下面网址，并使用"网页源代码"查看吧，就不另写说明了，麻烦
* [示例](https://rawcdn.githack.com/skeychen/jskey_calendar/master/jskey_calendar.html)