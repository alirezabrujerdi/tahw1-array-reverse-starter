# TA HW 1 - Reverse Array - 20 Points

[![Grader Status](https://kntu-grader.herokuapp.com/minimal?repo=alirezabrujerdi/tahw1-array-reverse-starter&id=9725073)](https://kntu-grader.herokuapp.com/minimal?repo=alirezabrujerdi/tahw1-array-reverse-starter&id=9725073)




# Assignment discription

<div dir="rtl" align="right">
برنامه ای بنویسید که آرگمان های داده شده توسط کامند لاین را به شکل برعکس شده نشان دهد.

برای اینکار بدنه متد داده شده را به گونه ای تکمیل کنید که یک آرایه دریافت کند و همان آرایه را بدون هیچ آرایه کمکی بتواند برعکس کند. امضای متد تعریف شده را تغییر ندهید.
</div>



```java
package ir.ac.kntu;

import java.util.Arrays;

public class ArrayReverse{
    public static void reverse(String[] array){
        //complete the body of this method
        //don't reverse using a helper array
    }
    public static void main(String[] args){

        reverse(args);
        //show reversed array
        System.out.println("args = " + Arrays.toString(args));
    }

}
```
