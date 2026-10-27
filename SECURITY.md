# セキュリティ上の問題の報告

脆弱性や認証情報の漏えいが疑われる場合は、公開のIssueやPRに詳細・秘密情報を書き込まず、
このリポジトリの **Security → Advisories → Report a vulnerability** から非公開で報告してください。

再現手順、影響するバージョン、影響範囲を、秘密情報の値を含めずに記載してください。
対応時期やサポート対象についての個別の約束は、この文書では定めません。

## 自動検査の対応範囲

GitHub Dependency reviewは、GitHubのDependency graphが対応するエコシステムを検査します。
Unity Package Managerは対応外のため、`com.unity.mathematics`・`com.unity.collections`などのUnityパッケージについて、
このチェックの成功はアドバイザリの確認完了を意味しません。Unityの公式セキュリティ情報の確認は別途必要です。
参照: https://docs.github.com/en/code-security/reference/supply-chain-security/dependency-graph-supported-package-ecosystems
