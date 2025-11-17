https://tsai002.github.io/

将博客引擎从 jekyll 迁移到了 [Zola](https://www.getzola.org/)（Powered by Rust）。追求最小依赖和最大页面加载速度，做了一点改进。

- 如果页面不使用 Latex，不会加载相关组件。如果页面使用了 Latex，只需要添加 `latex = true`
- 仅使用了 [typo.css](https://github.com/sofish/typo.css/)
