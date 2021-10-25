# 10/25-27Notes

## 10/25
***EXAM REVIEW***

* .equals // == does NOT work with Doubles instead use:

```java
double sum = .1;
 for(int i =0; i<10; i++){
  sum+=0.1;
  }
  
  sum2 = 11*.01

if(Math.abs(sum-sum2)<DELTA){
  System.out.println("yes");
  }

```

* Make hashmap from arrays

```java
String[] keys = new String[10];
Integer[] values = new Integer[10];

keys[0] = "hello";
values[0] = Integer.valueOf(100);
```

* takes time of nano seconds

```java
public void aha(){
  long before = System.nanoTime();
  for(int i = 0; i < 100; ++i){
    int[] a = new int[i*1000];
  }
  long after = System.nanoTime();
  System.out.println("Difference "+ (after-before));
}
```

* LinkedHashSet

```java
LinkedHashSet<String> llm = new LinkedHashSet<>();
```

* LinkedHashSet adds to the end
* TreeMap sorts
* HashMap adds randomly







## 10/27
