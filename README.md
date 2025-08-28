# Rust 测验系统

一个交互式的 Rust 编程语言学习测验系统，帮助开发者测试和提升对 Rust 核心概念的理解。

## 🚀 项目特性

- **多样化测验内容**：涵盖 Rust 的核心概念和语法特性
- **交互式界面**：现代化的 Web 界面，支持实时答题和即时反馈
- **详细解析**：每道题目都提供详细的答案解析和知识点说明
- **进度跟踪**：实时显示答题进度和得分情况
- **响应式设计**：支持桌面和移动设备访问
- **统一样式**：使用外部 CSS 文件确保所有页面样式一致

## 📚 测验内容

### 当前可用的测验模块：

1.  **基本数据类型** (`rust_data_types_quiz.html`)
2.  **所有权与移动** (`rust_ownership_quiz.html`)
3.  **引用与借用** (`rust_references_quiz.html`)
4.  **结构体** (`rust_structs_quiz.html`)
5.  **枚举与模式匹配** (`rust_enums_patterns_quiz.html`)
6.  **表达式与控制流** (`rust_expressions_quiz.html`)
7.  **错误处理** (`rust_error_handling_quiz.html`)
8.  **Crate 与模块** (`rust_crates_modules_quiz.html`)
9.  **数组、向量和切片** (`rust_arrays_vectors_slices_quiz.html`)
10. **字符串类型** (`rust_string_types_quiz.html`)
11. **Trait 与泛型** (`rust_traits_generics_quiz.html`)
12. **指针类型** (`rust_pointer_types_quiz.html`)
13. **运算符重载** (`rust_operator_overloading_quiz.html`)
14. **类型系统** (`rust_type_system_quiz.html`)


## 🛠️ 技术栈

- **前端**：HTML5, CSS3, JavaScript (ES6+)
- **样式**：自定义 CSS 框架，响应式设计
- **交互**：原生 JavaScript，无外部依赖

## 📁 项目结构

```
rust-quize/
├── index.html                           # 主页面，测验选择界面
├── quiz-styles.css                      # 统一的样式文件
├── rust_data_types_quiz.html            # 基本数据类型测验
├── rust_ownership_quiz.html             #的所有权测验
├── rust_references_quiz.html            # 引用与借用测验
├── rust_structs_quiz.html               # 结构体测验
├── rust_enums_patterns_quiz.html        # 枚举和模式匹配测验
├── rust_expressions_quiz.html           # 表达式测验
├── rust_error_handling_quiz.html        # 错误处理测验
├── rust_crates_modules_quiz.html        # Crate和模块测验
├── rust_arrays_vectors_slices_quiz.html # 数组、向量和切片测验
├── rust_string_types_quiz.html          # 字符串类型测验
├── rust_traits_generics_quiz.html       # Trait和泛型测验
├── rust_pointer_types_quiz.html         # 指针类型测验
├── rust_operator_overloading_quiz.html  # 运算符重载测验
├── rust_type_system_quiz.html           # 类型系统测验
└── README.md                            # 项目说明文档
```

## 🚀 快速开始

### 本地运行

1. **克隆项目**
   ```bash
   git clone <repository-url>
   cd rust-quize
   ```

2. **启动本地服务器**
   ```bash
   # 使用 Python 3
   python -m http.server 8000
   
   # 或使用 Python 2
   python -m SimpleHTTPServer 8000
   
   # 或使用 Node.js
   npx serve .
   ```

3. **访问应用**
   打开浏览器访问 `http://localhost:8000`

### 直接使用

也可以直接在浏览器中打开 `index.html` 文件，但建议使用本地服务器以获得最佳体验。

## 📖 使用说明

### 答题流程

1. **选择测验**：在主页选择想要参加的测验模块
2. **开始答题**：
   - 选择题：点击选项进行选择
   - 简答题：在文本框中输入答案
3. **查看进度**：页面顶部显示当前答题进度
4. **提交测验**：完成所有题目后点击"提交测验"按钮
5. **查看结果**：
   - 查看总分和正确率
   - 点击"查看解析"查看详细答案解析
   - 点击"重新开始"重新进行测验

### 评分标准

- **优秀**：正确率 ≥ 80%
- **良好**：正确率 ≥ 60%
- **需要提升**：正确率 < 60%

## 🎯 学习建议

1. **循序渐进**：建议按照数据类型 → 指针类型 → 字符串类型 → 数组和向量的顺序学习
2. **反复练习**：可以多次进行同一个测验，加深理解
3. **仔细阅读解析**：每道题的解析都包含重要的知识点
4. **实践验证**：建议在 Rust 环境中实际编写代码验证学到的概念

## 🔧 开发说明

### 样式系统

项目使用统一的外部样式文件 `quiz-styles.css`，包含：
- 全局样式和布局
- 响应式设计
- 交互状态样式
- 结果显示样式

### 交互逻辑

所有测验页面使用统一的 JavaScript 交互模式：
- 统一的答案存储结构
- 一致的事件处理逻辑
- 标准化的提交和重置流程

## 🤝 贡献指南

欢迎贡献新的测验内容或改进现有功能：

1. Fork 项目
2. 创建功能分支
3. 提交更改
4. 发起 Pull Request

### 添加新测验

1. 复制现有测验文件作为模板
2. 修改题目内容和答案
3. 确保使用统一的样式和交互逻辑
4. 在主页添加新测验的入口

## 📄 许可证

本项目采用 MIT 许可证，详情请查看 LICENSE 文件。

## 📞 联系方式

如有问题或建议，请通过以下方式联系：
- 提交 Issue
- 发起 Pull Request

---

**Happy Learning Rust! 🦀**