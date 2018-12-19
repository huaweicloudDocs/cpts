# 云性能测试服务CPTS文档<a name="cpts_01_0001"></a>

云性能测试服务（Cloud Performance Test Service）是一项为基于HTTP/HTTPS/TCP/UDP协议构建的云应用提供性能测试的服务。服务支持快速模拟大规模并发用户的业务高峰场景，可以很好的支持报文内容和时序自定义、多事务组合的复杂场景测试，测试完成后会为您提供专业的测试报告呈现您的服务质量。

通过简单的四步操作，您就可以完成一次性能测试。

**表 1**  使用流程

<a name="table7421348122620"></a>
<table><thead align="left"><tr id="row7431348112618"><th class="cellrowborder" valign="top" width="25.11%" id="mcps1.2.5.1.1"><p id="p1743194810269"><a name="p1743194810269"></a><a name="p1743194810269"></a>1. <span class="keyword" id="keyword10195182942816"><a name="keyword10195182942816"></a><a name="keyword10195182942816"></a>环境资源准备</span></p>
</th>
<th class="cellrowborder" valign="top" width="24.89%" id="mcps1.2.5.1.2"><p id="p1243448162616"><a name="p1243448162616"></a><a name="p1243448162616"></a>2. <span class="keyword" id="keyword1652071211312"><a name="keyword1652071211312"></a><a name="keyword1652071211312"></a>创建测试工程</span></p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.3"><p id="p13431748182619"><a name="p13431748182619"></a><a name="p13431748182619"></a>3. <span class="keyword" id="keyword1836171820316"><a name="keyword1836171820316"></a><a name="keyword1836171820316"></a>添加测试任务</span></p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.4"><p id="p5432482268"><a name="p5432482268"></a><a name="p5432482268"></a>4. <span class="keyword" id="keyword17561182133119"><a name="keyword17561182133119"></a><a name="keyword17561182133119"></a>查看测试报告</span></p>
</th>
</tr>
</thead>
<tbody><tr id="row74319486263"><td class="cellrowborder" valign="top" width="25.11%" headers="mcps1.2.5.1.1 "><p id="p17437487261"><a name="p17437487261"></a><a name="p17437487261"></a>压测服务需要运行在用户自己创建的节点中。首先需要创建执行性能测试的资源组。</p>
</td>
<td class="cellrowborder" valign="top" width="24.89%" headers="mcps1.2.5.1.2 "><p id="p34354812260"><a name="p34354812260"></a><a name="p34354812260"></a>为用户的测试工程提供管理能力，事务、测试任务、测试报告的内容在同一个工程内共享。</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.3 "><p id="p184312487267"><a name="p184312487267"></a><a name="p184312487267"></a>引用定义好的测试事务，为用户创建性能测试场景。</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.4 "><p id="p6431248182610"><a name="p6431248182610"></a><a name="p6431248182610"></a>提供性能测试的实时报告和离线报告，用于测试结果分析。</p>
</td>
</tr>
</tbody>
</table>

## 操作约束<a name="section3918152421"></a>

若使用CPTS服务压测公共网站，需确保该公共网站对于压测者是白名单，否则一切法律后果需自负。

