# JDK-9-Release-Note
# Impotant Changes and Information
これはJava9リリースにあたってのドキュメントの和訳版です。訳者の暇つぶしで行ったものなので一部誤りがある可能性がありますがご了承をいただけると幸いです。
元リンク：http://www.oracle.com/technetwork/java/javase/9-relnote-issues-3704069.html

# 概要
この項目は今回のリリースについて重要な変更と情報についての説明です。場合によっては説明の中で問題か変更についての追加された詳細がリンクで提供されています。このページは他で提供されているJDK9のリリースノートの内容と重複していません。
## ![Whats New in JDK 9](http://docs.oracle.com/javase/9/whatsnew/toc.htm#JSNEW-GUID-C23AFD78-C777-460B-8ACE-58BE5EA681F6)
## ![JSR 379: Java SE 9: Annex1](http://cr.openjdk.java.net/~iris/se/9/java-se-9-pr-spec-01/java-se-9-annex-1.html)
あなたはこの２つのドキュメントの中で説明された項目の内容を同じくらいよく知っている必要があるでしょう。
この説明はまたJDK 9への移行時に発生する可能性のある互換性の問題を特定します。特定の互換性の問題については、「JDK 9移行ガイド」を参照してください。

OpenJDK-wikiにある互換性の種類のページはこれらの説明の中で使われてる三種類のJavaプログラムの性能互換性の問題を識別しています。
### ソース
ソース互換性はJavaソースをクラスファイルに変更する時に懸念されています。
### バイナリ
バイナリ互換性はエラーなくリンクする機能が "The Java Language Specification"として定義されています。
### 動き
jdk9の動きの互換性は実行時に実行されるコードの意味論が含まれます。

jdk9のリリースにおける互換性についてのより多くの情報はOpen JDK wikiにある　![Compatibility & Specification Review (CSR)](https://wiki.openjdk.java.net/display/csr/Main) を見てください

# モジュールシステム(箇条書き項目は省略)
JavaSEとJDKは大幅なアップデートがJava platformのモジュールシステム（JSR 376）を使用し、モジュールシステムを使用してJava SEプラットフォームとJDKをモジュール化します。変更による互換性の問題は、JEP 261の「リスクと前提条件」のセクションに記載されており、ここで要約されている紹介によってされています。
