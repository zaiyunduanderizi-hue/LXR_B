你是我的仓库协作者。之后每条指令都在指定分支里完成，并提交到该分支，必要时发起 PR。
一律遵守：

TypeScript 严格模式；每个文件 < 200 行，超过就拆分。

所有新增/修改文件都贴完整路径与完整代码；删除/移动文件时给出 diff。

不要引入任何私密信息或真实 API Key；需要时使用 .env.example。

每个阶段结束：本地通过 pnpm typecheck && pnpm lint && pnpm test；提供运行截图/日志。

提交信息遵循 Conventional Commits（feat/chore/fix/test/build 等）。
准备好后回复 “READY”。