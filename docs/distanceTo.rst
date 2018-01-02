########################
distanceTo 物件的距離
########################

``distanceTo`` 通常與其他的命令一起使用如 ``step`` 或 ``say`` 及一個物件。

使用 ``distanceTo`` 時很像是在問一個問題：

"物件與香蕉距離多遠？"而答案是一個電腦算出來整數代表距離。

例如:

::

  step distanceTo banana

使用 ``distanceTo`` 時電腦會計算出猴子與物件(香蕉)的距離，這個數值就會成為 ``step`` 的參數。

這個方法可以節省我們的時間，也可以幫助我們知道物件的位置。

另一種使用方法是將 ``distanceTo`` 做為一個變數：

::

  x = distanceTo banana
  step x

在這個範例中，電腦會算出香蕉與猴子的距離並且將這個數值代入 X，並做為 ``step`` 的參數。

``distanceTo`` 是一個函數: 執行特定任務的一組指令。

``distanceTo banana`` 是名為(distanceTo)的函數加上(banana)的參數所組成的指令。

``distanceTo`` 的參數是我們想要測量距離的物體，如香蕉或灌木。
例如: ``step distanceTo banana`` 中， ``distanceTo`` 的參數是香蕉，回傳值就成為 ``step`` 的參數。

CodeMonkey 的工程師相當貼心為了節省我們的時間已經幫我們寫好 "step" 這個函數。

在實際的編程工作上，使用別人寫好的函數也是相當常見並且使用的方法。

點擊 `這裡 <Function.html>`_ 可以了解更多有關函數的資訊。

點擊 "distanceTo" 按鈕時，在你的程式碼中就會出現 "distanceTo" 的字樣。

.. image:: /images/xdistanceTogif.gif
