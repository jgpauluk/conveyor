|  Welcome to JShell -- Version 25.0.5
|  For an introduction type: /help intro
$1 ==> 0.30000000000000004
$2 ==> 0.3

This happens because 0.1 + 0.2 is a sum with floating point, which can not always represent decimal values with the same precision as a BigDecimal.
