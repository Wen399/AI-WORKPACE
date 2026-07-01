# SOP-PSI

## 项目简介

这是一个供应链 S&OP + PSI 一体化 HTML 系统。

用于：

- 销售预测
- 库存分析
- 采购建议
- 风险预警
- 快照导出

---

## 当前状态

开发中

---

## 项目文件

SKILL.md
AI 开发规则

CHANGELOG.md
项目更新记录

index.html
正式运行版本（后续创建）
# 供应链库销平衡系统

Version
v3.6 Product UI Enterprise

---

## 项目介绍

本项目用于供应链 S&OP / PSI / 库销平衡分析。

支持：

- Excel业务数据导入
- 自动库存计算
- 采购计划计算
- S&OP分析
- 供应商交付分析
- 库龄分析
- 预测质量分析
- Dashboard驾驶舱

本版本仅对 UI / UX 进行了升级。

所有计算逻辑保持不变。

---

## 本版本设计原则

本版本遵循：

Enterprise Dashboard Design

参考：

- SAP Fiori
- Microsoft Power BI
- Apple Soft UI
- FineBI Dashboard

整体设计采用：

- Low Saturation
- Soft UI
- Minimal
- Dashboard First

---

## 设计规范

页面背景

#FDFBF7

普通卡片

#FFFDFC

KPI卡片

#F6E6C8

Primary

#F4B248

Border

#E6D6B8

Shadow

rgba(88,65,32,.06)

取消：

- 重阴影
- 高饱和颜色
- 渐变背景
- 发光效果

统一采用纯色主题。

---

## Dashboard布局

整体布局

顶部：

KPI Summary

中部：

Dashboard

底部：

Detail Table

左侧：

Navigation + Global Filter

---

## KPI规范

统一：

18px Radius

Pure Color

Light Shadow

Center Align

统一高度

---

## 图表规范

统一颜色主题：

Inventory

Blue

Production

Orange

Warning

Light Orange

Risk

Red

Neutral

Gray

Legend颜色与图表颜色统一。

---

## 按钮规范

统一：

40px高度

Primary Orange

Hover

Light Shadow

Rounded

---

## 间距规范

Page

24px

Module

24px

Card

16px

Content

20px

遵循8pt Grid。

---

## 修改范围

仅修改：

HTML

CSS

UI

Layout

Theme

未修改：

JavaScript

计算公式

Excel解析

导入导出

业务逻辑

数据结构

事件绑定

Chart数据

---

## 浏览器

推荐：

Chrome

Edge

不建议：

IE
