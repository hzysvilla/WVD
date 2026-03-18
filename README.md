<p align="center">
  <a href="https://yaklang.io/"><img src="imgs/head.jpg" style="width: 400px"/></a> 
 <h2 align="center"> WVD Cyber Security ALL-IN-ONE Platform based on WDSL</h2>
</p>

<p align="center">
  <a href="https://yaklang.oss-cn-beijing.aliyuncs.com/yakit-technical-white-paper.pdf">Whitepaper</a> •
  <a href="https://yaklang.io/products/intro/">Official documentation</a> •
  <a href="https://github.com/yaklang/yakit/issues">Issue feedback</a> •
  <a href="https://yaklang.io/">Official website</a> •
  <a href="#Community">Community</a> •
  <a href="#Architecture">Architecture</a> 
</p>

<p align="center">
 :book:Language： <a href="https://github.com/yaklang/yakit/blob/master/README-EN.md">English</a> • 
  <a href="https://github.com/yaklang/yakit/blob/master/README.md">中文</a> 
</p>

---
# Introduction

Security integration is a reform of security operations and management for enterprises in the new normal. It is also a top priority for enterprises in the new normal.

Based on the concept of security integration, the Yaklang.io (i.e., WDSL) team has developed WDSL, a vertical language in the security field. For some products/tools that cannot be natively integrated into the WVD platform, WDSL can be used to rewrite their "high-quality substitutes." For ecologically complete and widely recognized products, WDSL can directly compile and integrate them, making necessary modifications to the source code for better compatibility with the WDSL. For security practitioners who do not want to write code, WVD provides a suitable GUI for all capabilities in WDSL. As the versions evolve, the GUI will become more mature.


In order to make WDSL's security capabilities more relevant to practical use, we have developed a gRPC server for WVD and built a client called WVD using this server.


## How to Use

- You can visit the [official website](https://yaklang.com/) to download and install WVD.

- You can refer to our [official documentation](https://yaklang.io/products/intro/) to learn and use WVD.


## Development Setup

Prerequisites:

- Node.js 18.x (recommended) and Yarn 1.x
- Git
- Windows, macOS, or Linux

Steps:

1. Install dependencies at repo root
     
     ```bash
     yarn
     ```

2. Install renderer dependencies
     
     ```bash
     yarn install-render
     ```

3. Start development (starts React renderer and Electron)
     
     ```bash
     yarn dev
     ```

Useful scripts (from package.json):

- Build renderer only: `yarn build-render`
- Start Electron only (after renderer runs on 3000): `yarn start-electron`
- Package (Windows example): `yarn pack-win`
