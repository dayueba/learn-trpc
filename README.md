# learn trpc

> 这个trpc是 https://trpc.io/docs/getting-started 不是腾讯的开源的trpc

特点
1. 本身不启动服务，要依赖[adapter](https://trpc.io/docs/server/adapters)
2. 基于http协议，所以不用为了性能去使用它。由于依赖于别的web框架，所以性能比较相当于比较web框架的性能了
3. 适合monorepo
4. 与next.js集成好
5. 适合全栈开发者和先学前端再学后端的

缺点
1. 国内不火，官方文档也没中文，有社区维护的，但是不是最新的，但是有一说一[中文文档](https://trpc.nodejs.cn/docs/quickstart)还是不错的，中文下面还有英文对照版

个人感受
1. 不是全栈 + 不是 monorepo ，并没有很强的欲望取用它
