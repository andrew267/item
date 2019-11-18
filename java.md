```
public class A{
   string a1;
    int a2;
   public A(){} //default
   public A(String a1,int a2){
         this.a1 = a1;
         this.a2 = a2;
   }
   public static void methodA (){    }
   }
```
```
   public class B{
         public static void main(String[]args){
                A obj1 = new A (); //建立新物件obj1
                A obj2 = new A("資工一A","40"); //建立新物件obj2

```                
```   
  需要執行(呼叫)建構子 --------> 物件Object ---------->副函式
                       (建立)              執行(呼叫)
                      
