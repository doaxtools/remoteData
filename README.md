# remoteData
<!--写法规则及示例：
规则: 所有内容必须写在“<span id=XXXXstart>”和“</span><span id=XXXXend></span>”之间('XXXX'为remotedata、remoteoptionname、remotetext、remotetablearr、remoteremark、remotesize、remoterowspan、remotecolspan、remotefontweight)
remotedata: 所有数据都应该包含在remotedata中，程序会最先抓取remotedata中的所有数据，再分别处理。
remoteoptionname: 在小程序的其它数据模块新增一个radio选项，该部分内容即为选项名。
remotetext: 新增radio项的文本内容，位于表格上方。
remotetablearr: 新增radio项的的table数据，如[1,2,3],[4,5,6]，创建一个两行三列的表格，第一行为1,2,3，第二行为4,5,6。
remoteremark: 新增radio项的备注内容，位于表格下方。
remotesize: 14，设置表格中数字大小为14px
remoterowspan: [0,1,5]，用于合并单元格，将第0行第1列的表格向下扩展5个单元格
remotecolspan: [1,2,4]，用于合并单元格，将第1行第2列的表格向右扩展4个单元格
remotefontweight: [1,2]，将第1行第2列的表格中字体加粗；remotefontweight: [1]，将第1行整行加粗；remotefontweight: [,3]，将第3列整列加粗；
-->
<span id=remotedatastart>
<span id=remoteoptionnamestart>排位分数</span><span id=remoteoptionnameend></span>
<span id=remotetextstart><br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2022/06/09“珠宝之夜的愿望～羁绊挑战赛篇～”<a title="点击前往百度贴吧【22.06.09魅力排位】全记录" style="text-decoration:none;color:blue" href="#" rel="external nofollow" onclick="useDefBrowser('https://tieba.baidu.com/p/7872576277')">分数线</a>(单位:万)</span><span id=remotetextend></span>
<span id=remotetablearrstart>
[23:00分数线,100,400,800,2000,5000,6500],
[周四,1303,687,470,261,100,67],
[周五,6181,2800,1681,799,329,233],
[周六,,,,,,],
[周日,,,,,,],
[周一,,,,,,],
[周二,,,,,,],
[周三,,,,,,]
</span><span id=remotetablearrend></span>
<span id=remoteremarkstart>&nbsp;&nbsp;&nbsp;&nbsp;每日23:00更新数据（<b>注意</b>：由于远程数据放在github上，国内github网站非常不稳定，所以此页面有可能会时有时无。建议更新至3.10之后的版本）<br><br><br><br></span><span id=remoteremarkend></span>
<span id=remotesizestart>14</span><span id=remotesizeend></span>
<span id=remotefontweightstart>[0]</span><span id=remotefontweightend></span>
</span><span id=remotedataend></span>
