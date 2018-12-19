# JMeter与CPTS字段对应关系<a name="cpts_01_0048"></a>

CPTS支持JMeter脚本导入及自动切换。JMeter字段与CPTS字段的对应关系如[表1](#table9157104912287)。

**表 1**  JMeter字段与CPTS字段对应关系

<a name="table9157104912287"></a>
<table><thead align="left"><tr id="row3157949102811"><th class="cellrowborder" colspan="2" valign="top" id="mcps1.2.5.1.1"><p id="p64711233112911"><a name="p64711233112911"></a><a name="p64711233112911"></a>Jmeter字段</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.2.5.1.2"><p id="p1015784910288"><a name="p1015784910288"></a><a name="p1015784910288"></a>CPTS字段</p>
</th>
<th class="cellrowborder" valign="top" id="mcps1.2.5.1.3"><p id="p161571249152817"><a name="p161571249152817"></a><a name="p161571249152817"></a>参数解释</p>
</th>
</tr>
</thead>
<tbody><tr id="row121571149102812"><td class="cellrowborder" rowspan="3" valign="top" width="22.87771222877712%" headers="mcps1.2.5.1.1 "><p id="p171573496286"><a name="p171573496286"></a><a name="p171573496286"></a>线程组</p>
</td>
<td class="cellrowborder" valign="top" width="24.297570242975702%" headers="mcps1.2.5.1.1 "><p id="p1515718490284"><a name="p1515718490284"></a><a name="p1515718490284"></a>名称</p>
</td>
<td class="cellrowborder" valign="top" width="27.757224277572245%" headers="mcps1.2.5.1.2 "><p id="p16157249102813"><a name="p16157249102813"></a><a name="p16157249102813"></a>事务名称</p>
</td>
<td class="cellrowborder" rowspan="3" valign="top" width="25.067493250674932%" headers="mcps1.2.5.1.3 "><p id="p856910382319"><a name="p856910382319"></a><a name="p856910382319"></a>与其下面的HTTP请求组成一个事务。</p>
<p id="p34232588308"><a name="p34232588308"></a><a name="p34232588308"></a>读取不到有效值时，默认并发个数为1，持续时间为1分钟。</p>
</td>
</tr>
<tr id="row11157949132815"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p915714491281"><a name="p915714491281"></a><a name="p915714491281"></a>线程数</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p315714912281"><a name="p315714912281"></a><a name="p315714912281"></a>测试任务并发个数</p>
</td>
</tr>
<tr id="row1815724962818"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p19157204913289"><a name="p19157204913289"></a><a name="p19157204913289"></a>持续时间</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p1515744932815"><a name="p1515744932815"></a><a name="p1515744932815"></a>测试任务持续时间</p>
</td>
</tr>
<tr id="row5157549202815"><td class="cellrowborder" rowspan="2" valign="top" width="22.87771222877712%" headers="mcps1.2.5.1.1 "><p id="p201575497282"><a name="p201575497282"></a><a name="p201575497282"></a>用户定义的变量</p>
</td>
<td class="cellrowborder" valign="top" width="24.297570242975702%" headers="mcps1.2.5.1.1 "><p id="p71571749192816"><a name="p71571749192816"></a><a name="p71571749192816"></a>名称</p>
</td>
<td class="cellrowborder" valign="top" width="27.757224277572245%" headers="mcps1.2.5.1.2 "><p id="p115715495287"><a name="p115715495287"></a><a name="p115715495287"></a>枚举变量名称</p>
</td>
<td class="cellrowborder" rowspan="2" valign="top" width="25.067493250674932%" headers="mcps1.2.5.1.3 "><p id="p13743123719329"><a name="p13743123719329"></a><a name="p13743123719329"></a>全局变量，枚举型。命名需要唯一。</p>
</td>
</tr>
<tr id="row19157154914289"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p1415754912816"><a name="p1415754912816"></a><a name="p1415754912816"></a>值</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p9157184982813"><a name="p9157184982813"></a><a name="p9157184982813"></a>枚举变量值</p>
</td>
</tr>
<tr id="row5157104972814"><td class="cellrowborder" rowspan="5" valign="top" width="22.87771222877712%" headers="mcps1.2.5.1.1 "><p id="p17157649142812"><a name="p17157649142812"></a><a name="p17157649142812"></a>用户参数</p>
</td>
<td class="cellrowborder" valign="top" width="24.297570242975702%" headers="mcps1.2.5.1.1 "><p id="p13915141133318"><a name="p13915141133318"></a><a name="p13915141133318"></a>名称</p>
</td>
<td class="cellrowborder" valign="top" width="27.757224277572245%" headers="mcps1.2.5.1.2 "><p id="p8528829133315"><a name="p8528829133315"></a><a name="p8528829133315"></a>枚举变量名称</p>
</td>
<td class="cellrowborder" rowspan="5" valign="top" width="25.067493250674932%" headers="mcps1.2.5.1.3 "><p id="p9960622173513"><a name="p9960622173513"></a><a name="p9960622173513"></a>全局变量，枚举型。命名需要唯一。</p>
</td>
</tr>
<tr id="row11157154932810"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p7915151114334"><a name="p7915151114334"></a><a name="p7915151114334"></a>用户_1</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p752815292336"><a name="p752815292336"></a><a name="p752815292336"></a>枚举变量值</p>
</td>
</tr>
<tr id="row19159134912287"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p291551143313"><a name="p291551143313"></a><a name="p291551143313"></a>用户_2</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p552822973320"><a name="p552822973320"></a><a name="p552822973320"></a>枚举变量值</p>
</td>
</tr>
<tr id="row2015994910282"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p5915111163314"><a name="p5915111163314"></a><a name="p5915111163314"></a>...</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p65289296338"><a name="p65289296338"></a><a name="p65289296338"></a>枚举变量值</p>
</td>
</tr>
<tr id="row13159184916281"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p915914972815"><a name="p915914972815"></a><a name="p915914972815"></a>用户_N</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p315912492285"><a name="p315912492285"></a><a name="p315912492285"></a>枚举变量值</p>
</td>
</tr>
<tr id="row1915944913287"><td class="cellrowborder" rowspan="2" valign="top" width="22.87771222877712%" headers="mcps1.2.5.1.1 "><p id="p6159194982815"><a name="p6159194982815"></a><a name="p6159194982815"></a>HTTP信息头管理器</p>
</td>
<td class="cellrowborder" valign="top" width="24.297570242975702%" headers="mcps1.2.5.1.1 "><p id="p815974920285"><a name="p815974920285"></a><a name="p815974920285"></a>名称</p>
</td>
<td class="cellrowborder" valign="top" width="27.757224277572245%" headers="mcps1.2.5.1.2 "><p id="p315918498289"><a name="p315918498289"></a><a name="p315918498289"></a>报文头域</p>
</td>
<td class="cellrowborder" rowspan="2" valign="top" width="25.067493250674932%" headers="mcps1.2.5.1.3 "><p id="p171591495287"><a name="p171591495287"></a><a name="p171591495287"></a>当POST、PATCH、PUT、DELETE请求方法不存在Content-Type头域时，默认Content-Type头域的值为application/x-www-form-urlencoded。</p>
</td>
</tr>
<tr id="row111594498285"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p171591249182817"><a name="p171591249182817"></a><a name="p171591249182817"></a>值</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p415954912815"><a name="p415954912815"></a><a name="p415954912815"></a>头域值</p>
</td>
</tr>
<tr id="row91591949162811"><td class="cellrowborder" rowspan="7" valign="top" width="22.87771222877712%" headers="mcps1.2.5.1.1 "><p id="p71597497282"><a name="p71597497282"></a><a name="p71597497282"></a>HTTP请求默认值</p>
</td>
<td class="cellrowborder" valign="top" width="24.297570242975702%" headers="mcps1.2.5.1.1 "><p id="p1534734213382"><a name="p1534734213382"></a><a name="p1534734213382"></a>协议</p>
</td>
<td class="cellrowborder" rowspan="7" valign="top" width="27.757224277572245%" headers="mcps1.2.5.1.2 "><p id="p155644506389"><a name="p155644506389"></a><a name="p155644506389"></a>-</p>
</td>
<td class="cellrowborder" rowspan="7" valign="top" width="25.067493250674932%" headers="mcps1.2.5.1.3 "><p id="p194487193397"><a name="p194487193397"></a><a name="p194487193397"></a>HTTP请求中没有值时，自动取HTTP请求默认值。</p>
<p id="p1773995415389"><a name="p1773995415389"></a><a name="p1773995415389"></a>优先级：HTTP请求下的 &gt; 线程组下的 &gt; 测试计划下的。</p>
</td>
</tr>
<tr id="row11160114982815"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p834711429386"><a name="p834711429386"></a><a name="p834711429386"></a>服务器名称或IP</p>
</td>
</tr>
<tr id="row181609498281"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p183471742163818"><a name="p183471742163818"></a><a name="p183471742163818"></a>端口号</p>
</td>
</tr>
<tr id="row61601492283"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p634713428389"><a name="p634713428389"></a><a name="p634713428389"></a>路径</p>
</td>
</tr>
<tr id="row6160164917288"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p1734724203820"><a name="p1734724203820"></a><a name="p1734724203820"></a>参数</p>
</td>
</tr>
<tr id="row18160154992816"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p93471542103813"><a name="p93471542103813"></a><a name="p93471542103813"></a>消息体数据</p>
</td>
</tr>
<tr id="row13160104915287"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p4347194233817"><a name="p4347194233817"></a><a name="p4347194233817"></a>高级选项中的响应超时</p>
</td>
</tr>
<tr id="row1516044982810"><td class="cellrowborder" rowspan="8" valign="top" width="22.87771222877712%" headers="mcps1.2.5.1.1 "><p id="p4160349182816"><a name="p4160349182816"></a><a name="p4160349182816"></a>HTTP请求</p>
</td>
<td class="cellrowborder" valign="top" width="24.297570242975702%" headers="mcps1.2.5.1.1 "><p id="p132361751407"><a name="p132361751407"></a><a name="p132361751407"></a>协议</p>
</td>
<td class="cellrowborder" valign="top" width="27.757224277572245%" headers="mcps1.2.5.1.2 "><p id="p12253195144019"><a name="p12253195144019"></a><a name="p12253195144019"></a>协议类型</p>
</td>
<td class="cellrowborder" rowspan="8" valign="top" width="25.067493250674932%" headers="mcps1.2.5.1.3 "><p id="p3933153105216"><a name="p3933153105216"></a><a name="p3933153105216"></a>报文，请忽略POST、GET、PATCH、PUT、DELETE以外的请求方法；当读取不到响应超时有效值时默认为5000。</p>
</td>
</tr>
<tr id="row416034992815"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p723635144019"><a name="p723635144019"></a><a name="p723635144019"></a>协议、服务器名称或IP、端口号、路径</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p1925213519403"><a name="p1925213519403"></a><a name="p1925213519403"></a>请求链接</p>
</td>
</tr>
<tr id="row17160349172817"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p1523613512403"><a name="p1523613512403"></a><a name="p1523613512403"></a>端口号</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p19250125134010"><a name="p19250125134010"></a><a name="p19250125134010"></a>-</p>
</td>
</tr>
<tr id="row5160134914285"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p132365518402"><a name="p132365518402"></a><a name="p132365518402"></a>方法</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p10249453402"><a name="p10249453402"></a><a name="p10249453402"></a>请求方法</p>
</td>
</tr>
<tr id="row161614491282"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p1023612554012"><a name="p1023612554012"></a><a name="p1023612554012"></a>路径</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p1424855104015"><a name="p1424855104015"></a><a name="p1424855104015"></a>-</p>
</td>
</tr>
<tr id="row1616184914282"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p1123619517404"><a name="p1123619517404"></a><a name="p1123619517404"></a>参数</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p224715154019"><a name="p224715154019"></a><a name="p224715154019"></a>-</p>
</td>
</tr>
<tr id="row10161949102813"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p82361955403"><a name="p82361955403"></a><a name="p82361955403"></a>消息体数据</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p124616511408"><a name="p124616511408"></a><a name="p124616511408"></a>-</p>
</td>
</tr>
<tr id="row7161194916288"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p8237105144015"><a name="p8237105144015"></a><a name="p8237105144015"></a>高级选项中的响应超时</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p142448534011"><a name="p142448534011"></a><a name="p142448534011"></a>响应超时</p>
</td>
</tr>
<tr id="row31614497282"><td class="cellrowborder" rowspan="7" valign="top" width="22.87771222877712%" headers="mcps1.2.5.1.1 "><p id="p108995552458"><a name="p108995552458"></a><a name="p108995552458"></a>正则表达式提取器（要检查的响应字段）</p>
</td>
<td class="cellrowborder" valign="top" width="24.297570242975702%" headers="mcps1.2.5.1.1 "><p id="p10381715194710"><a name="p10381715194710"></a><a name="p10381715194710"></a>主体</p>
</td>
<td class="cellrowborder" valign="top" width="27.757224277572245%" headers="mcps1.2.5.1.2 "><p id="p111612491283"><a name="p111612491283"></a><a name="p111612491283"></a>报文内容</p>
</td>
<td class="cellrowborder" rowspan="12" valign="top" width="25.067493250674932%" headers="mcps1.2.5.1.3 "><p id="p14448480483"><a name="p14448480483"></a><a name="p14448480483"></a>响应提取，只有在HTTP请求下的正则表达式提取器、固定定时器时才会被导入。缺省值为空时，默认取引用名称。</p>
</td>
</tr>
<tr id="row56484131416"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p173821512477"><a name="p173821512477"></a><a name="p173821512477"></a>Body(unescaped)</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p364811311416"><a name="p364811311416"></a><a name="p364811311416"></a>报文内容</p>
</td>
</tr>
<tr id="row07161411144119"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p143912159471"><a name="p143912159471"></a><a name="p143912159471"></a>Body as a Document</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p11716111114415"><a name="p11716111114415"></a><a name="p11716111114415"></a>报文内容</p>
</td>
</tr>
<tr id="row298616974118"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p539015174714"><a name="p539015174714"></a><a name="p539015174714"></a>信息头</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p998610924110"><a name="p998610924110"></a><a name="p998610924110"></a>头域</p>
</td>
</tr>
<tr id="row114471289414"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p239111524715"><a name="p239111524715"></a><a name="p239111524715"></a>URL</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p1444717824112"><a name="p1444717824112"></a><a name="p1444717824112"></a>URL</p>
</td>
</tr>
<tr id="row55277313418"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p33921515473"><a name="p33921515473"></a><a name="p33921515473"></a>响应代码</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p175274394116"><a name="p175274394116"></a><a name="p175274394116"></a>响应码</p>
</td>
</tr>
<tr id="row362194110475"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p3621204114710"><a name="p3621204114710"></a><a name="p3621204114710"></a>Request Headers、响应信息</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p1162144112471"><a name="p1162144112471"></a><a name="p1162144112471"></a>不支持导入，该正则表达式提取器会被忽略。</p>
</td>
</tr>
<tr id="row39641154113"><td class="cellrowborder" rowspan="5" valign="top" headers="mcps1.2.5.1.1 "><p id="p4685137144820"><a name="p4685137144820"></a><a name="p4685137144820"></a>正则表达式提取器</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p696421174115"><a name="p696421174115"></a><a name="p696421174115"></a>引用名称</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.2 "><p id="p25322362487"><a name="p25322362487"></a><a name="p25322362487"></a>变量名称</p>
</td>
</tr>
<tr id="row035419084111"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p16354130174120"><a name="p16354130174120"></a><a name="p16354130174120"></a>正则表达式</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p1953293674819"><a name="p1953293674819"></a><a name="p1953293674819"></a>正则表达式</p>
</td>
</tr>
<tr id="row144151058164019"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p14164587407"><a name="p14164587407"></a><a name="p14164587407"></a>模板</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p13532113612482"><a name="p13532113612482"></a><a name="p13532113612482"></a>第几个匹配项</p>
</td>
</tr>
<tr id="row1652925613402"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p353105684014"><a name="p353105684014"></a><a name="p353105684014"></a>匹配数字</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p653273624816"><a name="p653273624816"></a><a name="p653273624816"></a>表达式取值</p>
</td>
</tr>
<tr id="row151611349132813"><td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p31615493289"><a name="p31615493289"></a><a name="p31615493289"></a>缺省值</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 "><p id="p25334369487"><a name="p25334369487"></a><a name="p25334369487"></a>缺省值</p>
</td>
</tr>
<tr id="row78741839457"><td class="cellrowborder" valign="top" width="22.87771222877712%" headers="mcps1.2.5.1.1 "><p id="p8712674482"><a name="p8712674482"></a><a name="p8712674482"></a>固定定时器</p>
</td>
<td class="cellrowborder" valign="top" width="24.297570242975702%" headers="mcps1.2.5.1.1 "><p id="p1187416319454"><a name="p1187416319454"></a><a name="p1187416319454"></a>线程延迟</p>
</td>
<td class="cellrowborder" valign="top" width="27.757224277572245%" headers="mcps1.2.5.1.2 "><p id="p087410374517"><a name="p087410374517"></a><a name="p087410374517"></a>持续时间</p>
</td>
<td class="cellrowborder" valign="top" width="25.067493250674932%" headers="mcps1.2.5.1.3 "><p id="p178741135456"><a name="p178741135456"></a><a name="p178741135456"></a>思考时间，读取不到有效值时默认取5000。</p>
</td>
</tr>
</tbody>
</table>

