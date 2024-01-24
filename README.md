- [中文](#Discord机器人框架内核)
- [English](#Discord-Bot-Framework-Kernel)

# Discord机器人框架内核
![doc/discord-bot-framework.drawio.png](https://github.com/retr0-init/discord-bot-framework-doc/blob/master/discord-bot-framework.drawio.png)

如上图所示，这是与模块相结合与互动的内核。其中所有的功能应该是必要、极简的，并且也要为了更好地模块化集成提供极可能多的接口。

模块模板在这里（待办）。为了能让您的模块以最好的方式与内核一起工作，请按照其中的`README.md`中的准则进行开发。

## 如何运行
1. 安装python3. 它的版本应该至少为`3.10`.
2. 在正确配置的python环境下运行`./run.sh`.

# Discord Bot Framework Kernel
![doc/discord-bot-framework-en.drawio.png](https://github.com/retr0-init/discord-bot-framework-doc/blob/master/discord-bot-framework-en.drawio.png)

As shown above, this is the kernel to interact with modules. All features are meant to be essential, minimal while providing as many ports as possible for greater modularity.

The module template is here (TODO). Please follow the template guidelines as stated in its `README.md` file to make it properly work with the kernel.

## How to run it
1. Install python3, whose version is `>=3.10`.
2. Run `./run.sh` under the correct python environment.
