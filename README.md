#  关系型数据 CSV 导入图数据 Neo4j --zhangdong
演示了将CSV数据导入Neo4j的不同方法以及该过程中可能出现的潜在问题的解决方案。
CSV是一个用逗号分隔的值的文件，通常在Excel或其他电子表格工具中查看。可以使用其他类型的值作为定界符，但最标准的是逗号。如今，许多系统和流程已经将其数据转换为CSV格式，以便将文件输出到其他系统，人性化的报告以及其他需求。这是人类和系统已经熟悉的使用和处理的标准文件格式。

为Neo4j提供读取和加载CSV文件的功能有助于减少将数据从各种格式和系统导入Neo4j的麻烦
