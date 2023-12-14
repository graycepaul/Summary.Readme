<h1>JavaScript Array Methods</h1>
<p>
  JavaScript arrays are zero indexed meaning you count an array starting from
  zero.
</p>
<h3>Array length:</h3>
<p>The length property returns the length (size) of an array</p>

<h3>Array toString() and join() Methods:</h3>
<p>
  The JavaScript method toString() converts an array to a string of (comma
  separated) array values. The join() method also joins all array elements into
  a string. It behaves just like toString(), but in addition you can specify the
  separator
</p>
<h3>Array .pop() and .shift() methods</h3>
<p>
  Array .pop() and .shift() methods are used to remove items from an array.
  However, the .pop() method is used to remove the last item while the .shift()
  method removes the first item of the array.
</p>
<h3>Array .push() and .unshift() methods</h3>
<p>
  Array .push() and .unshift() methods are used to add items to an array. Push()
  method adds a new item to the end while the .unshift() method adds the new
  item to the beginning of the array.
</p>
<h3>Array Delete Method</h3>
<p>
  The delete operator or method deletes an item from the array but retains the
  space where the deleted item used to sit.Using delete leaves undefined holes
  in the array hence, it is advised to use pop() or shift() instead.
</p>
<h3>Array .concat() method</h3>
<p>
  The concat() method creates a new array by merging (concatenating) existing
  arrays. The concat() method does not change the existing arrays but always
  returns a new array.
</p>
<h3>Array flat() method</h3>
<p>
  Flattening an array is the process of reducing the dimensionality of an array.
  The flat() method creates a new array with sub-array elements concatenated to
  a specified depth.
</p>
<h3>Array .slice() and splice() methods</h3>
<p>
  The splice() method adds new items to an array. The first parameter defines
  the position where new elements should be added (spliced in) and the second
  parameter defines how many elements should be removed followed by the item(s)
  to be added.
</p>
The slice() method on the other hand slices out a piece of an array into a new
array.
<h3>Automatic toString()</h3>
<p>
  JavaScript automatically converts an array to a comma separated string when a
  primitive value is expected.
</p>
<br />

<h2>Function</h2>
<p>
  A JavaScript function is a block of code designed to perform a particular task
  and is executed when "something" invokes it (calls it). A function cam be
  called using the function name and the parenthesis where in the arguments or
  values are passed. The argument passed allows us to build a new instance of
  the function.
</p>
<h3>Function Syntax</h3>
<p>
  A JavaScript function is defined with the function keyword, followed by a
  name( can contain letters, digits, underscores, and dollar signs), followed by
  parentheses (). The parentheses may include parameter names separated by
  commas: (parameter1, parameter2, ...) The code to be executed, by the
  function, is placed inside curly brackets: {}.
</p>
<h3>Function Return</h3>
<p>
  A javaScript function will stop executing when JavaScript reaches a return
  statement. If the function was invoked from a statement, JavaScript will
  "return" to execute the code after the invoking statement.
</p>
<p>
  One function call can only return one value, but you can simulate the effect
  of returning multiple values by returning an object or array and destructuring
  the result.
</p>
<p>JavaScript has four kinds of functions:</p>
<ul>
  <li>
    Regular function: can return anything; always runs to completion after
    invocation
  </li>
  <li>
    Generator function: returns a Generator object; can be paused and resumed
    with the yield operator
  </li>
  <li>
    Async function: returns a Promise; can be paused and resumed with the await
    operator
  </li>
  <li>
    Async generator function: returns an AsyncGenerator object; both the await
    and yield operators can be used
  </li>
</ul>
<h3>Function parameters</h3>
<p>
  Each function parameter is a simple identifier that you can access in the
  local scope. There are three special parameter syntaxes:
</p>
<ul>
  <li>
    Default parameters allow formal parameters to be initialized with default
    values if no value or undefined is passed.
  </li>
  <li>
    The rest parameter allows representing an indefinite number of arguments as
    an array.
  </li>
  <li>
    Destructuring allows unpacking elements from arrays, or properties from
    objects, into distinct variables.
  </li>
</ul>
<br />
<h2>Control Flow Statement</h2>
<p>
  Control flow statements are one of the fundamental parts of Programming
  language. They allow us control the order our statements gets executed based
  on if the meet certain conditions.
</p>
<p>Javascript has three main types of control statements namely:</p>
<h3>if/else Statements:</h3>
<p>
  The if…else statement executes a block of code if a specified condition is
  true. If the condition is false, another block of code can be executed.
</p>
<h3>Switch Statements:</h3>
<p>
  Switch statements are used to execute a block of code based on the value of a
  variable or expression.
</p>
<p>
  The case part of the statement hold the values to be compared with the
  variable or expression. It usually also have a break after each case to allow
  the switch statement to stop running once a condition has been met. The
  default condition holds the code to be executed if none of the conditions are
  met.
</p>
<h3>Loops:</h3>
<p>
  There are two main types of loops in JavaScript: for loops and while loops.
</p>
<p>
  There are two main types of loops in Javascript. The for and while loop:
  for-loops and while loops
</p>
<h3>For Loops</h3>
<p>A for loop repeats until a specified condition evaluates to false.</p>
<p>
  A for statement looks as follows: for (initialization; condition;
  afterthought) statement
</p>
<h3>While and Do-While loops</h3>
<p>
  A while loop simply repeats itself while something is true. Theoretically a
  while loop can loop forever. It continues until the condition is false.
</p>
<p>
  The while loop executes a specified statement as long as the test condition
  evaluates to true. The do…while loop will first execute the code, then
  continue while the condition remains true.
</p>
