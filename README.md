# node-app

dev...

## electron

### 主进程 - Main Process

- 可以使用和 **系统对接** 的 **Electron API**：
  - **创建菜单**
  - **上传文件**
  - **等等**
- 创建渲染进程：
  - **Renderer Process**
- 全面支持：
  - **Node.js**

### 渲染进程 - Renderer Process

- **复数**，每个对应一个窗口。
- 每个都是 **一个单独的进程**。
- 全面支持 **Node.js** 和 **DOM API**。
- 可以使用 一部分 **Electron 提供的 API**。

## 进程之间的通讯方式

- Electron 使用 IPC（interprocess communication）在进程之间进行通讯。