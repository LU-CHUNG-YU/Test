# Description
練習で自作したクローラーを残します
* ***ニュース取得（Bloomberg）*** は Bloomberg のホームページから指定のキーワードが含まれる記事を抽出する.(https://www.bloomberg.co.jp/)
* ***ニュース取得（Google）*** は Google news から指定のキーワード・条件の検査結果を抽出する.(https://news.google.com/)
* ***指標追跡*** は Yahoo!ファイナンス から指定の銘柄の価格・前日比の情報を抽出し、csvに保存する. また価格の歴史データをプロットする.(https://stocks.finance.yahoo.co.jp/)
* ***インターン探し*** は複数のインターン求人サイトから指定の条件（職種、エリアなど）を満たした記事をスクレイピングし、格納する. 新着求人がなければ「新着求人がない」というメッセージを表示させる. 今のところ対応したサイトは：
  - キャリアバイト：https://careerbaito.com/
  - Infra：https://www.in-fra.jp/long-internship
  - ゼロワン：https://01intern.com
