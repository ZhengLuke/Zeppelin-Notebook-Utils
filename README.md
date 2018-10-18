# Zeppelin-Notebook-Utils
Zeppelin Notebook is a comprehensive and versatile notebook software mostly used for Big Data analytics, which can be integrated with Python, Scala, JavaScript, Spark, Pig, Hive, SQL, etc. It saves data scientist/ engineer from heavy programming work in developing and maintaining a dynamic web app while provide the functionality and flexibitiy they need to do data analytics and visualzation.
<br>This repo comprise some tricks and utility code for using Zepplin Notebook as a analytics and reporting frontend.
<b>Tricks</b>
<ol>
  <li>Bind python variables to Angular Variable:<br>Due to the limitation of current Zeppelin Notebook release, it only supports binding angular variable in Python when the variable is of string type. By passing using string interpolation and python print function, we can pass python variables to JavaScript then Angular</li>
</ol>
