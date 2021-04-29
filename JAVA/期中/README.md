
#
https://www.javatpoint.com/factorial-program-in-java
```
class FactorialExample{  
 public static void main(String args[]){  
  int i,fact=1;  
  int number=5;//It is the number to calculate factorial    
  for(i=1;i<=number;i++){    
      fact=fact*i;    
  }    
  System.out.println("Factorial of "+number+" is: "+fact);    
 }  
}  
```
#
https://ithelp.ithome.com.tw/articles/10192342
```

傳值呼叫(call by value)
指定另一個變數指向這個值時，電腦會在記憶體中新增(複製)一個新值，讓後來的這個變數指向新的值。

(X,Y) = 28 18
(X,Y) = 36 14


參考呼叫(call by reference)
指定另一個變數指向這物件，這個變數就會指向電腦記憶體中同樣的物件，不會有新的物件在記憶體中被創造出來。

(x,y) = 10 15
(x,y) = 15 10

方法多載（Overloading）是指多個名稱相同但參數個數或型別不同的方法，編譯器依傳入參數的個數、型別與順序決定使用哪一個方法

int mether()[]                 不能多載,回傳直不同但引數值相同
void methed(int a)[]           成功,比int多一個引數
void methed(int b)[]           不能,引數不同
void methed(string s)[]        成功引數相同,型別不同
void methed(int a,string s)[]  成功引數型別不同
void methed(string s ,int a)[] 成功引數型別相同順序不同

```

```
遞迴
static void factorial(int x) {
	if (x == 1)
           return 1;
	else		
	  return (x*factorial(x-1));
	}
	
iterative


ublic class Method1 {
	public static void main(String[] args) {
		factorial(6);
		factorial(9);
	}

	static void factorial(int x) {
		int i = x, j = 1;
		while(i > 0)
			j *= i--;
		System.out.println(x + "! = " + j);
	}
```
```

public class firbonacci
{
	static int fib(int n)
	{
	if (n <= 1)
	   return n;
	return fib(n-1) + fin(n-2);
	}
	
	public static void main (string args[])
	{
	int n = 9;
	system.out.println(fib(n));
	}
}

















```

