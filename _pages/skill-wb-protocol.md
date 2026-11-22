---
title: Western Blot 蛋白免疫印迹
permalink: /skills/wb-protocol/
layout: single
author_profile: true
---

<div style="display: flex;gap:10px;flex-wrap: wrap;margin:1.5rem 0 2rem 0;">
<a href="{{ site.baseurl }}/skills/" style="padding:8px 16px;background:#283747;color:white;border-radius:4px;text-decoration:none;">← 返回技能总览</a>
<a href="{{ site.baseurl }}/skills/cell-culture/" style="padding:8px 16px;background:#eaecee;color:#283747;border-radius:4px;text-decoration:none;">细胞培养</a>
<a href="{{ site.baseurl }}/skills/protein-purify/" style="padding:8px 16px;background:#eaecee;color:#283747;border-radius:4px;text-decoration:none;">蛋白纯化与定量</a>
</div>

# Western Blot 蛋白免疫印迹

> 用途：检测特定蛋白表达水平、验证过表达/敲低效率、比较不同处理组间的蛋白差异。以下为常规流程，抗体稀释比与上样量按实际优化结果执行。

## 一、样品制备

1. 冷 PBS 洗涤细胞 2 次，弃净残液；
2. 加入含蛋白酶抑制剂与磷酸酶抑制剂的 RIPA 裂解液（约每 10⁶ 细胞 100 μL），冰上裂解 20–30 min，期间每 5 min 振荡一次；
3. 4 ℃、12000 g 离心 15 min，取上清；
4. BCA 法测定浓度（见[蛋白纯化与定量]({{ site.baseurl }}/skills/protein-purify/)页）；
5. 按 4:1 加入 5× Loading Buffer，95–100 ℃ 变性 5–10 min，−20 ℃ 分装保存。

## 二、电泳与转膜

1. **配胶**：按目标蛋白分子量选择分离胶浓度（<30 kDa 用 12%–15%，30–100 kDa 用 10%–12%，>100 kDa 用 6%–8%）；
2. **上样**：每孔总蛋白 20–30 μg，两侧加预染 Marker；
3. **电泳**：浓缩胶 80 V 约 30 min，分离胶 120 V 至溴酚蓝到达底部；
4. **转膜**：PVDF 膜甲醇活化 1 min，按“海绵—滤纸—胶—膜—滤纸—海绵”装配，冰浴恒流 200 mA 或恒压 100 V，60–90 min（依分子量调整）。

## 三、封闭、抗体孵育与显影

- 5% 脱脂奶粉/TBST 室温封闭 1 h；
- 一抗 4 ℃ 过夜或室温 2 h，TBST 洗 3 次 × 10 min；
- HRP 标记二抗室温 1 h，TBST 洗 3 次 × 10 min；
- ECL 显影，避免过度曝光；条带定量用 ImageJ，以目的蛋白/内参（GAPDH、β-actin 或 β-tubulin）灰度比值比较。

## 四、结果判断与常见问题

| 问题 | 排查方向 |
| --- | --- |
| 无条带 | 抗体失效、蛋白降解、转膜方向错误、上样量过低 |
| 条带过强/弥散 | 上样过量、曝光过久、胶浓度与分子量不匹配 |
| 背景高 | 封闭不充分、洗涤不足、抗体浓度过高、ECL 试剂老化 |
| 多条非特异带 | 抗体特异性差、样品降解、二抗交叉反应 |
| 内参不齐 | 上样量未校准（必须先做 BCA 定量） |

## 五、可复现性要点

固定上样总量、固定曝光时长区间、每次必带内参与阳性对照；记录胶浓度、抗体批号与稀释比。同一结论至少重复 3 次独立实验，避免用单张“漂亮条带”下结论。
