# OperateResult

[![.NET](https://img.shields.io/badge/.NET-8.0-512BD4)](https://dotnet.microsoft.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-x64-lightgrey)](https://github.com/wan-official/OperateResult)

一个用于 .NET 8 的操作结果处理库，提供统一的操作结果封装和错误处理机制。

## ✨ 特性

- 🎯 统一的操作结果返回模式
- 🛡️ 类型安全的错误处理
- 📦 轻量级，无外部依赖
- 🚀 支持 .NET 8
- 💡 简洁的 API 设计

## 📦 安装

### 通过 源码安装


## 🚀 快速开始

### 基本用法

```using
成功的操作结果 var successResult = OperateResult.Success();
带返回值的成功结果 var dataResult = OperateResult.Success("操作成功");
失败的操作结果 var failResult = OperateResult.Fail("操作失败");
检查结果 if (dataResult.IsSuccess) { Console.WriteLine(dataResult.Data); }
```
