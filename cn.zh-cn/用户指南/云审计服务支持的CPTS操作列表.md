# 云审计服务支持的CPTS操作列表<a name="cpts_01_0038"></a>

## 支持审计的关键操作列表<a name="section59120490409"></a>

云审计服务（Cloud Trace Service，简称CTS），是华为云安全解决方案中专业的日志审计服务，提供对各种云资源操作记录的收集、存储和查询功能，可用于支撑安全分析、合规审计、资源跟踪和问题定位等常见应用场景。

通过云审计服务，您可以记录与消息通知服务相关的操作事件，便于日后的查询、审计和回溯。

**表 1**  支持审计的关键操作列表

<a name="table19874194611398"></a>
<table><thead align="left"><tr id="row1887444616391"><th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.2.6.1.1"><p id="p749317587395"><a name="p749317587395"></a><a name="p749317587395"></a>service_type</p>
</th>
<th class="cellrowborder" valign="top" width="19%" id="mcps1.2.6.1.2"><p id="p1949395816399"><a name="p1949395816399"></a><a name="p1949395816399"></a>resource_type</p>
</th>
<th class="cellrowborder" valign="top" width="18%" id="mcps1.2.6.1.3"><p id="p1349375833918"><a name="p1349375833918"></a><a name="p1349375833918"></a>resource_id</p>
</th>
<th class="cellrowborder" valign="top" width="26%" id="mcps1.2.6.1.4"><p id="p84931958193914"><a name="p84931958193914"></a><a name="p84931958193914"></a>trace_name</p>
</th>
<th class="cellrowborder" valign="top" width="23%" id="mcps1.2.6.1.5"><p id="p44936589390"><a name="p44936589390"></a><a name="p44936589390"></a>中文描述</p>
</th>
</tr>
</thead>
<tbody><tr id="row15874646143912"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p649345813392"><a name="p649345813392"></a><a name="p649345813392"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p149305816392"><a name="p149305816392"></a><a name="p149305816392"></a>cptsProject</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p1649314582390"><a name="p1649314582390"></a><a name="p1649314582390"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p14493185812397"><a name="p14493185812397"></a><a name="p14493185812397"></a>createCptsProject</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p1493105853917"><a name="p1493105853917"></a><a name="p1493105853917"></a>创建工程</p>
</td>
</tr>
<tr id="row08741046113917"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p54931058193910"><a name="p54931058193910"></a><a name="p54931058193910"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p10493195818396"><a name="p10493195818396"></a><a name="p10493195818396"></a>cptsProject</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p19493135815394"><a name="p19493135815394"></a><a name="p19493135815394"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p16493205812393"><a name="p16493205812393"></a><a name="p16493205812393"></a>deleteCptsProject</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p1749385883916"><a name="p1749385883916"></a><a name="p1749385883916"></a>删除工程</p>
</td>
</tr>
<tr id="row1387534653919"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p18493185820399"><a name="p18493185820399"></a><a name="p18493185820399"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p14494155812391"><a name="p14494155812391"></a><a name="p14494155812391"></a>cptsProject</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p54949589394"><a name="p54949589394"></a><a name="p54949589394"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p194941858163910"><a name="p194941858163910"></a><a name="p194941858163910"></a>modifyCptsProject</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p949417584396"><a name="p949417584396"></a><a name="p949417584396"></a>修改工程</p>
</td>
</tr>
<tr id="row4875174618395"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p17494175810399"><a name="p17494175810399"></a><a name="p17494175810399"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p19494115812396"><a name="p19494115812396"></a><a name="p19494115812396"></a>cptsTask</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p14941558193911"><a name="p14941558193911"></a><a name="p14941558193911"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p14494458173913"><a name="p14494458173913"></a><a name="p14494458173913"></a>createCptsTask</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p249455893915"><a name="p249455893915"></a><a name="p249455893915"></a>创建任务</p>
</td>
</tr>
<tr id="row2087594620399"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p149475863910"><a name="p149475863910"></a><a name="p149475863910"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p15494125811392"><a name="p15494125811392"></a><a name="p15494125811392"></a>cptsTask</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p9494658163915"><a name="p9494658163915"></a><a name="p9494658163915"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p10495558133916"><a name="p10495558133916"></a><a name="p10495558133916"></a>deleteCptsTask</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p10495858133912"><a name="p10495858133912"></a><a name="p10495858133912"></a>删除任务</p>
</td>
</tr>
<tr id="row118754468397"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p449510587396"><a name="p449510587396"></a><a name="p449510587396"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p1049575863910"><a name="p1049575863910"></a><a name="p1049575863910"></a>cptsTask</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p194951458183913"><a name="p194951458183913"></a><a name="p194951458183913"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p5495155883915"><a name="p5495155883915"></a><a name="p5495155883915"></a>modifyCptsTask</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p74953586396"><a name="p74953586396"></a><a name="p74953586396"></a>修改任务</p>
</td>
</tr>
<tr id="row687614610393"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p849514586391"><a name="p849514586391"></a><a name="p849514586391"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p449555853916"><a name="p449555853916"></a><a name="p449555853916"></a>cptsTemp</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p9495145813394"><a name="p9495145813394"></a><a name="p9495145813394"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p114957583394"><a name="p114957583394"></a><a name="p114957583394"></a>createCptsTemp</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p13495145863915"><a name="p13495145863915"></a><a name="p13495145863915"></a>创建事务</p>
</td>
</tr>
<tr id="row387624620399"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p2049511586397"><a name="p2049511586397"></a><a name="p2049511586397"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p5495158143913"><a name="p5495158143913"></a><a name="p5495158143913"></a>cptsTemp</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p18495105812393"><a name="p18495105812393"></a><a name="p18495105812393"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p749665818391"><a name="p749665818391"></a><a name="p749665818391"></a>deleteCptsTemp</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p749615843910"><a name="p749615843910"></a><a name="p749615843910"></a>删除事务</p>
</td>
</tr>
<tr id="row08761046183911"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p349615581393"><a name="p349615581393"></a><a name="p349615581393"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p1649695817396"><a name="p1649695817396"></a><a name="p1649695817396"></a>cptsTemp</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p449610583395"><a name="p449610583395"></a><a name="p449610583395"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p1249615817399"><a name="p1249615817399"></a><a name="p1249615817399"></a>modifyCptsTemp</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p17496115893916"><a name="p17496115893916"></a><a name="p17496115893916"></a>修改事务</p>
</td>
</tr>
<tr id="row11876144623914"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p849665893912"><a name="p849665893912"></a><a name="p849665893912"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p6496185817391"><a name="p6496185817391"></a><a name="p6496185817391"></a>cptsCluster</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p184961358133920"><a name="p184961358133920"></a><a name="p184961358133920"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p10497115883917"><a name="p10497115883917"></a><a name="p10497115883917"></a>createCptsCluster</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p19497195803915"><a name="p19497195803915"></a><a name="p19497195803915"></a>创建集群</p>
</td>
</tr>
<tr id="row18771467391"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p1249717588397"><a name="p1249717588397"></a><a name="p1249717588397"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p11497758123920"><a name="p11497758123920"></a><a name="p11497758123920"></a>cptsCluster</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p04976583399"><a name="p04976583399"></a><a name="p04976583399"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p04977585398"><a name="p04977585398"></a><a name="p04977585398"></a>deleteCptsCluster</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p64971658123910"><a name="p64971658123910"></a><a name="p64971658123910"></a>删除集群</p>
</td>
</tr>
<tr id="row1387774611397"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p1349735843918"><a name="p1349735843918"></a><a name="p1349735843918"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p2497958163916"><a name="p2497958163916"></a><a name="p2497958163916"></a>cptsCluster</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p104971958193914"><a name="p104971958193914"></a><a name="p104971958193914"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p12497158153911"><a name="p12497158153911"></a><a name="p12497158153911"></a>modifyCptsCluster</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p249775853911"><a name="p249775853911"></a><a name="p249775853911"></a>修改集群</p>
</td>
</tr>
<tr id="row487774603919"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p174981558143915"><a name="p174981558143915"></a><a name="p174981558143915"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p14986588394"><a name="p14986588394"></a><a name="p14986588394"></a>cptsVariable</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p34988583395"><a name="p34988583395"></a><a name="p34988583395"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p349818583399"><a name="p349818583399"></a><a name="p349818583399"></a>createCptsVariable</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p64982058183915"><a name="p64982058183915"></a><a name="p64982058183915"></a>创建变量</p>
</td>
</tr>
<tr id="row587724618393"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p649818586394"><a name="p649818586394"></a><a name="p649818586394"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p194981058123917"><a name="p194981058123917"></a><a name="p194981058123917"></a>cptsVariable</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p449814588398"><a name="p449814588398"></a><a name="p449814588398"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p17498105843911"><a name="p17498105843911"></a><a name="p17498105843911"></a>deleteCptsVariable</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p7498145817392"><a name="p7498145817392"></a><a name="p7498145817392"></a>删除变量</p>
</td>
</tr>
<tr id="row087820461395"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p1549885819391"><a name="p1549885819391"></a><a name="p1549885819391"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p04982584392"><a name="p04982584392"></a><a name="p04982584392"></a>cptsTempDebug</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p5498195817395"><a name="p5498195817395"></a><a name="p5498195817395"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p7498185853912"><a name="p7498185853912"></a><a name="p7498185853912"></a>postTempDebug</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p1549975819390"><a name="p1549975819390"></a><a name="p1549975819390"></a>模板debug</p>
</td>
</tr>
<tr id="row1887816469398"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p114992058123916"><a name="p114992058123916"></a><a name="p114992058123916"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p17499165818390"><a name="p17499165818390"></a><a name="p17499165818390"></a>cptsTaskStatus</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p15499175817391"><a name="p15499175817391"></a><a name="p15499175817391"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p649945819391"><a name="p649945819391"></a><a name="p649945819391"></a>UpdateTaskStatus</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p3499105816391"><a name="p3499105816391"></a><a name="p3499105816391"></a>更新任务状态</p>
</td>
</tr>
<tr id="row13878174633914"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p17499658133910"><a name="p17499658133910"></a><a name="p17499658133910"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p1449985818399"><a name="p1449985818399"></a><a name="p1449985818399"></a>cptsStack</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p1649915863916"><a name="p1649915863916"></a><a name="p1649915863916"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p1249910588398"><a name="p1249910588398"></a><a name="p1249910588398"></a>StackUpgradeByACId</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p1349925843918"><a name="p1349925843918"></a><a name="p1349925843918"></a>升级堆栈</p>
</td>
</tr>
<tr id="row18781046183911"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p154999586397"><a name="p154999586397"></a><a name="p154999586397"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p05001558173919"><a name="p05001558173919"></a><a name="p05001558173919"></a>cptsCluster</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p150020583397"><a name="p150020583397"></a><a name="p150020583397"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p1450015818392"><a name="p1450015818392"></a><a name="p1450015818392"></a>ClearUnDeleteAppCluster</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p1350019587398"><a name="p1350019587398"></a><a name="p1350019587398"></a>强制删除集群</p>
</td>
</tr>
<tr id="row14878846183916"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p155001658133912"><a name="p155001658133912"></a><a name="p155001658133912"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p450045812393"><a name="p450045812393"></a><a name="p450045812393"></a>cptsStackVersion</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p1250065893917"><a name="p1250065893917"></a><a name="p1250065893917"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p65001358123918"><a name="p65001358123918"></a><a name="p65001358123918"></a>SetStackVersion</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p750005863915"><a name="p750005863915"></a><a name="p750005863915"></a>设置堆栈版本</p>
</td>
</tr>
<tr id="row487819468394"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.6.1.1 "><p id="p350013582397"><a name="p350013582397"></a><a name="p350013582397"></a>CPTS</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.2 "><p id="p75001358133920"><a name="p75001358133920"></a><a name="p75001358133920"></a>cptsStack</p>
</td>
<td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.6.1.3 "><p id="p1950065810395"><a name="p1950065810395"></a><a name="p1950065810395"></a>数据库主键</p>
</td>
<td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.6.1.4 "><p id="p65001658133919"><a name="p65001658133919"></a><a name="p65001658133919"></a>UpdateAccountResourceStatus</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.6.1.5 "><p id="p457143419218"><a name="p457143419218"></a><a name="p457143419218"></a>更新账号资源状态</p>
</td>
</tr>
</tbody>
</table>

