## 分析电商网页转化能力A/B测试

Udacity数据分析入门班项目四

该项目从以下三个方面对电商新旧网页的转换率进行对比：  
* 概率：  
利用pandas计算出新页面转换率和旧页面转换率的概率基本相同  
* 假设检验：  
利用numpy对数据进行抽样分布，得出的P值表明，新页面并没有比旧页面的转化率更高  
* 逻辑回归：  
从不同地区分析对新旧页面的转化率是否有影响，根据逻辑回归得出的结论，不同地区对新旧页面的转化率影响微乎其微  
得出新页面的转化率没有足够的数据表明优于旧页面的转化率，在加长A/B测试周期以得出新结论或者有更新的页面出现之前，可以继续使用旧页面的结论
