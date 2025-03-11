
## Advice for machine learning PhD students

[Markus Heinonen](https://markusheinonen.github.io/), Aalto University, March 2025 

Here's what I learned doing a machine learning PhD and supervising many others.

Accompanying [slideset](https://markusheinonen.github.io/research-tips.pptx)

**Listen to big-shots**
- Andrej Karpathy ["A Survival Guide to a PhD"](https://karpathy.github.io/2016/09/07/phd/)
- Patrick Kidger ["Just know stuff"](https://kidger.site/thoughts/just-know-stuff/)
- Bill Freeman ["How to do research"](https://people.csail.mit.edu/billf/publications/How_To_Do_Research.pdf)
- Eamonn Keogh [“How to do good research"](https://www.cs.ucr.edu/~eamonn/Keogh_SIGKDD09_tutorial.pdf)
- Stefano Albrecht [PhD Handbook](https://agents-lab.org/phd-handbook/)

**The three pillars.** Machine learning is (1) conceptualising, (2) communicating, and (3) implementing; in this order of importance. To minimize time spent coding one should maximize time spent on understanding the problems and the solutions. 

**Clarity is all you need**. Research often boils down to simplifying the problems, solutions and ideas to their simplest version. It's a good idea to refactor and rework the math until it's so clear that an outsider could grasp the ideas at ease from a first glance. This often takes time, but will help make a best realisation of a contribution. Implementing, writing and publishing becomes much easier after the conceptual work is done.

**Become a coder wiz**. Learn to automate your workflows: code, experiments, runs, logging, analysis, plotting, results. Make sure you can reconfig and restart your experiments in minutes on a GPU cluster. Make clean code and refactor often. Learn the latest tools, and exploit LLMs. Ask your collegues for their best practises. **One can't survive a PhD anymore without being an adequate ML engineer**. This can easily accelerate research output 10x.

**SOTA is not science**. Paper's should not be treated as benchmark competitions, but opportunities to identify novel research problems and understand and address their root causes. Benchmark tables are not scientifically interesting: every year new methods come up and errors go down, brrrr. Instead aim at understanding the insight behind the contributions, or finding qualitative improvements, gaps in literature, or problems behind SOTA models. These often come from understanding related works and your model more in-depth. By solving true open problems one obtains SOTA as a side-effect.

**Focus on problems**. Instead of finding solutions, focus on finding problems that are true, novel and significant. Find open problems by looking at what state-of-the-art can’t do, does poorly, or ignores.

**Make a point**. Don't just present a method with 2% better performance. So what? Why is this important and significant; what do we learn from this; why should everyone know this method?

**It's a marathon**. PhD is around 1000 days of work. Plan long term and check progress yearly.

**Keep learning**. One needs to become world’s top expert in the phd topic during it. This means reading 100's of papers during your phd. Most scientists know one thing very well, and apply it everywhere. For instance, differential geometry, Bayes, numerics, etc. This makes publishing much easier. 

**Do the homework**. Follow good ML principles and keep the quality bar high. Don't make shortcuts. This will come around and cause trouble in future. Understand your own code and data and literature throughout. Prepare for any question a collegue could have. Don't submit unfinished manuscripts: I try to reject papers with typos, poor formatting, poor figures, messy presentation, or sloppy math.

**Debug to understand**. When things are not working, visualise everything: the loss, the optimisation, the network, the activations, the weights, the data, the likelihood, the gradients, the layers, etc. A "that's odd.." moment will come.

**Do project reviews**. Present your ideas, projects and code to other phd students for honest feedback. You will learn a ton. If this doesn't exist in your lab, make it exist. 

**How to present**. Make slides for every meeting. Include a context slide. Distill your ideas to their simplest version: what are the main points you need to convey? Great slides usually have 1 picture and little text (closer 10 words than 100 per slide). Distribute meeting agenda beforehand and notes afterward.

**How to give a talk**. Math-heavy talks are pointless: the experts in audience already know your work, and rest can't follow. Talks should be aimed at a non-expert audience to inspire them about stuff they don't know about. Spend third of your time giving a big picture of the domain: why is it important and cool? Spend rest on the specific problem, and your high-level ideas. Remember that an average listener has mental budget for max 5 equations, and will stop listening if you present more. 

**Slow down to speed up**. Spend time understanding the problem you want to solve, and verify it exists. Formulate hypotheses on how to improve. Start from trivial baselines (random forest, linear regression), simple neural networks, and pre-trained SOTA baselines. Run a sequence of more and more complex models, where ideally you change and quantify only one thing at a time. You want to do coordinate descent: move along one design axis at a time. See Andrej Karpathy's neural network [training recipe](http://karpathy.github.io/2019/04/25/recipe/) and Google's [DL tuning playbook](https://github.com/google-research/tuning_playbook). 

**Don't tell me "it doesn't work"**. Why doesn't it? What steps did you make to narrow down where the problem lies?

**Break your model**. Stress-test your model until it breaks. What are its limits? This gives you direct avenue to making a second paper. Look at the [XAI question bank](https://arxiv.org/abs/2001.02478).

**Make first-author papers**. To have a PhD and a career afterwards, you need to focus on making first-author papers where you were the driving force. A paper record of middle-author papers indicates poor priorities and inability to deliver.

**Don’t hide from your supervisors**. Supervisors love talking about science, being challenged, and hearing about your ideas. Actively ask for advice and feedback from your supervisor: meetings where only you talk benefit no one. Insist on regular update meetings.

**Be honest**. Tell your supervisor when you don’t understand something or when you are struggling. Don’t nod if you didn’t understand, ask for clarification. Implying otherwise makes it difficult to work with you. Don’t imply that you are doing fine when you aren’t. Never cancel meetings. 

**Go to conferences**. Attend a top conference in your field (NeurIPS/ICML/ICLR/etc) every year, even if you have no paper. Workshops are a great way to get your foot in, and practise presenting. 

**Be visible**. Have a website for collegues and bigshots to find you. If you have no papers yet, having a technical blog is a good way to show your expertise. Make a website for each paper you make (a good [example](https://www.guandaoyang.com/PointFlow/)).

**Write simple papers.** Write in a way that is accessible to a non-expert reader. Use illustrations, colors and short paragraphs. Use LLMs to polish the language. Shorten, distill and simplify as much as you can. If you can't write a simple paper, the idea is not yet ready from the oven. Be explicit and use precise math. Organise internal mock peer-review with other students.

**Go to the point** Write what you want to say, and nothing more. For instance, a short introduction of 2 paragraphs is often ideal. Bullet your contributions. Related works often works best at the end of the paper. Make a comparison table wrt competing methods. Add conclusions in boxes. Color equations. Use \underbrace copiously. Put math in full lines. Captions should have two phrases: conclusion and description. Make figures and tables self-contained. Annotate everything about figures. Figure font size should not decrease from paper. Include standard deviations. Put full math derivations in appendix.

**Follow the domain**. Check all orals and keynotes of all top ML conferences, even if they don't relate to your research. This tells where the field is moving, and you always get some useful ideas. Follow what your competitors are publishing. Use Google Scholar to follow seminal papers and their forward citations. 

**Attend a summer school**. Go to one on your first year.

**Do an internship**. Company internships or research lab visits are very useful. Most labs are happy to receive students, while company processes are stochastic. Apply early and often. Three month internships strike a good balance.

**Enjoy what you do**. Move towards projects that interest you. Finish your current project regardless. If your project is not progressing, take initiative. This is your phd thesis and career, you need to drive it forward. Don't expect a supervisor to make the phd happen.

**If you are stuck**. Slow down, rethink what you are doing, and discuss with your collegues (you will notice that people love to give advice!): what problem are you solving and is it the right problem? If the problem is right, is the solution? Keep reading literature: all ML problems have already been solved by someone in some paper (almost surely).

**Organize your time**. Make sure to spend at least 20% of your time reading. Do not slip from this. Keep a research diary and a technical report on your project. Share these as a persistent single-click url for your supervisors.

**Queue your work**. Research is a sequence of small tasks. Treat it as FIFO queue: have a single active task at a time, and conclude and close it before you move forward. Do not multitask. Do not leave unfinished tasks. If your backlog is growing, stop, and resolve them first.

**Calendar, not TODO lists**. Don't make TODO lists. They expand until they become unbearable, and you restart. Instead, allocate time for tasks on your calendar. Follow [Devi Parikh's advice](https://deviparikh.substack.com/p/calendar-in-stead-of-to-do-lists-9ada86a512dd).

**Study math**. You want to understand algebra, calculus, probability, statistics, measure theory, functional analysis, differential geometry, complex analysis, and optimisation. 

**The ideal story**. Science builds incrementally on top of earlier results. The earlier state-of-the-art is the bedrock, and your contribution sits on top. A supervisor probably expects to see these steps:
1) Understand the research domain, and read all papers on it
2) Be able to reproduce earlier, state-of-the-art results 
3) Demonstrate a significant short-coming in state-of-the-art
4) Find or adapt a known solution to the type of problem

**Read books**. Reading textbooks cover-to-cover is useful to obtain holistic knowledge. You want to understand mathematical foundations (Deisenroth), statistical learning (Hastie), machine learning (Bishop) and deep learning (Murphy). If you only read one book, go for Bishop. Great books are:
- On math: Deisenroth et al [Mathematics for machine learning](https://mml-book.github.io/)
- On modern ML: Murphy [Probabilistic machine learning](https://probml.github.io/pml-book/) series, Bishops' [Deep Learning](https://www.bishopbook.com/)
- On learning theory: Mohri et al [Foundations of machine learning](https://cs.nyu.edu/~mohri/mlbook/), Shalev-Shwartz et al [Understanding Machine Learning](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/)
- On statistical learning: Hastie et al [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
- On Bayesian modelling: Gelman et al [Bayesian Data Analysis](https://sites.stat.columbia.edu/gelman/book/)
- On generative models: Tomczak [Deep Generative Models](https://jmtomczak.github.io/dgm_book.html)
- On information theory: MacKay [Information theory, Inference and Learning Algorithms](https://www.inference.org.uk/mackay/itila/book.html)
