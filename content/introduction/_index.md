---

title: "介绍"
weight: 10
layout: "single"

menu:
  main:
    identifier: "user-guide-introduction"

---


欢迎来到Camunda平台手册！ Camunda是一个基于java的框架，支持用于工作流和过程自动化的BPMN、用于案例管理的CMMN和用于商业决策管理的DMN。还请参阅： [实施标准]({{< ref "/introduction/implemented-standards.md" >}}).

本文档包含有关Camunda平台提供的功能的信息。

要为你提供Camunda的概述，下图显示了最重要的组件以及一些典型的用户角色。

{{< img src="img/architecture-overview.png" title="Camunda组件和角色" >}}


# 流程引擎和基础设施

* [流程引擎]({{< ref "/user-guide/process-engine/_index.md" >}}) 流程引擎是负责执行BPMN 2.0流程、CMMN 1.1案例和DMN 1.3决策的Java库。它有一个轻量级的POJO核心，并使用关系数据库来持久性。 orm映射由mybatis映射框架提供。
* [Spring 框架集成]({{< ref "/user-guide/spring-framework-integration/_index.md" >}})
* [CDI/Java EE 集成]({{< ref "/user-guide/cdi-java-ee-integration/_index.md" >}})
* [Runtime 容器集成]({{< ref "/user-guide/runtime-container-integration/_index.md" >}}) (与应用服务器基础架构集成。)

# 建模工具

* [Camunda Modeler]({{< ref "/modeler/_index.md" >}}): BPMN 2.0和CMMN 1.1图表以及DMN 1.3决策表的建模工具。
* [bpmn.io](http://bpmn.io/): 用于建模框架和工具包的开源项目。

# Web应用

* [REST API]({{< ref "/reference/rest/_index.md" >}}) REST API允许你使用远程应用或JavaScript应用的流程引擎。 （注意：REST API的文档已成为自己的文档。）
* [Camunda Tasklist]({{< ref "/webapps/tasklist/_index.md" >}}) 用于人工流管理和用户任务的Web应用，允许流程参与者检查其工作流任务并导航到任务表单，以便在任务上工作并提供数据输入。
* [Camunda Cockpit]({{< ref "/webapps/cockpit/_index.md" >}}) 用于过程监视和操作的Web应用，允许你搜索流程实例，检查其状态并修复损坏的实例。
* [Camunda Admin]({{< ref "/webapps/admin/_index.md" >}}) 允许你管理用户，组和授权的Web应用。
