<div align="center">

<img src="assets/banner.svg" alt="susunola — cloud control plane, local-first tools" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2600&pause=900&color=6EE7D2&center=true&vCenter=true&width=720&height=36&lines=Tencent+Cloud+IaC+%26+Ansible;certificates+that+renew+themselves;CIS+%2F+GxP+baselines+as+code;local-first+tools%2C+zero+tracking" alt="currently building" />

云的控制面，和只在自己机器上跑的小工具。  
基础设施写成代码，证书自己续，基线能扫能修，浏览器里的东西不上传。

</div>

<br>

## 现在在做

| | |
|---|---|
| **控制面** | 腾讯云 Ansible、Landing Zone、Sentinel、组织 SCP |
| **证书** | `wecert` — 一个二进制 + 一份 SQLite，DNS-01，续完绑回 CLB / CDN |
| **基线** | OHBS：主机、镜像、云上 CIS / GxP，能扫、能修、能出报告 |
| **本地** | LightTab、WeScreen、WeSwitch、TravelTime。中英界面，密钥进 Keychain |

## 作品

<table>
<tr>
<td width="50%" valign="top">

**云与合规**

[**ansible-collection-tencentcloud**](https://github.com/susunola/ansible-collection-tencentcloud)  
腾讯云资源的 Ansible Collection。

[**wecert**](https://github.com/susunola/wecert)  
给 CLB 用的 cert-manager。DNSPod / 腾讯云 DNS / Cloudflare / Route 53，ARI 感知，换绑不断流。

[**ohbs-image**](https://github.com/susunola/ohbs-image)  
CIS 加固黄金镜像。13 套 OS profile，Packer + Ansible。

[**ohbs-host**](https://github.com/susunola/ohbs-host) · [**ohbs-cloud**](https://github.com/susunola/ohbs-cloud)  
主机与云上基线。扫、修、漂移，一份代码。

[**tencentcloud-landingzone**](https://github.com/susunola/tencentcloud-landingzone) · [**gxp-landing-zone**](https://github.com/susunola/gxp-landing-zone-tencentcloud)  
控制中心落地，以及 GxP 版本。

[**sentinel policies**](https://github.com/susunola/tencentcloud-sentinel-policies) · [**SCP examples**](https://github.com/susunola/tencentcloud-service-control-policy-examples)  
Terraform 治理，和组织级拒绝清单。

</td>
<td width="50%" valign="top">

**本地工具**

[**wescreen**](https://github.com/susunola/wescreen)  
Edge 录屏扩展。时间线、标记、回放，不经过别人的服务器。

[**lighttab**](https://github.com/susunola/lighttab) · [server](https://github.com/susunola/lighttab-server)  
极简新标签页。农历、搜索、待办、壁纸。默认同步是可选的。

[**WeSwitch**](https://github.com/susunola/WeSwitch)  
macOS 上的 Codex 模型切换。中英界面，钥匙串，改之前先预览和备份。

[**TravelTime**](https://github.com/susunola/TravelTime)  
菜单栏多时区，一键切系统时区。

[**copyin**](https://github.com/susunola/copyin)  
只在浏览器里的文本分享。没有服务器。

[**cloudtab**](https://github.com/susunola/cloudtab)  
Terraform 项目的云成本估算。

</td>
</tr>
</table>

## 栈

<p>
<img alt="Go" src="https://img.shields.io/badge/Go-6ee7d2?style=flat-square&logo=go&logoColor=101418"/>
<img alt="Python" src="https://img.shields.io/badge/Python-e7c07b?style=flat-square&logo=python&logoColor=101418"/>
<img alt="Swift" src="https://img.shields.io/badge/Swift-f4f7f6?style=flat-square&logo=swift&logoColor=101418"/>
<img alt="Terraform" src="https://img.shields.io/badge/Terraform-7ee0d6?style=flat-square&logo=terraform&logoColor=101418"/>
<img alt="Ansible" src="https://img.shields.io/badge/Ansible-c9d1d9?style=flat-square&logo=ansible&logoColor=101418"/>
<img alt="HCL" src="https://img.shields.io/badge/Sentinel%20%2F%20HCL-8b9794?style=flat-square"/>
</p>

腾讯云 · DNSPod · Cloudflare · Let’s Encrypt · Packer · GitHub Actions · SQLite · Chrome / Edge MV3

## 轨迹

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=susunola&show_icons=true&hide_border=true&include_all_commits=true&bg_color=101418&title_color=6ee7d2&text_color=c9d1d9&icon_color=e7c07b" alt="GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=susunola&layout=compact&hide_border=true&langs_count=6&bg_color=101418&title_color=6ee7d2&text_color=c9d1d9" alt="Top languages"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=susunola&bg_color=101418&color=c9d1d9&line=6ee7d2&point=e7c07b&area=true&hide_border=true&custom_title=recent%20commits" alt="contribution graph" width="100%"/>

<img src="https://raw.githubusercontent.com/susunola/susunola/output/github-contribution-grid-snake-dark.svg" alt="contribution snake"/>

</div>

<br>

<div align="center">

<sub>2018 年注册。最近在把云上该自动化的东西，和本地不该上传的东西，分开做干净。</sub>

</div>
