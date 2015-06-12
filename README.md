### Commonplug-ins
#Common plug-in list

---------
select模拟器(联动)
插架介绍：

LinkageSelect 模拟联动select器(ajax请求,多项联动)<br/>
该插件需要初始一级列表内容<br/>
width为自适应<br/>
参数：<br/>
id(容器ID)<br/>
evt(事件类型 click)<br/>
ajaxUrl(ajax数据请求地址)<br/>
type(ajax type请求方式) 默认GET<br/>
inputId(后端接入数据提交inputId号默认txt_put)例如：这里id号是txt_put<br/>
defTxt(是否有自定义提示默认值)例如：defTxt:'请选择项目'<br/>
请注意：如果defTxt无值，首项内容展示第一条内容，二级开始展示提示选择信息，例如：请选择<br/>
defKey(默认值id标示，默认为-1)例如：defKey:"-1"<br/>
dateId(后端数据ID) 例如：这里是dateId:'dateid'<br/>
datelayerRoot(顶层级定义[生成层级标注号，默认datelayer,0级别开始]) //html首层datelayer对应<br/>
cssClass(hover,btn样式转换class) 例如：.menBox ul .hovers{background:#000;}<br/>
callBack回调函数(可以表单提交，也可不在callBack外做操作)<br/>
提交input[type='hiden']隐藏域各值以,分隔name值可以自行设置<br/>
后端请求需要返回的数据格式:<br/>
{"父id":{"子id":"内容","子id":"内容","子id":"内容"}},以这种格式为好，如果许改变，需前端协调修改<br/>
