LeetCode 指南
===

- 语言: Java
- 说明： 每道题在代码头部都添加了我的解题思路和批注，Eg:


        /*****
         * 287. Find the Duplicate Number
         * 题意：n+1个数属于[1~n]，找出重复的那个数
         * 难度：Medium
         * 分类：Array, Two Pointers, Binary Search
         * 思路：如果nums[i]不在对应位置，则和对应位置交换。如果对应位置上也为该数，说明这个数就是重复的数字。这个方法改变了数组。是错误的。
         *      另一种方法，把问题转换成有环链表，找环的起始节点。O(n) O(1) lc142
         *      二分查找，每次看一边数字的个数, O(nlog(n)) O(1)
         * Tips：剑指offer原题
         */

---

### RoadMap
- :soccer: [用户最喜欢的100道题(Top 100 Liked Questions)](./Top100.md)
- :basketball: [面试最容易被问到的题(Top Interview Questions)](./TopInterview.md)
- :hamburger: [我的题解(Problems I have Soved)](#LeetCode-Problems-I-have-Soved)

### LeetCode Problems I have Soved

001 [Java](./code/lc1.java)
| 002 [Java](./code/lc2.java)
| 003 [Java](./code/lc3.java)
| 004 [Java](./code/lc4.java)
| 005 [Java](./code/lc5.java)
| 007 [Java](./code/lc7.java)
| 008 [Java](./code/lc8.java)
| 009 [Java](./code/lc9.java)
| 010 [Java](./code/lc10.java)
| 011 [Java](./code/lc11.java)
| 013 [Java](./code/lc13.java)
| 014 [Java](./code/lc14.java)
| 015 [Java](./code/lc15.java)
| 016 [Java](./code/lc16.java)
| 017 [Java](./code/lc17.java)
| 019 [Java](./code/lc19.java)
| 020 [Java](./code/lc20.java)
| 021 [Java](./code/lc21.java)
| 022 [Java](./code/lc22.java)
| 023 [Java](./code/lc23.java)
| 024 [Java](./code/lc24.java)
| 026 [Java](./code/lc26.java)
| 027 [Java](./code/lc27.java)
| 028 [Java](./code/lc28.java)
| 029 [Java](./code/lc29.java)
| 031 [Java](./code/lc31.java)
| 032 [Java](./code/lc32.java)
| 033 [Java](./code/lc33.java)
| 034 [Java](./code/lc34.java)
| 034 [Java](./code/lc35.java)
| 036 [Java](./code/lc36.java)
| 038 [Java](./code/lc38.java)
| 039 [Java](./code/lc39.java)
| 041 [Java](./code/lc41.java)
| 042 [Java](./code/lc42.java)
| 043 [Java](./code/lc43.java)
| 044 [Java](./code/lc44.java)
| 046 [Java](./code/lc46.java)
| 048 [Java](./code/lc48.java)
| 049 [Java](./code/lc49.java)
| 050 [Java](./code/lc50.java)
| 051 [Java](./code/lc51.java)
| 053 [Java](./code/lc53.java)
| 054 [Java](./code/lc54.java)
| 055 [Java](./code/lc55.java)
| 056 [Java](./code/lc56.java)
| 058 [Java](./code/lc58.java)
| 062 [Java](./code/lc62.java)
| 063 [Java](./code/lc63.java)
| 064 [Java](./code/lc64.java)
| 066 [Java](./code/lc66.java)
| 069 [Java](./code/lc69.java)
| 070 [Java](./code/lc70.java)
| 072 [Java](./code/lc72.java)
| 073 [Java](./code/lc73.java)
| 075 [Java](./code/lc75.java)
| 076 [Java](./code/lc76.java)
| 078 [Java](./code/lc78.java)
| 079 [Java](./code/lc79.java)
| 084 [Java](./code/lc84.java)
| 085 [Java](./code/lc85.java)
| 087 [Java](./code/lc87.java)
| 088 [Java](./code/lc88.java)
| 091 [Java](./code/lc91.java)
| 094 [Java](./code/lc94.java)
| 095 [Java](./code/lc95.java)
| 096 [Java](./code/lc96.java)
| 097 [Java](./code/lc97.java)
| 098 [Java](./code/lc98.java)
| 100 [Java](./code/lc100.java)
| 101 [Java](./code/lc101.java)
| 102 [Java](./code/lc102.java)
| 103 [Java](./code/lc103.java)
| 104 [Java](./code/lc104.java)
| 105 [Java](./code/lc105.java)
| 108 [Java](./code/lc108.java)
| 112 [Java](./code/lc112.java)
| 113 [Java](./code/lc113.java)
| 114 [Java](./code/lc114.java)
| 116 [Java](./code/lc116.java)
| 118 [Java](./code/lc118.java)
| 119 [Java](./code/lc119.java)
| 120 [Java](./code/lc120.java)
| 121 [Java](./code/lc121.java)
| 122 [Java](./code/lc122.java)
| 123 [Java](./code/lc123.java)
| 124 [Java](./code/lc124.java)
| 125 [Java](./code/lc125.java)
| 127 [Java](./code/lc127.java)
| 128 [Java](./code/lc128.java)
| 129 [Java](./code/lc129.java)
| 130 [Java](./code/lc130.java)
| 131 [Java](./code/lc131.java)
| 134 [Java](./code/lc134.java)
| 136 [Java](./code/lc136.java)
| 138 [Java](./code/lc138.java)
| 139 [Java](./code/lc139.java)
| 140 [Java](./code/lc140.java)
| 141 [Java](./code/lc141.java)
| 142 [Java](./code/lc142.java)
| 144 [Java](./code/lc144.java)
| 145 [Java](./code/lc145.java)
| 146 [Java](./code/lc146.java)
| 148 [Java](./code/lc148.java)
| 149 [Java](./code/lc149.java)
| 150 [Java](./code/lc150.java)
| 151 [Java](./code/lc151.java)
| 152 [Java](./code/lc152.java)
| 153 [Java](./code/lc153.java)
| 155 [Java](./code/lc155.java)
| 160 [Java](./code/lc160.java)
| 162 [Java](./code/lc162.java)
| 166 [Java](./code/lc166.java)
| 169 [Java](./code/lc169.java)
| 171 [Java](./code/lc171.java)
| 172 [Java](./code/lc172.java)
| 179 [Java](./code/lc179.java)
| 188 [Java](./code/lc188.java)
| 189 [Java](./code/lc189.java)
| 190 [Java](./code/lc190.java)
| 191 [Java](./code/lc191.java)
| 198 [Java](./code/lc198.java)
| 199 [Java](./code/lc199.java)
| 200 [Java](./code/lc200.java)
| 202 [Java](./code/lc202.java)
| 204 [Java](./code/lc204.java)
| 206 [Java](./code/lc206.java)
| 207 [Java](./code/lc207.java)
| 208 [Java](./code/lc208.java)
| 210 [Java](./code/lc210.java)
| 212 [Java](./code/lc212.java)
| 213 [Java](./code/lc213.java)
| 215 [Java](./code/lc215.java)
| 217 [Java](./code/lc217.java)
| 218 [Java](./code/lc215.java)
| 221 [Java](./code/lc221.java)
| 226 [Java](./code/lc226.java)
| 227 [Java](./code/lc227.java)
| 230 [Java](./code/lc230.java)
| 234 [Java](./code/lc234.java)
| 236 [Java](./code/lc236.java)
| 237 [Java](./code/lc237.java)
| 238 [Java](./code/lc238.java)
| 239 [Java](./code/lc239.java)
| 240 [Java](./code/lc240.java)
| 242 [Java](./code/lc242.java)
| 263 [Java](./code/lc263.java)
| 264 [Java](./code/lc264.java)
| 268 [Java](./code/lc268.java)
| 279 [Java](./code/lc279.java)
| 283 [Java](./code/lc283.java)
| 287 [Java](./code/lc287.java)
| 295 [Java](./code/lc295.java)
| 297 [Java](./code/lc297.java)
| 300 [Java](./code/lc300.java)
| 301 [Java](./code/lc301.java)
| 303 [Java](./code/lc303.java)
| 309 [Java](./code/lc309.java)
| 312 [Java](./code/lc312.java)
| 315 [Java](./code/lc315.java)
| 322 [Java](./code/lc322.java)
| 324 [Java](./code/lc324.java)
| 326 [Java](./code/lc326.java)
| 328 [Java](./code/lc328.java)
| 329 [Java](./code/lc329.java)
| 334 [Java](./code/lc334.java)
| 337 [Java](./code/lc337.java)
| 338 [Java](./code/lc338.java)
| 341 [Java](./code/lc341.java)
| 343 [Java](./code/lc343.java)
| 344 [Java](./code/lc344.java)
| 347 [Java](./code/lc347.java)
| 350 [Java](./code/lc350.java)
| 371 [Java](./code/lc371.java)
| 378 [Java](./code/lc378.java)
| 380 [Java](./code/lc380.java)
| 384 [Java](./code/lc384.java)
| 387 [Java](./code/lc387.java)
| 394 [Java](./code/lc394.java)
| 395 [Java](./code/lc395.java)
| 406 [Java](./code/lc406.java)
| 412 [Java](./code/lc412.java)
| 416 [Java](./code/lc416.java)
| 437 [Java](./code/lc437.java)
| 438 [Java](./code/lc438.java)
| 448 [Java](./code/lc448.java)
| 454 [Java](./code/lc454.java)
| 461 [Java](./code/lc461.java)
| 493 [Java](./code/lc493.java)
| 494 [Java](./code/lc494.java)
| 538 [Java](./code/lc538.java)
| 543 [Java](./code/lc543.java)
| 559 [Java](./code/lc559.java)
| 560 [Java](./code/lc543.java)
| 572 [Java](./code/lc572.java)
| 581 [Java](./code/lc581.java)
| 589 [Java](./code/lc589.java)
| 590 [Java](./code/lc590.java)
| 617 [Java](./code/lc617.java)
| 621 [Java](./code/lc621.java)
| 647 [Java](./code/lc647.java)
| 685 [Java](./code/lc685.java)
| 714 [Java](./code/lc714.java)
| 746 [Java](./code/lc746.java)
| 771 [Java](./code/lc771.java)
| 834 [Java](./code/lc834.java)
| 877 [Java](./code/lc877.java)
| 912 [Java](./code/lc912.java)
| 921 [Java](./code/lc921.java)
| 922 [Java](./code/lc922.java)
| 923 [Java](./code/lc923.java)
| 978 [Java](./code/lc978.java)
| 983 [Java](./code/lc983.java)
| 1025 [Java](./code/lc1025.java)
| 1026 [Java](./code/lc1026.java)
| 1027 [Java](./code/lc1027.java)
| 1028 [Java](./code/lc1028.java)
| 1093 [Java](./code/lc1093.java)
| 1094 [Java](./code/lc1094.java)
