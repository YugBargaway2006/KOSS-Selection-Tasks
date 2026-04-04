# Collection library and Context Manager in Python

## Background

### Context managers :

In any programming language, resources are limited in supply. Therefore, the main problem lies in making sure to release these resources after usage. If they are not released, it can lead to resource leakage and may cause the system to either slow down or crash. It would be very helpful if the user has a mechanism for the automatic setup and teardown of resources in Python, This can be achieved by using context managers. In order to make our lives easier and optimize code ,context managers were introduced.

### Container library :

The Python programming language has four collection datatypes- list, tuple, sets and dictionary. However, Python also comes with a built-in module called collections which has specialized data structures which basically covers for the shortcomings of the four data types and reduces the number of lines of extra code.

## What do you need to do

The interviewee needs to make a presentation (keep the presentation simple, a simple PowerPoint presentation is good enough). The interviewee needs to keep in mind that the crowd they will be presenting to, will have mixed people of different knowledge levels, so it is advised that to keep the content balanced for everyone, touch upon both basics and advanced topics in the domains below. Your presentation should mainly consist of the following parts.

- Implementations of Context Managers and its Merits.
- Introduction to collection libraries and container datatypes.
- How are the container datatypes within the collections modules different from the Python's built-in containers.
- Task to be demonstrated using the implementations of context managers and collection libraries.

Please remember to keep the presentation short and concise. Long presentations bore the audience and you would also get tired in presenting. It has also been observed that images, quotes, interactive programming sessions tend to keep the audience interested in the content. **(Recommended: Keep the presentation to around 20 slides). The Interviewee should be also prepared for questions regarding the topics being presented by him/her.**

### Task Details

- **Part I**:Given below is the link to a colab file which contains a list of words for which you need to calculate the count of each word present in the list, using the collections library.
  Using context managers, print the output of the code in a txt file.
- **Part II** -Once you have generated the word count, you need to find the count of any word X, say,"happy" ,which may or may not be present in the generated dict.If the word is present, then print it's word count else print "Not Present".

For the list of words, use: https://www.gutenberg.org/cache/epub/11/pg11.txt?hl=en-IN
For simplicity, ignore numeric values.

## Materials

- https://docs.python.org/3/library/collections.html
- https://book.pythontips.com/en/latest/context_managers.html
- https://github.com/kossiitkgp/Python-Classes

## Tech Stack

Prior knowledge of basic python programming is required in order to perform the task

## Learning from the Task

- The foremost and major skill that a student will earn is to how to google. Obviously not everyone are acquainted with all the technical concepts and while creating the presentation, the interviewee will learn more about how to google for correct information and gather relevant data properly from the chunk of web pages that google will throw at you on a search query. The resources provided will give you a head start but are not complete resources.

- An in-depth comparative study will improve decision-making skills, and defending why context managers and container libraries are beneficial in specific domains will further deepen your understanding.

- Finally if you are new to the programming domain, you get a head start on one of the simplest and easy to learn programming languages (namely Python).
