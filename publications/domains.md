How to onboard yourself into an unfamiliar domain
-------------------------------------------------

*Matt Archer, Paul Brown, Stephen Dowsland, David Mawdsley, Amy Krause, Mark Turner*

  

So… you’ve just started on an exciting new data science project, but you know nothing about the domain you’re working on. Besides briefly panicking, how do you get up to speed on the area you’re working on?

  

First thing's first...it's good to meet the researchers you'll be working with as quickly as possible. Most researchers are excited about their research; this enthusiasm is infectious. Ask questions. Be interested.

  

To get a basic grounding in your new area, YouTube is an invaluable source of quick bursts of domain knowledge for both a general subject area or the detailed specifics and intricacies of a niche within that subject area. Video tutorials can take many forms but the useful ones to look for are short explainers on concepts or tooling, as well as longer form recordings of things like lectures, workshops and panel discussions. YouTube has become a primary method of user training materials for large software vendors, there are thousands of video tutorials on how to use tools or perform specific actions for things like Jupyter Notebooks, Excel and Adobe Photoshop. If there are large commonly used pieces of software in the domain you’re trying to learn, there may be similar videos available to help get started with that software platform.

  

It can be useful to ask for a background reading list from the researchers you're working with. Selectively reading a monograph on the subject can be a good way of gaining a broad overview of the subject, with the option of diving more deeply into areas of particular relevance to the project you're working on. Depending on how far removed from your own specialities and experiences the new domain is, papers or review articles can be either useful or intimidatingly heavy-going. It's always worth asking for a reading list of relevant papers; even if these are too technical at the start of the project they will become more useful as the project progresses. They are also a good source of references to existing domain specific software and libraries.

  

So now that you’ve built up a bit of knowledge around the subject area, it’s now time to check out in more detail how they get things done. This is going to involve looking at the tools that are used and, in particular, which software is currently used in that domain.

  

From the previous activities you should have accustomed yourself to different software packages that are used on a regular basis in this domain. Start out by making a list of these items, first noting what, why and where? What is the name of the software, what is it used for, why is it used, and where is it used? A good example of this would be Excel; used to wrangle data and produce visuals. It’s easy to use and is installed on all campus machines. It will run on the user’s laptop, on windows. It’s also useful to note down the licensing for this software will you be able to use it on your machine, in the cloud or HPC stack.

  

Now that you’re familiar with typical tools used, a very quick way to gain familiarity with a new domain is to get hands on experience with a typical dataset used by the investigator. As data scientists/software engineers we are at home with data, and we are trained to understand patterns quickly.

  

The opportunity to play around, be it through data visualisation or further processing with example scripts, allows us to rapidly explore the domain, posing new questions that can be addressed at follow up meetings. The data set needs not be large and might be merely an analogy to the real thing, generated with rudimentary scripts. This can be especially helpful for long-term projects where the data acquisition process is lengthy (for instance, astronomical surveys, where data appears in cycles ) and so proof of principal investigations with dummy data is essential.

  

Let a domain expert walk you through an example ("a typical day") to show you what they do. This way you can ask questions and get a first hand experience how the domain expert works, what kind of environment they are using etc. For example, having worked with seismologists, a typical use case would look like this: first they select and download data from an online catalog; this data is in a binary format. They use a Python library to apply a number of analysis steps and finally they visualise the analysis results. As you go, ask lots of questions:

  

-   What software/tools are they using and why?
    
-   Are there any licensing issues?
    
-   Is that their preferred way of working or what would they like to change?
    
-   What do the results mean, and what are they looking for?
    
-   How do they tell when something went wrong?
    
-   What do they do with the results? Are they stored, published, discarded?
    

  
  

We would also encourage you to attend lectures (if possible) relevant to the domain area which might encourage greater familiarity with terminology used. This might be helpful particularly to put the work in context of the discipline as a whole.

  

More often than not a domain has language all of its own, and learning that language can be critical to the success of the project. Generating a glossary of terms can be useful to always have to hand to refer to when encounting words and terms unique to that domain. This glossary can usually be bootstrapped from a domain expert, and then added to as words and phrases are encountered throughout the project. Located in some kind of shared project space such as a git repository or a project management tool the glossary can be shared between project team members and refined as the project proceeds.

  

In order to determine a suitable format for the output and the software, as far as possible, the full requirements for this output should be agreed upon in advance with the domain specialist. This will prevent time consuming changes needing to be made to software design if requirements change and the current design proves to be not optimal or even incompatible with the changing aims of the software. This places responsibility on the domain specialist to have thought this all through and to communicate requirements effectively, and places responsibility on the software engineer to ask the right questions, and to anticipate possible issues. Issues to consider include:

  

**Operating System Portability**
Text files do not transfer well between Windows and Unix. Binary files may not transfer at all between operating systems.

**Human Readable v Machine Readable**
Outputs may be required to be processed for analysis and visualisation on a webpage. A format such XML is a machine readable format with processing libraries available in most platforms. However, a number of other users may need to be able to read and verify these files so functions to convert to csv for display in a spreadsheet. Outputs should be in common portable formats so ease conversion between file types.

**Inputs & Outputs**
If the output of the application is to provide input to pre-existing software as part of an analysis pipeline, what are the input requirements of this software? and what options should be included in our output format/which are not relevant?

**Post-processing Requirements**
Do your outputs require further processing, statistical analysis or database storage? Think about making the transfer to the next stage as seamless as possible.

  

These tips on getting started are jumping off points for ways of finding and absorbing more information. Some can be done in 10 minutes, others are more of a mindset to hone over the length of a project. The effectiveness of each one will largely depend on your own learning style and the ethos of your team and project members. Hopefully by now you’re well on your way to, if not being a domain expert, at least feeling at home in this new domain!
