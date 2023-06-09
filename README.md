# exHilbert

Hilbert 拓展

众所周知 Hilbert 曲线只能映射边长为 2 的幂的正方形，这个项目以类似 Hilbert 曲线
的方式在任意长宽的矩形上生成遍历顺序

提供两种映射，位置到遍历顺序，与遍历顺序到位置。

## example

```
$ make
$ ./a.out
  0  3  4  5
  1  2  7  6
 14 13  8  9
 15 12 11 10

$ ./a.out 16 9
   0   3   4   5  66  67  68  71  72  75  76  77 138 139 140 143
   1   2   7   6  65  64  69  70  73  74  79  78 137 136 141 142
  14  13   8   9  62  63  58  57  86  85  80  81 134 135 130 129
  15  12  11  10  61  60  59  56  87  84  83  82 133 132 131 128
  16  17  34  35  36  37  54  55  88  89 106 107 108 109 126 127
  19  18  33  32  39  38  53  52  91  90 105 104 111 110 125 124
  20  25  26  31  40  45  46  51  92  97  98 103 112 117 118 123
  21  24  27  30  41  44  47  50  93  96  99 102 113 116 119 122
  22  23  28  29  42  43  48  49  94  95 100 101 114 115 120 121

```
