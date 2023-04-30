Download Link: https://assignmentchef.com/product/solved-cs301-assignment-11
<br>
<span class="kksr-muted">Rate this product</span>

Q 1) Consider a 1kB, byte-addressable, direct-mapped cache with line size of 64 bytes. Consider the following sequence of accesses (16 bit addresses in hexadecimal format): 0x0001, 0x0002, 0x0003, 0x0041, 0x0081, 0x00A1, 0x00C1, 0x0401, 0x0402, 0x0001,

0x0002, 0x0003.The LSB bits are used to determine the offset within the line.How many cache hits occur? Assume the cache is entirely empty at the beginning.

Q 2)  What if the cache in Q 1) was 2-way set associative?

Q 3)  ​Consider a 128B, 4-way set associative cache, with line size 16B. The memory is byte-addressable. Can you come up with a sequence of addresses where

<ul>

 <li>●  The LRU replacement policy performs better than LFU</li>

 <li>●  The LFU replacement policy performs better than LRU</li>

</ul>

Q 4) [5 marks] How do your answers change if the cache is fully associative?

Q 5) [5 marks] Consider a fully associative cache following the LRU replacement scheme and consisting of only 8 words. Consider the following sequence of memory accesses (the numbers denote word address):

20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 22, 30, 21, 23, 31Assume a line size of 2 words. Assume that we begin when the cache is empty.

<ul>

 <li>●  What is the hit rate?</li>

 <li>●  What are the contents of the cache at the end?Q 6) [5 marks] What if the cache in Q 5) was 2-way associative?</li>