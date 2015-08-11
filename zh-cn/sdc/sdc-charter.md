# SDC 项目章程

## 背景

EHR系统的应用越多越广，医疗机构采集的信息的数量和详细程度呈指数级增长。尽管医疗机构使用多种方式、系统来采集患者信息，EHR被视为能给
二次利用(医疗服务质量和患者安全、公共卫生、临床研究)提供实时可用数据的最有可能的数据源。在患者诊疗过程中收集的EHR数据，对于想要通过数据来提升医疗质量和服
务效率而医疗机构越来越重要，特别是讲临床数据和其他数据相关联：临床科研的、患者安全事件上报、公共卫生事件上报、determination of coverage。
比如，某患者正在参加一项临床研究或CER，医生在EHR的系统中想要为其选择合适的eCRF，自动的从EHR系统中抽取出之前录入的数据填充到表单之中，额外的信息
医生可以直接录入。

## 挑战

由于EHR系统之间术语、数据项定义的不统一，EHR数据很少能够用作其他目的。局限性主要在于临床的工作流程通过以非结构化的方式记录患者信息。如果能够以统一的、结构化的方式将EHR数据与其他数据链接起来
，将加速质量和安全的改善、公共卫生和临床科研。

众多医疗健康科研组织和专业协会已经发起了对各自领域的数据采集标准化的项目，在诸如PROMIS,PHenX，FITBIR等。。。。。。。


## 范围

该标准将开发一种标准的数据框架并对其进行校验，这样就可以以结构化的方式从EHR中获取数据，可以与其他目的采集的数据进行整合
* eCRF
* 事件上报
* 监测案例上报
* determination of coverage

该框架包括4类标准来实现数据的结构化采集和存储，包括：
* 用于填写表单、模板的标准化数据项、数据元标准
* 用于设计和定义表单、模板的标准
* 描述EHR如何与表单、模板进行交互的标准
* 如何利用EHR中已有的数据为表单、模板自动赋值的标准

。。。。。。。。

## 价值



## 目标产出物

1、在保护安全和隐私的前提下，通过描述实现特定表单的数据采集和存储的关键条件和业务规则的Use Case来确定功能需求
2、提供易于理解的文档、工具和模型来辅助对表单、模板的定制。
3、对特定表单标准进行试点
4、使用code
5、定义范围中提到的4大类标准
6、
7、
8、

## 标准

可以利用的其他项目或产出物
* 使用统一数据元和标准化评估工具的NLM/NIH的PCOR相关项目，如：
    * Common data elements developed/supported by NIH Institutes, e.g., National Cancer Institute (NCI), National Institute of Neurological Disorders and Stroke (NINDS).
    * Standards and measures developed by the NIH funded project, Patient Reported Outcomes Measurement Information System (PROMIS)
    * PhenX Toolkit measures for use in genome-wide association studies and other large-scale genomic research
    * CDISC CDASH
* 使用统一数据元和标准化评估工具的其他项目
    * Agency for Healthcare Research and Quality (AHRQ) defined ‘Common Formats’ for Patient Safety Event Reporting, which reside in the United States Healthcare Information Knowledgebase (USHIK)
    * CDISC Clinical Data Acquisition Standards Harmonization (CDASH)
    * Biomedical Research Integrated Domain Group (BRIDG)
    * Food & Drug Administration (FDA) Adverse Spontaneous Triggered Events Reporting for Devices (ASTER-D)
* IHE 和CDISC的 RFD规范
* IHE的CRD和RCK规范
* MU标准中的术语标准
* [the S&I Framework's Standards Catalog](https://docs.google.com/spreadsheet/ccc?key=0AlOTOBa8bhDodFpQb2NCYWgzNkFrTl9McXRiaEh2SVE#gid=0)    
* [ONC Challenge Grant Program, Theme 5: Fostering Distributed Population-Level Analytics,](http://statehieresources.org/program-initiatives/challenge-grant-consumer-innovations/) and [SHARPn Project ‘Secondary Use of EHR Data’](http://informatics.mayo.edu/sharp/index.php/Main_Page)中的标准和方法
* 其他S&I项目的标准和框架
* ONC Direct项目


## 参考资料

1、[SDC Initiative Charter](http://wiki.siframework.org/Structured+Data+Capture+Charter+and+Members)
