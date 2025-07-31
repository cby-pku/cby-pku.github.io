# Google Scholar 引用数据更新指南

本文档说明如何更新您主页上的Google Scholar引用统计数据。

## 📊 当前引用统计

从最近更新的数据来看：
- **总引用数**: 1044
- **h指数**: 8
- **i10指数**: 7

## 🔄 更新方式

### 方式一：GitHub Actions 自动更新（推荐）

#### 1. 自动定时更新
系统已配置为每天早上8点（UTC时间）自动更新引用数据。

#### 2. 手动触发更新
我已经为您的GitHub Actions添加了手动触发功能：

1. 访问您的GitHub仓库
2. 点击 "Actions" 标签
3. 选择 "Get Citation Data" 工作流
4. 点击 "Run workflow" 按钮
5. 可选择性地添加更新原因
6. 点击绿色的 "Run workflow" 按钮

### 方式二：本地手动更新

#### 安装依赖
```bash
# 安装Python依赖
pip3 install scholarly==1.5.1 jsonpickle==1.4.2
```

#### 运行更新脚本
```bash
# 在网站根目录运行
python3 update_citations.py
```

#### 提交更改
更新完成后，将生成的文件提交到Git：
```bash
git add google-scholar-stats/
git commit -m "更新引用数据"
git push
```

## 📝 引用显示配置

### 已配置的论文引用

以下论文已在主页中配置了引用显示：

- **Language Models Resist Alignment** (ACL 2025 Best Paper): 8 引用
- **PKU-SafeRLHF**: 44 引用  
- **Aligner** (NeurIPS 2024 Oral): 90 引用
- **BEAVERTAILS** (NeurIPS 2023): 494 引用
- **Align Anything**: 11 引用
- **AI Alignment Survey**: 338 引用
- **InterMT**: 0 引用（已启用显示）

### 添加新论文引用

如需为新论文添加引用统计，请：

1. 获取Google Scholar论文ID：
   - 访问您的Google Scholar主页
   - 点击论文标题
   - 从URL中的 `citation_for_view=XXXX` 提取ID

2. 在`_pages/about.md`中添加引用标签：
   ```html
   <strong><span class='show_paper_citations' data='您的论文ID'></span></strong>
   ```

## 🔧 故障排除

### 常见问题

1. **引用数据不显示**
   - 检查论文ID是否正确
   - 确认论文已被Google Scholar索引
   - 检查JavaScript控制台是否有错误

2. **自动更新失败**
   - 检查GitHub Secrets中的 `GOOGLE_SCHOLAR_ID` 设置
   - 查看Actions运行日志

3. **本地更新失败**
   - 确认已安装正确版本的依赖
   - 检查网络连接到Google Scholar

### 调试信息

前端JavaScript会在浏览器控制台输出调试信息，包括：
- 数据文件加载状态
- 找到的引用元素数量
- 各论文的引用数据

## 📈 数据文件结构

系统生成两个主要文件：

1. **`google-scholar-stats/gs_data.json`**: 完整的作者和论文数据
2. **`google-scholar-stats/gs_data_shieldsio.json`**: 简化格式，用于badges

## 💡 最佳实践

1. **定期检查**: 虽然有自动更新，建议偶尔手动检查数据准确性
2. **新论文**: 新发表的论文可能需要几天才会出现在Google Scholar中
3. **备份**: 重要更新前建议备份现有数据

---

如有任何问题，请查看GitHub Actions日志或在Issues中提出。 