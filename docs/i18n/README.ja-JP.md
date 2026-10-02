<p align="center"><img src="../../icon.png" alt="AnchorMC アイコン" width="128"></p>

# AnchorMC

Minecraft 1.8 を基盤とし、PracticePvP、イベント、PartyPvP などを楽しめる現代的な PvP サーバーです。

*Schema’Fox Labs による再構築*

---

[English](../../README.md) · [中文](README.zh.md) · **日本語** · [हिन्दी](README.hi-IN.md)

AnchorMC は、NetherMC（現在は閉鎖）の完全な再構築版として運営される、営利を目的としないコミュニティプロジェクトです。

> 言語版に相違や曖昧さがある場合、サーバーとコミュニティの規則は英語版を基準とします。

> 英語版を含むすべての版の規則の表現、翻訳の相違、曖昧さは、確認と修正のため [Security and quality](https://github.com/SchemaFoxLabs/AnchorMC/security) の **Report a vulnerability** から報告できます。

セキュリティ問題は Security ページの **Report a vulnerability** から報告してください。利用できない場合は、非公開の連絡方法だけを Issue で問い合わせ、脆弱性の詳細は公開しないでください。

_このリポジトリは、サーバーの公開フィードバックと更新履歴の窓口です。_
_ソースコードやデプロイ可能なサーバービルドは含まず、プロジェクトの方針として Pull Request は受け付けていません。_
_フィードバックや不具合報告には Issues をご利用ください。_

## よく使う文書と機能

- [サーバーとコミュニティの規則](SERVER_RULES.ja-JP.md)
- [プレイヤー通報・異議申し立て](https://github.com/Labs-mcdev/AnchorMC-PublicReport/)
- [セキュリティ問題を報告](https://github.com/SchemaFoxLabs/AnchorMC/security)
- [機能提案・フィードバック](https://github.com/SchemaFoxLabs/AnchorMC/issues/new/choose)
- [開発ログ](https://github.com/SchemaFoxLabs/AnchorMC/releases)
- [イベント記録・アーカイブ](../../Events/)
- [クライアント最適化 Mod](https://github.com/Labs-mcdev/VanillaEnhance)
- [ゲームプレイ機能と仕組み](GAMEPLAY_FEATURES.ja-JP.md)
- 公式サイト（soon）

---

## 目次

- [プロジェクトについて](#プロジェクトについて)
- [フィードバックと課題管理](#フィードバックと課題管理)
- [サーバーと基本コマンド](#サーバーと基本コマンド)
- [支援者への特典](#支援者への特典)
- [規則と運営](#規則と運営)
- [プロジェクトの歩み](#プロジェクトの歩み)
- [謝辞](#謝辞)

## プロジェクトについて

AnchorMC は、アジアのプレイヤーに現代的な PvP 体験を提供することを目指す対戦型 Minecraft サーバープロジェクトです。

Schema’Fox Labs が再構築し、保守する AnchorMC は、従来の 1.8 PvP の仕組みに新しい技術、最適化されたインフラ、独創的なゲームプレイを組み合わせています。

昔ながらの Minecraft を保ちながら、新しい体験を届けることを目標としています。

## フィードバックと課題管理

不具合報告、質問、機能提案の前に、[フィードバック規則（英語）](../FeedbackRule_QA-SI.md)をご確認ください。

> [!IMPORTANT]
> 具体的な問題や要望を明確に説明してください。主観的な評価だけの投稿や、実質的な情報のない投稿は処理できない場合があります。

> [!WARNING]
> 投稿が観察した内容を正確に説明していることを確認してください。
>
> 公開 Issue は他の人も閲覧できます。本名、私的な連絡先、個人を特定できる情報、現実の所在地が分かる情報を文章、ログ、スクリーンショットから除いてください。公開後の情報を完全に撤回できるとは限りません。

Staff は対応可能な時間と証拠に応じて処理します。一部のフィードバックは長期間保留となる場合があります。

通常の 1～7 日、繁忙期の 8～30 日は最初の対応または返信の目安にすぎず、特に機能提案ではこれを超える場合があります。調査、解決、処分の期限ではありません。

機能提案は、必要性、実現可能性、開発予定、既存アーキテクチャとの互換性を確認します。

セキュリティに関係しない機能上の不具合は Bug report フォームから報告してください。脆弱性や悪用可能な問題は Security ページから報告してください。

Staff 不在時のプレイヤー通報や Join Block、Feature Block、SubServer Block への異議申し立てには [AnchorMC-PublicReport](https://github.com/Labs-mcdev/AnchorMC-PublicReport/) をご利用ください。

## サーバーと基本コマンド

サーバーを切り替えるには：

```minecraft-command
/server <identification>
```

| サーバー | 内部識別子 | 説明 | Minecraft バージョン |
| :--- | :--- | :--- | :--- |
| Practice | `practice` | 1v1 対戦、イベント、PartyPvP を備えた現代的な Practice PvP | コア 1.8.x；クライアント 1.7.10–1.20.x |
| Bridge | `bridge` | ブリッジ、戦闘、ブロック設置の練習 | コア 1.8.x；クライアント 1.7.10–1.20.x |
| Flat-PVP | `flatpvp/flat` | 強烈なノックバックで相手を倒す対戦 | コア 1.8.x；クライアント 1.7.10–1.20.x |
| Sky PVP | `skypvp` | 資源を集め、さまざまな効果を持つ装備を購入 | コア 1.8.x；クライアント 1.7.10–1.20.x |
| PracticeX | soon | 1.20.x 向けの Practice PvP | コア 1.20.x；クライアント 1.7.10–1.20.x |
| 1.9+ | soon | 剣による対戦 | コア 1.12.2；クライアント 1.7.10–1.20.x |

予算の都合により、プレイヤーの利用がなくなったサーバーは一時停止する場合があります。Practice は通常オンラインを維持します。

## 支援者への特典

重大な脆弱性、バグ、セキュリティ問題の報告が確認され、報酬条件を満たした場合：

- 長期有効の Support Rank。
- 貢献者としての公開紹介（一覧が長くなった場合は別文書に移すことがあります）。

ランクは報告の価値と回数に応じて昇格します。

**Support → SupportX → BugFinder → IssueExpert**

報酬の対象となるかは Staff が確認します。送信や受け付けだけでは報酬は発生しません。購入によらない貢献報酬であり、将来の金銭的支援とは無関係です。

## 規則と運営

- [サーバーとコミュニティの規則](SERVER_RULES.ja-JP.md)
- [ゲームプレイ機能と仕組み](GAMEPLAY_FEATURES.ja-JP.md)
- [サーバーの利用と運営](SERVER_TERMS.ja-JP.md)
- [著作権と第三者コンテンツ](ASSET_RIGHTS.ja-JP.md)

現在、サーバーでは外観、権限、その他の有料コンテンツを販売しておらず、スポンサー支援、寄付、支払いも受け付けていません。将来、正規の Minecraft オンラインアカウントを持つプレイヤーが実際のサーバーホスティング費用を直接支援できる仕組みを検討する可能性があります。導入する場合は開始前に案内します。

## プロジェクトの歩み

元のサーバーは NightCelest と Tiantang が構築しました。Schema’Fox Labs がプロジェクトを再構築し、Alice Tuna と nullindex が技術、システム設計、再構築を担当しました。AnchorMC は従来の PvP の基盤を保ちながら新しい体験を開発しています。

---

## 謝辞

### 元のサーバーの構築者

- [NightCelest](https://github.com/a3087814532)
- Tiantang（公開のソーシャルメディアプロフィールは見つかりませんでした）

### システム、ゲームプレイ、UI/UX 設計、体験アーキテクチャ

- [Alice Tuna](https://github.com/LocalHost0080)

### 技術

- [nullindex](https://github.com/error-nullindex)

### マップリソース提供者

- [Alice Tuna](https://github.com/LocalHost0080)
- [rido](https://builtbybit.com/members/rido.331767/)
- [thegetawxy](https://www.planetminecraft.com/project/slime-arena-duel-pvp/)
- [Redstone Labs](https://builtbybit.com/members/redstone-labs.268653/)
- [betapaste](https://builtbybit.com/members/betapaste.512624/)
- [ColoN_](https://builtbybit.com/members/colon_.468523/)
- [PokyBuilds](https://builtbybit.com/members/pokybuilds.531551/)
- [zsomborr](https://builtbybit.com/members/zsomborr.335177/)
- [Solar Studios](https://builtbybit.com/members/solar-studios.500547/)

マップリソースまたはシステム設計の貢献の登録・修正は `mc-s-reg@schemafoxlabs.com` までご連絡ください。

---

*この優先関係は AnchorMC 自身の規則に限られ、第三者のライセンス、プラットフォームの規則、適用法上排除できない権利を変更しません。*

*Mojang または Microsoft とは関係なく、承認も受けていません。*

Regards,

@SchemaFoxLabs 2026
