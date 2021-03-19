The Turing Way Training: 19 March 2021, Day 2 report: Group 3
===

###### tags: `turing-way` `Workshop` `External`

:::info
- **Event:** The Turing Way workshop
- **Date:** 18-19 March, 2021 
- **Group members:** Hannah, Andrea, Syu, Agostina
- **GitHub username:** 
- **Title:** Getting started with code review
:::

- Suggested topic: **Hosting a code review with your colleague**
- Using references in The Turing Way and beyond, discuss and plan remote collaboration as specified in your group project. 
- Please discuss and agree on a specific topic that relate to some real-case scenarios from your work.


**Prompts for preparatory discussion** 

- Main concepts you would like to discuss.
- Examples and scenarios from your research providing perspective and insight about how these concepts apply to your work.
- Discuss clear call-to-action.

*Tips to plan your report*

- Start with an itemised list. 
- When you have collected all the items, use them to structure your content. 
- Feel free to use images and external resources (check licensing), or code blocks to tell a compelling story.
- Finish by explaining how readers are expected to benefit from the subject's experiences.

# Notes

* Working with people in different time zones makes it more difficult to do code review on a call. It might be easier to use pull requests as a way to communicate. This does mean that we need to be clear and specific, even if it means writing more in the pull request itself and in the actual code documentation.
* Potential problem: expectations of the person needing the code review. Setting reasonable standards and being specific.
* Finding a dedicated space to have discussions.
* Having an easy way to access and run the code.
* Code review also obliges you to write code with human readers in mind.
* Think about the actual collaborative aspect and maybe pick a scenario to focus on.
* Be considerate with other people's time. Let them know what exactly you need review on. Ideally do this in advance so people have time to think about it.

**Suggested sections in your report**

## 1. Problem statement
(What are the main challenges? Provide background and issues these concepts address.)
* Ensuring your code to be reviewed is accessible/reproducible (across different operating systems and coding setups)
* Trying to learn a new language and not knowing the most efficient way to solve a given problem. Others might have better ways to solve that problem which you might not know about. 
* Getting feedback about our code's interface, in order to make it more usable.
* How do you get this feedback while being considerate of other people's time?
* Getting started and gauging interest in a group code review

## 2. Solutions & Recommendations
(Explain the key solutions and recommendations and how these concepts can make collaboration effective. It’s ok if the solutions don’t work in all situations but try to capture when they might need customising.)
* Code with comprehension and (try to)  make the code reviewing process easier by being clear and organised with the format and logic. The code itself does not have to look professional due to limited experience of the coder, but should be equipped with comments that help reviewers to understand. Good format to allow advanced coding (Object-oriented programming, list comprehension) to be applied.  
* Be as specific as you can in terms of the aspects of your code that need review. Is it a specific function that you are worried about? Or perhaps the way you have structured your code?
* Ask someone else to use your library/run your code, even for a toy example. If they find it hard or ask you questions on how to use it, then there is room for improvement :smile: 
* Develop code with other operating systems in mind where possible (e.g. specify your OS and environment settings) and include code run on binder to ensure others can run the code in some form - testing code on multiple operating systems also provides a better opportunity for reproducibility testing!
* Contacting your team for gauging interest (e.g. via email, raising the topic in lab meetings or sharing a poll) alongside your institution for any more experienced recommendations on how to get started with a group code review - e.g. university admin teams may have setup similar groups before. Also include people interested and institution experts in your prelimnary meetings to setup the code review group.


## 3. Examples
(Practical applications and examples. Here you can describe how you have adapted the guidance for specific purposes.)
* Scenario: live code-review session with the research group.
* The person asking for code review should share the code in advance, together with some specific questions that they'd like to be addressed [(Reference)](https://the-turing-way.netlify.app/reproducible-research/reviewing/reviewing-recommend.html).
* Mark the specific chunk of codes that require reviewing, so to save time for the reviewers. Differenciate the parts for change. 
* Prioritise the chunks which require urgent updates and feedback. 

## 4. Summary
(Conclusion, thoughts, reflections and lessons that you discussed in your group.)
* Code review is awesome! However it can seem daunting at first to put yourself out there. We are not often encouraged to share our work and ask for feedback. But doing so can have two main benefits:
    1. Help you improve your code by getting tips and tricks for multiple people.
    2. Your code will inevitably become more reproducible as a result of you having to think about people, other than yourself, reading your code.

**References**

- GitHub review: https://the-turing-way.netlify.app/collaboration/maintain-review.html
- See [The Turing Way templates](https://github.com/alan-turing-institute/the-turing-way/tree/master/book/templates/chapter-template) for more guidance.
- https://ropensci.org/blog/2017/09/01/nf-softwarereview/
- *Code reviews: the lab meeting for code* http://fperez.org/py4science/code_reviews.html
