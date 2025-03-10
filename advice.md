## Advice for machine learning PhD students

[Markus Heinonen](https://markusheinonen.github.io/), Aalto University, 2025

Here's what I learned doing a machine learning PhD and supervising many others.

Accompanying [slideset](https://markusheinonen.github.io/research-tips.pptx)


**(1) Listen to big-shots**
- Andrej Karpathy ["A Survival Guide to a PhD"](https://karpathy.github.io/2016/09/07/phd/)
- Patrick Kidger ["Just know stuff"](https://kidger.site/thoughts/just-know-stuff/)
- Bill Freeman ["How to do research"](https://people.csail.mit.edu/billf/publications/How_To_Do_Research.pdf)
- Eamonn Keogh [“How to do good research"](https://www.cs.ucr.edu/~eamonn/Keogh_SIGKDD09_tutorial.pdf)
- Stefano Albrecht [PhD Handbook](https://agents-lab.org/phd-handbook/)

**(2) The three pillars.** Machine learning is (1) conceptualising, (2) communicating, and (3) implementing; in this order of importance. Maximize your time spent on understanding the problem and the solution, and minimize your time spent coding. 

**(3) Become a coder wizard**. Learn to automate your workflows: code, experiments, logging, analysis, plotting, results. Make sure you can reconfig and restart your experiments in minutes on a GPU cluster. Make clean code and refactor often. Learn the latest tools, and exploit LLMs. Ask your collegues for their best practises. *One can't survive a PhD anymore without being at least an adequate ML engineer*.

**(4) Papers are not result tables**. Don't treat papers as benchmark competitions, but opportunities to identify a novel research problems, and understand and address its root causes. 

**(5) Don’t chase SOTA**. Benchmark tables are not scientifically interesting: every year new methods come up and errors go down, brrrr. Instead aim at understanding the insight behind the contribution, or finding qualitative improvements, gaps in literature, or problems behind SOTA models. These often come from understanding related works and your model more in-depth.

**(6) Focus on problems**. Instead of finding solutions, focus on finding problems that are true, novel and significant. Find open problems by looking at what state-of-the-art can’t do, does poorly, or ignores.

**(7) Conceptualise**. Refactor and rework your math and illustrations until they are so clear that an outsider could grasp the ideas at ease from a first glance. This often takes a long time, but will help make a best realisation of your contributions.

**(8) Make a point**. Don't just present a method with 2% better performance. So what? Why is this important and significant; what do we learn from this; why should everyone know this method?

**(9) Do your homework**. Follow good ML principles and keep the quality bar high. Don't make shortcuts. Understand your own code and data and competing methods throughout. Prepare for any question a collegue could have. 

**(10) Read**. You need to become world’s top expert in your phd topic during it. This means reading 100's of papers during your phd. Do not stop reading when you hit problems with your experiments, instead start reading even more: all ML problems have already been solved by someone in some paper (almost surely).

**(11) It's a marathon**. PhD is around 1000 working days. Remember to plan your research long-term. 

**(12) How to present**. Make slides for every meeting: Your audience will appreciate this. Include a setting slide, and include a slide on why are we meeting. Minimize text in slides. Distill your ideas: what are the main points you need to convey? Great slides usually have 1 picture and around 10 words per slide (not 100). Make meetings notes and distribute them.

**(13) How to give a talk**. Math-heavy talks benefit no one: the experts in audience already know your work, and rest don't care. Talks should be aimed at a non-expert audience who might not even know what the domain is. Spend third of your time giving an overview to the domain: why is it important and cool? Spend rest on the specific problem, and your high-level ideas. Remember that an average listener has mental budget for max 5 equations, and will stop listening if you present more. 

**(14) Do project reviews**. Present your ideas, projects and code to your collegues and other phd students for honest feedback. You will learn a ton. 

**(15) Debug to understand**. When things are not working, visualise  everything: the loss, the optimisation, the network, the activations, the weights, the data, the likelihood, the gradients, the layers, etc.

**(16) Slow down to speed up**. Spend time understanding the problem you want to solve, and verify it exists. Formulate hypotheses on how to improve. Start from trivial baselines (random forest, linear regression), then simple neural netowrks, and finally SOTA baselines.  Run a sequence of more and more complex models, where ideally you change and quantify only one thing at a time. If you get stuck, avoid temptation to spend more time running experiments. Instead start reading, writing and discussing more to clarify that the problem is true, and solution is correct. See Andrej Karpathy's neural network [training recipe](http://karpathy.github.io/2019/04/25/recipe/).

**(17) Don't tell me it doesn't work**. Why doesn't it? What steps did you make to narrow down where the problem lies?

**(18) Break your model**. Stress-test your model until it breaks. What are its limits? This gives you direct avenue to making a second paper. Look at the [XAI question bank](https://arxiv.org/abs/2001.02478).

**(19) Become really good in one thing**. Most scientists know one thing very well, and apply it everywhere. For instance, differential geometry, Bayes, numerics, etc. This makes publishing papers efficient. 

**(20) Make first-author papers**. To have a PhD and a career afterwards, you need to focus on making first-author papers where you were the driving force. If your paper record is mostly middle-author papers people can interpret this as poor priorities or inability to deliver.

**(21) Don’t hide from your supervisors**. Supervisors love talking about science, being challenged, and hearing about your ideas. If you spend a week reading, don’t say that “I have no new results”; you have made lots of progress by learning new things. Actively ask for advice and feedback from your supervisor: meetings where only you talk benefit little. Insist on regular update meetings.

**(22) Be honest**. Tell your supervisor when you don’t understand something or when you are struggling. Don’t nod if you didn’t understand, ask for clarification. Implying otherwise makes it difficult to work with you. Don’t imply that you are doing fine when you aren’t. Project meetings are not an exam: you don’t need to pass. Instead, you should give transparent situation report such that people around you can help you. Don’t cancel meetings. 

**(23) Network and socialise**. Attend a top conference in your field (NeurIPS/ICML/ICLR/etc) every year, even if you have no paper. Workshops are a great way to get your foot in, and practise presenting.  

**(24) Be visible**. Have a website for collegues and bigshots to find you. If you have no papers yet, having a technical blog is a good way to show your expertise. Make a website for each paper you make (a good [example](https://www.guandaoyang.com/PointFlow/)).

**(25) Make papers reader-friendly.** Write in a way that is accessible to a non-expert reader. Be explicit and precise. Use illustrations, colors and short paragraphs. Shorten as much as you can. Ask LLMs to improve the language. Write simple papers. If you can't, the idea is not yet ready from the oven.

**(26) Follow the domain**. Check all orals and keynotes of all top ML conferences, even if they don't relate to your research. This tells where the field is moving, and you always get some useful ideas. Follow what your competitors are publishing. Use Google Scholar to follow seminal papers and their forward citations. 

**(27) Attend a summer school**. Go to one on your first year.

**(28) Do an internship**. Company internships or research lab visits are very useful. Most labs are happy to receive students, while company processes are stochastic. Apply early and often. Three month internships strike a good balance.

**(29) Enjoy what you do**. Move towards projects that interest you. Finish your current project regardless. Students who deliver are more likely to get the cool projects in future. If your project is not progressing, take initiative. This is your phd thesis and career, you need to drive it forward.

**(30) If you are stuck**. Slow down, rethink what you are doing, and discuss with your collegues (you will notice that people love to give advice!): what problem are you solving and is it the right problem? What is your goal again? If the problem is right, is the solution?

**(31) Organize your time**. Make sure to spend at least 20% of your time reading. Do not slip from this. Keep a research diary and a technical report on your project. Share these as a persistent single-click url for your supervisors.

**(32) Queue your work**. Research is a sequence of small tasks. Treat it as FIFO queue: have a single active task at a time, and conclude it before you move forward. Do not multitask. Do not leave unfinished tasks. If your backlog is growing, stop, and resolve them first.

**(33) Calendar, not TODO lists**. Don't make TODO lists. They expand until they become too much, and you restart. Instead, allocate time for tasks on your calendar. Follow [Devi Parikh's advice](https://deviparikh.substack.com/p/calendar-in-stead-of-to-do-lists-9ada86a512dd).

**(34) Study math**. You want to understand algebra, calculus, probability, statistics, measure theory, functional analysis, differential geometry, complex analysis, and optimisation. 

**(35) The usual story**. Science builds incrementally on top of earlier results. The earlier state-of-the-art is the bedrock, and your contribution sits on top. The steps are
1) Understand the research domain, and read all papers on it
2) Be able to reproduce earlier, state-of-the-art results 
3) Demonstrate a significant short-coming in state-of-the-art
4) Find or adapt a known solution to the type of problem

**(36) Read books**. Courses, Wikipedia or blogs do not give deep understanding. Reading textbooks cover-to-cover is useful to obtain holistic knowledge. You want to understand mathematical foundations (Deisenroth), statistical learning (Gelman, Tibshirani), classic machine learning (Bishop, Murphy) and deep learning. Delving deeper into advanced topics is even better. If you only read one book, choose Bishop or Tibshirani. Great books are:
- On math: Deisenroth et al [“Mathematics for machine learning”](https://mml-book.github.io/)
- On modern ML: Murphy [Probabilistic machine learning](https://probml.github.io/pml-book/) series, Bishops' [Deep Learning](https://www.bishopbook.com/)
- On learning theory: Mohri et al [Foundations of machine learning](https://cs.nyu.edu/~mohri/mlbook/), Shalev-Shwartz et al [Understanding Machine Learning](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/)
- On statistical learning: Tibshirani et al [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
- On Bayesian modelling: Gelman et al [Bayesian Data Analysis](https://sites.stat.columbia.edu/gelman/book/)
- On generative models: Tomczak [Deep Generative Models](https://jmtomczak.github.io/dgm_book.html)
- On information theory: MacKay [Information theory, Inference and Learning Algorithms](https://www.inference.org.uk/mackay/itila/book.html)
