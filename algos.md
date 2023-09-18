0. foreword

>**Abstract**
>Algorithms are like a beautiful symphony, and each line of code flows like a rhythm.
>
>May this book sound softly in your mind, leaving a unique and profound melody.

0.1. about this book

This project aims to create an open source, free, novice-friendly introductory tutorial on data structures and algorithms.

- The whole book uses animation diagrams to explain data structure and algorithm knowledge in a structured way, the content is clear and easy to understand, and the learning curve is smooth.
- The source code of the algorithms can be run with one click, supporting Java, C++, Python, Go, JS, TS, C#, Swift, Zig and other languages.
- We encourage readers to help each other and make progress together in the chapter discussion area. Questions and comments can usually be answered within two days.

0.1.1. readers

If you are a beginner in algorithms, have never been exposed to algorithms, or have some experience in solving problems, have a vague understanding of data structures and algorithms, and jump back and forth between knowing and not knowing, then this book is tailored just for you!

If you have already built up a certain amount of knowledge and are familiar with most of the problem types, then this book can help you review and sort out the algorithm knowledge system, and the source code of the repository can be used as a "tool library for practicing problems" or "algorithm dictionary".

If you are an algorithm master, we look forward to receiving your valuable suggestions, or [participating in the creation together](https://www.hello-algo.com/chapter_appendix/contribution/).

>**Preconditions**
>You need at least some programming background in any language, being able to read and write simple code.

0.1.2. content structure

The main contents of this book include:

- **Complexity analysis**: methods to evaluate scope of data structures and algorithms. Methods to calculate time complexity and space complexity, common types, examples, etc.
- **Data structure**: basic data types, classification methods of data structures. Definition, advantages and disadvantages, common operations, common types, typical applications, implementation methods, etc. of data structures such as arrays, linked lists, stacks, queues, hash tables, trees, heaps, and graphs.
- **Algorithms**: Definitions, advantages and disadvantages, efficiency, application scenarios, problem-solving steps, sample questions, etc. of algorithms such as search, sorting, divide-and-conquer, backtracking, dynamic programming, and greedy.

![Fig. Hello 算法内容结构](./algos/0.1.2.0.png)

0.1.3. thank you

During the creation of this book, I have had help from many people, including but not limited to:

- Thanks to Dr. Li Xi, my mentor in the company, you encouraged me to "act quickly" during a talk, which strengthened my determination to write this book.
- Thanks to my girlfriend, Bubble, as the first reader of this book, who made many valuable suggestions from the perspective of algorithm novice, making this book more suitable for novices to read.
- Thanks to Tengbao, Qibao, and Feibao for giving this book a creative name, which evokes the fond memories of everyone writing the first line of code "Hello World!".
- Thanks to Su Tong for designing the beautiful cover and LOGO for this book, and for patiently modifying it many times under my obsessive-compulsive disorder.
- Thanks to @squidfunk for writing and typography advice, and the excellent open source project [Material-for-MkDocs](https://github.com/squidfunk/mkdocs-material/tree/master).

During the writing process, I read many textbooks and articles on data structures and algorithms. These works provide an excellent model for this book and ensure the accuracy and quality of the content of this book. Thanks to all teachers and seniors for their outstanding contributions!

This book advocates the learning method of using both hands and brain, and is deeply inspired by ["Hands-on Deep Learning"](https://github.com/d2l-ai/d2l-zh) in this regard. I strongly recommend this excellent book to all readers.

My heartfelt thanks to my parents, it is your continuous support and encouragement that gave me the opportunity to do this interesting thing.

0.2. how to use this book

>**Tip**
>For the best reading experience, it is recommended that you read through this section.

0.2.1. writing style convention

- Chapters marked with * after the title are optional chapters, and the content is relatively difficult. If your time is limited, it is recommended to skip it first.
- Proper nouns and words with specific meanings will be marked with "double quotation marks" to avoid ambiguity.
- Important terms in the article will be marked with "" brackets, such as "Array". Be sure to memorize these terms for future use when reading the literature.
- **Bold text** indicates key points or conclusions, and this type of text deserves special attention.
- When it comes to inconsistent nouns between programming languages, Python shall prevail in this book, such as using None to represent "empty".
- This book partially abandons the comment specification of the programming language in exchange for a more compact content layout. Comments are mainly divided into three types: title comments, content comments, multi-line comments.

```zig
// Title comment, used to mark functions, classes, test cases, etc.

// Content comments, used to explain the code in detail

// Multi-line
// comment
```

0.2.2. Learn efficiently in animated illustrations

Compared with text, videos and pictures have higher information density and structure, and are easier to understand. In this book, **key and difficult knowledge will be mainly displayed in the form of animations and diagrams**, while text will be used as explanations and supplements for animations and pictures.

When reading this book, if you find that a certain piece of content provides animation or illustrations, **it is recommended to use the picture as the main line, supplemented by the text (usually located above the image)**, and integrate the two to understand the content.

Fig. 动画图解示例

0.2.3. Deepen understanding in code practice

The accompanying code for this book is hosted in a [GitHub repository](https://github.com/krahets/hello-algo). **The source code is accompanied by a test sample, which can be run with one click**.

If time permits, **I suggest you to type it by yourself with reference to the code**. If study time is limited, at least read through and run all the code.

Writing code is often more rewarding than reading it. **Learning by doing is really learning**.

Fig. 运行代码示例

**Step 1: Install the local programming environment**. Please refer to the [appendix tutorial](https://www.hello-algo.com/chapter_appendix/installation/) for installation, if it is already installed, you can skip this step.

**Step 2: Download the code repository**. If you have installed [Git](https://git-scm.com/downloads), you can clone this repository with the following command.

`git clone <https://github.com/krahets/hello-algo.git>`

Of course, you can also click "Download ZIP" to directly download the code compression package, and then decompress it locally.

Fig. 克隆仓库与下载代码

**Step 3: Run the source code**. If a code block is marked with a file name at the top, the corresponding source code file can be found in the `codes` folder of the repository. Source code files will help you save unnecessary debugging time, allowing you to focus on learning the content.

Fig. 代码块与对应的源代码文件

0.2.4. Grow together in questioning and discussion

When reading this book, please don't "get used to" those knowledge points that you didn't understand. **You are welcome to ask your questions in the comment area**, and I and other small partners will try our best to answer them for you, and usually you can get a reply within two days.

At the same time, I hope you can spend more time in the comment area. On the one hand, you can learn about the problems people are encountering, so you can fill in the gaps, which will help stimulate deeper thinking. On the other hand, I hope you can generously answer other friends' questions and share your insights, so that everyone can learn and make progress together.

Fig. 评论区示例

0.2.5. Algorithm Learning Route

In general, we can divide the process of learning data structures and algorithms into three stages:

1. **Introduction to algorithms**. We need to be familiar with the characteristics and usage of various data structures, and learn the principles, processes, uses, and efficiency of different algorithms.
2. **Practice algorithm problems**. It is recommended to start with popular topics, such as [Jianzhi Offer](https://leetcode.cn/problem-list/xb9nqhhg/) and [LeetCode Hot 100](https://leetcode.cn/problem-list/2cktkvj/), and accumulate at least 100 topics first to familiarize yourself with mainstream algorithm problems. "Knowledge Forgotten" can be a challenge when you first practice the problems, but don't worry, it's normal. We can review the topic according to the "Ebbinghaus Forgetting Curve", and usually after 3-5 rounds of repetition, we can keep it in mind.
3. **Build a knowledge system**. In terms of learning, we can read algorithm column articles, problem-solving frameworks and algorithm teaching materials to continuously enrich the knowledge system. In terms of practicing problems, you can try to use advanced strategies, such as classification by topic, multiple solutions for one problem, multiple problems for one solution, etc. Relevant experience in practicing problems can be found in various communities.

As an introductory tutorial, the content of this book mainly covers the "first stage", aiming to help you carry out the second and third stages of learning more efficiently.

Fig. 算法学习路线

0.3. summary

- The primary audience for this book is beginners in algorithms. If you have a certain foundation, this book can help you review algorithm knowledge systematically, and the source code in the book can also be used as a "tool library for practicing problems".
- The content of the book mainly includes three parts: complexity analysis, data structure, and algorithm, covering most of the topics in this field.
- For beginners in algorithms, it is very important to read an introductory book at the initial stage, which can avoid many detours.
- The animations and illustrations in the book are usually used to introduce important and difficult knowledge. These should be given more attention when reading this book.
- The best way to learn programming is by doing. It is highly recommended to run the source code and hammer the code yourself.
- Each chapter of the web version of this book has a discussion area, and you are welcome to share your doubts and insights at any time.

1. Algorithms for the first time

>**Abstract**
>A girl dances lightly, intertwined with data, and the melody of algorithms flutters from her skirt.
>
>She invites you to dance together, please follow her steps and step into the algorithmic world full of logic and beauty.

1.1. Algorithms are everywhere

When we hear the word "algorithm," it's natural to think of mathematics. In reality, however, many algorithms do not involve complex mathematics, but rely more on basic logic, which is found everywhere in our daily lives.

Before discussing algorithms formally, there is an interesting fact worth sharing: **you have learned many algorithms without knowing it, and are used to applying them in your daily life**. Below, I will give a few specific examples to confirm this point.

**Example 1**: Look up a dictionary. In the dictionary, each word is arranged in alphabetical order. Suppose we need to find a word whose first letter is *r*, usually this will implemented as in the following pictures:

1. Turn over about half of the pages of the dictionary to see what the first letter of the page is, assuming the first letter is *m*.
2. Since `r` is located after `m` in the alphabet, the first half of the dictionary is excluded, and the search range is narrowed to the second half.
3. Repeat steps `1.` and `2.` until you find the page number whose first letter is *r*.

![Step 1](./algos/1.1.1-1.png)![Step 2](./algos/1.1.1-2.png)![Step 3](./algos/1.1.1-3.png)![Step 4](./algos/1.1.1-4.png)![Step 5](./algos/1.1.1-5.png)

Looking up a dictionary, an essential skill for elementary school students, is actually the famous "binary search". From the perspective of data structure, we can regard the dictionary as a sorted "array"; from the perspective of algorithm, we can regard the above series of operations of looking up the dictionary as a "binary search" algorithm.

**Example 2**: Organize poker. When we play cards, we need to arrange the poker cards in each game so that they are arranged from small to large. The implementation process is shown in the following picture:

1. Divide the playing cards into two parts, "ordered" and "disordered", and assume that the leftmost playing card is already in order in the initial state.
2. Draw a playing card from the unordered part and insert it into the correct position of the ordered part; after completion, the leftmost 2 cards are already in order.
3. Continuously loop step `2.` , each round insert a playing card from the unordered part to the ordered part, until all the playing cards are in order.

![Fig. 扑克排序步骤](./algos/1.1.2.png)

The above method of sorting playing cards is essentially an "insertion sort" algorithm, which is very efficient when dealing with small data sets. Insertion sort exists in the sorting library functions of many programming languages.

**Example 3**: Currency change. Suppose we bought 69 euros of goods in the supermarket and paid 100 euros to the cashier, the cashier needs to give us 31 euros. He will naturally complete the reasoning shown in the following picture:

1. The options are currencies smaller than the face value of 31 euros, including 1, 5, 10, and 20 euros.
2. Take the largest 20 euros from the options, and the remaining is 31 - 20 = 11 euros.
3. Take the largest 10 euros from the remaining options, and the remaining is 11 - 10 = 1 euros.
4. Take the largest 1 euros from the remaining options, and the remaining is 1 - 1 = 0 euros.
5. Complete the change, the solution is 20 + 10 + 1 = 31 euros.

![Fig. 货币找零过程](./algos/1.1.3.png)

In the above steps, we take the best option available (use as large a denomination currency as possible) at each step, and finally get a change solution. From the perspective of data structure and algorithm, this method is essentially a "greedy algorithm".

As small as cooking a dish, as large as interstellar navigation, almost all problems can be solved with algorithms. The advent of computers allowed us to program data structures to be stored in memory while writing code to call CPUs and GPUs to execute algorithms. In this way, we can transfer the problems in our lives to computers and solve various complex problems in a more efficient way.

>**Tip**
>So far, if you still have a little understanding of concepts such as data structures, algorithms, arrays, and binary search, great! Because that's what this book is about. Next, this book will guide you step by step into the palace of knowledge of data structures and algorithms.

1.2. what is an algorithm

1.2.1. Algorithm definition

An "Algorithm" is a set of instructions or steps to solve a specific problem in a finite amount of time. It has the following properties:

- The problem is unambiguous, containing clear definitions of inputs and outputs.
- Feasible and able to be done with limited steps, time and memory space.
- Each step has a definite meaning, and the output is always the same under the same input and operating conditions.

1.2.2. data structure definition

"Data Structure" is the way data is organized and stored in a computer. Its design goals include:

- Minimize space occupation and save computer memory.
- Data operations are as fast as possible, covering data access, adding, deleting, updating, etc.
- Provide concise data representation and logical information in order to make the algorithm run efficiently.

**Data structure design is a process full of trade-offs**. If you want to improve in one aspect, you often need to make compromises in another, such as:

- Compared with arrays, linked lists are more convenient in data addition and deletion operations, but at the expense of data access speed.
- Compared with the linked list, the graph provides richer logical information, but requires a larger memory space.

1.2.3. The relationship between data structures and algorithms

Data structure and algorithm are highly related and closely integrated, as shown in the following picture:

- Data structures are the cornerstone of algorithms. Data structures provide algorithms with structured storage of data and methods for manipulating the data.
- Algorithms are the stage where data structures play. The data structure itself only stores data information, and specific problems can be solved by combining algorithms.
- Specific algorithms usually have corresponding optimal data structures. Algorithms can usually be implemented based on different data structures, but the final execution efficiency may vary greatly.

![Fig. 数据结构与算法的关系]()

Data structures and algorithms are like building blocks. A set of building blocks, in addition to containing many parts, also comes with detailed assembly instructions. We follow the instructions step by step to assemble a beautiful building block model.

![Fig. 拼装积木]()

The detailed correspondence between the two is shown in the table below.

|Data Structures and Algorithms|LEGO|
|---|---|
|Input Data|unassembled building blocks|
|Data Structure|Building block organization form, including shape, size, connection method, etc.|
|Algorithm|A series of operation steps to assemble the building blocks into the target shape|
|Output Data|building block model|

It is worth noting that data structures and algorithms are independent of programming languages. Because of this, this book is able to provide implementations in a variety of programming languages.

>**Conventional abbreviation**
>In actual discussions, we usually refer to "data structures and algorithms" as "algorithms" for short. For example, the well-known LeetCode algorithm topic actually examines both data structure and algorithm knowledge.

1.3. summary

- Algorithms are ubiquitous in everyday life, and are not remote and advanced knowledge. In fact, we have unconsciously learned many algorithms to solve life's problems big and small.
- The principle of looking up a dictionary is consistent with the binary search algorithm. Binary search embodies the important algorithmic idea of ​​divide and conquer.
- The process of sorting poker is very similar to the insertion sort algorithm. Insertion sort is good for sorting small datasets.
- The steps of currency change are essentially a greedy algorithm, and each step takes the best option currently seen.
- An algorithm is a set of instructions or steps to solve a specific problem in a finite amount of time, while a data structure is the way data is organized and stored in a computer.
- Data structures are closely linked with algorithms. The data structure is the cornerstone of the algorithm, and the algorithm is the stage where the data structure plays its role.
- Lego blocks correspond to data, the shape and connection of the blocks represent the data structure, and the steps of assembling the blocks correspond to the algorithm.

2. the complexity

>**Abstract**
>Complexity is like a compass in the vast universe of algorithms.
>
>It guides us to explore deeply in the dimensions of time and space to find more elegant solutions.

2.1. Algorithm Efficiency Evaluation

In algorithm design, we pursue the following two levels of goals:

1. **Find the solution to the problem**: The algorithm needs to reliably find the correct solution to the problem within the specified input range.
2. **Seeking the optimal solution**: There may be multiple solutions to the same problem, and we hope to find an algorithm that is as efficient as possible.

Therefore, under the premise of being able to solve the problem, algorithm efficiency becomes the main evaluation dimension, including:

- **Time efficiency**, that is, how fast the algorithm runs.
- **Space efficiency**, that is, the size of the memory space occupied by the algorithm.

In short, **our goal is to design "fast and cheap" data structures and algorithms**. It is very important to effectively evaluate the efficiency of algorithms, because only by understanding the evaluation criteria can we compare and analyze various algorithms, thereby guiding the algorithm design and optimization process.

2.1.1. practical testing¶

Suppose we now have Algorithm `A` and Algorithm `B`, both of which can solve the same problem, and now we need to compare the efficiency of these two algorithms. The most direct way is to find a computer, run these two algorithms, and monitor and record their running time and memory usage. This evaluation method can reflect the real situation, but it also has major limitations.

*It is difficult to rule out the interference factors of the test environment*. Hardware configuration will affect the performance of the algorithm. For example, in a computer, the running time of algorithm `A` is shorter than that of algorithm `B`; but in another computer with different configurations, we may get the opposite test results. This means that we need to test on various machines and calculate the average efficiency, which is unrealistic.

**Rolling out a full test is very resource intensive**. Algorithms exhibit different efficiencies as the amount of input data varies. For example, when the amount of input data is small, the running time of algorithm `A` is less than that of algorithm `B`; when the amount of input data is large, the test results may be just the opposite. Therefore, in order to draw convincing conclusions, we need to test input data of various sizes, which requires a lot of computing resources.

2.1.2 Theoretical estimates¶

Due to the large limitations of the actual test, we can consider evaluating the efficiency of the algorithm only through some calculations. This estimation method is called "Asymptotic Complexity Analysis", or "complexity analysis" for short.

Complexity analysis reflects the relationship between the time (space) resources required for the algorithm to run and the size of the input data. **It describes the growing trend in the time and space required for algorithm execution as the size of the input data increases**. This definition is a bit of a mouthful, we can divide it into three key points to understand.

- "Algorithm operation efficiency" can be divided into two parts: running time and occupied space. Correspondingly, complexity can be divided into "Time Complexity" and "Space Complexity".
- "As the amount of input data increases" means that the complexity is related to the amount of input data, which reflects the relationship between the operating efficiency of the algorithm and the amount of input data.
- "Growth trend" means that the complexity analysis focuses on the growth trend of the algorithm's time and space, rather than the specific running time or occupied space.

**Complexity analysis overcomes the shortcomings of practical testing methods**, which is reflected in the following two aspects.

- It is independent of the test environment, so the analysis results are applicable to all running platforms.
- It can reflect the algorithm efficiency under different data volumes, especially the algorithm performance under large data volumes.

>**Tip**
>If you are still confused about the concept of complexity analysis, don't worry, we will introduce it in detail in subsequent chapters.

2.2. Iteration and recursion

In data structures and algorithms, it is very common to repeatedly execute a certain task, which is closely related to the complexity of the algorithm. To repeat a task, we usually choose two basic program structures: iteration and recursion.

2.2.1. Iteration

An "iteration" is a control structure that repeatedly executes a task. In iteration, a program executes a certain piece of code repeatedly if a certain condition is met until the condition is no longer met.

1. for loop

`for` loops are one of the most common forms of iteration and **are useful when the number of iterations is known in advance**.

The following function implements the summation $1 + 2 +...+ n$ based on the for loop, and the summation result is recorded using the variable `res`. It should be noted that the interval corresponding to `range(a, b)` in Python is "left closed and right open", and the corresponding traversal range is $a, a + 1, ...,b - 1$.

```zig
[class]{}-[func]{forLoop}
```

The follwoing picture shows a block diagram of the summation function.

![图 2-1   求和函数的流程框图](./algos/2.2.1.1.png)

The number of operations of this summation function is proportional, or "linear", to the input data size $n$. In fact, time complexity describes this as "linear relationship". Related content will be introduced in detail in the next section.

2. while loop

Similar to the `for` loop, the `while` loop is also a way to implement iteration. In a `while` loop, the program checks the condition first each round, and continues execution if the condition is true, otherwise it ends the loop.

Below, we use a while loop to implement the sum $1 + 2 +... + n$.

```zig
[class]{}-[func]{whileLoop}
```

In the `while` loop, since the steps of initializing and updating the condition variable are independent of the loop structure, **it has more degrees of freedom than the** `for` **loop**.

For example, in the following code, the condition variable $i$ is updated twice per round, which is not very convenient to implement with a `for` loop.

```zig
[class]{}-[func]{whileLoopII}
```

In general, **the** `for` **loop is more compact in code, while the** `while` **loop is more flexible**, and both can implement iteration structures. The choice of which one to use should be determined by the needs of a particular problem.

3. nested loop

We can nest another loop structure inside a loop structure, taking the `for` loop as an example:

```zig
[class]{}-[func]{nestedForLoop}
```

The following picture shows the block diagram of the nested loop.

![图 2-2   嵌套循环的流程框图](./algos/2.2.1.3.png)

In this case, the number of operations of the function is proportional to $n^2$, or the running time of the algorithm is "squared" with the size of the input data $n$.

We can continue to add nested loops, each nesting is a "dimension increase", which will increase the time complexity to "cubic relationship", "fourth power relationship", and so on.

2.2.2. Recursion

"Recursion" is an algorithmic strategy in which a function calls itself to solve a problem. It mainly consists of two stages.

1. **Recursion**: The program calls itself deeper and deeper, usually passing in smaller or more simplified arguments, until a "terminating condition" is reached.
2. **Return**: After the "termination condition" is triggered, the program returns layer by layer from the deepest recursive function, and gathers the results of each layer.

From an implementation point of view, recursive code mainly contains three elements.

1. **Termination condition**: used to decide when to switch from "pass" to "return".
2. **Recursive call**: Corresponding to "recursion", the function calls itself, usually with smaller or more simplified parameters.
3. **Return result**: corresponding to "return", returns the result of the current recursive level to the previous level.

Observe the following code, we simply call the function `recur(n)` to complete the calculation of $1 + 2 +...+ n$:

```zig
[class]{}-[func]{recur}
```

![图 2-3   求和函数的递归过程](./algos/2.2.2.0.png)

Although computationally, iteration and recursion can achieve the same results, **they represent two completely different paradigms for thinking and solving problems**.

- **Iteration**: Solving problems "from the bottom up". Start with the most basic steps and keep repeating or adding up the steps until the task is complete.
- **Recursion**: Solve problems "from the top down". Decompose the original problem into smaller sub-problems that have the same form as the original problem. Next, the subproblem continues to be decomposed into smaller subproblems until the base case is reached (the solution of the base case is known).

Taking the previous summation function as an example, let the equation $f(n) = 1 + 2 +...+ n$.

- **Iteration**: Simulate the summation process in a loop, traverse from $1$ to $n$, perform the summation operation in each round, and then obtain $f(n)$.
- **Recursion**: Decompose the problem into sub-problems $f(n) = n + f(n - 1)$, and decompose continuously (recursively) until the basic case $f(0) = 0$.

1. call stack

Every time a recursive function calls itself, the system will allocate memory for the newly opened function to store local variables, calling addresses, and other information. This will lead to two results.

- The context data of a function is stored in a memory area called "stack frame space" and will not be released until the function returns. Therefore, **recursion is usually more memory-intensive than iteration**.
- Calling functions recursively incurs additional overhead. **So recursion is usually less time efficient than looping**.

As shown in the follwoing picture, before the termination condition is triggered, there are $n$ recursive functions that do not return at the same time, and the recursion depth is $n$.

![图 2-4   递归调用深度](./algos/2.2.2.1.png)

In practice, the depth of recursion allowed by a programming language is usually limited, and too deep recursion may cause a stack overflow error.

2. tail recursion

Interestingly, **if a function is called recursively as the last step before returning**, the function can be optimized by the compiler or interpreter to be comparable to iteration in terms of space efficiency. This situation is called "tail recursion".

- **Ordinary recursion**: After the function returns to the function of the previous level, it needs to continue to execute the code, so the system needs to save the context of the previous level call.
- **Tail recursion**: The recursive call is the last operation before the function returns, which means that after the function returns to the previous level, there is no need to continue to perform other operations, so the system does not need to save the context of the previous function.

Taking the calculation of $1 + 2 +...+ n$ as an example, we can set the result variable `res` as a function parameter to achieve tail recursion.

```zig
[class]{}-[func]{tailRecur}
```

A comparison of the two recursive processes is shown in the following picture.

- **Ordinary recursion**: The summation operation is performed during the "return" process, and the summation operation must be performed again after each layer returns.
- **Tail recursion**: The summation operation is performed in the "recursive" process, and the "recursive" process only needs to return layer by layer.

![图 2-5   尾递归过程](./algos/2.2.2.2.png)

Note that many compilers or interpreters do not support tail recursion optimization. For example, Python does not support tail-recursive optimization by default, so even if the function is tail-recursive, it is still possible to encounter stack overflow problems.

3. recursion tree

When dealing with algorithmic problems related to "divide and conquer", recursion is often more intuitive than iteration, and the code is easier to read. Take the "Fibonacci sequence" as an example.

>**Problem**
>Given a Fibonacci sequence $0, 1, 1, 2, 3, 5, 8, 13,...$, find the *n*th number of the sequence.

Assuming that the *n*th number of the Fibonacci sequence is $f(n)$, it is easy to get two conclusions.

- The first two numbers of the sequence are $f(1) = 0$ and $f(2) = 1$.
- Each number in the sequence is the sum of the previous two numbers, i.e. $f(n) = f(n - 1) + f(n - 2)$.

Perform recursive calls according to the recursive relationship, and use the first two numbers as the termination condition to write the recursive code. Call `fib(n)` to get the *n*th number of the Fibonacci sequence.

```zig
[class]{}-[func]{fib}
```

Looking at the above code, we recursively call two functions inside the function, **which means that two call branches are generated from one call**. As shown in the following picture, this continuous recursive call will eventually generate a "recursion tree recursion tree" with $n$ layers.

- From an algorithmic point of view, many important algorithmic strategies such as search, sorting, backtracking, divide and conquer, and dynamic programming directly or indirectly apply this way of thinking.
- From the perspective of data structure, recursion is naturally suitable for dealing with problems related to linked lists, trees and graphs, because they are very suitable for analysis with the idea of ​​divide and conquer.

![图 2-6   斐波那契数列的递归树 ](./algos/2.2.2.3.png)

In essence, recursion embodies the thinking paradigm of "decomposing a problem into smaller sub-problems", and this divide-and-conquer strategy is crucial.

2.3. time complexity¶

The running time can intuitively and accurately reflect the efficiency of the algorithm. If we want to accurately estimate the running time of a piece of code, how should we do it?

1. **Determine the operating platform**, including hardware configuration, programming language, system environment, etc. These factors will affect the operating efficiency of the code.
2. **Estimate the runtime required for various computational operations**, e.g. addition `+` takes 1 ns, multiplication `*` takes 10 ns, `print()` takes 5 ns, etc.
3. **Count all calculation operations in the code**, and sum the execution time of all operations to obtain the running time.

For example, in the following code, the input data size is $n$.

```zig
```

According to the above method, the running time of the algorithm can be obtained as $6n+12$ ns.

$$1+1+10+(1+5) \times n=6n+12$$

But in practice, **the running time of statistical algorithms is neither reasonable nor realistic**. First of all, we don't want to bind the estimated time to the running platform, because the algorithm needs to run on various platforms. Second, it is difficult for us to know the running time of each operation, which brings great difficulty to the estimation process.

2.3.1. Statistical time growth trend

Time complexity analysis counts not the running time of the algorithm, but **the growth trend of the running time of the algorithm as the amount of data increases**.

The concept of "time growth trend" is relatively abstract, and we use an example to understand it. Suppose the input data size is $n$, given three algorithm functions `A` , `B` , `C` .

```zig
```

The following picture shows the time complexity of the above three algorithmic functions.

- Algorithm `A` has only $1$` print operation, and the running time of the algorithm does not increase as $n$ increases. We call the time complexity of this algorithm "constant order".
- The print operation in algorithm `B` needs to loop $n$ times, and the running time of the algorithm increases linearly as $n$ increases. The time complexity of this algorithm is called "linear order".
- The print operation in algorithm `C` needs to loop $1000000$ times, although the running time is very long, it is independent of the input data size $n$. Therefore, the time complexity of `C` is the same as that of `A`, which is still "constant order".

![图 2-7   算法 A 、B 和 C 的时间增长趋势](./algos/2.3.1.png)

Compared with directly counting the running time of algorithms, what are the characteristics of time complexity analysis?

- **Time complexity can effectively evaluate the efficiency of the algorithm**. For example, the running time of algorithm `B` grows linearly, being slower than algorithm A when $n>1$, and slower than algorithm C when $n>1000000$. In fact, as long as the input data size $n$ is large enough, the algorithm with the complexity of "constant order" must be better than the algorithm of "linear order", which is exactly the meaning expressed by the time growth trend.
- **The calculation method of time complexity is simpler**. Clearly, neither the running platform nor the type of computing operation has any bearing on the increasing trend of the algorithm's running time. Therefore, in time complexity analysis, we can simply regard the execution time of all computing operations as the same "unit time", thus simplifying the "statistics of the running time of computing operations" to "statistics of the number of computing operations". In this way, the difficulty of estimation is greatly reduced.
- **There are also certain limitations in time complexity**. For example, although algorithms `A` and `C` have the same time complexity, the actual running times differ significantly. Also, although the time complexity of algorithm `B` is higher than that of `C`, algorithm `B` significantly outperforms algorithm `C` when $n$ is small. In these cases, it is difficult for us to estimate the efficiency of the algorithm based on the time complexity alone. Of course, despite the above problems, complexity analysis is still the most effective and commonly used method to estimate the efficiency of algorithms.

2.3.2. Function Asymptotically Upper Bound

Given a function with input size $n$:

```zig
```

Assuming that the number of computing operations of the algorithm is a function of the input data size $n$, denoted as $T(n)$, then the number of operations of the above function is:

$$T(n)=3+2n$$

$T(n)$ is a linear function, indicating that the growth trend of time is linear, so its time complexity is linear order.

We record the time complexity of linear order as $O(n)$. This mathematical symbol is called "Big-O Notation", which means the "Asymptotic Upper Bound" of the function $T(n)$.

Time complexity analysis is essential to calculate the asymptotic upper bound of the "number of operations function $T(n)$". Next, let's look at the mathematical definition of the asymptotic upper bound of a function.

>**Asymptotical upper bound function**
>If there are positive real numbers $c$ and $n_0$, so that for all $n>n_0$, there is $$T(n) \le c \cdot f(n)$$ then it can be considered that $f(n)$ gives an asymptotic upper bound of $T(n)$, written as $$T(n)=O(f(n))$$

As shown in the following picture, calculating the asymptotic upper bound is to find a function $f(n)$, so that when $n$ tends to infinity, $T(n)$ and $f(n)$ are at the same growth level, only differing by a constant term multiple of $c$.

![Fig. 函数的渐近上界](./algos/2.3.2.png)

2.3.3. Calculation method

Asymptotic upper bounds are a bit mathematical, so don't worry if you don't feel you fully understand them. Because in actual use, we only need to master the calculation method, and the mathematical meaning can be gradually understood.

According to the definition, after determining $f(n)$, we can get the time complexity $O(f(n))$. So how to determine the asymptotic upper bound $f(n)$? The overall process is divided into two steps: first count the number of operations, and then estimate the asymptotic upper bound.

1. Step 1: Count the number of operations

For the code, it is enough to calculate line by line from top to bottom. However, since the constant $c$ in the above $c \cdot f(n)$ can take any size, various coefficients and constants in the operand $T(n)$ can be ignored. According to this principle, the following counting simplification techniques can be summarized.

1. **Constant terms in $T(n)$ are ignored**. Since they are all independent of $n$, they have no impact on the time complexity.
2. **Omit all coefficients**. For example, looping $2n$ times, $5n+1$ times, etc., can be simplified as $n$ times, because the coefficient in front of $n$ has no effect on the time complexity.
3. **Use multiplication when loops are nested**. The total number of operations is equal to the product of the number of operations in the outer loop and the inner loop, and each loop can still apply the above techniques `1.` and `2.`.

The following code and formulas show the statistical results before and after using the above technique. Both have the same time complexity, which is $O(n^2)$.

$$\begin{align*}
T(n)&=2n(n+1)+(5n+1)+2\\
&=2n^2+7n+3\\
T(n)&=n^2+n
\end{align*}$$

```zig
```

2. Step 2: Determine the asymptotic upper bound

**The time complexity is determined by the highest order term in the polynomial $T(n)$**. This is because as n tends to infinity, the highest-order term will play a dominant role, and the influence of other terms can be ignored.

The following table shows some examples, where some exaggerated values are used to emphasize the conclusion that "the coefficient cannot shake the order". These constants become irrelevant as $n$ goes to infinity.

|number of operations $T(n)$|time complexity $O(f(n))$|
|---|---|
|$100000$                   |$O(1)$                   |
|$3n+2$                     |$O(n)$                   |
|$2n2+3n+2$                 |$O(n^2)$                 |
|$n3+10000n^2$              |$O(n^3)$                 |
|$2n+100000n^{10000}$       |$O(2^n)$                 |

2.3.4. common type

Assuming that the input data size is n, common time complexity types include (arranged in order from low to high):

$$O(1)<O(log\,n)<O(n)<O(n\,log\,n)<O(n^2)<O(2^n)<O(n!)$$
$$\text{constant order}<\text{logarithmic order}<\text{linear order}<\text{linear logarithmic order}<\text{square order}<\text{exponential order}<\text{factorial order}$$

![Fig. 时间复杂度的常见类型](./algos/2.3.4.0.png)

>**Tip**
>Some sample codes require some prior knowledge, including arrays, recursion, and more. If you encounter a part that you don't understand, you can review it after studying the following chapters. At this stage, please focus on understanding the meaning and calculation method of time complexity.

1. Constant order $O(1)$

The number of operations of constant order has nothing to do with the input data size $n$, that is, it does not change as $n$ changes.

For the following algorithm, although the number of operations `size` may be large, the time complexity is still $O(1)$ since it is independent of the data size $n$.

```zig
// constant order
fn constant(n: i32) i32 {
    _ = n;
    var count: i32 = 0;
    const size: i32 = 100_000;
    var i: i32 = 0;
    while(i<size) : (i += 1) {
        count += 1;
    }
    return count;
}
```

2. Linear order $O(n)$

The number of operations of linear order grows linearly with respect to the input data size $n$. Linear order usually occurs in single-layer loops:

```zig
// linear order
fn linear(n: i32) i32 {
    var count: i32 = 0;
    var i: i32 = 0;
    while (i < n) : (i += 1) {
        count += 1;
    }
    return count;
}
```

The time complexity of operations such as traversing arrays and traversing linked lists is $O(n)$, where $n$ is the length of the array or linked list.

```zig
// linear order (traversing arrays)
fn arrayTraversal(nums: []i32) i32 {
    var count: i32 = 0;
    // the number of loops is proportional to the length of the array
    for (nums) |_| {
        count += 1;
    }
    return count;
}
```

It is worth noting that **the data size $n$ needs to be determined specifically according to the type of input data**. For example, in the first example, the variable $n$ is the input data size; in the second example, the array length $n$ is the data size.

3. Square order $O(n2)$

The number of operations of quadratic order grows quadratically with respect to the input data size. Quadratic order usually occurs in nested loops, both outer and inner loops are $O(n)$, so $O(n2)$ overall.

```zig
// square order
fn quadratic(n: i32) i32 {
    var count: i32 = 0;
    var i: i32 = 0;
    // the number of loops is proportional to the square of the array length
    while (i < n) : (i += 1) {
        var j: i32 = 0;
        while (j < n) : (j += 1) {
            count += 1;
        }
    }
    return count;
}
```

The follwoing picture compares the three time complexities of constant order, linear order and square order.

![Fig. 常数阶、线性阶、平方阶的时间复杂度](./algos/2.3.4.3.png)

Taking "bubble sort" as an example, the outer loop executes $n-1$ times, and the inner loop executes $n-1,n-2,...,2,1$ times, with an average of $n/2$ times, so the time complexity is $O((n-1)n/2)=O(n^2)$.

```zig
// square order (bubble sort)
fn bubbleSort(nums: []i32) i32 {
    var count: i32 = 0;  // counter 
    // outer loop: the unsorted range is [0, i]
    var i: i32 = @as(i32, @intCast(nums.len)) - 1;
    while (i > 0) : (i -= 1) {
        var j: usize = 0;
        // inner loop: swaps the largest element in the unsorted range [0, i] to the rightmost end of the range 
        while (j < i) : (j += 1) {
            if (nums[j] > nums[j + 1]) {
                // swap nums[j] with nums[j + 1]
                var tmp = nums[j];
                nums[j] = nums[j + 1];
                nums[j + 1] = tmp;
                count += 3;  // element swap consists of 3 unit operations
            }
        }
    }
    return count;
}
```

4. Exponential order $O(2n)$

"Cell division" in biology is a typical example of exponential growth: the initial state is $1$ cell, after one round of division, it becomes $2$, after two rounds of division, it becomes $4$, and so on, after $n$ rounds of division, there are $2n$ cells.

The following code and picture simulate the process of cell division with a time complexity $O(2^n)$.

```zig
// exponential order (loop implementation)
fn exponential(n: i32) i32 {
    var count: i32 = 0;
    var bas: i32 = 1;
    var i: i32 = 0;
    // cells are divided into two each round to form sequence 1, 2, 4, 8, ..., 2^(n-1)
    while (i < n) : (i += 1) {
        var j: i32 = 0;
        while (j < bas) : (j += 1) {
            count += 1;
        }
        bas *= 2;
    }
    // count = 1 + 2 + 4 + 8 + .. + 2^(n-1) = 2^n - 1
    return count;
}
```

![Fig. 指数阶的时间复杂度](./algos/2.3.4.4.png)

In practical algorithms, exponential order often appears in recursive functions. For example, in the following code, which recursively splits in two and stops after $n$ splits.

```zig
// exponential order (recursive implementation)
fn expRecur(n: i32) i32 {
    if (n == 1) return 1;
    return expRecur(n - 1) + expRecur(n - 1) + 1;
}
```

Exponential order growth is very fast and is more common in exhaustive methods (brute force search, backtracking, etc.). For problems with large data sizes, exponential order is unacceptable, and algorithms such as "dynamic programming" or "greedy" are usually used to solve them.

5. logarithmic order $O(log\,n)$

In contrast to exponential order, logarithmic order reflects the "reduction to half each round". Assuming that the input data size is $n$, since each round is reduced to half, the number of cycles is $log_2\,n$, which is the inverse function of $2^n$.

The following code and picture simulate the process of "reducing each round to half" with a time complexity of $O(log_2\,n$), abbreviated as $O(log],n)$.

```zig
// logarithmic order (loop implementation)
fn logarithmic(n: f32) i32 {
    var count: i32 = 0;
    var n_var = n;
    while (n_var > 1)
    {
        n_var = n_var / 2;
        count +=1;
    }
    return count;
}
```

![Fig. 对数阶的时间复杂度](./algos/2.3.4.5.png)

Similar to exponential order, logarithmic order is also commonly found in recursive functions. The following code forms a recursive tree of height $log_2\,n$.

```zig
// logarithmic order (recursive implementation)
fn logRecur(n: f32) i32 {
    if (n <= 1) return 0;
    return logRecur(n / 2) + 1;
}
```

Logarithmic order often appears in algorithms based on divide-and-conquer strategies, embodying the algorithmic ideas of "one divides into many" and "simplifies complexity". It grows slowly and is second only to the ideal time complexity of constant order.

>**Tip**
>To be precise, the time complexity corresponding to "one divided into $m$" is $O(log_m\,n)$. And through the logarithm-for-base formula, we can get equal time complexity with different bases:
$$O(log_m\,n)=O(log_k\,n/log_k\,m)=O(log_k\,n)$$
That is, the base $m$ can be converted without affecting the complexity. Therefore, we usually omit the base $m$, and record the logarithmic order directly as $O(log_n)$.

6. Linear-logarithmic order $O(n\,log\,n)$

The linear-logarithmic order often appears in nested loops, and the time complexities of the two loops are $O(n\,log\,n)$ and $O(n)$ respectively. The relevant code is as follows:

```zig
// linear logarithmic order
fn linearLogRecur(n: f32) i32 {
    if (n <= 1) return 1;
    var count: i32 = linearLogRecur(n / 2) +
                linearLogRecur(n / 2);
    var i: f32 = 0;
    while (i < n) : (i += 1) {
        count += 1;
    }
    return count;
}
```

The following picture shows how the linear-logarithmic order is generated. The total number of operations on each layer of the binary tree is $n$, and the tree has a total of layers $log_2\,n+1$, so the time complexity is $O(n\,log\,n)$.

![Fig. 线性对数阶的时间复杂度](./algos/2.3.4.6.png)

The time complexity of mainstream sorting algorithms, such as quick sort, merge sort, heap sort, etc is usually $O(n\,log\,n)$.

7. Factorial order $O(n!)$

The factorial order corresponds to the "full permutation" problem in mathematics. Given $n$ non-repeating elements, find all possible permutations, the number of which is:

$$n! =n\times(n-1)\times(n-2)\times...\times2\times1$$

Factorial is usually implemented using recursion. As shown in the follwoing code and picture, the first layer splits out $n$, the second layer splits out $n-1$, and so on, until the *n*th layer stops splitting:

```zig
// factorial step (recursive implementation)
fn factorialRecur(n: i32) i32 {
    if (n == 0) return 1;
    var count: i32 = 0;
    var i: i32 = 0;
    // split n starting from 1
    while (i < n) : (i += 1) {
        count += factorialRecur(n - 1);
    }
    return count;
}
```

![Fig. 阶乘阶的时间复杂度](./algos/2.3.4.7.png)

Note that since $n!>2^n$ is constant for $n>4$, the factorial order grows faster than the exponential order, which is also unacceptable for large $n$.

2.3.5 Worst, best, average time complexity

**The time efficiency of the algorithm is often not fixed, but related to the distribution of the input data**. Suppose you input an array `nums` with a length of $n$, where `nums` consists of numbers from $1$ to $n$, and each number appears only once, but the order of elements is randomly shuffled, and the goal of the task is to return the index of element $1$. We can draw the following conclusions.

- When `nums = [?, ?, ..., 1]`, that is, when the last element is $1$, it is necessary to traverse the array completely **achieving the worst time complexity $O(n)$**.
- When `nums = [1, ?, ?, ...]`, that is, when the first number is $1$, no matter how long the array is, there is no need to continue traversing and **the optimal time complexity $\Omega(1)$ is achieved**.

The "worst time complexity" corresponds to the asymptotic upper bound of the function, expressed in big $O$ notation. Correspondingly, the "best time complexity" corresponds to the asymptotic lower bound of the function, expressed in $\Omega$ notation.

```zig
// generate an array with elements { 1, 2, ..., n } in shuffled order
pub fn randomNumbers(comptime n: usize) [n]i32 {
    var nums: [n]i32 = undefined;
    // generate array nums = { 1, 2, 3, ..., n }
    for (nums) |*num, i| {
        num.* = @intCast(i32, i) + 1;
    }
    // randomly shuffle array elements
    const rand = std.crypto.random;
    rand.shuffle(i32, &nums);
    return nums;
}

// find the index of the number 1 in the array nums
pub fn findOne(nums: []i32) i32 {
    for (nums) |num, i| {
        // when element 1 is at the head of the array, time complexity is the best O(1)
        // when element 1 is at the end of the array, time complexity is the worst O(n)
        if (num == 1) return @intCast(i32, i);
    }
    return -1;
}
```

It is worth noting that we rarely use the optimal time complexity in practice, because it can only be achieved with a small probability, which may be misleading. **The worst time complexity is more practical, because it gives an efficiency security value**, so that we can use the algorithm with confidence.

It can be seen from the above examples that the worst or best time complexity only occurs in "special data distributions". The probability of these situations may be very small and cannot truly reflect the operating efficiency of the algorithm. In contrast, **the average time complexity can reflect the operating efficiency of the algorithm under random input data**, expressed by $\Theta$ notation.

For some algorithms, we can simply extrapolate the average of random data distributions. For example, in the above example, since the input array is shuffled, the probability of element $1$ appearing at any index is equal, then the average number of loops of the algorithm is half $n/2$ of the array length, and the average time complexity is $\Theta(n /2)=\Theta(n)$.

However, for more complex algorithms, it is often difficult to calculate the average time complexity, because it is difficult to analyze the overall mathematical expectation under the data distribution. In this case, we usually use the worst time complexity as a criterion for the efficiency of the algorithm.

>**Why do I rarely see the symbol $\Theta$?**
>Perhaps because the $O$ notation is so catchy, we often use it to represent "average complexity", but in a strict sense, this practice is not standardized. In this book and other materials, if you encounter an expression like "average time complexity $O(n)$", please understand it directly as $\Theta(n)$.

2.4. space complexity

"Space Complexity" is used to measure the growth trend of the memory space occupied by the algorithm as the amount of data increases. The concept is very similar to time complexity, just replace "running time" with "occupied memory space".

2.4.1. Algorithmic correlation space

The memory space used during the running of the algorithm mainly includes the following types:

- **Input space**: used to store the input data of the algorithm.
- **Temporary storage space**: used to store data such as variables, objects, and function contexts during the running of the algorithm.
- **Output space**: used to store the output data of the algorithm.

In general, the statistical range of space complexity is "temporary storage space" plus "output space".

The scratch space can be further divided into three parts:

- **Temporary data**: used to save various constants, variables, objects, etc. during the running of the algorithm.
- **Stack frame space**: used to save the context data of the calling function. The system will create a stack frame at the top of the stack every time a function is called, and the stack frame space will be released after the function returns.
- **Instruction space**: used to save compiled program instructions, usually ignored in actual statistics.

Therefore, when analyzing the space complexity of a program, **we usually count three parts: temporary storage data, output data, and stack frame space**.

Fig. 算法使用的相关空间

```zig
```

2.4.2. Calculation method

The calculation method of space complexity is roughly the same as that of time complexity, just change the statistical object from "number of calculation operations" to "used space size".

Unlike time complexity, **we usually only focus on worst-case space complexity**. This is because memory space is a hard requirement and we must ensure that there is enough memory space reserved under all input data.

Looking at the following code, "worst" in worst space complexity has two meanings.

1. **Based on the worst input data**: when $n<10$, the space complexity is $O(1)$; but when $n>10$, the initialized array `nums` occupies $O(n)$ space; so the worst space complexity is $O(n)$.
2. **Based on the peak memory in the running of the algorithm**: for example, the program occupies $O(1)$ space before executing the last line; when initializing the array `nums`, the program occupies $O(n)$ space; so the worst space complexity is $O(n)$.

```zig
```

**In the recursive function, you need to pay attention to the statistical stack frame space**. For example the following code:

- The function `loop()` calls `function()` $n$ times in the loop, and `function()` in each round returns and releases the stack frame space, so the space complexity is still $O(1)$.
- The recursive function `recur()` will have $n$ unreturned `recur()` during the running process, thus occupying $O(n)$ stack frame space.

```zig
```

2.4.3. common type

Assuming the input data size is $n$, the following figure shows the common types of space complexity (arranged from low to high).

$$O(1)<O(log\,n)<O(n)<O(n^2)<O(2^n)$$
$$\text{constant order}<\text{logarithmic order}<\text{linear order}<\text{square order}<\text{exponential order}$$

![Fig. 空间复杂度的常见类型](./algos/2.4.3.0.png)

>Tip
>Some sample codes require some pre-knowledge, including arrays, linked lists, binary trees, recursive algorithms, etc. If you encounter something you don't understand, you can review it after studying the following chapters.

1. Constant order $O(1)$

Constant order is common in constants, variables, and objects whose number is independent of the input data size $n$.

It should be noted that the memory occupied by initializing variables or calling functions in the loop will be released after entering the next loop, that is, it will not accumulate occupied space, and the space complexity is still $O(1)$:

```zig
[class]{}-[func]{function}

// constant order
fn constant(n: i32) void {
    // constants, variables, objects take up O(1) space
    const a: i32 = 0;
    var b: i32 = 0;
    var nums = [_]i32{0}**10000;
    var node = inc.ListNode(i32){.val = 0};
    var i: i32 = 0;
    // variables in loops take O(1) space
    while (i < n) : (i += 1) {
        var c: i32 = 0;
        _ = c;
    }
    // functions in loops take O(1) space
    i = 0;
    while (i < n) : (i += 1) {
        _ = function();
    }
    _ = a;
    _ = b;
    _ = nums;
    _ = node;
}
```

2. Linear order $O(n)$

Linear order is common in arrays, linked lists, stacks, queues, etc. where the number of elements is proportional to $n$:

```zig
// linear order
fn linear(comptime n: i32) !void {
    // an array of length n takes O(n) space
    var nums = [_]i32{0}**n;
    // a list of length n takes O(n) space
    var nodes = std.ArrayList(i32).init(std.heap.page_allocator);
    defer nodes.deinit();
    var i: i32 = 0;
    while (i < n) : (i += 1) {
        try nodes.append(i);
    }
    // a hash table of length n takes O(n) space
    var map = std.AutoArrayHashMap(i32, []const u8).init(std.heap.page_allocator);
    defer map.deinit();
    var j: i32 = 0;
    while (j < n) : (j += 1) {
        const string = try std.fmt.allocPrint(std.heap.page_allocator, "{d}", .{j});
        defer std.heap.page_allocator.free(string);
        try map.put(i, string);
    }
    _ = nums;
}
```

As shown in the following picture, the recursion depth of this function is $n$, that is, there are $n$ unreturned `linear_recur()` functions at the same time, and the stack frame space of $O(n)$ size is used:

```zig
// linear order (recursive implementation)
fn linearRecur(comptime n: i32) void {
    std.debug.print("Recursion n = {}\n", .{n});
    if (n == 1) return;
    linearRecur(n - 1);
}
```

![Fig. 递归函数产生的线性阶空间复杂度](./algos/2.4.3.2.png)

3. Square order $O(n2)$

Quadratic order is common in matrices and graphs, where the number of elements is quadratic with $n$.

```zig
// square order
fn quadratic(n: i32) !void {
    // 2-dimensions list takes O(n^2) space
    var nodes = std.ArrayList(std.ArrayList(i32)).init(std.heap.page_allocator);
    defer nodes.deinit();
    var i: i32 = 0;
    while (i < n) : (i += 1) {
        var tmp = std.ArrayList(i32).init(std.heap.page_allocator);
        defer tmp.deinit();
        var j: i32 = 0;
        while (j < n) : (j += 1) {
            try tmp.append(0);
        }
        try nodes.append(tmp);
    }
}
```

As shown in the following picture, the recursion depth of this function is $n$, and an array is initialized in each recursive function, the lengths are $n,n-1,...,2,1$, and the average length is $n/2$, so $O(n2)$ space overall:

```zig
// square order (recursive implementation)
fn quadraticRecur(comptime n: i32) i32 {
    if (n <= 0) return 0;
    var nums = [_]i32{0}**n;
    std.debug.print("Recursion n = {} length of nums = {}\n", .{n, nums.len});
    return quadraticRecur(n - 1);
}
```

![Fig. 递归函数产生的平方阶空间复杂度](./algos/2.4.3.3.png)

4. Exponential order $O(2n)$

Exponential order is common in binary trees. Observe in the following picture, the number of nodes of a "full binary tree" with height $n$ is $2^n-1$, occupying $O(2n)$ space:

```zig
// exponential order (build a full binary tree)
fn buildTree(mem_allocator: std.mem.Allocator, n: i32) !?*inc.TreeNode(i32) {
    if (n == 0) return null;
    const root = try mem_allocator.create(inc.TreeNode(i32));
    root.init(0);
    root.left = try buildTree(mem_allocator, n - 1);
    root.right = try buildTree(mem_allocator, n - 1);
    return root;
}
```

![Fig. 满二叉树产生的指数阶空间复杂度](./algos/2.4.3.4.png)

5. Logarithmic order $O(log\,n)$

Logarithmic order is common in divide and conquer algorithms. For example, merge sort, input an array of length $n$, each round of recursion divides the array into two halves from the midpoint, forming a recursive tree with a height of $log\,n$, using $O(log\,n)$ stack frame space.

Another example is to convert a number into a string, input a positive integer $n$, and its number of digits is $log_{10}\,n+1$, that is, the corresponding string length is $log_{10}\,n+1$, so the space complexity is $O(log_{10}\,n+1)=O(log\,n)$.

2.4.4. balance time and space

Ideally, we hope that the time complexity and space complexity of the algorithm can be optimal. However, in practical situations, it is usually very difficult to simultaneously optimize time complexity and space complexity.

**Reducing time complexity usually comes at the expense of increasing space complexity, and vice versa**. We call the idea of sacrificing memory space to improve the running speed of the algorithm as "trading space for time"; otherwise, it is called "trading time for space".

Which idea to choose depends on which aspect we value more. In most cases, time is more valuable than space, so trading space for time is usually the more common strategy. Of course, in the case of a large amount of data, it is also very important to control the space complexity.

2.5. summary

Algorithm Efficiency Evaluation

- Time efficiency and space efficiency are two key dimensions for evaluating algorithm performance.
- We can evaluate the efficiency of the algorithm through actual testing, but it is difficult to eliminate the impact of the testing environment, and it will consume a lot of computing resources.
- Complexity analysis can overcome the disadvantages of actual testing, the analysis results are applicable to all operating platforms, and can reveal the efficiency of algorithms under different data scales.

time complexity

- Time complexity is used to measure the trend of the algorithm's running time increasing with the amount of data, which can effectively evaluate the efficiency of the algorithm, but it may fail in some cases, such as when the amount of input data is small or the time complexity is the same, it is impossible to accurately compare the algorithms The pros and cons of efficiency.
- The worst time complexity is represented by Big O notation, which is the asymptotic upper bound of the function, reflecting the growth level of T(n) when n tends to positive infinity.
- Calculating the time complexity is divided into two steps, first counting the number of calculation operations, and then estimating the asymptotic upper bound.
- The common time complexity is O(1), O(log n), O(n), O(n logn), O(n2), O(2n), O(n!) etc. from small to large.
- The time complexity of some algorithms is not fixed, but related to the distribution of the input data. The time complexity is divided into worst, best, and average time complexity. The best time complexity is almost useless, because the input data generally needs to meet strict conditions to achieve the best situation.
- The average time complexity reflects the operating efficiency of the algorithm under random data input, which is closest to the algorithm performance in practical applications. Calculating the average time complexity requires statistical distribution of input data and mathematical expectations after synthesis.

space complexity

- Similar to time complexity, space complexity is used to measure the trend of the space occupied by the algorithm as the amount of data grows.
- The relevant memory space during the operation of the algorithm can be divided into input space, temporary storage space, and output space. Normally, the input space is not included in the space complexity calculation. The temporary storage space can be divided into instruction space, data space, and stack frame space. The stack frame space usually only affects the space complexity in recursive functions.
- We usually only focus on the worst space complexity, that is, the space complexity of the statistical algorithm under the worst input data and worst running time point.
- Common space complexities are $O(1)$, $O(log\,n)$, $O(n)$, $O(n^2)$, $O(2^n)$, etc. from small to large.

2.4.1. Q & A

>**Is the space complexity of tail recursion $O(1)$?**
>Theoretically, the space complexity of tail recursive functions can be optimized to $O(1)$. However, most programming languages (such as Java, Python, C++, Go, C#, etc.) do not support automatic optimization of tail recursion, so the space complexity is generally considered to be $O(n)$.

>**What is the difference between the terms function and method?**
>Functions can be executed independently, and all parameters are passed explicitly. A method is associated with an object. The method is implicitly passed to the object that calls it. The method can operate on the data contained in the instance of the class.
>
>Take several common programming languages as examples:
>
>- C language is a procedural programming language, there is no object-oriented concept, so there are only functions. But we can simulate object-oriented programming by creating a structure (struct), and the function associated with the structure is equivalent to the method in other languages.
>- Java, C# are object-oriented programming languages, code blocks (methods) are usually part of a class. A static method behaves like a function because it is bound to the class and cannot access specific instance variables.
>- C++, Python supports both procedural programming (functions) and object-oriented programming (methods).

>**Does the picture "Common types of space complexity" reflect the absolute size of the occupied space?**
>No, the graph shows the space complexity, which reflects the growth trend, not the absolute size of the occupied space.
>
>Assuming $n=8$, you may find that the value of each curve does not correspond to the function. This is because each curve contains a constant term that compresses the range of values into a visually comfortable range.
>
>In practice, because we usually don't know the "constant term" complexity of each method, it is generally impossible to select the optimal solution under $n=8$ based on complexity alone. But it is a good choice for $n=8^5$, when the growth trend is already dominant.

3. data structures

>**Abstract**
>A data structure are like a solid and diverse framework.
>
>It provides a blueprint for the orderly organization of data, enabling algorithms to come to life on this basis.

3.1. Data Structure Classification

Common data structures include arrays, linked lists, stacks, queues, hash tables, trees, heaps, and graphs, which can be classified into two dimensions: "logical structure" and "physical structure".

3.1.1. Logical Structure: Linear vs. Non-linear

**The logical structure reveals the logical relationships between data elements**. In arrays and linked lists, data is arranged sequentially, reflecting a linear relationship between the data; In the tree, the data is arranged hierarchically from the top down, showing the derived relationship between ancestors and descendants; diagrams are made up of nodes and edges, reflecting complex network relationships.

As shown in the following picture, logic structures can be divided into two categories: "linear" and "non-linear". The linear structure is intuitive, which means that the data is arranged linearly in logical relationships; non-linear structures, on the other hand, are arranged nonlinearly.

- **Linear data structures**: arrays, linked lists, stacks, queues, hash tables.
- **Non-linear data structures**: trees, heaps, graphs, hash tables.

![Fig. 线性与非线性数据结构](./algos/3.1.1.png)

Non-linear data structures can be further divided into tree structures and network structures.

- **Linear structure**: arrays, linked lists, queues, stacks, hash tables, elements have a one-to-one order relationship.
- **Tree structure**: tree, heap, hash table, elements have a one-to-many relationship.
- **Network structure**: a graph, where elements have a many-to-many relationship.

3.1.2. Physical Structure: Continuous vs. Discrete

In computers, memory and hard disks are the two main storage hardware devices. Hard drives are primarily used for long-term data storage and are relatively large (often in the terabyte range) and relatively slow. Memory is used to temporarily store data when running programs, and it is fast, but has a small capacity (usually at the GB level).

**During the operation of the algorithm, relevant data are stored in memory**. The following picture shows a computer memory stick, where each black square contains a memory space. We can think of memory as a huge Excel table, where each cell can store 1 byte of data, and all data is stored in these cells when the algorithm is running.

**The system accesses the data of the target memory location through the "memory address Memory Location"**. As shown in the following picture, the computer assigns numbers to each cell in the table according to certain rules, ensuring that each memory space has a unique memory address. With these addresses, the program can access the data in memory.

![Fig. 内存条、内存空间、内存地址](./algos/3.1.2.1.png)

Memory is a shared resource of all programs. When the memory is occupied by a program, other programs cannot use it at the same time. **Therefore, memory resources are an important consideration in the design of data structures and algorithms**. For example, the peak memory occupied by the algorithm should not exceed the remaining free memory of the system; if there are many running programs and lack of a large amount of contiguous memory space, then the selected data structure must be able to be stored in a discrete memory space.

As shown in the following picture, **the physical structure reflects the way data is stored in computer memory**, which can be divided into continuous space storage of arrays and discrete space storage of linked lists. The physical structure determines the operation methods of data access, update, addition and deletion from the bottom layer, and at the same time presents complementary characteristics in terms of time efficiency and space efficiency.

![Fig. 连续空间存储与离散空间存储](./algos/3.1.2.2.png)

It is worth noting that **all data structures are implemented based on arrays, linked lists, or a combination of the two**. For example, stacks and queues can be implemented using both arrays and linked lists; and an implementation of a hash table might contain both an array and a linked list.

- **Based on arrays**: stacks, queues, hash tables, trees, heaps, graphs, matrices, tensors (arrays with dimensions $\ge3$), etc.
- **Based on linked list**: stack, queue, hash table, tree, heap, graph, etc.

Data structures implemented based on arrays are also referred to as "static data structures", which means that such data structures do not have a variable length after initialization. Correspondingly, the data structure implemented based on the linked list is called a "dynamic data structure". After initialization, the length of this type of data structure can still be adjusted during the running of the program.

>**Tip**
>If you feel that it is difficult to understand the physical structure, it is recommended to read the next chapter "Arrays and Linked Lists" first, and then review the content of this section.

3.2. Basic data types¶

When it comes to data in computers, we think of various forms such as text, pictures, videos, voices, 3D models, etc. Although these data are organized in different forms, they are all composed of various basic data types.

**The basic data types are the types that the CPU can directly operate on**, and are directly used in the algorithm, mainly including the following types:

- Integer types `byte`, `short`, `int`, `long .
- Floating point type `float`, `double`, used to represent decimals.
- The character type `char`, used to represent letters, punctuation marks, and even emoji in various languages.
- Boolean type `bool`, used to represent "yes" and "no" estimations.

**Basic data types are stored in the computer in binary form**. One binary bit is 1 bit. In most modern systems, a byte consists of 8 bits.

The value range of a basic data type depends on the space it occupies. For example, Java stipulates:

- The integer type `byte` occupies $1\,byte=8\,bits$ and can represent $2^8$ numbers.
- The integer type `int` occupies $4\,bytes=32\,bits$ and can represent $2^{32}$ numbers.

The following table lists the occupied space, value range and default value of various basic data types. There is no need to memorize this form, just a general understanding, and it can be recalled by looking up the table when necessary.

|Type|Symbol|Footprint|Min|Max|Default|
|---|---|---|---|---|---|
|integer|`byte`|1 byte|$-2^7(-128)$|$2^7-1(127)$|$0$|
||`short`|2 bytes|$-2^15$|$2^{15}-1$|$0$|
||`int`|4 bytes|$-2^31$|$2^{31}-1$|$0$|
||`long`|8 bytes|$-2^63$|$2^{63}-1$|$0$|
|floating point number|`float`|4 bytes|$1.175\times10^{-38}$|$3.403\times10^{38}$|$0.0\text{f}$|
||`double`|8 bytes|$2.225\times10^{-308}$|$1.798\times10^{308}$|$0.0$|
|character|`char`|4 bytes/1 byte|$0$|$2^{16}-1$|$0$|
|boolean|`bool`|1 byte|$\text{false}$|$\text{true}$|$\text{false}$|

For the table above, note the following:

- C, C++ does not specify the size of the basic data type, but it varies with implementation and platform. The above table follows the LP64 [data model](https://en.cppreference.com/w/cpp/language/types#Properties), which is used on Unix 64-bit operating systems (eg Linux , macOS).
- The size of character `char` is 1 byte in C, C++, and depends on the specific character encoding method in most programming languages, see the "Character Encoding" chapter for details.
- Modern computer CPUs usually use 1 byte as the smallest addressable memory unit. So even though only 1 bit ($0$ or $1$) is needed to represent a boolean, it is usually stored as 1 byte in memory.

So, what is the connection between primitive data types and data structures? We know that a data structure is the way data is organized and stored in a computer. Its subject is "structure", not "data".

If we want to represent "a row of numbers", we naturally think of using an array. This is because the linear structure of the array can represent the adjacent relationship and order relationship of numbers, but as for the stored content is an integer `int`, a decimal `float`, or a character `char`, it has nothing to do with the "data structure".

In other words, **primitive data types provide the "content type" of the data, while data structures provide the "organization" of the data**. For example, in the following code, we use the same data structure (array) to store and represent different basic data types, including `int`, `float`, `char`, `bool`, etc.

```zig
```

3.3. Binary code*

>**Note**
>In this book, titles marked with a * are optional chapters. If you have limited time or find it difficult to understand, it is recommended to skip it first, and then tackle it alone after finishing the required chapters.

3.3.1. Original, Inverse and Complement

From the table in the previous section, we found that all integer types can represent one more negative number than positive number. For example, the value range of byte is $[-128,127]$. This phenomenon is quite counter-intuitive, and its internal reason involves the relevant knowledge of original code, inverse code, and complement code.

First of all, it needs to be pointed out that numbers are stored in the computer in the form of "complement". Before analyzing the reasons for this, we first give the definitions of the three representations.

- **Original code**: We consider the highest bit of the binary representation of a number as the sign bit, where $0$ indicates a positive number, $1$ indicates a negative number, and the remaining bits indicate the value of the number.
- **Inverse code**: The inverse code of a positive number is the same as its original code, and the inverse code of a negative number is the inversion of all bits except the sign bit of its original code.
- **Complement code**: the complement code of a positive number is the same as its original code, and the complement code of a negative number is based on its inverse code plus 1.

The following picture shows the conversion method between original, inverse and complement.

![Fig. 原码、反码与补码之间的相互转换](./algos/3.3.1.png)

Although the "true form of the original code" is the most intuitive, it has some limitations. On the one hand, **the original code of negative numbers cannot be directly used in operations**. For example, when calculating $1+(-2)$ under the original code, the result is $-3$, which is obviously wrong.

$$\begin{align*}
&1+(-2)\\
&\rightarrow0000\,0001+1000\,0010\\
&=1000\,0011\\
&=-3
\end{align*}$$

In order to solve this problem, the computer introduced "one's complement code". If we first convert the original code to the inverse code, and calculate $1+(-2)$ under the inverse code, and finally convert the result from the inverse code back to the original code, we can get the correct result $-1$.
$$\begin{align*}
&1+(-2)\\
&\rightarrow00000001(\text{original code})+10000010(\text{original code})\\
&=00000001(\text{inverse code})+11111101(\text{inverse code})\\
&=11111110(\text{inverse code})\\
&=10000001(\text{original code})\\
&=-1
\end{align*}$$
On the other hand, **the original code of the number zero has two representations of $+0$ and $-0$**. This means that the number zero corresponds to two different binary codes, which can cause ambiguity problems. For example, in conditional estimation, if there is no distinction between positive zero and negative zero, it may lead to wrong estimation results. If we want to deal with positive zero and negative zero ambiguity, we need to introduce additional estimation operations, which may reduce the computing efficiency of the computer.
$$
+0\rightarrow00000000\\
-0\rightarrow10000000
$$
Like the original code, the inverse code also has the problem of positive and negative zero ambiguity. For this reason, the computer further introduces "2's complement code". Let's first observe the conversion process of the original code, inverse code, and complement code of negative zero:
$$\begin{align*}
&-0\rightarrow10000000(original code)\\
&=11111111(inverse code)\\
&=100000000(complement)
\end{align*}$$
Adding $1$ to the complement of negative zero will generate a carry, and since the length of the `byte` type is only 8 bits, so the $1$ overflowing to the ninth bit will be discarded. **Thus the complement of negative zero is $0000\,0000$, which is the same as the complement of positive zero**. This means that there is only one zero in the two's complement representation, resolving the positive and negative zero ambiguity.

There is one last doubt left: the value range of the `byte` type is $[-128,127]$, how to get the extra negative number $-128$? We noticed that all integers in the interval $[-127,+127]$ have corresponding original code, inverse code and complement code, and the original code and complement code can be converted to each other.

However, **the two's complement $1000\,0000$ is an exception, it does not have a corresponding original code**. According to the conversion method, we get the original code of this complement as $0000\,0000$. This is clearly contradictory, since the original code represents the number $0$, whose complement should be itself. The computer specifies that this special two's complement $1000\,0000$ represents $-128$. In fact, $(-1)+(-127)$ evaluates to $-128$ in two's complement.

$$\begin{align*}
&(-127)+(-1)\\
&\rightarrow11111111(\text{original code})+10000001(\text{original code})\\
&=10000000(\text{inverse code})+11111110(\text{inverse code})\\
&=10000001(\text{complement})+11111111(\text{complement})\\
&=10000000(\text{complement})\\
&\rightarrow-128
\end{align*}$$

You may have noticed that all the calculations above are addition operations. This implies an important fact: **the hardware circuit inside the computer is mainly designed based on the addition operation**. This is because addition operations are simpler to implement in hardware than other operations such as multiplication, division, and subtraction, and are easier to parallelize for faster operations.

However, this does not mean that computers can only do addition. **By combining addition with some basic logical operations, computers are able to perform various other mathematical operations**. For example, to calculate the subtraction $a-b$ can be converted to calculating addition $a+(-b)$; calculating multiplication and division can be converted to calculating multiple additions or subtractions.

Now, we can summarize the reason why computers use two's complement: Based on two's complement representation, computers can use the same circuits and operations to handle the addition of positive and negative numbers, no need to design special hardware circuits to handle subtraction, and no special processing The ambiguity of plus and minus zero. This greatly simplifies hardware design and improves computing efficiency.

The design of the complement code is very delicate, and we will introduce it here first due to space constraints. Interested readers are advised to further in-depth understanding.

3.3.2. Floating point encoding

If you are careful, you may find that `int` and `float` have the same length, both are 4 bytes, but why the value range of `float` is much larger than that of `int`? This is very counter-intuitive, because it stands to reason that `float` needs to represent decimals, and the value range should be smaller.

In fact, **this is because of the different representation of the floating-point number `float`**. Note that a 32-bit length binary number is:
$$b_{31}b_{30}b_{29}...b_2b_1b_0$$
According to the IEEE 754 standard, a 32-bit length `float` consists of the following parts:

- Sign bit S: occupies 1 bit, corresponding to $b_{31}$.
- Exponent bit E: occupies 8 bits, corresponding to $b_{30}b_{29}...b_{23}$.
- Mantissa bit N: 23 bits, corresponding to $b_{22}b_{21}...b_0$.

The value corresponding to the binary float is calculated by:
$$val=(-1)^{b_{31}}\times2^{(b_{30}b_{29}...b_{20})*2-127}\times(1 \cdot b*{22}b_{21}...b_0)*2$$
The calculation formula converted to decimal system:
$$val=(-1)^S\times2^{E-127}\times(1+N)$$
The value range of each item:
$$S\in\{0,1\},\,E\in\{1,2,...,254\}$$
$$(1+N)=(1+\sum_{i=1}^{23}b_{23-i}2^{-i})\subset[1,2-2^{-23}]$$

![Fig. IEEE 754 标准下的 float 表示方式](./algos/3.3.2.png)

Take the above picture as an example, given S=0, E=124, N=2-2+2-3=0.375, then:
$$val=(-1)^0\times2^{124-127}\times(1+0.375)=0.171875$$
Now we can answer the original question: **float's representation includes exponent bits, resulting in a much larger range of values than int**. According to the above calculation, the maximum positive number that float can represent is $2^{254-127}\times(2-2^{-23})\approx3.4\times10^{38}$, and the smallest negative number can be obtained by switching the sign bit.

**Although the floating-point number `float` expands the range of values, it has the side effect of sacrificing precision**. The integer type `int` uses all 32 bits to represent numbers, and the numbers are evenly distributed; due to the existence of exponent bits, the larger the value of the floating-point number `float`, the larger the difference between two adjacent numbers will tend to be.

As shown in the following tqable the exponent bits $E=0$ and $E=255$ have special meanings and are used to represent zero, infinity, $NaN$ and so on.

|ExponentbitE|ScoreN=0|fraction $N\ne0$|Calculation formula|
|---|---|---|---|
|$0$|$\pm0$|subnormal number|$(-1)^S\times2^{-126}\times(0.N)$|
|$1,2,...,254$|normal number|normal number|$(-1)^S\times2^{(E-127)}\times(1.N)$|
|$255$|$\pm\infty$|$NaN$||

It is worth noting that subnormal numbers significantly improve the precision of floating-point numbers. The smallest positive normal number is $2^{-126}$, and the smallest positive subnormal number is $2^{-126}x2^{-23}$.

Double-precision `double` also adopts a representation method similar to `float`, which will not be described in detail here.

3.4. Character Encoding*

In a computer, all data is stored in the form of binary numbers, and the character `char` is no exception. In order to represent characters, we need to establish a "character set" that specifies the one-to-one correspondence between each character and a binary number. With the character set, the computer can complete the conversion from binary numbers to characters by looking up the table.

3.4.1. ASCII character set

"ASCII code" is the earliest character set, and its full name is "American Standard Code for Information Interchange". It uses a 7-bit binary number (that is, the lower 7 bits of a byte) to represent a character, and can represent up to 128 different characters. This includes the case of the English alphabet, the numbers 0-9 , some punctuation marks, and some control characters such as newlines and tabs.

| decimal | binary    | character | meaning                   | decimal | binary    | character | meaning                   |
|---------|-----------|-----------|---------------------------|---------|-----------|-----------|---------------------------
| 0       | 00000000  | NUL       | Null                      | 65      | 01000001  | A         | Capital A                 |
| 1       | 00000001  | SOH       | Start of Header           | 66      | 01000010  | B         | Capital B                 |
| 2       | 00000010  | STX       | Start of Text             | 67      | 01000011  | C         | Capital C                 |
| 3       | 00000011  | ETX       | End of Text               | 68      | 01000100  | D         | Capital D                 |
| 4       | 00000100  | EOT       | End of Transmission       | 69      | 01000101  | E         | Capital E                 |
| 5       | 00000101  | ENQ       | Enquiry                   | 70      | 01000110  | F         | Capital F                 |
| 6       | 00000110  | ACK       | Acknowledge               | 71      | 01000111  | G         | Capital G                 |
| 7       | 00000111  | BEL       | Bell                      | 72      | 01001000  | H         | Capital H                 |
| 8       | 00001000  | BS        | Backspace                 | 73      | 01001001  | I         | Capital I                 |
| 9       | 00001001  | HT        | Horizontal Tab            | 74      | 01001010  | J         | Capital J                 |
| 10      | 00001010  | LF        | Line Feed                 | 75      | 01001011  | K         | Capital K                 |
| 11      | 00001011  | VT        | Vertical Tab              | 76      | 01001100  | L         | Capital L                 |
| 12      | 00001100  | FF        | Form Feed                 | 77      | 01001101  | M         | Capital M                 |
| 13      | 00001101  | CR        | Carriage Return           | 78      | 01001110  | N         | Capital N                 |
| 14      | 00001110  | SO        | Shift Out                 | 79      | 01001111  | O         | Capital O                 |
| 15      | 00001111  | SI        | Shift In                  | 80      | 01010000  | P         | Capital P                 |
| 16      | 00010000  | DLE       | Data Link Escape          | 81      | 01010001  | Q         | Capital Q                 |
| 17      | 00010001  | DC1       | Device Control 1          | 82      | 01010010  | R         | Capital R                 |
| 18      | 00010010  | DC2       | Device Control 2          | 83      | 01010011  | S         | Capital S                 |
| 19      | 00010011  | DC3       | Device Control 3          | 84      | 01010100  | T         | Capital T                 |
| 20      | 00010100  | DC4       | Device Control 4          | 85      | 01010101  | U         | Capital U                 |
| 21      | 00010101  | NAK       | Negative Acknowledge      | 86      | 01010110  | V         | Capital V                 |
| 22      | 00010110  | SYN       | Synchronize               | 87      | 01010111  | W         | Capital W                 |
| 23      | 00010111  | ETB       | End of Transmission Block | 88      | 01011000  | X         | Capital X                 |
| 24      | 00011000  | CAN       | Cancel                    | 89      | 01011001  | Y         | Capital Y                 |
| 25      | 00011001  | EM        | End of Medium             | 90      | 01011010  | Z         | Capital Z                 |
| 26      | 00011010  | SUB       | Substitute                | 91      | 01011011  | [         | Left square bracket       |
| 27      | 00011011  | ESC       | Escape                    | 92      | 01011100  | \         | Backslash                 |
| 28      | 00011100  | FS        | File Separator            | 93      | 01011101  | ]         | Right square bracket      |
| 29      | 00011101  | GS        | Group Separator           | 94      | 01011110  | ^         | Caret / circumflex        |
| 30      | 00011110  | RS        | Record Separator          | 95      | 01011111  | _         | Underscore                |
| 31      | 00011111  | US        | Unit Separator            | 96      | 01100000  | `         | Grave / accent            |  
| 32      | 00100000  | Space     | Space                     | 97      | 01100001  | a         | Small a                   |  
| 33      | 00100001  | !         | Exclamation mark          | 98      | 01100010  | b         | Small b                   |  
| 34      | 00100010  | "         | Double quote              | 99      | 01100011  | c         | Small c                   |
| 35      | 00100011  | #         | Number                    | 100     | 01100100  | d         | Small d                   |  
| 36      | 00100100  | $         | Dollar sign               | 101     | 01100101  | e         | Small e                   |
| 37      | 00100101  | %         | Percent                   | 102     | 01100110  | f         | Small f                   |  
| 38      | 00100110  | &         | Ampersand                 | 103     | 01100111  | g         | Small g                   |
| 39      | 00100111  | '         | Single quote              | 104     | 01101000  | h         | Small h                   |  
| 40      | 00101000  | (         | Left parenthesis          | 105     | 01101001  | i         | Small i                   |  
| 41      | 00101001  | )         | Right parenthesis         | 106     | 01101010  | j         | Small j                   |  
| 42      | 00101010  | *         | Asterisk                  | 107     | 01101011  | k         | Small k                   |  
| 43      | 00101011  | +         | Plus                      | 108     | 01101100  | l         | Small l                   |  
| 44      | 00101100  | ,         | Comma                     | 109     | 01101101  | m         | Small m                   |  
| 45      | 00101101  | -         | Minus                     | 110     | 01101110  | n         | Small n                   |  
| 46      | 00101110  | .         | Period                    | 111     | 01101111  | o         | Small o                   |  
| 47      | 00101111  | /         | Slash                     | 112     | 01110000  | p         | Small p                   |  
| 48      | 00110000  | 0         | Zero                      | 113     | 01110001  | q         | Small q                   |  
| 49      | 00110001  | 1         | One                       | 114     | 01110010  | r         | Small r                   |  
| 50      | 00110010  | 2         | Two                       | 115     | 01110011  | s         | Small s                   |  
| 51      | 00110011  | 3         | Three                     | 116     | 01110100  | t         | Small t                   |  
| 52      | 00110100  | 4         | Four                      | 117     | 01110101  | u         | Small u                   |  
| 53      | 00110101  | 5         | Five                      | 118     | 01110110  | v         | Small v                   |  
| 54      | 00110110  | 6         | Six                       | 119     | 01110111  | w         | Small w                   |  
| 55      | 00110111  | 7         | Seven                     | 120     | 01111000  | x         | Small x                   |  
| 56      | 00111000  | 8         | Eight                     | 121     | 01111001  | y         | Small y                   |  
| 57      | 00111001  | 9         | Nine                      | 122     | 01111010  | z         | Small z                   |  
| 58      | 00111010  | :         | Colon                     | 123     | 01111011  | {         | Left curly bracket        |  
| 59      | 00111011  | ;         | Semicolon                 | 124     | 01111100  | |         | Vertical bar              |  
| 60      | 00111100  | <         | Less than                 | 125     | 01111101  | }         | Right curly bracket       |  
| 61      | 00111101  | =         | Equality sign             | 126     | 01111110  | ~         | Tilde                     |  
| 62      | 00111110  | >         | Greater than              | 127     | 01111111  | DEL       | Delete                    |  
| 63      | 00111111  | ?         | Question mark             |  
| 64      | 01000000  | @         | At sign                   |

However, **ASCII codes can only represent English**. With the globalization of computers, a character set "EASCII" capable of representing more languages was born. It expands to 8 bits based on ASCII's 7 bits, and can represent 256 different characters. Worldwide, a number of EASCII character sets suitable for different regions have emerged one after another. The first 128 characters of these character sets are unified as ASCII codes, and the last 128 characters are defined differently to meet the needs of different languages.

3.4.2. GBK character set

It was later discovered that **the EASCII code was still insufficient for the number of characters required by many languages**. For example, there are about 100,000 Chinese characters, and only a few thousand are used in daily use. The General Administration of Standards of China released the "GB2312" character set in 1980, which contains 6763 Chinese characters, which basically meets the needs of computer processing of Chinese characters.

However, GB2312 cannot handle some rare and traditional characters. Later, on the basis of GB2312, the "GBK" character set was expanded, which contained a total of 21886 Chinese characters. In the GBK encoding scheme, ASCII characters are represented by one byte, and Chinese characters are represented by two bytes.

3.4.3. Unicode character set

With the vigorous development of computers, character sets and encoding standards have flourished, and this has brought many problems. On the one hand, these character sets generally only define the characters of a specific language and cannot work normally in a multilingual environment; on the other hand, there are multiple character set standards in the same language. If two computers are installed with different encoding standards , then there will be garbled characters when the information is transmitted.

People in that era were thinking: **If a sufficiently complete character set is introduced to include all languages and symbols in the world, won't it be possible to solve the problem of cross-language environments and garbled characters**? Driven by this idea, a large and comprehensive character set Unicode came into being.

The full name of "Unicode" is "Unicode", which can theoretically accommodate more than one million characters. It is committed to incorporating characters from all over the world into a unified character set, providing a common character set to process and display various languages, and reducing garbled characters caused by different encoding standards.

Since its release in 1991, Unicode has been continuously expanded with new languages and characters. As of September 2022, Unicode already contains 149,186 characters, including characters, symbols, and even emoji in various languages. In the huge Unicode character set, commonly used characters occupy 2 bytes, and some uncommon characters occupy 3 bytes or even 4 bytes.

Unicode is a character set standard that essentially assigns a number (called a "code point") to each character, **but it doesn't dictate how those character code points are stored in a computer**. We can't help asking: How does the system parse characters when Unicode code points of multiple lengths appear in the same text at the same time? For example, given an encoding with a length of 2 bytes, how does the system determine whether it is one 2-byte character or two 1-byte characters?

**A straightforward solution to the above problem is to store all characters as equal-length codes**. As shown in the figure below, each character in "Hello" occupies 1 byte, and each character in "Algorithm" occupies 2 bytes. We can encode all characters in the "Hello Algorithm" into 2-byte length by filling high bits with 0. In this way, the system can parse a character every 2 bytes and recover the content of this phrase.

![Fig. Unicode 编码示例](./algos/3.4.3.png)

However, ASCII has shown us that only 1 byte is needed to encode English. If the above solution is adopted, the size of the space occupied by the English text will be twice the size of the ASCII encoding, which is a waste of memory space. Therefore, we need a more efficient Unicode encoding method.

3.4.4. UTF-8 encoding

Currently, UTF-8 has become the most widely used Unicode encoding method in the world. **It is a variable-length encoding** that uses 1 to 4 bytes to represent a character, depending on the complexity of the character. ASCII characters only need 1 byte, Latin and Greek letters need 2 bytes, commonly used Chinese characters need 3 bytes, and some other rare characters need 4 bytes.

The encoding rules of UTF-8 are not complicated and can be divided into two cases:

- For characters 1 byte long, set the highest bit to $0$ and the remaining 7 bits to the Unicode code point. It's worth noting that ASCII characters occupy the first 128 code points of the Unicode character set. In other words, **UTF-8 encoding can be backward compatible with ASCII code**. This means we can use UTF-8 to parse age-old ASCII text.
- For a character with a length of $n$ bytes (where $n>1$), set the upper $n$ bits of the first byte to $1$, and set the $n+1th$ bit to $0$; starting from the second byte, set the upper 2 bits of the byte to $10$; all remaining bits are used to pad the Unicode code point of the character.

The following picture shows the UTF-8 encoding corresponding to the "Hello algorithm". Observe that since the highest $n$ bits are all set to $1$, the system can parse out the length of the character as $n$ by reading the number of the highest bit $1$.

But why set the upper 2 bits of all the rest of the bytes to $10$? In fact, this $10$ can act as a validator. Assuming that the system starts to parse the text from a wrong byte, the $10$ in the byte header can help the system quickly estimate the abnormality.

The reason why $10$ is used as a check character is because under the UTF-8 encoding rules, it is impossible for the highest two digits of a character to be $10$. This conclusion can be proved by contradictory method: Suppose the highest two digits of a character are $10$, indicating that the length of the character is $1$, which corresponds to the ASCII code. The highest bit of the ASCII code should be $0$, which contradicts the assumption.

![Fig. UTF-8 编码示例](./algos/3.4.4.png)

In addition to UTF-8, common encoding methods include the following.

- **UTF-16 encoding**: use 2 or 4 bytes to represent a character. All ASCII characters and many commonly used non-English characters are represented by 2 bytes; a few characters need to be represented by 4 bytes. For 2-byte characters, the UTF-16 encoding is equivalent to a Unicode code point.
- **UTF-32 encoding**: Each character uses 4 bytes. This means that UTF-32 will take up more space than UTF-8 and UTF-16, especially for text that uses mostly ASCII characters.

From the perspective of storage space, using UTF-8 to represent English characters is very efficient because it only requires 1 byte; it is more efficient to use UTF-16 to encode some non-English characters (such as Chinese) because it only requires 2 bytes bytes, while UTF-8 may require 3 bytes.

From the perspective of compatibility, UTF-8 has the best versatility, and many tools and libraries support UTF-8 first.

3.4.5. Character Encoding for Programming Languages

For most programming languages in the past, the strings in the running program are encoded with equal length such as UTF-16 or UTF-32. This is because under equal-length encoding, we can treat strings as arrays, which has the following advantages:

- **Random access**: UTF-16 encoded strings can be easily accessed randomly. UTF-8 is a variable-length encoding. To find the $ith$ character, we need to traverse from the beginning of the string to the $ith$ character, which takes $O(n)$ time.
- **Character counting**: Similar to random access, calculating the length of a UTF-16 string is also an $O(1)$ operation. However, calculating the length of a UTF-8 encoded string requires traversing the entire string.
- **String operations**: Many string operations (such as split, concatenate, insert, delete, etc.) are easier to perform on UTF-16 encoded strings. Doing these operations on UTF-8 encoded strings usually requires extra computation to ensure that invalid UTF-8 encodings are not produced.

The design of character encoding schemes for programming languages is an interesting topic involving many factors:

- Java's `String` type uses UTF-16 encoding, and each character occupies 2 bytes. This is because the Java language was originally designed with the belief that 16 bits would be sufficient to represent all possible characters. However, this is an incorrect estimation. Later the Unicode specification was extended beyond 16 bits, so characters in Java may now be represented by a pair of 16-bit values (called a "surrogate pair").
- JavaScript and TypeScript strings are UTF-16 encoded for similar reasons as Java. When the JavaScript language was first introduced by Netscape in 1995, Unicode was in its relatively early days when 16-bit encodings were sufficient to represent all Unicode characters.
- C# uses UTF-16 encoding, mainly because the .NET platform was designed by Microsoft, and many Microsoft technologies, including the Windows operating system, use UTF-16 encoding extensively.

Due to the underestimation of the number of characters in the above programming languages, they have to adopt "surrogate pairs" to represent Unicode characters longer than 16 bits. This was an act of desperation that had to be done. On the one hand, a character in a string containing a surrogate pair may occupy 2 or 4 bytes, thus losing the advantage of equal-length encoding. On the other hand, processing surrogate pairs requires additional code, which increases the complexity of programming and the difficulty of debugging.

For the above reasons, some programming languages propose different encoding schemes:

- Python 3 uses a flexible string representation where the length of characters stored depends on the largest Unicode code point in the string. For a string of all ASCII characters, each character occupies 1 byte; if the string contains characters outside the ASCII range, but all within the Basic Multilingual Plane (BMP), each character occupies 2 bytes ; If there are characters beyond the BMP in the string, each character occupies 4 bytes.
- The `string` type of Go language uses UTF-8 encoding internally. The Go language also provides the `rune` type, which is used to represent a single Unicode code point.
- Rust's str and String types use UTF-8 encoding internally. Rust also provides the char type, which represents a single Unicode code point.

It should be noted that the above discussions are all about the way strings are stored in programming languages, **which is a different issue from how strings are stored in files or transmitted over the network.** In file storage or network transmission, we generally encode strings in UTF-8 format to achieve optimal compatibility and space efficiency.

3.5. Summary

- Data structure can be classified from two perspectives of logical structure and physical structure. Logical structure describes the logical relationship between data elements, while physical structure describes how data is stored in computer memory.

- Common logical structures include linear, tree, and network. Usually we divide data structures into linear (arrays, linked lists, stacks, queues) and nonlinear (trees, graphs, heaps) according to the logical structure. Hash table implementations may contain both linear and non-linear structures.

- While the program is running, data is stored in the computer's memory. Each memory space has a corresponding memory address, and the program accesses data through these memory addresses.

- The physical structure is mainly divided into continuous space storage (array) and discrete space storage (linked list). All data structures are implemented by arrays, linked lists, or a combination of both.

- The basic data types in the computer include integer `byte`, `short`, `int`, `long`, floating point number `float`, `double`, character `char` and Boolean `boolean`. Their range of values ​​depends on the size of the footprint and the representation.

- Original code, inverse code, and complement code are three methods of encoding numbers in a computer, and they can be converted to each other. The highest bit of the original code of an integer is the sign bit, and the remaining bits are the value of the number.

- Integers are stored in a computer in two's complement form. Under the complement representation, the computer can treat the addition of positive numbers and negative numbers equally, and there is no need to design special hardware circuits for subtraction operations, and there is no ambiguity between positive and negative zeros.

- The encoding of floating point numbers consists of 1 sign bit, 8 exponent bits and 23 fraction bits. Due to the existence of exponent bits, the value range of floating-point numbers is much larger than that of integers, at the cost of sacrificing precision.

- ASCII code is the earliest English character set, with a length of 1 byte and a total of 127 characters.  The GBK character set is a commonly used Chinese character set, which contains more than 20,000 Chinese characters.  Unicode is committed to providing a complete character set standard, including characters from various languages ​​in the world, so as to solve the problem of garbled characters caused by inconsistent character encoding methods.

- UTF-8 is the most popular Unicode encoding method and is very versatile. It is a variable-length encoding method with good scalability and effectively improves the efficiency of storage space.  UTF-16 and UTF-32 are equal-length encoding methods. UTF-16 takes up less space than UTF-8 when encoding Chinese.  Programming languages ​​such as Java and C# use UTF-16 encoding by default.

3.5.1. Q & A

>**Why does a hash table contain both linear and non-linear data structures?**
>The bottom layer of the hash table is an array, and in order to resolve hash conflicts, we may use the "zipper method" (will be discussed in the subsequent hash table chapter). In the zipper method, each address (bucket) in the array points to a linked list; when the length of the linked list exceeds a certain threshold, it may be converted into a tree (usually a red-black tree). Therefore, hash tables may contain both linear (arrays, linked lists) and non-linear (trees) data structures.

>**Is the length of the `char` type 1 byte?**
>The length of the `char` type is determined by the encoding method used by the programming language. For example, Java, JS, TS, C# all use UTF-16 encoding (save Unicode code points), so the length of char type is 2 bytes.

4. Arrays and Linked Lists

>**Abstract**
>The world of data structures is like seeing a thick brick wall.
>
>The bricks of the array are neatly arranged, one by one close to each other. The bricks of the linked list are scattered everywhere, and the connected vines freely shuttle between the bricks.

4.1. Arrays¶

An "array" is a linear data structure that stores elements of the same type in contiguous memory space. We refer to the position of an element in the array as the "index" of that element. The following picture shows the main terms and concepts of arrays.

![Fig. 数组定义与存储方式](./algos/4.1.0.png)

4.1.1. Array common operations

1. Initializing the array

We can choose two initialization methods for arrays according to our needs: no initial value and provided initial value. Most programming languages ​​initialize array elements to $0$ when no initial value is specified.

```zig
// initializing the array
var arr = [_]i32{0} ** 5; // { 0, 0, 0, 0, 0 }
var nums = [_]i32{ 1, 3, 2, 5, 4 };
```

2. Accessing elements

Array elements are stored in contiguous memory space, which means that calculating the memory address of an array element is very easy. Given the memory address of the array (that is, the memory address of the first element) and the index of an element, we can use the following formula to calculate the memory address of the element, so as to directly access this element.

```none
# Element memory address = array memory address(first element memory address) + element length * element index
elementAddr = firtstElementAddr + elementLength * elementIndex
```

![Fig. 数组元素的内存地址计算](./algos/4.1.1.2.png)

Looking at the previous picture, we see that the first element of the array has an index of $0$, which seems counter-intuitive since counting from $1$ would be more natural. But from the perspective of the address calculation formula, the meaning of the index is essentially the offset of the memory address. The address offset of the first element is $0$, so its index is also reasonable.

Accessing elements in an array is very efficient, and we can randomly access any element in an array in $O(1)$ time.

```zig
// accessing a random element
fn randomAccess(nums: []i32) i32 {
    // randomly draw an integer in the interval [0, nums.len)
    var randomIndex = std.crypto.random.intRangeLessThan(usize, 0, nums.len);
    // get and return a random element
    var randomNum = nums[randomIndex];
    return randomNum;
}
```

3. Inserting elements

Array elements are "next to each other" in memory, with no space between them for any further data. As shown in the following picture, if you want to insert an element in the middle of the array, you need to move all the elements behind the element backward by one bit, and then assign the element to the index.

![图 4-3   数组插入元素示例 ](./algos/4.1.1.3.png)

It is worth noting that since the length of the array is fixed, inserting an element will definitely cause a "lost" element at the end of the array. We leave the solution to this problem for the list chapter.

```zig
// Insert element num at index of the array
fn insert(nums: []i32, num: i32, index: usize) void {
    // Move the index and all subsequent elements backward by one
    var i = nums.len - 1;
    while (i > index) : (i -= 1) {
        nums[i] = nums[i - 1];
    }
    // Assign num to the element at index

    nums[index] = num;
}
```

4. Deleting elements

Similarly, as shown in the following picture, if you want to delete the element at index i, you need to move all the elements after index i forward by one.

![图 4-4   数组删除元素示例 ](./algos/4.1.1.4.png)

Please note that after deleting the element, the original end element becomes "meaningless", so we don't need to modify it specially.

```zig
// delete the element at index
fn remove(nums: []i32, index: usize) void {
    // Move all elements after the index forward by one
    var i = index;
    while (i < nums.len - 1) : (i += 1) {
        nums[i] = nums[i + 1];
    }
}
```

In general, the insertion and deletion operations of arrays have the following disadvantages.

- **High time complexity**: The average time complexity of array insertion and deletion is $O(n)$, where $n$ is the length of the array.
- **Losing elements**: Since the length of the array is immutable, after inserting elements, elements that exceed the length of the array are lost.
- **Memory waste**: We can initialize a relatively long array and only use the first part, so that when inserting data, the missing elements at the end are "meaningless", but doing so will also cause a waste of part of the memory space.

5. Iterating over an array

In most programming languages, we can either traverse the array by index, or directly traverse to get each element in the array.

```zig
// iterating over an array
fn traverse(nums: []i32) void {
    var count: i32 = 0;
    // iterating over an array by index
    var i: i32 = 0;
    while (i < nums.len) : (i += 1) {
        count += 1;
    }
    count = 0;
    // iterating over an array directly
    for (nums) |_| {
        count += 1;
    }
}
```

6. Finding an element

Finding the specified element in the array requires traversing the array, and each round estimates whether the element value matches, and outputs the corresponding index if it matches.

Because arrays are linear data structures, the above lookup operations are called "linear lookups".

```zig
// finding the specified element in the array
fn find(nums: []i32, target: i32) i32 {
    for (nums, 0..) |num, i| {
        if (num == target) return @intCast(i);
    }
    return -1;
}
```

7. Expanding an array

In a complex system environment, it is difficult for the program to ensure that the memory space behind the array is available, so that the capacity of the array cannot be expanded safely. So in most programming languages, **the length of the array is immutable**.

If we want to expand the array, we need to re-create a larger array, and then copy the elements of the original array to the new array in turn. This is an $O(n)$ operation, which is very time-consuming when the array is large.'

```zig
// extending array length
fn extend(mem_allocator: std.mem.Allocator, nums: []i32, enlarge: usize) ![]i32 {
    // initializing an array with extended length
    var res = try mem_allocator.alloc(i32, nums.len + enlarge);
    @memset(res, 0);
    // copying all elements of the original array to the new array
    std.mem.copy(i32, res, nums);
    // returning the new expanded array
    return res;
}
```

4.1.2. Array advantages and limitations

Arrays are stored in contiguous memory space with elements of the same type. This practice contains a wealth of prior information that the system can exploit to optimize the operational efficiency of the data structure.

- **High space efficiency**: Arrays allocate contiguous blocks of memory for data without additional structural overhead.
- **Supports random access**: Arrays allow access to any element in $O(1)$ time.
- **Cache locality**: When an array element is accessed, the computer not only loads it, but also caches other data around it, thereby using the cache to speed up subsequent operations.

Continuous space storage is a double-edged sword, which has the following disadvantages.

- **Insertion and deletion are inefficient**: When there are many elements in the array, insertion and deletion operations need to move a large number of elements.
- **Immutable length**: The length of the array is fixed after initialization. To expand the array, all data needs to be copied to the new array, which is very expensive.
- **Space wastage**: If an array is allocated with a larger size than is actually needed, then the excess space is wasted.

4.1.3. Array typical application

Array is a basic and common data structure, which is frequently used in various algorithms and can also be used to implement various complex data structures.

- **Random access**: If we want to draw some samples randomly, we can store them in an array, generate a random sequence, and implement random sampling of samples according to the index.
- **Sorting and Searching**: Arrays are the most commonly used data structures for sorting and searching algorithms. For example, quick sort, merge sort, binary search, etc. are mainly performed on arrays.
- **Lookup table**: When we need to quickly find an element or need to find the corresponding relationship of an element, we can use an array as a lookup table. For example, if we have a mapping from a character to its ASCII code, the ASCII code value of the character can be used as an index, and the corresponding element is stored in the corresponding position in the array.
- **Machine learning**: Linear algebra operations between vectors, matrices, and tensors are widely used in neural networks, and these data are constructed in the form of arrays. Arrays are the most commonly used data structures in neural network programming.
- **Data structure implementation**: Arrays can be used to implement data structures such as stacks, queues, hash tables, heaps, and graphs. For example, an adjacency matrix is one of the common representations of graphs, which is essentially a two-dimensional array.

4.2. linked list

Memory space is a common resource of all programs. In a complex system operating environment, free memory space may be scattered all over the memory. We know that the memory space for storing arrays must be continuous, and when the array is very large, the memory may not be able to provide such a large continuous space. Compared with arrays, linked lists are more flexible and can be stored in non-contiguous memory spaces.

"Linked List" is a linear data structure, each element of which is a node object, each node is connected by a pointer, and the next node can be accessed from the current node through the pointer. Since the pointer records the memory address of the next node, there is no need to ensure the continuity of the memory address, so that each node can be scattered and stored in various parts of the memory.

![Fig. 链表定义与存储方式](./algos/4.2.0.png)

In the previous picture, the "Node" in the linked list contains two pieces of data, one is the node "Value", and the other is the "Pointer" pointing to the next node, or "Reference".

- The first node of a linked list is called the "head node" and the last node is called the "tail node".
- The tail node points to "empty", which is denoted as $null$, $nullptr$, and $None$ in Java, C++, and Python, respectively.
- In languages that support pointers, such as C, C++, Go, and Rust, the above "reference" should be replaced with "pointer".

As shown in the following code, the linked list node `ListNode` contains an additional reference (pointer) in addition to the value. Therefore, for the same amount of data, **a linked list takes up more memory space than an array**.

```zig
// linked list node class
pub fn ListNode(comptime T: type) type {
    return struct {
        const Self = @This();

        val: T = 0, // node value
        next: ?*Self = null, // a pointer to the next node

        // constructor
        pub fn init(self: *Self, x: i32) void {
            self.val = x;
            self.next = null;
        }
    };
}
```

4.2.1. Common operations for linked lists

1. initializing the linked list

Building a linked list is a two-step process, the first step is to initialize the individual node objects, and the second step is to build a reference pointing relationship. After initialization, we can start from the head node of the linked list and access all nodes sequentially by pointing to `next` by reference.

```zig
// initializing the linked list
// initializing the nodes
var n0 = inc.ListNode(i32){.val = 1};
var n1 = inc.ListNode(i32){.val = 3};
var n2 = inc.ListNode(i32){.val = 2};
var n3 = inc.ListNode(i32){.val = 5};
var n4 = inc.ListNode(i32){.val = 4};
// constructing references to
n0.next = &n1;
n1.next = &n2;
n2.next = &n3;
n3.next = &n4;
```

The array as a whole is a variable, for example, the array `nums` contains the elements `nums[0]` and `nums[1]`, etc., while a linked list is composed of multiple independent node objects. **We usually think of the head node as a synonym for a linked list**, for example, the linked list in the above code can be denoted as the linked list `n0`.

2. inserting a node

Inserting nodes in a linked list is very easy. As shown in the following picture, suppose we want to insert a new node `P` between two adjacent nodes `n0` and `n1`, **we only need to change the two node references (pointers)** with a time complexity of $O(1)$.

![图 4-6   链表插入节点示例](./algos/4.2.1.2.png)

```zig
// inserting node P after node n0 in the linked list
fn insert(n0: ?*inc.ListNode(i32), P: ?*inc.ListNode(i32)) void {
    var n1 = n0.?.next;
    P.?.next = n1;
    n0.?.next = P;
}
```

3. deleting a node

As shown in the following picture, it is also very convenient to delete nodes in the linked list, **just change the reference (pointer) of a node**.

Please note that although the node `P` still points to `n1` after the delete operation is completed, it is actually impossible to visit `P` by traversing the linked list, which means that `P` no longer belongs to the linked list.

![图 4-7   链表删除节点](./algos/4.2.1.3.png)

```zig
// deleting the first node after node n0 of the linked list
fn remove(n0: ?*inc.ListNode(i32)) void {
    if (n0.?.next == null) return;
    // n0 -> P -> n1
    var P = n0.?.next;
    var n1 = P.?.next;
    n0.?.next = n1;
}
```

4. accessing a node

Accessing nodes in a linked list is less efficient. As mentioned in the previous section, we can access any element in the array in $O(1)$ time. For the linked list it is not the case. The program needs to start from the head node and traverse backwards one by one until the target node is found. That is to say, to visit the $ith$ node of the linked list it needs to cycle $i-1$ rounds, and the time complexity is $O(n)$.

```zig
// accessing the node at index in the linked list
fn access(node: ?*inc.ListNode(i32), index: i32) ?*inc.ListNode(i32) {
    var head = node;
    var i: i32 = 0;
    while (i < index) : (i += 1) {
        head = head.?.next;
        if (head == null) return null;
    }
    return head;
}
```

5. finding a node

Traverse the linked list, find the node whose value is `target` in the linked list, and output the index of the node in the linked list. This process is also a linear search.

```zig
// finding the first node whose value is target in the linked lis
fn find(node: ?*inc.ListNode(i32), target: i32) i32 {
    var head = node;
    var index: i32 = 0;
    while (head != null) {
        if (head.?.val == target) return index;
        head = head.?.next;
        index += 1;
    }
    return -1;
}
```

4.2.2. Arrays vs Linked lists

The following table summarizes and compares the characteristics and operation efficiency of arrays and linked lists. Since they adopt two opposite storage strategies, various properties and operational efficiencies also present opposite characteristics.

||Array|Linked list|
|---|---|---|
|Storage mode|Continuous memory space|Discrete memory space|
|Cache locality|Friendly|Unfriendly|
|Capacity extension|Fixed length|Flexible expansion|
|Memory eficiency|Occupies less memory and wastes some space|Occupies more memory|
|Accessing an element|$O(1)$|$O(n)$|
|Adding an element|$O(n)$|$O(1)$|
|Deleting an element|$O(n)$|$O(1)$|

4.2.3. Common Linked List Types

As shown in the following picture, there are three common linked list types.

- **Singly linked list**: That is, the ordinary linked list introduced above. The nodes of the singly linked list contain two pieces of data, a value and a pointer (reference) to the next node. We call the first node the head node, and the last node the tail node, which points to an empty $None$.
- **Circular linked list**: If we make the tail node of the singly linked list point to the head node (that is, end to end), we get a circular linked list. In a circular linked list, any node can be regarded as the head node.
- **Doubly linked list**: Compared with a singly linked list, a doubly linked list records pointers (references) in both directions. The node definition of the doubly linked list contains pointers to both the successor node (next node) and the predecessor node (previous node). Compared with the singly linked list, the doubly linked list is more flexible and can traverse the linked list in two directions, but correspondingly requires more memory space.

```zig
// doubly linked list node class
pub fn ListNode(comptime T: type) type {
    return struct {
        const Self = @This();

        val: T = 0, // node value
        next: ?*Self = null, // pointer to successor node
        prev: ?*Self = null, // pointer to predecessor node

        // constructor
        pub fn init(self: *Self, x: i32) void {
            self.val = x;
            self.next = null;
            self.prev = null;
        }
    };
}
```

![Fig. 常见链表种类](./algos/4.2.3.png)

4.2.4. Typical application of linked list

Singly linked lists are commonly used to implement data structures such as stacks, queues, hash tables, and graphs.

- **Stack and queue**: When the insertion and deletion operations are performed at one end of the linked list, it shows the characteristics of first-in, last-out, corresponding to the stack; when the insertion operation is performed at one end of the linked list, and the deletion operation is performed at the other end of the linked list, it Show the characteristics of first-in first-out, corresponding to the queue.
- **Hash table**: The chain address method is one of the mainstream solutions for hash conflicts. In this solution, all conflicting elements will be placed in a linked list.
- **Graphs**: Adjacency lists are a common way to represent graphs, in which each vertex of the graph is associated with a linked list, and each element in the linked list represents the other vertices connected to that vertex.

Doubly linked lists are often used in scenarios where you need to quickly find the previous and next elements.

- **Advanced data structures**: For example, in red-black trees and B-trees, we need to know the parent node of a node, which can be achieved by saving a pointer to the parent node in the node, similar to a doubly linked list.
- **Browser History**: In a web browser, when the user clicks the forward or back button, the browser needs to know the previous and next web pages the user has visited. The nature of doubly linked lists makes this easy.
- **LRU algorithm**: In the cache elimination algorithm (LRU), we need to quickly find the least recently used data, and support the rapid addition and deletion of nodes. At this time, it is very appropriate to use a doubly linked list.

Circular linked lists are often used in scenarios that require periodic operations, such as resource scheduling of the operating system.

- **Time slice round-robin scheduling algorithm**: In the operating system, time slice round-robin scheduling algorithm is a common CPU scheduling algorithm, which needs to cycle a group of processes. Each process is given a time slice, and when the time slice is exhausted, the CPU will switch to the next process. This kind of circular operation can be realized by circular linked list.
- **Data buffer**: In the implementation of some data buffers, circular linked lists may also be used. For example, in audio and video players, the data stream may be divided into multiple buffer blocks and put into a circular linked list to achieve seamless playback.

4.3. the list

**The immutable length of the array makes it less useful**. In practice, we may not be able to determine in advance how much data needs to be stored, which makes the choice of array length difficult. If the length is too small, you need to expand the array frequently when adding data. If the length is too large, it will cause waste of memory space.

To solve this problem, a data structure called a "dynamic array" has emerged, that is, an array of variable length, also often referred to as a "List". The list is implemented based on arrays, inherits the advantages of arrays, and can be dynamically expanded during program operation. We are free to add elements to the list without worrying about exceeding the capacity limit.

4.3.1. List common operations

1. initializing the list.

Usually we use two initialization methods of "no initial value" and "with initial value".

```zig
// initializing the list
var list = std.ArrayList(i32).init(std.heap.page_allocator);
defer list.deinit();
try list.appendSlice(&[_]i32{ 1, 3, 2, 5, 4 });
```

2. accessing an element

Lists are arrays in nature, so elements can be accessed and updated in O(1) time, which is efficient.

```zig
// accessing an element
var num = list.items[1]; // accessing the element at index 1

// updating an element
list.items[1] = 0; // updating the element at index 1 to 0
```

3. inserting and deleting elements

In contrast to arrays, lists can add and remove elements freely. Adding elements at the end of the list has a time complexity of O(1), but inserting and deleting elements is still the same as an array with a time complexity of O(n).

```zig
// emptying the list
list.clearRetainingCapacity();

// tail adding an element
try list.append(1);
try list.append(3);
try list.append(2);
try list.append(5);
try list.append(4);

// inserting an element in the middle
try list.insert(3, 6); // inserting the number 3 at index 6

// deleting an element
_ = list.orderedRemove(3); // deleting the element at index 3
```

4. iterating over the list

Like arrays, lists can be traversed based on indexes or directly through elements.

```zig
// traversing the list by index
var count: i32 = 0;
var i: i32 = 0;
while (i < list.items.len) : (i += 1) {
    count += 1;
}

// traversing the list elements directly
count = 0;
for (list.items) |_| {
    count += 1;
}
```

5. concatenating two lists

Given a new list `list1` , we can concatenate that list to the end of the original list.

```zig
// concatenating two lists
var list1 = std.ArrayList(i32).init(std.heap.page_allocator);
defer list1.deinit();
try list1.appendSlice(&[_]i32{ 6, 8, 7, 10, 9 });
try list.insertSlice(list.items.len, list1.items); // joining list list1 after list
```

6. sorting a list

After sorting the list, we can use the "binary search" and "double pointer" algorithms that are often investigated in array algorithm problems.

```zig
// sorting a list
std.sort.sort(i32, list.items, {}, comptime std.sort.asc(i32));
```

4.3.2. list implementation

Many programming languages ​​provide built-in lists, such as Java, C++, Python, etc. Their implementation is relatively complicated, and the setting of each parameter is also very sophisticated, such as initial capacity, expansion multiple, etc. Interested readers can refer to the source code for learning.

In order to deepen the understanding of the working principle of the list, we try to implement a simplified version of the list, including the following three key designs.

- **Initial Capacity**: Select a reasonable initial capacity of the array. In this example, we choose 10 as the initial capacity.
- **Quantity record**: Declare a variable size to record the current number of elements in the list, and update it in real time as elements are inserted and deleted. According to this variable, we can locate the end of the list and determine whether expansion is required.
- **Expansion mechanism**: The capacity of the list may be exceeded when inserting elements, and the list needs to be expanded at this time. The expansion method is to create a larger array according to the expansion multiple, and move all elements of the current array to the new array in turn. In this example, we specify that the array be expanded by a factor of 2 each time.

```zig
// simple implementation of list class
fn MyList(comptime T: type) type {
    return struct {
        const Self = @This();

        nums: []T = undefined,                        // array (store list elements)
        numsCapacity: usize = 10,                     // list capacity
        numSize: usize = 0,                           // list length (i.e. current number of elements)
        extendRatio: usize = 2,                       // the multiple of each list expansion
        mem_arena: ?std.heap.ArenaAllocator = null,
        mem_allocator: std.mem.Allocator = undefined, // memory allocator

        // constructor (allocate memory + initializer list)
        pub fn init(self: *Self, allocator: std.mem.Allocator) !void {
            if (self.mem_arena == null) {
                self.mem_arena = std.heap.ArenaAllocator.init(allocator);
                self.mem_allocator = self.mem_arena.?.allocator();
            }
            self.nums = try self.mem_allocator.alloc(T, self.numsCapacity);
            @memset(self.nums, @as(T, 0));
        }

        // destructor (frees memory)
        pub fn deinit(self: *Self) void {
            if (self.mem_arena == null) return;
            self.mem_arena.?.deinit();
        }

        // get the length of the list (that is, the current number of elements)
        pub fn size(self: *Self) usize {
            return self.numSize;
        }

        // get list capacity
        pub fn capacity(self: *Self) usize {
            return self.numsCapacity;
        }

        // access element
        pub fn get(self: *Self, index: usize) T {
            // if the index is out of bounds, an exception will be thrown, the same below
            if (index < 0 or index >= self.size()) @panic("index out of bounds");
            return self.nums[index];
        }  

        // update element
        pub fn set(self: *Self, index: usize, num: T) void {
            // if the index is out of bounds, an exception will be thrown, the same below
            if (index < 0 or index >= self.size()) @panic("index out of bounds");
            self.nums[index] = num;
        }  

        // add elements at the end
        pub fn add(self: *Self, num: T) !void {
            // when the number of elements exceeds the capacity, the expansion mechanism is triggered
            if (self.size() == self.capacity()) try self.extendCapacity();
            self.nums[self.size()] = num;
            // update the number of elements
            self.numSize += 1;
        }  

        // insert element in the middle
        pub fn insert(self: *Self, index: usize, num: T) !void {
            if (index < 0 or index >= self.size()) @panic("index out of bounds");
            // when the number of elements exceeds the capacity, the expansion mechanism is triggered
            if (self.size() == self.capacity()) try self.extendCapacity();
            // mve the index index and the following elements backward by one bit
            var j = self.size() - 1;
            while (j >= index) : (j -= 1) {
                self.nums[j + 1] = self.nums[j];
            }
            self.nums[index] = num;
            // update the number of elements
            self.numSize += 1;
        }

        // delete element
        pub fn remove(self: *Self, index: usize) T {
            if (index < 0 or index >= self.size()) @panic("index out of bounds");
            var num = self.nums[index];
            // all elements after index i are moved forward one bit
            var j = index;
            while (j < self.size() - 1) : (j += 1) {
                self.nums[j] = self.nums[j + 1];
            }
            // update the number of elements
            self.numSize -= 1;
            // return the deleted element
            return num;
        }

        // list expansion
        pub fn extendCapacity(self: *Self) !void {
            // create a new array with length size * extendRatio, and copy the original array to the new array
            var newCapacity = self.capacity() * self.extendRatio;
            var extend = try self.mem_allocator.alloc(T, newCapacity);
            @memset(extend, @as(T, 0));
            // copy all elements of the original array to the new array
            std.mem.copy(T, extend, self.nums);
            self.nums = extend;
            // update list capacity
            self.numsCapacity = newCapacity;
        }

        // convert list to array
        pub fn toArray(self: *Self) ![]T {
            // only convert list elements within the valid length range
            var nums = try self.mem_allocator.alloc(T, self.size());
           @memset(nums, @as(T, 0));
            for (nums, 0..) |*num, i| {
                num.* = self.get(i);
            }
            return nums;
        }
    };
}
```

4.4. summary

- Arrays and linked lists are two basic data structures, which respectively represent the continuous space storage and discrete space storage methods of data in computer memory. The advantages and disadvantages of the two are complementary.
- Arrays support random access and occupy less memory; however, inserting and deleting elements is inefficient, and the length is immutable after initialization.
- The linked list achieves efficient node insertion and deletion by changing references (pointers), and can flexibly adjust the length; however, node access is inefficient and takes up more memory. Common linked list types include singly linked list, circular linked list, and doubly linked list.
- A dynamic array, also known as a list, is a data structure based on an array. It retains the advantages of arrays, while being flexible to adjust the length. The appearance of the list greatly improves the ease of use of the array, but may cause some memory space to be wasted.

4.4.1. Q & A

>**Does array storage on the stack and storage on the heap have any impact on time efficiency and space efficiency?**
>Stack memory allocation is automatically done by the compiler, while heap memory is allocated by the programmer in the code (note that the stack and heap here are not the same concept as the stack and heap in the data structure).
>
>1. The stack is not flexible, and the allocated memory size cannot be changed; the heap is relatively flexible, and memory can be allocated dynamically.
>2. The stack is a relatively small piece of memory, which is prone to insufficient memory; the heap memory is large, but because it is dynamically allocated, it is easy to fragment, and it is more difficult and costly to manage the heap memory.
>3. Accessing the stack is faster than accessing the heap, because the stack memory is small and friendly to the cache, and the heap frame is scattered in a large space, and there will be more cache misses.

>Why does the array emphasize the elements of the same type, but does not emphasize the same type in the linked list?
>The linked list is composed of nodes, and the nodes are connected by references (pointers). Each node can store different types of data, such as int, double, string, object, etc.
>
>In contrast, array elements must be of the same type, so that the corresponding element position can be obtained by calculating the offset. For example, if the array contains both int and long types, and a single element occupies 4 bytes and 8 bytes respectively, then the following formula cannot be used to calculate the offset at this time, because the array contains two types of `elementLength`.

>`// element memory address = array memory address + element length * element index`
>`elementAddr = firtstElementAddr + elementLength * elementIndex`

>**After deleting a node, do I need to set `P.next` to $None$?**
>It is also possible to not modify `P.next`. From the point of view of the linked list, `P` has not been encountered from the traversal from the head node to the tail node. This means that the node `P` has been deleted from the linked list, and no matter where the node `P` points to, it will not affect the linked list.
>
>From the perspective of garbage collection, for Java, Python, Go and other languages with automatic garbage collection, whether the node `P` is recycled depends on whether there is still a reference to it, rather than the value of `P.next`. In C, C++ and other languages, we need to manually release the node memory.

>**The time complexity of inserting and deleting operations in a linked list is $O(1)$. But $O(n)$ is required to find elements before addition and deletion, so why is the time complexity not $O(n)$?**
>If it is to find the element first and then delete the element, it is indeed O$(n)$. However, the advantages of $O(1)$ addition and deletion of linked lists can be realized in other applications. For example, a bidirectional queue is suitable for implementation using a linked list. We maintain a pointer variable that always points to the head node and the tail node. Each insertion and deletion operation is $O(1)$.

>**In the picture "Linked List Definition and Storage Method", does the light blue storage node pointer occupy a memory address? Or is it half and half of the node value?**
>The text is only a schematic diagram, only a qualitative representation. Quantitative words need to be analyzed according to specific situations:
>
>- The space occupied by different types of node values is different, such as `int`, `long`, `double`, or an instance of a class, etc.
>- The size of the memory space occupied by pointer variables depends on the operating system and compilation environment used, mostly 8 bytes or 4 bytes.

>**Is adding an element at the end of the list $O(1)$ all the time?**
>If the length of the list is exceeded when adding elements, the list needs to be expanded before adding. The system will apply for a new piece of memory and move all the elements of the original list over. At this time, the time complexity will be $O(n)$.

>**"The appearance of the list greatly improves the practicability of the array, but the side effect is that some memory space will be wasted." Does the space waste here refer to the memory occupied by additional variables such as capacity, length, and expansion multiple?**
>The waste of space here mainly has two meanings: on the one hand, the list will set an initial length, and we don't necessarily need to use so much. On the other hand, in order to prevent frequent expansion, expansion is generally multiplied by a factor, such as $x1.5$. As a result, there are also a lot of empty slots, and we usually can't completely fill them.

>**After initializing `n = [1, 2, 3]` in Python, the addresses of these three elements are connected, but initializing `m = [2, 1, 3]` will find that the ids of each of their elements are not consecutive, and are the same as in n respectively. The addresses of these elements are not consecutive, so is m still an array?**
>If the list elements are replaced with linked list nodes `n = [n1, n2, n3, n4, n5]`, usually these five node objects are also scattered and stored in memory. However, given a list index, we can still get the memory address of the node in $O(1)$ time to access the corresponding node. This is because the references to the nodes are stored in the array, not the nodes themselves.
>
>Unlike many languages, numbers are also wrapped as objects in Python, and what is stored in the list is not the number itself, but a reference to the number. Therefore, we will find that the same numbers in the two arrays have the same id, and the memory addresses of these numbers do not need to be consecutive.

>**The std::list in C++ STL has implemented a double-linked list, but it seems that some algorithm books do not use this directly, is there any limitation?**
>On the one hand, we tend to prefer to use arrays to implement algorithms, and only use linked lists when necessary, for two main reasons.
>
>- Space overhead: Since each element requires two additional pointers (one for the previous element and one for the latter), `std::list` usually takes up more space than `std::vector`.
>- Caching is not friendly: `std::list` has low utilization of the cache because data is not stored contiguously. In general, `std::vector` performs better.
>
>On the other hand, the cases where a linked list is necessary are mainly binary trees and graphs. Stacks and queues tend to use `stack` and `queue` provided by programming languages instead of linked lists.

5. Stacks and Queues

>**Abstract**
>A stack is like stacking cats, and a queue is like lining up cats.
>
>The two represent the logical relationship of first-in-first-out and first-in-first-out respectively.

5.1. the stack

A stack is a linear data structure that follows a first-in, last-out logic.

We can compare the stack to a stack of plates on the table. If you need to take out the bottom plate, you need to take out the top plates in turn. We replace the plate with various types of elements (such as integers, characters, objects, etc.), and we get the stack data structure.

As shown in the following picture, we refer to the top of the stacked elements as the "top of the stack" and the bottom as the "bottom of the stack". The operation of adding an element to the top of the stack is called "pushing", and the operation of deleting the top element of the stack is called "popping".

![Fig. 栈的先入后出规则](./algos/5.1.0.png)

5.1.1. Stack common operations

The common operations of the stack are shown in the following table, and the specific method name needs to be determined according to the programming language used. Here, we take the common names of `push()`, `pop()`, `peek()` as examples.

|Method|Description|Time complexity|
|---|---|---|
|push()|Elements are pushed onto the stack(addedtothetopofthestack)|$O(1)$|
|pop()|The top element of the stack is popped|$O(1)$|
|peek()|Access the top element of the stack|$O(1)$|

Usually, we can directly use the built-in stack class of the programming language. However, some languages may not specifically provide a stack class. At this time, we can use the "array" or "linked list" of the language as a stack, and ignore operations that have nothing to do with the stack.

```zig
```

5.1.2. Implementation of the stack

In order to gain a deeper understanding of the operating mechanism of the stack, let's try to implement a stack class by ourselves.

The stack follows the principle of first in, last out, so we can only add or remove elements at the top of the stack. However, both arrays and linked lists can add and remove elements at arbitrary positions, so a stack can be viewed as a sort of restricted array or linked list. In other words, we can "mask" some irrelevant operations of the array or linked list, so that the logic of its external appearance conforms to the characteristics of the stack.

1. implementation based on linked list

When using a linked list to implement a stack, we can regard the head node of the linked list as the top of the stack and the tail node as the bottom of the stack.

for the push operation, we only need to insert elements into the head of the linked list. This node insertion method is called "head insertion method". For the stack operation, just delete the head node from the linked list.

![LinkedListStack](./algos/5.1.2-1.1png) ![push()](./algos/5.1.2-1.2.png) ![pop()](./algos/5.1.2-1.3.png)

The following is a sample code for implementing a stack based on a linked list.

```zig
// stack based on linked list
fn LinkedListStack(comptime T: type) type {
    return struct {
        const Self = @This();

        stack_top: ?*inc.ListNode(T) = null,             // using the head node as the top of the stack
        stk_size: usize = 0,                             // stack length
        mem_arena: ?std.heap.ArenaAllocator = null,
        mem_allocator: std.mem.Allocator = undefined,    // memory allocator

        // constructor (allocates memory + initializes stack)
        pub fn init(self: *Self, allocator: std.mem.Allocator) !void {
            if (self.mem_arena == null) {
                self.mem_arena = std.heap.ArenaAllocator.init(allocator);
                self.mem_allocator = self.mem_arena.?.allocator();
            }
            self.stack_top = null;
            self.stk_size = 0;
        }

        // destructor (frees memory)
        pub fn deinit(self: *Self) void {
            if (self.mem_arena == null) return;
            self.mem_arena.?.deinit();
        }

        // gets the length of the stack
        pub fn size(self: *Self) usize {
            return self.stk_size;
        }

        // checks if the stack is empty
        pub fn isEmpty(self: *Self) bool {
            return self.size() == 0;
        }

        // accesses the top element of the stack
        pub fn peek(self: *Self) T {
            if (self.size() == 0) @panic("栈为空");
            return self.stack_top.?.val;
        }  

        // stacks
        pub fn push(self: *Self, num: T) !void {
            var node = try self.mem_allocator.create(inc.ListNode(T));
            node.init(num);
            node.next = self.stack_top;
            self.stack_top = node;
            self.stk_size += 1;
        } 

        // pops out
        pub fn pop(self: *Self) T {
            var num = self.peek();
            self.stack_top = self.stack_top.?.next;
            self.stk_size -= 1;
            return num;
        } 

        // converts stack to array
        pub fn toArray(self: *Self) ![]T {
            var node = self.stack_top;
            var res = try self.mem_allocator.alloc(T, self.size());
            @memset(res, @as(T, 0));
            var i: usize = 0;
            while (i < res.len) : (i += 1) {
                res[res.len - i - 1] = node.?.val;
                node = node.?.next;
            }
            return res;
        }
    };
}
```

2. Array-based implementation

When using an array to implement a stack, we can use the end of the array as the top of the stack. As shown in the following picture, the operations of pushing and popping correspond to adding and deleting elements at the end of the array respectively, and the time complexity is $O(1)$.

![ArrayStack](./algos/5.1.2-1.1png) ![push()](./algos/5.1.2-1.2.png) ![pop()](./algos/5.1.2-1.3.png)

Since the elements pushed onto the stack may increase continuously, we can use dynamic arrays, so that we don't need to deal with the problem of array expansion by ourselves. Below is the sample code.

```zig
// array based stack
fn ArrayStack(comptime T: type) type {
    return struct {
        const Self = @This();

        stack: ?std.ArrayList(T) = null,     

        // constructor (allocates memory + initializes stack)
        pub fn init(self: *Self, allocator: std.mem.Allocator) void {
            if (self.stack == null) {
                self.stack = std.ArrayList(T).init(allocator);
            }
        }

        // destructor (frees memory)
        pub fn deinit(self: *Self) void {
            if (self.stack == null) return;
            self.stack.?.deinit();
        }

        // gets the length of the stack
        pub fn size(self: *Self) usize {
            return self.stack.?.items.len;
        }

        // checks if the stack is empty
        pub fn isEmpty(self: *Self) bool {
            return self.size() == 0;
        }

        // access the top element of the stack
        pub fn peek(self: *Self) T {
            if (self.isEmpty()) @panic("栈为空");
            return self.stack.?.items[self.size() - 1];
        }  

        // stacks
        pub fn push(self: *Self, num: T) !void {
            try self.stack.?.append(num);
        } 

        // pops out
        pub fn pop(self: *Self) T {
            var num = self.stack.?.pop();
            return num;
        } 

        // returns ArrayList
        pub fn toList(self: *Self) std.ArrayList(T) {
            return self.stack.?;
        }
    };
}
```

5.1.3. Comparison of two implementations

**Supported operations**

Both implementations support the operations in the stack definition. The array implementation additionally supports random access, but this is outside the scope of the stack definition, so it is generally not used.

**Time efficiency**

In the array-based implementation, stacking and popping operations are performed in pre-allocated continuous memory, which has good cache locality, so the efficiency is high. However, if the capacity of the array is exceeded when pushing to the stack, the expansion mechanism will be triggered, causing the time complexity of the stack operation to become $O(n)$.

In the implementation of the linked list, the expansion of the linked list is very flexible, and there is no problem of the above-mentioned reduction in efficiency when the array is expanded. However, the push operation needs to initialize the node object and modify the pointer, so the efficiency is relatively low. However, if the stacked element itself is a node object, the initialization step can be omitted, thereby improving efficiency.

To sum up, when the elements of the push and pop operations are basic data types (such as `int`, `double`), we can draw the following conclusions:

- The stack implemented based on arrays will be less efficient when triggering expansion, but since expansion is a low-frequency operation, the average efficiency is higher.
- The stack implemented based on the linked list can provide more stable efficiency performance.

**Space efficiency**

When a list is initialized, it is allocated an "initial capacity" that may be larger than actually needed. Moreover, the expansion mechanism is usually based on a specific ratio (such as 2 times), and the expanded capacity may also exceed the actual demand. Therefore, **the stack implemented based on the array may cause a certain waste of space**.

However, since the linked list nodes need additional storage for the pointers, **the space occupied by the linked list nodes is relatively large**.

In summary, we cannot simply determine which implementation is more memory-efficient, and we need to analyze specific situations.

5.1.4. Stack typical application

- **Back and Forward in the browser, Undo and Redo in software applications**. Whenever we open a new webpage, the browser will push the execution of the previous webpage onto the stack, so that we can return to the previous page through the "back" operation. The back operation is actually performing a stack pop. If you want to support back and forward at the same time, you need two stacks to work together.
- **Program memory management**. Every time a function is called, the system will add a stack frame to the top of the stack to record the context information of the function. In a recursive function, the recursive downward phase will continuously perform stack operations, while the upward traceback phase will perform pop operations.

5.2. queue

"Queue" is a linear data structure that follows the first-in-first-out rule. As the name suggests, the queue simulates the phenomenon of queuing, that is, newcomers continue to join the tail of the queue, while those at the head of the queue leave one by one.

As shown in the following picture, we call the head of the queue the "head of the queue", the tail the "tail of the queue", the operation of adding elements to the tail of the queue is called "enqueuing", and the operation of deleting elements at the head of the queue is called "dequeuing".

![Fig. 队列的先入先出规则](./algos/5.2.0.png)

5.2.1. Queue Common Operations

Common operations on queues are shown in the following table. It is important to note that method names may vary in different programming languages. We use the same method of naming here as we did for the stack.

|Method|Description|Time complexity|
|---|---|---|
|push()|Elements are added to the end of the queue|$O(1)$|
|pop()|The first element of the line is dequeued|$O(1)$|
|peek()|Access the first element|$O(1)$|

We can directly use the ready-made queue class in the programming language.

```zig
```

5.2.2. queue implementation

To implement a queue, we need a data structure that can add elements at one end and remove elements at the other end. Therefore, both linked lists and arrays can be used to implement queues.

1. Implementation based on linked list

As shown in the following picture, we can regard the "head node" and "tail node" of the linked list as the front and end of the line respectively, and stipulate that only nodes can be added at the end of the line, and nodes can only be deleted at the front of the line.

![LinkedListQueue](./algos/5.2.2.1-1.png) ![push()](./algos/5.2.2.1-2.png) ![pop()](./algos/5.2.2.1-3.png)

The following is a sample code to implement a queue with a linked list.

```zig
// queue based on linked list
fn LinkedListQueue(comptime T: type) type {
    return struct {
        const Self = @This();

        front: ?*inc.ListNode(T) = null,                // head node front
        rear: ?*inc.ListNode(T) = null,                 // tail node rear
        que_size: usize = 0,                            // queue length
        mem_arena: ?std.heap.ArenaAllocator = null,
        mem_allocator: std.mem.Allocator = undefined,   // memory allocator

        // constructor (allocates memory + initializes queue)
        pub fn init(self: *Self, allocator: std.mem.Allocator) !void {
            if (self.mem_arena == null) {
                self.mem_arena = std.heap.ArenaAllocator.init(allocator);
                self.mem_allocator = self.mem_arena.?.allocator();
            }
            self.front = null;
            self.rear = null;
            self.que_size = 0;
        }

        // destructor (frees memory)
        pub fn deinit(self: *Self) void {
            if (self.mem_arena == null) return;
            self.mem_arena.?.deinit();
        }

        // gets the length of the queue
        pub fn size(self: *Self) usize {
            return self.que_size;
        }

        // checks if the queue is empty
        pub fn isEmpty(self: *Self) bool {
            return self.size() == 0;
        }

        // accesses the first element
        pub fn peek(self: *Self) T {
            if (self.size() == 0) @panic("队列为空");
            return self.front.?.val;
        }  

        // enqueues
        pub fn push(self: *Self, num: T) !void {
            // adds num after the tail node
            var node = try self.mem_allocator.create(inc.ListNode(T));
            node.init(num);
            // if the queue is empty, makes the head and tail nodes both point to this node
            if (self.front == null) {
                self.front = node;
                self.rear = node;
            // if the queue is not empty, adds the node after the tail node
            } else {
                self.rear.?.next = node;
                self.rear = node;
            }
            self.que_size += 1;
        } 

        // dequeues
        pub fn pop(self: *Self) T {
            var num = self.peek();
            // deletes head node
            self.front = self.front.?.next;
            self.que_size -= 1;
            return num;
        } 

        // converts linked list to array
        pub fn toArray(self: *Self) ![]T {
            var node = self.front;
            var res = try self.mem_allocator.alloc(T, self.size());
            @memset(res, @as(T, 0));
            var i: usize = 0;
            while (i < res.len) : (i += 1) {
                res[i] = node.?.val;
                node = node.?.next;
            }
            return res;
        }
    };
}
```

2. Array-based implementation

Since the time complexity of deleting the first element of the array is $O(n)$, this will result in low efficiency of the dequeue operation. However, we can avoid this problem with the following clever method.

We can use a variable `front` to point to the index of the first element of the queue, and maintain a variable `queSize` to record the queue length. Define `rear = front + queSize`, the `rear` calculated by this formula points to the next position after the element at the end of the queue.

Based on this design, **the effective range of elements contained in the array is `[front, rear - 1]`**, and the implementation methods of various operations are shown in the following picture.

- For enqueue operations: assign the input element to the `rear` index and increase `queSize` by 1.
- For dequeue operations: simply increase `front` by 1 and decrease `queSize` by 1.

It can be seen that both the enqueue and dequeue operations only need to be performed once, and the time complexity is $O(1)$.

![ArrayQueue](./algos/5.2.2.2-1.png) ![push()](./algos/5.2.2.2-2.png) ![pop()](./algos/5.2.2.2-3.png)

You may find a problem: both `front` and `rear` are moving to the right during the process of enqueuing and dequeueing, and **when they reach the end of the array, they cannot continue to move**. To solve this problem, we can think of the array as a "circular array" connected end to end.

For circular arrays, we need to let `front` or `rear` directly return to the head of the array to continue traversing when it crosses the end of the array. This periodic law can be realized by "remainder operation", the code is as follows.

```zig
// queue based on circular array
fn ArrayQueue(comptime T: type) type {
    return struct {
        const Self = @This();

        nums: []T = undefined,                          // array to store queue elements
        cap: usize = 0,                                 // queue capacity
        front: usize = 0,                               // head pointer, pointing to the head element of the queue
        queSize: usize = 0,                             // tail pointer, pointing to the end of the queue + 1
        mem_arena: ?std.heap.ArenaAllocator = null,
        mem_allocator: std.mem.Allocator = undefined,   // memory allocator

        // constructor (allocates memory + initializes array)
        pub fn init(self: *Self, allocator: std.mem.Allocator, cap: usize) !void {
            if (self.mem_arena == null) {
                self.mem_arena = std.heap.ArenaAllocator.init(allocator);
                self.mem_allocator = self.mem_arena.?.allocator();
            }
            self.cap = cap;
            self.nums = try self.mem_allocator.alloc(T, self.cap);
            @memset(self.nums, @as(T, 0));
        }

        // destructor (frees memory)
        pub fn deinit(self: *Self) void {
            if (self.mem_arena == null) return;
            self.mem_arena.?.deinit();
        }

        // gets the capacity of the queue
        pub fn capacity(self: *Self) usize {
            return self.cap;
        }

        // gets the length of the queue
        pub fn size(self: *Self) usize {
            return self.queSize;
        }

        // checks if the queue is empty
        pub fn isEmpty(self: *Self) bool {
            return self.queSize == 0;
        }

        // enqueues
        pub fn push(self: *Self, num: T) !void {
            if (self.size() == self.capacity()) {
                std.debug.print("queue is full\n", .{});
                return;
            }
            // calculates the tail pointer, pointing to the tail index + 1
            // through the remainder operation, rear returns to the start after crossing the end of the array
            var rear = (self.front + self.queSize) % self.capacity();
            // adds num after the tail node
            self.nums[rear] = num;
            self.queSize += 1;
        } 

        // dequeues
        pub fn pop(self: *Self) T {
            var num = self.peek();
            // the head pointer moves backward one bit,
            // and returns to the start of the array if it crosses the tail
            self.front = (self.front + 1) % self.capacity();
            self.queSize -= 1;
            return num;
        } 

        // accesses the first element
        pub fn peek(self: *Self) T {
            if (self.isEmpty()) @panic("queue is empty");
            return self.nums[self.front];
        } 

        // returns array
        pub fn toArray(self: *Self) ![]T {
            // only converts list elements within the valid length range
            var res = try self.mem_allocator.alloc(T, self.size());
            @memset(res, @as(T, 0));
            var i: usize = 0;
            var j: usize = self.front;
            while (i < self.size()) : ({ i += 1; j += 1; }) {
                res[i] = self.nums[j % self.capacity()];
            }
            return res;
        }
    };
}
```

The queue implemented above still has the limitation that its length is immutable. However, this problem is not difficult to solve. We can replace the array with a dynamic array to introduce an expansion mechanism. Interested students can try to realize it by themselves.

The comparison conclusion of the two implementations is consistent with that of the stack, and will not be repeated here.

5.2.3. Queue typical application

- **Taobao order**. After a shopper places an order, the order is added to a queue, and the system then processes the orders in the queue in sequence. During Double 11, a large number of orders will be generated in a short period of time, and high concurrency has become a problem that engineers need to focus on.
- **Various to-do items**. Any scenario that needs to implement the "first come, first served" function, such as the task queue of the printer, the meal queue of the restaurant, etc. Queues can effectively maintain processing order in these scenarios.

5.3. bidirectional queue

In a queue, we can only remove elements from the head or add elements to the tail. As shown in the folowing picture, a "bidirectional queue dequeue" provides more flexibility, allowing the addition or removal of elements at the head and tail.

![Fig. 双向队列的操作](./algos/5.3.0.png)

5.3.1. Common operations on bidirectional queues

The common operations of the bidirectional queue are shown in the table below, and the specific method name needs to be determined according to the programming language used.

|Method|Description|Time complexity|
|---|---|---|
|pushFirst()|Add element to the head of the queue|$O(1)$|
|pushLast()|Add an element to the end of the queue|$O(1)$|
|popFirst()|remove the first element|$O(1)$|
|popLast()|delete tail element|$O(1)$|
|peekFirst()|Access the first element|$O(1)$|
|peekLast()|Access the tail element|$O(1)$|

Similarly, we can directly use the bidirectional queue class implemented in the programming language.

```zig
```

5.3.2. bidirectional queue implementation *

The implementation of a bidirectional queue is similar to a queue, and a linked list or an array can be selected as the underlying data structure.

1. Implementation based on doubly linked list

Looking back at the previous section, we use an ordinary one-way linked list to implement the queue, because it can easily delete the head node (corresponding to the dequeue operation) and add a new node after the tail node (corresponding to the enqueue operation).

For a bidirectional queue, both the head and the tail can perform enqueue and dequeue operations. In other words, bidirectional queues need to implement operations in another symmetric direction. For this reason, we use "doubly linked list" as the underlying data structure of the bidirectional queue.

We regard the head node and tail node of the doubly linked list as the head and tail of the bidirectional queue, and at the same time realize the function of adding and deleting nodes at both ends.

![LinkedListDeque](./algos/5.3.2.1-1.png) ![pushLast()](./algos/5.3.2.1-2.png) ![pushFirst()](./algos/5.3.2.1-3.png) ![popLast()](./algos/5.3.2.1-4.png) ![popFirst()](./algos/5.3.2.1-5.png)

The implementation code is shown below.

```zig
// doubly linked list node
fn ListNode(comptime T: type) type {
    return struct {
        const Self = @This();

        val: T = undefined,     // node value
        next: ?*Self = null,    // successor node pointer
        prev: ?*Self = null,    // predecessor node pointer

        // Initialize a list node with specific value
        pub fn init(self: *Self, x: i32) void {
            self.val = x;
            self.next = null;
            self.prev = null;
        }
    };
}

// a bidirectional queue based on a doubly linked list
fn LinkedListDeque(comptime T: type) type {
    return struct {
        const Self = @This();

        front: ?*ListNode(T) = null,                    // head node front
        rear: ?*ListNode(T) = null,                     // tail node rear
        que_size: usize = 0,                            // the length of the bidirectional queue
        mem_arena: ?std.heap.ArenaAllocator = null,
        mem_allocator: std.mem.Allocator = undefined,   // memory allocator

        // constructor (allocates memory + initializes queue)
        pub fn init(self: *Self, allocator: std.mem.Allocator) !void {
            if (self.mem_arena == null) {
                self.mem_arena = std.heap.ArenaAllocator.init(allocator);
                self.mem_allocator = self.mem_arena.?.allocator();
            }
            self.front = null;
            self.rear = null;
            self.que_size = 0;
        }

        // destructor (frees memory)
        pub fn deinit(self: *Self) void {
            if (self.mem_arena == null) return;
            self.mem_arena.?.deinit();
        }

        // gets the length of the bidirectional queue
        pub fn size(self: *Self) usize {
            return self.que_size;
        }

        // determines whether the bidirectional queue is empty
        pub fn isEmpty(self: *Self) bool {
            return self.size() == 0;
        }

        // enqueue operation
        pub fn push(self: *Self, num: T, is_front: bool) !void {
            var node = try self.mem_allocator.create(ListNode(T));
            node.init(num);
            // if the linked list is empty, make front and rear point to node
            if (self.isEmpty()) {
                self.front = node;
                self.rear = node;
            // head enqueue operation
            } else if (is_front) {
                // adds node to the head of the linked list
                self.front.?.prev = node;
                node.next = self.front;
                self.front = node;  // updates head node
            // tail enqueue operation
            } else {
                // adds node to the end of the linked list
                self.rear.?.next = node;
                node.prev = self.rear;
                self.rear = node;   // updates tail node
            }
            self.que_size += 1;      // updates queue length
        } 

        // front of line
        pub fn pushFirst(self: *Self, num: T) !void {
            try self.push(num, true);
        } 

        // end of line
        pub fn pushLast(self: *Self, num: T) !void {
            try self.push(num, false);
        } 

        // dequeue operation
        pub fn pop(self: *Self, is_front: bool) T {
            if (self.isEmpty()) @panic("double queue is empty");
            var val: T = undefined;
            // dequeue operation at the head of the queue
            if (is_front) {
                val = self.front.?.val;     // temporary header node value
                // deletes head node
                var fNext = self.front.?.next;
                if (fNext != null) {
                    fNext.?.prev = null;
                    self.front.?.next = null;
                }
                self.front = fNext;         // updates head node
            // dequeue operation at the end of the queue
            } else {
                val = self.rear.?.val;      // staging the tail node value
                // deletes tail node
                var rPrev = self.rear.?.prev;
                if (rPrev != null) {
                    rPrev.?.next = null;
                    self.rear.?.prev = null;
                }
                self.rear = rPrev;          // updates tail node
            }
            self.que_size -= 1;             // updates queue length
            return val;
        } 

        // line head out
        pub fn popFirst(self: *Self) T {
            return self.pop(true);
        } 

        // dequeues at the end of the line
        pub fn popLast(self: *Self) T {
            return self.pop(false);
        } 

        // accesses the first element
        pub fn peekFirst(self: *Self) T {
            if (self.isEmpty()) @panic("double queue is empty");
            return self.front.?.val;
        }  

        // accesses the tail element
        pub fn peekLast(self: *Self) T {
            if (self.isEmpty()) @panic("double queue is empty");
            return self.rear.?.val;
        }

        // returns array for printingv
        pub fn toArray(self: *Self) ![]T {
            var node = self.front;
            var res = try self.mem_allocator.alloc(T, self.size());
            @memset(res, @as(T, 0));
            var i: usize = 0;
            while (i < res.len) : (i += 1) {
                res[i] = node.?.val;
                node = node.?.next;
            }
            return res;
        }
    };
}
```

2. Array-based implementation

As shown in the following pcture, similar to implementing a queue based on an array, we can also use a circular array to implement a bidirectional queue.

![ArrayDeque](./algos/5.3.2.2-1.png) ![pushLast()](./algos/5.3.2.2-2.png) ![pushFirst()](./algos/5.3.2.2-3.png) ![popLast()](./algos/5.3.2.2-4.png) ![popFirst()](./algos/5.3.2.2-5.png)

On the basis of the implementation of the queue, it is only necessary to add the methods of "enqueue at the head of the queue" and "dequeue at the end of the queue".

```zig
[class]{ArrayDeque}-[func]{}
```

5.3.3. bidirectional queue applications

The bidirectional queue has both the logic of the stack and the queue, **so it can realize all application scenarios of the two, while providing a higher degree of freedom**.

We know that the "undo" function of software is usually implemented using a stack: the system `push`es each change operation to the stack, and then implements undo through `pop`. However, considering the limitation of system resources, the software usually limits the number of undo steps (for example, only $50$ steps are allowed to be saved). When the length of the stack exceeds $50$, the software needs to perform a delete operation at the bottom of the stack (that is, the head of the queue). **But the stack cannot realize this function, so a bidirectional queue needs to be used instead of the stack**. Please note that the core logic of "undo" still follows the first-in, first-out principle of the stack, but the bidirectional queue can implement some additional logic more flexibly.

5.4. summary

- A stack is a data structure that follows the principle of first-in, first-out, and can be implemented by an array or a linked list.
- From the perspective of time efficiency, the array implementation of the stack has a higher average efficiency, but in the process of expansion, the time complexity of a single push operation will be reduced to $O(n)$. In contrast, the stack based on linked list has more stable efficiency performance.
- In terms of space efficiency, the array implementation of the stack may lead to a certain degree of space waste. But it should be noted that the memory space occupied by linked list nodes is larger than that of array elements.
- A queue is a data structure that follows the first-in-first-out principle, and can also be implemented by an array or a linked list. In the comparison of time efficiency and space efficiency, the conclusion of the queue is similar to the conclusion of the aforementioned stack.
- A bidirectional queue is a queue with a higher degree of freedom, which allows adding and removing elements at both ends.

5.4.1. Q & A

>**Is the forward and backward of the browser implemented as a doubly linked list?**
>The forward and backward function of the browser is essentially the embodiment of the "stack". When the user visits a new page, the page is added to the top of the stack; when the user clicks the back button, the page is popped from the top of the stack. Using a bidirectional queue can facilitate some additional operations, which are mentioned in the bidirectional queue section.

>**After popping the stack, do I need to release the memory of the popped node?**
>If you still need to use the pop-up node later, you don't need to release the memory. Languages such as `Java` and `Python` have automatic garbage collection mechanisms, so there is no need to manually release memory if it is not needed later; in `C` and `C++`, memory needs to be manually released.

>**A bidirectional queue is like two stacks spliced together. What is its purpose?**
>A bidirectional queue is like a combination of a stack and a queue, or two stacks put together. It represents the logic of stack + queue, so all applications of stack and queue can be realized, and it is more flexible.

6. hash table

>**Abstract**
>In the computer world, a hash table is like an intelligent librarian.
>
>He knows how to calculate the call number so that he can quickly find the target book.

6.1. hash table

"Hash Table", realizes efficient element query by establishing a mapping between `key` and `value`. Specifically, if we input a `key` into the hash table, the corresponding `value` can be obtained in $O(1)$ time.

As shown in the following picture, given $n$ students, each student has two data items of "name" and "student number". If we want to implement the query function of "enter a student number and return the corresponding name", we can use a hash table to achieve it.

![Fig. 哈希表的抽象表示](./algos/6.1.0.png)

In addition to hash tables, arrays and linked lists can also implement query functions, and their efficiency comparisons are shown in the following table.

- **Adding elements**: Just add elements to the end of the array (linked list), using $O(1)$ time.
- **Querying elements**: Since the array (linked list) is out of order, it is necessary to traverse all the elements in it, using $O(n)$ time.
- **Deleting elements**: You need to query the elements first, and then delete them from the array, using $O(n)$ time.

||Array|Linked List|Hash Table|
|---|---|---|---|
|find element|$O(n)$|$O(n)$|$O(1)$|
|add element|$O(1)$|$O(1)$|$O(1)$|
|delete element|$O(n)$|$O(n)$|$O(1)$|

It is observed that **the time complexity of adding, deleting, checking and modifying in the hash table is O(1)**, which is very efficient.

6.1.1. Hash table common operations

Common operations of hash tables include: initialization, query operations, adding key-value pairs, and deleting key-value pairs.

```zig
```

There are three common traversal methods for hash tables: traversing key-value pairs, traversing keys, and traversing values.

```zig
```

6.1.2. Simple implementation of hash table

Let's consider the simplest case first, **using only an array to implement a hash table**. In the hash table, we call each slot in the array a "bucket", and each bucket can store a key-value pair. Therefore, the query operation is to find the bucket corresponding to the `key` and get the `value` in the bucket.

So, how to locate the corresponding bucket based on the `key`? This is achieved through the "Hash Function". What a hash function does is map a larger input space to a smaller output space. In a hash table, the input space is all `key`s, and the output space is all buckets (array indexes). In other words, input a `key`, and **we can get the storage location of the key-value pair corresponding to the key in the array through the hash function**.

Given a `key`, the calculation process of the hash function is divided into two steps:

1. Calculate the hash value through a certain hash algorithm `hash()`.
2. The hash value is modulo the number of buckets (array length) `capacity` to obtain the array `index` corresponding to the `key`.

`index = hash(key) % capacity`

Then, we can use the `index` to access the corresponding bucket in the hash table to obtain the `value`.

Let the array length `capacity = 100`, the hash algorithm `hash(key) = key`, and the easily obtained hash function be `key % 100`. The following picture shows the working principle of the hash function by taking the `key` student number and `value` name as an example.

![Fig. 哈希函数工作原理](./algos/6.1.2.png)

The following code implements a simple hash table. Here, we encapsulate key and value into a class Pair to represent key-value pairs.

```zig
// key value pair
const Pair = struct {
    key: usize = undefined,
    val: []const u8 = undefined,

   pub fn init(key: usize, val: []const u8) Pair {
        return Pair {
            .key = key,
            .val = val,
        };
    }
};

// hash table based on simple implementation of array
fn ArrayHashMap(comptime T: type) type {
    return struct {
        bucket: ?std.ArrayList(?T) = null,
        mem_allocator: std.mem.Allocator = undefined,

        const Self = @This();

        // constructor
        pub fn init(self: *Self, allocator: std.mem.Allocator) !void {
            self.mem_allocator = allocator;
            // initializes a bucket(array) with a length of 100
            self.bucket = std.ArrayList(?T).init(self.mem_allocator);
            var i: i32 = 0;
            while (i < 100) : (i += 1) {
                try self.bucket.?.append(null);
            }
        }

        // destructor
        pub fn deinit(self: *Self) void {
            if (self.bucket != null) self.bucket.?.deinit();
        }

        // hash function
        fn hashFunc(key: usize) usize {
            var index = key % 100;
            return index;
        }

        // query operation
        pub fn get(self: *Self, key: usize) []const u8 {
            var index = hashFunc(key);
            var pair = self.bucket.?.items[index];
            return pair.?.val;
        }

        // add operation
        pub fn put(self: *Self, key: usize, val: []const u8) !void {
            var pair = Pair.init(key, val);
            var index = hashFunc(key);
            self.bucket.?.items[index] = pair;
        }

        // delete operation
        pub fn remove(self: *Self, key: usize) !void {
            var index = hashFunc(key);
            // sets to null, which means delete
            self.bucket.?.items[index] = null;
        }       

        // gets all key-value pairs
        pub fn pairSet(self: *Self) !std.ArrayList(T) {
            var entry_set = std.ArrayList(T).init(self.mem_allocator);
            for (self.bucket.?.items) |item| {
                if (item == null) continue;
                try entry_set.append(item.?);
            }
            return entry_set;
        }  

        // gets all keys
        pub fn keySet(self: *Self) !std.ArrayList(usize) {
            var key_set = std.ArrayList(usize).init(self.mem_allocator);
            for (self.bucket.?.items) |item| {
                if (item == null) continue;
                try key_set.append(item.?.key);
            }
            return key_set;
        }  

        // gets all values
        pub fn valueSet(self: *Self) !std.ArrayList([]const u8) {
            var value_set = std.ArrayList([]const u8).init(self.mem_allocator);
            for (self.bucket.?.items) |item| {
                if (item == null) continue;
                try value_set.append(item.?.val);
            }
            return value_set;
        }

        // prints hash table
        pub fn print(self: *Self) !void {
            var entry_set = try self.pairSet();
            defer entry_set.deinit();
            for (entry_set.items) |item| {
                std.debug.print("{} -> {s}\n", .{item.key, item.val});
            }
        }
    };
}
```

6.1.3. Hash Collisions and Scaling

In essence, the function of the hash function is to map the input space composed of all `key`s to the output space composed of all indexes of the array, and the input space is often much larger than the output space. Therefore, **theoretically there must be a situation where "multiple inputs correspond to the same output"**.

For the hash function in the above example, when the last two digits of the input `key` are the same, the output of the hash function is also the same. For example, when querying for two students whose student IDs are 12836 and 20336, we get:

`12836 % 100 = 36`
`20336 % 100 = 36`

As shown in the following picture, two student numbers point to the same name, which is obviously wrong. We call this situation where multiple inputs correspond to the same output "Hash Collision".

![Fig. 哈希冲突示例](./algos/6.1.3.1.png)

It is easy to think that the larger the capacity $n$ of the hash table, the lower the probability that multiple keys will be assigned to the same bucket, and the fewer conflicts. Therefore, **we can reduce hash collisions by expanding the hash table**.

As shown in the figure below, the key-value pairs `(136, A)` and `(236, D)` conflict before the expansion, and the conflict disappears after the expansion.

![Fig. 哈希表扩容](./algos/6.1.3.2.png)

Similar to array expansion, hash table expansion requires migrating all key-value pairs from the original hash table to the new hash table, which is very time-consuming. And because the `capacity` of the hash table changes, we need to recalculate the storage locations of all key-value pairs through the hash function, which further increases the computational overhead of the expansion process. For this reason, programming languages usually reserve a large enough hash table capacity to prevent frequent expansion.

"Load Factor" is an important concept of the hash table. It is defined as the number of elements in the hash table divided by the number of buckets. It is used to measure the severity of hash conflicts and **is often used as a trigger for hash table expansion**. . For example, in Java, when the load factor exceeds $0.75$, the system will expand the capacity of the hash table by $2$ times.

6.2. hash collision

As mentioned in the previous section, **usually the input space of a hash function is much larger than the output space**, so theoretically hash collisions are inevitable. For example, if the input space is all integers and the output space is the size of the array, there must be multiple integers mapped to the same array index.

Hash collisions will lead to wrong query results and seriously affect the availability of the hash table. To solve this problem, we can expand the hash table every time we encounter a hash collision until the collision disappears. This method is simple, crude and effective, but the efficiency is too low, because the expansion of the hash table requires a lot of data handling and hash value calculation. In order to improve efficiency, let's switch our thinking:

1. Improve the data structure of the hash table **so that the hash table can work normally when there is a hash collision**.
2. Execute capacity expansion only when necessary, that is, when hash collisions are serious.

The structural improvement methods of the hash table mainly include chained address and open addressing.

6.2.1. chained address

In the original hash table, each bucket can only store one key-value pair. "Separate Chaining" converts a single element into a linked list, uses key-value pairs as linked list nodes, and stores all conflicting key-value pairs in the same linked list. The following picture shows an example of a chained address hash table.

![Fig. 链式地址哈希表](./algos/6.2.1.png)

The operation method of the hash table under the chained address has undergone some changes.

- **Query element**: input `key`, get the array index through the hash function, and then access the head node of the linked list, then traverse the linked list and compare the `key`s to find the target key-value pair.
- **Adding elements**: first access the head node of the linked list through the hash function, and then add the node (that is, the key-value pair) to the linked list.
- **Delete elements**: access the head of the linked list according to the result of the hash function, then traverse the linked list to find the target node, and delete it.

Chained adresses method has some limitations, including:

- **The occupied space increases**. The linked list contains node pointers, which consume more memory space than the array.
- **The query efficiency is reduced** because the linked list needs to be traversed linearly to find the corresponding element.

A simple implementation of a chained address hash table is given below, two points need to be noted:

- In order to keep the code as short as possible, we use lists (dynamic arrays) instead of linked lists. In this setting, the hash table (array) contains multiple buckets, and each bucket is a list.
- The following code implements the hash table expansion method. Specifically, when the load factor exceeds $0.75$, we double the size of the hash table.

```zig
[class]{HashMapChaining}-[func]{}
```

>**Tip**
>When the linked list is very long, the query efficiency O(n) is very poor. **At this point, the linked list can be converted into an "AVL tree" or "red-black tree"**, thereby optimizing the time complexity of the query operation to $O(log\,n)$.

6.2.2. open addressing

"Open Addressing" does not introduce additional data structures, but handles hash conflicts through "multiple detection". The detection methods mainly include linear detection, square detection, multiple hashing, etc.

1. linear detection

Linear detection uses a fixed-step linear search for detection, and its operation method is different from that of ordinary hash tables.

- Inserting elements: Calculate the array index through the hash function. If an element is found in the bucket, traverse backward linearly from the conflict position (the step size is usually $1$) until an empty space is found, and insert the element into it.
Find an element: If a hash conflict is found, use the same stride to traverse backward linearly until the corresponding element is found, and return `value`; if a vacancy is encountered, it means that the target key-value pair is not in the hash table, and return $None$.

![Fig. 线性探测](./algos/6.2.2.1.png)

However, linear probing suffers from the following drawbacks:

- **Elements cannot be deleted directly**. Deleting an element will create a vacancy in the array. When looking for elements after the vacancy, the vacancy may cause the program to misjudge that the element does not exist. To do this, it is usually necessary to mark the deleted element with the help of a flag bit.
- **Prone to aggregation**. The longer the consecutive occupied positions in the array are, the more likely hash collisions will occur at these consecutive positions, which will further promote the growth of this position and form a vicious circle, which will eventually lead to the deterioration of the efficiency of adding, deleting, checking and modifying operations.

The following code implements a simple open addressable (linear probing) hash table.

- We use a fixed key-value pair instance `removed` to mark removed elements. That is to say, when the element in a bucket is $None$ or `removed`, it means that the bucket is empty and can be used to place key-value pairs.
- When probing linearly, we traverse backward from the current `index`; when we cross the end of the array, we need to go back to the head to continue traversing.

```zig
[class]{HashMapOpenAddressing}-[func]{}
```

2. multiple hashes

As the name suggests, multiple hashing methods use multiple hash functions $f1(x),f2(x),f3(x),...$ for detection.

- **Insert element**: If there is a conflict in the hash function $f1(x)$, try $f2(x)$, and so on, until an empty space is found and the element is inserted.
- Find element: Search in the same hash function order until the target element is found; or return $None$ if a space is encountered or all hash functions have been tried, indicating that the element does not exist in the hash table.

Compared with linear probing, multiple hashing methods are not prone to aggregation, but multiple hash functions will increase the amount of additional calculations.

6.2.3. Choice of programming language

Java uses chained addresses. Since JDK 1.8, when the length of the array in the HashMap reaches 64 and the length of the linked list reaches 8, the linked list will be converted into a red-black tree to improve search performance.

Python uses open addressing. Dictionary dict probes with pseudorandom numbers.

Golang uses chained addressing. Go stipulates that each bucket can store up to 8 key-value pairs, and if the capacity is exceeded, an overflow bucket will be connected; when there are too many overflow buckets, a special equal expansion operation will be performed to ensure performance.

6.3. hash algorithm

In the last two sections, we saw how hash tables work and how hash collisions are handled. However, whether it is open addressing or chain addressing, **they can only ensure that the hash table can work normally when conflicts occur, but cannot reduce the occurrence of hash conflicts**.

If the hash collisions are too frequent, the performance of the hash table will be drastically degraded. As shown in the following picture, for the chain address hash table, ideally, the key-value pairs are evenly distributed in each bucket to achieve the best query efficiency; in the worst case, all key-value pairs are stored in the same bucket, and the time complexity degrades to $O(n)$.

![Fig. 哈希冲突的最佳与最差情况](./algos/6.3.0.png)

**The distribution of key-value pairs is determined by the hash function**. Recall the calculation steps of the hash function, first calculate the hash value, and then take the modulus of the length of the array:

`index = hash(key) % capacity`

Observing the above formula, when the `capacity` of the hash table is fixed, **the hash algorithm `hash()` determines the output value**, and then determines the distribution of key-value pairs in the hash table.

This means that in order to reduce the probability of hash collisions, we should focus on the design of the hash algorithm `hash()`.

6.3.1. The goal of the hash algorithm

In order to realize a "fast and stable" hash table data structure, the hash algorithm should include the following characteristics:

- **Deterministic**: Given the same input, a hashing algorithm should always produce the same output. This ensures that the hash table is reliable.
- **Efficient**: The process of calculating the hash value should be fast enough. The smaller the computational overhead, the more practical the hash table is.
- **Uniform distribution**: The hash algorithm should make the key-value pairs evenly distributed in the hash table. The more even the distribution, the lower the probability of hash collisions.

In fact, in addition to being used to implement hash tables, hash algorithms are also widely used in other fields.

- **Password storage**: In order to protect the security of user passwords, the system usually does not directly store the user's plaintext password, but stores the hash value of the password. When a user enters a password, the system calculates a hash of the entered password and compares it to the stored hash. If the two match, then the password is considered correct.
- **Data integrity check**: The data sender can calculate the hash value of the data and send it together; the receiver can recalculate the hash value of the received data and compare it with the received hash value. If the two match, then the data is considered complete.

For cryptography-related applications, the hash algorithm needs to meet higher security standards to prevent reverse engineering such as deriving the original password from the hash value, including:

- **Collision resistance**: It should be extremely difficult to find two different inputs such that they have the same hash.
- **Avalanche Effect**: A small change in the input should result in a significant and unpredictable change in the output.

Please note that **"uniform distribution" and "collision resistance" are two independent concepts**, and satisfying uniform distribution does not necessarily satisfy collision resistance. For example, given a random input `key`, the hash function `key % 100` can produce a uniformly distributed output. However, the hash algorithm is too simple, and the output of all `key`s with the same last two digits is the same, so we can easily deduce the usable `key` from the hash value to crack the password.

6.3.2. Hash Algorithm Design

The design of a hash algorithm is a complex issue that requires consideration of many factors. However, for simple scenarios, we can also design some simple hash algorithms.

- **Additive hashing**: Add the ASCII code of each input character, and use the sum as the hash value.
- **Multiplicative hashing**: Using the irrelevance of multiplication, each round is multiplied by a constant, and the ASCII codes of each character are accumulated into the hash value.
- **XOR hashing**: accumulate each element of the input data into a hash value through XOR operation.
- **Rotation hashing**: accumulate the ASCII code of each character into a hash value, and rotate the hash value before each accumulation.

```zig
[class]{}-[func]{addHash}

[class]{}-[func]{mulHash}

[class]{}-[func]{xorHash}

[class]{}-[func]{rotHash}
```

It is observed that the last step of each hash algorithm is to take the modulus of the large prime number $1000000007$ to ensure that the hash value is within the appropriate range. It is worth thinking about why we should emphasize modulo prime numbers, or what are the disadvantages of modulo composite numbers? This is an interesting question.

Let’s draw the conclusion first: **when we use a large prime number as the modulus, we can maximize the uniform distribution of the hash value**. Because prime numbers do not have common divisors with other numbers, periodic patterns due to modulo operations can be reduced, thereby avoiding hash collisions.

As an example, suppose we choose the composite number $9$ as the modulus, which is divisible by $3$. Then all `key`s that are divisible by $3$ will be mapped to the three hash values of $0$, $3$ and $6$.
$$\begin{align*}
modulus&=9\\
key&=\{0,3,6,9,12,15,18,21,24,27,30,33,...\}\\
hash&=\{0,3,6,0,3,6,0,3,6,0,3,6,...\}
\end{align*}$$
If the input `key` just satisfies the data distribution of this arithmetic sequence, then the hash value will be piled up, which will aggravate the hash collision. Now, assuming that `modulus` is replaced by the prime number 13, since there is no common divisor between `key` and `modulus`, the uniformity of the output hash value will be significantly improved.
$$\begin{align*}
modulus&=13\\
key&=\{0,3,6,9,12,15,18,21,24,27,30,33,...\}\\
hash&=\{0,3,6,9,12,2,5,8,11,1,4,7,...\}
\end{align*}$$
It is worth noting that if the `key` can be guaranteed to be randomly and uniformly distributed, then it is possible to choose a prime number or a composite number as the modulus, and they can both output uniformly distributed hash values. And when the `key` distribution has some periodicity, it is easier to aggregate when taking the modulus of the composite number.

All in all, we usually choose a prime number as the modulus, and this prime number is preferably large enough to eliminate periodic patterns as much as possible and improve the robustness of the hash algorithm.

6.3.3. Common Hash Algorithms

It is not difficult to find that the simple hash algorithms introduced above are relatively "fragile", far from reaching the design goal of the hash algorithm. For example, since addition and XOR satisfy the commutative law, additive hashing and XOR hashing cannot distinguish strings with the same content but different orders, which may aggravate hash collisions and cause some security issues.

In practice, we usually use some standard hash algorithms, such as MD5, SHA-1, SHA-2, SHA3, etc. They can map input data of arbitrary length to constant-length hashes.

For nearly a century, the hash algorithm has been in the process of continuous upgrading and optimization. Some researchers work hard to improve the performance of hashing algorithms, while other researchers and hackers are working on finding security issues of hashing algorithms.

- MD5 and SHA-1 have been successfully attacked many times, so they are deprecated for multiple security applications.
- SHA-256 in the SHA-2 series is one of the most secure hash algorithms, and there have been no successful attack cases, so it is often used in various security applications and protocols.
- Compared with SHA-2, SHA-3 has lower implementation overhead and higher computational efficiency, but the current use coverage is not as good as the SHA-2 series.

||MD5|SHA-1|SHA-2|SHA-3|
|---|---|---|---|---|
|launch time|1992|1995|2002|2008|
|output length|128 bits|160 bits|256/512 bits|224/256/384/512 bits|
|hash collision|more|more|rare|rare|
|security level|low, sucessfully attacked|low, successfully attacked|high|high|
|application|deprecated, still used<br>for data integrity checks|deprecated|cryptocurrency transaction<br>verification, digital<br>digital signatures, etc|can be used instead<br>of SHA-2|

6.3.4. data structure of the hash value

We know that the `key` of the hash table can be a data type such as an integer, a decimal, or a string. Programming languages usually provide built-in hash algorithms for these data types, which are used to calculate the bucket index in the hash table. Taking Python as an example, we can call the `hash()` function to calculate the hash value of various data types, including:

- The hash value of integers and booleans is itself.
- The calculation of the hash value of floating-point numbers and strings is more complicated, and interested students should learn by themselves.
- The hash value of a tuple is to hash each element in it, and then combine these hash values to obtain a single hash value.
- An object's hash value is generated based on its memory address. By overriding the object's hash method, it is possible to generate a hash value based on the content.

>**Tip**
>Note that different programming languages have different definitions and methods of built-in hash calculation functions.

```zig
```

In many programming languages, **only immutable objects can be used as hash table `keys`**. If we use a list (dynamic array) as the `key`, when the content of the list changes, its hash value will also change, and we will not be able to query the original `value` in the hash table.

Although the member variables of a custom object (such as a linked list node) are mutable, it is hashable. **This is because the hash value of the object is usually generated based on the memory address**. Even if the content of the object changes, but its memory address does not change, the hash value remains unchanged.

If you are careful, you may find that when you run the program in different consoles, the output hash values are different. **This is because the Python interpreter adds a random salt (Salt) value to the string hash function every time it starts**. This approach can effectively prevent HashDoS attacks and improve the security of the hash algorithm.

6.4. summary

- Given a `key`, one can query the `value` in the hash table in $O(1)$ time, which is very efficient.
- Common hash table operations include querying, adding key-value pairs, deleting key-value pairs, and traversing hash tables, etc.
- The hash function maps the `key` to an array index to access the corresponding bucket and obtain the `value`.
- Two different `key`s may get the same array index after passing through the hash function, resulting in an error in the query result. This phenomenon is called a hash collision.
- The larger the capacity of the hash table, the lower the probability of hash collisions. Therefore, hash conflicts can be alleviated by expanding the hash table. Similar to array expansion, hash table expansion operations are expensive.
- The load factor is defined as the number of elements in the hash table divided by the number of buckets, which reflects the severity of hash collisions and is often used as a condition to trigger the expansion of the hash table.
- Chained addressing stores all conflicting elements in the same linked list by converting a single element into a linked list. However, if the linked list is too long, the query efficiency will be reduced, and the linked list can be further converted into a red-black tree to improve efficiency.
- Open addressing handles hash collisions by probing multiple times. Linear detection uses a fixed step size. The disadvantage is that elements cannot be deleted and aggregation is easy to occur. Multiple hashing uses multiple hash functions for detection, which is less likely to generate aggregation than linear detection, but multiple hash functions increase the amount of calculation.
- Different programming languages adopt different hash table implementations. For example, Java's `HashMap` uses chained addressing, while Python's `Dict` uses open addressing.
- In a hash table, we want the hash algorithm to be deterministic, efficient, and evenly distributed. In cryptography, the hash algorithm should also have anti-collision and avalanche effects.
- Hash algorithms usually use a large prime number as the modulus to maximize the uniform distribution of hash values and reduce hash collisions.
- Common hash algorithms include MD5, SHA-1, SHA-2, SHA3, etc. MD5 is often used to check file integrity, and SHA-2 is often used in security applications and protocols.
- Programming languages usually provide a built-in hash algorithm for data types, which is used to calculate the bucket index in the hash table. Typically, only immutable objects are hashable.

6.4.1. Q & A

>**Why is the time complexity of the hash table not $O(n)$?**
>When the hash collision is serious, the time complexity of the hash table will degenerate to $O(n)$. When the hash function is well designed, the capacity setting is reasonable, and the collisions are average, the time complexity is $O(1)$. When we use the hash table built into the programming language, we usually think that the time complexity is $O(1)$.

>**Why not just use the hash function $f(x)=x$? Then there will be no conflict**
>Under the $f(x)=x$ hash function, each element corresponds to a unique bucket index, which is equivalent to an array. However, the input space is usually much larger than the output space (array length), so the final step of a hash function is often modulo the array length. In other words, the goal of a hash table is to map a larger state space into a smaller space and provide $O(1)$ query efficiency.

>**The underlying implementation of the hash table is an array, a linked list, and a binary tree, but why can it be more efficient than them?**
>First, the time efficiency of the hash table becomes higher, but the space efficiency becomes lower. A considerable part of the memory of the hash table is unused,
>
>Secondly, the time efficiency becomes higher only in specific usage scenarios. If a function can be implemented using an array or a linked list with the same time complexity, then it is usually faster than a hash table. This is because the hash function calculation requires overhead, and the constant term of the time complexity is larger.
>
>Finally, the time complexity of hash tables may be degraded. For example, in the chain address, we take the search operation in the linked list or red-black tree, and there is still a risk of degenerating to $O(n)$ time.

>**Does multiple hashing have the disadvantage of not being able to delete elements directly? For spaces marked as deleted, can the space be used again?**
>Multiple hashing is a type of open addressing. Open addressing methods have the defect that elements cannot be deleted directly, and need to be deleted by marking. Space marked as deleted can be used again. When a new element is inserted into the hash table, and the hash function finds a location marked as deleted, that location can be used by the new element. In this way, the detection sequence of the hash table can be kept unchanged, and the space utilization rate of the hash table can be guaranteed.

>**Why do hash collisions occur when looking for elements in linear detection?**
>When searching, find the corresponding bucket and key-value pair through the hash function, and find that the `key` does not match, which means there is a hash conflict. Therefore, the linear probing method will search down sequentially according to the preset step size until the correct key-value pair is found or no escape can be found.

>**Why can hash table expansion alleviate hash collisions?**
>The last step of the hash function is often to take the remainder of the array length $n$, so that the output value falls within the array index range; after expansion, the array length $n$ changes, and the index corresponding to the `key` may also change. Multiple `key`s that were originally in the same bucket may be allocated to multiple buckets after capacity expansion, so as to alleviate hash conflicts.

7. Tree

>**Abstract**
>The towering tree is full of vitality, its roots are deep and leafy, and its branches are sparse.
>
>It shows us the vivid form of data partition.

7.1. binary tree

A "Binary Tree" is a non-linear data structure that represents the derivation relationship between ancestors and descendants, and embodies the divide-and-conquer logic of "one divides into two". Similar to a linked list, the basic unit of a binary tree is a node, and each node contains a "value" and two "pointers": a reference to a left child node, and a reference to a right child node.

```zig
```

The two pointers of the node point to the "left child node" and "right child node" respectively, and the node is called the "parent node" of these two child nodes. Given a node of a binary tree, we call the tree formed by the left child node of the node and its following nodes the "left subtree" of the node, and the "right subtree" can be obtained similarly.

In a binary tree, all nodes except leaf nodes contain child nodes and non-empty subtrees. For example, in the following example, if "node 2" is regarded as the parent node, its left and right child nodes are "node 4" and "node 5" respectively, and the left subtree is "The tree formed by node 4 and its following nodes", the right subtree is "the tree formed by node 5 and below".

![Fig. 父节点、子节点、子树](./algos/7.1.0.png)

7.1.1. Binary tree common terms

Common terminology for binary trees is shown in the following picture.

- "Root Node": The node at the top of the binary tree without a parent node.
- "Leaf Node": A node with no child nodes, both of its pointers point to $None$.
- "Layer/Level" of the node: increasing from top to bottom, and the root node's layer is 1.
- "Degree" of the node: the number of child nodes of the node. In a binary tree, the values range of degree is from 0, 1, 2.
- "Edge": The line segment connecting two nodes, that is, the node pointer.
- "Height" of the binary tree: the number of edges passed from the root node to the furthest leaf node.
- "Depth" of the node: the number of edges passed from the root node to the node.
- "Height" of the node: the number of edges passed from the furthest leaf node to the node.

![Fig. 二叉树的常用术语](./algos/7.1.1.png)

>**Tip**
>Please note that we usually define "height" and "depth" as "the number of edges walked", but some topics or textbooks may define them as "the number of nodes walked". In this case, both height and depth need to be incremented by 1.

7.1.2. Basic operation of binary tree

1. Initializing the binary tree.

Similar to a linked list, the nodes are initialized first, and then the reference points (i.e. pointers) are built.

```zig
```

2. Inserting and deleting nodes.

Similar to a linked list, inserting and deleting nodes in a binary tree can be achieved by modifying pointers. The following picture shows an example.

![Fig. 在二叉树中插入与删除节点](./algos/7.1.2.png)

```zig
```

>**Note**
>It should be noted that inserting a node may change the original logical structure of the binary tree, and deleting a node usually means deleting the node and all its subtrees. Therefore, in the binary tree, the insertion and deletion operations are usually completed by a set of operations to achieve practical operations.

7.1.3. Common Binary Tree Types

1. perfect binary tree

The "perfect binary tree" is completely filled with nodes in all but the bottom layer. In a perfect binary tree, the degree of the leaf nodes is $0$, and the degree of all other nodes is $2$; if the height of the tree is $h$, the total number of nodes is $2^{h+1}-1$, presenting a standard exponential relationship, reflecting the common phenomenon of cell division in nature.

>**Tip**
>In the Chinese community, a perfect binary tree is often called a "full binary tree", please pay attention to the distinction.

![Fig. 完美二叉树](./algos/7.1.3.1.png)

2. complete binary tree

As shown in the following picture, only the lowest node of the "complete binary tree" is not filled, and the lowest node is filled as far as possible to the left.

![Fig. 完全二叉树](./algos/7.1.3.2.png)

3. full binary tree

As shown in the following picture, the "full binary tree" all nodes have two child nodes except for the leaf node.

![Fig. 完满二叉树](./algos/7.1.3.3.png)

4. balanced binary tree

As shown in the following picture, the absolute value of the difference between the heights of the left subtree and the right subtree of any node in the "balanced binary tree" does not exceed 1.

![Fig. 平衡二叉树](./algos/7.1.3.4.png)

7.1.4. Degradation of Binary Trees

When the nodes of each layer of the binary tree are filled, a "perfect binary tree" is achieved; and when all nodes are biased to one side, the binary tree degenerates into a "linked list".

- The perfect binary tree is the ideal situation to take full advantage of the binary tree's "divide and conquer".
- The linked list is the other extreme. All operations become linear operations, and the time complexity degenerates to $O(n)$.

![Fig. 二叉树的最佳与最差结构](./algos/7.1.4.png)

As shown in the following table, under the best and worst structures, the number of leaf nodes, total number of nodes, height, etc. of the binary tree reach maximum or minimum values.

||Perfect binary tree|Linked list|
|---|---|---|
|The number of nodes in layer $i$|$2^{i-1}$|$1$|
|The number of leaf nodes when the height of the tree is $h$|$2^h$|$1$|
|The total number of nodes when the height of the tree is $h$|$2^{h+1}-1$|$h+1$|
|The height of the tree when the total number of nodes is $n$|$log_2(n+1)-1$|$n-1$|

7.2. binary tree traversal

From the perspective of physical structure, a tree is a data structure based on a linked list, so its traversal method is to visit nodes one by one through pointers. However, a tree is a non-linear data structure, which makes traversing a tree more complicated than traversing a linked list, requiring the help of a search algorithm.

Common traversal methods of binary trees include level-order traversal, pre-order traversal, in-order traversal, and post-order traversal.

7.2.1. level-order traversal

As shown in the following picture "Level-Order Traversal" traverses the binary tree layer by layer from top to bottom, and visits nodes in order from left to right at each layer.

Level-order traversal essentially belongs to "Breadth-First Traversal", which embodies a layer-by-layer search method of "expanding outward one by one".

![Fig. 二叉树的层序遍历](./algos/7.2.1.png)

1. code

Breadth-first traversal is usually implemented with the help of a "queue". The queue follows the "first in, first out" rule, while the breadth-first traversal follows the "layer-by-layer advance" rule, and the ideas behind the two are the same.

```zig
// level-order traversal
fn levelOrder(comptime T: type, mem_allocator: std.mem.Allocator, root: *inc.TreeNode(T)) !std.ArrayList(T) {
    // initializes the queue and join the root node
    const L = std.TailQueue(*inc.TreeNode(T));
    var queue = L{};
    var root_node = try mem_allocator.create(L.Node);
    root_node.data = root;
    queue.append(root_node); 
    // initializes a list to save the traversal sequence
    var list = std.ArrayList(T).init(std.heap.page_allocator);
    while (queue.len > 0) {
        var queue_node = queue.popFirst().?;    // queue dequeue
        var node = queue_node.data;
        try list.append(node.val);              // save node value
        if (node.left != null) {
            var tmp_node = try mem_allocator.create(L.Node);
            tmp_node.data = node.left.?;
            queue.append(tmp_node);             // enqueue the left child node
        }
        if (node.right != null) {
            var tmp_node = try mem_allocator.create(L.Node);
            tmp_node.data = node.right.?;
            queue.append(tmp_node);             // enqueue the right child node
        }        
    }
    return list;
}
```

2. complexity analysis

- **Time complexity $O(n)$**: All nodes are visited once, using $O(n)$ time, where $n$ is the number of nodes.
- Space complexity $O(n)$: In the worst case, that is, when the binary tree is full, before traversing to the bottom layer, there are at most $(n+1)/2$ nodes in the queue at the same time, occupying $O(n)$ space.

7.2.2. Pre-order, in-order, post-order traversal

Correspondingly, pre-order, in-order, and post-order traversals all belong to "Depth-First Traversal", which embodies a traversal method of "go to the end first, and then continue backtracking".

The following picture shows how depth-first traversal of a binary tree works. **Depth-first traversal is like "walking" around the periphery of the entire binary tree**. At each node, three positions will be encountered, corresponding to pre-order traversal, in-order traversal, and post-order traversal.

![Fig. 二叉搜索树的前、中、后序遍历](./algos/7.2.2.0.png)

1.code

Depth-first search is usually implemented based on recursion:

```zig
// pre-order traversal
fn preOrder(comptime T: type, root: ?*inc.TreeNode(T)) !void {
    if (root == null) return;
    // access priority: root node -> left subtree -> right subtree
    try list.append(root.?.val);
    try preOrder(T, root.?.left);
    try preOrder(T, root.?.right);
}

// in-order traversal
fn inOrder(comptime T: type, root: ?*inc.TreeNode(T)) !void {
    if (root == null) return;
    // access priority: left subtree -> root node -> right subtree
    try inOrder(T, root.?.left);
    try list.append(root.?.val);
    try inOrder(T, root.?.right);
}

// post-order traversal
fn postOrder(comptime T: type, root: ?*inc.TreeNode(T)) !void {
    if (root == null) return;
    // access priority: left subtree -> right subtree -> root node
    try postOrder(T, root.?.left);
    try postOrder(T, root.?.right);
    try list.append(root.?.val);
}
```

>**Note**
>Depth-first search can also be implemented based on iteration, and interested students can do their own research.

The following picture shows the recursive process of traversing a binary tree in preorder, which can be divided into two opposite parts: "recurse" and "backtrack".

1. "Recurse" means to open a new method, and the program visits the next node in the process.
2. "Return" indicates that the function returns, indicating that the current node has been visited.

![<1>](./algos/7.2.2.1-1.png) ![<2>](./algos/7.2.2.1-2.png) ![<3>](./algos/7.2.2.1-3.png) ![<4>](./algos/7.2.2.1-4.png) ![<5>](./algos/7.2.2.1-5.png) ![<6>](./algos/7.2.2.1-6.png) ![<7>](./algos/7.2.2.1-7.png) ![<8>](./algos/7.2.2.1-8.png) ![<9>](./algos/7.2.2.1-9.png) ![<10>](./algos/7.2.2.1-10.png) ![<11>](./algos/7.2.2.1-11.png)

2. complexity analysis

- Time complexity $O(n)$: All nodes are visited once, using $O(n)$ time.
- Space complexity $O(n)$: In the worst case, when the tree degenerates into a linked list, the recursion depth reaches $n$, and the system occupies $O(n)$ stack frame space.

7.3. Binary tree array representation

Under the linked list representation, the storage unit of the binary tree is the node `TreeNode`, and the nodes are connected by pointers. In the last section, we learned the basic operations of the binary tree under the linked list representation.

So, can an "array" be used to represent a binary tree? The answer is yes.

7.3.1. Representing a perfect binary tree

Let's analyze a simple case first. Given a perfect binary tree, we store all nodes in an array in the order of level-order traversal, and each node corresponds to a unique array index.

According to the characteristics of layer order traversal, we can deduce the "mapping formula" between the index of the parent node and the index of the child node: **if the index of the node is $i$, then the index of the left child node of the node is $2i+1$, and the index of the right child node is $2i+2$**. The following picture shows the mapping relationship between each node index.

![Fig. 完美二叉树的数组表示](./algos/7.3.1.png)

**The role of the mapping formula is equivalent to the pointer in the linked list**. Given any node in the array, we can access its left (right) child nodes through the mapping formula.

7.3.2. represent any binary tree

However, a perfect binary tree is a special case. In the middle layer of the binary tree, there are usually many $None$. Since the sequence traversal sequence does not contain these $None$, we cannot infer the number and distribution of $None$ based on the sequence alone. **This means that there are various binary tree structures that conform to this sequence of level-order traversals**.

As shown in the following picture, given an imperfect binary tree, the above-mentioned array representation method is invalid.

![Fig. 层序遍历序列对应多种二叉树可能性](./algos/7.3.2.1.png)

To solve this problem, **we can consider writing out all $None$ explicitly in the level-order traversal sequence**. As shown in the figure below, after this processing, the sequence traversal sequence can uniquely represent the binary tree.

```zig
```

![Fig. 任意类型二叉树的数组表示](./algos/7.3.2.2.png)

It is worth noting that **complete binary trees are well suited to be represented by arrays**. Looking back at the definition of a complete binary tree, $None$ only appears at the bottom and right, so **all $None$ must appear at the end of the sequence traversal sequence**.

This means that when using an array to represent a complete binary tree, you can omit storing all $None$, which is very convenient. The following picture shows an example.

![Fig. 完全二叉树的数组表示](./algos/7.3.2.3.png)

The following code implements a binary tree based on array representation, including the following operations.

- Given a node, get its value, left (right) child node, parent node.
- Obtain pre-order traversal, in-order traversal, post-order traversal, and level-order traversal sequences.

```zig
[class]{ArrayBinaryTree}-[func]{}
```

7.3.3. Strengths and Limitations

The array representation of the binary tree mainly has the following advantages.

- Arrays are stored in contiguous memory space, which is cache-friendly and has faster access and traversal speeds.
- There is no need to store pointers, which saves space.
- Allow random access to nodes.

However, array representation also have some limitations:

- Array storage requires continuous memory space, so it is not suitable for storing trees with large amounts of data.
- Adding and deleting nodes needs to be implemented through array insertion and deletion operations, which is inefficient.
- When there are a large number of $None$ in the binary tree, the proportion of node data contained in the array is low, and the space utilization rate is low.

7.4. binary search tree

As shown in the following picture, the "Binary Search Tree" satisfies the following conditions.

1. For the root node, the value of all nodes in the left subtree $<$ the value of the root node $<$ the value of all nodes in the right subtree.
2. The left and right subtrees of any node are also binary search trees, which also satisfy condition 1.

![Fig. 二叉搜索树](./algos/7.4.0.png)

7.4.1. Operations on Binary Search Trees

We encapsulate the binary search tree as a class `ArrayBinaryTree`, and declare a member variable `root`, pointing to the root node of the tree.

1. finding a node

Given the target node value `num`, it can be looked up based on the nature of the binary search tree. As shown in the following picture, we declare a node `cur` and compare the size relationship between the node values `cur.val` and `num` in a loop, starting from the `root` node of the binary tree.

- If `cur.val < num`, the target node is in the right subtree of `cur`, so `cur = cur.right` is executed.
- If `cur.val > num`, the target node is in the left subtree of `cur`, so `cur = cur.left`.
- If `cur.val = num`, it means that the target node is found, jump out of the loop and return this node.

![<1>](./algos/7.4.1.1-1.png) ![<2>](./algos/7.4.1.1-2.png) ![<3>](./algos/7.4.1.1-3.png) ![<4>](./algos/7.4.1.1-4.png)

The search operation of the binary search tree is consistent with the working principle of the binary search algorithm, which excludes half of the cases in each round. The number of loops is at most the height of the binary tree, which takes $O(log\,n)$ time when the binary tree is balanced.

```zig
// find node
fn search(self: *Self, num: T) ?*inc.TreeNode(T) {
    var cur = self.root;
    // loop search, jump out after crossing the leaf node
    while (cur != null) {
        // the target node is in the right subtree of cur
        if (cur.?.val < num) {
            cur = cur.?.right;
        // the target node is in the left subtree of cur
        } else if (cur.?.val > num) {
            cur = cur.?.left;
        // find the target node and jump out of the loop
        } else {
            break;
        }
    }
    // return target node
    return cur;
}
```

2. inserting a node

Given an element num to be inserted, in order to maintain the nature of the binary search tree "left subtree < root node < right subtree", the insertion operation is shown in the following picture.

1. **Find the insertion position**: Similar to the search operation, start from the root node, and search downwards according to the size relationship between the current node value and num, and jump out of the loop until you cross the leaf node (traversing to $None$).
2. **Insert a node at this position**: initialize the node `num` and put the node at the position of $None$.

![Fig. 在二叉搜索树中插入节点](./algos/7.4.1.2.png)

In the code implementation, you need to pay attention to the following two points.

- A binary search tree does not allow duplicate nodes, otherwise it would violate its definition. Therefore, if the node to be inserted already exists in the tree, the insertion will not be performed, and the search will return immediately.
- In order to insert nodes, we need to use the node `pre` to save the nodes of the previous cycle. In this way, when traversing to $None$, we can get its parent node to complete the node insertion operation.

```zig
// insert node
fn insert(self: *Self, num: T) !void {
    // if the tree is empty, immediately return early
    if (self.root == null) return;
    var cur = self.root;
    var pre: ?*inc.TreeNode(T) = null;
    // loop search, jump out after crossing the leaf node
    while (cur != null) {
        // find duplicate nodes and return immediately
        if (cur.?.val == num) return;
        pre = cur;
        // the insertion position is in the right subtree of cur
        if (cur.?.val < num) {
            cur = cur.?.right;
        // the insertion position is in the left subtree of cur
        } else {
            cur = cur.?.left;
        }
    }
    // insert node
    var node = try self.mem_allocator.create(inc.TreeNode(T));
    node.init(num);
    if (pre.?.val < num) {
        pre.?.right = node;
    } else {
        pre.?.left = node;
    }
}
```

Same as looking up a node, inserting a node takes $O(log\,n)$ time.

3. deleting a node

First find the target node in the binary tree, and then delete it from the binary tree.

Similar to inserting a node, we need to ensure that the property of "left subtree < root node < right subtree" of the binary search tree is still satisfied after the deletion operation is completed.

Therefore, according to the number of child nodes of the target node, we need to divide them into three cases: 0, 1 and 2, and perform the corresponding delete node operation.

As shown in the following picture, when the degree of the node to be deleted is $0$, it means that the node is a leaf node and can be deleted directly.

![Fig. 在二叉搜索树中删除节点（度为 0）](./algos/7.4.1.3.1.png)

As shown in the following picture, when the degree of the node to be deleted is $1$, just replace the node to be deleted with its child node.

![Fig. 在二叉搜索树中删除节点（度为 1）](./algos/7.4.1.3.2.png)

When the degree of the node to be deleted is $2$, we cannot delete it directly, but need to replace it with a node. Since the "left $<$ root $<$ right" property of the binary search tree must be maintained, **this node can be the smallest node of the right subtree or the largest node of the left subtree**.

Assuming we choose the smallest node of the right subtree (that is, the next node in the in-order traversal), the deletion operation flow is shown in the following picture.

1. Find the next node in the "in-order traversal sequence" of the node to be deleted, denoted as `tmp`.
2. Overwrite the value of the node to be deleted with the value of `tmp`, and recursively delete the node `tmp` in the tree.

![<1>](./algos/7.4.1.3.3-1.png) ![<2>](./algos/7.4.1.3.3-2.png) ![<3>](./algos/7.4.1.3.3-3.png) ![<4>](./algos/7.4.1.3.3-4.png)

The operation of deleting a node also takes $O(log\,n)$ time. It takes $O(log\,n)$ time to find the node to be deleted, and $O(log\,n)$ time to obtain the successor node of the in-order traversal.

```zig
// delete node
fn remove(self: *Self, num: T) void {
    // f the tree is empty, return immediately early
    if (self.root == null) return;
    var cur = self.root;
    var pre: ?*inc.TreeNode(T) = null;
    // loop search, exit after crossing the leaf node
    while (cur != null) {
        // ind the node to be deleted and exit of the loop
        if (cur.?.val == num) break;
        pre = cur;
        // the node to be deleted is in the right subtree of cur
        if (cur.?.val < num) {
            cur = cur.?.right;
        // the node to be deleted is in the left subtree of cur
        } else {
            cur = cur.?.left;
        }
    }
    // if there is no node to delete, return immediately
    if (cur == null) return;
    // number of child nodes = 0 or 1
    if (cur.?.left == null or cur.?.right == null) {
        // when the number of child nodes = 0 / 1, child = null / the child node
        var child = if (cur.?.left != null) cur.?.left else cur.?.right;
        // delete node cur
        if (pre.?.left == cur) {
            pre.?.left = child;
        } else {
            pre.?.right = child;
        }
    // number of child nodes = 2
    } else {
        // get the next node of cur in in-order traversal
        var tmp = cur.?.right;
        while (tmp.?.left != null) {
            tmp = tmp.?.left;
        }
        var tmp_val = tmp.?.val;
        // recursively delete node tmp
        self.remove(tmp.?.val);
        // overwrite cur with tmp
        cur.?.val = tmp_val;
    }
}
```

4. in-order traversal order

As shown in the following picture the in-order traversal of a binary tree follows the traversal order of "left $\rightarrow$ root $\rightarrow$ right", while the binary search tree satisfies the size relationship of "left child $<$ root node $<$ right child".

This means that when performing an in-order traversal in a binary search tree, the next smallest node is always traversed first, which leads to an important property: **the in-order traversal sequence of a binary search tree is in ascending order**.

Using the ascending nature of inorder traversal, we only need $O(n)$ time to obtain ordered data in the binary search tree, without additional sorting, which is very efficient.

![Fig. 二叉搜索树的中序遍历序列](./algos/7.4.1.4.png)

7.4.2. Efficiency of binary search tree

Given a set of data, we consider using an array or binary search tree storage. Observing the following table, the time complexity of each operation of the binary search tree is logarithmic, with stable and efficient performance. Only in the scenario of high-frequency addition and low-frequency search and deletion of data, arrays are more efficient than binary search trees.

||Unorderd array|Binary search tree|
|---|---|---|
|find element|$(n)$|$O(log\,n)$|
|insert element|$O(1)$|$O(log\,n)$|
|delete element|$O(n)$|$O(log\,n)$|

Ideally, a binary search tree is "balanced" such that any node can be searched in $log\,n$ rounds.

However, if we continuously insert and delete nodes in the binary search tree, it may cause the binary tree to degenerate into a linked list as shown in the following picture, and the time complexity of various operations will also degenerate to $O(n)$.

![Fig. 二叉搜索树的平衡与退化](./algos/7.4.2.png)

7.4.3. Common applications of binary search trees

- Used as a multi-level index in the system to achieve efficient search, insert, and delete operations.
- As an underlying data structure for some search algorithms.
- Used to store streams of data to keep them in an ordered state.

7.5. AVL tree*

In the chapter on binary search tree, we mentioned that after multiple insertion and deletion operations, a binary search tree may degenerate into a linked list. In this case, the time complexity of all operations will deteriorate from $O(log\,n)$ to $O(n)$.

As shown in the following picture, after two node deletion operations, the binary search tree will degenerate into a linked list.

![Fig. AVL 树在删除节点后发生退化](./algos/7.5.0.1.png)

For another example, after inserting two nodes in the following perfect binary tree, the tree will be severely skewed to the left, and the time complexity of the search operation will also deteriorate.

![Fig. AVL 树在插入节点后发生退化](./algos/7.5.0.2.png)

G. M. Adelson-Velsky and E. M. Landis proposed "AVL trees" in their 1962 paper "An algorithm for the organization of information". The paper describes a series of operations in detail to ensure that the AVL tree will not degenerate after continuous addition and deletion of nodes, thus keeping the time complexity of various operations at the $O(log\,n)$ level. In other words, in scenarios where frequent addition, deletion, query, and modification operations are required, the AVL tree can always maintain efficient data operation performance and has good application value.

7.5.1. AVL Tree Common Terms

The "AVL tree" is both a binary search tree and a balanced binary tree, and it satisfies all the properties of these two types of binary trees at the same time, so it is also called "balanced binary search tree".

1. node height

When operating the AVL tree, we need to get the height of the node, so we need to add the height variable to the node class of the AVL tree.

```zig
```

"Node height" refers to the distance from the node to the furthest leaf node, that is, the number of "edges" traversed. It is important to note that leaf nodes have a height of 0 , while empty nodes have a height of -1 . We'll create two utility functions for getting and updating the height of a node, respectively.

```zig
// get node height
fn height(self: *Self, node: ?*inc.TreeNode(T)) i32 {
    _ = self;
    // empty nodes have a height of -1 and leaf nodes have a height of 0
    return if (node == null) -1 else node.?.height;
}

// update node height
fn updateHeight(self: *Self, node: ?*inc.TreeNode(T)) void {
    // node height is equal to highest subtree height + 1
    node.?.height = @max(self.height(node.?.left), self.height(node.?.right)) + 1;
}
```

2. node balance factor

The "Balance Factor" of a node is defined as the height of the left subtree minus the height of the right subtree, and the balance factor of an empty node is 0. We also encapsulate the function of obtaining the node balance factor into a function for subsequent use.

```zig
// get balance factor
fn balanceFactor(self: *Self, node: ?*inc.TreeNode(T)) i32 {
    // empty node balance factor is 0
    if (node == null) return 0;
    // node balance factor = left subtree height - right subtree height
    return self.height(node.?.left) - self.height(node.?.right);
}
```

>**Note**
>If the balance factor is $f$, then the balance factor of any node in an AVL tree satisfies $-1 \le f \le 1$.

7.5.2. AVL tree rotation

The feature of the AVL tree is the "rotation" operation, which can restore the balance of unbalanced nodes without affecting the in-order traversal sequence of the binary tree. In other words, **the rotation operation can not only maintain the "binary search tree" property of the tree, but also make the tree become a "balanced binary tree" again**.

We refer to the nodes with an absolute value of balance factor $>1$ as "unbalanced nodes". Depending on the node imbalance, the rotation operation is divided into four types: right rotation, left rotation, right rotation first and then left rotation, first left rotation and then right rotation. Below we describe these rotation operations in detail.

1. clockwise

As shown in the figure below, below the nodes is the balance factor. From bottom to top, the first unbalanced node in the binary tree is "Node 3". We consider the subtree with the unbalanced node as the root node, record this node as node, and record its left child node as child, and perform the "right rotation" operation. After the clockwise rotation is completed, the subtree has been restored to balance, and still maintains the characteristics of the binary search tree.

![<1>](./algos/7.5.2.1.1-1.png) ![<2>](./algos/7.5.2.1.1-2.png) ![<3>](./algos/7.5.2.1.1-3.png) ![<4>](./algos/7.5.2.1.1-4.png)

In addition, if the node `child` itself has a right child (denoted as `grandChild`), you need to add a step in the "right rotation": make `grandChild` the left child of `node`.

![Fig. 有 grandChild 的右旋操作](./algos/7.5.2.1.2.png)

"Rotating clockwise" is a visual statement, in fact, it needs to be realized by modifying the node pointer, the code is as follows.

```zig
// clockwise rotation
fn rightRotate(self: *Self, node: ?*inc.TreeNode(T)) ?*inc.TreeNode(T) {
    var child = node.?.left;
    var grandChild = child.?.right;
    // with child as the origin, rotate node to the right
    child.?.right = node;
    node.?.left = grandChild;
    // update node height
    self.updateHeight(node);
    self.updateHeight(child);
    // return the root node of the rotated subtree
    return child;
}
```

2. counter clockwise

Correspondingly, if the "mirror image" of the above-mentioned unbalanced binary tree is considered, the "left-rotation" operation shown in the following picture needs to be performed.

![Fig. 左旋操作](./algos/7.5.2.2.1.png)

Similarly, as shown in the following picture, if the node `child` itself has a left child node (denoted as `grandChild`), it is necessary to add a step in the "left rotation": make `grandChild` as the right child node of `node`.

![Fig. 有 grandChild 的左旋操作](./algos/7.5.2.2.2.png)

It can be observed that **the clockwise and counter clockwise operations are logically mirror-symmetrical, and the two imbalances they respectively resolve are also symmetrical**. Based on symmetry, we can easily deduce the left-handed code from the right-handed one. Specifically, you only need to replace all `left` with `right` in the "clockwise" code, and replace all `right` with `left` to get the "counter clockwise" code.

```zig
// counter clockwise operation
fn leftRotate(self: *Self, node: ?*inc.TreeNode(T)) ?*inc.TreeNode(T) {
    var child = node.?.right;
    var grandChild = child.?.left;
    // with child as the origin, rotate node to the left
    child.?.left = node;
    node.?.right = grandChild;
    // update node height
    self.updateHeight(node);
    self.updateHeight(child);
    // return the root node of the rotated subtree
    return child;
}
```

3. First counter clockwise and then clockwise

For the unbalanced node 3 in the following picture, neither left nor right rotation alone can bring the subtree back into balance. At this time, it is necessary to rotate to the left and then to the right, that is, first perform "left rotation" on `child`, and then perform "right rotation" on `node`.

![Fig. 先左旋后右旋](./algos/7.5.2.3.png)

4. Clockwise and then counter clockwise

As shown in the following picture, for the mirror image of the above-mentioned unbalanced binary tree, it is necessary to perform "right rotation" on `child` first, and then perform "left rotation" on `node`.

![Fig. 先右旋后左旋](./algos/7.5.2.4.png)

5. rotation options

The four unbalanced situations shown in the following picture correspond to the above cases one by one, requiring rotation operations of right rotation, left rotation, right first then left, first left then right respectively.

![Fig. AVL 树的四种旋转情况](./algos/7.5.2.5.png)

As shown in the following table, we determine which of the imbalance nodes falls into the case in the previous picture by determining the balance factor of the imbalance node and the positive and negative signs of the balance factor of the higher child node.

|The balance factor of the unbalanced node|The balance factor of the child node|The rotation method that should be used|
|---|---|---|
|$>1$ (left-biased tree)|$\ge0$|clockwise|
|$>1$ (left-biased tree)|$<0$|first turn left then turn right|
|$<-1$ (right-skewed tree)|$\le0$|counter clockwise|
|$<-1$ (right-skewed tree)|$>0$|first turn right then turn left|

For ease of use, we encapsulate the rotation operation into a function. **With this function, we can rotate various unbalanced situations to bring the unbalanced nodes back into balance**.

```zig
// perform a rotation operation to bring the subtree back into balance
fn rotate(self: *Self, node: ?*inc.TreeNode(T)) ?*inc.TreeNode(T) {
    // get the balance factor of node node
    var balance_factor = self.balanceFactor(node);
    // left-biased tree
    if (balance_factor > 1) {
        if (self.balanceFactor(node.?.left) >= 0) {
            // clockwise
            return self.rightRotate(node);
        } else {
            // first rotate left and then right
            node.?.left = self.leftRotate(node.?.left);
            return self.rightRotate(node);
        }
    }
    // right-biased tree
    if (balance_factor < -1) {
        if (self.balanceFactor(node.?.right) <= 0) {
            // counter clockwise
            return self.leftRotate(node);
        } else {
            // first rotate right and then left
            node.?.right = self.rightRotate(node.?.right);
            return self.leftRotate(node);
        }
    }
    // balanced tree, no rotation needed, return immediately
    return node;
}
```

7.5.3. AVL tree common operations

1. inserting a node

The node insertion operation of "AVL tree" is similar to that of "binary search tree" in principle. The only difference is that after a node is inserted in an AVL tree, there may be a series of unbalanced nodes on the path from that node to the root node. Therefore, **we need to start from this node and perform a rotation operation from the bottom up to bring all unbalanced nodes back into balance**.

```zig
// insert node
fn insert(self: *Self, val: T) !void {
    self.root = (try self.insertHelper(self.root, val)).?;
}

// recursively insert nodes (helper method)
fn insertHelper(self: *Self, node_: ?*inc.TreeNode(T), val: T) !?*inc.TreeNode(T) {
    var node = node_;
    if (node == null) {
        var tmp_node = try self.mem_allocator.create(inc.TreeNode(T));
        tmp_node.init(val);
        return tmp_node;
    }
    // 1. Find the insertion position and insert the node
    if (val < node.?.val) {
        node.?.left = try self.insertHelper(node.?.left, val);
    } else if (val > node.?.val) {
        node.?.right = try self.insertHelper(node.?.right, val);
    } else {
        return node;            // duplicate nodes are not inserted and returned directly
    }
    self.updateHeight(node);    // update node height
    // 2. Perform a rotation operation to bring the subtree back into balance
    node = self.rotate(node);
    // return the root node of the subtree
    return node;
}
```

2. deleting a node

Similarly, on the basis of the delete node method of the binary search tree, the rotation operation needs to be performed from the bottom to the top to bring all unbalanced nodes back into balance.

```zig
// delete node
fn remove(self: *Self, val: T) void {
   self.root = self.removeHelper(self.root, val).?;
}

// recursively delete nodes (helper method)
fn removeHelper(self: *Self, node_: ?*inc.TreeNode(T), val: T) ?*inc.TreeNode(T) {
    var node = node_;
    if (node == null) return null;
    // 1. Find the node and delete it
    if (val < node.?.val) {
        node.?.left = self.removeHelper(node.?.left, val);
    } else if (val > node.?.val) {
        node.?.right = self.removeHelper(node.?.right, val);
    } else {
        if (node.?.left == null or node.?.right == null) {
            var child = if (node.?.left != null) node.?.left else node.?.right;
            // number of child nodes = 0, directly delete node and return
            if (child == null) {
                return null;
            // number of child nodes = 1, delete node directly
            } else {
                node = child;
            }
        } else {
            // if the number of child nodes = 2, delete the next node in the in-order traversal
            // and replace the current node with this node
            var temp = node.?.right;
            while (temp.?.left != null) {
                temp = temp.?.left;
            }
            node.?.right = self.removeHelper(node.?.right, temp.?.val);
            node.?.val = temp.?.val;
        }
    }
    self.updateHeight(node); // update node height
    // 2. Perform a rotation operation to bring the subtree back into balance
    node = self.rotate(node);
    // return the root node of the subtree
    return node;
}
```

3. finding a node

The node lookup operation of the AVL tree is consistent with that of the binary search tree, and will not be repeated here.

7.5.4. Typical application of AVL tree

- Organize and store large-scale data, suitable for high-frequency search, low-frequency addition and deletion scenarios.
- Used to build the indexing system of a database.
- Red-black trees are more popular than AVL trees in many applications. This is because the balance condition of the red-black tree is relatively loose, and the rotation operations required to insert and delete nodes in the red-black tree are relatively small, and the average efficiency of node addition and deletion operations is higher.

7.6. summary

- A binary tree is a non-linear data structure that embodies the divide-and-conquer logic of "one divides into two". Each binary tree node contains a value and two pointers to its left and right child nodes.
- For a node in a binary tree, its left (right) child node and the tree formed below it are called the left (right) subtree of the node.
- The related terms of binary tree include root node, leaf node, layer, degree, edge, height and depth etc.
- Binary tree initialization, node insertion and node deletion operations are similar to linked list operations.
- Common binary tree types are perfect binary tree, complete binary tree, full binary tree and balanced binary tree. A perfect binary tree is the most ideal state, while a linked list is the worst state after degradation.
- A binary tree can be represented by an array, by arranging the node values and slots in the order of traversal, and implementing pointers according to the index mapping relationship between parent nodes and child nodes.
- The layer-order traversal of the binary tree is a breadth-first search method, which embodies the hierarchical traversal method of "one circle and one circle outward", and is usually implemented through a queue.
- Pre-order, in-order, and post-order traversals are all depth-first searches, which embody the backtracking traversal method of "going to the end, then going back and continuing", and are usually implemented using recursion.
- A binary search tree is an efficient element lookup data structure, and its lookup, insertion, and deletion operations have a time complexity of $O(log\,n)$. When the binary search tree degenerates into a linked list, the time complexity will be degraded to $O(n)$.
- An AVL tree, also known as a balanced binary search tree, uses a rotation operation to ensure that the tree remains balanced after repeated insertions and deletions of nodes.
- The rotation operations of the AVL tree include right rotation, left rotation, right rotation first and then left rotation, first left rotation and then right rotation. After a node is inserted or deleted, the AVL tree is rotated from bottom to top to bring the tree back into balance.

7.6.1. Q & A

>**For a binary tree with only one node, is the height of the tree and the depth of the root node both $0$?**
>Yes, because height and depth are usually defined as "amount of edge traveled".

>**Insertion and deletion in a binary tree are generally completed by a set of operations. What does the "set of operations" here mean? Can it be understood as the resource release of the child nodes of the resource?**
>Taking a binary search tree as an example, the operation of deleting a node is divided into three cases, each of which requires multiple steps of node operations.

>**Why does DFS have three orders of front, middle and last when traversing a binary tree, and what are the uses of each?**
>The pre-, middle-, and post-order traversals of DFS are similar to the order of accessing arrays. They are the basic methods for traversing binary trees. Using these three traversal methods, we can obtain a specific order of traversal results. For example, in a binary search tree, since the size of the node satisfies `the value of the left child node < the value of the root node < the value of the right child node`, we only need to traverse the tree according to the priority of `left -> root -> right` to get an ordered sequence of nodes.

>**The right-handed operation is to deal with the relationship between unbalanced nodes `node`, `child`, and `grand_child`. Doesn’t the original connection between `node`’s parent node and `node` need to be maintained? Isn't it broken after the right-hand operation?**
>We need to look at this problem from a recursive perspective. The right rotation operation `right_rotate(root)` passes in the root node of the subtree, and finally `return child` returns the root node of the rotated subtree. The connection between the root node of the subtree and its parent node is completed after the function returns, and it does not belong to the maintenance scope of the right rotation operation.

>**In C++, functions are divided into `private` and `public`, is there any consideration in this regard? Why put the `height()` function and `updateHeight()` function in `public` and `private` respectively?**
>It mainly depends on the scope of use of the method. If the method is only used inside the class, then it is designed as `private`. For example, it does not make sense for the user to call `updateHeight()` alone, it is just a step in the insert and delete operations. And `height()` is the access node height, similar to `vector.size()`, so it is set to `public` for easy use.

>**How to build a binary search tree from a set of input data? Is the choice of the root node important?**
>Yes, the way to build the tree is given in the `build_tree()` method in the binary search tree code. As for the selection of the root node, we usually sort the input data, then use the midpoint element as the root node, and recursively build the left and right subtrees. Doing so can ensure the balance of the tree to the greatest extent.

>**In Java, is it necessary to use the `equals()` method for string comparison?**
>In Java, for primitive data types, `==` is used to compare the values of two variables for equality. For reference types, the two notations work differently:
>
>- `==` : Used to compare whether two variables point to the same object, that is, whether their locations in memory are the same.
>- `equals()`: Used to compare whether the values of two objects are equal.
>
>So if we want to compare values, we usually use `equals()`. However, the strings initialized by `String a = "hi"; String b = "hi";` are stored in the string constant pool, and they point to the same object, so `a == b` can also be used to compare two strings Content.

>**Before breadth-first traversal to the bottom, is the number of nodes in the queue $2^h$?**
>Yes, for example, for a full binary tree with height $h=2$, the total number of nodes is $n=7$, and the number of bottom nodes is $4=2^h=(n+1)/2$.

8. heap

>**Abstract**
>The piles are like the peaks of mountains and rivers, they are layered and undulating, with different shapes.
>
>Every mountain has its highs and lows, and the highest peaks are always the first to catch the eye.

8.1. heap

A "Heap" is a complete binary tree that satisfies certain conditions and can be divided into two types:

- "Max Heap", the value of any node $\ge$ the value of its child nodes.
- "Min Heap", the value of any node $\le$ the value of its child nodes.

![Fig. 小顶堆与大顶堆](./algos/8.1.0.png)

As a special case of a complete binary tree, a heap has the following properties:

- The bottommost node is filled to the left, and the nodes of other layers are filled.
- We refer to the root node of the binary tree as the "top of the heap", and the rightmost node at the bottom as the "bottom of the heap".
- For large top heaps (small top heaps), the value of the top element (ie root node) of the heap is the largest (smallest) respectively.

8.1.1. Common Heap Operations¶

It should be pointed out that many programming languages ​​provide "Priority Queue", which is an abstract data structure defined as a queue with priority ordering.

In practice, the heap is often used to implement priority queues, which are equivalent to priority queues in which elements are queued from largest to smallest. From a usage perspective, we can think of "priority queue" and "heap" as equivalent data structures. Therefore, this book does not make a special distinction between the two, and uses the name "heap" uniformly.

The common operations of the heap are shown in the following table, and the method name needs to be determined according to the programming language.

|Method name|Description|Time complexity|
|---|---|---|
|push()|elements into the heap|$O(log\,n)$|
|pop()|heap top element out of heap|$O(log\,n)$|
|peek()|Access the top element of the heap<br>(the largest/smallest values for<br>large/small top heaps respectively)|$O(1)$|
|size()|Get the number of elements in the heap|$O(1)$|
|isEmpty()|Check if the heap is empty|$O(1)$|

In practical applications, we can directly use the heap class (or priority queue class) provided by the programming language

>**Tip**
>Similar to "arrange from small to large" and "arrange from large to small" in the sorting algorithm, we can realize the conversion between "small top heap" and "big top heap" by modifying the Comparator.

```zig
```

8.1.2 implementation of the heap

The following implements the big top heap. To convert it to a small top heap, just invert all size logic estimations (for example, replace $\ge$ with $\le$). Interested readers can do it on their own.

1. Storage and representation of the heap

As we learned in the chapter on binary trees, complete binary trees are well suited to be represented by arrays. Since a heap is exactly a complete binary tree, **we will use an array to store the heap**.

When an array is used to represent a binary tree, the elements represent node values, and the index represents the position of the node in the binary tree. **Node pointers are implemented through an index mapping formula**.

As shown in the following picture, given an index $i$, its left child has index $2i+1$, its right child has index $2i+2$, and its parent has index $(i-1)/2$ (rounded down). When the index is out of range, it means empty node or node does not exist.

![Fig. 堆的表示与存储](./algos/8.1.2.1.png)

We can encapsulate the index mapping formula into a function for subsequent use.

```zig
// get the index of the left child node
fn left(i: usize) usize {
    return 2 * i + 1;
}

// get the index of the right child node
fn right(i: usize) usize {
    return 2 * i + 2;
}

// get parent node index
fn parent(i: usize) usize {
    // return (i - 1) / 2; // 向下整除
    return @divFloor(i - 1, 2);
}
```

2. Access the top element of the heap

The top element of the heap is the root node of the binary tree, which is the first element of the list.

```zig
// access the top element of the heap
fn peek(self: *Self) T {
    return self.max_heap.?.items[0];
}  
```

3. Adding elements into the heap

Given an element `val`, we first add it to the bottom of the heap. After the addition, since `val` may be larger than other elements in the heap, the condition of the heap may have been violated. Therefore, **each node on the path from the inserted node to the root node needs to be repaired**. This operation is called "Heapify".

Consider **performing heapization from the bottom to the top**, starting from the entry node. As shown in the following picture, we compare the value of the inserted node with its parent, and swap them if the inserted node is larger. It then continues to do this, repairing each node in the heap from bottom to top, until it passes the root node or ends when it encounters a node that does not need to be swapped.

![<1>](./algos/8.1.2.3-1.png) ![<2>](./algos/8.1.2.3-2.png) ![<3>](./algos/8.1.2.3-3.png) ![<4>](./algos/8.1.2.3-4.png) ![<5>](./algos/8.1.2.3-5.png) ![<6>](./algos/8.1.2.3-6.png) ![<7>](./algos/8.1.2.3-7.png) ![<8>](./algos/8.1.2.3-8.png) ![<9>](./algos/8.1.2.3-9.png)

If the total number of nodes is $n$, the height of the tree is $log\,n$. It can be seen from this that the maximum number of rounds of heap operations is $O(log\,n)$, and **the time complexity of elements into the heap is $O(log\,n)$**.

```zig
// add element to the heap
fn push(self: *Self, val: T) !void {
    // add node
    try self.max_heap.?.append(val);
    // heaping from bottom to top
    try self.siftUp(self.size() - 1);
}  

// starting from node i, heap from bottom to top
fn siftUp(self: *Self, i_: usize) !void {
    var i = i_;
    while (true) {
        // get the parent node of node i
        var p = parent(i);
        // when "root node is met" or "node does not need to be repaired", end heap
        if (p < 0 or self.max_heap.?.items[i] <= self.max_heap.?.items[p]) break;
        // swap two nodes
        try self.swap(i, p);
        // loop upwards
        i = p;
    }
}
```

4. Taking heap top element out of heap

The top element of the heap is the root node of the binary tree, which is the first element of the list. If we directly remove the first element from the list, then the index of all nodes in the binary tree will change, which will make it difficult to do heap repair later. In order to minimize the change of element index, we take the following steps.

1. Swap the top element of the heap with the bottom element of the heap (that is, swap the root node with the rightmost leaf node).
2. After the exchange is completed, delete the bottom of the heap from the list (note that since the exchange has been performed, the original top element of the heap is actually deleted).
3. Starting from the root node, **perform heapization from top to bottom**.

As shown in the following picture, top-to-bottom heaping operates in the opposite direction of bottom-to-top heaping. We compare the value of the root node with the values of its two children, swap the largest child with the root node; then do this in a loop, until it meets a leaf node or encounters a node that does not need to be exchanged.

![<1>](./algos/8.1.2.4-1.png) ![<2>](./algos/8.1.2.4-2.png) ![<3>](./algos/8.1.2.4-3.png) ![<4>](./algos/8.1.2.4-4.png) ![<5>](./algos/8.1.2.4-5.png) ![<6>](./algos/8.1.2.4-6.png) ![<7>](./algos/8.1.2.4-7.png) ![<8>](./algos/8.1.2.4-8.png) ![<9>](./algos/8.1.2.4-9.png) ![<10>](./algos/8.1.2.4-10.png)

Similar to the operation of adding elements to the heap, the time complexity of the operation of removing elements from the top of the heap is also $O(log\,n)$.

```zig
// take an element out of the heap
fn pop(self: *Self) !T {
    // process decision
    if (self.isEmpty()) unreachable;
    // swap the root node and the rightmost leaf node
    // (that is, swap the first element and the last element)
    try self.swap(0, self.size() - 1);
    // delete node
    var val = self.max_heap.?.pop();
    // heaping from top to bottom
    try self.siftDown(0);
    // return the top element of the heap
    return val;
} 

// starting from node i, heap from top to bottom
fn siftDown(self: *Self, i_: usize) !void {
    var i = i_;
    while (true) {
        // determine the node with the largest value among nodes i, l, r, denoted as ma
        var l = left(i);
        var r = right(i);
        var ma = i;
        if (l < self.size() and self.max_heap.?.items[l] > self.max_heap.?.items[ma]) ma = l;
        if (r < self.size() and self.max_heap.?.items[r] > self.max_heap.?.items[ma]) ma = r;
        // if the node i is the largest or the index l, r is out of bounds, exit
        if (ma == i) break;
        // swap two nodes
        try self.swap(i, ma);
        // loop downwards
        i = ma;
    }
}
```

8.1.3. Heap common applications

- **Priority queue**: The heap is usually used as the preferred data structure to implement the priority queue. The time complexity of its enqueue and dequeue operations is $O(log\,n)$, while the queue building operation is $O(log\,n)$. These operations are very efficient .
- **Heap sorting**: Given a set of data, we can use that to build a heap, and then continuously take elements out of the heap to obtain ordered data. However, we usually use a more elegant way to implement heap sorting, see the subsequent heap sorting chapter for details.
- Obtaining the largest k elements: This is a classic algorithm problem, and it is also a typical application, such as selecting the top 10 news as Weibo hot searches, selecting the top 10 sales items, etc.

8.2. Heap operation

If we want to generate a heap based on an input list, this process is called "heap building".

8.2.1. Building from top to bottom

We first create an empty heap, then traverse the list, and perform a "heap operation" on each element in turn, that is, first add the element to the end of the heap, and then perform "bottom-to-top" heapization on the element.

Whenever an element is put into the heap, the length of the heap is increased by one, so the heap is built "top-down".

Assuming that the number of elements is $n$, the heap operation of each element takes $O(log\,n)$ time, so the time complexity of this heap building method is $O(n\,log\,n)$.

8.2.2. Building from the bottom up

In fact, we can implement a more efficient heap building method, which is divided into two steps.

1. Add all elements of the list unchanged to the heap.
2. Traverse the heap in reverse order (that is, the reverse order of hierarchical traversal), and perform "heaping from top to bottom" for each non-leaf node in turn.

In reverse order traversal, the heap is built "bottom-up", and the following two points need to be understood.

- Since leaf nodes have no children, there is no need to heapify them. The parent of the last node is the last non-leaf node.
- In reverse order traversal, we can ensure that the subtree under the current node has been heaped (already a legal heap), which is a precondition for heaping the current node.

```zig
// construction method, build a heap according to the input list
fn init(self: *Self, allocator: std.mem.Allocator, nums: []const T) !void {
    if (self.max_heap != null) return;
    self.max_heap = std.ArrayList(T).init(allocator);
    // add the list elements unchanged to the heap
    try self.max_heap.?.appendSlice(nums);
    // heapify all nodes except leaf nodes
    var i: usize = parent(self.size() - 1) + 1;
    while (i > 0) : (i -= 1) {
        try self.siftDown(i - 1);
    }
}
```

8.2.3. Complexity Analysis

Next, let's try to calculate the time complexity of the second heap building method.

- Assuming that the number of nodes in a complete binary tree is $n$, the number of leaf nodes is $(n+1)/2$, where $/$ is a downward integer division. Thus the number of nodes to be heaped is $(n-1)/2$.
- In the process of heaping from top to bottom, each node is at most heaped to the leaf node, so the maximum number of iterations is the height $log n$ of the binary tree.

By multiplying the above two, the time complexity of the heap building process can be obtained as $O(log\,n)$. **However, this estimate is not accurate because we do not take into account the fact that the number of nodes at the bottom of a binary tree is much greater than that at the top**.

Let's do a more accurate calculation next. In order to reduce the difficulty of calculation, it is assumed that a "perfect binary tree" with $n$ nodes and height $h$ is given, and this assumption will not affect the correctness of the calculation results.

![Fig. 完美二叉树的各层节点数量](./algos/8.2.3.png)

As shown in the previous picture, the maximum number of iterations of a node "top-to-bottom heaping" is equal to the distance from the node to the leaf node, which is exactly the "node height". Therefore, we can sum the "number of nodes $\times$ node height" of each layer to get **the sum of the heaping iterations of all nodes**.
$$T(h)=2^0h+2^1(h-1)+2^2(h-2)+...+2^{(h-1)}\times1$$
To simplify the above formula, we need to rely on the knowledge of sequence from middle school. First multiply $T(h)$ by $2$ to get:
$$2T(h)=2^1h+2^2(h-1)+2^3(h-2)+...+ 2^h\times1$$
Subtract the above equation $T(h)$ from the next equation $2T(h)$, and get:
$$2T(h)-T(h)=T(h)=-2^0h+2^1+2^2+...+2^{(h-1)}+2^h$$
Observing the above formula, it is found that $T(h)$ is a geometric sequence, and the summation formula can be directly used to obtain the time complexity as:
$$\begin{align*}
T(h)&=2\frac{1-2^h}{1-2}-h\\
&=2^{(h+1)}-h-2\\
&=O(2^h)
\end{align*}$$
Furthermore, the number of nodes of a perfect binary tree with height $h$ is $n=2^{h+1}-1$, and the easy complexity is $O(2^h)=O(n)$. The above calculation shows that **the time complexity of inputting a list and building a heap is $O(n)$, which is very efficient**.

8.3. Top-K questions

>**Question**
>Given an unordered array `nums` of length $n$, return the first $k$ largest elements in the array.

For this problem, we first introduce two more direct solutions, and then introduce the more efficient heap solution.

8.3.1. Method 1: traverse the selection

We can perform the $k$ rounds of traversal shown in the following picture, and extract the $1st$, $2nd$, $...$, $kth$ largest elements in each round, and the time complexity is $O(nk)$.

This method is only applicable to the case of $k \ll n$, because when $k$ is close to $n$, its time complexity tends to be $O(n^2)$, which is very time-consuming.

![Fig. 遍历寻找最大的 k 个元素](./algos/8.3.1.png)

>**Tip**
>When $k=n$, we can get a sequence from large to small, which is equivalent to the "selection sort" algorithm.

8.3.2. Method 2: Sorting

As shown in the following picture, we can sort the array `nums` and return the rightmost $k$ elements in $O(n\,log\,n)$ time complexity.

Obviously, this method "exceeds" the task, because we only need to find the largest $k$ elements without sorting other elements.

![Fig. 排序寻找最大的 k 个元素](./algos/8.3.2.png)

8.3.3. Method Three: Heaping

We can solve the Top-K problem more efficiently based on the heap, as shown in the folowing picture.

1. Initialize a small top heap whose top element is the smallest.
2. Put the first $k$ elements of the array into the heap one by one.
3. Starting from the $k+1th$ element, if the current element is greater than the top element, remove the top element from the heap and put the current element into the heap.
4. After the traversal is completed, the largest $k$ elements are saved in the heap.

![<1>](./algos/8.3.3-1.png) ![<2>](./algos/8.3.3-2.png) ![<3>](./algos/8.3.3-3.png) ![<4>](./algos/8.3.3-4.png) ![<5>](./algos/8.3.3-5.png) ![<6>](./algos/8.3.3-6.png) ![<7>](./algos/8.3.3-7.png) ![<8>](./algos/8.3.3-8.png) ![<9>](./algos/8.3.3-9.png)

A total of $n$ rounds of entering and exiting the heap are performed, and the maximum length of the heap is $k$, so the time complexity is $O(n\,log\,k)$. The efficiency of this method is very high. When $k$ is small, the time complexity tends to $O(n)$; when k is large, the time complexity will not exceed $O(n\,log\,n)$.

In addition, the method is suitable for usage scenarios of dynamic data streams. When continuously adding data, we can continuously maintain the elements in the heap, so as to realize the dynamic update of the maximum $k$ elements.

```zig
[class]{}-[func]{topKHeap}
```

8.4. summary

- The heap is a complete binary tree, which can be divided into a large top heap and a small top heap according to the establishment conditions. The top element of the big (small) top heap is the largest (smallest).
- The definition of a priority queue is a queue with dequeue priority, usually implemented using a heap.
- Common operations on the heap and their corresponding time complexities include: $O(log\,n)$ for elements entering the heap, $O(log\,n)$ for removing the top element from the heap, and $O(1)$ for accessing the top element of the heap.
- Complete binary trees are well suited to be represented by arrays, so we usually use arrays to store heaps.
- The heap operation is used to maintain the properties of the heap, and it is used in both heap entry and heap exit operations.
- The time complexity of inputting $n$ elements and building a heap can be optimized to $O(n)$, which is very efficient.
- Top-K is a classical algorithm problem that can be efficiently solved using a heap data structure with a time complexity of $O(n\,log\,k)$.

8.4.1. Q & A

>**Is the "heap" of data structure and the "heap" of memory management the same concept?**
>The two are not the same concept, they just happen to be called heaps. The heap in computer system memory is part of the dynamic memory allocation that programs can use to store data while they are running. Programs can request a certain amount of heap memory for storing complex structures such as objects and arrays. When the data is no longer needed, the program needs to release the memory to prevent memory leaks. Compared with stack memory, the management and use of heap memory needs to be more cautious. Improper use may lead to problems such as memory leaks and wild pointers.

9. graph

>**Abstract**
>In the journey of life, we are like every node, connected by countless invisible edges.
>
>Every acquaintance and departure leaves a unique mark on this huge network map.

9.1. graph

A "Graph" is a non-linear data structure consisting of "Vertex" and "Edge". We can abstractly represent a graph G as a set of vertices V and a set of edges E. The following example shows a graph with 5 vertices and 7 edges.

$$\begin{align*}
&V=\{1,2,3,4,5\}\\
&E=\{(1,2),(1,3),(1,5),(2,3),(2,4),(2,5),(4,5)\}\\
&G=\{V,E\}
\end{align*}$$

If the vertices are regarded as nodes and the edges are regarded as references (pointers) connecting each node, we can regard the graph as a data structure extended from the linked list. As shown in the following picture, compared with linear relationships (linked lists) and divide-and-conquer relationships (trees), network relationships (graphs) have higher degrees of freedom and thus are more complex.

![Fig. 链表、树、图之间的关系](./algos/9.1.0.png)

9.1.1. Common types of graphs

According to whether the edge has direction, it can be divided into "Undirected Graph" and "Directed Graph" as shown in the following picture.

- In an undirected graph, an edge represents a "two-way" connection between two vertices, such as the "friend relationship" in WeChat or QQ.
- In a directed graph, the edges are directional, that is, the edges in the two directions of $A \rightarrow B$ and $A \leftarrow B$ are independent of each other, such as the relationship between "follow" and "followed" on Weibo or Douyin.

![Fig. 有向图与无向图](./algos/9.1.1.1.png)

According to whether all vertices are connected, it can be divided into "Connected Graph" and "Disconnected Graph".

- For a connected graph, starting from a certain vertex, you can reach any other vertex.
- For a disconnected graph, starting from a vertex, at least one vertex cannot be reached.

![Fig. 连通图与非连通图](./algos/9.1.1.2.png)

We can also add a "weight" variable to the edge to get a "weighted graph" shown in the following picture. For example, in mobile games such as Glory of Kings, the system will calculate the "intimacy" between players based on the common game time, and this intimacy network can be represented by a weighted graph.

![Fig. 有权图与无权图](./algos/9.1.1.3.png)

Graph data structures contain the following common terms.

- "Adjacency": When there is an edge connection between two vertices, the two vertices are said to be "adjacent". In the previous picture, the adjacent vertices of vertex 1 are vertices 2, 3, 5.
- "Path": The sequence of edges passing from vertex A to vertex B is called the "path" from A to B. In the previous picture, the edge sequence 1-5-2-4 is a path from vertex 1 to vertex 4.
- "Degree" indicates the number of edges a vertex has. For a directed graph, "In-Degree" indicates how many edges point to the vertex, and "Out-Degree" indicates how many edges point from the vertex.

9.1.2. graph representation

Common representations of graphs include "adjacency matrix" and "adjacency list". The following uses an undirected graph as an example.

1. adjacency matrix

Assuming that the number of vertices in the graph is n, the "Adjacency Matrix" uses a matrix of nxn size to represent the graph, each row (column) represents a vertex, the matrix element represents an edge, and 1 or 0 represents whether there is an edge between two vertices.

As shown in the following picture, if the adjacency matrix is $M$ and the vertex list is $V$, then the matrix element $M[i][j]=1$ means that there is an edge between the vertex $V[i]$ and the vertex $V[j]$, otherwise $M[i][j]=0$ means there is no edge between the two vertices.

![Fig. 图的邻接矩阵表示](./algos/9.1.2.1.png)

An adjacency matrix has the following properties.

- A vertex cannot be connected to itself, so the main diagonal elements of the adjacency matrix are meaningless.
- For undirected graphs, the edges in both directions are equivalent, and the adjacency matrix is symmetric about the main diagonal.
- A weighted graph can be represented by replacing the elements of the adjacency matrix from $1$, $0$ with weights.

When using an adjacency matrix to represent a graph, we can directly access matrix elements to obtain edges, so the efficiency of adding, deleting, and checking operations is very high, and the time complexity is $O(1)$. However, the space complexity of the matrix is $O(n^2)$, and the memory usage is high.

2. adjacency list

An "Adjacency list" uses $n$ linked lists to represent graphs, and linked list nodes represent vertices. The $ith$ linked list corresponds to the vertex $i$, which stores all the adjacent vertices of the vertex (that is, the vertices connected to the vertex). The following picture shows an example of a graph stored using an adjacency list.

![Fig. 图的邻接表表示](./algos/9.1.2.2.png)

The adjacency list only stores the edges that actually exist, and the total number of edges is usually much smaller than $n^2$, so it is more space efficient. However, in the adjacency list, the edge needs to be found by traversing the linked list, so its time efficiency is not as good as that of the adjacency matrix.

Looking at the previous picture, the adjacency list structure is very similar to the "chained addressing" in the hash table, so we can also use similar methods to optimize efficiency. For example, when the linked list is long, the linked list can be converted into an AVL tree or a red-black tree, thereby optimizing the time efficiency from $O(n)$ to $O(log\,n)$; the linked list can also be converted into a hash table, thereby reducing the time complexity speed down to $O(1)$.

9.1.3. Graph common application

As shown in the following table, many real systems can be modeled by graphs, and the corresponding problems can also be reduced to graph computing problems.

||vertex|edge|graph calculation problem|
|---|---|---|---|
|social network|users|friend relationship|potential friend recommendation|
|metro lines|stations|connectivity between stations|shortest route recommendation|
|solar system|celestial bodies|gravitational interactions between celestial bodies|calculation of planet orbits|

9.2. Graph Basic Operations

The basic operations of graphs can be divided into operations on "edges" and operations on "vertexes". Under the two representation methods of "adjacency matrix" and "adjacency list", the implementation methods are different.

9.2.1. Implementation based on adjacency matrix

Given an undirected graph with n vertices, the implementation of various operations is shown in the following picture.

- **Adding or deleting edges**: Just modify the specified edges directly in the adjacency matrix, using $O(1)$ time. Since it is an undirected graph, it is necessary to update the edges in both directions at the same time.
- **Adding vertices**: Add a row and a column at the end of the adjacency matrix, and fill all $0s$, using $O(n)$ time.
- **Deleting vertices**: Delete a row and a column in the adjacency matrix. The worst case is reached when the first row and first column are deleted, and $(n-1)^2$ elements need to be "moved up to the left", thus using $O(n^2)$ time.
- **Initialization**: Pass in $n$ vertices, initialize the vertex list `vertices` of length $n$, use $O(n)$ time; initialize the `adjMat` of $n \times n$ size, use $O(n^2)$ time.

![Initializing the adjacency matrix](./algos/9.2.1-1.png) ![Adding edge](./algos/9.2.1-2.png) ![Deleting edge](./algos/9.2.1-3.png) ![Adding vertex](./algos/9.2.1-4.png) ![Deleting vertex](./algos/9.2.1-5.png)

The following is the implementation code based on the adjacency matrix representation graph.

```zig
```

9.2.2. Implementation based on adjacency list

Assuming that the total number of vertices of the undirected graph is n and the total number of edges is m, various operations can be realized according to the method shown in the following picture.

- **Adding edge**: Just add an edge at the end of the linked list corresponding to the vertex, using $O(1)$ time. Because it is an undirected graph, edges in both directions need to be added at the same time.
- **Deleting edge**: Find and delete the specified edge in the linked list corresponding to the vertex, using $O(m)$ time. In an undirected graph, edges in both directions need to be deleted at the same time.
- **Adding vertex**: Add a linked list in the adjacency list, and use the new vertex as the head node of the linked list, using $O(1)$ time.
- **Deleting vertex**: It is necessary to traverse the entire adjacency list, delete all edges containing the specified vertex, and use $O(n+m)$ time.
- **Initialization**: Create $n$ vertices and $2m$ edges in adjacency list, takes $O(n+m)$ time.

![Initializing adjacency list](./algos/9.2.2-1.png) ![Add edge](./algos/9.2.2-2.png) ![Delete edge](./algos/9.2.2-3.png) ![Add vertex](./algos/9.2.2-4.png) ![Delete vertex](./algos/9.2.2-5.png)

The following is a code example for implementing a graph based on an adjacency list. Careful students may notice that **we use the `Vertex` node class to represent vertices in the adjacency list**, and there is a reason for doing so.

1. If we choose to distinguish different vertices by vertex value, vertices with duplicate values will not be distinguished.
2. If, as in the case adjacency matrix, we use vertex list index to distinguish different vertices. Then, suppose we want to delete the vertex with index $i$, we need to traverse the entire adjacency list, and subtract $1$ from all the indexes $>i$, which is inefficient.
3. Therefore, we consider introducing the vertex class `Vertex` to make each vertex a unique object. At this time, when deleting a vertex, there is no need to change other vertices.

```zig
[class]{GraphAdjList}-[func]{}
```

9.2.3. Efficiency comparison

Assuming that there are n vertices and m edges in the graph, the following table shows the time and space efficiency comparison between adjacency matrix and adjacency list.

||adjacency matrix|adjacency list(linkedlist)|adjacency list(hashtable)|
|---|---|---|---|
|estimating whether it is adjacent|$O(1)$|$O(m)$|$O(1)$|
|add edge|$O(1)$|$O(1)$|$O(1)$|
|delete edge|$O(1)$|$O(1)$|$O(1)$|
|add vertex|$O(n)$|$O(n)$|$O(1)$|
|delete vertex|$O(n^2)$|$O(n+m)$|$O(n)$|
|memory usage|$O(n^2)$|$O(n+m)$|$O(n+m)$|

Looking at the above table, it seems that the adjacency list (hash table) has the best time and space efficiency. But in fact, it is more efficient to manipulate edges in an adjacency matrix, requiring only one array access or assignment operation. On the whole, the adjacency matrix embodies the principle of "trading space for time", while the adjacency list embodies the principle of "trading time for space".

9.3. graph traversal

A tree represents a "one-to-many" relationship, while a graph has a higher degree of freedom and can represent any "many-to-many" relationship. Therefore, we can think of trees as a special case of graphs. Obviously, **the tree traversal operation is also a special case of the graph traversal operation**.

Both "graph" and "tree" are nonlinear data structures, and both need to use "search algorithm" to implement traversal operations. The graph traversal methods can be divided into two types: "breadth-first traversal" and "depth-first traversal". They are also often referred to as "breadth-first search" and "depth-first search", or BFS and DFS for short.

9.3.1. breadth first traversal

**Breadth-first traversal is a traversal method from near to far. Starting from a certain node, the vertex with the closest distance is always visited first, and expanded layer by layer**. As shown in the following picture, start from the upper left corner vertex, first traverse all adjacent vertices of this vertex, then traverse all adjacent vertices of the next vertex, and so on until all vertices are visited.

![Fig. 图的广度优先遍历](./algos/9.3.1.png)

1. Algorithm implementation

BFS is usually implemented with the help of "queues". The queue has the property of "first in, first out", which is similar to the idea of "near to far" of BFS.

1. Add the traversal start vertex `startVet` to the queue and start the loop.
2. In each iteration of the loop, pop the head vertex and record the access, and then add all the adjacent vertices of this vertex to the tail of the queue.
3. Repeat step `2.` until all vertices are visited and end.

In order to prevent repeated traversal of vertices, we need to use a hash table `visited` to record which nodes have been visited.

```zig
[class]{}-[func]{graphBFS}
```

The code is relatively abstract, it is recommended to refer to the following picture to deepen the understanding.

![<1>](./algos/9.3.1.1-1.png) ![<2>](./algos/9.3.1.1-2.png) ![<3>](./algos/9.3.1.1-3.png) ![<4>](./algos/9.3.1.1-4.png) ![<5>](./algos/9.3.1.1-5.png) ![<6>](./algos/9.3.1.1-6.png) ![<7>](./algos/9.3.1.1-7.png) ![<8>](./algos/9.3.1.1-8.png) ![<9>](./algos/9.3.1.1-9.png) ![<10>](./algos/9.3.1.1-10.png) ![<11>](./algos/9.3.1.1-11.png)

>**Is the sequence of breadth-first traversal unique?**
>Not unique. Breadth-first traversal only requires traversal in the order of "from near to far", and the traversal order of multiple vertices with the same distance is allowed to be arbitrarily disrupted. Taking the above picture as an example, the access order of vertices $1$ and $3$ can be exchanged, and the access order of vertices $2$, $4$ and $6$ can also be exchanged arbitrarily.

2. Complexity Analysis

**Time complexity**: All vertices will be queued and dequeued once, using $O(|V|)$ time; in the process of traversing adjacent vertices, since it is an undirected graph, all edges will be visited twice, using $O(2|E|)$ time; overall takes $O(|V|+|E|)$ time.

**Space complexity**: list `res`, hashtable `visited`, queue `que` with at most $|V|$ vertices, using $O(|V|)$ space.

9.3.2. Depth-first traversal

**Depth-first traversal is a traversal method that goes to the end first, goes back when there is nowhere to go**. As shown in the following picture, start from a the upper left corner vertex, visit an adjacent vertex of the current vertex, return when reaching the end, contniue walking to the end and return, and so on, until all vertex traversal is completed.

![Fig. 图的深度优先遍历](./algos/9.3.2.0.png)

1. Algorithm implementation

This "go to the end + backtrack" algorithmic form is usually implemented based on recursion. Similar to BFS, in DFS we also need to use a hash table `visited` to record the visited vertices to avoid repeated visits to vertices.

```zig
[class]{}-[func]{dfs}

[class]{}-[func]{graphDFS}
```

The algorithm flow of depth-first traversal is shown in the following picture.

- **The straight dashed line represents downward recursion**, indicating that a new recursive method is opened to access new vertices.
- **The curved dotted line represents backtracking upwards**, indicating that the recursive method has returned, backtracking to the position where the recursive method was started.

In order to deepen the understanding, it is recommended to combine the diagram with the code to simulate the entire DFS process in the mind (or draw it with a pen), including when each recursive method is opened and when it returns.

![<1>](./algos/9.3.2.1-1.png) ![<2>](./algos/9.3.2.1-2.png) ![<3>](./algos/9.3.2.1-3.png) ![<4>](./algos/9.3.2.1-4.png) ![<5>](./algos/9.3.2.1-5.png) ![<6>](./algos/9.3.2.1-6.png) ![<7>](./algos/9.3.2.1-7.png) ![<8>](./algos/9.3.2.1-8.png) ![<9>](./algos/9.3.2.1-9.png) ![<10>](./algos/9.3.2.1-10.png) ![<11>](./algos/9.3.2.1-11.png)

>**Is the sequence of depth-first traversal unique?**
>Similar to breadth-first traversal, the order of depth-first traversal sequence is not unique. Given a vertex, it doesn’t matter which direction to explore first, that is, the order of adjacent vertices can be arbitrarily disrupted, and it is all depth-first traversal.
>
>Taking tree traversal as an example, "root $\rightarrow$ left $\rightarrow$ right", "left $\rightarrow$ root $\rightarrow$ right", and "left $\rightarrow$ right $\rightarrow$ root" correspond to pre-order, in-order, and post-order traversal respectively. They show There are three different traversal priorities, but all three belong to depth-first traversal.

2. Complexity Analysis

**Time complexity**: All vertices will be visited once, using $O(|V|)$ time; all edges will be visited twice, using $O(2|E|)$ time; overall use $O(|V|+|E|)$ time.

Space complexity: The list `res`, the hash table `visited` have at most $|V|$ vertices, and the maximum recursion depth is $|V|$, so $O(|V|)$ space is used.

9.4. summary

- A graph consists of vertices and edges and can be represented as a collection of vertices and edges.
- Compared with linear relationship (linked list) and divide-and-conquer relationship (tree), network relationship (graph) has a higher degree of freedom and is therefore more complex.
- The edges of the directed graph have directionality, and any vertex in the connected graph can be reached, and each edge of the weighted graph contains a weight variable.
- The adjacency matrix uses a matrix to represent a graph, each row (column) represents a vertex, matrix elements represent edges, and $1$ or $0$ indicates that there is an edge or no edge between two vertices. The adjacency matrix is very efficient in adding, deleting, and checking operations, but it takes up a lot of space.
- The adjacency list uses multiple linked lists to represent the graph, and the $ith$ linked list corresponds to vertex $i$, in which all adjacent vertices of the vertex are stored. The adjacency list is more space-efficient than the adjacency matrix, but it is less time-efficient due to the need to traverse the linked list to find the edge.
- When the linked list in the adjacency list is too long, it can be converted into a red-black tree or hash table to improve query efficiency.
- From the perspective of algorithm thinking, the adjacency matrix embodies "exchanging space for time", and the adjacency list embodies "exchanging time for space".
- Graphs can be used to model various real-world systems, such as social networks, subway lines, etc.
- A tree is a special case of a graph, and tree traversal is also a special case of graph traversal.
- The breadth-first traversal of the graph is a search method that expands from near to far, layer by layer, and is usually implemented with the help of queues.
- The depth-first traversal of the graph is a search method that goes to the bottom first and backtracks when there is no way to go, and is often implemented based on recursion.

9.4.1. Q & A

>**Is a path defined as a sequence of vertices or a sequence of edges?**
>The definitions of different language versions on Wikipedia are inconsistent: the English version is "a path is a sequence of edges", while the Chinese version is "a path is a sequence of vertices". The following is the original English version: In graph theory, a path in a graph is a finite or infinite sequence of edges which joins a sequence of vertices. In this paper, a path is considered as a sequence of edges, not a sequence of vertices. This is because there may be multiple edge connections between two vertices, and each edge corresponds to a path.

>**In a disconnected graph, are there any points that cannot be traversed?**
>In a disconnected graph, starting from a certain vertex, at least one vertex cannot be reached. Traversing a disconnected graph requires setting multiple starting points to traverse to all connected components of the graph.

>**In the adjacency list, is there any requirement for the vertex order of "all vertices connected to this vertex"?**
>Can be in any order. However, in practical applications, it may be necessary to sort according to specified rules, such as the order in which vertices are added, or the order of vertex values, etc., which can help to quickly find vertices with "extreme values".

10. search

>**Abstract**
>Search is an unknown adventure. We may need to go to every corner of the mysterious space, or we may be able to quickly lock the target.
>
>In this journey of discovery, every exploration may lead to an unexpected answer.

10.1. binary search

"Binary Search" is an efficient search algorithm based on the divide-and-conquer startegy. It takes advantage of the orderliness of the data to reduce the search range by half in each round until the target element is found or the search range is empty.

>**Question**
>Given an array `nums` of length $n$, the elements are arranged in ascending order, and the array does not contain repeated elements. Find and return the index of the element `target` in this array. Returns $-1$ if the array does not contain the element.

![Fig. 二分查找示例数据](./algos/10.1.0.png)

As shown in the following picture, we first initialize the pointers $i=0$ and $j=n-1$, pointing to the first element and the last element of the array respectively, representing the search interval $[0, n-1]$. Note that square brackets denote closed intervals, which contain the boundary values themselves.

Next, loop through the following two steps:

1. Calculate the midpoint index $m=\lfloor(i+k)/2\rfloor$, where $\lfloor\rfloor$ represent the rounding down operation.
2. The size relationship between `nums[m]` and `target` is divided into three situations:
    a. When `nums[m] < target`, it means that `target` is in the interval `[m+1, j]`, so execute $i=m+1$.
    b. When `nums[m] > target`, it means that `target` is in the interval `[i, m-1]`, so execute $j=m-1$.
    c. When `nums[m] = target`, it means that `target` is found, so the index $m$ is returned.

If the array does not contain the target element, the search range will eventually be reduced to empty. In this case $-1$ is returned.

![<1>](./algos/10.1.0-1.png) ![<2>](./algos/10.1.0-2.png) ![<3>](./algos/10.1.0-3.png) ![<4>](./algos/10.1.0-4.png) ![<5>](./algos/10.1.0-5.png) ![<6>](./algos/10.1.0-6.png) ![<7>](./algos/10.1.0-7.png)

It is worth noting that since both $i$ and $j$ are of type `int`, **$i+j$ may exceed the value range of type `int`**. In order to avoid large numbers out of bounds, we usually use the formula $m=\lfloor i+(j-i)/2 \rfloor$ to calculate the midpoint.

```zig
// dichotomy search (double closed interval)
fn binarySearch(comptime T: type, nums: std.ArrayList(T), target: T) T {
    // initialize the double-closed interval [0, n-1], that is,
    // i, j point to the first and last elements of the array, respectively
    var i: usize = 0;
    var j: usize = nums.items.len - 1;
    // loop, exit when the search interval is empty (empty when i > j).
    while (i <= j) {
        var m = i + (j - i) / 2;                // calculate the midpoint index m
        if (nums.items[m] < target) {           // this case states that target is in the interval [m+1, j]
            i = m + 1;
        } else if (nums.items[m] > target) {    // this case states that target is in the interval [i, m-1]
            j = m - 1;
        } else {                                // locate the target element and return its index
            return @intCast(m);
        }
    }
    // target element not found, return -1
    return -1;
}
```

**The time complexity is $O(log n)$**. In a binary cycle, the interval is reduced by half per round and the number of cycles is $log_2n$.

**The space complexity is $O(1)$**. Pointers $i$, $j$ use constant size space.

10.1.1. Interval representation method

In addition to the above-mentioned double-closed intervals, common interval representations include "left-closed-right-open" intervals, defined as $[0, n)$, that is, the left boundary is contained, and the right boundary is not contained. Under this representation, the interval $[i, j]$ is empty when $i=j$.

We can implement a binary search algorithm with the same functionality based on this representation.

```zig
// binary search (left closed, right open)
fn binarySearchLCRO(comptime T: type, nums: std.ArrayList(T), target: T) T {
    // initialize left closed and right open [0, n), that is,
    // i, j point to the first element and last element +1 of the array respectively
    var i: usize = 0;
    var j: usize = nums.items.len;
    // loop, exit when the search range is empty (empty when i = j)
    while (i <= j) {
        var m = i + (j - i) / 2;                // calculate midpoint index m
        if (nums.items[m] < target) {           // this case shows that the target is in the interval [m+1, j)
            i = m + 1;
        } else if (nums.items[m] > target) {    // this case shows that the target is in the interval [i, m)
            j = m;
        } else {                                // find the target element and return its index
            return @intCast(m);
        }
    }
    // if the target element is not found, return -1
    return -1;
}
```

As shown in the following picture, under the two interval representations, the initialization, loop conditions, and interval reduction operations of the binary search algorithm are different.

Since the left and right boundaries in the "double-closed interval" representation are both defined as closed intervals, the operation of pointers $i$ and $j$ to shrink the interval is also symmetrical. This is less error-prone, so it is generally recommended to use the "double-closed interval" writing method.

![Fig. 两种区间定义](./algos/10.1.1.png)

10.1.2. Advantages and limitations

Binary search has better performance in both time and space.

- Binary search is time efficient. Under a large amount of data, the time complexity of logarithmic order has a significant advantage. For example, when the data size $n=2^{20}$, linear search requires $2^{20}=1048576$ cycles, while binary search only needs $log_22^{20}=20$ cycles.
- Binary search requires no extra space. Binary search is more space-efficient than search algorithms that require additional space, such as hash search.

However, binary search is not suitable for all situations, mainly for the following reasons.

- Binary search only works on ordered data. If the input data is out of order, sorting it specifically in order to use binary search is not worth the gain. Because the time complexity of the sorting algorithm is usually $O(n\,log\,n)$, which is higher than both linear search and binary search. For scenarios where elements are frequently inserted, in order to maintain the order of the array, elements need to be inserted at specific positions, and the time complexity is $O(n)$, which is also very expensive.
- Binary search only works on arrays. Binary search requires skippin (non-continuous) access to elements, and the efficiency of skipping access in linked lists is low, so it is not suitable for applications in linked lists or data structures based on linked lists.
- Under small data volumes, the performance of linear search is better. In linear search, only 1 estimation operation is required per round; while in binary search, 1 addition, 1 division, 1 to 3 validation operations, and 1 addition (subtraction) are required, totaling 4 to 6 unit operations; therefore, when the amount of data $n$ is small, linear search is faster than binary search.

10.2. binary search insertion point

Binary search can not only be used to search for the target element, but also has many variants, such as searching for the insertion position of the target element.

10.2.1. The case of no repeated elements

>**Question**
>Given an ordered array `nums` of length n and an element `target`, the array has no duplicate elements. Now insert `target` into the array `nums`, keeping its order. If the element `target` already exists in the array, it is inserted to the left of it. Please return the index of `target` in the array after insertion.

![Fig. 二分查找插入点示例数据](./algos/10.2.1.png)

If you want to reuse the binary search code in the previous section, you need to answer the following two questions.

**Question 1**: When the array contains `target`, is the index of the insertion point the index of the element?

The title requires that the `target` be inserted to the left of equal elements, which means that the newly inserted `target` replaces the original `target`. That is, **when the array contains a `target`, the index of the insertion point is the index of that `target`**.

**Question 2**: When the `target` does not exist in the array, which element's index is the insertion point?

Think further about the binary search process: $i$ moves when `nums[m] < target`, which means that the pointer $i$ is approaching the element greater than or equal to `target`. Similarly, the pointer $j$ is always approaching the elements less than or equal to `target`.

Therefore, at the end of the binary division, there must be: $i$ points to the first element greater than `target`, and $j$ points to the first element smaller than `target`. **It is easy to insert index $i$ when the array does not contain `target`**.

```zig
[class]{}-[func]{binarySearchInsertionSimple}
```

10.2.2. In the case of deuplicate elements

>**Question**
>Based on the previous question, it is stipulated that the array may contain repeated elements, and the rest will remain unchanged.

Assuming that there are multiple `target`s in the array, ordinary binary search can only return the index of one of the `target`s, **but cannot determine how many `target`s are on the left and right of the element**.

The title requires inserting the `target` element to the leftmost, so **we need to find the index of the leftmost `target` in the array**. Preliminary consideration is achieved through the following two steps/

1. Perform a binary search to get the index of any `target`, denoted as $k$.
2. Starting from index $k$, traverse linearly to the left, and return when the leftmost `target` is found.

![Fig. 线性查找重复元素的插入点](./algos/10.2.2.1.png)

This method works, but it involves a linear search, so the time complexity is $O(n)$. This method is inefficient when there are many duplicate `target`s in the array.

Now consider expanding the binary search code. As shown in the following picture, the overall process remains unchanged. In each round, the midpoint index $m$ is calculated first, and then the relationship between `target` and `nums[m]` is evaluated.

1. When `nums[m] < target` or `nums[m] > target`, it means that the target has not been found yet, so the narrowing interval operation of ordinary binary search is used **thereby makes the pointers $i$ and $j$ move closer to the `target`.**.
2. When `nums[m] == target`, it means that the elements smaller than target are in the interval $[i,m-1]$, so $j=m-1$ is used to narrow the interval, **thus the pointer $j$ approaches the elements smaller than `target`**.

After the loop is complete, $i$ points to the leftmost `target` and $j$ points to the first element smaller than `target`, **so index $i$ is the insertion point**.

![<1>](./algos/10.2.2.2-1.png) ![<2>](./algos/10.2.2.2-2.png) ![<3>](./algos/10.2.2.2-3.png) ![<4>](./algos/10.2.2.2-4.png) ![<5>](./algos/10.2.2.2-5.png) ![<6>](./algos/10.2.2.2-6.png) ![<7>](./algos/10.2.2.2-7.png) ![<8>](./algos/10.2.2.2-8.png)

Observe the following code, it is verified that the operations of branches `nums[m] > target` and `nums[m] == target` are the same, so the two can be merged.

Even so, we can still keep the verification condition expanded, because its logic is clearer and more readable.

```zig
[class]{}-[func]{binarySearchInsertion}
```

>**Tip**
>The codes in this section are all written in the "double-closed interval". Interested readers can realize the "left closed and right open" writing method by themselves.

In general, binary search is nothing more than setting search targets for pointers $i$ and $j$ respectively. The target may be a specific element (such as `target`) or a range of elements (such as elements smaller than `target`).

In the continuous dichotomy cycle, the pointers $i$ and $j$ are gradually approaching the preset target. Eventually, they either succeed in finding the answer, or stop after crossing the boundary.

10.3. binary search boundary

10.3.1. find left border

>**Question**
>Given an ordered array `nums` of length $n$, the array may contain duplicate elements. Please return the index of the leftmost element `target` in the array. Returns $-1$ if the element is not contained in the array.

Recall the method of binary search for the insertion point. After the search is completed, $i$ points to the leftmost `target`, **so finding the insertion point is essentially looking for the index of the leftmost `target`**.

Consider finding the left boundary implemented by a function that finds the insertion point. Please note that `target` may not be included in the array, this situation can lead to the following two results.

1. The index $i$ of the insertion point is out of bounds.
2. Element `nums[i]` is not equal to `target`.

When encountering the above two situations, just return $-1$ directly.

```zig
[class]{}-[func]{binarySearchLeftEdge}
```

10.3.2. find right border

So how to find the rightmost `target`? The most straightforward way is to modify the code and replace the pointer shrinking operation in the case of `nums[m] == target`. The code is omitted here, and interested students can implement it by themselves.

Below we introduce two more clever methods.

1. Reuse Find Left Boundary

In fact, we can use the function of finding the leftmost element to find the rightmost element **by converting finding the rightmost `target` to finding the leftmost `target + 1`**.

As shown in the following picture, after the search is complete, the pointer $i$ points to the leftmost `target + 1` (if it exists), and $j$ points to the rightmost `target`, so just return $j$.

![Fig. 将查找右边界转化为查找左边界](./algos/10.3.2.1.png)

Note that the returned insertion point is $i$, so you need to subtract $1$ from it to get $j$.

```zig
[class]{}-[func]{binarySearchRightEdge}
```

2. Convert to lookup element

We know that when the array does not contain `target`, $i$ and $j$ will point to the first element greater than and less than `target` respectively.

So, as shown in the following picture, we can construct an element that does not exist in the array to find the left and right boundaries.

- **Find the leftmost target**: it can be converted to find `target - 0.5` and return the pointer $i$.
- **Find the rightmost target**: it can be converted to find `target + 0.5` and return the pointer $j$.

![Fig. 将查找边界转化为查找元素](./algos/10.3.2.2.png)

The code is omitted here, but it is worth noting the following two points.

- The given array does not contain decimals, which means we don't have to worry about how to handle equality cases.
- Because the method introduces decimals, you need to change the variable `target` in the function to a float type.

10.4. Hash optimization strategy

In algorithm problems, **we often reduce the time complexity of the algorithm by replacing linear search with hash search**. We use an algorithm problem to deepen our understanding.

>**Question**
>Given an integer array `nums` and a target element `target`, search the array for two elements whose "sum" is `target` and return their array indices. Return any solution.

10.4.1. Linear search: trading time for space

Consider iterating over all possible combinations directly. As shown in the following picture, we start a two-level loop, and in each round determine whether the sum of two integers is target, and if so, return their indexes.

![Fig. 线性查找求解两数之和](./algos/10.4.1.png)

```zig
// method 1: brute force enumeration
fn twoSumBruteForce(nums: []i32, target: i32) ?[2]i32 {
    var size: usize = nums.len;
    var i: usize = 0;
    // two-level loop, time complexity O(n^2)
    while (i < size - 1) : (i += 1) {
        var j = i + 1;
        while (j < size) : (j += 1) {
            if (nums[i] + nums[j] == target) {
                return [_]i32{@intCast(i), @intCast(j)};
            }
        }
    }
    return null;
}
```

The time complexity of this method is $O(n^2)$ and the space complexity is $O(1)$, which is very time-consuming under large amount of data.

10.4.2. Hash Lookup: Trading Space for Time

Consider a hash table, where the key-value pairs are array elements and element indices, respectively. Loop through the array, executing the steps shown in the following picture each rund.:

1. Determine whether the number `target - nums[i]` is in the hash table, and if so, directly return the indexes of these two elements.
2. Add the key-value pair `nums[i]` and index `i` to the hash table.

![<1>](./algos/10.4.2-1.png) ![<2>](./algos/10.4.2-2.png) ![<3>](./algos/10.4.2-3.png)

The implementation code is as follows, only a single layer of loop is required.

```zig
// method 2: auxiliary hash table
fn twoSumHashTable(nums: []i32, target: i32) !?[2]i32 {
    var size: usize = nums.len;
    // auxiliary hash table, space complexity O(n)
    var dic = std.AutoHashMap(i32, i32).init(std.heap.page_allocator);
    defer dic.deinit();
    var i: usize = 0;
    // single-level loop, time complexity O(n)
    while (i < size) : (i += 1) {
        if (dic.contains(target - nums[i])) {
            return [_]i32{dic.get(target - nums[i]).?, @intCast(i)};
        }
        try dic.put(nums[i], @intCast(i));
    }
    return null;
}
```

This method reduces the time complexity from $O(n^2)$ to $O(n)$ through hash lookup, greatly improving operating efficiency.

Since an additional hash table needs to be maintained, the space complexity is $O(n)$. **Nevertheless, the overall space-time efficiency of this method is more balanced, so it is the optimal solution for this problem**.

10.5. recognizable search algorithm

A "Searching Algorithm" is used to search a data structure (such as an array, linked list, tree or graph) for an element or a group of elements that meet certain conditions.

According to the implementation idea, the search algorithms can be generally divided into two types.

- **Locate the target element by traversing the data structure**, such as the traversal of arrays, linked lists, trees and graphs, etc.
- **Utilize the data organization structure or the prior information contained in the data to realize efficient element search**, such as binary search, hash search and binary tree search, etc.

It is not difficult to find that these knowledge points have been introduced in the previous chapters, so the search algorithm is not unfamiliar to us. In this section, we revisit search algorithms from a more systematic perspective.

10.5.1. brute force search

Brute force search locates the target element by traversing each element of the data structure.

- "Linear Search" is suitable for linear data structures such as arrays and linked lists. It starts at one end of the data structure and visits elements one by one until it finds the target element or reaches the other end without finding the target element.
- "Breadth-first search" and "depth-first search" are two traversal strategies for graphs and trees. Breadth-first search starts from the initial node to search layer by layer, and visits each node from near to far. Depth-first search starts from the initial node, walks along a path to the end, and then backtracks and tries other paths until the entire data structure is traversed.

The advantage of brute force search is that it is simple and versatile, **without preprocessing the data and using additional data structures**.

However, **the time complexity of such algorithms is $O(n)$**, where $n$ is the number of elements, so the performance is poor when the amount of data is large.

10.5.2. adaptive search

Adaptive search takes advantage of unique properties of the data, such as order, to optimize the search process to locate target elements more efficiently.

- "Binary search" uses the order of data to achieve efficient search, which is only applicable to arrays.
- "Hash lookup" uses a hash table to establish a key-value pair mapping between search data and target data and implement query operations.
- "Tree Search" quickly excludes nodes based on comparing node values in a specific tree structure (such as a binary search tree) to locating the target element.

The advantage of this type of algorithm is high efficiency, and **the time complexity can reach $O(log\,n)$ or even $O(1)$**.

However, **using these algorithms often requires preprocessing of the data**. For example, binary search requires the array to be sorted in advance, hash search and tree search both require additional data structures, and maintaining these data structures also requires additional time and space expenses.

>**Note**
>Adaptive search algorithms, often referred to as lookup algorithms, **focus on quickly retrieving target elements in specific data structures**.

10.5.3. Search Method Selection

Given a set of data of size $n$, we can use linear search, binary search, tree search, hash search and other methods to search for a target element in this data. The working principle of each method is shown in the following picture.

![Fig. 多种搜索策略](./algos/10.5.3.png)

The operational efficiency and characteristics of the above methods are shown in the table below.

||Linear Search|Binary Search|Tree Search|Hash Search|
|---|---|---|---|---|
|find element|$O(n)$|$O(log\,n)$|$O(log\,n)$|$O(1)$|
|insert element|$O(1)$|$O(n)$|$O(log\,n)$|$O(1)$|
|delete element|$O(n)$|$O(n)$|$O(log\,n)$|$O(1)$|
|extra space|$O(1)$|$O(1)$|$O(n)$|$O(n)$|
|data preprocessing|$/$|to sort $O(n\,log\,n)$|build a tree $O(n\,log\,n)$|build hash table $O(n)$|
|is the data in order|disorderd|ordered|ordered|disorderd|

The choice of search algorithm also depends on the data volume, search performance requirements, data query and update frequency, etc.

**linear search**

- Good versatility, without any data preprocessing operations. If we only need to query the data once, the data preprocessing time of the other three methods is longer than that of linear search.
- Applicable to data with a small volume, in which case the time complexity has little impact on efficiency.
- Suitable for scenarios with high data update frequency, because this method does not require any additional maintenance of the data.

**binary search**

- Applicable to the situation of large amount of data, the efficiency performance is stable, and the worst time complexity is $O(log\,n)$.
- The amount of data cannot be too large, because storing an array requires continuous memory space.
- It is not suitable for scenarios where data is added or deleted frequently, because the overhead of maintaining an ordered array is high.

**hash lookup**

- Suitable for scenarios with high query performance requirements, the average time complexity is $O(1)$.
- Not suitable for scenarios that require ordered data or range lookups, because hash tables cannot maintain the orderliness of data.
- High dependence on hash functions and hash collision processing strategies, with a greater risk of performance degradation.
- Not suitable for large data volumes, as hash tables require additional space to minimize collisions and thus provide good query performance.

tree search

- Suitable for massive data, because tree nodes are stored discretely in memory.
- Suitable for scenarios where you need to maintain ordered data or range lookups.
- In the process of continuously adding and deleting nodes, the binary search tree may become skewed, and the time complexity is degraded to $O(n)$.
- If an AVL tree or red-black tree is used, each operation can run stably with $O(log\,n)$ efficiency, but the operation of maintaining tree balance will increase additional overhead.

10.6. Summary

- Binary search relies ipon the orderliness of the data, and searches by gradually reducing the search interval by half through a loop. It requires that the input data is ordered and is only applicable to arrays or data structures implemented based on arrays.
- Brute force searches locate data by traversing data structures. Linear search works on arrays and linked lists, and breadth-first and depth-first searches work on graphs and trees. This type of algorithm has good versatility and does not need to preprocess the data, but the time complexity is $O(n)$.
- Hash search, tree search, and binary search are efficient search methods for quickly locating a target element in a specific data structure. This type of algorithm is efficient, and the time complexity can reach $O(log\,n)$ or even $O(1)$, but usually requires the help of additional data structures.
- In practice, we need to conduct a specific analysis of factors such as data volume, search performance requirements, data query and update frequency, so as to choose an appropriate search method.
- Linear search is suitable for small or frequently updated data; binary search is suitable for large, sorted data; hash search is suitable for data that requires high query efficiency and does not require range queries; tree search is suitable for large dynamic data that needs to maintain order and support range queries.
- Replacing linear lookups with hash lookups is a commonly used strategy to optimize runtime, which can reduce the time complexity from $O(n)$ to $O(1)$.

11. sorting

>**Abstract**
>Sorting is like a magic key that turns chaos into order, enabling us to understand and process data in a more efficient way.
>
>Whether it is a simple ascending order or a complex classification arrangement, sorting shows us the harmonious beauty of data.

11.1. Sorting Algorithm

"Sorting Algorithm" is used to arrange a set of data in a specific order. Sorting algorithms have a wide range of applications because ordered data can often be found, analyzed, and processed more efficiently.

As shown in the following picture, the data type in sorting algorithms can be integers, floating point numbers, characters or strings, etc. The ordering evaluation rules can be set according to needs, such as number size, character ASCII code order or custom rules.

![Fig. 数据类型和判断规则示例](./algos/11.1.0.png)

11.1.1. Evaluation dimension

**Operational efficiency**: We expect the time complexity of the sorting algorithm to be as low as possible, and the overall number of operations to be small (i.e., the constant term in the time complexity is reduced). For large volumes of data, operating efficiency is particularly important.

**In-place**: As the name suggests, "in-place sorting" achieves sorting by directly operating on the original array without resorting to additional auxiliary arrays, thereby saving memory. Typically, in-place sorting requires less data moves and runs faster.

**Stability**: "Stable sorting" means that the relative order of equal elements in the array does not change after sorting is completed.

Stable sorting is a necessary condition for multi-level sorting scenarios. Suppose we have a table that stores student information. Column 1 and column 2 are name and age respectively. In this case, "unstable sorting" may lead to the loss of the orderliness of the input data.

```none
# input data is sorted by name
# (name, age)
  ('A', 19)
  ('B', 18)
  ('C', 21)
  ('D', 19)
  ('E', 23)

# assuming a non-stable sorting algorithm is used to sort the list by
# age, the relative position of ('D', 19) and ('A', 19) in the result changes, 
# and the nature of the input data sorted by name is lost.
  ('B', 18)
  ('D', 19)
  ('A', 19)
  ('C', 21)
  ('E', 23)
```

**Adaptability**: The time complexity of "adaptive sorting" will be affected by the input data, that is, the best, worst, and average time complexities are not exactly equal.

Adaptability needs to be assessed on a case-by-case basis. If the worst time complexity is worse than the average time complexity, it means that the performance of the sorting algorithm may be degraded under some data, so it is regarded as a negative attribute; and if the best time complexity is better than the average time complexity, it is regarded as positive attributes.

**Whether it is based on comparison**: "Comparison-based sorting" relies on comparison operators ($<$, $=$, $>$) to determine the relative order of elements to sort the entire array. The theoretical optimal time complexity is $O(n\,log\,n)$. The "non-comparative sorting" does not use comparison operators, and the time complexity can reach $O(n)$, but its versatility is relatively poor.

11.1.2. ideal sorting algorithm

**It runs fast, in situ, is stable, forward adaptive, and has good versatility**. Apparently, no sorting algorithm that combines all the above properties has been found so far. Therefore, when choosing a sorting algorithm, the decision must be made based on specific data characteristics and problem requirements.

Next, we will learn together various sorting algorithms, and analyze the advantages and disadvantages of each sorting algorithm based on the above evaluation dimensions.

11.2. selection sort

The working principle of "Selection Sort" is very straightforward: start a loop, select the smallest element from the unsorted interval each round, and put it at the end of the sorted interval.

Assuming the length of the array is $n$, the algorithm flow of the selection sort is as shown in the following picture.

1. In the initial state, all elements are unsorted, that is, the unsorted (index) interval is $[0,n-1]$.
2. Select the smallest element in the interval $[0,n-1]$ and exchange it with the element at index $0$. When done, the first element of the array is sorted.
3. Select the smallest element in the interval $[1,n-1]$ and exchange it with the element at index $1$. When done, the first 2 elements of the array are sorted.
4. And so on. After $n-1$ rounds of selection and exchange, the first $n-1$ elements of the array are sorted.
5. The only remaining element must be the largest element and does not need to be sorted, so the array sorting is complete.

![<1>](./algos/11.2.0-1.png) ![<2>](./algos/11.2.0-2.png) ![<3>](./algos/11.2.0-3.png) ![<4>](./algos/11.2.0-4.png) ![<5>](./algos/11.2.0-5.png) ![<6>](./algos/11.2.0-6.png) ![<7>](./algos/11.2.0-7.png) ![<8>](./algos/11.2.0-8.png) ![<9>](./algos/11.2.0-9.png) ![<10>](./algos/11.2.0-10.png) ![<11>](./algos/11.2.0-11.png)

In the code, we use $k$ to record the smallest element in the unsorted interval.

```zig
[class]{}-[func]{selectionSort}
```

11.2.1. Algorithm characteristics

- **Time complexity is $O(n^2)$, non-adaptive sorting**: the outer loop has $n-1$ rounds, the length of the unsorted interval in the first round is $n$, and the length of the unsorted interval in the last round is $2$, that is, the outer loop of each round Contains $n$, $n-1$, $...$, $3$, $2$ inner loops respectively, and the sum is $\frac{(n-1)(n+2)}{2}$.
- **Space complexity $O(1)$, in-place sorting**: pointers $i$, $j$ use constant size extra space.
- **Unstable sorting**: as shown in the following picture, element `nums[i]` may be exchanged to the right of its equal element, causing the relative order of the two to change.

![Fig. 选择排序非稳定示例](./algos/11.2.1.png)

11.3 Bubble Sort

"Bubble Sort" achieves sorting by continuously comparing and exchanging adjacent elements. This process is like bubbles rising from the bottom to the top, hence the name bubble sort.

As shown in the following picture, the bubbling process can be simulated using the element swapping operation: traverse from the far left of the array, compare the size of adjacent elements in turn, and swap them if "left element > right element". When the traversal is complete, the largest element is moved to the far right of the array.

![<1>](./algos/11.3.0-1.png) ![<2>](./algos/11.3.0-2.png) ![<3>](./algos/11.3.0-3.png) ![<4>](./algos/11.3.0-4.png) ![<5>](./algos/11.3.0-5.png) ![<6>](./algos/11.3.0-6.png) ![<7>](./algos/11.3.0-7.png)

11.3.1. Algorithmic process

Assuming the length of the array is $n$, the steps of bubble sorting are shown in the following picture.

1. First, perform "bubbling" on $n$ elements, **swap the largest element of the array to the correct position**,
2. Next, perform "bubbling" on the remaining $n-1$ elements, and s**wap the second largest element to the correct position**.
3. By analogy, after $n-1$ rounds of "bubbling", **the first $n-1$ largest elements are swapped to the correct position**.
4. The only remaining element must be the smallest element and does not need to be sorted, so the array sorting is complete.

![Fig. 冒泡排序流程](./algos/11.3.1.png)

```zig
// bubble sort
fn bubbleSort(nums: []i32) void {
    // outer loop: the unsorted interval is [0, i]
    var i: usize = nums.len - 1;
    while (i > 0) : (i -= 1) {
        var j: usize = 0;
        // inner loop: Swap the largest element in the unsorted
        // interval [0, i] to the right end of the interval
        while (j < i) : (j += 1) {
            if (nums[j] > nums[j + 1]) {
                // swap nums[j] with nums[j + 1]
                var tmp = nums[j];
                nums[j] = nums[j + 1];
                nums[j + 1] = tmp;
            }
        }
    }
}
```

11.3.2. efficiency optimization

We found that if no swap operation is performed in a certain round of "bubbling", it means that the array has been sorted and the result can be returned directly. Therefore, you can add a `flag` to monitor this situation, and return immediately once it occurs.

After optimization, the worst and average time complexities of bubble sorting are still $O(n^2)$; but when the input array is completely ordered, the best time complexity $O(n)$ can be achieved.

```zig
// bubble sort (flag optimization)
fn bubbleSortWithFlag(nums: []i32) void {
    // outer loop: the unsorted interval is [0, i]
    var i: usize = nums.len - 1;
    while (i > 0) : (i -= 1) {
        var flag = false;   // flag initialization
        var j: usize = 0;
        // 内循环：将未排序区间 [0, i] 中的最大元素交换至该区间的最右端 
        while (j < i) : (j += 1) {
            if (nums[j] > nums[j + 1]) {
                // swap nums[j] with nums[j + 1]
                var tmp = nums[j];
                nums[j] = nums[j + 1];
                nums[j + 1] = tmp;
                flag = true;
            }
        }
        if (!flag) break;   // this round of bubbling does not swap any elements and exits directly
    }
}
```

11.3.3. Algorithm characteristics

- **The time complexity is $O(n^2)$, adaptive sorting**: the array lengths of each round of "bubble" traversal are $n-1$, $n-2$, .$..$, $2$, $1$, and the sum is $(n-1)n /2$. After introducing `flag` optimization, the optimal time complexity can reach $O(n)$.
- **Space complexity is $O(1)$, in-place sorting**: pointers $i$, $j$ use constant size extra space.
- **Stable sorting**: no swap occurs due to equal elements encountered in "bubbling".

11.4. insertion sort

"Insertion Sort" is a simple sorting algorithm that works much like the process of manually sorting a deck of cards.

Specifically, we select a reference element in the unsorted interval, compare the size of the element with the elements in the sorted range to the left one by one, and insert the element into the correct position.

The following picture shows the operation process of inserting elements into the array. Assuming the base element is `base`, we need to move all elements between the target index and `base` one position to the right, and then assign `base` to the target index.

![Fig. 单次插入操作](./algos/11.4.0.png)

11.4.1. Algorithmic process

The overall process of insertion sort is shown in the following picture.

1. In the initial state, the first element of the array has been sorted.
2. Select the second element of the array as `base` and insert it into the correct position, **the first two elements of the array are sorted**.
3. Select the 3rd element as `base` and insert it in the correct position, **the first 3 elements of the array are sorted**.
4. By analogy, in the last round, the last element is selected as the `base`, and after inserting it in the correct position, **all elements are sorted**.

![Fig. 插入排序流程](./algos/11.4.1.png)

```zig
// insertion sort
fn insertionSort(nums: []i32) void {
    // outer loop: the number of sorted elements is 1, 2, ..., n
    var i: usize = 1;
    while (i < nums.len) : (i += 1) {
        var base = nums[i];
        var j: usize = i;
        // inner loop: insert base into the correct position of the sorted section
        while (j >= 1 and nums[j - 1] > base) : (j -= 1) {
            nums[j] = nums[j - 1];  // 将 move nums[j] one position to the right
        }
        nums[j] = base;             // assign base to the correct location
    }
}
```

11.4.2. Algorithmic characteristics

- **Time complexity $O(n^2)$, adaptive sorting**: in the worst case, each insertion operation needs to loop $n-1$, $n-2$, $..$, $2$, $1$ times, and the sum is $(n-1)n/2$, so the time complexity is $O(n^2)$. Insert operations are terminated early when ordered data is encountered. Insertion sort achieves optimal time complexity $O(n)$ when the input array is completely sorted.
- **Space complexity $O(1)$, in-place sorting**: pointers $i$, $j$ use constant size extra space.
- **Stable sorting**: during an insertion operation, we will insert elements to the right of equal elements without changing their order.

11.4.3. Insertion sort advantage

The time complexity of insertion sort is $O(n^2)$, and the time complexity of quick sort, which we are about to learn, is $O(n\,log\,n)$. Although the time complexity of insertion sort is higher than that of quick sort, **insertion sort is usually faster when the amount of data is small**.

This conclusion is similar to the conclusion for the applicable cases of linear search and binary search. $O(n\,log\,n)$ algorithms such as quick sort are divide-and-conquer-based sorting algorithms, which often include more unit calculation operations. When the amount of data is small, the values ​​of $n^2$ and $n\,log\,n$ are relatively close, and the complexity does not play a dominant role; the number of unit calculation operations in each round plays a decisive factor.

In fact, the built-in sorting functions of many programming languages ​​(such as Java) use insertion sorting. The general idea is: for long arrays, use a sorting algorithm based on divide and conquer, such as quick sort; for short arrays, use insertion sorting directly.

Although the time complexity of bubble sort, selection sort and insertion sort is $O(n^2)$, in practice, insertion sort is used significantly more frequently than bubble sort and selection sort, mainly for the following reasons.

- Bubble sorting is implemented based on element swapping and requires the use of a temporary variable, involving a total of 3 unit operations; insertion sorting is based on element assignment and only requires 1 unit operation. Therefore, **bubble sort is usually more computationally expensive than insertion sort**.
- The time complexity of selection sort is $O(n^2)$ in any case. **Given a partially ordered set of data, insertion sort is usually more efficient than selection sort**.
- Selection sort is unstable and cannot be applied to multilevel sorting.

11.5. quick sort

"Quick Sort" is a sorting algorithm based on the divide-and-conquer strategy, which is efficient and widely used.

The core operation of quicksort is "pivot partitioning", and its goal is to select an element in the array as the "reference number", move all elements smaller than the reference number to its left, and move elements larger than the reference number to its right. Specifically, the pivot division process is shown in the folowing picture.

1. Select the leftmost element of the array as the reference number, and initialize two pointers $i$ and $j$ to point to the two ends of the array respectively.
2. Set up a loop, use `i` (`j`) in each round to find the first element that is larger (smaller) than the reference number, and then swap the two elements.
3. Repeat step `2.` until `i` and `j` meet then stop, and finally swap the reference number to the dividing line of the two sub-arrays.

![<1>](./algos/11.5.0-1.png) ![<2>](./algos/11.5.0-2.png) ![<3>](./algos/11.5.0-3.png) ![<4>](./algos/11.5.0-4.png) ![<5>](./algos/11.5.0-5.png) ![<6>](./algos/11.5.0-6.png) ![<7>](./algos/11.5.0-7.png) ![<8>](./algos/11.5.0-8.png) ![<9>](./algos/11.5.0-9.png)

After the pivot division is completed, the original array is divided into three parts: left sub-array, reference number, and right sub-array, and "any element of the left sub-array $\le$ reference number $\le$ any element of the right sub-array". So we next just need to sort those two subarrays.

>**Divide and conquer idea of quick sort**
>The essence of pivot partition is to simplify the sorting problem of one longer array into the sorting problem of two shorter arrays.

```zig
// element swap
fn swap(nums: []i32, i: usize, j: usize) void {
    var tmp = nums[i];
    nums[i] = nums[j];
    nums[j] = tmp;
}

// pivot partitioning
fn partition(nums: []i32, left: usize, right: usize) usize {
    // use nums[left] as the base number
    var i = left;
    var j = right;
    while (i < j) {
        while (i < j and nums[j] >= nums[left]) j -= 1; // from right to left, find the first element 
                                                        // that is less than the base number
        while (i < j and nums[i] <= nums[left]) i += 1; // from left to right, find the first element
                                                        // that is greater than the base number
        swap(nums, i, j);   // swap these two elements
    }
    swap(nums, i, left);    // swap the base number to the dividing line of the two subarrays
    return i;               // return the index of the base number
}
```

11.5.1. Algorithmic process

The overall flow of quicksort is shown in the following picture

1. First, perform a "pivot partition" on the original array to obtain the unsorted left sub-array and right sub-array.
2. Then, recursively perform "pivot partition" on the left sub-array and the right sub-array respectively.
3. Continue to recurse until the length of the sub-array is 1, thus completing the sorting of the entire array.

![Fig. 快速排序流程](./algos/11.5.1.png)

```zig
// quicksort
fn quickSort(nums: []i32, left: usize, right: usize) void {
    // end recursion when the subarray length is 1
    if (left >= right) return;
    // pivot partitioning
    var pivot = partition(nums, left, right);
    // recurse left subarray, right subarray
    quickSort(nums, left, pivot - 1);
    quickSort(nums, pivot + 1, right);
}
```

11.5.2. Algorithm characteristics

- **Time complexity $O(n\,log\,n)$, adaptive sorting**: In the average case, the number of recursive layers of the pivot partition is $log\,n$, and the total number of cycles in each layer is $n$, and the overall time is $O(n\,log\,n)$. In the worst case, each round of pivot division divides an array of length $n$ into two sub-arrays of length $0$ and $n-1$. At this time, the number of recursive layers reaches $n$ layers, and the number of cycles in each layer is $n$. Overall using $O(n^2)$ time.
- **Space complexity $O(n)$, in-place sorting**: When the input array is completely reversed, the worst recursion depth $n$ is reached, using $O(n)$ stack frame space. The sorting operation is performed on the original array without the help of an additional array.
- **Unstable sort**: In the last step of pivot division, the base numbers may be swapped to the right of equal elements.

11.5.3. Why is quicksort quick?

As can be seen from the name, quick sort should have certain advantages in terms of efficiency. Although the average time complexity of quick sort is the same as that of "merge sort" and "heap sort", it is usually more efficient for the following reasons.

- **The probability of the worst case is very low**: although the worst time complexity of quick sort is $O(n^2)$ and it is not as stable as merge sort, in most cases, quick sort can run at time complexity $O(n\,log\,n)$.
- **High cache usage efficiency**: when performing pivot division operations, the system can load the entire sub-array to the cache, so the efficiency of accessing elements is high. Algorithms like "heap sort" need to jump to access elements, thus lacking this feature.
- **The constant coefficient of complexity is low**: among the above three algorithms, the total number of operations such as comparison, assignment, and exchange of quick sort is the lowest. This is similar to why Insertion Sort is faster than Bubble Sort.

11.5.4. Benchmark optimization

**Quicksort may be less time efficient on certain inputs**. To take an extreme example, assuming that the input array is completely reversed, since we choose the leftmost element as the reference number, then after the pivot division is completed, the reference number is swapped to the rightmost end of the array, resulting in the length of the left sub-array being $n-1$ and the right subarray length is $0$. If this recursion continues, the length of the right sub-array after each round of pivot division is $0$, the divide-and-conquer strategy fails, and the quick sort degenerates into "bubble sort".

In order to avoid this situation as much as possible, **we can optimize the selection strategy of the benchmark number in the pivot division**. For example, we can randomly pick an element as the base number. However, if you are unlucky and choose an unsatisfactory benchmark every time, the efficiency is still not satisfactory.

It should be noted that programming languages usually generate "pseudo-random numbers". If we construct a specific test case against a sequence of pseudo-random numbers, the efficiency of quicksort may still be degraded.

In order to further improve, we can select three candidate elements in the array (usually the first, last, and midpoint elements of the array), and use the median of these three candidate elements as the reference number. In this way, the probability that the benchmark number is "neither too small nor too large" will be greatly improved. Of course, we can also select more candidate elements to further improve the robustness of the algorithm. After adopting this method, the probability of time complexity degradation to $O(n^2)$ is greatly reduced.

```zig
// select the median of three elements
fn medianThree(nums: []i32, left: usize, mid: usize, right: usize) usize {
    // XOR operation is used here to simplify the code
    // the XOR rule is 0^0 = 1^1 = 0, 0^1 = 1^0 = 1
    if ((nums[left] < nums[mid]) != (nums[left] < nums[right])) {
        return left;
    } else if ((nums[mid] < nums[left]) != (nums[mid] < nums[right])) {
        return mid;
    } else {
        return right;
    }
}

// pivot partiton (using the median of three numbers)
fn partition(nums: []i32, left: usize, right: usize) usize {
    // select the median of three candidate elements
    var med = medianThree(nums, left, (left + right) / 2, right);
    // swap the median to the leftmost end of the array
    swap(nums, left, med);
    // use nums[left] as the base number
    var i = left;
    var j = right;
    while (i < j) {
        while (i < j and nums[j] >= nums[left]) j -= 1; // find the first element less than
                                                        // the base number from right to left
        while (i < j and nums[i] <= nums[left]) i += 1; // find the first element greater than
                                                        // the reference number from left to right
        swap(nums, i, j);   // swap these two elements
    }
    swap(nums, i, left);    // swap the base number to the dividing line between two subarrays
    return i;               // return the index of the base number
}
```

11.5.5. tail recursion optimization

**With some inputs, quicksort can take up a lot of space**. Take the completely reversed input array as an example. Since the length of the right sub-array is $0$ after each round of pivot division, the height of the recursive tree will reach $n-1$. At this time, a stack frame space of $O(n)$ size needs to be occupied.

In order to prevent the accumulation of stack frame space, we can compare the lengths of the two sub-arrays after each round of pivot sorting, and only recurse on the shorter sub-arrays. Since the length of the shorter subarray does not exceed $n/2$, this approach ensures that the recursion depth does not exceed $log\,n$, thus optimizing the worst-case space complexity to $O(log\,n)$.

```zig
// quicksort (tail recursive optimization)
fn quickSort(nums: []i32, left_: usize, right_: usize) void {
    var left = left_;
    var right = right_;
    // exit recursion when the length of the subarray is 1
    while (left < right) {
        // pivot partition
        var pivot = partition(nums, left, right);
        // perform quicksort on the shorter of the two subarrays
        if (pivot - left < right - pivot) {
            quickSort(nums, left, pivot - 1);   // recursively sort left subarray
            left = pivot + 1;                   // the remaining unsorted interval is [pivot + 1, right]
        } else {
            quickSort(nums, pivot + 1, right);  // recursively sort right subarray
            right = pivot - 1;                  // the remaining unsorted interval is [left, pivot - 1]
        }
    }
}
```

11.6. merge sort

"Merge Sort" implements sorting based on the idea of divide and conquer, including two stages of "division" and "merge" as shown in the following picture.

- **Division stage**: the array is continuously divided from the midpoint by recursion, and the sorting problem of long arrays is converted into the sorting problem of short arrays.
- **Merging stage**: when the length of the sub-array is 1, the division is terminated, and the merging is started, and the two shorter ordered arrays on the left and right are continuously merged into a longer ordered array until the end.

![Fig. 归并排序的划分与合并阶段](./algos/11.6.0.png)

11.6.1. Algorithmic process

As shown in the following picture, the "partition phase" recursively cuts the array from the midpoint into two subarrays, from top to bottom.

1. Calculate the midpoint `mid` of the array, and recursively divide the left subarray (interval `[left, mid]`) and right subarray (interval `[mid + 1, right]`).
2. Perform step `1.` recursively until the length of the sub-array interval is 1, then terminate the recursive division.

The "merge phase" merges the left and right subarrays into one sorted array from bottom to top. It should be noted that the merging starts from the subarray with length 1, and each subarray in the merging stage is ordered.

![<1>](./algos/11.6.1-1.png) ![<2>](./algos/11.6.1-2.png) ![<3>](./algos/11.6.1-3.png) ![<4>](./algos/11.6.1-4.png) ![<5>](./algos/11.6.1-5.png) ![<6>](./algos/11.6.1-6.png) ![<7>](./algos/11.6.1-7.png) ![<8>](./algos/11.6.1-8.png) ![<9>](./algos/11.6.1-9.png) ![<10>](./algos/11.6.1-10.png) ![<11>](./algos/11.6.1-11.png)

It is observed that the recursive order of merge sort is the same as the post-order traversal of the binary tree.

- **Post-order traversal**: first recurse the left subtree, then recurse the right subtree, and finally process the root node.
- **Merge sort**: first recurse the left sub-array, then recurse the right sub-array, and finally process the merge.

```zig
// merge left subarray and right subarray
// left sub-array interval [left, mid]
// right subarray interval [mid + 1, right]
fn merge(nums: []i32, left: usize, mid: usize, right: usize) !void {
    // initialize auxiliary array
    var mem_arena = std.heap.ArenaAllocator.init(std.heap.page_allocator);
    defer mem_arena.deinit();
    const mem_allocator = mem_arena.allocator();
    var tmp = try mem_allocator.alloc(i32, right + 1 - left);
    std.mem.copy(i32, tmp, nums[left..right+1]);
    // the starting index and the ending index of the left subarray
    var leftStart = left - left;
    var leftEnd = mid - left;
    // the starting index and ending index of the right subarray    
    var rightStart = mid + 1 - left;
    var rightEnd = right - left;
    // i, j point to the first element of the left subarray and right subarray respectively.
    var i = leftStart;
    var j = rightStart;
    // merge the left subarray and the right subarray by overwriting the original array nums
    var k = left;
    while (k <= right) : (k += 1) {
        // if "the left sub-array has been merged",
        // then select the right subarray element,
        // and increment j
        if (i > leftEnd) {
            nums[k] = tmp[j];
            j += 1;
        // otherwise, if "the right sub-array has been merged"
        // or "the left sub-array element <= the right sub-array element"
        // then select the left sub-array element,
        // and incrment i
        } else if  (j > rightEnd or tmp[i] <= tmp[j]) {
            nums[k] = tmp[i];
            i += 1;
        // otherwise, if "neither the left or right sub-arrays have been merged"
        // and "the left sub-array element > the right sub-array element"
        // then select the right sub-array element
        // and increment j
        } else {
            nums[k] = tmp[j];
            j += 1;
        }
    }
}

// merge sort
fn mergeSort(nums: []i32, left: usize, right: usize) !void {
    // exit condition
    if (left >= right) return;              // end recursion when subarray length is 1
    // partitioninig stage
    var mid = (left + right) / 2;           // calculate midpoint
    try mergeSort(nums, left, mid);         // recurse left subarray
    try mergeSort(nums, mid + 1, right);    // recurse right subarray
    // merging stage
    try merge(nums, left, mid, right);
}
```

Implementing the merge function `merge()` presents the following difficulties.

- **Special attention needs to be paid to the meaning of each variable**. The range of `nums` to be merged is `[left, right]`, but since `tmp` only copies the elements of an interval of `nums`, the corresponding range of tmp is `[0, right - left]`.
- When comparing the sizes of `tmp[i]` and `tmp[j]`, **it is also necessary to consider the index out-of-bounds problem after the sub-array traversal is completed**, that is, the case of `i > leftEnd` and `j > rightEnd`. The priority of index out of bounds is the highest. If the left sub-array has been merged, there is no need to continue the comparison, and the elements of the right sub-array can be merged directly.

11.6.2. Algorithmic characteristics

- **Time complexity $O(n\,log\,n)$, non-adaptive sorting**: partitioning produces a recursive tree with a height of $log\,n$, and the total number of merged operations at each level is $n$, so the overall time complexity is $O(n,log,n)$.
- **Space complexity $O(n)$, not-in-place sorting**: the recursion depth is $log\,n$, and the stack frame space of $O(log\,n)$ size is used. The merge operation needs to be implemented with the aid of an auxiliary array, using $O(n)$ additional space.
- **Stable sorting**: During the merge process, the order of equal elements remains unchanged.

11.6.3. Sorting linked lists*

Merge sort has significant advantages when sorting linked lists over other sorting algorithms, and the space complexity can be optimized to $O(1)$.

- **Partition phase**: you can use "iteration" instead of "recursion" to realize the division of the linked list, thereby saving the stack frame space used by recursion.
- **Merge phase**: In the linked list, node addition and deletion operations only need to change the reference (pointer), so the merge stage (merging two short ordered linked lists into a long ordered linked list) does not require the creation of additional linked lists.

The specific implementation details are relatively complicated, and interested students can refer to relevant materials to learn.

11.7. heap sort

>**Tip**
>Before reading this section, please make sure you have completed the "Heap" chapter.

"Heap Sort" is an efficient sorting algorithm based on a heap data structure. We can use the "heap building operation" and "element removal operation" we have already learned to implement heap sorting.

1. Input an array and create a small top heap, where the smallest element is at the top of the heap.
2. Continuously execute the heap operation, and record the heap elements in order to obtain a sequence sorted from small to large.

Although the above method is feasible, it needs an additional array to save the popped elements, which is a waste of space. In practice, we usually use a more elegant implementation.

11.7.1. Algorithmic process

Assuming the length of the array is $n$, the process of heap sorting shown in the following picture.

1. Input an array and build a large heap. When done, the largest element is on top of the heap.
2. Swap the top element of the heap (the first element) with the bottom element of the heap (the last element). After the swap is done, the length of the heap is reduced by 1 and the number of sorted elements is increased by 1.
3. Starting from the top element of the heap, perform the heap operation (Sift Down) from the top to the bottom. After heapification is done, the properties of the heap are fixed.
4. Repeat steps `2.` and `3.` in a loop. After looping $n-1$ rounds, the array sorting can be completed.

>**Tip**
>In fact, step `2.` and step `3.` are also included in the operation of removing elements from the heap, but there is an additional step of popping out elements.

![<1>](./algos/11.7.1-1.png) ![<2>](./algos/11.7.1-2.png) ![<3>](./algos/11.7.1-3.png) ![<4>](./algos/11.7.1-4.png) ![<5>](./algos/11.7.1-5.png) ![<6>](./algos/11.7.1-6.png) ![<7>](./algos/11.7.1-7.png) ![<8>](./algos/11.7.1-8.png) ![<9>](./algos/11.7.1-9.png) ![<10>](./algos/11.7.1-10.png) ![<11>](./algos/11.7.1-11.png) ![<12>](./algos/11.7.1-12.png)

In the code implementation, we use the same top-to-bottom heap (Sift Down) function as in the heap chapter. It is worth noting that since the length of the heap will decrease as the largest element is extracted, we need to add a length parameter $n$ to the `siftDown()` function to specify the current effective length of the heap.

```zig
[class]{}-[func]{siftDown}

[class]{}-[func]{heapSort}
```

11.7.2. Algorithmic characteristics

- **Time complexity $O(n\,log\,n)$, non-adaptive sorting**: the heap operation uses $O(n)$ time. The time complexity of extracting the largest element from the heap is $O(log\,n)$, with a total of $n-1$ rounds.
- **Space complexity $O(1)$, in-place sorting**: Several pointer variables use $O(1)$ space. Element swap and heap operations are performed on the original array.
- **Unstable sorting**: When swapping the top and bottom elements of the heap, the relative positions of equal elements may change.

11.8. bucket sort

The aforementioned sorting algorithms all belong to the "comparison-based sorting algorithms", which implements sorting by comparing the size of elements. The time complexity of such sorting algorithms cannot exceed $O(n\,log\,n)$. Next, we explore several "non-comparison sorting algorithms" whose time complexity can reach linear order.

"Bucket Sort" is a typical application of the divide-and-conquer strategy. It sets some buckets with order of size, each bucket corresponds to a data range, and distributes the data evenly into each bucket; then, performs sorting in each bucket; finally merges all the data according to the order of the buckets.

11.8.1. algorithmic process

Consider an array of length n whose elements are floating point numbers in the range [0, 1). The bucket sorting process is shown in the following picture.

1. Initialize $k$ buckets and assign $n$ elements to $k$ buckets.
2. Perform sorting on each bucket separately (this document uses the built-in sorting function of the programming language).
3. Merge the results in ascending order of the buckets.

![Fig. 桶排序算法流程](./algos/11.8.1.png)

```zig
[class]{}-[func]{bucketSort}
```

11.8.2. Algorithmic characteristics

Bucket sorting is suitable for processing large volumes of data. For example, the input data contains 1 million elements, and the system memory cannot load all the data at once due to space constraints. At this point, you can divide the data into 1000 buckets, sort each bucket separately, and finally combine the results.

- **Time complexity $O(n+k)$**: Assuming that the elements are evenly distributed in each bucket, then the number of elements in each bucket is $\frac{n}{k}$. Assuming sorting a single bucket takes $O(\frac{n}{k}log\,\frac{n}{k})$ time, sorting all buckets takes $O(n\,log\,\frac{n}{k})$ time. When the number of buckets $k$ is relatively large, the time complexity tends to be $O(n)$. When merging results, it is necessary to traverse all buckets and elements, which takes $O(n+k)$ time.
- **Adaptive sorting**: In the worst case, all data is allocated into one bucket, and sorting the bucket takes $O(n^2)$ time.
- **Space complexity $O(n+k)$, not-in-place sorting**: additional space for $k$ buckets and a total of $n$ elements is required.
- Whether the bucket sort is stable depends on whether the algorithm for sorting the elements in the bucket is stable.

11.8.3. How to achieve an even distribution

The time complexity of bucket sorting can theoretically reach $O(n)$. **The key is to evenly distribute the elements into each bucket**, because actual data is often not evenly distributed. For example, we want to evenly distribute all products on Taobao into 10 buckets by price range, but the distribution of product prices is uneven, there are many products below 100 yuan, and very few above 1000 yuan. If the price range is evenly divided into 10 shares, the quantity of goods in each bucket will vary greatly.

In order to achieve even distribution, we can first set a rough dividing line and roughly divide the data into 3 buckets. **After the allocation is complete, the bucket with more products is further divided into 3 buckets until the number of elements in all buckets is approximately equal**.

As shown in the following picture, this approach essentially creates a recursive tree with the goal of making the leaf node values ​​as even as possible. Of course, it is not necessary to divide the data into three buckets in each round, and the specific division method can be flexibly selected according to the characteristics of the data.

![Fig. 递归划分桶](./algos/11.8.3.1.png)

If we know the probability distribution of product prices in advance, **we can set the price boundary of each bucket according to the data probability distribution**. It is worth noting that the data distribution does not necessarily require special statistics, and can also be approximated by using a certain probability model according to the characteristics of the data.

As shown in the following picture, we assume that product prices obey a normal distribution, so that the price range can be set reasonably, so that products are evenly distributed to each bucket.

![Fig. 根据概率分布划分桶](./algos/11.8.3.2.png)

11.9. counting sort

"Counting Sort" sorts by counting the number of elements, usually applies to integer arrays.

11.9.1. Simple implementation

Let's look at a simple example first. Given an array `nums` of length $n$ whose elements are all "non-negative integers". The overall process of counting sort is shown in the following picture.

1. Traverse the array, find the largest number in the array, record it as $m$, and then create an auxiliary array `counter` with a length of $m+1$.
2. **Use `counter` to count the number of occurrences of each number in `nums`**, where `counter[num]` corresponds to the number of occurrences of number `num`. The statistical method is very simple, just traverse `nums` (set the current number as `num`), and increase `counter[num]` by $1$ every round.
3. **Since each index of `counter` is naturally ordered, it is equivalent to all numbers having been sorted**. Next, we traverse `counter`, and fill in `nums` in ascending order according to the number of occurrences of each number.

![Fig. 计数排序流程](./algos/11.9.1.png)

```zig
[class]{}-[func]{countingSortNaive}
```

>**The connection between counting sort and bucket sort**
>From the perspective of bucket sorting, we can regard each index of the counting array `counter` in the counting sort as a bucket, and regard the process of counting the number as assigning each element to the corresponding bucket. Essentially, counting sort is a special case of bucket sort on integer data.

11.9.2. Full implementation

Observant students may find that **if the input data is an object, the above step `3.` will be invalid**. Suppose the input data is a product object, and we want to sort the products according to the product price (member variable of the class), then the above algorithm can only give the price sorting result.

So how can we get the sorting results of the original data? We first compute the "prefix sum" of `counter`. As the name implies, the prefix sum `prefix[i]` at index `i` is equal to the sum of the first `i` elements of the array:

$$prefix[i]=\sum_{j=0}^icounter[j]$$

**The prefix sum has a definite meaning, `prefix[num] - 1` represents the index of the last occurrence of the element `num` in the result array `res`**. This information is very critical, because it tells us where each element should appear in the resulting array. Next, we traverse each element `num` of the original array `nums` in reverse order, and perform the following two steps in each iteration:

1. Fill `num` into the index `prefix[num] - 1` of the array `res`.
2. Decrement the prefix and `prefix[num]` by $1$ to get the next index to place `num`.

After the traversal is completed, the sorted results are in the array `res`, and finally use `res` to overwrite the original array `nums`. The following picture shows the complete counting sort process.

![<1>](./algos/11.9.2-1.png) ![<2>](./algos/11.9.2-2.png) ![<3>](./algos/11.9.2-3.png) ![<4>](./algos/11.9.2-4.png) ![<5>](./algos/11.9.2-5.png) ![<6>](./algos/11.9.2-6.png) ![<7>](./algos/11.9.2-7.png) ![<8>](./algos/11.9.2-8.png)

The implementation code of counting sort is as follows.

```zig
[class]{}-[func]{countingSort}
```

11.9.3. Algorithmic characteristics

- **Time complexity $O(n+m)$**: involves traversing `nums` and traversing `counter`, both using linear time. In general, $n \gg m$, the time complexity tends to $O(n)$.
- **Space complexity $O(n+m)$, non-in-place sorting**: with the help of arrays `res` and `counter` with lengths $n$ and $m$ respectively.
- **Stable sorting**: Since the order of filling elements into `res` is "from right to left", traversing `nums` in reverse order can avoid changing the relative position between equal elements, thereby achieving stable sorting. In fact, traversing `nums` in positive order can also get the correct sorting result, but the result is unstable.

11.9.4. limitation

Seeing this, you may feel that counting sorting is very ingenious, and efficient sorting can be achieved only by counting the number. However, the preconditions for using counting sort are relatively strict.

**Counting sort only works with non-negative integers**. If you want to use it for other types of data, you need to ensure that these data can be converted into non-negative integers, and the relative size relationship between the elements cannot be changed during the conversion process. For example, for an integer array containing negative numbers, you can first add a constant to all numbers, convert all numbers into positive numbers, and convert them back after sorting.

**Counting sort is suitable for situations where the amount of data is large but the range of data is small**. For example, $m$ cannot be too large in the above example, otherwise it would take up too much space. And when $n \ll m$, counting sort uses $O(m)$ time, which may be slower than the $O(n\,log\,n)$ sorting algorithm.

11.10. radix sort

In the previous section, we introduced counting sort, which is suitable for situations where the amount of data $n$ is large but the data range $m$ is small. Suppose we need to sort $n=10^6$ student numbers, and the student number is an $8$-digit number, which means that the data range $m=10^8$ is very large, then counting sorting needs to allocate a lot of memory space, and radix sorting can avoid this situation.

The core idea of "Radix Sort" is consistent with counting sorting, and sorting is also achieved by counting numbers. On this basis, radix sorting uses the progressive relationship between digits to sort each digit in turn to obtain the final sorting result.

11.10.1. Algorithmic process

Taking the student number data as an example, assuming that the lowest digit of the number is the first digit and the highest digit is the eighth digit, the steps of radix sorting are as follows:

1. Initialize the number of bits $k=1$.
2. Perform "counting sort" on the $kth$ digit of the student number. After completion, the data will be sorted according to the $kth$ bit from small to large.
3. Increase $k$ by $1$, then return to step `2.` Continue to iterate until all bits are sorted then end.

![Fig. 基数排序算法流程](./algos/11.10.1.png)

Let's analyze the code implementation. For a number $x$ in base $d$, to obtain its $kth$ digit $x_k$, the following calculation formula can be used:
$$x_k=\lfloor\frac{x}{d^{k-1}}\rfloor mod\,d$$
In which $\lfloor a \rfloor$ means to round down the floating-point number $a$, and $mod\,d$ means to take the remainder of $d$. For student ID data, $d=10$ and $k\in[1,8]$.

In addition, we need to slightly change the counting sort code so that it can sort according to the $kth$ digit of the number.

```zig
// get the kth bit of element num, where exp = 10^(k-1)
fn digit(num: i32, exp: i32) i32 {
    // 传入 exp 而非 k 可以避免在此重复执行昂贵的次方计算
    return @mod(@divFloor(num, exp), 10);
}

// 计数排序（根据 nums 第 k 位排序）
fn countingSortDigit(nums: []i32, exp: i32) !void {
    // passing exp instead of k avoids repeating expensive power calculations here
    var mem_arena = std.heap.ArenaAllocator.init(std.heap.page_allocator);
    // defer mem_arena.deinit();
    const mem_allocator = mem_arena.allocator();
    var counter = try mem_allocator.alloc(usize, 10);
    @memset(counter, 0);
    var n = nums.len;
    // count the number of occurrences of each number from 0 to 9
    for (nums) |num| {
        var d: u32 = @bitCast(digit(num, exp)); // get the kth digit of nums[i], denoted as d
        counter[d] += 1; // count the number of occurrences of the number d
    }
    // find the prefix sum and convert the "number of occurrences" into "array index"
    var i: usize = 1;
    while (i < 10) : (i += 1) {
        counter[i] += counter[i - 1];
    }
    // traversing in reverse order, filling each element
    // into res according to the statistical results in the bucket
    var res = try mem_allocator.alloc(i32, n);
    i = n - 1;
    while (i >= 0) : (i -= 1) {
        var d: u32 = @bitCast(digit(nums[i], exp));
        var j = counter[d] - 1; // get the index j of d in the array
        res[j] = nums[i];       // fill the current element at index j
        counter[d] -= 1;        // decrement the amount of d by 1
        if (i == 0) break;
    }
    // overwrite the original array nums with the result
    i = 0;
    while (i < n) : (i += 1) {
        nums[i] = res[i];
    }
}

// radix sort
fn radixSort(nums: []i32) !void {
    // get the largest element of the array, used to determine the maximum number of digits
    var m: i32 = std.math.minInt(i32);
    for (nums) |num| {
        if (num > m) m = num;
    }
    // traverse in order from low to high
    var exp: i32 = 1;
    while (exp <= m) : (exp *= 10) {
        // performs a counting sort on the kth bit of an array element
        // k = 1 -> exp = 1
        // k = 2 -> exp = 10
        // i.e. exp = 10^(k-1)
        try countingSortDigit(nums, exp);    
    }
} 
```

>**Why start sorting from the lowest bit?**
>In consecutive sorting rounds, the subsequent round of sorting will overwrite the results of the previous round of sorting. For example, if the result of the first round of sorting is $a<b$, and the result of the second round of sorting is a>b, then the result of the second round will replace the result of the first round. Since the higher digits of numbers have higher priority than the lower digits, we should sort the lower digits first and then the higher digits.

11.10.2. Algorithm characteristics

Compared with counting sorting, radix sorting is suitable for situations with a large range of values, **but the premise is that the data must be expressible in a format with a fixed number of digits, and the number of digits cannot be too large**. For example, floating-point numbers are not suitable for radix sorting, because the number of digits $k$ is too large, which may lead to time complexity $O(nk) \gg O(n^2)$.

- **Time complexity $O(nk)$**: assuming that the amount of data is $n$, the data is in base $d$, and the maximum number of digits is $k$, then it takes $O(n+d)$ time to perform counting and sorting on a certain bit, and $O((n+d)k)$ time to sort all k bits. Usually, both $d$ and $k$ are relatively small, and the time complexity tends to be $O(n)$.
- **Space complexity $O(n+d)$, non-in-place sorting**: Same as counting sorting, radix sorting requires the use of arrays `res` and `counter` with lengths $n$ and $d$.
- **Stable sort**: same as counting sort.

11.11. summary

- Bubble sort achieves sorting by swapping adjacent elements. By adding a flag to achieve early return, we can optimize the best time complexity of bubble sort to $O(n)$.
- Insertion sort inserts the elements in the unsorted interval into the correct position of the sorted interval in each round, thus completing the sorting. Although the time complexity of insertion sort is $O(n^2)$, it is very popular in sorting tasks with small data volumes due to relatively few unit operations.
- Quicksort implements sorting based on the pivot partition operation. In pivot division, it is possible to select the worst benchmark number every time, resulting in time complexity degraded to $O(n^2)$. Introducing a median base or a random base reduces the probability of this degradation. The tail recursion method can effectively reduce the recursion depth and optimize the space complexity to $O(log\,n)$.
- Merge sort includes two stages of partitioning and merging, which typically embodies the divide and conquer strategy. In merge sorting, the sorting array needs to create an auxiliary array, and the space complexity is $O(n)$; however, the space complexity of sorting linked lists can be optimized to $O(1)$.
- Bucket sorting consists of three steps: data bucketing, sorting within buckets, and merging results. It also embodies the divide-and-conquer strategy and is suitable for situations with large data volumes. The key to bucket sorting is to evenly distribute data.
- Counting sort is a special case of bucket sorting, which implements sorting by counting the number of occurrences of data. Counting sort is suitable for situations where the amount of data is large but the data range is limited, and the data is required to be converted into positive integers.
- Radix sorting implements data sorting by bitwise sorting, requiring data to be represented as a number with a fixed number of digits.
- In general, we hope to find a sorting algorithm that has the advantages of high efficiency, stability, in-place and positive adaptability. However, like other data structures and algorithms, no sorting algorithm can satisfy all these conditions simultaneously. In practical applications, we need to choose the appropriate sorting algorithm according to the characteristics of the data.

The follwoing picture compares the efficiency, stability, in-place and adaptability of mainstream sorting algorithms.

![Fig. 排序算法对比](./algos/11.11.png)

11.11.1. Q & A

>**When is sorting algorithm stability necessary?**
>In reality, we may be sorting on a certain property of the object. For example, students have two attributes of name and height, we want to implement a multi-level sort/
>
>First sort by name to get `(A, 180)` `(B, 185)` `(C, 170)` `(D, 170)`; then sort by height. Since the sorting algorithm is unstable, we might end up with `(D, 170)` `(C, 170)` `(A, 180)` `(B, 185)`.
>
>It can be found that the positions of students D and C have been exchanged, and the order of the names has been destroyed, which we do not want to see.

>**Can the order of "search from right to left" and "search from left to right" in the pivot division be exchanged?**
>No, when we use the leftmost element as the reference number, we must first "search from right to left" and then "search from left to right". This conclusion is somewhat counter-intuitive, let's analyze why.
>
>The final step of pivot `partition()` is to swap `nums[left]` and `nums[i]`. After the exchange is completed, the elements on the left of the reference number are all $\le$ the reference number, **which requires that `nums[left]` $\ge$ `nums[i]` must be established before the last step of exchange**. Suppose we first "search from left to right", then if no element smaller than the reference number can be found, **it will exit the loop when `i == j`, at this time it may be `nums[j] == nums[i]` $\gt$ `nums[left]`**. That is to say, at this time, the last step of the exchange operation will exchange an element larger than the reference number to the leftmost end of the array, causing the pivot division to fail.
>
>For example, given an array `[0, 0, 0, 0, 1]`, if you first "search from left to right", the array will be `[1, 0, 0, 0, 0]` after pivot division, the result is not correct.
>
>Thinking about it further, if we choose `nums[right]` as the reference number, then just the opposite, we must first "search from left to right".

>**Regarding tail recursion optimization, why does choosing a short array ensure that the recursion depth does not exceed $log\,n$?**
>The recursion depth is the number of recursive methods that are not currently returning. Each round of pivot division we divide the original array into two sub-arrays. After tail recursion optimization, the length of the recursive sub-array is at most half the length of the original array. Assuming the worst case, it is always half the length, then the final recursion depth is $log\,n$.
>
>Looking back at the original quick sort, we may continuously recurse arrays with larger lengths, in the worst case $n$, $n-1$, $n-2$, $...$, $2$, $1$, so the recursion depth is $n$. Tail recursion optimization can avoid this situation.

>**Is the time complexity of quicksort $O(n^2)$ when all elements in the array are equal? How to deal with this degenerate situation?**
>Yes. In this case, it can be considered to divide the array into three parts by pivot division: less than, equal to, and greater than the reference number. Only the less than and greater than parts are recursed downwards. Under this method, input an array whose elements are all equal, and only one round of pivot division can complete the sorting.

>**Why is the worst time complexity of bucket sorting $O(n^2)$?**
>In the worst case, all elements are grouped into the same bucket. If we adopt an $O(n^2)$ algorithm to sort these elements, the time complexity is $O(n^2)$.

12. Divide and conquer

>**Abstract**
>The puzzle is broken down layer by layer, making it simpler each time.
>
>Divide and conquer reveals an important truth: start simple, and nothing is complicated.

12.1. "Divide and Conquer" is a very important and common algorithmic strategy. Divide and conquer is usually implemented based on recursion, including two steps of "divide" and "conquer".

1. **Divide (partition stage)**: Recursively decompose the original problem into two or more sub-problems until the smallest sub-problem is reached.
2. **Conquer (merging stage)**: Starting from the smallest sub-problem with known solutions, the solutions to the sub-problems are combined from bottom to top to construct a solution to the original problem.

As shown in the following picture, the "merge sort" algorithm that has been introduced is one of the typical applications of the divide-and-conquer strategy.

1. **Divide**: Recursively divide the original array (original problem) into two sub-arrays (sub-problems) until there is only one element left in the sub-array (minimum sub-problem).
2. **Conquer**: Merge ordered sub-arrays (solutions to sub-problems) from bottom to top to obtain an ordered original array (solutions to the original problem).

![Fig. 归并排序的分治策略](./algos/12.1.0.png)

12.1.1. How to estimate the divide and conquer problem

Whether a problem is suitable to use divide and conquer can usually refer to the following estimation criteria:

1. **The problem can be decomposed**: the original problem can be decomposed into smaller, similar sub-problems, and can be divided recursively in the same way.
2. **The sub-problems are independent**: there is no overlap between the sub-problems, there is no dependence on each other, and they can be solved independently.
3. **The solutions of the subproblems can be combined**: the solution of the original problem is obtained by combining the solutions of the subproblems.

Obviously, merge sorting satisfies the above three estimation criteria:

1. **The problem can be decomposed**: Recursively divide the array (original problem) into two sub-arrays (subproblems).
2. **Subproblems are independent**: Each subarray can be sorted independently (subproblems can be solved independently).
3. **Solutions to subproblems can be merged**: Two ordered subarrays (solutions to the subproblem) can be combined into one ordered array (solution to the original problem).

12.1.2. Increase efficiency through divide and conquer

Divide and conquer can not only effectively solve algorithm problems, **but also often improve algorithm efficiency**. Among sorting algorithms, quick sort, merge sort, and heap sort are faster than selection, bubble, and insertion sort because they apply a divide-and-conquer strategy.

Then, we can't help but ask: **why can divide and conquer improve the efficiency of the algorithm, and what is its underlying logic**? In other words, decomposing a large problem into multiple sub-problems, solving the sub-problems, and merging the solutions of the sub-problems into the solution of the original problem, why are these steps more efficient than directly solving the original problem? This problem can be discussed from two aspects: the number of operations and parallel computing.

1. Operation Quantity Optimization

Taking "bubble sort" as an example, it takes $O(n^2)$ time to process an array of length $n$. Suppose that we divide the array into two sub-arrays from the midpoint as shown in the following picture, it takes $O(n)$ time to divide, $O((n/2)^2)$ time to sort each sub-array, and $O(n)$ time to merge two sub-arrays.The overall time complexity is:

$$O(n+(\frac{n}{2})^2\times2+n)=O(\frac{n^2}{2}+2n)$$

![Fig. 划分数组前后的冒泡排序](./algos/12.1.2.1.png)

Next, we compute the following inequality, whose left and right sides are the total number of operations before and after division, respectively:

$$\begin{align*}
n^2&>\frac{n^2}{2}+2n\\
n^2-\frac{n^2}{2}-2n&>0\\
n(n-4)&>0
\end{align*}$$

**This means that when $n>4$, the number of operations after division is less, and the sorting efficiency should be higher**. Please note that the time complexity after division is still square order $O(n^2)$, but the constant term in the complexity becomes smaller.

Thinking further, what **if we divide the sub-array into two sub-arrays continuously from the midpoint** until there is only one element left in the sub-array? This idea is actually "merge sorting", and the time complexity is $O(n\,log\,n)$.

Think again, what **if we set a few more division points** to divide the original array into $k$ sub-arrays on average? This situation is very similar to "bucket sorting", which is very suitable for sorting massive data, and the theoretical time complexity can reach $O(n+k)$.

2. Parallel Computing Optimization

We know that the subproblems generated by divide and conquer are independent of each other, **so they can usually be solved in parallel**. That is to say, divide and conquer can not only reduce the time complexity of the algorithm, **but also facilitate the parallel optimization of the operating system**.

Parallel optimization is especially effective in a multi-core or multi-processor environment, because the system can process multiple sub-problems at the same time, making fuller use of computing resources, thereby significantly reducing the overall running time.

For example, in bucket sorting shown in the following picture, we evenly distribute massive amounts of data into each bucket, then the sorting tasks of all buckets can be distributed to each computing unit, and the results can be merged after completion.

![Fig. 桶排序的并行计算](./algos/12.1.2.2.png)

12.1.3. Divide and conquer common applications

On the one hand, divide and conquer can be used to solve many classical algorithmic problems.

- **Find nearest point pair**: The algorithm first divides the point set into two parts, then finds the closest point pair in the two parts separately, and finally finds the closest point pair across the two parts.
- **Multiplication of large integers**: such as Karatsuba's algorithm, which decomposes multiplication of large integers into multiplications and additions of several smaller integers.
- **Matrix multiplication**: such as Strassen's algorithm, which decomposes a large matrix multiplication into multiple multiplications and additions of smaller matrices.
- **Tower of Hanoi problem**: The Tower of Hanoi problem can be regarded as a typical divide-and-conquer strategy, which is solved recursively.
- **Solving reversed pairs**: In a sequence, if the previous number is greater than the following number, then the two numbers form a reversed pair. Solving the problem of reverse order can be solved by the idea of ​​divide and conquer with the help of merge sort.

On the other hand, divide and conquer is widely used in the design of algorithms and data structures.

- **Binary search**: Binary search is to divide the ordered array into two parts from the midpoint index, and then determine which half of the interval to exclude according to the comparison result between the target value and the intermediate element value, and then perform the same binary operation on the remaining interval.
- **Merge sort**: It has been introduced at the beginning of the document, so I won't go into details.
- **Quick sort**: Quick sort is to select a reference value, and then divide the array into two sub-arrays. The elements of one sub-array are smaller than the reference value, and the elements of the other sub-array are larger than the reference value, and then perform the same division operation on these two parts until only one element remains in the subarray.
- **Bucket sorting**: The basic idea of bucket sorting is to disperse data into multiple buckets, then sort the elements in each bucket, and finally take out the elements of each bucket in turn to obtain an ordered array.
- **Trees**: For example, binary search trees, AVL trees, red-black trees, B trees, B+ trees, etc., their search, insertion, and deletion operations can be regarded as divide-and-conquer applications.
- **Heap**: A heap is a special complete binary tree, and its various operations, such as insertion, deletion, and heapization, actually imply the idea of ​​divide and conquer.
- **Hash table**: Although the hash table does not directly apply the divide-and-conquer strategy, some hash conflict resolution strategies apply the divide-and-conquer strategy indirectly. For example, the long list in the chained addressing will be converted into a red-black tree to improve query efficiency.

It can be seen that **divide and conquer is an algorithmic idea** which is implicit in various algorithms and data structures.

12.2. divide and conquer search strategy

We have already learned that search algorithms fall into two broad categories:

- **Brute Force Search**: It is implemented by traversing the data structure with a time complexity of $O(n)$.
- **Adaptive search**: It utilizes unique data organization form or prior information, and can achieve $O(log\,n)$ or even $O(1)$ time complexity.

In fact, **search algorithms with a time complexity of $O(log\,n)$ are usually implemented based on a divide-and-conquer strategy**, such as binary search and trees.

- Each step of binary search breaks down the problem (search for the target element in the array) into a smaller problem (search for the target element in half of the array), and this process continues until the array is empty or the target element is found.
- Trees represent divide-and-conquer relationships. In data structures such as binary search trees, AVL trees, and heaps, the time complexity of various operations is $O(log\,n)$.

The divide and conquer strategy for binary search is as follows.

- **The problem can be decomposed**: binary search recursively decomposes the original problem (search in the array) into subproblems (search in half of the array), which is achieved by comparing the intermediate elements with the target elements.
- **Subproblems are independent**: In binary search, only one subproblem is processed per round, and it is not affected by other subproblems.
- **Solutions to subproblems do not need to be merged**: Binary search aims to find a specific element, so solutions to subproblems do not need to be merged. When the subproblem is solved, the original problem is also solved at the same time.

Divide and conquer can improve search efficiency, essentially because brute force search can only exclude one option in each round, while **divide and conquer search can exclude half of the options in each round**.

1. Realize dichotomy based on divide and conquer

In the previous chapters, binary search was implemented based on recursion (iteration). Now we implement it based on divide and conquer (recursion).

>**Question**
>Given an ordered array `nums` of length $n$ where all elements are unique, find the element `target`.

From the perspective of divide and conquer, we denote the sub-problem corresponding to the search interval $[i,j]$ as $f(i,j)$.

Starting from the original problem $f(0,n-1)$, perform a binary search through the following steps.

1. Calculate the midpoint $m$ of the search interval $[i,j]$, and exclude half of the search interval based on it.
2. Recursively solve subproblems of half the size, possibly $f(i,m-1)$ or $f(m+1,j)$.
3. Repeat steps `1.` , `2.` until `target` is found or the interval is empty.

The following picture shows the divide and conquer process of binary search for element 6 in the array.

![Fig. 二分查找的分治过程](./algos/12.2.png)

In the implementation code, we declare a recursive function `dfs()` to solve the problem $f(i,j)$.

```zig
[class]{}-[func]{dfs}

[class]{}-[func]{binarySearch}
```

12.3. Building a Binary Tree Problem

>**Question**
>Given a `preorder` traversal and `inorder` traversal of a binary tree, construct a binary tree from it and return the root node of the binary tree.

![Fig. 构建二叉树的示例数据](./algos/12.3.0.png)

1. estimating whether it is a divide-and-conquer problem

The original problem is defined as building a binary tree from `preorder` and `inorder`, which is a typical divide and conquer problem.

- **The problem can be decomposed**: From the perspective of divide and conquer, we can divide the original problem into two sub-problems: constructing the left subtree, constructing the right subtree, plus one step operation: initializing the root node. For each subtree (subproblem), we can still reuse the above division method to divide it into smaller subtrees (subproblems) until the smallest subproblem (empty subtree) is reached.
- **The subproblems are independent**: the left subtree and the right subtree are independent of each other, there is no intersection between them. When constructing the left subtree, we only need to pay attention to the part corresponding to the left subtree in the in-order traversal and pre-order traversal. The same is true for the right subtree.
- **Solutions to subproblems can be merged**: once we have the left and right subtrees (solutions to subproblems), we can link them to the root node to get the solution to the original problem.

2. How to divide the subtree

According to the above analysis, this problem can be solved by divide and conquer, **but the question is: how to divide the left subtree and right subtree by `preorder` traversal and `inorder` traversal**?

By definition, both `preorder` and `inorder` can be divided into three parts.

- Preorder traversal: `[root node | left subtree | right subtree]`, for example, the tree in the previous picture corresponds to `[ 3 | 9 | 2 1 7 ]`.
- Inorder traversal: `[left subtree | root node | right subtree]`, for example, the tree in the previous picture corresponds to `[ 9 | 3 | 1 2 7 ]`.

Taking the data in the previous picture as an example, we can obtain the division results through the steps shown in the following picture.

1. The first element 3 of the preorder traversal is the value of the root node.
2. Find the index of the root node 3 in `inorder`, which can be used to divide `inorder` into `[ 9 | 3 | 1 2 7 ]`.
3. According to the results of `inorder` division, the number of nodes in the left subtree and right subtree is easily obtained as 1 and 3 respectively, so the `preorder` can be divided into `[ 3 | 9 | 2 1 7 ]`.

![Fig. 在前序和中序遍历中划分子树](./algos/12.3.2.png)

3. Describe subtree intervals based on variables

According to the above division method, **we have obtained the index intervals of the root node, left subtree, and right subtree in `preorder` and `inorder`**. In order to describe these index intervals, we need to use several pointer variables:

- Let $i$ be the index of the root node of the current tree in `preorder`.
- Record the index of the root node of the current tree in `inorder` as $m$
- Record the index range of the current tree in `inorder` as $[l,r]$.

As shown in the following table, the above variables can represent the index of the root node in `preorder` and the index interval of the subtree in `inorder`.

||The index of the root node in preorder|The index interval of the subtree in inorder|
|---|---|---|
|current tree|$i$|$[l,r]$|
|left subtree|$i+1$|$[l,m-1]$|
|right subtree|$i+1+(m-l)$|$[m+1,r]$|

Please note that the meaning of $(m-l)$ in the index of the root node of the right subtree is "the number of nodes in the left subtree". It is recommended to understand it with the following figure.

![Fig. 根节点和左右子树的索引区间表示](./algos/12.3.3.png)

4. Code

In order to improve the efficiency of querying $m$, we use a hash table `hmap` to store the mapping from the elements in the array `inorder` to the index.

```zig
[class]{}-[func]{dfs}

[class]{}-[func]{buildTree}
```

The following picture shows the recursive process of building a binary tree. Each node is established in the process of "downward" recursion, and each edge (ie reference) is established in the process of "upward" recursion.

![<1>](./algos/12.3.4.1-1.png) ![<2>](./algos/12.3.4.1-2.png) ![<3>](./algos/12.3.4.1-3.png) ![<4>](./algos/12.3.4.1-4.png) ![<5>](./algos/12.3.4.1-5.png) ![<6>](./algos/12.3.4.1-6.png) ![<7>](./algos/12.3.4.1-7.png) ![<8>](./algos/12.3.4.1-8.png) ![<9>](./algos/12.3.4.1-9.png)

The following picture shows the division results of the `preorder` traversal and `inorder` traversal in each recursive function.

![图 12-9   每个递归函数中的划分结果](./algos/12.3.4.2.png)

Assuming that the number of nodes in the tree is $n$, initializing each node (executing a recursive function `dfs()`) takes $O(1)$ time. So the overall time complexity is $O(n)$.

The hash table stores the mapping from the `inorder` elements to the index, and the space complexity is $O(n)$. In the worst case, that is, when the binary tree degenerates into a linked list, the recursion depth reaches $n$, and $O(n)$ stack frame space is used. So the overall space complexity is $O(n)$.

12.4. Towers of Hanoi problem

In both merge sort and building a binary tree, we decompose the original problem into two subproblems half the size of the original problem. However, for the Tower of Hanoi problem, we use a different decomposition strategy.

>**Question**
>Given three columns, denoted as `A`, `B` and `C`. In the initial state, there are $n$ disks on the column `A`, and they are arranged in order from small to large from top to bottom. Our task is to move the $n$ discs to the column `C` and keep their original order unchanged. In the process of moving the disc, the following rules need to be followed.
>
>1. The disc can only be taken out from the top of one column and put in from the top of the other column.
>2. Only one disc can be moved at a time.
>3. The smaller disc must always be on top of the larger disc.

![Fig. 汉诺塔问题示例](./algos/12.4.0.png)

We denote the Tower of Hanoi problem of size $i$ as $f(i)$. For example $f(3)$ represents the Tower of Hanoi problem of moving $3$ disks from `A` to `C`.

1. Consider the base case

as shown in the following picture, for problem $f(1)$, that is, when there is only one disk, it is sufficient to move it directly from `A` to `C`.

![<1>](./algos/12.4.1.1-1.png) ![<2>](./algos/12.4.1.1-2.png)

For problem $f(2)$, that is, when there are two disks, since the small disk must always be above the large disk, **it is necessary to use `B` to complete the movement**.

1. First move the upper small disc from `A` to `B`.
2. Move the large disk from `A` to `C` again.
3. Finally move the small disc from `B` to `C`.

![<1>](./algos/12.4.1.2-1.png) ![<2>](./algos/12.4.1.2-2.png) ![<3>](./algos/12.4.1.2-3.png) ![<4>](./algos/12.4.1.2-4.png)

The process of solving problem $f(2)$ can be summarized as: **Move two discs from `A` to `C` with the aid of `B`**. Among them, `C` is called the target column, and `B` is called the buffer column.

2. subproblem decomposition

For problem $f(3)$, when there are three disks, the situation becomes slightly more complicated.

Since the solutions of $f(1)$ and $f(2)$ are known, we can think from the perspective of divide and conquer, regard the two discs on the top of `A` as a whole, and perform the steps shown in the following picture. In this way the three discs are smoothly moved from `A` to `C`.

1. Let `B` be the target column and `C` the buffer column, and move the two discs from `A` to `B`.
2. Move the remaining one disc in `A` directly from `A` to `C`.
3. Let `C` be the target column and `A` the buffer column, move the two discs from `B` to `C`.

![<1>](./algos/12.4.2.1-1.png) ![<2>](./algos/12.4.2.1-2.png) ![<3>](./algos/12.4.2.1-3.png) ![<4>](./algos/12.4.2.1-4.png)

Essentially, **we divide problem $f(3)$ into two subproblems $f(2)$ and subproblem $f(1)$**. After solving these three sub-problems in sequence, the original problem is solved. This shows that the subproblems are independent and the solutions can be combined.

So far, we can summarize the divide-and-conquer strategy for the Tower of Hanoi problem shown in the follwoing picture: Divide the original problem $f(n)$ into two sub-problems $f(n-1)$ and one sub-problem $f(1)$. The order in which the subproblems are solved is the following.

1. Move $n-1$ disks from `A` to `B` with `C`.
2. Move the remaining $1$ disc from `A` to `C` directly.
3. Move $n-1$ disks from `B` to `C` with `A`.

For these two sub-problems $f(n-1)$, recursive division can be performed in the same way until the smallest sub-problem $f(1)$ is reached. While the solution of $f(1)$ is known, only one move operation is required.

![Fig. 汉诺塔问题的分治策略](./algos/12.4.2.2.png)

3. Code

In the code, we declare a recursive function `dfs(i, src, buf, tar)` whose effect is to move $i$ disks on top of the column `src` to the target column `tar` with the help of the buffer column `buf`.

```zig
[class]{}-[func]{move}

[class]{}-[func]{dfs}

[class]{}-[func]{hanota}
```

As shown in the following picture, the Tower of Hanoi problem forms a recursive tree with a height of $n$, each node represents a sub-problem and corresponds to an open `dfs()` function, s**o the time complexity is $O(2^n)$, and the space complexity is $O(n)$**.

![Fig. 汉诺塔问题的递归树](./algos/12.4.3.png)

>**Quote**
>The Tower of Hanoi problem comes from an ancient legend. In a temple in ancient India, the monks had three tall diamond pillars and $64$ gold discs of various sizes. The monks kept moving the original discs, believing that the moment the last disc was placed correctly, the world would end.
>
>However, according to the above analysis, even if the monks move once per second, it will take a total of about $2^{64}\approx1.84\times10^{19}$ seconds, which is about $585$ billion years, far exceeding the current estimate of the age of the universe. So, if this legend is true, we should not need to worry about the end of the world.

12.5. Summary

- Divide and conquer algorithm is a common algorithm design strategy, including two stages of divide (divide) and conquer (merge), usually based on recursive implementation.
- The basis for estimating whether it is a divide-and-conquer algorithm problem includes: whether the problem can be decomposed, whether the sub-problems are independent, and whether the sub-problems can be combined.
- Merge sort is a typical application of the divide-and-conquer strategy, which recursively divides the array into two sub-arrays of equal length, and starts merging layer by layer until there is only one element left, thereby completing the sorting.
- The introduction of a divide-and-conquer strategy can often improve the efficiency of the algorithm. On the one hand, the divide-and-conquer strategy reduces the number of computing operations; on the other hand, it is beneficial to the parallel optimization of the system after divide-and-conquer.
- Divide and conquer can not only solve many algorithm problems, but also is widely used in data structure and algorithm design, and can be seen everywhere.
- Compared with brute force search, adaptive search is more efficient. Search algorithms with a time complexity of $O(log\,n)$ are usually implemented based on a divide-and-conquer strategy.
- Binary search is another typical application of the divide-and-conquer strategy, which does not include the step of merging the solutions of the subproblems. We can implement binary search by recursive divide and conquer.
- In the problem of building a binary tree, building the tree (the original problem) can be divided into building the left subtree and the right subtree (subproblems), which can be realized by dividing the index intervals of the pre-order traversal and the in-order traversal.
- In the Tower of Hanoi problem, a problem of size $n$ can be divided into two subproblems of size $n-1$ and one subproblem of size $1$. After solving these three sub-problems in sequence, the original problem is solved.

13. Backtracking

>**Abstract**
>We are like explorers in a maze, and we may encounter difficulties along the way.
>
>The power of backtracking allows us to start over, keep trying, and finally find the exit to the light.

13.1. backtracking algorithm

A "Backtracking Algorithm" is a method to solve problems through exhaustion. Its core idea is to start from an initial state, brute-force search for all possible solutions, and record them when the correct solution is encountered until the solution is found or all possible choices are tried and the solution cannot be found.

Backtracking algorithms usually use a "depth-first search" to traverse the solution space. In the chapter on binary trees, we mentioned that pre-order, in-order and post-order traversals all belong to depth-first search. Next, we use preorder traversal to construct a backtracking problem, and gradually understand the working principle of the backtracking algorithm.

>**Example one**
>
>Given a binary tree, search and record all nodes with value $7$, please return a list of nodes.

For this question, we traverse the tree in preorder and estimate whether the value of the current node is $7$, and if so, add the value of the node to the result list `res`. The relevant process implementation is shown in the following picture and code.

```zig
[class]{}-[func]{preOrder}
```

![Fig. 在前序遍历中搜索节点](./algos/13.1.0.png)

13.1.1. try and fallback

**The reason why it is called a backtracking algorithm is that the algorithm uses a strategy of "trying" and "falling back" when searching the solution space**. When the algorithm encounters a certain state during the search process and cannot move forward or cannot obtain a solution that satisfies the conditions, it will undo the choice of the previous step, return to the previous state, and try other possible choices.

For Example 1, visiting each node represents an "attempt", while the `return` that crosses a leaf node or returns to a parent node represents a "fallback".

It's worth noting that **fallbacks don't just involve function returns**. To explain this, we expand Example 1 a little.

>**Example 2**
>
>Search for all nodes with value 7 in the binary tree, **please return the path from the root node to these nodes**.

Based on the code of Example 1, we need to use a list `path` to record the path of the visited nodes. When the node whose value is 7 is visited, `path` is copied and added to the result list `res`. After the traversal is completed, all solutions are saved in `res`.

```zig
[class]{}-[func]{preOrder}
```

In each "attempt", we record the path by adding the current node to `path`; before "rewinding", we need to pop the node out of `path` **to restore the state before this attempt**.

Observing the process shown in the following picture, we can understand try and rollback as "forward" and "undo", and the two operations are inverse to each other.

![<1>](./algos/13.1.1-1.png) ![<2>](./algos/13.1.1-2.png) ![<3>](./algos/13.1.1-3.png) ![<4>](./algos/13.1.1-4.png) ![<5>](./algos/13.1.1-5.png) ![<6>](./algos/13.1.1-6.png) ![<7>](./algos/13.1.1-7.png) ![<8>](./algos/13.1.1-8.png) ![<9>](./algos/13.1.1-9.png) ![<10>](./algos/13.1.1-10.png) ![<11>](./algos/13.1.1-11.png)

13.1.2. pruning

Complex backtracking problems often contain one or more constraints, **which can often be used for "pruning"**.

>**Example 3**
>
>Search for all nodes with value $7$ in the binary tree, please return the path from the root node to these nodes, **and require that the node with value $3$ is not included in the path**.

In order to meet the above constraints, we need to add a pruning operation: during the search process, if a node with a value of $3$ is encountered, it will return in advance and stop continuing to search.

```zig
[class]{}-[func]{preOrder}
```

Pruning is a very vivid term. As shown in the following picture, during the search process, we "cut off" the search branches that do not meet the constraint conditions, avoiding many meaningless attempts, thereby improving the search efficiency.

![Fig. 根据约束条件剪枝](./algos/13.1.2.png)

13.1.3. framework code

Next, we try to extract the main framework of the backtracking "try, rollback, and pruning" to improve the versatility of the code.

In the following framework code, `state` represents the current state of the problem, and `choices` represent the choices that can be made in the current state.

```zig

```

Next, we solve Example 3 based on the framework code. The state `state` is the node traversal path, the `choices` are the left child node and the right child node of the current node, and the result `res` is the path list.

```zig
[class]{}-[func]{isSolution}

[class]{}-[func]{recordSolution}

[class]{}-[func]{isValid}

[class]{}-[func]{makeChoice}

[class]{}-[func]{undoChoice}

[class]{}-[func]{backtrack}
```

According to the meaning of the question, the search should continue after finding a node with a value of 7, **so we need to delete the `return` statement after recording the solution**. The follwoing picture compares the search process for retaining or removing return statements.

![Fig. 保留与删除 return 的搜索过程对比](./algos/13.1.3.png)

Compared with the code implementation based on preorder traversal, the code implementation based on the backtracking algorithm framework is more verbose, but it is more versatile. In fact, **many backtracking problems can be solved under this framework**. We only need to define `state` and `choices` according to specific problems, and implement each method in the framework.

13.1.4. common term

In order to analyze the algorithmic issues more clearly, we summarize the meaning of the commonly used terms in backtracking algorithms, and give corresponding examples in comparison with Example 3.

|Noun|Definition|Example3|
|---|---|---|
|Solution|A solution is an answer that satisfies certain conditions of the problem,<br>and there may be one or more|All paths from the root node to node7 satisfying the constraints|
|Constraint|Constraints are conditions that limit the feasibility of a solution in a<br>problem, and are often used for pruning|Node3 is not included in the path, only a node7 is included|
|State|The state represents the state of the problem at a certain moment,<br>including the choices that have been made|The currently visited node path, that is, the list of path nodes|
|Attempt|An attempt is the process of exploring the solution space according to<br>the available choices, including making a choice, updating the state,<br>checking whether it is a solution|Recursively visit the left(right) child node, add the node to<br>path, and determine whether the value of the node is 7|
|Backtracking|Rollback means that when encountering a state that does not meet the<br>constraints, undo the previous selection and return to the previous state|When the leaf node is crossed, the node access is ended, and the<br>node with a value of 3 is encountered, the search is terminated,<br>and the function returns|
|Pruning|Pruning is a method to avoid meaningless search paths according to<br>problem characteristics and constraints, which can improve search<br>efficiency|When encountering a node with a value of 3, stop and continue<br>searching|

>**Tip**
>Concepts such as problem, solution, and state are universal, and are involved in algorithms such as divide and conquer, backtracking, dynamic programming, and greed.

13.1.5. Strengths and Limitations

The backtracking algorithm is essentially a depth-first search algorithm that tries all possible solutions until a satisfying solution is found. The advantage of this method is that it is able to find all possible solutions, and with reasonable pruning operations, it is very efficient.

However, when dealing with large-scale or complex problems, **the operating efficiency of backtracking algorithms may be unacceptable**.

- **Time**: Backtracking algorithms usually need to traverse all possibilities of the state space, and the time complexity can reach exponential or factorial order.
- **Space**: The current state needs to be saved in the recursive call (such as paths, auxiliary variables for pruning, etc.), and when the depth is large, the space requirement may become large.

Even so, **backtracking algorithms are still optimal solutions to certain search problems and constraint satisfaction problems**. For these problems, since it is impossible to predict which choices will yield valid solutions, we must iterate over all possible choices. In this case, **the key is how to optimize efficiency**. There are two common efficiency optimization methods.

- **Pruning**: saves time and space by avoiding searching for paths that will definitely not yield a solution.
- **Heuristic search**: Introduce some strategies or estimated values in the search process, so as to give priority to the path that is most likely to produce an effective solution.

13.1.6. Backtracking typical examples

Backtracking algorithms can be used to solve many search problems, constraint satisfaction problems, and combinatorial optimization problems.

**Search Problems**: The goal of this type of problem is to find a solution that satisfies certain criteria.

- Full permutation problem: Given a set, find all possible permutations and combinations.
- Subset sum problem: Given a set and a target sum, find all subsets in the set whose sum is the target sum.
- Tower of Hanoi problem: Given three columns and a series of disks of different sizes, it is required to move all the disks from one column to another. Only one disk can be moved at a time, and a large disk cannot be placed on a small disc.

**Constraint Satisfaction Problems**: The goal of this type of problem is to find a solution that satisfies all constraints.

- $n$ Queens: Place $n$ queens on a $n \times n$ board so that they do not attack each other.
- Sudoku: Fill in the numbers $1\sim9$ in the $9\times9$ grid so that the numbers in each row, each column and each $3\times3$ subgrid do not repeat.
- Graph coloring problem: Given an undirected graph, color each vertex of the graph with the fewest colors so that adjacent vertices have different colors.

**Combinatorial optimization problems**: The goal of this type of problem is to find the optimal solution in a combinatorial space satisfying certain conditions.

- 0-1 bag problem: Given a set of items and a bag, each item has a certain value and weight, and it is required to select items to maximize the total value within the bag capacity limit.
- Traveling salesman problem: In a graph, start from one point, visit all other points exactly once and return to the starting point, find the shortest path.
- Largest group problem: Given an undirected graph, find the largest complete subgraph, that is, any two vertices in the subgraph are connected by an edge.

Note that backtracking is not an optimal solution for many combinatorial optimization problems.

- The 0-1 bag problem is usually solved using dynamic programming to achieve greater time efficiency.
- Traveling salesman is a well-known NP-Hard problem, commonly used solutions include genetic algorithms and ant colony algorithms.
- The largest group problem is a classic problem in graph theory, which can be solved by heuristic algorithms such as greedy.

13.2. full permutation problem

The full permutation problem is a typical application of the backtracking algorithm. Its definition is given a collection (such as an array or string), find all possible permutations of the elements in this collection.

The following table lists several sample data, including input arrays and all corresponding permutations.

|Input array|All permutations|
|---|---|
|$[1]$|$[1]$|
|$[1,2]$|$[1,2]$, $[2,1]$|
|$[1,2,3]$|$[1,2,3]$, $[1,3,2]$, $[2,1,3]$, $[2,3,1]$, $[3,1,2]$, $[3,2,1]$|

13.2.1. in the case of no equal elements

>**Question**
>Input an integer array, the array does not contain duplicate elements, return all possible permutations.

From the perspective of the backtracking algorithm, **we can imagine the process of generating permutations as the result of a series of choices**. Assuming the input array is $[1,2,3]$, if we first select $1$, then $3$, and finally $2$, we get the permutation $[1,3,2]$. Falling back means undoing a choice and continuing to try other choices.

From the point of view of the backtracking code, the candidate set `choices` are all elements in the input array, and the state `state` is the elements that have been selected so far. Note that each element is only allowed to be selected once, **so all elements in `state` should be unique**.

As shown in the following picture, we can expand the search process into a recursive tree, and each node in the tree represents the current state `state`. Starting from the root node, after three rounds of selection, the leaf nodes are reached, and each leaf node corresponds to a permutation.

![Fig. 全排列的递归树](./algos/13.2.1.png)

1. Repeat selection pruning

In order to realize that each element is only selected once, we consider introducing a Boolean array `selected`, where `selected[i]` indicates whether `choices[i]` has been selected, and implement the following pruning operations based on it.

- After making choice `choice[i]`, we set `selected[i]` to $True$, which means it has been selected.
- When traversing the selection list `choices`, skip all nodes that have been selected, that is, pruning.

As shown in the following picture, suppose we choose 1 in the first round, 3 in the second round, and 2 in the third round, then we need to cut off the branch of element 1 in the second round, and cut off the branches of elements 1 and 3 in the third round.

![Fig. 全排列剪枝示例](./algos/13.2.1.1.png)

Looking at the previous picture, this pruning operation reduces the search space size from $O(n^n)$ to $O(n!)$.

2. Code

After thinking about the above information, we can perfrom "cloze" in the framework code. In order to shorten the number of lines of code, we do not implement each function in the framework code separately, but expand them in the `backtrack()` function.

```zig
[class]{}-[func]{backtrack}

[class]{}-[func]{permutationsI}
```

13.2.2. Consider the case of equal elements

>**Question**
>Input an integer array, **the array may contain repeated elements**, return all non-repeated permutations.

Assume the input array is $[1,1,2]$. In order to easily distinguish between two repeated elements $1$, we will record the second $1$ as $\^1$.

As shown in the following picture, half of the permutations generated by the above method are duplicates.

![Fig. 重复排列](./algos/13.2.2.png)

So how do you remove duplicate alignments? Most directly, consider de-duplicating the alignments directly with the help of a hash table. However, this is not elegant enough, **as the search branch that generates the duplicate alignments is unnecessary and should be identified and pruned in advance**, which further improves the efficiency of the algorithm.

1. equal element pruning

Looking at the following picture, in the first round, choice $1$ or choice $\^1$ are equivalent, and all permutations generated under these two choices are duplicates. Therefore $\^1$ should be pruned away.

Similarly, after selecting $2$ in the first round, $1$ and $\^1$ in the second round of selection will also generate duplicate branches, so $\^1$ in the second round should also be pruned.

Essentially, **our goal is to ensure that multiple equal elements are selected only once in a certain round of selection**.

![Fig. 重复排列剪枝](./algos/13.2.2.1.png)

2. Code

Based on the code of the previous question, we consider opening a hash table `duplicated` in each round of selection to record the elements that have been tried in this round, and to prune the duplicated elements.

```zig
[class]{}-[func]{backtrack}

[class]{}-[func]{permutationsII}
```

Assuming that the elements are different from each other, there are $n!$ types of permutations (factorial) for $n$ elements; when recording the results, it is necessary to copy a list of length $n$, using $O(n)$ time. **Therefore, the time complexity is $O(n!n)$**.

The maximum recursion depth is $n$, using $O(n)$ stack frame space. `selected` uses $O(n)$ space. There are at most $n$ duplicated at the same time, using $O(n^2)$ space. So the space complexity is $O(n^2)$.

3. Comparison of two kinds of pruning

Note that while both `selected` and `duplicated` are used for pruning, they have different goals.

- **Repeated selection pruning**: only one `selected` during the entire search. It records which elements are contained in the current state, and its function is to prevent an element from appearing repeatedly in `state`.
- **Equal element pruning**: Each round of selection (i.e., each enabled `backtrack` function) contains a `duplicated`. It records which elements have been selected in the traversal, and its function is to ensure that equal elements are only selected once.

The following picture shows the effective range of the two pruning conditions. Note that each node in the tree represents a choice, and each node on the path from the root node to the leaf node constitutes a permutation.

![Fig. 两种剪枝条件的作用范围](./algos/13.2.2.3.png)

13.3. Subsets and Questions

13.3.1. The case of no repeated elements

>**Question**
>Given an array of positive integers `nums` and a target positive integer `target`, find all possible combinations such that the sum of elements in the combination is equal to `target`. Given an array with no duplicate elements, each element can be selected multiple times. Please return these combinations as a list, the list should not contain duplicates.

For example, given the input set $\{3,4,5\}$ and the target integer $9$, the solution is $\{3,3,3\},\{4,5\}$. There are two points to note:

- Elements in the input collection can be selected an infinite number of times.
- Subsets do not distinguish the order of elements, such as $\{4,5\}$ and $\{5,4\}$ are the same subset.

1. Refer to the full array solution

Similar to the full permutation problem, we can think of the subset generation process as the result of a series of selections, and update the "element sum" in real time during the selection process. When the element sum is equal to `target`, the subset is recorded in the result list.

Unlike the full permutation problem, **the elements in the set of this problem can be selected infinitely**, so there is no need to use the `selected` Boolean list to record whether the element has been selected. We can make minor modifications to the full permutation code, and initially obtain the problem-solving code.

```zig
[class]{}-[func]{backtrack}

[class]{}-[func]{subsetSumINaive}
```

Enter the array $[3,4,5]$ and target element $9$ into the above code, the output result is $[3,3,3],[4,5],[5,4]$. **Although all the subsets with sum are found successfully, there are duplicate subsets $[4,5]$ and $[5,4]$**.

This is because the search process is selection order sensitive, whereas subsets are not. As shown in the following picture, selecting $4$ before selecting $5$ and selecting $5$ before selecting $4$ are two different branches, but both correspond to the same subset.

![Fig. 子集搜索与越界剪枝](./algos/13.3.1.1.png)

In order to remove duplicate subsets, **a direct idea is to deduplicate the result list**. But this method is very inefficient for two reasons.

- When there are many elements in the array, especially when `target` is large, the search process will produce a large number of duplicate subsets.
- Comparing the similarities and differences of subsets (arrays) is very time-consuming. It is necessary to sort the array first, and then compare the similarities and differences of each element in the array.

2. Repeat Subset Pruning

**We consider deduplication by pruning during search**. Observe the following picture, the repeated subsets are generated when the elements of the array are selected in different orders, such as the following case.

1. When $3$ and $4$ are selected in the first round and the second round respectively, all subsets containing these two elements will be generated, denoted as $[3,4,...]$.
2. After that, when $4$ is selected in the first round, **$3$ should be skipped in the second round**, because the subset $[4,3,...]$ generated by this choice is completely duplicated with the subset generated in `1.`.

In the search, each layer of choices is attempted one by one from left to right, so the further to the right a branch is, the more it is clipped.

1. Select $3$ and $5$ in the first two rounds to generate subset $[3,5,...]$.
2. Select $4$ and $5$ in the first two rounds to generate subset $[4,5,...]$.
3. If $5$ is selected in the first round, **$3$ and $4$ should be skipped in the second round**, because the subset $[5,3,...]$ and the subset $[5,4,...]$ are exactly the same as the subsets described in steps 1. and 2.

![Fig. 不同选择顺序导致的重复子集](./algos/13.3.1.2.png)

To sum up, given the input array $[x_1,x_2,...,x_n]$, if the selection sequence in the search process is $[x_{i_1},x_{i_2},...,x_{i_m}]$, then the selection sequence needs to satisfy $i_1 \le i_2 \le ... \le i_m$, **selection sequences that do not satisfy this condition will cause repetitions and should be pruned**.

3. Code

To implement this pruning, we initialize the variable `start` to indicate the starting point of the traversal. **After selecting $x_i$, set the next round to traverse from index $i$**. In this way, the selection sequence can satisfy $i_1 \le i_2 \le ... \le i_m$, thus ensuring the uniqueness of the subset.

In addition, we also made two optimizations to the code:

- Sort the array `nums` before starting the search. When traversing all selections, **when the subset sum exceeds `target`, the loop ends directly**, because the subsequent elements are larger, and the subset sum must exceed `target`.
- Leave out the elements and the variable `total`, **count the element-wise sums by performing subtraction on `target`**, and record the solution when `target` equals $0$.

```zig
[class]{}-[func]{backtrack}

[class]{}-[func]{subsetSumI}
```

The following picture shows the overall backtracking process after inputting the array $[3,4,5]$ and the target element $9$ into the above code.

![Fig. 子集和 I 回溯过程](./algos/13.3.1.3.png)

13.3.2. Consider the case of repeated elements

>**Question**
>Given an array of positive integers `nums` and a target positive integer `target`, find all possible combinations such that the sum of elements in the combination is equal to `target`. **Given the array may contain duplicate elements, each element can be selected only once**. Please return these combinations as a list, the list should not contain duplicates.

Compared with the previous question, **the input array of this question may contain repeated elements**, which introduces new problems. For example, given the array $[4,\^4,5]$ and the target element $9$, the output of the existing code is $[4,5],[\^4,5]$, with repeated subsets.

**The reason for this duplication is that equal elements are selected multiple times in a certain round**. As shown in the following picture, there are three choices in the first round, two of which are $4$, which will generate two repeated search branches, thereby outputting a repeated subset; similarly, two $4s$ in the second round will also generate repeated sub-sets set.

![Fig. 相等元素导致的重复子集](./algos/13.3.2.0.png)

1. equal element pruning

To solve this problem, **we need to restrict equal elements to be selected only once in each round**. The implementation is clever: since the array is sorted, equal elements are adjacent. This means that in a certain round of selection, if the current element is equal to the left element, it means that it has been selected, so the current element is skipped directly.

At the same time, **each array element specified in this question can only be selected once**. Fortunately, we can also use the variable `start` to satisfy this constraint: when the selection $x_i$ is made, set the next round to traverse backwards from index $i+1$. In this way, duplicate subsets can be removed, and duplicate selection elements can also be avoided.

2. Code

```zig
[class]{}-[func]{backtrack}

[class]{}-[func]{subsetSumII}
```

The following picture shows the backtracking process of the array $[4,4,5]$ and the target element $9$, including four pruning operations. Please combine diagrams with code comments to understand the entire search process and how each pruning operation works.

![Fig. 子集和 II 回溯过程](./algos/13.3.2.2.png)

13.4. N queens problem

>**Question**
>According to the rules of chess, a queen can attack a piece on the same row or column or on the same diagonal as the queen. Given $n$ queens and a chessboard of size $n \times n$, find a placement plan that makes all queens unable to attack each other.

As shown in the following picture, when $n=4$, a total of two solutions can be found. From the perspective of the backtracking algorithm, there are $n^2$ squares in the $n\ times n$ size chessboard, and all `choices` are given. In the process of placing queens one by one, the state of the board is constantly changing, and the board at each moment is the state `state`.

![Fig. 4 皇后问题的解](./algos/13.4.0.1.png)

The following picture shows the three constraints of this problem: multiple queens cannot be in the same row, column, or diagonal. It is worth noting that the diagonals are divided into main diagonals `\` and secondary diagonals `/`.

![Fig. n 皇后问题的约束条件](./algos/13.4.0.2.png)

1. row by row placement strategy

The number of queens and the number of rows of the chessboard are both $n$, so we can easily get an inference: **each row of the chessboard allows only one queen to be placed**.

That is to say, we can adopt a row-by-row placement strategy: starting from the first row, place a queen in each row until the end of the last row.

As shown in the followingh picture, it is the row-by-row placement process of the $4$ queens problem. Due to the limitation of the frame, only one of the search branches in the first row is expanded in the following picture, and the solutions that do not satisfy the column constraints and diagonal constraints are all pruned.

![Fig. 逐行放置策略](./algos/13.4.1.png)

Essentially, **the row-by-row placement strategy acts as pruning**, which avoids all search branches where multiple queens appear in the same row.

2. Column and Diagonal Pruning

In order to satisfy column constraints, we can use a boolean array `cols` of length $n$ to record whether each column has a queen. Before each decision to place, we prune the columns that already have queens through `cols`, and dynamically update the state of `cols` in the backtracking.

So, how to deal with diagonal constraints? Let the row and column index of a square in the chessboard be $(row,col)$, select a main diagonal in the matrix, we find that the row index minus the column index of all squares on the diagonal are equal, **that is, $row-col$ of all squares on the diagonal is a constant value**.

That is to say, if two squares satisfy $row1-col1=row2-col2$, they must be on the same main diagonal. Using this rule, we can use an array `diag1` shown in the following picture to record whether there are queens on each main diagonal.

Similarly, **$row+col$ of all squares on the sub-diagonal is a constant value**. We can use the same method to handle the subdiagonal constraints with the help of the array `diag2`.

![Fig. 处理列约束和对角线约束](./algos/13.4.2.png)

3. Code

Please note that the range of $row-col$ in an $n$-dimensional square matrix is $[-n+1,n-1]$, and the range of $row+col$ is $[0,2n-2]$, so the number of main and secondary diagonals are both $2n-1$, that is, the lengths of the arrays `diag1` and `diag2` are both $2n-1$.

```zig
[class]{}-[func]{backtrack}

[class]{}-[func]{nQueens}
```

Placing $n$ times row by row, considering column constraints, there are $n$, $n-1$, $...$, $2$, $1$ choices from the first row to the last row respectively, **so the time complexity is $O(n!)$**. In fact, pruning based on diagonal constraints can also greatly reduce the search space, so the search efficiency is often better than the above time complexity.

The array `state` uses $O(n^2)$ space, and the arrays `cols`, `diags1`, `diags2` all use $O(n)$ space. The maximum recursion depth is $n$, using $O(n)$ stack frame space. Therefore, **the space complexity is $O(n^2)$**.

13.5. summary

- The essence of the backtracking algorithm is an exhaustive method, which searches for a solution that meets the conditions through a depth-first traversal of the solution space. During the search process, solutions that meet the conditions are recorded until all solutions are found or the traversal is completed.
- The search process of the backtracking algorithm includes two parts: trying and backtracking. It tries various options through depth-first search, and when it encounters a situation that does not meet the constraints, it undoes the selection of the previous step, returns to the previous state, and continues to try other options. Trying and backtracking are two opposite operations.
- Backtracking problems usually contain multiple constraints, which can be used to implement pruning operations. Pruning can end unnecessary search branches in advance, greatly improving search efficiency.
- Backtracking algorithms can mainly be used to solve search problems and constraint satisfaction problems. Although combinatorial optimization problems can be solved by backtracking algorithms, there are often solutions with higher efficiency or better results.
- The full permutation problem aims to search for all possible permutations of a given set. We use an array to record whether each element is selected, and prune off the search branches that repeatedly select the same element to ensure that each element is selected only once.
- In the full permutation problem, if there are duplicate elements in the set, the final result will be a duplicate permutation. We need to constrain equal elements to be selected only once in each round, which is usually achieved with the help of a hash table.
- The goal of the subset sum problem is to find all subsets in a given set that sum to the target value. Sets do not distinguish the order of elements, while the search process outputs results in all orders, resulting in duplicate subsets. We sort the data before backtracking and set a variable to indicate the starting point of the traversal for each round, thereby pruning search branches that generate duplicate subsets.
- For subset sum problems, equal elements in the array produce duplicate sets. We use the precondition that the array is sorted to implement pruning by estimating whether adjacent elements are equal, so as to ensure that equal elements can only be selected once in each round.
- $n$ Queens aims to find a solution to place $n$ queens on an $n \times n$ size chessboard, requiring that all queens cannot attack each other in pairs. The constraints of this problem include row constraints, column constraints, main diagonal and secondary diagonal constraints. In order to satisfy the row constraints, we adopt a row-by-row placement strategy to ensure that a queen is placed in each row.
- Column constraints and diagonal constraints are handled similarly. For column constraints, we use an array to record whether each column has a queen, thus indicating whether the selected square is legal. For diagonal constraints, we use two arrays to record whether there are queens on the main and sub-diagonals; the difficulty lies in finding the row and column index rules that are satisfied by the square on the same main (sub-) diagonal.

13.5.1. Q & A

>**How to understand the relationship between backtracking and recursion?**
>In general, backtracking is an "algorithmic strategy", while recursion is more like a "tool".
>
>- Backtracking algorithms are often implemented based on recursion. However, backtracking is one of the application scenarios of recursion and is the application of recursion in search problems.
>- The recursive structure embodies the problem-solving paradigm of "sub-problem decomposition" and is often used to solve problems such as divide and conquer, backtracking, and dynamic programming (memory recursion).

14. dynamic programming

>**Abstract**
>Streams flow into rivers, and rivers flow into seas.
>
>Dynamic programming brings together the solutions to small problems into answers to big problems, leading us step by step to the other side of problem solving.

14.1. A first look at Dynamic Programming

"Dynamic Programming" is an important algorithm paradigm. It decomposes a problem into a series of smaller sub-problems, and avoids repeated calculations by storing the solutions of the sub-problems, thereby greatly improving time efficiency.

In this section, we start with a classic example, first give its brute force backtracking solution, observe the overlapping sub-problems contained in it, and then gradually derive a more efficient dynamic programming solution.

>**climbing stairs**
>Given a staircase with $n$ steps in total, you can go up $1$ or $2$ steps each step. How many options are there to climb to the top of the building?

As shown in the figure below, for a $3$-step staircase, there are $3$ ways to climb to the top of the building.

![Fig. 爬到第 3 阶的方案数量](./algos/14.1.0.png)

The goal of this problem is to solve the number of solutions. We can consider exhaustively enumerating all possibilities by backtracking. Specifically, think of climbing stairs as a process of multiple rounds of selection: starting from the ground, choosing $1$ or $2$ steps per round, increasing the number of solutions by $1$ each time you reach the top of the stairs, and pruning them when you cross the top of the stairs.

```zig
// backtracking
fn backtrack(choices: []i32, state: i32, n: i32, res: std.ArrayList(i32)) void {
    // when climbing to the nth level, the number of options increases by 1
    if (state == n) {
        res.items[0] = res.items[0] + 1;
    }
    // iterate through all selections
    for (choices) |choice| {
        // pruning: not allowed beyond the nth level
        if (state + choice > n) {
            break;
        }
        // try: make a selection, update the status
        backtrack(choices, state + choice, n, res);
        // backtrack
    }
}

// climbing stairs: backtracking
fn climbingStairsBacktrack(n: usize) !i32 {
    var choices = [_]i32{ 1, 2 }; // you can choose to climb 1 or 2 steps
    var state: i32 = 0; // start climbing from step 0
    var res = std.ArrayList(i32).init(std.heap.page_allocator);
    defer res.deinit();
    try res.append(0); // use res[0] to record the number of solutions
    backtrack(&choices, state, @intCast(n), res);
    return res.items[0];
}
```

14.1.1. Method 1: Brute force search

Backtracking algorithms usually do not explicitly disassemble the problem, but treat the problem as a series of decision-making steps, and search for all possible solutions through trial and error.

We can try to analyze this question from the perspective of problem decomposition. Assuming that there are $dp[i]$ solutions to climb to the $ith$ step, then $dp[i]$ is the original problem, and its sub-problems include:

$$dp[i-1],dp[i-2],...,dp[2],dp[1]$$

Since we can only go up 1 or 2 steps in each round, when we stand on the $ith$ step, we can only stand on the $i-1th$ or $i-2th$ step in the previous round. In other words, we can only go to the $ith$ step from the $i-1th$ or $i-2th$ step.

From this, an important inference can be drawn: **the number of solutions to climb to the $i-1th$ step plus the number of solutions to climb to the $i-2th$ step is equal to the number of solutions to climb to the $i-th$ step**. The formula is as follows:

$$dp[i]=dp[i-1]+dp[i-2]$$

This means that in the stair climbing problem, there is a recursive relationship between the subproblems, and **the solution to the original problem can be constructed from the solutions to the subproblems**. The followoing picture shows this recurrence relationship.

![Fig. 方案数量递推关系](./algos/14.1.1.1.png)

We can get the brute force search solution according to the recursive formula. Taking $dp[n]$ as the starting point, recursively decompose a larger problem into the sum of two smaller problems until it return when it reaches the smallest sub-problems $dp[1]$ and $dp[2]$. Among them, the solution $dp[1]=1$, $ of the smallest subproblem is known, which means climbing to the $1st$ and $2nd$ level respectively has $1$ and $2$ solutions.

Observe the following code, which is a depth-first search like the standard backtracking code, but more concise.

```zig
// search
fn dfs(i: usize) i32 {
    // return given dp[1] and dp[2] are known
    if (i == 1 or i == 2) {
        return @intCast(i);
    }
    // dp[i] = dp[i-1] + dp[i-2]
    var count = dfs(i - 1) + dfs(i - 2);
    return count;
}

// climbing stairs: search
fn climbingStairsDFS(comptime n: usize) i32 {
    return dfs(n);
}
```

The following picture shows the recursive tree formed by brute force search. For the problem $dp[n]$, the depth of the recursion tree is $n$, and the time complexity is $O(2^n)$. The exponential growth is explosive. If we input a relatively large $n$, we will be stuck in a long wait.

![Fig. 爬楼梯对应递归树](./algos/14.1.1.2.png)

Looking at the previous picture, it is found that **the exponential time complexity is caused by "overlapping sub-problems"**. For example: $dp[9]$ is decomposed into $dp[8]$ and $dp[7]$, dp[8] is decomposed into $dp[7]$ and $dp[6]$, both of which contain the subproblem $dp[7]$.

By analogy, the sub-problems contain smaller overlapping sub-problems, and the children and grandchildren are endless. The vast majority of computing resources are wasted on these overlapping problems.

14.1.2. Method 2: Memorized search

In order to improve the efficiency of the algorithm, **we want that all overlapping subproblems are only calculated once**. To do this, we declare an array `mem` to record the solution to each subproblem, and prune overlapping subproblems during the search process.

1. When $dp[i]$ is first calculated, we record it to `mem[i]` for later use.
2. When it is necessary to calculate $dp[i]$ again, we can directly obtain the result from `mem[i]`, thereby avoiding repeated calculation of this sub-problem.

```zig
// memoized search
fn dfs(i: usize, mem: []i32) i32 {
    // return given dp[1] and dp[2] are known
    if (i == 1 or i == 2) {
        return @intCast(i);
    }
    // if there is a record dp[i], return it directly
    if (mem[i] != -1) {
        return mem[i];
    }
    // dp[i] = dp[i-1] + dp[i-2]
    var count = dfs(i - 1, mem) + dfs(i - 2, mem);
    // store dp[i]
    mem[i] = count;
    return count;
}

// climbing stairs: memoized search
fn climbingStairsDFSMem(comptime n: usize) i32 {
    // mem[i] records the total number of solutions that have reached the ith step,
    // -1 represents no record
    var mem = [_]i32{ -1 } ** (n + 1);
    return dfs(n, &mem);
}
```

Looking at the following picture, after memorization processing, all overlapping sub-problems only need to be calculated once, and the time complexity is optimized to $O(n)$, which is a huge leap.

![Fig. 记忆化搜索对应递归树](./algos/14.1.2.png)

14.1.3. Method Three: Dynamic Programming

**Memoized search is a "top-down" approach**: we start with the original problem (root node) and recursively decompose larger subproblems into smaller subproblems until we solve the smallest known subproblem (leaf node). Afterwards, the solutions to the sub-problems are collected layer by layer through backtracking, and the solution to the original problem is constructed.

In contrast, **dynamic programming is a "bottom-up" approach**: starting with the solution to the smallest subproblem, iteratively building solutions to larger subproblems until the solution to the original problem is reached.

Since dynamic programming does not include a backtracking process, it only needs to be implemented using loop iterations without using recursion. In the following code, we initialize an array `dp` to store the solutions of the subproblems, which plays the same recording role as the array `mem` in the memoized search.

```zig
// climbing stairs: dynamic programming
fn climbingStairsDP(comptime n: usize) i32 {
    // return given dp[1] and dp[2] are known
    if (n == 1 or n == 2) {
        return @intCast(n);
    }
    // initialize the dp table, used to store solutions to subproblems
    var dp = [_]i32{-1} ** (n + 1);
    // initial state: preset solution to the minimum subproblem
    dp[1] = 1;
    dp[2] = 2;
    // state transition: solving larger sub-problems step by step from smaller sub-problems
    for (3..n + 1) |i| {
        dp[i] = dp[i - 1] + dp[i - 2];
    }
    return dp[n];
}
```

The following picture simulates the execution process of the above code.

![Fig. 爬楼梯的动态规划过程](./algos/14.1.3.png)

Like the backtracking algorithm, dynamic programming also uses the concept of "states" to represent a specific stage of problem solving, and each state corresponds to a subproblem and the corresponding local optimal solution. For example, the state of the stair climbing problem is defined as the current stair step $i$.

Based on the above, we can summarize the common terms of dynamic programming.

- The array `dp` is called "dp table", and $dp[i]$ represents the solution of the subproblem corresponding to state $i$.
- The state corresponding to the smallest subproblem (that is, the $1st$ and $2nd$ steps of the stairs) is called the "initial state".
- The recursive formula $dp[i]=dp[i-1]+dp[i-2]$ is called "state transition equation".

14.1.4. space optimization

If you are careful, you may find that **since $dp[i]$ is only related to $dp[i-1]$ and $dp[i-2]$, we do not need to use an array `dp` to store the solutions of all sub-problems**, but only need to roll two variables forward.

```zig
// climbing stairs: dynamic planning after space optimization
fn climbingStairsDPComp(comptime n: usize) i32 {
    if (n == 1 or n == 2) {
        return @intCast(n);
    }
    var a: i32 = 1;
    var b: i32 = 2;
    for (3..n + 1) |_| {
        var tmp = b;
        b = a + b;
        a = tmp;
    }
    return b;
}
```

Looking at the previous code, since the space occupied by the array `dp` is omitted, the space complexity is reduced from $O(n)$ to $O(1)$.

In dynamic programming problems, the current state is often only related to a limited number of previous states. At this time, we can only retain the necessary states and save memory space through "dimensionality reduction". This space optimization technique is called "rolling variables" or "rolling arrays".

14.2. Dynamic Programming Problem Properties

In the previous section, we learned how dynamic programming solves problems by decomposing them into subproblems. In fact, sub-problem decomposition is a general algorithm idea, with different emphases in divide-and-conquer, dynamic programming, and backtracking.

- "Divide and conquer algorithm" recursively divides the original problem into multiple independent sub-problems until the smallest sub-problem is reached, and merges the solutions of the sub-problems in backtracking to finally obtain the solution of the original problem.
- "Dynamic programming" also recursively decomposes the problem, but the main difference from the divide-and-conquer algorithm is that the sub-problems in dynamic programming are interdependent, and many overlapping sub-problems will appear during the decomposition process.
- "Backtracking Algorithm" exhausts all possible solutions in trial and error, and avoids unnecessary search branches by pruning. The solution to the original problem consists of a series of decision-making steps, and we can regard the subsequence before each decision-making step as a sub-problem.

In fact, dynamic programming is often used to solve optimization problems. They not only contain overlapping subproblems, but also have two other properties: optimal substructure and no aftereffect.

14.2.1. optimal substructure

We slightly modify the stair climbing problem to make it more suitable for demonstrating the concept of optimal substructure.

>**Minimal Cost of Climbing Stairs**
>Given a staircase, you can go up $1$ or $2$ steps each step. Each staircase is labeled with a non-negative integer, indicating the price you need to pay for that step. Given a non-negative integer array `cost`, where $cost[i]$ represents the cost to be paid on the $ith$ step, and $cost[0]$ is the starting point on the ground. Please calculate the minimum cost to reach the top?

As shown in the following picture, if the costs of the $1st$, $2nd$ and $3rd$ steps are $1$, $10$, and $1$ respectively, then the minimum cost to climb from the ground to the $3rd$ step is $2$.

![Fig. 爬到第 3 阶的最小代价](./algos/14.2.1.1.png)

Let $dp[i]$ be the cumulative cost of climbing to the $ith$ level. Since the $ith$ level can only come from the $i-1th$ or $i-2th$ level, $dp[i]$ can only be equal to $dp[i-1]+cost[i]$ or $dp[i-2]+cost[i]$. In order to reduce the cost as much as possible, we should choose the smaller of the two, namely:

$$dp[i]=min(dp[i-1],dp[i-2])+cost[i]$$

This leads to the meaning of "optimal substructure": **the optimal solution to the original problem is constructed from the optimal solution to the subproblems**.

This problem obviously has an optimal substructure: we select the better one from the optimal solutions $dp[i-1]$, $dp[i-2]$ of the two subproblems, and use it to construct the optimal substructure of the original problem $dp[i]$. Excellent solution.

So, is there an optimal substructure for the stair climbing problem in the previous section? Its goal is to solve the number of solutions, which seems to be a counting problem, but if you ask another way: "solve the maximum number of solutions". We unexpectedly found that **although the question is equivalent before and after modification, the optimal substructure emerges**: the maximum number of solutions at the $nth$ step is equal to the sum of the maximum number of solutions at the $n-1th$ and $n-2th$ steps. Therefore, the interpretation of the optimal substructure is more flexible and has different meanings in different problems.

According to the state transition equation, and the initial state $dp[1]=cost[1]$, $dp[2]=cost[2]$, the dynamic programming code can be obtained.

```zig
// minimum cost of climbing stairs: dynamic programming
fn minCostClimbingStairsDP(comptime cost: []i32) i32 {
    comptime var n = cost.len - 1;
    if (n == 1 or n == 2) {
        return cost[n];
    }
    // initialize the dp table, used to store solutions to subproblems
    var dp = [_]i32{-1} ** (n + 1);
    // initial state: preset solution to the minimum subproblem
    dp[1] = cost[1];
    dp[2] = cost[2];
    // sate transition: solving larger sub-problems step by step from smaller sub-problems
    for (3..n + 1) |i| {
        dp[i] = @min(dp[i - 1], dp[i - 2]) + cost[i];
    }
    return dp[n];
}
```

The following picture shows the dynamic programming process of the previous code.

![Fig. 爬楼梯最小代价的动态规划过程](./algos/14.2.1.2.png)

This problem can also be space optimized, compressing one dimension to zero dimension, reducing the space complexity from $O(n)$ to $O(1)$.

```zig
// minimum cost of climbing stairs: dynamic programming after space optimization
fn minCostClimbingStairsDPComp(cost: []i32) i32 {
    var n = cost.len - 1;
    if (n == 1 or n == 2) {
        return cost[n];
    }
    var a = cost[1];
    var b = cost[2];
    // state transition: solving larger sub-problems step by step from smaller sub-problems
    for (3..n + 1) |i| {
        var tmp = b;
        b = @min(a, tmp) + cost[i];
        a = tmp;
    }
    return b;
}
```

14.2.2. No after effect

"No after effect" is one of the important characteristics of dynamic programming that can effectively solve problems. It is defined as: **given a certain state, its future development is only related to the current state, and has nothing to do with all the states that the current state has experienced in the past**.

Taking the stairs climbing problem as an example, given state $i$, it will develop state $i+1$ and state $i+2$, which correspond to jumping $1$ step and jumping $2$ steps respectively. When making these two choices, we don't need to consider the states before state $i$, they have no effect on the future of state $i$.

However, the situation is different if we add a constraint to the stairs climbing problem.

>**Climb stairs with constraint**
>Given a staircase with a total of $n$ steps, you can go up $1$ or $2$ steps each step, but you cannot jump $1$ step in two consecutive rounds. How many ways are there to climb to the top of the building?

For example, in the following picture, there are only two feasible solutions left to climb up to the third step, and the solution of jumping the first step three times in a row does not meet the constraint conditions, so it is discarded.

![Fig. 带约束爬到第 3 阶的方案数量](./algos/14.2.2.1.png)

In this problem, if you jumped $1$ step in the previous round, then you must jump $2$ steps in the next round. This means that **the choice of the next step cannot be independently determined by the current state (the current number of stairs), but is also related to the previous state (the number of stairs in the previous round)**.

It is not difficult to find that this problem does not satisfy the no after effect, and the state transition equation $dp[i]=dp[i-1]+dp[i-2]$ is also invalid, because $dp[i-1]$ represents the current round of step skipping, but it contains many "step skippng solutions of the previous round", and in order to meet the constraints, we cannot directly include $dp[i-1]$ into $dp[i]$.

To this end, we need to expand the state definition: **state $[i,j]$ means that it is at the $ith$ step and skipped $j$ levels in the previous round**, where $j\in\{1,2\}$. This state definition effectively distinguishes whether the last jump was $1$ step or $2$ steps, and we can use this to decide how to jump next.

- When $j$ is equal to $1$, that is, if you jumped $1$ step in the previous round, you can only choose to jump $2$ steps in this round.
- When $j$ is equal to $2$, that is, if you skipped $2$ steps in the previous round, you can choose to skip $1$ step or $2$ steps in this round.

As shown in the following picture, under this definition, $dp[i,j]$ represents the number of options corresponding to state $[i,j]$. The state transition equation under this definition is:
$$\begin{cases}
dp[i,1]=dp[i-1,2]\\
dp[i,2]=dp[i-2,1]+dp[i-2,2]
\end{cases}$$
![Fig. 考虑约束下的递推关系](./algos/14.2.2.2.png)

In the end, just return $dp[n,1]+dp[n,2]$, and the sum of the two represents the total number of solutions to climbed to the $nth$ step.

```zig
// constrained stair climbing: dynamic programming
fn climbingStairsConstraintDP(comptime n: usize) i32 {
    if (n == 1 or n == 2) {
        return 1;
    }
    // initialize the dp table, used to store solutions to subproblems
    var dp = [_][3]i32{ [_]i32{ -1, -1, -1 } } ** (n + 1);
    // initial state: preset solution to the minimum subproblem

    dp[1][1] = 1;
    dp[1][2] = 0;
    dp[2][1] = 0;
    dp[2][2] = 1;
    // state transition: solving larger sub-problems step by step from smaller sub-problems
    for (3..n + 1) |i| {
        dp[i][1] = dp[i - 1][2];
        dp[i][2] = dp[i - 2][1] + dp[i - 2][2];
    }
    return dp[n][1] + dp[n][2];
}
```

In the above case, since we only need to consider the previous state, we can still make the problem satisfy no aftereffects again by extending the state definition. However, some problems have very serious "repercussions."

>**Stair climbing and obstacle generation**
>Given a staircase with $n$ steps in total, you can go up $1$ or $2$ steps each step. It is stipulated that when climbing to the $ith$ step, the system will automatically place obstacles on the $2ith$ step, after which all it is not allowed to jump to the $2ith$ step. For example, if you jumped to the $2nd$ and $3rd$ steps in the first two rounds, you cannot jump to the $4th$ and $6th$ steps after that. How many ways are there to climb to the top of the building?

In this problem, the next jump depends on all past states, because each jump places obstacles higher up the ladder and affects future jumps. For such problems, dynamic programming is often difficult to solve.

In fact, many complex combinatorial optimization problems (such as the traveling salesman problem) do not satisfy the after effect-free property. For this type of problem, we usually choose to use other methods, such as heuristic search, genetic algorithm, reinforcement learning, etc., so as to obtain the available local optimal solution in a limited time.

14.3. Dynamic programming solutions ideas

The previous two sections introduced the main characteristics of dynamic programming problems. Next, we explore two more practical problems together.

1. How to estimate whether a problem is a dynamic programming problem?
2. Where should I start to solve the dynamic programming problem, and what are the complete steps?

14.3.1. problem estimation

In general, if a problem contains overlapping subproblems, optimal substructure, and satisfies no aftereffects, then it is usually suitable to be solved by dynamic programming. However, it is difficult for us to directly extract these features from the problem description. Therefore, we usually relax the conditions and **first observe whether the problem is suitable to be solved using backtracking (exhaustive)**.

**Problems suitable for backtracking usually satisfy the "decision tree model"**, which can be described using a tree structure, where each node represents a decision, and each path represents a decision sequence.

In other words, if a problem contains a well-defined notion of decision making, and the solution arises through a sequence of decisions, then it satisfies the decision tree model and can usually be solved using backtracking.

On this basis, there are some "bonus items" for estimating dynamic programming problems.

- Problems contain optimization descriptions such as maximum (minimum) or most (few).
- The state of the problem can be represented by a list, multidimensional matrix or tree, and a state has a recursive relationship with its surrounding states.

Correspondingly, there are some "minus items".

- The goal of the problem is to find all possible solutions, not to find the optimal solution.
- There are obvious permutations and combinations in the problem description, and multiple specific solutions need to be returned.

If a problem satisfies the decision tree model and has obvious "bonus items", we can assume that it is a dynamic programming problem and verify it during the solution process.

14.3.2. problem solving steps

The problem-solving process of dynamic programming will vary depending on the nature and difficulty of the problem, but generally follows the following steps: describe the decision, define the state, build the dp table, derive the state transition equation, determine the boundary conditions, etc.

In order to show the problem-solving steps more vividly, we use a classic problem "minimum path sum" as an example.

>**Question**
>Given a $n \times m$ two-dimensional grid `grid`, each cell in the grid contains a non-negative integer representing the cost of that cell. The robot takes the upper left cell as the starting point, and can only move down or to the right one step at a time until it reaches the lower right cell. Please return the minimum sum of paths from top left to bottom right.

The following picture shows an example where the minimum path sum for a given grid is 13.

![Fig. 最小路径和示例数据](./algos/14.3.2.0.1.png)

**Step 1: think about the decision-making of each round, define the state, and get the dp table**

The decision for each round of this problem is to take a step down or to the right from the current cell. Assuming that the row and column index of the current grid is $[i,j]$, after one step down or to the right, the index becomes $[i+1,j]$ or $[i,j+1]$. Therefore, the state should contain two variables, row index and column index, denoted as $[i,j]$.

The sub-problem corresponding to the state $[i,j]$ is: the minimum path sum from the starting point $[0,0]$ to $[i,j]$, denoted as $dp[i,j]$.

So far, we have obtained a two-dimensional $dp$ matrix with the same size as the input grid `grid`.

![Fig. 状态定义与 dp 表](./algos/14.3.2.0.2.png)

>**Note**
>The dynamic programming and backtracking process can be described as a sequence of decisions, and the state consists of all decision variables. It should contain all the variables describing the progress of the problem, and it should contain enough information to be able to deduce the next state.
>
>Each state corresponds to a sub-problem. We will define a $dp$ table to store the solutions of all sub-problems. Each independent variable of the state is a dimension of the $dp$ table. Essentially, a $dp$ table is a mapping between the state and the solution to a subproblem.

**Step 2: Find the optimal substructure, and then derive the state transition equation**

For the state $[i,j]$, it can only be accessed from the upper grid $[i-1,j]$ and the left grid $[i,j-1]$. Therefore, the optimal substructure is: the minimum path sum to reach $[i,j]$ is determined by the smaller of the minimum path sum of $[i,j-1]$ and the minimum path sum of $[i-1,j]$.

Based on the above analysis, the following state transition equation can be deduced:

$$dp[i,j]=min(dp[i-1,j],dp[i,j-1])+grid[i,j]$$

![Fig. 最优子结构与状态转移方程](./algos/14.3.2.0.3.png)

>**Note**
>According to the defined $dp$ table, consider the relationship between the original problem and the sub-problem, and find out the method of constructing the optimal solution of the original problem through the optimal solution of the sub-problem, that is, the optimal substructure.

Once we have found the optimal substructure, we can use it to construct state transition equations.

**Step 3: Determine boundary conditions and state transition sequence**

In this problem, the state in the first row can only be transferred to the right, and the state in the first column can only be transferred downwards, so the first row $i=0$ and the first column $j=0$ are boundary conditions.

As shown in the following picture, since each cell is transferred from the cell to its left and the cell above it, we use a loop to traverse the matrix, an outer loop to traverse the rows, and an inner loop to traverse the columns.

![Fig. 边界条件与状态转移顺序](./algos/14.3.2.0.4.png)

>**Note**
>Boundary conditions are used in dynamic programming to initialize the $dp$ table and in search for pruning.
>
>The core of the state transition sequence is to ensure that when the solution of the current problem is calculated, the solutions of all the smaller sub-problems it depends on have been correctly calculated.

According to the above analysis, we can already write the dynamic programming code directly. However, sub-problem decomposition is a top-down thinking, so it is more in line with thinking habits to implement in the order of "brute force search $\to$ memory search $\to$ dynamic programming".

1. Method 1: Brute force search

Starting with the state $[i,j]$, the search is continuously broken down into smaller states $[i-1,j]$ and $[i,j-1]$, and the recursive function includes the following elements:

- **Recursive parameter**: state $[i,j]$.
- **Return value**: the minimum path from $[0,0]$ to $[i,j]$ and $dp[i,j]$.
- **Termination condition**: when $i=0$ and $j=0$, return the cost $grid[0,0]$.
- **Pruning**: When $i<0$ or $j<0$, the index is out of bounds, and the return cost $+\infty$ means it is not feasible.

```zig
// minimum path sum: brute force search
fn minPathSumDFS(grid: anytype, i: i32, j: i32) i32 {
    // if it is a cell in the upper left corner, the search is terminated
    if (i == 0 and j == 0) {
        return grid[0][0];
    }
    // if the row and column index is out of bounds, the +∞ cost is returned
    if (i < 0 or j < 0) {
        return std.math.maxInt(i32);
    }
    // calculates the minimum path cost from the upper-left corner to (i-1, j) and (i, j-1)
    var left = minPathSumDFS(grid, i - 1, j);
    var up = minPathSumDFS(grid, i, j - 1);
    // returns the minimum path cost from the upper-left corner to (i, j)
    return @min(left, up) + grid[@as(usize, @intCast(i))][@as(usize, @intCast(j))];
}
```

The following picture shows a recursive tree with $dp[2,1]$ as the root node, which contains some overlapping sub-problems, the number of which will increase dramatically as the size of the grid grid increases.

Essentially, the overlapping subproblem is caused by the fact that **there are multiple paths to reach a cell from the upper left corner**.

![Fig. 暴力搜索递归树](./algos/14.3.2.1.png)

Each state has two choices: down and right. It takes $m+n-2$ steps to go from the upper left corner to the lower right corner, so the worst time complexity is $O(2^{m+n})$. Note that this calculation does not take into account the proximity to the grid boundary, leaving only one choice when reaching the network boundary. So the actual number of paths will be less.

2. Method 2: Memory search

We introduce a memory list `mem` of the same size as `grid` to record the solution of each sub-problem and prune overlapping sub-problems.

```zig
// minimum path sum: memoized search
fn minPathSumDFSMem(grid: anytype, mem: anytype, i: i32, j: i32) i32 {
    // if it is a cell in the upper left corner, the search is terminated
    if (i == 0 and j == 0) {
        return grid[0][0];
    }
    // if the row and column index is out of bounds, the +∞ cost is returned
    if (i < 0 or j < 0) {
        return std.math.maxInt(i32);
    }
    // if there is already a record, return it directly
    if (mem[@as(usize, @intCast(i))][@as(usize, @intCast(j))] != -1) {
        return mem[@as(usize, @intCast(i))][@as(usize, @intCast(j))];
    }
    // calculates the minimum path cost from the upper-left corner to (i-1, j) and (i, j-1)
    var left = minPathSumDFSMem(grid, mem, i - 1, j);
    var up = minPathSumDFSMem(grid, mem, i, j - 1);
    // returns the minimum path cost from the upper-left corner to (i, j)
    // records and return the minimum path cost from the upper left corner to (i, j)
    mem[@as(usize, @intCast(i))][@as(usize, @intCast(j))] = @min(left, up) + grid[@as(usize, @intCast(i))][@as(usize, @intCast(j))];
    return mem[@as(usize, @intCast(i))][@as(usize, @intCast(j))];
}
```

As shown in the following picture, after the introduction of memoization, the solutions of all subproblems only need to be calculated once, so the time complexity depends on the total number of states, that is, the grid size $O(nm)$.

![Fig. 记忆化搜索递归树](./algos/14.3.2.2.png)

3. Method Three: Dynamic Programming

Dynamic programming solution based on iteration.

```zig
// minimum path sum: dynamic programming
fn minPathSumDP(comptime grid: anytype) i32 {
    comptime var n = grid.len;
    comptime var m = grid[0].len;
    // initialize dp table
    var dp = [_][m]i32{[_]i32{0} ** m} ** n;
    dp[0][0] = grid[0][0];
    // state transition: first row
    for (1..m) |j| {
        dp[0][j] = dp[0][j - 1] + grid[0][j];
    }
    // state transfer: first column
    for (1..n) |i| {
        dp[i][0] = dp[i - 1][0] + grid[i][0];
    }
    // state transition: remaining rows and columns
    for (1..n) |i| {
        for (1..m) |j| {
            dp[i][j] = @min(dp[i][j - 1], dp[i - 1][j]) + grid[i][j];
        }
    }
    return dp[n - 1][m - 1];
}
```

The following picture shows the state transition process of the minimum path sum, which traverses the entire grid, so the time complexity is $O(nm)$.

The array dp has size $n \times m$, so the space complexity is $O(nm)$.

![<1>](./algos/14.3.2.3-1.png) ![<2>](./algos/14.3.2.3-2.png) ![<3>](./algos/14.3.2.3-3.png) ![<4>](./algos/14.3.2.3-4.png) ![<5>](./algos/14.3.2.3-5.png) ![<6>](./algos/14.3.2.3-6.png) ![<7>](./algos/14.3.2.3-7.png) ![<8>](./algos/14.3.2.3-8.png) ![<9>](./algos/14.3.2.3-9.png) ![<10>](./algos/14.3.2.3-10.png) ![<11>](./algos/14.3.2.3-11.png) ![<12>](./algos/14.3.2.3-12.png)

4. space optimization

Since each cell is only related to the cell on its left and above, we can implement the $dp$ table with only a single row array.

Please note that because the array `dp` can only represent the state of one row, we cannot initialize the state of the first column in advance, but update it while traversing each row.

```zig
// minimum path sum: dynamic programming after spatial optimization
fn minPathSumDPComp(comptime grid: anytype) i32 {
    comptime var n = grid.len;
    comptime var m = grid[0].len;
    // initialize dp table
    var dp = [_]i32{0} ** m;
    // state transition: first row
    dp[0] = grid[0][0];
    for (1..m) |j| {
        dp[j] = dp[j - 1] + grid[0][j];
    }
    // state transition: remaining rows
    for (1..n) |i| {
        // state transfer: first column
        dp[0] = dp[0] + grid[i][0];
        for (1..m) |j| {
            dp[j] = @min(dp[j - 1], dp[j]) + grid[i][j];
        }
    }
    return dp[m - 1];
}
```

14.4. 0-1 bag problem

The bag problem is a very good introduction to dynamic programming and is the most common form of problem in dynamic programming. It has many variants such as 0-1 bag problem, full bag problem, multiple bag problem, etc.

In this section, we first solve the most common 0-1 bag problem.

>**Question**
>Given $n$ items, the $ith$ item has weight $wgt[i-1]$, value $val[i-1]$, and a bag with capacity $cap$. Each item can be selected only once, and it is asked what is the maximum value of an item that can be put into the bag without exceeding its capacity.

Observe the following picture, since the item number $i$ starts counting from $1$ and the array index starts counting from $0$, them item $i$ corresponds to weight $wgt[i-1]$ and value $val[i-1]$.

![Fig. 0-1 背包的示例数据](./algos/14.4.0.png)

We can think of the 0-1 bag problem as a process consisting of $n$ rounds of decisions. Each object has two decisions, whether to put it in or not, so the problem satisfies the decision tree model.

The goal of this problem is to solve the "maximum value under the limited bag capacity", so it is most likely a dynamic programming problem.

**Step 1: think about the decision-making of each round, define the state, and get the $dp$ table**

For each item, if it is not placed in the bag, the capacity of the bag will remain the same; if it is placed in the bag, the capacity of the bag will decrease. From this, the state definition can be obtained: the current item number $i$ and the remaining bag capacity $c$, denoted as $[i,c]$.

The sub-problem corresponding to the state $[i,c]$ is: the maximum value of the first $i$ items in the bag with a remaining capacity of $c$, denoted as $dp[i,c]$.

What is to be solved is $dp[n,cap]$, so a two-dimensional $dp$ table of size $(n+1)\times(cap+1)$ is required.

**Step 2: Find the optimal substructure, and then derive the state transition equation**

When we make a decision on item $i$, what remains is the decision of the first $i-1$ item, which can be divided into the following two situations.

- **Do not put item $i$**: the capacity of the bag remains unchanged, and the status changes to $[i-1,c]$.
- **Put item $i$**: the capacity of the bag decreases by $wgt[i-1]$, the value increases by $val[i-1]$, and the state shifts to $[i-1,c-wgt[i-1]]$.

The above analysis reveals to us the optimal substructure of this problem: the maximum value $dp[i,c]$ is equal to the one with the greater value of the two options of not putting the item $i$ and putting the item $i$. From this, the state transition equation can be deduced:
$$dp[i,c]=max(dp[i-1,c],dp[i-1,c-wgt[i-1]]+val[i-1])$$
It should be noted that if the current item weight $wgt[i-1]$ exceeds the remaining bag capacity $c$, you can only choose not to put it in the bag.

**Step 3: Determine boundary conditions and state transition sequence**

When there is no item or no remaining bag capacity, the maximum value is $0$, that is, the first column $dp[i,0]$ and the first row $dp[0,c]$ are both equal to $0$.

The current state $[i,c]$ is transitioned from the upper state $[i-1,c]$ and the upper left state $[i-1,c-wgt[i-1]]$, so the entire dp table can be traversed in a positive order through two layers of loops.

According to the above analysis, we will implement brute force search, memory search, and dynamic programming solution in order.

1. Method 1: Brute force search

The search code consists of the following elements:

- **Recursive parameter**: state $[i,c]$.
- **Return value**: the solution $dp[i,c]$ of the subproblem.
- **Termination condition**: when the item number exceeds $i=0$ or the remaining capacity of the bag is $0$, terminate the recursion and return a value of $0$.
- **Pruning**: if the weight of the current item exceeds the remaining capacity of the bag, it must not be put into the bag.

```zig
// 0-1 bag: brute force search
fn knapsackDFS(wgt: []i32, val: []i32, i: usize, c: usize) i32 {
    // if all items have been selected or the bag has no capacity, the return value is 0
    if (i == 0 or c == 0) {
        return 0;
    }
    // if it exceeds the capacity of the bag, it can only not be put into the bag
    if (wgt[i - 1] > c) {
        return knapsackDFS(wgt, val, i - 1, c);
    }
    // calculate the maximum value of the item i without and with the item i
    var no = knapsackDFS(wgt, val, i - 1, c);
    var yes = knapsackDFS(wgt, val, i - 1, c - @as(usize, @intCast(wgt[i - 1]))) + val[i - 1];
    // returns the greater value of the two options
    return @max(no, yes);
}
```

As shown in the following picture, since each item will generate two search branches of not selecting and selecting, the time complexity is $O(2^n)$.

Observing the recursion tree, it is easy to find that there are overlapping sub-problems, such as $dp[1,10]$, etc. However, when there are many items and the bag capacity is large, especially when there are many items of the same weight, the number of overlapping sub-problems will increase significantly.

![Fig. 0-1 背包的暴力搜索递归树](./algos/14.4.1.png)

2. Method 2: Memorized search

In order to ensure that the overlapping subproblems are only evaluated once, we record the solutions of the subproblems with the help of a memory list `mem`, where `mem[i][c]` corresponds to $dp[i,c]$.

After the introduction of memoization, **the time complexity depends on the number of sub-problems**, which is $O(n\times cap)$.

```zig
// 0-1 bag: memoized search
fn knapsackDFSMem(wgt: []i32, val: []i32, mem: anytype, i: usize, c: usize) i32 {
    // if all items have been selected or the backpack has no capacity, the return value is 0
    if (i == 0 or c == 0) {
        return 0;
    }
    // if there is a record, return it directly
    if (mem[i][c] != -1) {
        return mem[i][c];
    }
    // if it exceeds the capacity of the backpack, it can only not be put into the backpack
    if (wgt[i - 1] > c) {
        return knapsackDFSMem(wgt, val, mem, i - 1, c);
    }
    // calculate the maximum value of the item i without and with the item i
    var no = knapsackDFSMem(wgt, val, mem, i - 1, c);
    var yes = knapsackDFSMem(wgt, val, mem, i - 1, c - @as(usize, @intCast(wgt[i - 1]))) + val[i - 1];
    // record and return the value of the two alternatives whichever is greater
    mem[i][c] = @max(no, yes);
    return mem[i][c];
}
```

The following picture shows the pruned search branches in memoized recursion.

![Fig. 0-1 背包的记忆化搜索递归树](./algos/14.4.2.png)

3. Method 3: Dynamic Programming

Dynamic programming is essentially the process of filling the $dp$ table in the state transition, the code is as follows.

```zig
// 0-1 bag: dynamic programming
fn bagDP(comptime wgt: []i32, val: []i32, comptime cap: usize) i32 {
    comptime var n = wgt.len;
    // initialize dp table
    var dp = [_][cap + 1]i32{[_]i32{0} ** (cap + 1)} ** (n + 1);
    // state transition
    for (1..n + 1) |i| {
        for (1..cap + 1) |c| {
            if (wgt[i - 1] > c) {
                // if the capacity of the bag is exceeded, the item i will not be selected
                dp[i][c] = dp[i - 1][c];
            } else {
                // the greater value of the two options of not choosing and choosing item i
                dp[i][c] = @max(dp[i - 1][c], dp[i - 1][c - @as(usize, @intCast(wgt[i - 1]))] + val[i - 1]);
            }
        }
    }
    return dp[n][cap];
}
```

As shown in the following picture, the time complexity and space complexity are determined by the size of the array $dp$, that is, $O(n \times cap)$.

![<1>](./algos/14.4.3-1.png) ![<2>](algos/14.4.3-2.png) ![<3>](algos/14.4.3-3.png) ![<4>](algos/14.4.3-4.png) ![<5>](algos/14.4.3-5.png) ![<6>](algos/14.4.3-6.png) ![<7>](algos/14.4.3-7.png) ![<8>](algos/14.4.3-8.png) ![<9>](algos/14.4.3-9.png) ![<10>](algos/14.4.3-10.png) ![<11>](algos/14.4.3-11.png) ![<12>](algos/14.4.3-12.png) ![<13>](algos/14.4.3-13.png) ![<14>](algos/14.4.3-14.png)

4. state compression

Since each state is only related to the state of the row above it, we can use two arrays to roll forward, reducing the space complexity from $O(n^2)$ to $O(n)$.

Thinking further, can we achieve space optimization with only one array? It can be seen that each state is transferred from the grid directly above or to the upper left. Assuming that there is only one array, when starting to traverse the $ith$ row, the array still stores the state of the $i-1th$ row.

- If traversing in positive order is adopted, when traversing to $dp[i,j]$, the values of $dp[i-1,1] \sim dp[i-1,j-1]$ on the upper left may have been overwritten and the correct state transition result cannot be obtained at this time.
- If reverse order traversal is adopted, there will be no overwriting problem, and the state transfer can be performed correctly.

The following picture shows the transition from row i=1 to row i=2 under a single array. Please consider the difference between forward order traversal and reverse order traversal.

![<1>](./algos/14.4.4-1.png) ![<2>](./algos/14.4.4-2.png) ![<3>](./algos/14.4.4-3.png) ![<4>](./algos/14.4.4-4.png) ![<5>](./algos/14.4.4-5.png) ![<6>](./algos/14.4.4-6.png)

In the code implementation, we only need to delete the first dimension $i$ of the array `dp` directly, and change the inner loop to reverse order traversal.

```zig
// 0-1 bag: dynamic programming after space optimization
fn bagDPComp(wgt: []i32, val: []i32, comptime cap: usize) i32 {
    var n = wgt.len;
    // initialize dp table
    var dp = [_]i32{0} ** (cap + 1);
    // state transition
    for (1..n + 1) |i| {
        // reverse order traversal
        var c = cap;
        while (c > 0) : (c -= 1) {
            if (wgt[i - 1] < c) {
                // the greater value of the two options of not choosing and choosing item i
                dp[c] = @max(dp[c], dp[c - @as(usize, @intCast(wgt[i - 1]))] + val[i - 1]);
            }
        }
    }
    return dp[cap];
}
```

14.5. full bag problem

In this section, we first solve another common bag problem: the full bag problem, and then look at a special case of it: coin change.

14.5.1. full bag

Question
Given $n$ items, the $ith$ item has weight $wgt[i-1]$, value $val[i-1]$, and a bag with capacity $cap$. **Each item can be selected repeatedly**, and the question is what is maximum value of the item that can be placed within the bag capacity.

![Fig. 完全背包问题的示例数据](./algos/14.5.1.0.png)

1. dynamic programming ideas

The full bag problem is very similar to the 0-1 bag problem, **except that it does not limit the number of item choices**.

- In the 0-1 bag, there is only one of each item, so after putting item $i$ in the bag, you can only choose from the first $i-1$ items.
- In full bag, there are infinite number of each item, so after putting item $i$ in bag, **you can still choose from the previous $i$ items**.

Under the full bag rule, the change of state $[i,c]$ is divided into two cases.

- **Don't put item $i$**: Same as 0-1 bag, transition to $[i-1,c]$.
- **Put item $i$**: different from 0-1 bag, transfer to [i,c-wtg[i-1]].

So the state transition equation becomes:
$$dp[i,c]=max(dp[i-1,c],dp[i,c-wgt[i-1]]+val[i-1])$$

2. Code

Comparing the codes of the two questions, one of the state transitions changes from $i-1$ to $i$, and the rest is exactly the same.

```zig
// full bag: dynamic programming
fn unboundedBagDP(comptime wgt: []i32, val: []i32, comptime cap: usize) i32 {
    comptime var n = wgt.len;
    // initialize dp table
    var dp = [_][cap + 1]i32{[_]i32{0} ** (cap + 1)} ** (n + 1);
    // state transition
    for (1..n + 1) |i| {
        for (1..cap + 1) |c| {
            if (wgt[i - 1] > c) {
                // if the capacity of the backpack is exceeded, the item i will not be selected
                dp[i][c] = dp[i - 1][c];
            } else {
                // the greater value of the two options of not choosing and choosing item i
                dp[i][c] = @max(dp[i - 1][c], dp[i][c - @as(usize, @intCast(wgt[i - 1]))] + val[i - 1]);
            }
        }
    }
    return dp[n][cap];
}
```

3. space optimization

Since the current state is transferred from the state on the left and above, each row in the $dp$ table should be traversed in positive order after space optimization.

This traversal order is the exact opposite of the 0-1 bag. Please use the following picture to understand the difference between the two.

![<1>](./algos/14.5.1.3-1.png) ![<2>](./algos/14.5.1.3-2.png) ![<3>](./algos/14.5.1.3-3.png) ![<4>](./algos/14.5.1.3-4.png) ![<5>](./algos/14.5.1.3-5.png) ![<6>](./algos/14.5.1.3-6.png)

The code implementation is relatively simple, only need to delete the first dimension of the array $dp$.

```zig
// full bag: dynamic programming after space optimization
fn unboundedKnapsackDPComp(comptime wgt: []i32, val: []i32, comptime cap: usize) i32 {
    comptime var n = wgt.len;
    // initialize dp table
    var dp = [_]i32{0} ** (cap + 1);
    // state transition
    for (1..n + 1) |i| {
        for (1..cap + 1) |c| {
            if (wgt[i - 1] > c) {
                // if the capacity of the backpack is exceeded, the item i will not be selected
                dp[c] = dp[c];
            } else {
                // the greater value of the two options of not choosing and choosing item i
                dp[c] = @max(dp[c], dp[c - @as(usize, @intCast(wgt[i - 1]))] + val[i - 1]);
            }
        }
    }
    return dp[cap];
}
```

14.5.2. coin change problem

The bag problem is representative of a large class of dynamic programming problems, which have many variants, such as the coin change problem.

>**Question**
>Given $n$ kinds of coins, the face value of the $ith$ coin is $coins[i-1]$, and the target amount is $amt$. **Each coin can be selected repeatedly**, and the question is what is the minimum number of coins that can make up the target amount. Returns $-1$ if the target amount cannot be made.

![Fig. 零钱兑换问题的示例数据](./algos/14.5.2.0.png)

1. dynamic programming ideas

**coin change can be regarded as a special case of full bag**, the two have the following connections and differences.

- The two questions can be interchanged, "item" corresponds to "coin", "item weight" corresponds to "coin face value", and "bag capacity" corresponds to "target amount".
- In contrast to the optimization objective, the bag problem is to maximize the item value, and the coin change problem is to minimize the number of coins.
- The bag problem is to find a solution that "does not exceed" the bag capacity, and the coin change is to find a solution that "exactly" reaches the target amount.

**Step 1: think about the decision-making of each round, define the state, and get the $dp$ table**

The sub-problem corresponding to the state $[i,a]$ is: **the first $i$ coins that can make up the minimum number of coins of the amount $a$**, denoted as $dp[i,a]$.

The size of the two-dimensional $dp$ table is $(n+1)\times(amt+1)$.

**Step 2: Find the optimal substructure, and then derive the state transition equation**

There are two differences between this question and the state transition equation of the full bag.

- This problem requires a minimum value, so the operator $max()$ needs to be changed to $min()$.
- The optimization subject is the number of coins rather than the value of the product, so $+1$ is sufficient when the coin is selected.
$$dp[i,a]=min(dp[i-1,a],dp[i,a-coins[i-1]]+1)$$

**Step 3: Determine boundary conditions and state transition sequence**

When the target amount is $0$, the minimum number of coins to collect is $0$, that is, all $dp[i,0]$ in the first column are equal to $0$.

When there is no coin, it is impossible to make any target amount $>0$, which is an invalid solution. In order for the $min()$ function in the state transition equation to identify and filter invalid solutions, we consider using $+\infty$ to represent them, that is, all $dp[0,a]$ in the first row are equal to $+\infty$.

2. Code

Most programming languages do not provide a $+\infty$ variable, and can only use the maximum value of the integer type `int` instead. And this will lead to a large number out of bounds: the $+1$ operation in the state transition equation may overflow.

For this reason, we use the number $amt+1$ to represent an invalid solution, because the number of coins that can be coined for $amt$ is at most $amt$.

Before returning at the end, estimate whether $dp[n,amt]$ is equal to $amt+1$, if so, return $-1$, which means that the target amount cannot be collected.

```zig
// coin change: dynamic programming
fn coinChangeDP(comptime coins: []i32, comptime amt: usize) i32 {
    comptime var n = coins.len;
    comptime var max = amt + 1;
    // initialize dp table
    var dp = [_][amt + 1]i32{[_]i32{0} ** (amt + 1)} ** (n + 1);
    // state transition: first row first column
    for (1..amt + 1) |a| {
        dp[0][a] = max;
    }
    // state transition: remaining rows and columns
    for (1..n + 1) |i| {
        for (1..amt + 1) |a| {
            if (coins[i - 1] > @as(i32, @intCast(a))) {
                // if it exceeds the capacity of the backpack, do not choose the coin i
                dp[i][a] = dp[i - 1][a];
            } else {
                // the smaller value of the two schemes of not choosing and choosing coin i
                dp[i][a] = @min(dp[i - 1][a], dp[i][a - @as(usize, @intCast(coins[i - 1]))] + 1);
            }
        }
    }
    if (dp[n][amt] != max) {
        return @intCast(dp[n][amt]);
    } else {
        return -1;
    }
}
```

The following picture shows the dynamic programming process of coin change, which is very similar to the full bag.

![<1>](./algos/14.5.2.2-1.png) ![<2>](./algos/14.5.2.2-2.png) ![<3>](./algos/14.5.2.2-3.png) ![<4>](./algos/14.5.2.2-4.png) ![<5>](./algos/14.5.2.2-5.png) ![<6>](./algos/14.5.2.2-6.png) ![<7>](./algos/14.5.2.2-7.png) ![<8>](./algos/14.5.2.2-8.png) ![<9>](./algos/14.5.2.2-9.png) ![<10>](./algos/14.5.2.2-10.png) ![<11>](./algos/14.5.2.2-11.png) ![<12>](./algos/14.5.2.2-12.png) ![<13>](./algos/14.5.2.2-13.png) ![<14>](./algos/14.5.2.2-14.png) ![<15>](./algos/14.5.2.2-15.png)

3. space optimization

The space optimization of the coin change is handled in the same way as the full bag.

```zig
// coin change: dynamic programming after space optimization
fn coinChangeDPComp(comptime coins: []i32, comptime amt: usize) i32 {
    comptime var n = coins.len;
    comptime var max = amt + 1;
    // initialize dp table
    var dp = [_]i32{0} ** (amt + 1);
    @memset(&dp, max);
    dp[0] = 0;
    // state transition
    for (1..n + 1) |i| {
        for (1..amt + 1) |a| {
            if (coins[i - 1] > @as(i32, @intCast(a))) {
                // if it exceeds the target amount, do not choose the coin i
                dp[a] = dp[a];
            } else {
                // the smaller value of the two options of not choosing and choosing coin i
                dp[a] = @min(dp[a], dp[a - @as(usize, @intCast(coins[i - 1]))] + 1);
            }
        }
    }
    if (dp[amt] != max) {
        return @intCast(dp[amt]);
    } else {
        return -1;
    }
}
```

14.5.3. coin change Problem II

Question
Given $n$ kinds of coins, the face value of the $ith$ coin is $coins[i-1]$, and the target amount is $amt$. Each coin can be selected repeatedly, what is the number of coin combinations to get the target amount?

![Fig. 零钱兑换问题 II 的示例数据](./algos/14.5.3.0.png)

1. dynamic programmin ideas

Compared with the previous question, the goal of this question is the number of combinations, so the sub-problem becomes: **the first $i$ coins that can make up the number of combinations of amount $amt$**. And the $dp$ table is still a two-dimensional matrix of size $(n+1)\times(amt+1)$.

The number of combinations for the current state is equal to the sum of the number of combinations for the decisions not to choose the current coin and to choose the current coin. The state transition equation is:
$$dp[i,a]=dp[i-1,a]+dp[i,a-coins[i-1]]$$
When the target amount is $0$, the target amount can be collected without selecting any coin, so all $dp[i,0]$ in the first column should be initialized to $1$. When there are no coins, it is impossible to make any target amount $>0$, so all $dp[0,a]$ in the first line are equal to $0$.

2. ode

```zig
// coin change II: II: dynamic programming
fn coinChangeIIDP(comptime coins: []i32, comptime amt: usize) i32 {
    comptime var n = coins.len;
    // initialize dp table
    var dp = [_][amt + 1]i32{[_]i32{0} ** (amt + 1)} ** (n + 1);
    // initialize the first column
    for (0..n + 1) |i| {
        dp[i][0] = 1;
    }
    // state transition
    for (1..n + 1) |i| {
        for (1..amt + 1) |a| {
            if (coins[i - 1] > @as(i32, @intCast(a))) {
                // if it exceeds the target amount, do not choose the coin i
                dp[i][a] = dp[i - 1][a];
            } else {
                // the smaller value of the two options of not choosing and choosing coin i
                dp[i][a] = dp[i - 1][a] + dp[i][a - @as(usize, @intCast(coins[i - 1]))];
            }
        }
    }
    return dp[n][amt];
}
```

3. space optimization

State compression is handled in the same way, just remove the coin dimension.

```zig
// coin change II: dynamic programming after space optimization
fn coinChangeIIDPComp(comptime coins: []i32, comptime amt: usize) i32 {
    comptime var n = coins.len;
    // initialize dp table
    var dp = [_]i32{0} ** (amt + 1);
    dp[0] = 1;
    // state transition
    for (1..n + 1) |i| {
        for (1..amt + 1) |a| {
            if (coins[i - 1] > @as(i32, @intCast(a))) {
                // if it exceeds the target amount, do not choose the coin i
                dp[a] = dp[a];
            } else {
                // the smaller value of the two schemes of not choosing and choosing coin i
                dp[a] = dp[a] + dp[a - @as(usize, @intCast(coins[i - 1]))];
            }
        }
    }
    return dp[amt];
}
```

14.6. Edit distance problem

Edit distance, also known as Levenshtein distance, refers to the minimum number of modifications between two strings and is usually used to measure the similarity of two sequences in information retrieval and natural language processing.

>**Question**
>Given two strings $s$ and $t$, return the minimum number of edit steps required to convert $s$ to $t$.
>
>You can perform three editing operations in a string: insert a character, delete a character, and replace a character with any character.

As shown in the following picture, converting `kitten` to `sitting` requires 3 editing steps, including 2 replacement operations and 1 addition operation; converting `hello` to `algo` requires 3 steps, including 2 replacement operations and 1 deletion operation.

![Fig. 编辑距离的示例数据](./algos/14.6.0.1.png)

**The edit distance problem can be explained naturally with a decision tree model**. Strings correspond to tree nodes, and a decision round (an edit operation) corresponds to an edge of the tree.

As shown in the followin picture, in the case of unlimited operations, each node can derive many edges, and each edge corresponds to an operation, which means that there are many possible paths from `hello` to `algo`.

From the perspective of decision tree, the goal of this problem is to find the shortest path between node `hello` and node `algo`.

![Fig. 基于决策树模型表示编辑距离问题](./algos/14.6.0.2.png)

1. dynamic programming ideas

**Step 1: think about the decision-making of each round, define the state, and get the dp table**

The decision in each round is to perfrom an edit operation on the string $s$.

We hope that during the edit operation, the size of the problem will gradually shrink so that sub-problems can be constructed. Let the lengths of strings $s$ and $t$ be $n$ and $m$ respectively, we first consider the characters $s[n-1]$ and $t[m-1]$ at the end of the two strings.

- If $s[n-1]$ and $t[m-1]$ are the same, we can skip them and consider $s[n-2]$ and $t[m-2]$ directly.
- If s[n-1] and t[m-1] are different, we need to edit $s$ once (insert, delete, replace) so that the characters at the end of the two strings are the same, so that they can be skipped and consider smaller problems.

That is to say, each round of decision-making (edit operation) we make in the string $s$ will change the remaining characters to be matched in $s$ and $t$. Therefore, the state is the $ith$ and $jth$ character currently considered in $s$ and $t$, denoted as $[i,j]$.

Subproblem corresponding to state [i,j]: **the minimum number of editing steps required to change the first $i$ characters of $s$ to the first $j$ characters of $t$**.

At this point, a two-dimensional $dp$ table with size $(i+1)\times(j+1)$ is obtained.

**Step 2: Find the optimal substructure, and then derive the state transition equation**

Consider the sub-problem $dp[i,j]$, the tail characters of the corresponding two strings are $s[i-1]$ and $t[j-1]$, which can be divided into three cases as shown in the following picture according to different editing operations.

1. Adding $t[j-1]$ after $s[i-1]$ leaves the remaining subproblem $dp[i,j-1]$.
2. Delete $s[i-1]$, then the sub-problem $dp[i-1,j]$ remains.
3. Replace $s[i-1]$ with $t[j-1]$, then the subproblem $dp[i-1,j-1]$ remains.

![Fig. 编辑距离的状态转移](./algos/14.6.1.png)

According to the above analysis, the optimal substructure can be obtained: the minimum number of editing steps of $dp[i,j]$ is equal to the minimum number of editing steps among $dp[i,j-1]$, $dp[i-1,j]$, $dp[i-1,j-1]$, plus the number of editing steps this time $1$. The corresponding state transition equation is:
$$dp[i,j]=min(dp[i,j-1],dp[i-1,j],dp[i-1,j-1])+1$$
Please note that when $s[i-1]$ and $t[j-1]$ are the same, there is no need to edit the current character, the state transition equation in this case is:
$$dp[i,j]=dp[i-1,j-1]$$

**Step 3: Determine boundary conditions and state transition sequence**

When both strings are empty, the number of edit steps is $0$, that is, $dp[0,0]=0$. When $s$ is empty but $t$ is not, the minimum number of editing steps is equal to the length of $t$, that is, the first row $dp[0,j]=j$. When $s$ is not empty but $t$ is empty, it is equal to the length of $s$, that is, the first column $dp[i,0]=i$.

Observing the state transition equation, the solution of $dp[i,j]$ depends on the solutions on the left, upper, and upper left, so it is enough to traverse the entire $dp$ table in positive order through a two-layer loop.

2. code

```zig
// edit distance: dynamic programming
fn editDistanceDP(comptime s: []const u8, comptime t: []const u8) i32 {
    comptime var n = s.len;
    comptime var m = t.len;
    var dp = [_][m + 1]i32{[_]i32{0} ** (m + 1)} ** (n + 1);
    // state transition: first row first column
    for (1..n + 1) |i| {
        dp[i][0] = @intCast(i);
    }
    for (1..m + 1) |j| {
        dp[0][j] = @intCast(j);
    }
    // state transition: remaining rows and columns
    for (1..n + 1) |i| {
        for (1..m + 1) |j| {
            if (s[i - 1] == t[j - 1]) {
                // if the two characters are equal, skip the two characters directly
                dp[i][j] = dp[i - 1][j - 1];
            } else {
                // minimum number of editing steps:
                // minimum number of editing steps for the three operations
                // of inserting, deleting, and replacing + 1
                dp[i][j] = @min(@min(dp[i][j - 1], dp[i - 1][j]), dp[i - 1][j - 1]) + 1;
            }
        }
    }
    return dp[n][m];
}
```

As shown in the following picture, the state transition process of the edit distance problem is very similar to the bag problem, and can be regarded as a process of filling in a two-dimensional grid.

![<1>](./algos/14.6.2-1.png) ![<2>](./algos/14.6.2-2.png) ![<3>](./algos/14.6.2-3.png) ![<4>](./algos/14.6.2-4.png) ![<5>](./algos/14.6.2-5.png) ![<6>](./algos/14.6.2-6.png) ![<7>](./algos/14.6.2-7.png) ![<8>](./algos/14.6.2-8.png) ![<9>](./algos/14.6.2-9.png) ![<10>](./algos/14.6.2-10.png) ![<11>](./algos/14.6.2-11.png) ![<12>](./algos/14.6.2-12.png) ![<13>](./algos/14.6.2-13.png) ![<14>](./algos/14.6.2-14.png) ![<15>](./algos/14.6.2-15.png)

3. space optimization

Since $dp[i,j]$ is transitoned to from the upper $dp[i-1,j]$, the left $dp[i,j-1]$, and the upper left state $dp[i-1,j-1]$, and the positive traversal will lose the upper left $dp[i-1,j-1]$, and the reverse order traversal cannot construct $dp[i,j-1]$ in advance, neither traversal orders are not desirable.

To this end, we can use a variable `leftup` to temporarily store the upper left solution $dp[i-1,j-1]$, so that only the left and upper solutions are considered. The situation at this time is the same as the full bag problem, and positive order traversal can be used.

```zig
// edit distance: dynamic programming after spatial optimization
fn editDistanceDPComp(comptime s: []const u8, comptime t: []const u8) i32 {
    comptime var n = s.len;
    comptime var m = t.len;
    var dp = [_]i32{0} ** (m + 1);
    // state transition: first row
    for (1..m + 1) |j| {
        dp[j] = @intCast(j);
    }
    // state transition: remaining rows
    for (1..n + 1) |i| {
        // state transition: first column
        var leftup = dp[0]; // 暂存 dp[i-1, j-1]
        dp[0] = @intCast(i);
        // state transition: remaining columns
        for (1..m + 1) |j| {
            var temp = dp[j];
            if (s[i - 1] == t[j - 1]) {
                // if the two characters are equal, skip the two characters directly
                dp[j] = leftup;
            } else {
                // minimum number of editing steps:
                // minimum number of editing steps for the three operations
                // of inserting, deleting, and replacing + 1
                dp[j] = @min(@min(dp[j - 1], dp[j]), leftup) + 1;
            }
            leftup = temp; // 更新为下一轮的 dp[i-1, j-1]
        }
    }
    return dp[m];
}
```

14.7 Summary

- Dynamic programming decomposes the problem and avoids repeated calculations by storing solutions to sub-problems, achieving high computational efficiency.
- Without considering time, all dynamic programming problems can be solved by backtracking (brute force search), but there is a large number of overlapping sub-problems in the recursive tree, which is extremely inefficient. By introducing a memoized list, the solutions of all computed subproblems can be stored, thereby ensuring that overlapping subproblems are computed only once.
- Memoized recursion is a top-down recursive solution, and the corresponding dynamic programming is a bottom-up recursive solution, which is like "filling in a table". Since the current state only depends on some local state, we can eliminate one dimension of the $dp$ table, thus reducing the space complexity.
- Subproblem decomposition is a general algorithmic idea, which has different properties in divide and conquer, dynamic programming, and backtracking.
- Three properties of dynamic programming problems: overlapping subproblems, optimal substructure, and no aftereffect.
- A problem has an optimal substructure if the optimal solution to the original problem can be constructed from the optimal solutions to the subproblems.
- No aftereffect means that for a state, its future development is only related to this state, and has nothing to do with all the past states it has experienced. Many combinatorial optimization problems are not aftereffect-free and cannot be solved quickly using dynamic programming.

**bag problem**

- The bag problem is the most typical dynamic programming problem, with variants such as 0-1 bag, full bag, and multiple bags.
- The state of a 0-1 bag is defined as the maximum value of the first $i$ items in a bag with remaining capacity $c$. According to the two decisions of not putting in the bag and putting in the bag, the optimal substructure can be obtained, and the state transition equation can be constructed. In spatial optimization, since each state depends on the state directly above and upper left, it is necessary to traverse the list in reverse order to avoid the upper left state from being overwritten.
- There is no limit to how much of each item can be picked in the full bag, so the state transition for selecting items to put in is different from the 0-1 bag. Since the state depends on the state directly above and directly to the left, it should be traversed in positive order in spatial optimization.
- The coin change problem is a variant of the full bag. It changed from seeking the "maximum" value to seeking the "minimum" number of coins, so $max()$ in the state transition equation should be changed to $min()$. From seeking "no more than" the bag capacity to seeking "exactly" the target amount, so use amt+1 to represent the invalid solution of "unable to make up the target amount".
- The coin change II problem is changed from "minimum number of coins" to "number of coin combinations", and the state transition equation is changed from $min()$ to summation operator accordingly.

**edit distance problem**

- Editing distance (Levenshtein distance) is used to measure the similarity between two strings, which is defined as the minimum number of editing steps from one string to another, and editing operations include addition, deletion, and replacement.
- The state of the edit distance problem is defined as the minimum number of edit steps required to change the first $i$ characters of $s$ to the first $j$ characters of $t$. When $s[i] \ne t[j]$, there are three kinds of decisions: add, delete, replace, and they all have corresponding remaining subproblems. Based on this, the optimal substructure can be found and the state transition equation can be constructed. And when $s[i]=t[j]$, there is no need to edit the current character.
- In the edit distance, the state depends on the state directly above, directly to the left, and the upper left, so neither the forward nor reverse order traversal after state compression can perform state transfer correctly. To this end, we use a variable to temporarily store the upper left state, so as to convert it to a situation equivalent to a full bag, which can be traversed in positive order after space optimization.

15. greedy

>**Abstract**
>The sunflower turns towards the sun, always pursuing the greatest possibility of its own growth.
>
>The greedy strategy gradually leads to the best answer in rounds of simple choices.

15.1. Greedy Algorithm

The greedy algorithm is a common algorithm for solving optimization problems. Its basic idea is to choose the best option at each decision-making stage of the problem, that is, to make a locally optimal decision greedily, in order to expect to obtain a global optimal solution. The greedy algorithm is simple and efficient, and has a wide range of applications in many practical problems.

Greedy algorithms and dynamic programming are both commonly used to solve optimization problems. They have some similarities, such as relying on optimal substructure properties, but their working principles are different.

- Dynamic programming considers the current decision based on all the decisions from previous stages and uses the solutions of the past subproblems to construct the solution of the current subproblem.
- The greedy algorithm does not reconsider past decisions, but makes greedy choices all the way forward, continuously narrowing the scope of the problem until the problem is solved.

Let's first understand the working principle of the greedy algorithm through the example "coin change". This problem has been introduced in the dynamic programming chapter, I believe you are no stranger to it.

>**Question**
>Given $n$ kinds of coins, the face value of the $ith$ coin is $coins[i-1]$, and the target amount is $amt$. Each coin can be selected repeatedly, and the minimum number of coins that can make up the target amount is asked. Returns $-1$ if the target amount cannot be made.

The greedy strategy of this question is shown in the following picture. Given the target amount, we greedily choose the coin that is not larger and closest to it, and repeat this step until the target amount is reached.

![Fig. 零钱兑换的贪心策略](./algos/15.1.0.png)

The implementation code is shown below. You may not help but sigh: So Clean! The greedy algorithm solves the coin change problem with only ten lines of code.

15.1.1. Advantages and limitations of greed

**Greedy algorithms are not only straightforward to operate and easy to implement, they are also usually very efficient**. In the previous code, the minimum face value of a coin is $min(coins)$, then the greedy selection cycle is at most $amt/min(coins)$ times, and the time complexity is $O(\frac{amt}{min(coins)})$. This is an order of magnitude higher than the time complexity $O(n \times amt)$ of the dynamic programming solution.

However, **for some combinations of coin values, the greedy algorithm cannot find the optimal solution**. The following picture shows two examples.

- **Positive example** $coins=[1,5,19,20,50,100]$: Under this combination of coins, given any $amt$, the greedy algorithm can find the optimal solution.
- **Counter example** $coins=[1,20,50]$: Assuming $amt=60$, the greedy algorithm can only find the exchange combination of $50+1x10$, a total of $11$ coins, but dynamic programming can find the optimal solution $20+20+20$, which only need $3$ coins.
- **Counter example** $coins=[1,49,50]$: Assuming $amt=98$, the greedy algorithm can only find the exchange combination of $50+1x48$, a total of $49$ coins, but dynamic programming can find the optimal solution $49+49$, only needing $2$ coins.

![Fig. 贪心无法找出最优解的示例](./algos/15.1.1.png)

In other words, for the coin change problem, the greedy algorithm cannot guarantee to find the global optimal solution, and may find a very poor solution. It is better suited to be solved with dynamic programming.

In general, the greedy algorithm is suitable for the following two types of problems.

1. **Finding the optimal solution is guaranteed**: the greedy algorithm is often the best choice in this case, because it is often more efficient than backtracking and dynamic programming.
2. **A near-optimal solution can be found**: greedy algorithms are also available in this case. For many complex problems, it is very difficult to find the global optimal solution, and it is also very good to be able to find suboptimal solutions with high efficiency.

15.1.2. Greedy Algorithm Features

So the question is, what kind of problem is suitable to be solved by greedy algorithm? In other words, under what circumstances can the greedy algorithm be guaranteed to find the optimal solution?

Compared with dynamic programming, the conditions for using the greedy algorithm are more stringent, and it mainly focuses on two properties of the problem:

- **Greedy choice property**: A greedy algorithm can guarantee an optimal solution only if a locally optimal choice can always lead to a globally optimal solution.
- **Optimal substructure**: The optimal solution to the original problem contains the optimal solutions to the subproblems.

The optimal substructure has already been introduced in the chapter of dynamic programming, and will not be repeated here. It is worth noting that some problems whose optimal substructure is not obvious can still be solved using a greedy algorithm.

We mainly explore the method of estimating the nature of greedy choice. Although its description seems relatively simple, **in fact, for many problems, it is not an easy task to prove the greedy choice property**.

For example, in the coin change problem, although we can easily give a counterexample to falsify the nature of greedy choice, it is more difficult to prove it. If you ask: **What coin combinations can be solved using the greedy algorithm**? We often can only give an ambiguous answer with intuition or examples, but it is difficult to give a rigorous mathematical proof.

>**Quote**
>There is a paper devoted to this issue. The author gives an algorithm with $O(n^3)$ time complexity, which is used to estimate whether a coin combination can use the greedy algorithm to find the optimal solution of any amount.
>
>Pearson, David. A polynomial-time algorithm for the change-making problem. Operations Research Letters 33.3 (2005): 231-234.

15.1.3. Greedy Problem Solving Steps

The greedy problem solving process can be roughly divided into the following three steps.

1. **Problem analysis**: sort out and understand the characteristics of the problem, including state definition, optimization goals and constraints, etc. This step is involved in both backtracking and dynamic programming.
2. **Determine the greedy strategy**: Determine how to make the greedy choice at each step. This strategy reduces the size of the problem at each step and eventually solves the entire problem.
3. **Proof of correctness**: It is usually necessary to prove that the problem has a greedy choice property and an optimal substructure. This step may require the use of mathematical proofs, such as induction or proof by contradiction.

Determining a greedy strategy is a central step in solving a problem, but it can be difficult to implement mainly for the following reasons.

- **Greedy strategies vary widely across problems**. For many problems, the greedy strategy is relatively simple, and we can get it through some general thinking and trying. For some complex problems, the greedy strategy may be very hidden. In this case, it is a test of personal problem-solving experience and algorithm ability.
- **Certain greedy strategies are highly deceptive**. When we design a greedy strategy with confidence, write the problem-solving code and submit it for operation, we may find that some test samples fail to pass. This is because the designed greedy strategy is only "partially correct". The coin change described above is a typical case.

In order to ensure correctness, we should carry out a rigorous mathematical proof of the greedy strategy, **which usually requires the use of proof by contradiction or mathematical induction**.

However, proof of correctness is also likely to be non-trivial. If we don’t have a clue, we usually choose to debug the test cases, modify and verify the greedy strategy step by step.

15.1.4. Greedy typical examples

Greedy algorithms are often used in optimization problems that satisfy greedy selection properties and optimal substructures. The following are some typical greedy algorithm problems.

- **Coin change problem**: Under certain coin combinations, the greedy algorithm can always get the optimal solution.
- **Interval Scheduling Problem**: Suppose you have some tasks, each of which is performed over a period of time, and your goal is to complete as many tasks as possible. If the task with the earliest end time is selected every time, then the greedy algorithm can get the optimal solution.
- **Fractional Bag Problem**: Given a set of items and a carrying capacity, your goal is to choose a set of items such that the total weight does not exceed the carrying capacity and the total value is maximized. If the most cost-effective (value/weight) item is chosen every time, then the greedy algorithm can get the optimal solution in some cases.
- **Stock buying and selling problem**: Given the historical prices of a set of stocks, you can buy and sell multiple times, but if you already hold the stock, you can't buy it again until you sell it, the goal is to get the maximum profit.
- **Huffman encoding**: Huffman encoding is a greedy algorithm for lossless data compression. By constructing the Huffman tree, the two nodes with the smallest frequency of occurrence are selected and merged each time, and the weighted path length (ie, the code length) of the finally obtained Huffman tree is the smallest.
- **Dijkstra's Algorithm**: It is a greedy algorithm that solves the problem of the shortest path from a given source vertex to the rest of the vertices.

15.2. fractional bag problem

>**Question**
>Given $n$ items, the $ith$ item has weight $wgt[i-1]$, value $val[i-1]$, and a bag with capacity $cap$. Each item can only be selected once, but a part of the item can be selected. The value is calculated according to the selected weight ratio. What is the maximum value of the items in the bag without exceeding the bag capacity?

![Fig. 分数背包问题的示例数据](./algos/15.2.0.1.png)

The fractional bag is very similar to 0-1 bag as a whole. The state includes the current item $i$ and capacity $c$. The goal is to find the maximum value that does not exceed the bag capacity.

The difference is that this problem allows only a part of the item to be selected, as shown in  the following picture **the item can be divided arbitrarily, and the value of the item is calculated according to the weight ratio**.

1. For item $i$, its value per unit weight is $\frac{val[i-1]}{wgt[i-1]}$, referred to as unit value.
2. Assuming that a part of the item $i$ is put in and the weight is $w$, the added value of the bag is $w \times \frac{val[i-1]}{wgt[i-1]}$.

![Fig. 物品在单位重量下的价值](./algos/15.2.0.2.png)

1. Greedy policy determination

Maximizing the total value of the items in the bag **essentially means maximizing the value of the items per unit weight**. From this, we can derive the greedy strategy shown in the following picture.

1. Sort the items by unit value from highest to lowest.
2. Go through all items, and **greedily select the item with the highest unit value each round**.
3. If the remaining bag capacity is insufficient, just use part of the current item to fill the bag.

![Fig. 分数背包的贪心策略](./algos/15.2.1.png)

2. code

We created an item class `Item` to sort items by unit value. The loop makes a greedy selection and exits when the backpack is full and returns to the solution.

```zig
[class]{Item}-[func]{}

[class]{}-[func]{fractionalKnapsack}
```

In the worst case, the entire list of items needs to be traversed, **so the time complexity is $O(n)$**, where $n$ is the number of items.

Since a list of `Item` objects is initialized, **the space complexity is $O(n)$**.

3. proof of correctness

Adopt counter-evidence. Assuming that item $x$ is the item with the highest unit value, use an algorithm to obtain the maximum value `res`, where the solution does not include item $x$.

Now take a weigth of any item from the bag and replace it with a weight of item x. Since item x has the highest unit value, the total value after replacement must be greater than `res`. **This contradicts that `res` is the optimal solution, indicating that item $x$ must be included in the optimal solution**.

For other items in the solution, we can also construct the above contradiction. All in all, **items with greater unit value are always a better choice**, which shows that the greedy strategy is effective.

As shown in the following picture, if the item weight and item unit value are regarded as the horizontal axis and vertical axis of a 2D chart respectively, the fractional bag problem can be transformed into "finding the maximum enclosed area under a limited horizontal axis interval". Through this analogy, we can understand the effectiveness of greedy strategies from a geometric perspective.

![Fig. 分数背包问题的几何表示](./algos/15.2.3.png)

15.3. maximum capacity problem

>**Question**
>Input an array $ht$, each element in the array represents the height of a vertical partition. Any two partitions in the array, and the space between them, can form a container.
>
>The container's capacity is equal to the product (i.e., area) of the height and width, where the height is determined by the shorter divider and the width is the difference between the array indices of the two dividers.
>
>Please select two partitions in the array to make the combined container have the largest capacity, and return the maximum capacity.

![Fig. 最大容量问题的示例数据](./algos/15.3.0.png)

The container is surrounded by any two partitions, so **the state of this problem is the index of the two partitions, denoted as $[i,j]$**.

According to the problem, the capacity is equal to the height multiplied by the width, where the height is determined by the short board, and the width is the difference between the indexes of the two partitions. Let the capacity be $cap[i,j]$, then the calculation formula can be obtained:
$$cap[i,j]=min(ht[i],ht[j])\times(j-i)$$
Assuming that the length of the array is $n$, and the number of combinations of two partitions (that is, the total number of states) is $\binom{n}{2}=\frac{n(n-1)}{2}$. Most directly, **we can exhaustively enumerate all states** to obtain the maximum capacity, and the time complexity is $O(n^2)$.

1. Greedy policy determination

There is a more efficient solution to this problem. As shown in the following picture, select a state $[i,j]$ which satisfies the index $i<j$ and the height $ht[i]<ht[j]$, that is, $i$ is a short board and $j$ is a long board.

![Fig. 初始状态](./algos/15.3.1.1.png)

As shown in the following picture, **if the long board $j$ is approached to the short board $i$ at this time, the capacity will definitely decrease**.

This is because after moving the long board $j$, the width $j-i$ will definitely become smaller; while the height is determined by the short board, so the height can only remain the same ($i$ is still a short board) or become smaller ($j$ after moving becomes a short board) .

![Fig. 向内移动长板后的状态](./algos/15.3.1.2.png)

Thinking in reverse, we can increase the capacity only if we shrink the shorter board $i$ inward. Because although the width will definitely become smaller, the height may become larger (the short board $i$ after moving may become longer). For example in the following picture the area becomes larger after moving the short board.

![Fig. 向内移动长板后的状态](./algos/15.3.1.3.png)

From this, the greedy strategy of this problem can be deduced: initialize the two pointers to split the two ends of the container, and shrink the pointer corresponding to the short board inward each round until the two pointers meet.

The following picture shows the execution process of the greedy strategy.

1. In the initial state, the pointers $i$ and $j$ are located at both ends of the array.
2. Calculate the capacity $cap[i,j]$ of the current state, and update the maximum capacity.
3. Compare the heights of board $i$ and board $j$, and move the short board one space inward.
4. Loop through steps `2.` and `3.` until $i$ and $j$ meet.

![<1>](./algos/15.3.1.4-1.png) ![<2>](./algos/15.3.1.4-2.png) ![<3>](./algos/15.3.1.4-3.png) ![<4>](./algos/15.3.1.4-4.png) ![<5>](./algos/15.3.1.4-5.png) ![<6>](./algos/15.3.1.4-6.png) ![<7>](./algos/15.3.1.4-7.png) ![<8>](./algos/15.3.1.4-8.png) ![<9>](./algos/15.3.1.4-9.png)

2. Code

The code loops at most $n$ rounds, **so the time complexity is $O(n)$**.

The variables $i$, $j$ and $res$ use constant size extra space, **so the space complexity is $O(1)$**.

```zig
[class]{}-[func]{maxCapacity}
```

3. proof of correctness

The reason why greedy is faster than exhaustive is because each round of greedy selection will "skip" some states.

For example, in the state $cap[i,j]$, $i$ is the short board and $j$ is the long board. If the short board $i$ is moved one space inward greedily, the state shown in the following picture will be "skipped". **This means that the capacity sizes of these states cannot be verified afterwards**.
$$cap[i,i+1],cap[i,i+2],...,cap[i,j-2],cap[i,j-1]$$

![Fig. 移动短板导致被跳过的状态](./algos/15.3.3.0.png)

It is observed that **these skipped states are actually all the states that move long board $j$ inwards**. In the second step, we have proved that moving the long board inward will definitely lead to a smaller capacity. That is to say, none of the skipped states can be the optimal solution, and **skipping them will not lead to missing the optimal solution**.

The above analysis shows that **the operation of moving the short board is "safe"**, and the greedy strategy is effective.

15.4. maximum split product problem

>**Question**
>Given a positive integer n, divide it into the sum of at least two positive integers, find the maximum product of all integers after division.

![Fig. 最大切分乘积的问题定义](./algos/15.4.0.png)

Suppose we divide $n$ into $m$ integer factors, and the $ith$ factor is recorded as $n_i$, that is
$$n=\sum_{i=1}^{m}n_i$$
The goal of this problem is to find the maximum product of all integer factors, that is
$$max(\prod_{i=1}^{m}n_i)$$
What we need to think about is: how big should be the number of splits $m$, and how much should each $n_i$ be?

1. Greedy policy determination

As a rule of thumb, the product of two integers is often greater than their sum. Suppose a factor $2$ is divided from $n$, then their product is $2(n-2)$. We compare this product with $n$:
$$\begin{align*}
2(n-2) &\ge n\\
2n-n-4 &\ge 0\\
n &\ge 4
\end{align*}$$
As shown in the following picture, when $n \ge 4$, the product will become larger after a $2$ is cut out, **which means that integers greater than or equal to $4$ should be cut**.

**Greedy strategy 1**: If the segmentation scheme contains a factor $\ge 4$, then it should continue to be divided. The final segmentation scheme should only have three factors $1$, $2$ and $3$.

![Fig. 切分导致乘积变大](./algos/15.4.1.1.png)

Next think about which factor is optimal. Among the three factors $1$, $2$ and $3$, $1$ is obviously the worst, because $1\times(n-1)<n$ is always true, that is, cutting out $1$ will lead to a reduction in the product.

As shown in the following picture when $n=6$, then $3\times3>2\times2\times2$. **This means that splitting out $3$ is better than splitting out $2$**.

**Greedy strategy 2**: In the segmentation scheme, there should be at most two $2s$$. Because three $2s$ can always be replaced by two $3s$, resulting in a larger product.

![Fig. 最优切分因子](./algos/15.4.1.2.png)

To sum up the above, the follwoing greedy strategy can be derived.

1. Input an integer $n$, from which the factor $3$ is continuously divided until the remainder is $0$, $1$ or $2$.
2. When the remainder is $0$, it means that $n$ is a multiple of $3$, so no processing is performed.
3. When the remainder is $2$, do not continue to divide and keep it.
4. When the remainder is $1$, since $2\times2>1\times3$, the last $3$ should be replaced with $2$.

2. Code

As shown in the following picture,  we do not need to use loops to divide the integers. Instead we can use the downward integer division operation to get the number $a$ of $3$, and use the modulo operation to get the remainder $b$. At this time we have:
$$n=3a+b$$

Note that for the edge case $n \le 3$, a $1$ must be split out, and the product is $1\times(n-1)$.

```zig
[class]{}-[func]{maxProductCutting}
```

![Fig. 最大切分乘积的计算方法](./algos/15.4.2.png)

**The time complexity depends on how the programming language's exponentiation is implemented**. Taking Python as an example, there are three commonly used power calculation functions:

- The time complexity of operator `**` and function `pow()` is $O(log\,a)$.
- The function `math.pow()` internally calls the `pow()` function of the C language library, which performs floating-point exponentiation, and the time complexity is $O(1)$.

The variables $a$ and $b$ use a constant amount of extra space, **so the space complexity is $O(1)$**.

3. proof of correctness

Using the method of proof by contradiction, only analyzing the case where $n \ge 3$.

1. **All factors $ \le 3$**: Assuming that there is a factor $x \ge 4$ in the optimal segmentation scheme, then it can be further divided into $2(x-2)$ to obtain a larger product. This contradicts the assumption.
2. **The segmentation scheme does not contain $1$**: Assuming that there is a factor $1$ in the optimal segmentation scheme, then it must be merged into another factor to obtain a larger product. This contradicts the assumption.
3. **The segmentation scheme contains at most two $2s$**: Assuming that the optimal segmentation scheme contains three $2s$, then it must be replaced by two 3s, and the product will be larger. This contradicts the assumption.

15.5. summary

- Greedy algorithms are usually used to solve optimization problems. The principle is to make locally optimal decisions at each decision-making stage in order to obtain a global optimal solution.
- The greedy algorithm will iteratively make one greedy choice after another, transforming the problem into a smaller sub-problem each round until the problem is solved.
- The greedy algorithm is not only simple to implement, but also has high problem-solving efficiency. Greedy algorithms usually have lower time complexity than dynamic programming.
- In the coin exchange problem, for some combinations of coins, the greedy algorithm is guaranteed to find an optimal solution; for other combinations of coins, it may not, and the greedy algorithm may find a poor solution.
- Problems suitable to be solved by greedy algorithms have two properties: greedy selection property and optimal substructure. The greedy choice property represents the effectiveness of the greedy strategy.
- For some complex problems, the proof of the greedy choice property is not straightforward. Relatively speaking, falsification is easier, such as the coin change problem.
- Solving the greedy problem is mainly divided into three steps: problem analysis, greedy strategy determination, and correctness proof. Among them, the determination of the greedy strategy is the core step, and the correctness proof is often difficult.
- The Fractional Bag Problem is based on the 0-1 bag, allowing the selection of a part of an item, so it can be solved using a greedy algorithm. The correctness of the greedy strategy can be proved by contradiction.
- The maximum capacity problem can be solved using an exhaustive method with a time complexity of $O(n^2)$. By designing a greedy strategy and moving the short board inward each round, the time complexity can be optimized to $O(n)$.
- In the maximum segmentation product problem, we deduced two greedy strategies successively: integers $\ge 4$ should continue to be divided, and the optimal division factor is $3$. The code contains exponentiation, and the time complexity depends on how the exponentiation is implemented, usually $O(1)$ or $O(log\,n)$.

16. appendix

16.1. Programming environment installation

16.1.1. VSCode

This book recommends using the open source and lightweight VSCode as the local IDE, download and install [VSCode](https://code.visualstudio.com/).

16.1.2. Java environment

1. Download and install [OpenJDK](https://jdk.java.net/18/) (version must meet > JDK 9).
2. Search for `java` in VSCode's plug-in market, and install Extension Pack for Java.

16.1.3. C/C++ environment

1. Windows system needs to install [MinGW](https://sourceforge.net/projects/mingw-w64/files/) ([configuration tutorial](https://blog.csdn.net/qq_33698226/article/details/129031241)), and MacOS comes with Clang without installation.
2. Search for `c++` in VSCode's plug-in market and install C/C++ Extension Pack.
3. (Optional) Open the Settings page, search for the `Clang_format_fallback Style` code formatting option, and set it to `{ BasedOnStyle: Microsoft, BreakBeforeBraces: Attach }`.

16.1.4. Python environment

1. Download and install [Miniconda3](https://docs.conda.io/en/latest/miniconda.html).
2. Search for `python` in VSCode's plug-in market and install Python Extension Pack.
3. (Optional) Enter `pip install black` on the command line to install the code formatting tool.

16.1.5. Go environment

1. Download and install [go](https://go.dev/dl/).
2. Search for `go` in VSCode's plug-in market and install Go.
3. Press the shortcut key `Ctrl + Shift + P` to call out the command bar, enter go , select `Go: Install/Update Tools`, check all of them and install them.

16.1.6. JavaScript environment

1. Download and install [node.js](https://nodejs.org/en/).
2. Search for `javascript` in VSCode's plug-in market, and install JavaScript (ES6) code snippets.
3. (Optional) Search for `Prettier` in VSCode's plug-in market to install the code formatting tool.

16.1.7. C# environment

1. Download and install [.Net 6.0](https://dotnet.microsoft.com/en-us/download).
2. Search for `C# Dev Kit` in the VSCode plug-in market and install C# Dev Kit ([configuration tutorial](https://code.visualstudio.com/docs/csharp/get-started))
3. Visual Studio ([installation tutorial](https://learn.microsoft.com/zh-cn/visualstudio/install/install-visual-studio?view=vs-2022)) can also be used.

16.1.8. Swift environment

1. Download and install [Swift](https://www.swift.org/download/).
2. Search for `swift` in VSCode's plug-in market, and install [Swift for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=sswg.swift-lang).

16.1.9. Dart

1. Download and install [Dart](https://dart.dev/get-dart).
2. Search for `dart` in the VSCode plug-in market and install [Dart](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code).

16.1.10. Rust environment

1. Download and install [Rust](https://www.rust-lang.org/tools/install).
2. Search for `rust` in VSCode's plug-in market and install [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer).

16.2. Participate in the creation together

Due to the limited ability of the author, there are inevitably some omissions and mistakes in the book, please understand. If you find problems such as typos, broken links, missing content, ambiguous text, unclear explanations, or unreasonable writing structure, please help us make corrections to help other readers obtain better learning resources.

The GitHub IDs of all [contributors](https://github.com/krahets/hello-algo/graphs/contributors) will be displayed on the home page of the repository, web version and PDF version to thank them for their selfless contributions to the open source community.

>**The charm of open source**
>The interval between printings of paper books often takes several years, and content updating is very inconvenient.
>
>However, in this open source book, the time for content changes is shortened to days or even hours.

16.2.1. content fine-tuning

As shown in the following picture, there is an "Edit" icon in the upper right corner of each page, you can modify the text or code by following the steps below.

1. Click the edit icon, if you encounter the prompt "Need to fork this repository", please agree to the operation.
2. Modify the content of the Markdown source file, check the correctness of the content, and try to keep the formatting consistent.
3. Fill out the modification instructions at the bottom of the page and click the "Propose file change" button. After the page redirects, click the "Create pull request" button to initiate a pull request.

![Fig. 页面编辑按键](./algos/16.2.1.png)

The picture cannot be modified directly, you need to create a new [Issue](https://github.com/krahets/hello-algo/issues) or comment to describe the problem, we will redraw and replace the picture as soon as possible.

16.2.2. content creation

If you are interested in participating in this open source project, including translating code into other programming languages, expanding article content, etc., you need to implement the following Pull Request workflow:

1. Log in to GitHub and Fork [this repository](https://github.com/krahets/hello-algo) to your personal account.
2. Go to your Fork repository webpage and use the `git clone` command to clone the repository locally.
3. Create content locally and conduct a complete test to verify the correctness of the code.
4. Commit the changes made locally, and then push to the remote repository.
5. Refresh the repository webpage, click the "Create pull request" button to initiate a pull request.

16.2.3. Docker deployment

Execute the following Docker script, and after a while, you can access this project on the webpage <http://localhost:8000>.

```none
git clone <https://github.com/krahets/hello-algo.git>
cd hello-algo
docker-compose up -d
```

Use the following command to delete a deployment.

```done
docker-compose down
```

references

[1] Thomas H. Cormen, et al. Introduction to Algorithms (3rd Edition).

[2] Aditya Bhargava. Grokking Algorithms: An Illustrated Guide for Programmers and Other Curious People (1st Edition).

[3] Yan Weimin. Data structure (C language version).

[4] Deng Junhui. Data Structure (C++ Language Edition, Third Edition).

[5] Mark Allen Weiss, translated by Chen Yue. Data Structure and Algorithm Analysis: Java Language Description (Third Edition).

[6] Cheng Jie. Big Talk Data Structure.

[7] Wang Zheng. The beauty of data structure and algorithm.

[8] Gayle Laakmann McDowell. Cracking the Coding Interview: 189 Programming Questions and Solutions (6th Edition).

[9] Aston Zhang, et al. Dive into Deep Learning.
