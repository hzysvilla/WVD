<p align="center">
  <a href="https://yaklang.io/"><img src="imgs/head.jpg" style="width: 400px"/></a> 
 <h2 align="center"> YAKIT-A (WVD) Cyber Security ALL-IN-ONE Platform based on Yak language</h2>
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

Based on the concept of security integration, the Yaklang.io team has developed Yaklang, a vertical language in the security field. For some products/tools that cannot be natively integrated into the Yak platform, Yaklang can be used to rewrite their "high-quality substitutes." For ecologically complete and widely recognized products, Yaklang can directly compile and integrate them, making necessary modifications to the source code for better compatibility with the Yaklang language. For security practitioners who do not want to write code, Yakit provides a suitable GUI for all capabilities in Yaklang. As the versions evolve, the GUI will become more mature.


In order to make Yaklang's security capabilities more relevant to practical use, we have developed a gRPC server for Yak and built a client called Yakit using this server.


## How to Use

- You can visit the [official website](https://yaklang.com/) to download and install Yakit.

- You can refer to our [official documentation](https://yaklang.io/products/intro/) to learn and use Yakit.


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

## Community

If you have any constructive feedback or bug reports regarding our product, we welcome everyone to raise an issue.

You can also contact us through our official WeChat account for inquiries or to explore business licensing and partnership opportunities.

If you would like to join our community for discussions or have questions to communicate with our technical team, please contact us.


## Stargazers over time

[![Stargazers over time](https://starchart.cc/yaklang/yakit.svg)](https://starchart.cc/yaklang/yakit)


## Disclaimer

1. This tool is only for legally authorized enterprise security construction behaviors and personal learning behaviors. If you need to test the usability of this tool, please build a virtual environment by yourself.

2. When using this tool for pentesting, you should ensure that the behavior complies with local laws and regulations and has obtained sufficient authorization. Do not scan unauthorized targets.

3. Reverse engineering, decompiling, attempting to decipher the source code, implanting backdoors to spread malware, etc. on this software are prohibited.

4. If you need to use Yakit for commercial purposes, please ensure that you have obtained official authorization; otherwise, we will hold you accountable for any related responsibilities.


If you have any illegal behavior when using this tool, you shall bear the corresponding consequences by yourself, and we will not bear any legal and joint responsibility.

Before installing and using this tool, please read carefully and fully understand the terms

Unless you have fully read, fully understood, and accepted all the terms of this agreement, please do not install and use this tool. Your use behavior or your acceptance of this Agreement in any other express or implied manner shall be deemed to have been read and agreed to be bound by this Agreement

