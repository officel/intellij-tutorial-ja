# IntelliJ IDEA Editor Tutorial Ja - php -

## はじめに

* PHP を使うにあたっての設定とか便利機能とか書きたい
* PHPStormとの違いとかイマイチわからないけど

## 目次

* Code Style : コーディングスタイルの設定
* PHP : 設定の PHP の項について



## さくっとメモ

* PHPUnit
    * PHPUnit でテストコードを書くと、PHPUnit_Framework_TestCase などが黄色になる
    * PHPUnit のパスが伝わってないのが原因
        * File - Settings - Project Setting - PHP の Include Path に PHPUnit のあるPATHを追加
        * Windows で XAMPP なら C:\xampp\php\pear など。


* if (true) func(); 的なコードを修正したい時
    * func(); 部分を CTRL + w 等で選択しておいて、CTRL+ALT+Tで Surround with で{}を選択
    * コードフォーマットの設定（Settings - Code Style - PHP - Wrapping and Braces - if() statement - Force braces を Always に）