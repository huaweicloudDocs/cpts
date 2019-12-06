# 创建云容器实例CCI资源组<a name="cpts_01_0054"></a>

云容器实例CCI资源组中使用的节点是CCI云容器实例中创建的实例化节点。

## 创建虚拟私有云<a name="section975319475587"></a>

创建云容器实例CCI资源组前，您必须先确保已存在虚拟私有云。

1.  登录CPTS控制台。
2.  在服务列表中，选择“网络 \> 虚拟私有云”。
3.  在“虚拟私有云”界面，单击“创建虚拟私有云”。
4.  根据界面提示创建虚拟私有云。如无特殊需求，界面参数均可保持默认。

## 创建云容器实例CCI资源组<a name="section1930819114541"></a>

云容器实例CCI资源组中使用的节点，是CCI云容器实例中创建的实例化节点。

1.  登录CPTS控制台，在左侧导航栏中选择“测试资源”，单击“云容器实例CCI资源购买“。
2.  参照[表1](#table5854195819284)设置实例化资源信息。

    **表 1**  创建云容器实例CCI资源组

    <a name="table5854195819284"></a>
    <table><thead align="left"><tr id="row1085216581283"><th class="cellrowborder" valign="top" width="16.09%" id="mcps1.2.3.1.1"><p id="p3852205819289"><a name="p3852205819289"></a><a name="p3852205819289"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="83.91%" id="mcps1.2.3.1.2"><p id="p3852185812819"><a name="p3852185812819"></a><a name="p3852185812819"></a>参数说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row385245862819"><td class="cellrowborder" valign="top" width="16.09%" headers="mcps1.2.3.1.1 "><p id="p432974591"><a name="p432974591"></a><a name="p432974591"></a>可用区</p>
    </td>
    <td class="cellrowborder" valign="top" width="83.91%" headers="mcps1.2.3.1.2 "><p id="p11450171631117"><a name="p11450171631117"></a><a name="p11450171631117"></a><span>可用区指在同一区域下，电力、网络隔离的物理区域，可用区之间内网互通，不同可用区之间物理隔离。</span></p>
    </td>
    </tr>
    <tr id="row128531158122817"><td class="cellrowborder" valign="top" width="16.09%" headers="mcps1.2.3.1.1 "><p id="p102877175919"><a name="p102877175919"></a><a name="p102877175919"></a>资源组名称</p>
    </td>
    <td class="cellrowborder" valign="top" width="83.91%" headers="mcps1.2.3.1.2 "><p id="p72613718595"><a name="p72613718595"></a><a name="p72613718595"></a>新建云容器实例CCI资源组的名称，可自定义。</p>
    </td>
    </tr>
    <tr id="row122947916144"><td class="cellrowborder" valign="top" width="16.09%" headers="mcps1.2.3.1.1 "><p id="p179645913419"><a name="p179645913419"></a><a name="p179645913419"></a>引擎选择</p>
    </td>
    <td class="cellrowborder" valign="top" width="83.91%" headers="mcps1.2.3.1.2 "><p id="p141361930102514"><a name="p141361930102514"></a><a name="p141361930102514"></a>提供两种压力测试引擎：</p>
    <p id="p7377173342018"><a name="p7377173342018"></a><a name="p7377173342018"></a><strong id="b1084211477203"><a name="b1084211477203"></a><a name="b1084211477203"></a>CPTS引擎：</strong>默认压测引擎。</p>
    <p id="p2963184881619"><a name="p2963184881619"></a><a name="p2963184881619"></a>并发规格：资源组支持的最大并发数，规格只能选择0.5或正整数。管理节点规格默认为2U 4GB，并发规格每增加10000，需要增加1个8U 16GB的CCI服务实例。</p>
    <div class="p" id="p163772033172012"><a name="p163772033172012"></a><a name="p163772033172012"></a><strong id="b1833205112013"><a name="b1833205112013"></a><a name="b1833205112013"></a>JMeter引擎：</strong>JMeter是Apache组织开发的基于Java的压力测试工具。用于对软件做压力测试，它最初被设计用于Web应用测试，但后来扩展到其他测试领域。 它可以用于测试静态和动态资源，例如静态文件、Java小服务程序、CGI脚本、Java对象、数据库、FTP服务器等。<a name="ul1248219962013"></a><a name="ul1248219962013"></a><ul id="ul1248219962013"><li>执行机数量：请根据压测需求输入执行机数量。</li><li>执行机规格：目前提供4核8GB、8核16GB、16核32GB三种执行机规格，请根据压测需求进行选择。</li></ul>
    </div>
    </td>
    </tr>
    <tr id="row56225325594"><td class="cellrowborder" valign="top" width="16.09%" headers="mcps1.2.3.1.1 "><p id="p17623123216599"><a name="p17623123216599"></a><a name="p17623123216599"></a>虚拟私有云</p>
    </td>
    <td class="cellrowborder" valign="top" width="83.91%" headers="mcps1.2.3.1.2 "><p id="p1639155915560"><a name="p1639155915560"></a><a name="p1639155915560"></a>新建云容器实例CCI资源组所在的虚拟私有云。</p>
    <p id="p46241332175913"><a name="p46241332175913"></a><a name="p46241332175913"></a>若无可用的虚拟私有云，请单击“新建虚拟私有云”进行创建，操作步骤请参见<a href="#section975319475587">创建虚拟私有云</a>。</p>
    </td>
    </tr>
    <tr id="row1462923925919"><td class="cellrowborder" valign="top" width="16.09%" headers="mcps1.2.3.1.1 "><p id="p19629163955917"><a name="p19629163955917"></a><a name="p19629163955917"></a>所在子网</p>
    </td>
    <td class="cellrowborder" valign="top" width="83.91%" headers="mcps1.2.3.1.2 "><p id="p2629193910595"><a name="p2629193910595"></a><a name="p2629193910595"></a>云容器实例CCI资源组运行的子网环境。</p>
    </td>
    </tr>
    <tr id="row966618368593"><td class="cellrowborder" valign="top" width="16.09%" headers="mcps1.2.3.1.1 "><p id="p9667636145919"><a name="p9667636145919"></a><a name="p9667636145919"></a>网络类型</p>
    </td>
    <td class="cellrowborder" valign="top" width="83.91%" headers="mcps1.2.3.1.2 "><p id="p1326523015265"><a name="p1326523015265"></a><a name="p1326523015265"></a>提供两种网络类型：</p>
    <a name="ul121514253265"></a><a name="ul121514253265"></a><ul id="ul121514253265"><li>内网：<span>测试内网性能时选择。配置为内网时，必须确保此处配置的虚拟私有云VPC和创建集群时配置的虚拟私有云VPC相同。</span></li><li>外网：<span>为特定的弹性云服务器配置公网IP，可直接访问Internet。</span>选择后需配置更多参数，见<a href="#table1497191593113">表2</a>。</li></ul>
    </td>
    </tr>
    </tbody>
    </table>

    当网络类型选择“外网“时，需配置如下参数：

    **表 2**  外网参数配置

    <a name="table1497191593113"></a>
    <table><thead align="left"><tr id="row16621134193113"><th class="cellrowborder" valign="top" width="14.879999999999999%" id="mcps1.2.4.1.1"><p id="p172661836173117"><a name="p172661836173117"></a><a name="p172661836173117"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="14.84%" id="mcps1.2.4.1.2"><p id="p24014351014"><a name="p24014351014"></a><a name="p24014351014"></a>选项</p>
    </th>
    <th class="cellrowborder" valign="top" width="70.28%" id="mcps1.2.4.1.3"><p id="p1426613364318"><a name="p1426613364318"></a><a name="p1426613364318"></a>参数说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row129801520316"><td class="cellrowborder" rowspan="2" valign="top" width="14.879999999999999%" headers="mcps1.2.4.1.1 "><p id="p1777874110282"><a name="p1777874110282"></a><a name="p1777874110282"></a>弹性IP</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.84%" headers="mcps1.2.4.1.2 "><p id="p640114351600"><a name="p640114351600"></a><a name="p640114351600"></a>现在购买</p>
    </td>
    <td class="cellrowborder" valign="top" width="70.28%" headers="mcps1.2.4.1.3 "><p id="p838911514386"><a name="p838911514386"></a><a name="p838911514386"></a>自动为每台弹性云服务器分配独享带宽的弹性公网IP，带宽值可以由您设定。</p>
    <a name="ul950715121917"></a><a name="ul950715121917"></a><ul id="ul950715121917"><li>购买量：购买弹性IP的数量。如果当前并发量不足，可单击“扩大弹性IP配额”进行扩容。</li><li>规格：<p id="p028211815200"><a name="p028211815200"></a><a name="p028211815200"></a>全动态BGP：可根据设定的寻路协议第一时间自动优化网络结构，以保持客户使用的网络持续稳定、高效。</p>
    <p id="p132823810206"><a name="p132823810206"></a><a name="p132823810206"></a>静态BGP：网络结构发生变化时，运营商无法在第一时间自动调整网络设置以保障用户的体验度。</p>
    </li><li>计费模式：指购买的弹性公网IP的带宽计费方式，包括以下两种：<p id="p13583958152110"><a name="p13583958152110"></a><a name="p13583958152110"></a>按带宽计费：按照购买的带宽大小计费。</p>
    <p id="p10583125814215"><a name="p10583125814215"></a><a name="p10583125814215"></a>按流量计费：按照实际使用的流量来计费。</p>
    </li><li>带宽：可根据需要调整带宽。</li></ul>
    </td>
    </tr>
    <tr id="row119811583110"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p1240220351019"><a name="p1240220351019"></a><a name="p1240220351019"></a>使用已有</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p20590118153616"><a name="p20590118153616"></a><a name="p20590118153616"></a>为弹性云服务器分配已有弹性公网IP。</p>
    <p id="p1162145915179"><a name="p1162145915179"></a><a name="p1162145915179"></a>已有IP：请选择已有的IP。</p>
    </td>
    </tr>
    </tbody>
    </table>

3.  单击“立即购买“。

    创建成功后，会在AOS、CCI分别创建模板、堆栈、命名空间和工作负载。

4.  如果不再需要该资源组，您可以删除该资源组。

    在资源组列表中，单击待修改资源组中的“删除”，根据系统提示执行删除操作。


