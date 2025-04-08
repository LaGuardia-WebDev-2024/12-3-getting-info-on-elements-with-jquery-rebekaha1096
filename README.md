# 12-3-Getting-Info-on-Elements-with-jQuery

## Video

[Video](https://youtu.be/nf5lCuLCpwQ) <-- Make sure to watch this video first<br>

## Directions

### Step #1 - Find the math heading <br>

This webpage displays famous discoveries using HTML headings and lists. In this first step, use jQuery to find the math heading (with id='math-heading') and store it in a variable named math.  If you'd like, you can use console.log() to see what's stored in the variable.
<br><br>
_Hint:_<br>`var math = $(_);`
<br><br>
### Step #2 - Change the math heading <br>
Now use jQuery to change the math heading to be the previous text plus an exclamation like ' ...wow!' or '...amazing!'.
<br><br>
_Hint:_<br>`$(_).text(math + "...")`

### Step #3 - Change the science heading <br>
Now follow the same steps for the science heading: use jQuery to find the element with id='science-heading', store it in a variable named science, and change its text to be the previous text plus some new exciting text. 
<br><br>
_Hint:_<br>`var sci = $(_);`<br>`$(_).text(math + "...")`

