.. 2011/07/23 yanchi 36a165e88363fd6e5b5eb0ae712303dd362545be


Min
===

値が、与えられた制限値以上であることを検証します。

.. code-block:: yaml

    properties:
        age:
            - Min: 1

オプション
----------

* ``limit`` (**デフォルト**, 必須): 制限値
* ``message``: 検証に失敗した場合のエラーメッセージ
