# CAPTCHA_Reader

## 来源 
>https://github.com/Kuri-su/CAPTCHA_Reader

## 兼容PHP低版本
* 7.0以上完全兼容
* 5.6兼容 去掉 PretreatmentTrait CuttingTrait string 形参类型，修改training/AddSamples/AddSamplesAuto.php，126行更改为以下代码
```php
  if ((isset($endFlag) ? $endFlag : false) == true) {
```
* 5.5兼容 去掉 CommonTrait dd(...$vars)限制类型参数，修改为 dd($vars)

## 包含了Vendor文件，下载即用

## 使用说明
* 识别验证码 访问 src/App/index.php
* 训练验证码 访问 training/AddSamples/test.php
* 测试验证码 访问 training/MultipleTests/test.php
* 详细代码说明可参看我写的几个MD文件，关于代码分析和使用说明
