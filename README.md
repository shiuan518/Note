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

onchange Event

```

onChange Event可以用在像是 input text、textarea(多行的文字輸入欄位)、select option 等 HTML Form 元素上，當元素內容改變時就觸發 onChange Event來執行你所準備好的 JavaScript 程式碼

  function ShowStr(x){
     var Str=document.getElementById(x).value;
     alert(Str);
  }

請隨意輸入幾個文字：<input type="text" id="Str" onchange="ShowStr(this.id)">

當輸入完文字滑鼠移開文字欄位就會觸發onchange Event

```

if ， else if ， else 條件判斷式

```

  var Str = "B";
  
  if(Str == "A")
  {
    document.write("這是A");
  }
  else if(Str == "B")
  {
    document.write("這是B");
  }
  else
  {
     document.write("這是C");
  }

輸出為 這是B。

```
