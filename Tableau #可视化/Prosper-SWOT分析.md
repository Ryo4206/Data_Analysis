
# Tableau故事-Prosper_SWOT分析

## 故事地址

初版和最终版见打包附件

## 总结

该可视化故事讲述了prosper的SWOT分析，利用图表展现了prosper公司的优势、劣势、机会和威胁，并根据swot法则提出了决策建议。

## 设计

1. **S**:这部分仪表盘想要展现prosper的优势，主要有四个方面：交易规模、风险分散、地理限制小、收益率高
  * 交易规模选择了最直观的数值表，希望阅读者一目了然地获取交易规模的数量大小，通过几亿交易额的展现认识到prosper业务量很大；其次使用了条形+线图展现了交易额的增长情况
  * 风险分散方面，希望阅读者知道大部分贷款由不止一个投资者承担风险，选择了饼图来说明比例之高，将投资人分组为1、2-10、10+，可以发现大部分贷款的风险分散给了10个以上投资人
  * 地理限制小方面，将原始数据转换成地理位置，直观地展现在地图上，清晰地看到业务覆盖全美
  * 收益率高方面，希望阅读者明白prosper的收益率一直较高，通过条形+线图展示了业务额和收益率的变化趋势。收益率通过收入减去损失计算，通过平均值线展示平均收益率约为10%，高于传统贷款
2. **W**:这部分仪表盘是展示劣势，prosper目前最大的劣势是已完成的订单坏账率高，其次是收款周期较长
  * 希望阅读者清楚的看到坏账订单的比例，将订单分为坏账、已完成未坏账、逾期还款、进行中，筛选掉进行中订单后，制成最适合观察比例关系的饼图，颜色设置为对比鲜明的蓝红色，坏账订单高达30%
  * 由于5年期贷款是近年才出现的，所以想要展示贷款期限变化的趋势，通过堆积条形图将各期限的贷款构成展现出来，希望可以很好的看出大部分贷款期限大于3年
3. **O**:
  * 希望直观展现出各个部分用户的变化趋势，采用了百分比堆积条形图，通过占比的按时间变化，可以发现高质量用户越来越多
  * 希望对比前后两段时间的坏账率，通过百分比堆积图的高度，直观展现两段时间的坏账率，可以发现引入新的信用数据后，坏账率得到降低
4. **T**:
  * prosper曾在2008年底遭遇政策风险，使其业务发展停止了三年，希望通过线图的来展现中间这停滞的三年，政策风险对于p2p借贷业务非常重要
  * prosper的业务中，债务合并的占比越来越高，这不是一个好信号，可能受外部经济因素影响，潜在的坏账风险升高。照例使用了百分比堆积条形图展现了这个变化趋势，希望清晰的看到占比的增加趋势

## 反馈

**阅读者对初版的意见**：

1. 图形未对齐----调整仪表盘至对齐
2. 错误的看板重点----调整图表大小、增加图表标题序号
3. 缺乏说明----图表标题后增加小字说明
4. 部分图逻辑不强----更换图表
5. 缺少数据提示----增加数据说明

对于故事的展现，阅读者可以理解并得出结论
