# crypto-tradingview

## 基本概念
* ema函数返回指数加权移动平均值。 在ema中，权重因子呈指数下降。 它使用以下公式进行计算： EMA = alpha * source + （1 - alpha） * EMA[1] , 其中 alpha = 2 / （length + 1） . source 指的是指数移动平均线， alpha = 2 / （长度 + 1）.
* sma函数返回移动平均值，即 x 的最后 y 值，除以 y。 
* close（内置变量） 当前 k 线关闭时的收盘价，或尚未完成的实时 k 线的最后交易价格。
* 
