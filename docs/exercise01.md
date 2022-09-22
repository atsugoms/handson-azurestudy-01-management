# Exercise1: Azure利用準備

## 【目次】

![](images/e01-0000-prepare.png)

1. [Azureポータルへアクセス](#azureポータルへアクセス)
2. [MFA(Multi Factor Authentication)設定](#mfamulti-factor-authentication設定)


## Azureポータルへアクセス

1. アカウント作成ができていない場合、あらかじめアカウント作成しておく

    [Azure の無料アカウント](https://azure.microsoft.com/ja-jp/free/dotnet/)

1. 「Azureポータル」へアクセスしてログイン

    [Azure ポータル（https://portal.azure.com/）](https://portal.azure.com/)


## MFA(Multi Factor Authentication)設定

MFA設定はログインしているアカウントの種類によって画面遷移が若干異なります。
ログインしているアカウントの種類に応じて手順を確認してください。

* [Microsoftアカウントの場合](#microsoftアカウントの場合)
* [組織アカウントの場合](#組織アカウントの場合)


### 【Microsoftアカウントの場合】

1. Azureポータルへログイン
1. 画面右上のアカウント名を展開

    ![](./images/e01-0201-mfa.png)

1. 「Microsoftアカウント」を選択

    ![](./images/e01-0202-mfa.png)

1. 「Microsoftアカウント」ページ上部メニューから「セキュリティ」を選択

    ![](./images/e01-0203-mfa.png)

1. 「高度なセキュリティオプション」を選択

    ![](./images/e01-0204-mfa.png)

1. 「2段階認証」を選択

    ![](./images/e01-0205-mfa.png)

1. ガイドに従ってMFA設定

    ![](./images/e01-0206-mfa.png)



### 【組織アカウントの場合】

1. Azureポータルへログイン
1. 画面右上のアカウント名を展開

    ![](./images/e01-0301-mfa.png)

1. 「アカウントを表示」

    ![](./images/e01-0302-mfa.png)

1. 「マイアカウント」ページ左メニューから「セキュリティ情報」を選択

    ![](./images/e01-0303-mfa.png)

1. 「サイインインの方法の追加」を選択

    ![](./images/e01-0304-mfa.png)

1. 「認証アプリ」を選択して「追加」

    ![](./images/e01-0305-mfa.png)

1. ガイドに従ってMFA設定

    ![](./images/e01-0306-mfa.png)





