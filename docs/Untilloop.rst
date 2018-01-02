######################
Untilloop until 迴圈
######################

until 迴圈也是一個區塊，它將繼續運行，直到滿足特定的條件，這個條件稱為循環條件。
電腦在執行時會檢查條件，當條件為Fail時，迴圈將持續續進行。直到條件為true，它才會停止。

當我們不小心給了一個無法滿足的條件，迴圈將會持續的執行直到系統崩潰。

.. image:: /images/untilgif.gif

在 CodeMonkey 中我們使用2個迴圈條件： near 和 cat.sleeping。

這邊有個使用 "near" 做為迴圈條件的範例:

::

  Until near mathch
  ....step 1

點擊 `這裡 <near.html>`_ 可以了解更多有關 ``near`` 的條件。

這邊有個使用 "cat.sleeping" 做為迴圈條件的範例:

::

  Until cat.sleeping()
  ....wait()

點擊 `這裡 <Sleepingwait.html>`_ 可以了解更多有關 ``cat.sleeping`` 的條件。

for 迴圈和 until 迴圈有什麼差異？

for 迴圈只對集合中的所有對象執行一次操作，然後停止。

until 迴圈將會持續運作直到滿足條件，如果沒有小心處理可能會造成無限迴圈

點擊 "until" 按鈕時，在你的程式碼中就會出現下列字樣:

::

  until condition
  ....# Your code here
