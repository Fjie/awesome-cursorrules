# Drupal 11 Awesome CursorRules

这个仓库提供了一个为Drupal 11项目量身定制的**CursorRules**文件。`.cursorrules`文件中定义的规则确保AI生成的代码符合Drupal 11的编码标准、最佳实践和现代架构，利用PHP 8.x、Symfony 6和Drupal的API。

## 目的

本项目的目标是通过为AI工具（如Cursor AI编辑器或VS Code扩展）提供Drupal特定的指导，实现一致、安全和高效的开发体验。这有助于确保所有代码建议：
- 完全兼容Drupal 11。
- 符合Drupal的编码和性能标准。
- 使用模块、主题和API开发的最佳实践进行设计。

## 内容

- **`.cursorrules`**：包含AI行为的详细指导，包括代码结构、命名约定、Drupal API使用、主题化和安全性的指南。
- **`README.md`**：提供项目概述、安装说明和贡献指南。

## 安装

1. **复制规则文件：**  
   将`.cursorrules`文件放置在Drupal 11项目的根目录（即与`composer.json`在同一目录）。

2. **在编辑器中启用：**  
   - 如果您使用Cursor AI编辑器，请确保项目规则已启用（通常通过设置切换）。
   - 对于VS Code用户，请安装[Cursor VS Code扩展](https://marketplace.visualstudio.com/)并使用其命令面板确保`.cursorrules`文件被识别。

3. **提交更改：**  
   添加后，将文件提交到您的仓库，以便与整个开发团队共享规则。

## 参考资料

- [GitHub上的Awesome CursorRules](https://github.com/awesome-cursorrules/awesome-cursorrules)
- [Drupal 11文档](https://www.drupal.org/docs/understanding-drupal)
- [Drupal编码标准(PSR-12)](https://www.drupal.org/docs/develop/standards)

## 贡献

欢迎贡献和改进。如果您有建议或增强，请提出问题或提交拉取请求。

## 许可证

本项目采用MIT许可证。有关更多详情，请参阅[LICENSE](LICENSE)文件。