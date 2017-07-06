## GPy hack day

Welcome to the GPy hack day. This is open to everyone - but it's aimed at those already using and developing with GPy.

### Where and when

Monday 10th July, 9:30am-5pm in Pam Liversidge Design Studio 2 E05

### Aims

Key issues:

- Documentation: Too many entry points
- Accessibility for new users
- Support for developers
- Testing of documentation notebooks
- Old notebooks floating around online causing confusion
- Code documentation

### Schedule

**9:30-11:00** Worked examples (from scratch): Alan & Zhenwen
We decided that it made sense potentially to start with a model (from the maths) and start implementing it with GPy. People ask questions when it's unclear why we did something - or what something means (e.g "what does the likelihood mean?" "how does this differ from the objective?" "how do we add priors?"... how to create new kernels, gradients? optimising?)... then move onto a more complex model and repeat? (e.g. one for regression, classification, LVM??? whatever people think would be useful) - we thought working through concrete examples will show up problems with the documentation etc.

Throughout this we maybe should refer back to the documentation and see what's missing - whether it is clear as it could be, etc? What about the doc strings in the code itself?

Throughout notes will be taken to detail improvements required.

Zhenwen will also give a talk about how to extend GP models including GP regression, lvm, deep GPs.

We'll work out how these two topics will work together - key is that this is a collaborative effort and everyone should ask questions etc - maybe it'd be worth Alan looking at the documentation while he goes through this.

**11:00-12:00** Break outs? Maybe smaller groups should focus on their own areas + consider the documentation there? Also we think it might be useful if we keep GPy simple and have references to other people's work (e.g. GPclust, etc :).

**12:00 - 12:30** Paramz: Max
A lot of the trouble during development has been understanding the paramz model - here Max will try to explain it.

**12:30 - 13:30** Lunch

**13:30 - 14:30** Croucher’s team introduce the hosted, git jupyter notebook concept. This provides a nice website for documentation. We are thinking along the lines of http://scikit-learn.org/ to provide an easy way in for both users and developers.

**14:30 - 15:30** Design website/documentation structure... what to include/exclude..?

**15:30...** ?

### Outcomes

 - a plan on how to change the documentation both structurally (e.g. auto testing?) and content (where entry points are, etc)
 - a few more jupyter notebooks for 'how to' style documentation
 - a list of features or issues that need to be focused on (maybe with who is doing what) - what is needed in GPy?
- how to support related projects
 - future meetings planned?

### Other notes

We probably need to come up with frequenctly asked questions to assist with improving documentation and code?

Other ideas for the day:

- Help people currently using GPy (i.e. not just an introduction) to contribute - e.g. people have specific problems that either require better documentation or assistance in knowing how to make changes to GPy.
- Although Alan points out new people also struggle (eg with..."(where can I get a list of all the kernels, how do I get the documentation for plotting, etc), and I think a few more introduction to GPs with GPy would be useful. A couple of questions about model comparison. I think a lot of these guys would take a quick look at GPy, get confused about some of the magic, then perhaps give up. I think we could certainly do some things to make it more approachable to newbies.")
- Write new documentation maybe covering these issues (e.g. how to write a new kernel, etc, etc)
- I don't know what was talked about in Berlin, but maybe a continuation of that - what needs working on next?
- What's the future of GPy (wrt GPFlow?)
- Do we want to spend some of the time actually working on these issues? (or maybe draft out parts for later implementation, e.g. docs to write, etc)

