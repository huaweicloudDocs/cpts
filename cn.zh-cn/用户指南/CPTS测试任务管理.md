# CPTS测试任务管理<a name="cpts_01_0015"></a>

-   **[创建测试任务](创建测试任务.md)**  
测试任务是指基于已定义的测试模型发起一次性能测试的活动。
-   **[添加数据指令](添加数据指令.md)**  
数据指令是指请求里的数据格式: \{\{cpts-data-set:var\}\}，四则运算特指加、减、乘、除二元操作以及保留精度的一元操作。
-   **[添加请求信息（报文）](添加请求信息（报文）.md)**  

-   **[添加请求信息（思考时间）](添加请求信息（思考时间）.md)**  

-   **[添加请求信息（响应提取）](添加请求信息（响应提取）.md)**  
如果同一用例中存在多个报文，通过正则表达式把前一个报文的输出提取出来，作后一个报文的输入。
-   **[添加请求信息（检查点）](添加请求信息（检查点）.md)**  
检查点是指通过自定义校验信息来验证服务端的返回内容是否正确。针对不同的协议类型，检查点支持比对的内容不同，HTTP/HTTPS支持响应码、头域和内容校验，TCP/UDP仅支持内容校验。
-   **[启动压测任务](启动压测任务.md)**  
测试任务指通过在不同压测点执行一系列测试，持续对系统发起压力测试，通过测试获取并分析系统运行的性能数据。
-   **[管理测试任务](管理测试任务.md)**  
测试任务创建成功后，您可以对测试任务和任务阶段进行管理。
-   **[关联分析对象](关联分析对象.md)**  
为测试任务选择关联分析对象。若测试任务处于已启动状态，则无法关联分析对象。
-   **[设置全局变量](设置全局变量.md)**  
全局变量用于构造数据集合，使测试数据更加丰富。在报文事务请求信息的报文内容中引用全局变量，执行压测任务过程会将报文内容中的变量值动态替换为指定的值。
-   **[绑定域名](绑定域名.md)**  
通过配置DNS地址池，实现域名与地址的映射，在URL定义域名，通过DNS地址池自动化获取IP。

