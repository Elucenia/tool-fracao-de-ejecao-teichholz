<!-- ELUCENIA technical documentation · fracao-de-ejecao-teichholz · zh · no clinical/professional/rights approval -->

# 射血分数（Teichholz）与短轴缩短率

[条件、来源与许可](https://elucenia.org/zh/tools/fracao-de-ejecao-teichholz)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 左心室舒张末期内径

`ddve`

cm · 范围: 2–9

### 左心室收缩末期内径

`dsve`

cm · 范围: 1–8

## 方法版本

Teichholz 1976：7 D³/(2.4+D)；EF及线性测量容积；ASE/EACVI 2015背景与几何限制

## 已记录的公式

容积（Teichholz） = 7 ÷ (2.4 + D) × D³ (D单位cm，容积单位mL)

射血分数 = (舒张末容积 − 收缩末容积) ÷ 舒张末容积 × 100

短轴缩短率 = (左室舒张末径 − 左室收缩末径) ÷ 左室舒张末径 × 100

## 限制与适用人群

Teichholz估计依赖心室直径与容积之间的几何关系。原始研究中，无壁运动不协调时一致性良好，而存在壁运动不协调时较差。冠状动脉疾病可能伴局部异常，须谨慎解释；由一个直径计算的射血分数不能代替适合心室几何形态的方法。

## 参考文献

- [Teichholz LE et al. Problems in echocardiographic volume determinations: echocardiographic-angiographic correlations in the presence or absence of asynergy. Am J Cardiol, 1976.](https://doi.org/10.1016/0002-9149(76)90491-4)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
