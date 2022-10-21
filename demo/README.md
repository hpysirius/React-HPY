### 文章
1. [实现一个组件库](https://shuliqi.github.io/2021/12/02/%E5%A6%82%E4%BD%95%E5%BC%80%E5%8F%91%E4%B8%80%E4%B8%AAreact-UI%E7%BB%84%E4%BB%B6%E5%BA%93/#%E5%89%8D%E6%9C%9F)

### 组件如何调试
本地完成组件的开发之后，在发布到npm 之前，需要在本地调试，避免带着问题上传到npm。那怎么调试呢？ 那就需要用到npm link / yarn link 了。

什么是npm link/ yarn link ？

在本地开发模块的时候， 我们可以使用npm link/ yarn link命令，将模块链接到对应的运行项目中去， 方便地对模块进行调试和测试。