# Note

提示框

```
  alert('123');
```

一開視窗就執行

```
  window.onload = function() 
    {
      // console.log("window loaded")
    };
```

console.log 偵錯

```
  function myfunction()
    {
    console.log('123');
    }
```

for迴圈

```
  for (i = 0; i < 10; i++) 
    { 
    console.log(i);
    }
    
輸出後會在console裡面出現1~10
```

Global Variable 全域變數與 Local Variable 區域變數

```
  var var1=0;

  function plus()
  {
    var1= var1 + 1;


    alert(var1);

  }
  
  輸出後會在提示框出現1,2,3,4...
  
  在函式（function）內，透過 var 所宣告的變數才能算是 Local Variable 區域變數，
  若沒有使用 var 關鍵字宣告，無論是在哪裡宣告的變數，都會屬於 Global Variable 全域變數的範疇。
  
```
