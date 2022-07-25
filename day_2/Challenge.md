# Challenge : day 2 🐣

TODO

# Prerequisites ✅

- Make sure you've read all the instructions on how to complete the challenges.

- Follow along with the daily guide.

# Coding 🧑‍💻

- Challenge 1 : Write a function <strong> <i> nat_to_nat8 </i> </strong> that converts a <strong> Nat n</strong> to a **Nat8**. Make sure that your function never trap.

- Challenge 2 : Write a function <strong> <i> max_number_with_n_bits </i> </strong> that takes a <strong> Nat n</strong> and returns the maximum number than can be represented with only <strong> n</strong>-bits.

- Challenge 3 : Write a function <strong> <i> decimal_to_bits </i> </strong> that takes a <strong> Nat n </strong> and returns a <strong> Text </strong> corresponding to the binary representation of this number. <br/>
  Note : decimal_to_bits(255) -> "11111111".

- Challenge 4 : Write a function <strong><i>capitalize_character </i> </strong> that takes a <strong> Char c </strong> and returns the capitalized version of it.

- Challenge 5 : Write a function <strong><i>capitalize_text </i> </strong> that takes a <strong> Text t </strong> and returns the capitalized version of it.

- Challenge 6 : Write a function <strong><i> is_inside </i> </strong> that takes two arguments : a  <strong> Text t </strong> and a <strong> Char c </strong> and returns a Bool indicating if <strong> c </strong> is inside <strong> t </strong>.

- Challenge 7 : Write a function <strong><i> trim_whitespace </i> </strong> that takes a text <strong> t </strong> and returns the trimmed version of t.
  Note : Trim means removing any leading and trailing spaces from the text : trim_whitespace(" Hello ") -> "Hello".

- Challenge 8 : Write a function <strong><i> duplicated_character </i> </strong> that takes a Text <strong> t </strong> and returns the first duplicated character in t converted to Text.
  Note : The function should return the whole Text if there is no duplicate character : duplicated_character("Hello") -> "l" & duplicated_character("World") -> "World".

- Challenge 9 : Write a function <strong> <i> size_in_bytes </i> </strong> that takes <strong> Text t </strong> and returns the number of bytes this text takes when encoded as UTF-8.

- Challenge 10 :

  1. Watch this video on <a href="https://www.youtube.com/watch?v=xli_FI7CuzA" target="_blank"> bubble sort.</a>
  2. Implement a function <strong><i> bubble_sort </i> </strong> that takes an <strong> array </strong> of natural numbers and returns the <strong> sorted array </strong>.

- Challenge 11 : Write a function <strong> <i> nat_opt_to_nat </i></strong> that takes two parameters : <strong> n </strong> of type <strong> ?Nat </strong> and <strong> m </strong> of type <strong> Nat </strong>. This function will return the value of n if n is <strong> not </strong> <strong> <i> null </strong> </i> and if n is <strong> <i> null </strong> </i> it will default to the value of <strong> m</strong>.

- Challenge 12 : Write a function <strong> <i> day_of_the_week </i></strong> that takes a <strong> Nat n </strong> and returns a Text value corresponding to the day. If n doesn't correspond to any day it will return<strong> <i> null </i></strong>. <br/> <br/>
  <strong> <i> day_of_the_week </i></strong>(1) -> "Monday". <br/>
  <strong> <i> day_of_the_week </i></strong>(7) -> "Sunday". <br/>
  <strong> <i> day_of_the_week </i></strong>(12) -> null. <br/>

- Challenge 13 : Write a function <strong> <i> populate_array </i></strong> that takes an <strong> array [?Nat] </strong> and returns an <strong> array [Nat] </strong> where all <strong> <i> null </strong> </i> values have been replaced by 0. <br/>
  Note : Do <strong> not </strong> use a loop.

- Challenge 14 : Write a function <strong> <i> sum_of_array </i></strong> that takes an <strong> array [Nat] </strong> and returns the sum of a values in the array. <br/>
  Note : Do <strong> not </strong> use a loop.

- Challenge 15 : Write a function <strong> <i> squared_array </i></strong> that takes an<strong> array [Nat] </strong> and returns a new array where each value has been squared. <br/>
  Note : Do <strong> not </strong> use a loop.

- Challenge 16 : Write a function <strong> <i> increase_by_index </i></strong> that takes an <strong> array [Nat] </strong> and returns a new array where each number has been increased by it's corresponding index.<br/>
  Note : <strong> <i> increase_by_index </i></strong>[1, 4, 8, 0] -> [1 + 0, 4 + 1 , 8 + 2 , 0 + 3] = [1,5,10,3] <br/>
  Note 2 : Do <strong> not </strong> use a loop.

- Challenge 17 : Write a higher order function <strong> <i> contains\<A> </i></strong> that takes 3 parameters : an array <strong> [A] </strong>, <strong> a </strong> of type <strong> A </strong> and a function f that takes a tuple of type <strong> (A,A) </strong> and returns a boolean. <br/> This function should return a boolean indicating whether or not <strong> a </strong> is present in the array.

<br/>
<strong> <i> Good luck 🎉 </strong> </i>