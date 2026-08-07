# Security Policy / セキュリティポリシー

[日本語](#日本語) | [English](#english)

---

## 日本語

### 脆弱性のご報告

> [!IMPORTANT]
> **脆弱性に関するご報告は、Issue や Pull Request など公開の場には投稿しないでください。**
> 公開の場に投稿された内容は、修正が提供される前に第三者の目に触れ、悪用される可能性があります。
>
> ご報告は **github@umin.ac.jp** 宛にメールでお願いいたします。

GitHub の非公開報告機能（Private vulnerability reporting）が有効になっているリポジトリでは、該当リポジトリの「Security」タブからご報告いただくこともできます。いずれの方法でも構いません。

### ご報告いただく際にお知らせいただきたい情報

差し支えのない範囲で、以下の情報をお知らせいただけますと、確認と対応が円滑に進みます。

- 対象のリポジトリ名およびバージョン（コミットハッシュ、タグ、リリース番号など）
- 脆弱性の種類および概要
- 再現手順、または再現に必要な条件
- 想定される影響の範囲
- 動作を確認された環境（OS、実行環境、依存ライブラリのバージョンなど）
- 参考情報（該当箇所のコード、ログ、スクリーンショットなど）

すべてが揃っていなくても構いません。判明している範囲でご報告ください。

日本語または英語でご報告いただけます。

### 対応の流れ

1. ご報告を受領次第、受付のご連絡を差し上げます。
2. 内容を確認し、脆弱性に該当するかどうかを判断のうえ、結果をご連絡します。
3. 脆弱性と判断された場合は、影響範囲と深刻度を評価し、修正の方針と見込み時期をご連絡します。
4. 修正を公開し、必要に応じて GitHub Security Advisory 等を通じて情報を公開します。

UMIN センターの業務時間外、および年末年始等の業務休止期間中は、ご連絡までにお時間をいただく場合があります。あらかじめご了承ください。

### 情報公開について

修正が利用可能となるまでの間、ご報告いただいた内容を公開しないでいただきますようお願いいたします。修正の公開後、ご報告者のお名前を謝辞として記載することが可能です。記載の要否およびお名前の表記については、ご報告の際にお知らせください。

### 対象となる範囲

本ポリシーは、**本 Organization（umin-center）で公開しているソフトウェア**を対象とします。

> [!WARNING]
> **UMIN が運用しているサービス（UMIN ID、UMIN メール、UMIN-CTR、INDICE、EPOC など）は、本ポリシーの対象外です。**
>
> 運用サービスに関する脆弱性やセキュリティ上の問題にお気づきの場合は、[UMIN のお問い合わせ窓口](https://www.umin.ac.jp/faq/)へご連絡ください。
>
> また、**UMIN が運用しているサーバやサービスに対して、脆弱性の調査や検証を目的としたアクセスを行わないでください。** 実運用中のシステムであり、医療・研究活動に影響を及ぼす可能性があります。本 Organization で公開しているソフトウェアの検証は、ご自身の環境で行ってください。

### 対象バージョン

原則として、各リポジトリの最新リリースを対象とします。過去のバージョンの取り扱いについては、各リポジトリの `README` に記載がある場合はそれに従います。

### ライセンスと無保証について

本 Organization で公開しているソフトウェアは、各リポジトリの `LICENSE` に定める条件のもとで、無保証で提供されます。脆弱性への対応に努めますが、修正の提供や特定の期日までの対応をお約束するものではありません。

---

## English

### Reporting a vulnerability

> [!IMPORTANT]
> **Please do not report vulnerabilities in public places such as issues or pull requests.**
> Anything posted publicly may be seen and exploited by others before a fix is available.
>
> Please send your report by email to **github@umin.ac.jp**.

For repositories where GitHub's private vulnerability reporting is enabled, you may also submit a report from the "Security" tab of that repository. Either route is fine.

### What to include

Where possible, the following information helps us verify and address the issue efficiently:

- The repository and version affected (commit hash, tag, or release number)
- The type of vulnerability and a summary of the issue
- Steps to reproduce, or the conditions required to reproduce it
- The expected impact
- The environment in which you observed the behaviour (OS, runtime, dependency versions)
- Any supporting material (relevant code, logs, screenshots)

You do not need all of the above. Please report what you have.

Reports may be written in Japanese or English.

### What happens next

1. We will acknowledge your report on receipt.
2. We will review it, determine whether it constitutes a vulnerability, and inform you of the outcome.
3. If it is a vulnerability, we will assess its scope and severity and inform you of our planned remediation and expected timeline.
4. We will publish the fix and, where appropriate, disclose the issue via a GitHub Security Advisory or similar.

Please note that responses may take longer outside UMIN Center business hours and during closure periods such as the new year holidays.

### Disclosure

We ask that you refrain from disclosing the issue publicly until a fix is available. After the fix is published, we are happy to credit you in the acknowledgements. Please let us know when you report whether you would like to be credited, and how you would like your name to appear.

### Scope

This policy covers **software published by this organization (umin-center)**.

> [!WARNING]
> **The services operated by UMIN — UMIN ID, UMIN email, UMIN-CTR, INDICE, EPOC and others — are outside the scope of this policy.**
>
> If you become aware of a vulnerability or security concern in an operational service, please contact us through the [UMIN inquiry form](https://center9.umin.ac.jp/inquiry/en/other/input/).
>
> Please also **do not attempt to probe or test the servers or services operated by UMIN for vulnerabilities.** These are production systems, and such activity may disrupt clinical and research work. Please test software published here in your own environment.

### Supported versions

We address vulnerabilities in the latest release of each repository. Where a repository states a different policy for earlier versions in its `README`, that policy applies.

### License and absence of warranty

Software published by this organization is provided without warranty, under the terms set out in the `LICENSE` of each repository. While we will make efforts to address vulnerabilities, we do not guarantee that a fix will be provided or that it will be provided by any particular date.

---

UMIN Center, the University of Tokyo Hospital
7-3-1 Hongo, Bunkyo-ku, Tokyo 113-8655, Japan
