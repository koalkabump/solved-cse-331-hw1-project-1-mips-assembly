Download Link: https://assignmentchef.com/product/solved-cse-331-hw1-project-1-mips-assembly
<br>
CSE 331 Computer OrganizationProject 1 – MIPS AssemblyMin-Set-Cover problem is used to find the least number of sets that can cover the union of all given sets.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/187.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/187.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Write an assembly program that takes different sets Si and then returns the indices of the sets so that the minimum number of sets are chosen. And the union of these sets is equal to the union of all sets as explained in the above definition.Actually optimal solution for that problem has no known polynomial time solution. It is an NP-complete problem. Therefore, you will implement a sub-optimal greedy heuristic solution for the problem as shown below:

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/162.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/162.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>BONUS:Taking all sets from a text file instead of MIPS console is a bonus with extra 25pts.In order to read a file you have to use syscall code 13 to open file and code 14 to read file. Details can be found here:http://courses.missouristate.edu/kenvollmar/mars/help/syscallhelp.htmlHonor code: It is not a group project. Do not take any code from Internet. Any cheating means at least -100 for both sides. Do not share your codes and design to any one in any circumstance. Do not forget, this is named as HONOR code. Be honest and uncorrupt not to win but because it is RIGHT!

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/771.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/771.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>