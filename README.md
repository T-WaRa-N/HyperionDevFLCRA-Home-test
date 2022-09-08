 <!-- Headings -->
 # SECTION A
> ## Code Review (Option-1 Python Task)



(An Anagram is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once.) 

_anagram.py_ **is the student's submission in the code block below**

```python
class Solution:
       def groupAnagrams(self, strs):
      result = {}
      for i in strs:
         x = "".join(sorted())
         if x in result:
            result[x].append(i)
         else:
            result[x] = [i]
      return list(result.values())
ob1 = Solution()
print(ob1.groupAnagrams(["eat", "tea", "tan", "ate", "nat", "bat"]))
```

>## Feedback or Code Review

Hi (Student name), 

It is thrilling to look at your well written code, your logic is spot on, I want you to remember at all times when you are coding that the logic and reasoning can be right but still experience errors when running the code. The errors shown give the programmer guidlines where the potential bug is. Computers are explicit they can not read between the line they read exactly the lines. Syntax is very important in computer programming and the rules that govern it my be followed at all times. Indentation in python is crucial because the intepreter is designed to execute commands accordingly guided by indentation for Python and curly braces for C, Java and JavaScript. Code under a function, conditionals, loops, class etc must be indented for that particular code block so it can be successfully executed otherwise it will be missed by the intepreter if not correctly indented. This is the first point. The second point is that some built-in functions require arguments such as append(arg_value), sorted(arg_value) and more. Ommitting arguments to built-in functions that require arguments will result in to a bug that will required debugging by introducing the argument into the function.

When you are programming it is a good practice to have comments in you code explaining the purpose of your code. This can be broken down by commenting for each code block so other programmers can easily understand you code and potential debug is quicker should the be a need. Commenting on your code is part of the good practice in coding and it can help during code optimization or factorization.

Each computer program you will ever write, it will utalize computer resources such as memory, CPU power, RAM etc so it is important to have this understand in mind because a larg computer program can consume more resources and time when not efficiently written. More line can mean more resources needed and more time. Code efficiency can be calculated just to let you know.

Style in programming has to do with how you approach problem solvoing using computer programming for example do have all that I have mentioned in mind when you are programming etc. 

Computer code has to be correct, it has to work according to expectations or give desired output or behaviour.


> ### Correctness 2/4

> ### Efficiency 4/4

> ### Style 3/4

> ### Documentation 1/4


Great work you have written the class well, the method has been indented right and there is still room for improvement to make your code work. Work on your indentation (check all code blocks to be rightfuly indented) and also check variable that might be missed for some built-in functions. Please fix the minor errors and resubmit.

Regards,

Code Reviewer