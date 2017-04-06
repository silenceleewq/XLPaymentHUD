# XLPaymentHUD
iOS 仿照支付宝支付动画

### 显示效果

<img src="https://github.com/mengxianliang/XLPaymentHUD/blob/master/GIF/1.gif" width=300 height=538 />

### 使用方法

* 显示/隐藏 付款中动画
```objc
[XLPaymentLoadingHUD showIn:self.view];
[XLPaymentLoadingHUD hideIn:self.view];
```
* 显示/隐藏 付款完成动画
```objc
[XLPaymentSuccessHUD showIn:self.view];
[XLPaymentSuccessHUD hideIn:self.view];
```
