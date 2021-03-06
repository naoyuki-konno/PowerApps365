# 1. Adaptive Cardsとは

Adaptive Cards はプラットフォームに依存しないユーザーインターフェースの構成要素で、JSONでその構造や標示データが記述されるます。

サービスやアプリはこのユーザーインターフェース側とこのJSONをやり取りすることで、それぞれの実行環境に最適化された表示に変換されます。

Adaptive Cards の重要な特徴は、情報量に富んだカードであることと、ユーザーとのインタラクションが可能であることです。
リッチなユーザーインターフェースを簡単に作れるだけでなく、ユーザーがいつも利用している環境上 (アプリ・サービス) でアクションを起こすようなカード (フォームやボタンでの表示切替) が利用できるため、ユーザーへの負担が少ないことがメリットであると考えられます。

**ここに絵をいれる**

現在サポートされているサービスとして、Bot Framework, Microsoft Teams, Outlook, Windows Timeline等がありますが、基本的にはOS, サービスを問わず提供されているライブラリを利用することでAdaptive Cardsを自身のサービス・アプリ上で展開することが可能です。

**ここにサービスとサポートバージョンの表**

**[ToDo]**

もう少しここで最近の利用され具合とかを書いておく。Teamsでもいいし、PVAでもいいし、Microsoft Searchのカスタマイズ、SPFxやAzureでHostする云々があるからProコード側でも関係がありますよと。


以降では、ローコードを基本として、Power Platformの利用者を中心にAdaptive Cardsの利用・作成方法、サービスへの送信方法について解説し、Graph API, Templating APIを利用した発展的な内容についても概観していきます。

なお、Adaptive Cards のバージョンは執筆時点の最新 (v1.2)を基本とします。