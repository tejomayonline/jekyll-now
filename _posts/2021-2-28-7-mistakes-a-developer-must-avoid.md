---
layout: post
title: 7 Mistakes That A Developer Must Avoid
---

![](https://cdn-images-1.medium.com/max/3200/0*m-g7Got0iZ2zsRu9)

To err is human, but sometimes the smallest error can turn out to be the costliest ones. Similarly, in our development process, some *mistakes can be catastrophic but* these can be avoided with *observations* and some *cool tricks*. And as a wise man had said,
> # *“We should not feel bad about the mistakes if we are learning from them.”*

So, here we are going to talk about some of the mistakes a developer tends to do with the tips to avoid them.

### **Lack of Planning:**

**Naturally, **you are eager to write codes and so some of you start writing it in your IDE/Editor without any plans. However, it is the wrong way of starting with code.

![](https://cdn-images-1.medium.com/max/3200/0*cGiCIxQxaaFimND9)

You need to think and plan how you are going to write the code before you start. Following a systematic approach as this would help:

* Understand the *problem* statement

* Find out all possible solutions and pick the *best* one

* Identify the correct **data-structure**

* Design the object model (**LLD**)

* Pick or create a **framework** (code behaviours, directory structure etc.)

Then you can proceed with writing the code and modify it as required. Programming *does not mean* only ***writing*** *lines of code*, it’s a combination of step-by-step processes of different actions.

### **No Test Cases:**

![](https://cdn-images-1.medium.com/max/3200/0*8Vl2c6g6ndKvYQ-4)

Even though you are **confident** about the code, proceeding without test cases is a recipe of disaster as it is prone to be error-laden.

If you test the code manually, there is nothing wrong with it. But, it is better if the *manual* test should be replicated as *automated tests*. Next time after adding new codes these test cases would run to check all the validations needed.

There is a huge possibility that you’ll *forget *to test the code with all the *previously successful validation* after each code change. Test cases can do that.

If possible it’s better to design your validation before writing code. **Test-Driven Development (TDD) **is a better way of how you think and design your feature.TDD is not for all projects, but if we can use it, it will be beneficial.

### **Code Quality:**
> # *“Always code as if the guy who ends up maintaining your code will be a violent psychopath who knows where you live.”*— *John Woods*

![](https://cdn-images-1.medium.com/max/2080/0*t1uUWa9JtVZeKjGI)

The **quality** of the code is essential, and the* readability* is absolutely uncompromisable. Coding is a way to *communicate the implementation*. Here are a few mistakes to be taken care of:

1. Using multiple lines in a method. You should always break methods into smaller ones.
> *A method should not have more than 10 lines.*

1. Using *short, generic, or type-based* variable names. Give your variables descriptive and non-ambiguous names.

1. Using *shortcuts, a workaround* to avoid spending more time on some problem is **not **a *good habit*.

1. Not sticking with *indentation, capitalization *must be avoided. Usage of ***Linting and formating tools*** can minimize a lot of issues.

The *excessive* use of* conditional logic* is not good. Find out the best simple alternatives approach.

### **Sensitive Data Leak:**

![](https://cdn-images-1.medium.com/max/2560/0*TManJPBMCAzrFQX_)

As a developer, it’s your responsibility to ensure there is no sensitive data shared during the development process.

There’s a known problem in server configuration and deploying when you have to store your private data such as **database passwords, application secret-keys**, **environment configurations** and so on inside the git repository. Even if this repository is* **private***, it is a security risk to just publish them on the *world wide web*.

There are certain **tools** that can be used like git users can use [**git-secrets](https://github.com/awslabs/git-secrets)** to ***prevent*** committing any *sensitive information to a repository*. Also, tools like [**repo-supervisor](https://github.com/auth0/repo-supervisor), [truffleHog](https://github.com/dxa4481/truffleHog)** are very helpful in scanning the repositories to find out if there is sensitive information-pushed accidentally.

### **Unnecessary Comments:**

Some of you used to add comments before **obvious** code blocks. We should **avoid** comments as much as possible with *naming elements* **properly**.

<iframe src="https://medium.com/media/2ff2cc65ae7a6c19245b1bc3cf103217" frameborder=0></iframe>

With *better naming conventions* on *methods, variables, and other entities* the written comments look unnecessary, don’t they? Though there are situations where only clarity can be provided by the comments but obvious comments to be avoided.

### **Attitude:**
> *Attitude is a little thing that makes a big difference. *— *Churchill Quotes*

![](https://cdn-images-1.medium.com/max/3200/0*zX7_2dXce4P1ot8E)

As the quotes said, your attitude decides your skill, quality of work. This is a huge topic in itself, but let’s discuss some of them here.

1. **Not testing code after deployment:** If the code is working fine in the *local *environment, it does not ensure that it will work the same way after code deployment. Some of you *forget* to test on deployment environments *assuming* it will work.

This habit can cause unwanted code breaks and must be avoided at any cost. In a development phase, these bugs can be found after a couple of days/weeks and will be a time-killer to fix them.

* **Not accepting the criticism: **For a person open to constructive criticism, the sky’s the limit. And that’s exactly how a developer should be. It is the only way to achieve perfection in your work.

You are human and you are not perfect. Sometimes some of you take a comment from a *code reviewer* into your **ego**. Rather than *criticising* reviewer feedback, you should try to learn from his/her words to *improve* yourself.

Also, that does not mean you should blindly follow whatever is said. Communication is the key here. If you feel like something can work in another way you should pitch it and contribute as a team.

* **Not focusing on knowledge enhancement:**
> # *Anyone who stops learning is old, whether at twenty or eighty. Anyone who keeps learning stays young. *— *Henry Ford*

Learning is the key to success. It improves your knowledge and as a *coder*, you should implement the knowledge **practically**. You should develop the evergreen learning attitude within you. This is a *special skill* that will not only help in your professional career but also with personal growth.

* **Picking the First Solution: **There are a couple of ways to solve a problem. The first solution might not be the best one. You should find out all possible ways to solve a problem and then analyze to pick the best suitable solution.

But if you are* not able to think* or approach differently on a problem statement, then the problem is not clear to you. Then you should ask more questions for clarity.

* **Emotional Attachment with Code: **As a programmer, you used to *attach* with your code, you try to continue to improve it. It becomes a *never-ending* process. Nothing is perfect, not will be. There will be always a scope for improvement. You should *limit the scope* as per the requirement and *move on* to the *next one*.

* **Not Asking for Help**: You sometimes think that you can fix an issue yourself and you are struggling with something. There is a way to handle this issue by using “**30 mins Rule***”*. So, next time you are stuck with a problem, you try yourself for *30 mins* and after that seek help to fix it.

* **Not picking the right tool for the Job: **For any feature development sometimes you use *tools /libraries *that are based on your *personal preference* rather than the solution required. Tools should be chosen as per the *feature requirement basis*.

### **Not taking breaks:**

![](https://cdn-images-1.medium.com/max/3200/0*9j1ESZAC3QLEHTo8)

Taking breaks is a must for your programming schedule. If you work *continuously *without any break and think after *finishing the* work you’ll take *rest *then your energy will be drained. It is not healthy for you too. Also if you take a break of **5 mins** in every **30–40 mins** mind will be more* balanced* and the *efficiency* will also *improve*.

Some of the interesting blogs I found worth reading on this topic:

* [9-key-mistakes-every-young-developer-should-avoid](https://codeburst.io/9-key-mistakes-every-young-developer-should-avoid-832e3c08da1e)

* [Beginner-programmers-mistakes](https://jscomplete.com/learn/pro-programmer/beginner-programmers-mistakes)

* [Newbie-programmers-mistakes](https://levelup.gitconnected.com/newbie-programmers-mistakes-and-how-to-avoid-them-f39a94bf753b)

**Conclusion:**

In this article, I shared some of the common mistakes developers make. With the right planning and correct attitude, mistakes can be minimized. Hope, the tips shared to ditch these mistakes will be worthwhile. Try to fail as early as possible to rectify quickly and get over it.
> Fail early, Fail Often

*Happy Coding :).*
