```
jshell> 0.1+ 0.2
$1 ==> 0.30000000000000004

jshell> new BigDecimal("0.1").add(new BigDecimal("0.2"))
$2 ==> 0.3
```

This happens because 0.1 + 0.2 is a sum with floating point, hence have no exact base-2 form and they are stored slightly rounded. BigDecimal built from string keeps the exact decimal digits.
