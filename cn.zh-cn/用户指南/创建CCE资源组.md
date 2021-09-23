# 创建CCE资源组<a name="cpts_01_0008"></a>

压测过程中或结束后，如果需要查看压测的各项数据，您需要先创建一个资源组并选择已创建的节点（即弹性云服务器）。此资源组作为压测的管理机和执行机。

CCE资源组中使用的节点是CCE的虚拟机节点。

新创建的CCE资源组均为私有CCE资源组，此资源组无需区分引擎，CPTS测试任务和JMeter测试任务都可以使用此资源组。

## 使用建议<a name="section7382659287"></a>

-   用于压测资源组的节点不要运行任何应用或做其他用途，可能会导致应用运行异常。
-   请根据需要压测的并发用户数，创建对应规格的节点，节点需要在云容器引擎服务中创建。**云容器引擎的集群版本支持v1.19及以下版本，集群网络模型建议选择“容器隧道网络”。创建节点时，请选择Euler OS系统。**

    至少创建2个节点，1个作为压测资源组的管理机（即管理执行机的节点），1个作为压测资源组的执行机（即在压测过程中能够提供自身性能数据的施压目标机器）。如需要压测外部服务，请为执行节点绑定弹性IP。如需要调试外部服务，请为管理节点和执行节点都绑定弹性IP。

    **表 1**  规格推荐

    <a name="table1040324710172"></a>
    <table><thead align="left"><tr id="row139675545187"><th class="cellrowborder" valign="top" width="26.732673267326728%" id="mcps1.2.4.1.1"><p id="p1296845411815"><a name="p1296845411815"></a><a name="p1296845411815"></a>并发用户数</p>
    </th>
    <th class="cellrowborder" valign="top" width="33.66336633663366%" id="mcps1.2.4.1.2"><p id="p996985420184"><a name="p996985420184"></a><a name="p996985420184"></a>所需规格</p>
    </th>
    <th class="cellrowborder" valign="top" width="39.6039603960396%" id="mcps1.2.4.1.3"><p id="p14683255102719"><a name="p14683255102719"></a><a name="p14683255102719"></a>数量</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row9971154141815"><td class="cellrowborder" rowspan="2" valign="top" width="26.732673267326728%" headers="mcps1.2.4.1.1 "><p id="p397265411180"><a name="p397265411180"></a><a name="p397265411180"></a>0-5000</p>
    </td>
    <td class="cellrowborder" valign="top" width="33.66336633663366%" headers="mcps1.2.4.1.2 "><p id="p1310821632919"><a name="p1310821632919"></a><a name="p1310821632919"></a>管理节点：4U8G</p>
    </td>
    <td class="cellrowborder" valign="top" width="39.6039603960396%" headers="mcps1.2.4.1.3 "><p id="p1068345512272"><a name="p1068345512272"></a><a name="p1068345512272"></a>1</p>
    </td>
    </tr>
    <tr id="row1292115222287"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p15585112702913"><a name="p15585112702913"></a><a name="p15585112702913"></a>执行节点：4U8G</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p692232272815"><a name="p692232272815"></a><a name="p692232272815"></a>1</p>
    </td>
    </tr>
    <tr id="row76471156152913"><td class="cellrowborder" rowspan="2" valign="top" width="26.732673267326728%" headers="mcps1.2.4.1.1 "><p id="p1825272418356"><a name="p1825272418356"></a><a name="p1825272418356"></a>5001-10000</p>
    </td>
    <td class="cellrowborder" valign="top" width="33.66336633663366%" headers="mcps1.2.4.1.2 "><p id="p14255124143512"><a name="p14255124143512"></a><a name="p14255124143512"></a>管理节点：4U8G</p>
    </td>
    <td class="cellrowborder" valign="top" width="39.6039603960396%" headers="mcps1.2.4.1.3 "><p id="p172581246355"><a name="p172581246355"></a><a name="p172581246355"></a>1</p>
    </td>
    </tr>
    <tr id="row193561354192913"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p16269424163516"><a name="p16269424163516"></a><a name="p16269424163516"></a>执行节点：8U16G</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p527132414353"><a name="p527132414353"></a><a name="p527132414353"></a>1</p>
    </td>
    </tr>
    <tr id="row16318163884013"><td class="cellrowborder" rowspan="2" valign="top" width="26.732673267326728%" headers="mcps1.2.4.1.1 "><p id="p1447225519406"><a name="p1447225519406"></a><a name="p1447225519406"></a>10001-20000</p>
    </td>
    <td class="cellrowborder" valign="top" width="33.66336633663366%" headers="mcps1.2.4.1.2 "><p id="p7474125512402"><a name="p7474125512402"></a><a name="p7474125512402"></a>管理节点：4U8G</p>
    </td>
    <td class="cellrowborder" valign="top" width="39.6039603960396%" headers="mcps1.2.4.1.3 "><p id="p13477185520401"><a name="p13477185520401"></a><a name="p13477185520401"></a>1</p>
    </td>
    </tr>
    <tr id="row2633173414011"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p748075514403"><a name="p748075514403"></a><a name="p748075514403"></a>执行节点：8U16G</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p1483755154017"><a name="p1483755154017"></a><a name="p1483755154017"></a>2</p>
    </td>
    </tr>
    <tr id="row1792915173010"><td class="cellrowborder" rowspan="2" valign="top" width="26.732673267326728%" headers="mcps1.2.4.1.1 "><p id="p18209142713511"><a name="p18209142713511"></a><a name="p18209142713511"></a>20001-30000</p>
    </td>
    <td class="cellrowborder" valign="top" width="33.66336633663366%" headers="mcps1.2.4.1.2 "><p id="p1294161414392"><a name="p1294161414392"></a><a name="p1294161414392"></a>管理节点：4U8G</p>
    </td>
    <td class="cellrowborder" valign="top" width="39.6039603960396%" headers="mcps1.2.4.1.3 "><p id="p221318277355"><a name="p221318277355"></a><a name="p221318277355"></a>1</p>
    </td>
    </tr>
    <tr id="row1492805114297"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p1898101413397"><a name="p1898101413397"></a><a name="p1898101413397"></a>执行节点：8U16G</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p12181527173511"><a name="p12181527173511"></a><a name="p12181527173511"></a>3</p>
    </td>
    </tr>
    <tr id="row16730949112918"><td class="cellrowborder" rowspan="2" valign="top" width="26.732673267326728%" headers="mcps1.2.4.1.1 "><p id="p3935654173614"><a name="p3935654173614"></a><a name="p3935654173614"></a>30001-40000</p>
    </td>
    <td class="cellrowborder" valign="top" width="33.66336633663366%" headers="mcps1.2.4.1.2 "><p id="p14467151510395"><a name="p14467151510395"></a><a name="p14467151510395"></a>管理节点：4U8G</p>
    </td>
    <td class="cellrowborder" valign="top" width="39.6039603960396%" headers="mcps1.2.4.1.3 "><p id="p2730649202918"><a name="p2730649202918"></a><a name="p2730649202918"></a>1</p>
    </td>
    </tr>
    <tr id="row128451446142919"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p247020159397"><a name="p247020159397"></a><a name="p247020159397"></a>执行节点：8U16G</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p148451246102911"><a name="p148451246102911"></a><a name="p148451246102911"></a>4</p>
    </td>
    </tr>
    <tr id="row199984546180"><td class="cellrowborder" rowspan="2" valign="top" width="26.732673267326728%" headers="mcps1.2.4.1.1 "><p id="p13999354191819"><a name="p13999354191819"></a><a name="p13999354191819"></a>40001-50000</p>
    </td>
    <td class="cellrowborder" valign="top" width="33.66336633663366%" headers="mcps1.2.4.1.2 "><p id="p19919181616399"><a name="p19919181616399"></a><a name="p19919181616399"></a>管理节点：4U8G</p>
    </td>
    <td class="cellrowborder" valign="top" width="39.6039603960396%" headers="mcps1.2.4.1.3 "><p id="p19683175511278"><a name="p19683175511278"></a><a name="p19683175511278"></a>1</p>
    </td>
    </tr>
    <tr id="row1043963112370"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p15922201610390"><a name="p15922201610390"></a><a name="p15922201610390"></a>执行节点：8U16G</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p243943193717"><a name="p243943193717"></a><a name="p243943193717"></a>5</p>
    </td>
    </tr>
    <tr id="row1614914117387"><td class="cellrowborder" rowspan="2" valign="top" width="26.732673267326728%" headers="mcps1.2.4.1.1 "><p id="p1014913112382"><a name="p1014913112382"></a><a name="p1014913112382"></a>50001以上</p>
    </td>
    <td class="cellrowborder" valign="top" width="33.66336633663366%" headers="mcps1.2.4.1.2 "><p id="p951517361469"><a name="p951517361469"></a><a name="p951517361469"></a>管理节点：4U8G</p>
    </td>
    <td class="cellrowborder" valign="top" width="39.6039603960396%" headers="mcps1.2.4.1.3 "><p id="p151495117387"><a name="p151495117387"></a><a name="p151495117387"></a>1</p>
    </td>
    </tr>
    <tr id="row13312714143814"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p1519536194616"><a name="p1519536194616"></a><a name="p1519536194616"></a>执行节点：8U16G</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p11313151433812"><a name="p11313151433812"></a><a name="p11313151433812"></a>n</p>
    <div class="note" id="note442472317509"><a name="note442472317509"></a><a name="note442472317509"></a><span class="notetitle"> 说明： </span><div class="notebody"><p id="p532418414498"><a name="p532418414498"></a><a name="p532418414498"></a>每台8U16G的执行节点可支撑10000并发。</p>
    </div></div>
    </td>
    </tr>
    </tbody>
    </table>

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >-   以上资源节点规格推荐是通用规格，仅供参考。实际压测时，资源规格的需求受思考时间、压测的协议类型、请求和响应的大小数量、响应时间、结果验证等因素影响，用户可根据实际情况进行调整。
    >-   压测外部服务时，执行节点需要绑定弹性IP，测试带宽受限于购买的EIP带宽。
    >-   当集群上的节点已经被部署上了应用，创建私有资源组时，该节点无法被选用。
    >-   JMeter引擎不适用该规格。


## 添加节点<a name="section1316062185410"></a>

在CPTS服务中，压测服务需要运行在用户自己创建的节点中。进行压测前，您需要先添加节点，作为CPTS压测资源组中的管理机和执行机。

>![](public_sys-resources/icon-notice.gif) **须知：** 
>CPTS压测资源组无法识别其他区域的CCE节点，请确保添加节点的区域和CPTS所在区域一致。

1.  登录CCE控制台。
2.  创建集群（集群版本支持v1.19及以下版本，集群网络模型建议选择“容器隧道网络”）并添加Euler OS系统的节点，请至少添加2个节点。节点数量和规格请根据实际业务需求选择。

    -   若CCE中已有可用集群，请添加管理机和执行机节点。添加节点操作请参考[购买节点](https://support.huaweicloud.com/usermanual-cce/cce_01_0033.html)。
    -   若CCE中无可用集群，请先创建集群。创建集群操作请参考[购买混合集群](https://support.huaweicloud.com/usermanual-cce/cce_01_0028.html)。集群创建成功后，再添加压测服务的管理机和执行机。

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >压测外部应用（部署在其他VPC的应用、部署在线下或其他公有云上的应用）时，需确保资源组中执行机已绑定弹性IP。


## 创建私有CCE资源组<a name="section151201698274"></a>

1.  登录CPTS控制台，在左侧导航栏中选择“测试资源”，单击“云容器CCE资源准备“。
2.  （可选）首次使用时，请根据提示信息，授权CPTS创建私有CCE资源组。
3.  参照[表2](#table12182171732716)设置基本信息。

    **表 2**  创建压测资源组

    <a name="table12182171732716"></a>
    <table><thead align="left"><tr id="row018351718278"><th class="cellrowborder" valign="top" width="18.68%" id="mcps1.2.3.1.1"><p id="p718371772715"><a name="p718371772715"></a><a name="p718371772715"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="81.32000000000001%" id="mcps1.2.3.1.2"><p id="p10183217132719"><a name="p10183217132719"></a><a name="p10183217132719"></a>参数说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row01831917122717"><td class="cellrowborder" valign="top" width="18.68%" headers="mcps1.2.3.1.1 "><p id="p14183171702711"><a name="p14183171702711"></a><a name="p14183171702711"></a>资源组名称</p>
    </td>
    <td class="cellrowborder" valign="top" width="81.32000000000001%" headers="mcps1.2.3.1.2 "><p id="p19183117162720"><a name="p19183117162720"></a><a name="p19183117162720"></a>新建私有CCE资源组的名称，可自定义。</p>
    </td>
    </tr>
    <tr id="row131832017122718"><td class="cellrowborder" valign="top" width="18.68%" headers="mcps1.2.3.1.1 "><p id="p1718313177277"><a name="p1718313177277"></a><a name="p1718313177277"></a>调试节点</p>
    </td>
    <td class="cellrowborder" valign="top" width="81.32000000000001%" headers="mcps1.2.3.1.2 "><p id="p1818319172278"><a name="p1818319172278"></a><a name="p1818319172278"></a>执行压测的管理机。</p>
    <p id="p31831317132716"><a name="p31831317132716"></a><a name="p31831317132716"></a>调试节点在资源组创建成功后不可修改。</p>
    </td>
    </tr>
    <tr id="row51835178272"><td class="cellrowborder" valign="top" width="18.68%" headers="mcps1.2.3.1.1 "><p id="p111841817102711"><a name="p111841817102711"></a><a name="p111841817102711"></a>执行节点</p>
    </td>
    <td class="cellrowborder" valign="top" width="81.32000000000001%" headers="mcps1.2.3.1.2 "><p id="p2018419174276"><a name="p2018419174276"></a><a name="p2018419174276"></a>执行压测的执行机，即在压测过程中能够提供自身性能数据的施压目标机器。</p>
    </td>
    </tr>
    </tbody>
    </table>

4.  单击“创建“。

    创建成功后，会通过AOS应用编排服务分别为管理节点和执行节点部署压测服务所用的堆栈。

5.  （可选）扩缩容、删除以及升级该资源组。
    -   扩容资源组：在资源组列表中，单击待修改资源组后的“扩缩容”，在“选择执行节点”对话框中，勾选当前已存在的执行节点+需要扩容的执行节点，单击“选择”。
    -   减容资源组：在资源组列表中，单击待修改资源组后的“扩缩容”，在“选择执行节点”对话框中，勾选需要保留的执行节点，单击“选择”。
    -   删除资源组：在资源组列表中，单击待删除资源组中的“删除”，根据系统提示执行删除操作。

        >![](public_sys-resources/icon-note.gif) **说明：** 
        >删除资源组，会同时删除该资源组部署在AOS的堆栈，但不会删除节点，仅表示该资源组中的节点不会再被压测服务使用。如需彻底删除节点，请到对应服务中删除。

    -   升级资源组：在资源组列表中，单击待升级资源组中的“升级”，根据系统提示执行升级操作。


