## TOPIC 4 - Coding Etiquette


#### In preparation for this week:
* read/listen/watch as much as you can from the annotated materials below

---



It is always delightful to start with the masters, and there is no larger master in this area than [Don Knuth](https://www.nytimes.com/2018/12/17/science/donald-knuth-computers-algorithms-programming.html). You may have heard his name because he's authored the still ongoing collection of books - [The Art of Computer Programming](https://www-cs-faculty.stanford.edu/~knuth/taocp.html). Let's begin this week by reading his 1974 ACM Turing Award Lecture - [__Computer Programming as an Art__](https://dl.acm.org/ft_gateway.cfm?id=1283929&type=pdf). An incredibly thoughtful and scholarly view of what coding is - and should be - all about:

> computer programming is an art, because it applies accumulated knowledge to the world, because it requires skill and ingenuity, and especially because it produces objects of beauty.

One thing we should not forget is that __computational thinking is the deeper skill for Data Scientists to learn__. Unfortunately, it is not always natural for social scientists to think as Data Scientists when it comes to exploiting the advantages of computing processes.

A fantastic introduction to starting to leverage mental tools developed in computer science is Jeanette Wing's (2006) article - [__Computational Thinking__](https://dl-acm-org.ezproxy.cul.columbia.edu/doi/10.1145/1118178.1118215) - where she carefully describes what computational thinking is about and why it is tremendously useful for all disciplines. Understanding this will go a long way to collaborate effectively with Data and Machine Learning engineers. In her own words:

> Computational thinking involves solving problems, designing systems, and understanding human behavior, by drawing on the concepts fundamental to computer science. Computational thinking includes a range of __mental tools__ that reflect the breadth of the field of computer science. <br/>
[...]<br/>
Computational thinking is using abstraction and decomposition when attacking a large complex task or designing a large complex system. It is __separation of concerns__. It is choosing an appropriate representation of a problem or modeling the relevant aspects of a problem to make it tractable. [...] It is modularizing something in anticipation of multiple users or prefetching and caching in anticipation of future use. <br/>  
[...] <br/>
Computational thinking is thinking in terms of __prevention__, __protection__, and __recovery from worst-case scenarios__ through __redundancy__, __damage containment__, and __error correction__.

With that background, we can jump directly to reading about coding best practices for social scientists in this old article by Jonathan Nagler (1995) - [__Coding Style and Good Computing Practices__](http://www.jstor.org/stable/420315) - providing  very useful advice on coding as related to ETL and data analysis. Still incredibly relevant advice. If you only have a few minutes to skim, that  piece was more recently (2015) updated and summarized in a blog post - [__Writing Good Code__](https://blog.oup.com/2015/02/jonathan-nagler-writing-good-code/).

For more advanced hackers, you will benefit from a more systematic approach to improving your coding practices by reading a few specialized pieces:

* [__The Practice of Programming__](http://www.informit.com/store/practice-of-programming-9780201615869), read the Preface, Chapters 1, 3, 5, 6, and the Epilogue
* [__The Structure and Interpretation of Computer Programs__](https://mitpress.mit.edu/sicp/full-text/book/book.html) to better understand object-oriented languages
* [__The Pragmatic Programmer__](https://www.amazon.com/dp/020161622X/ref=cm_sw_su_dp?tag=devtools-20) with general advice on how to be a good programmer/coder
* [SOLID design principles: the single responsibility explained](https://stackify.com/solid-design-principles/) as an introduction to a principle that would make your code easier to implement and prevents unexpected side effects from future changes
* [**Design Patterns: Elements of Reusable Object-Oriented Software**](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612) with incredibly useful advice to craft code with an eye to increase flexibility and reusability of your code
* [**Fluent Python: Clear, Concise and Effective Programmings**](https://www.amazon.com/Fluent-Python-Concise-Effective-Programming-ebook-dp-B0131L3PW4/dp/B0131L3PW4/ref=mt_other?_encoding=UTF8&me=&qid=1617839864) to take you to the next level in your Python 3.x programming.

### Debugging 

Every time you write code or work on someone else's code, there is a distinct possibility that you wil have to debug. It is a skill that comes with the Data Science territory, but that people end up learning on the job (and not always without pain). To help speed up the process, read Eric Lippert's (2014) post - [__How to debug small programs__](https://ericlippert.com/2014/03/05/how-to-debug-small-programs/) - to get some incredibly useful guidance on this process.  

Asking for help when you write code, or you debug it, is also part of the process. That means you'll need to learn how to share examples of where you need help that enable others to help you. You'll get the best help possible if you learn how to share __minimal__, __complete__, and __reproducible examples__. Fortunately, this is the bread and butter of places like Stackoverflow, and they have compiled their hard learned wisdom in an incredibly useful post - [__How to create a Minimal, Reproducible Example__](https://stackoverflow.com/help/minimal-reproducible-example). This is perhaps the most important skill you will ever learn, so read it now!


### Coding Style in Python

Nothing is more satisfying for a Python devotee than coming across code crafted in the correct "Pythonic" way. Not a hard thing to achieve since the community has produced a comprehensive document that leads the way - [__PEP 8 Style Guide for Python Code__](https://www.python.org/dev/peps/pep-0008/). In a more poetic - yet meaningful - way,  [__The Zen of Python__](https://www.python.org/dev/peps/pep-0020/) summarizes the spirit of Python coding. Be nice to your fellow Pythonistas - and your future self - and learn them by heart.

### Coding Style in R

A lot of knowledge has been accumulated over the last years and systematized in coding style rules by the RStudio folks. For a book-version, you may want to read [Hadley Wickham](http://hadley.nz/)'s  chapter on [R code](https://r-pkgs.org/code.html) from his [__R Packages__](http://r-pkgs.had.co.nz) book. You may also want to go directly to the [`tidyverse` style guide](https://style.tidyverse.org) that contains best practices followed by all developers working on the `tidyverse`. (_Useless Random Fact:_ While the guide itself was originally an evolution from an older [Google's R Style Guide](https://google.github.io/styleguide/Rguide.xml), Google has now adopted the [`tidyverse` style guide](https://style.tidyverse.org) as its own).


### Commenting your git commits

Unless you are a seasoned developer, it may not be obvious why or how to comment a git `commit`. Fortunately, Chris Beams (2014) wrote a very nice post - [__How to Write a Git Commit Message__](https://chris.beams.io/posts/git-commit/) - that provides much needed guidance and advice on the appropriate way to write `commit` messages.



