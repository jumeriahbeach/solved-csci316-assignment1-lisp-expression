Download Link: https://assignmentchef.com/product/solved-csci316-assignment1-lisp-expression
<br>
<ol>

 <li>Write a Lisp expression that multiplies 30 by the result of 7 minus 2. To do this, you must write a call of the function * with two arguments; the second argument will be a call of the function – with two arguments.</li>

</ol>




2.<strong>[Exercise 1 on page 15 of Wilensky]</strong>  Write Lisp expressions to evaluate each of the following:

<ul>

 <li>3<sup>2</sup> + 4<sup>2 </sup>                          (b) 3*17 + 4*19                         (c) 12<sup>3</sup>+1<sup>3</sup>   (9<sup>3</sup>+10<sup>3</sup>)</li>

</ul>




3.(a) Write a Lisp expression that divides thirty by the result of seven minus three, in such a way that the result is a             rational number (i.e., 15/2).

<ul>

 <li>Write a Lisp expression that divides thirty by the result of seven minus three, in such a way that the result is a</li>

</ul>

floating-point number (i.e., 7.5).  Do <strong><em>not</em></strong> use the FLOAT function.




4.<strong>[Exercise 3 on page 16 of Wilensky]</strong>  Write a Lisp expression that computes the mean of the five numbers eighty-three,      eighty-three, eighty-five, ninety-one, and ninety-seven.  Do this in such a way that the result is rational, and then in such a way      that the result is a floating-point number.  Do <strong><em>not</em></strong> use the FLOAT function.




<ol start="5">

 <li>Lisp always prints rational numbers (fractions) in <em>lowest terms</em>; for example, if you enter the number 20/12 at Clisp’s  &gt;       prompt (with no spaces before or after the “/”)  then Clisp will print the equivalent number  5/3.   Write a number that you      can enter at Clisp’s  &gt;   prompt to determine whether or not the two integers 7,360,001,711 and 58,879,948,151 are relatively      prime.  If they are not relatively prime, then find their greatest common divisor.   (Two integers are said to be <em>relatively prime      </em>or <em>coprime</em> if no integer greater than 1 divides both of them.  For example, 20 and 9 are relatively prime; but 10 and 8 are not      relatively prime because 2 divides both 10 and 8.)</li>

</ol>




6.<strong>[Exercise 4 on p. 16 of Wilensky]</strong>  The Lisp function SQRT returns the non-negative square root of any non-negative real      argument.  Use this function to write two Lisp expressions that evaluate to the roots of the equation <em>x</em><sup>2</sup> – 11<em>x</em> – 1302 = 0.  In      other words, use SQRT to write two Lisp expressions that are respectively equivalent to the following:




(a)                                                                                             (b)                                                                              <sup>−</sup><sup>(</sup><sup>−</sup><sup>11)</sup><sup>+ </sup><sup>(</sup><sup>−</sup><sup>11)</sup><sup>×</sup><sup>(</sup><sup>−</sup><sup>11)</sup><sup>−</sup><sup>4</sup><sup>×</sup><sup>1</sup><sup>×</sup><sup>(</sup><sup>−</sup><sup>1302)                                                  </sup><sup>−</sup><sup>(</sup><sup>−</sup><sup>11)</sup><sup>− </sup><sup>(</sup><sup>−</sup><sup>11)</sup><sup>×</sup><sup>(</sup><sup>−</sup><sup>11)</sup><sup>−</sup><sup>4</sup><sup>×</sup><sup>1</sup><sup>×</sup><sup>(</sup><sup>−</sup><sup>1302)</sup>

2×1                                                                           2×1




7.<strong>[Exercise 7 on p. 17 of Wilensky]</strong> Write a Lisp expression that can be entered at Clisp’s  &gt;  prompt to determine the order in      which Common Lisp evaluates function arguments when it calls a function.   You may assume that the order is either      <em>left-to-right</em> or <em>right-to-left</em>, and that the same order is used in all Common Lisp function calls.   [<strong>Hint</strong>: Consider a function      call (–  &lt;expr&gt;<sub>1</sub>  &lt;expr&gt;<sub>2</sub>).   To  evaluate this call with <em>left-to-right</em> argument evaluation order, do the following: First, evaluate      &lt;expr&gt;<sub>1</sub>;  next, evaluate &lt;expr&gt;<sub>2</sub>; finally, subtract the second result (i.e., the value of &lt;expr&gt;<sub>2</sub>) from the first result (i.e., the      value of &lt;expr&gt;<sub>1</sub>).    To evaluate this call with <em>right-to-left</em> argument evaluation order, do the following: First, evaluate &lt;expr&gt;<sub>2</sub>;      next, evaluate &lt;expr&gt;<sub>1</sub>; finally, subtract the first result (i.e., the value of &lt;expr&gt;<sub>2</sub>) from the second result (i.e., the value of      &lt;expr&gt;<sub>1</sub>).   <em>Normally, both evaluation orders would of course produce the same final value.</em>  <em>But if evaluation of one of the two      arguments has a side-effect, then evaluation order may make a difference</em>. <em> Try to think of an expression </em>(– &lt;expr&gt;<sub>1</sub>  &lt;expr&gt;<sub>2</sub>) <em>      for which one of the argument evaluation orders would produce an error but the other would not.</em>]




*If you wish to use Clisp on a Windows PC, download clisp-2.49-win32-mingw-big.zip by pointing a web browser to<strong>                             </strong><a href="https://sourceforge.net/projects/clisp/files/clisp/2.49/clisp-2.49-win32-mingw-big.zip/download"><strong>https://sourceforge.net/projects/clisp/files/clisp/2.49/clisp-2.49-win32-mingw-big.zip/download</strong></a><a href="https://sourceforge.net/projects/clisp/files/clisp/2.49/clisp-2.49-win32-mingw-big.zip/download">  </a>

and unzip the zip archive to a folder. Then check that the folder contains a file named clisp.exe, and add the folder to your PATH––see,

e.g.<a href="https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/">, </a><a href="https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/">https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/</a><a href="https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/"> i</a>f you don’t know how. After that you should be able to run    Clisp by opening a cmd or powershell window and then entering clisp.




Clisp is also available for a Mac: I use<a href="https://formulae.brew.sh/formula/clisp">d </a><a href="https://formulae.brew.sh/formula/clisp">https://formulae.brew.sh/formula/clisp</a><a href="https://formulae.brew.sh/formula/clisp"> t</a>o install it on my Mac.

<sup> </sup><strong>Note</strong>: You are <strong><em><u>not</u></em></strong> required to install Clisp on your PC or Mac, and I cannot guarantee that you will be able to do so.





