#####################
TimesLoop 定次數迴圈
#####################

這是一個最基本的迴圈可直接指定重復執行的次數

例如

.. image:: /images/loopexample.png

在上面的這個例子是說猴子會重復3次 ``step 5, turn left`` ，
在迴圈內的指令前面要加上縮排（在屏幕上顯示為``....``），
加上縮排的動作很簡單只要按下鍵盤的tab鍵。

編程不僅是以正確的順序寫出正確的語句，還要程式碼寫的清晰、簡短並且具有可維護性。

不可像下列這樣

::

 step 10
 turn left
 step 10
 turn left
 step 10
 turn left
 step 10
 turn left

而要像這樣下列這種寫法才是正確的

::

 4.times->
     step 10
     turn left

上列兩段的代碼都是做同一件事，但是第二段是用迴圈的寫法。
程式碼的意思是說將 ``step 10, turn left`` 重復執行4次然後結束，迴圈結束後電腦執行下一段的指令。

點擊 "times" 按鈕時，在你的程式碼中就會出現 ``3.times - >`` 的迴圈結構。

.. image:: /images/timesgif.gif
