.. index:: hlist, directive; hlist

リストを横に並べたい
---------------------------

``hlist`` を使います。

このディレクティブは短い文章のリストを含みます。このディレクティブは、水平にも数カラム展開することで、よりコンパクトなリストに変換するか、アイテム間のスペースを小さくします。どちらになるかはビルダー次第です。

水平に展開する機能をサポートしたビルダーでは、 columns オプションを使用して、水平のカラム数の設定をすることができます。デフォルトでは2になっています。

.. code-block:: rst

   .. hlist::
      :columns: <カラム数>

      * リスト
      * ...

適用例
~~~~~~

.. hlist::
   :columns: 3

   * 1番目のリスト
   * 2番目のリスト
   * 3番目のリスト
   * 4番目のリスト
   * 5番目のリスト
