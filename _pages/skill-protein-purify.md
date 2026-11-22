---
title: 蛋白纯化与 BCA 定量
permalink: /skills/protein-purify/
layout: single
author_profile: true
---

<div style="display: flex;gap:10px;flex-wrap: wrap;margin:1.5rem 0 2rem 0;">
<a href="{{ site.baseurl }}/skills/" style="padding:8px 16px;background:#283747;color:white;border-radius:4px;text-decoration:none;">← 返回技能总览</a>
<a href="{{ site.baseurl }}/skills/cell-culture/" style="padding:8px 16px;background:#eaecee;color:#283747;border-radius:4px;text-decoration:none;">细胞培养</a>
<a href="{{ site.baseurl }}/skills/wb-protocol/" style="padding:8px 16px;background:#eaecee;color:#283747;border-radius:4px;text-decoration:none;">Western Blot</a>
</div>

# 蛋白纯化与 BCA 定量

> 用途：从细胞或组织中获取可定量的总蛋白/重组蛋白，为 WB、酶活检测或下游功能实验提供一致的上样基础。

## 一、总蛋白提取（细胞）

1. 预冷 PBS 洗 2 次，尽量吸干；
2. RIPA（或 NP-40）裂解液加蛋白酶抑制剂，冰上 20–30 min，间隔振荡；
3. 4 ℃、12000 g 离心 15 min，上清即总蛋白液；
4. 立即分装（避免反复冻融），−80 ℃ 保存，定量结果当天记录。

## 二、BCA 定量流程

1. **标准曲线**：BSA 标准品梯度稀释（常见 0、0.125、0.25、0.5、1、2 mg/mL），每点做复孔；
2. **工作液**：A 液:B 液 = 50:1 现配现用，96 孔板每孔 200 μL；
3. **加样**：标准品/样品各 20 μL（样品可先稀释 1:5–1:10 以落入曲线中段）；
4. **孵育与读数**：37 ℃ 30 min，562 nm 读数；
5. **计算**：以标准曲线线性回归求浓度，乘以稀释倍数；R² 应 > 0.99，样品吸光度落在曲线中段才可信。

## 三、重组蛋白纯化（His 标签亲和纯化，简述）

1. 菌体或上清经 0.22 μm 滤膜澄清；
2. Ni-NTA 柱用结合缓冲液平衡；
3. 上样后以含 20 mM 咪唑缓冲液洗去非特异结合；
4. 以 100–250 mM 咪唑梯度洗脱，分段收集；
5. 洗脱峰透析/超滤换缓冲液，SDS-PAGE 验证纯度，BCA 复测浓度后分装冻存。

## 四、质控与常见问题

| 问题 | 原因 | 处理 |
| --- | --- | --- |
| 标准曲线线性差 | 加样误差、气泡、孵育不均 | 复孔、离心去气泡、统一孵育时间 |
| 样品浓度超出曲线 | 未稀释 | 稀释后重测，不强行外推 |
| 平行样品差异大 | 裂解不充分、蛋白降解 | 增加裂解时间、全程冰上操作 |
| 纯化产物杂带多 | 洗涤不足、咪唑浓度偏低 | 增加洗涤体积、优化梯度 |

## 五、记录规范

记录裂解液批号、抑制剂添加情况、稀释倍数、曲线方程与 R²、每个样品的最终浓度。下游 WB 上样量必须以这份定量结果为准，而不是“凭经验加 20 μL”。
