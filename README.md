<div align="center">
<h1>AD Filter Subscriber</h1>
  <p>
    广告过滤规则订阅器，整合不同来源的规则，帮助你快速构建属于自己的规则集~
  </p>
<!-- Badges -->
<p>
  <img src="https://img.shields.io/github/last-commit/woohong666/ad-filters-subscriber?style=flat-square" alt="last update" />
  <img src="https://img.shields.io/github/forks/woohong666/ad-filters-subscriber?style=flat-square" alt="forks" />
  <img src="https://img.shields.io/github/stars/woohong666/ad-filters-subscriber?style=flat-square" alt="stars" />
  <img src="https://img.shields.io/github/issues/woohong666/ad-filters-subscriber?style=flat-square" alt="open issues" />
  <img src="https://img.shields.io/github/license/woohong666/ad-filters-subscriber?style=flat-square" alt="license" />
</p>

<h4>
    <a href="#a">项目说明</a>
  <span> · </span>
    <a href="#b">快速开始</a>
  <span> · </span>
    <a href="#c">规则订阅</a>
  <span> · </span>
    <a href="#d">问题反馈</a>
  </h4>
</div>

<br/>
<h2 id="a">📔 项目说明</h2>

本项目旨在聚合不同来源、不同格式的广告过滤规则，自由的进行转换和整合。
> ⚠️ 新版不再兼容原配置格式，迁移前务必注意
#### 支持的规则格式
- [x] easylist
- [x] dnsmasq
- [x] clash
- [x] smartdns
- [x] hosts
      ## AbBlock List

广告过滤规则整合，使用 [fordes123/ad-filters-subscriber v2](https://github.com/fordes123/ad-filters-subscriber/tree/v2)
构建

> ⚠️ 此版本尚在测试中，规则转换错误请反馈至 [此处](https://github.com/fordes123/ad-filters-subscriber/issues)

| 文件              | 适用                          |        github        |         ghproxy          |         jsdelivr          |
|-----------------|:----------------------------|:--------------------:|:------------------------:|:-------------------------:|
| `easylist.txt`  | AdGuard、AdBlock 等主流去广告扩展和程序 | [link][easylist-raw] | [link][easylist-ghproxy] | [link][easylist-jsdelivr] |
| `dns.txt`       | AdGuard Home 等基于DNS的过滤工具    |   [link][dns-raw]    |   [link][dns-ghproxy]    |   [link][dns-jsdelivr]    |
| `dnsmasq.conf`  | dnsmasq 及其衍生版本              | [link][dnsmasq-raw]  | [link][dnsmasq-ghproxy]  | [link][dnsmasq-jsdelivr]  |
| `clash.yaml`    | clash 及其衍生版本                |  [link][clash-raw]   |  [link][clash-ghproxy]   |  [link][clash-jsdelivr]   |
| `smartdns.conf` | smartdns                    | [link][smartdns-raw] | [link][smartdns-ghproxy] | [link][smartdns-jsdelivr] |
| `hosts`         | 几乎所有操作系统原生支持                |  [link][hosts-raw]   |  [link][hosts-ghproxy]   |  [link][hosts-jsdelivr]   |
| `private.txt`   | 本仓库维护的私有规则，以 easylist 形式提供  | [link][private-raw]  | [link][private-ghproxy]  | [link][private-jsdelivr]  |

[easylist-raw]: https://raw.githubusercontent.com/woohong666/adblock_list/v2/rule/easylist.txt

[easylist-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/easylist.txt

[easylist-jsdelivr]: https://gcore.jsdelivr.net/gh/woohong666/adblock_list@beta/rule/easylist.txt

[dns-raw]: https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/dns.txt

[dns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/dns.txt

[dns-jsdelivr]: https://gcore.jsdelivr.net/gh/woohong666/adblock_list@beta/rule/dns.txt

[dnsmasq-raw]: https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/dnsmasq.conf

[dnsmasq-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/dnsmasq.conf

[dnsmasq-jsdelivr]: https://gcore.jsdelivr.net/gh/woohong666/adblock_list@beta/rule/dnsmasq.conf

[clash-raw]: https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/clash.yaml

[clash-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/clash.yaml

[clash-jsdelivr]: https://gcore.jsdelivr.net/gh/woohong666/adblock_list@beta/rule/clash.yaml

[smartdns-raw]: https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/smartdns.conf

[smartdns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/smartdns.conf

[smartdns-jsdelivr]: https://gcore.jsdelivr.net/gh/woohong666/adblock_list@beta/rule/smartdns.conf

[hosts-raw]: https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/hosts

[hosts-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/hosts

[hosts-jsdelivr]: https://gcore.jsdelivr.net/gh/woohong666/adblock_list@beta/rule/hosts

[private-raw]: https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/private.txt

[private-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/woohong666/adblock_list/beta/rule/private.txt

[private-jsdelivr]: https://gcore.jsdelivr.net/gh/woohong666/adblock_list@beta/rule/private.txt


<details>
<summary>点击查看上游规则</summary>
<ul>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt">AdGuard 基础过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt">AdGuard 移动广告过滤器</a></li>
    <li><a href="https://adguard.com/kb/zh-CN/general/ad-filtering/adguard-filters/">AdGuard 防跟踪保护过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_17_TrackParam/filter.txt">AdGuard URL跟踪过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt">AdGuard 恼人广告过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_10_Useful/filter.txt">AdGuard 解除搜索广告和自我推销过滤器</a></li>
    <li><a href="https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt">AdGuard 中文过滤器</a></li>
    <li><a href="https://github.com/jdlingyu/ad-wars">ad-wars</a></li>
    <li><a href="https://github.com/TG-Twilight/AWAvenue-Adblock-Rule">AWAvenue-Adblock-Rule</a></li>
    <li><a href="https://raw.githubusercontent.com/Noyllopa/NoAppDownload/master/NoAppDownload.txt">NoAppDownload</a></li>
    <li><a href="https://github.com/Cats-Team/AdRules">Cats-Team/AdRules AdBlock List Lite</a></li>
    <li><a href="https://github.com/badmojr/1Hosts">1Hosts (Lite)</a></li>
    <li><a href="https://github.com/hagezi/dns-blocklists">hagezi/dns-blocklists normal</a></li>
</ul>
</details>
#### 注意事项
1. 仅支持基本规则转换，即域名、通配域名构成的规则，对形如 `||example.org^$popup` 等规则无法转换(合并、去重不受影响)
2. 接受不可避免的缩限，如 `||example.org^` 将拦截 example.org 及其所有子域，但将其转换为 hosts 格式时，将无法匹配子域名。

<br/>
<h2 id="b">🛠️ 快速开始</h2>

### 示例配置

```yaml
application:
  rule:
    #远程规则订阅，path为 http、https地址
    remote:
      - name: 'Subscription 1'               #可选参数: 规则名称，如无将使用 path 作为名称
        path: 'https://example.org/rule.txt' #必要参数: 规则url，仅支持 http/https，不限定响应内容格式
        type:  easylist                      #可选参数: 规则类型：easylist (默认)、dnsmasq、clash、smartdns、hosts

    #本地规则，path为 操作系统支持的绝对或相对路径
    local:
      - name: 'private rule'
        path: '/rule/private.txt'

  output:
    #文件头配置，将自动作为注释添加至每个规则文件开始
    #可使用占位符 ${name}、${type}、${desc} 以及 ${date} (当前日期)
    file_header: |
      ADFS Adblock List
      Title: ${name}
      Last Modified: ${date}
      Homepage: https://github.com/fordes123/ad-filters-subscriber/
    path: rule   #规则文件输出路径，相对路径默认为程序所在路径
    files:
      - name: easylist.txt     #必要参数: 文件名
        type: EASYLIST         #必要参数: 文件类型: easylist、dnsmasq、clash、smartdns、hosts
        desc: 'ADFS EasyList'  #可选参数: 文件描述，可在file_header中通过 ${} 中使用
        filter:                #可选参数: 包含规则的类型，默认全选
          - basic              #基本规则，不包含任何控制、匹配符号, 可以转换为 hosts
          - wildcard           #通配规则，仅使用通配符
          - unknown            #其他规则，如使用了正则、高级修饰符号等，这表示目前无法支持
```

---
本程序基于 `Java21` 编写，使用 `Maven` 进行构建，你可以参照示例配置，编辑 `src/main/resources/application.yml`
，并通过以下任意一种方式快速开始：

#### **本地调试**

```bash
git clone https://github.com/fordes123/ad-filters-subscriber.git
cd ad-filters-subscriber
mvn clean
mvn spring-boot:run
```

#### **Github Action**

- fork 本项目
- 自定义规则订阅 (可选)
    - 参照示例配置，修改配置文件: `src/main/resources/application.yml`
- 打开 `Github Action` 页面，选中左侧 `Update Filters` 授权 `Workflow` 定时执行(⚠ 重要步骤)
- 点击 `Run workflow` 或等待自动执行。执行完成后相应规则生成在配置中指定的目录下

#### **Codespaces**

- 登录 `Github`，点击本仓库右上角 `Code` 按钮，选择并创建新的 `Codespaces`
- 等待 `Codespaces` 启动，即可直接对本项目进行调试

### 如何更新

当源代码存在更新时，(你的)仓库首页会出现如下图提示:
<img src="./screen.png">

此时选择 **Sync fork** 再选择 **Update branch** 即可同步更新.  
(如曾修改过源代码，那么合并可能存在冲突，请谨慎处理)

<br/>
<h2 id="c">🎯 规则订阅</h2>

**⚠ 本仓库不再提供规则订阅，我们更推荐 fork 本项目自行构建规则集.**

下面是使用了本项目进行构建的规则仓库，可在其中寻找合适的规则订阅:
<details>
<summary>点击查看</summary>
<ul>
    <li><a href="https://github.com/xndeye/adblock_list/">xndeye/adblock_list</a></li>
    <p>欢迎提交 issues 或 pr 留下你的仓库地址~</p>
</ul>
</details>

<br/>
<h2 id="d">💬 问题反馈</h2>

- 👉 [issues](https://github.com/fordes123/ad-filters-subscriber/issues)
