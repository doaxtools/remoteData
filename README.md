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
<span id=remoteoptionnamestart>重要更新</span><span id=remoteoptionnameend></span>
<span id=remotetextstart><br><br>&nbsp;&nbsp;&nbsp;&nbsp;v3.11(测试版)&nbsp;&nbsp;2022/06/16&nbsp;&nbsp; @卑微小萌新&nbsp;&nbsp;<br>更正了声援板中异属性SR经验值为8960。<br>使用免费空间替代github的功能，替换了所有github相关代码<br>在其它数据模块新增了衣服推荐项<br>v3.12&nbsp;&nbsp; 2022/06/19&nbsp;&nbsp;@卑微小萌新<br>更改整体配色方案，新版本整体颜色较旧版本偏亮<br>调整部分表格布局，使其垂直居中<br>略调整了悬浮文字位置<br>支持不同版本对应推送不同的远程数据<br>修复3.11版本点击下拉菜单可能导致程序闪退的BUG<br><b>注意</b>：3.10及之前的版本不再提供远程数据支持，请尽快更新至3.12版本！</span><span id=remotetextend></span>
<span id=remotetablearrstart></span><span id=remotetablearrend></span>
<span id=remoteremarkstart></span><span id=remoteremarkend></span>
<span id=remotesizestart>14</span><span id=remotesizeend></span>
<span id=remotefontweightstart></span><span id=remotefontweightend></span>
</span><span id=remotedataend></span>
