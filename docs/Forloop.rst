################
Forloop for 迴圈
################

for 迴圈通常使用於一個集合物件，並且透過持續重複的動作找出集合物件中的每一個物件。

.. image:: /images/forloopgif.gif

for 迴圈主要有兩個部份：loop 變數及陣列。

loop 的變數是由我們指定，它可以是任何的名稱，就好像是 `變數賦值 <Variables.html>`_ ，
一般來說都是使用陣列的一個字母來命名，陣列就是一組包含物件的集合。

舉個例子，我們有一個包含了6支香蕉的陣列，每支香蕉都有它的名字，如 "bananas[0]",
所有香蕉的集合也有一個名稱，這個名稱就是陣列的名如 "bananas"。

當電腦執行 for 迴圈，它會取出集合中的第一個項目做為變數，第一個物件處理完後會處理第二個依此類推。
集合中所有的物件都處理完成時迴圈就會停止。

例如下列這個 for 迴圈：

::

  for b in bananas
  ....turnTo b
  ....step distanceTo b

這個迴圈第一次執行時讀取的狀況如下：

::

  ....turnTo banana[0]
  ....step distanceTo banana[0]

接下來它會讀取下一個 banana:

::

  ....turnTo banana[1]
  ....step distanceTo banana[1]

依此類推，直到所有的 bananas 抓出來處理完成

這個與之前介紹的 times.loop 不一樣
  `times.loop <TimesLoop.html>`_ 是重復執行的特定次數，每次執行都是完全相同的操作。

  而 for 迴圈執行的次數會與集合的數量匹配，並且只有在集合中的所有項目完成所有操作後才會停止。

for 迴圈是如何讀取數值

  for (告訴電腦要執行 for 迴圈)

  b (for 迴圈的變數)

  in (for 迴圈的一部份)

  bananas (陣列名稱)

  ....turnTo b (b 就是陣列中的物件)

  ....step distanceTo b (b 就是陣列中的物件)

  我們必須使用迴圈變數的名稱，而不是在每個函數旁邊寫集合的全名。

巢狀迴圈
  .. image:: /images/double_forloop.png

  何謂巢狀迴圈?就是在 for 迴圈內再加上一個for 迴圈。

  上面這個範例是取自第70關，巢狀迴圈就是一層又一層的迴圈。
  當使用巢狀迴圈時，最內層的會最先被執行，最內層執行完成時會再回上一層的條件決定是否再次執行。

點擊 "for" 按鈕時，在你的程式碼中就會出現下列字樣。

::

  for name in array
  ....# Your code here
