

## Principles / Concepts ##

### Abstraction ###
> Abstraction  by  parameterization abstracts from the details of data representations by representing the data as named parameters.
> https://www.computer.org/web/swebok

>Abstraction  by  specification leads  to  three  major  kinds  of  abstraction: 
>* procedural abstraction
>* data abstraction
>* control (iteration) abstraction
>
> https://www.computer.org/web/swebok 

> ... s the process or result of generalization by reducing the information content of a concept or an observable phenomenon, typically in order to retain only information which is relevant for a particular purpose
> https://en.wikipedia.org/wiki/Software_design

### Minimization of Complexity ###
>The need to reduce complexity is mainly driven by limited ability of most people to hold complex structures and information in their working memories ...
>https://en.wikipedia.org/wiki/Software_construction#Minimizing_complexity

>reduced complexity is  achieved  through  emphasizing  code  creation  that is simple and readable rather than clever.
>https://www.computer.org/web/swebok

>* Simple is better than complex.
>* Complex is better than complicated.
>* Readability counts.
>
> https://www.python.org/dev/peps/pep-0020/#id3

### Separation of concerns / Coupling and Cohesion ###
> However, separating functionality at the wrong boundaries can result in high coupling and complexity between features even though the contained functionality within a feature does not significantly overlap.
>
> https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ee658124(v=pandp.10)#KeyDesignPrinciples

### Single Responsibility principle ###

> There should be one-- and preferably only one --obvious way to do it.
>
> https://www.python.org/dev/peps/pep-0020/#id3

### Principle of Least Knowledge ###
 Law of Demeter or LoD
 
### Don’t repeat yourself (DRY) ###
DRY by Andy Hunt / Dave Thomas in "The Pragmatic Programmer"

> ... a little copying is better than a little dependency ...
>
> Rob Pike / https://www.youtube.com/watch?v=PAAkCSZUG1c 

#### Reuse ####
> Systematic reuse can enable significant software productivity, quality, and cost improvements.
>
> https://www.computer.org/web/swebok


#### single source of truth (SSOT) ####
TODO https://en.wikipedia.org/wiki/Single_source_of_truth

#### Rule of three ####
> It states that two instances of similar code don't require refactoring, but when similar code is used three times, it should be extracted into a new procedure. 
> https://en.wikipedia.org/wiki/Rule_of_three_(computer_programming)

#### WET ####
* write everything twice
* we enjoy typing
* waste everyone's time

### Minimize upfront design ###
> In some cases, you may require upfront comprehensive design and testing if the cost of development or a failure in the design is very high.
> https://docs.microsoft.com/en-us/previous-versions/msp-n-p/ee658124(v=pandp.10)#KeyDesignPrinciples

> run-time fixes are vastly more costly than design fixes, so it is critical to use Agile methods such as frequent demonstrations and user feedback during development to fix issues during the development cycle. Improving software with the benefit of user feedback is generally less expensive than trying to anticipate and document every aspect of a system with BDUF. 
>
>  https://en.wikipedia.org/wiki/Big_Design_Up_Front


#### BDUF / Big Design Up Front ####

> argue that time spent in designing is a worthwhile investment, with the hope that less time and effort will be spent fixing a bug in the early stages of a software product's lifecycle than when that same bug is found and must be fixed later. That is, it is much easier to fix a requirements bug in the requirements phase than to fix that same bug in the implementation phase, as to fix a requirements bug in the implementation phase requires scrapping at least some of the implementation and design work which has already been completed. 
> https://en.wikipedia.org/wiki/Big_Design_Up_Front

#### YAGNI / You aren't gonna need it ####
Principle of XP. 
The need of implementing not currently required code is a sign of losing focus on the actual problem.

>"Always implement things when you actually need them, never when you just foresee that you need them.
>
> http://ronjeffries.com/xprog/articles/practices/pracnotneed/

### Links ###

[1] https://mixmastamyk.bitbucket.io/pro_soft_dev/index.html

[2] https://www.computer.org/web/swebok
