## Advice for machine learning PhD students

[Markus Heinonen](https://markusheinonen.github.io/), Aalto University, 2025

Here's what I learned doing a machine learning PhD and supervising many others.

Accompanying [slideset](https://markusheinonen.github.io/research-tips.pptx)


**Listen to big-shots**
- Andrej Karpathy ["A Survival Guide to a PhD"](karpathy.github.io/2016/09/07/phd/)
- Patrick Kidger ["Just know stuff"](https://kidger.site/thoughts/just-know-stuff/)
- Bill Freeman ["How to do research"](people.csail.mit.edu/billf/publications/How_To_Do_Research.pdf)
- Eamonn Keogh [“How to do good research"](www.cs.ucr.edu/~eamonn/Keogh_SIGKDD09_tutorial.pdf)
- Stefano Albrecht [PhD Handbook](https://agents-lab.org/phd-handbook/)

**The three pillars.** Machine learning is (1) conceptualising, (2) communicating, and (3) implementing; in this order of importance. Maximize your time spent on understanding the problem and the solution, and minimize your time spent coding. 

**Papers are not result tables**. Don't treat papers as benchmark competitions, but opportunities to identify a novel research problem, and understand and address its root causes.

**Become a coder wizard**. Learn to automate your workflows: code, experiments, logging, analysis, plotting, results. Make sure you can reconfig and restart your experiments in minutes on a GPU cluster. Make clean code and refactor often. Learn the latest tools, and exploit LLMs. Ask your collegues for their best practise. 

**Read**. You need to become world’s top expert in your phd topic during it. This means reading 100's of papers during your phd. Do not stop reading when you hit problems with your experiments, instead start reading even more: all ML problems have already been solved by someone in some paper (almost surely).

**Write**. Formalize your ideas and models with precise and simple math in latex. Writing forces you to conceptualise and clarify your thoughts into hypotheses and claims. Aim at publication style. 

**Communicate**. Prepare presentation slides for every meeting, no matter how casual: Your audience will appreciate this. Aim at conference presentation quality. Practising presentations from the very beginning is helpful, since it forces to conceptualise your work. Remember that your supervisors work on a dozen other projects and need a context switch for every meeting. Include a setting slide, and include a slide on why are we meeting. Minimize text in slides. What are the main points you need to convey? Great slides usually have 1 picture and around 10 words per slide (not 100). Make meetings notes during the meeting, and send them to everyone immediately after the meeting.

**Do project reviews**. Present your ideas, projects and code to your collegues and other phd students for honest feedback. You will learn a ton. 

**Conceptualise**. Your math and illustrations reflect your conceptualisation of the model. If you have messy equations or figures, your thinking is still messy.

**Visualise to understand**. Plot or draw everything about your model: the loss, the optimisation, the network, the activations, the weights, the data, the likelihood, the gradients, the layers, etc. You need to understand your model inside-out.

**Run experiments slowly**. Do not rush into training the big network right away, instead take things slowly. You first need to study and understand the data, and then the problem (spend time on this). Identify the problem you want to solve in the baselines, and make sure it exists. Formulate hypotheses on how to improve. Run a sequence of more and more complex models. Start from linear regression, and build your way up. Try to change one thing at a time, and make sure you can quantify whether you improve or not. If you get stuck, avoid temptation to spend more time running experiments. Instead start reading, writing and discussing more to clarify that the problem is true, and solution is correct. See Andrej Karpathy's neural network [training recipe](http://karpathy.github.io/2019/04/25/recipe/).

**Don’t chase SOTA**. Benchmark tables are not scientifically interesting: every year new methods come up and errors go down, brrrr. Instead aim at understanding the insight behind the contribution, or finding qualitative improvements, gaps in literature, or problems behind SOTA models. These often come from understanding related works and your model more in-depth.

**Break your model**. Stress-test your model until it breaks. What are its limits? This gives you direct avenue to making a second paper. Look at the [XAI question bank](https://arxiv.org/abs/2001.02478).

**Focus on problems**. Instead of finding solutions, focus on finding problems that are true, novel and significant. Find open problems by looking at what state-of-the-art can’t do, does poorly, or ignores. Focus your time on understanding the problem, and the solution will emerge.

**Become really good in one thing**. Most scientists know one thing very well, and apply it everywhere. For instance, differential geometry, Bayes, optimisation, Fourier analysis, etc. This makes publishing papers effortless. 

**Don’t hide from your supervisors**. We love to talk about science, we love to be challenged and proven wrong, we love to hear about your ideas and progress. If you spend a week reading, don’t say that “I have no new results”; you have made lots of progress by learning new things. Actively ask for advice and feedback from your supervisor: meetings where only you talk benefit no one. Insist on regular update meetings, the more often the better.

**Be honest**. Tell your supervisor when you don’t understand something or when you are struggling. Don’t nod if you didn’t understand, ask for clarification. Implying otherwise makes it difficult to work with you. Don’t imply that you are doing fine when you aren’t. Project meetings are not an exam: you don’t need to pass. Instead, you should give transparent situation report such that people around you can help you. Don’t cancel meetings. 

**Network and socialise**. Attend a top conference in your field (NeurIPS/ICML/ICLR/etc) every year, even if you have no paper. First time you will know no one, but next time you will. Workshops are a great way to get your foot in, and practise presenting. Attend journal clubs: establish one if none exists in your school. 

**Be visible**. Make a website of yourself so that collegues and bigshots can find you. If you have no papers yet, having a technical blog is a good way to show your expertise. Make a website for each paper you make (a good [example](https://www.guandaoyang.com/PointFlow/)).

**Make papers reader-friendly.** Write in a way that is accessible to a non-expert reader. Be explicit and precise. Use illustrations, colors and short paragraphs. Shorten as much as you can. Ask LLMs to improve the language. 

**Follow the domain**. Check all orals and keynotes of all top ML conferences, even if they don't relate to your research. This tells where the field is moving, and you always get some useful ideas. Follow what your competitors are publishing. Use Google Scholar to follow seminal papers and their forward citations. 

**Attend a summer school**. Go to one on your first year.

**Do an internship**. AI company internships or research lab visits are very useful. Most labs are happy to receive students, while company processes are more stochastic. Apply early and often. Three month internships strike a good balance.

**Enjoy what you do**. Move towards projects that interest you. Finish your current project regardless. Students who deliver are more likely to get the cool projects in future. If your project is not progressing, take initiative. This is your phd thesis and career, you need to drive it forward.

**If you are stuck**. Slow down, rethink what you are doing, and discuss with your collegues (you will notice that people love to give advice!): what problem are you solving and is it the right problem? What is your goal again? If the problem is right, is the solution?

**Organize your time**. Make sure to spend at least 20% of your time reading. Do not slip from this. Keep (i) a research diary and maintain (ii) a literature review and (iii) technical report on your models. Share these as a non-changing single-click url for your supervisors.

**Queue your work**. Research is a sequence of small tasks. Treat it as FIFO queue: have a single active task at a time, and conclude it before you move forward. Do not multitask. Do not leave unfinished tasks. If your backlog is growing, stop, and resolve them first.

**Calendar, not TODO lists**. Don't make TODO lists. They expand until they become too oppressing, and you restart. Instead, allocate time for tasks on your calendar. Follow [Devi Parikh's advice](https://deviparikh.substack.com/p/calendar-in-stead-of-to-do-lists-9ada86a512dd).

**Study math**. You want to understand algebra, calculus, probability, statistics, measure theory, functional analysis, differential geometry, complex analysis, and optimisation. 

**The story of a research project**. Science builds incrementally on top of earlier results. The earlier state-of-the-art is the bedrock, and your contribution sits on top. The steps are
1) Understand the research domain, and read all papers on it
2) Be able to reproduce earlier, state-of-the-art results 
3) Demonstrate a significant short-coming in state-of-the-art
4) Find or adapt a known solution to the type of problem

**Understand the foundations**. Courses, Wikipedia or blogs do not give deep understanding. Reading textbooks cover-to-cover is useful to obtain holistic knowledge. You want to understand mathematical foundations (Deisenroth), statistical learning (Gelman, Tibshirani), classic machine learning (Bishop, Murphy) and deep learning. Delving deeper into advanced topics is even better. If you only read one book, choose Bishop or Tibshirani. Great books are:
- On math: Deisenroth et al [“Mathematics for machine learning”](https://mml-book.github.io/)
- On modern ML: Murphy [Probabilistic machine learning](https://probml.github.io/pml-book/) series, Bishops' [Deep Learning](https://www.bishopbook.com/)
- On learning theory: Mohri et al [Foundations of machine learning](https://cs.nyu.edu/~mohri/mlbook/), Shalev-Shwartz et al [Understanding Machine Learning](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/)
- On statistical learning: Tibshirani et al [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
- On Bayesian modelling: Gelman et al [Bayesian Data Analysis](https://sites.stat.columbia.edu/gelman/book/)
- On generative models: Tomczak [Deep Generative Models](https://jmtomczak.github.io/dgm_book.html)
- On information theory: MacKay [Information theory, Inference and Learning Algorithms](https://www.inference.org.uk/mackay/itila/book.html)
