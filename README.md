<h1>Left Shift by Powers of Two!</h1> 

<p><strong>Challenge Description</strong></p>

<p>The left shift operation is similar to multiplication by powers of two.

Sample calculation using the left shift operator (<<):

10 << 3 = 10 * 2^3 = 10 * 8 = 80
-32 << 2 = -32 * 2^2 = -32 * 4 = -128
5 << 2 = 5 * 2^2 = 5 * 4 = 20
Write a function that mimics (without the use of <<) the left shift operator and returns the result from the two given integers.</p>

<p><strong>Example</strong></p> 

<ul>
<li>shiftToLeft(5, 2) ➞ 20</li>
<li>shiftToLeft(10, 3) ➞ 80</li>
<li>shiftToLeft(-32, 2) ➞ -128</li>
<li>shiftToLeft(-6, 5) ➞ -192</li>
<li>shiftToLeft(12, 4) ➞ 192</li>
<li>shiftToLeft(46, 6) ➞ 2944</li>
</ul>

<p><strong>Notes</strong></p>

There will be no negative values for the second parameter y.
<br>
This challenge is more like recreating of the left shift operation, thus, the use of the operator directly is prohibited.
<br>
Alternatively, you can solve this challenge via recursion.
<br>
A recursive version of this challenge can be found via this link.