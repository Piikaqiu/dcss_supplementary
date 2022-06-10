# Complex Problems 

Jillian Anderson    
Simon Fraser University  

I like to think of data science as a toolbox filled with specific tools and approaches for doing computational work. As with the physical toolbox that sits in my closet at home, my data science toolbox has evolved and grown as I encountered new challenges that needed to be tackled. Now, when I look into my toolbox, I see it contains a variety of tools and approaches, some of which haven’t been picked up in years but are ready to be used should the need arise. When faced with a big complex computational problem I can select a handful of data science techniques from my toolkit and work on solving the problem at hand. This can be easier said than done, since unlike assembling furniture, complex data science problems don’t come with detailed instructions. I like to make my own instructions by diagramming a pipeline that will layout the states data will go through during your project.

To do this, start at a high level. Whatever state the data is in now should be the first box in your diagram. Sometimes this will be an already collected dataset, but it could also be a list of variables, websites, or stakeholders that will help guide data collection. Next, think about where you need the data to be at the very end of the project. This should be the final box in the diagram.

Now, add as many intermediary boxes between the initial and final states as you can. Perhaps you have chosen an API for data collection, a statistical method for analysis, or a framework for visualization. These decisions help inform exactly what states the data will flow through. Continue to fill in the diagram by considering what steps are required to go from one state to the next. For the time being, don’t worry about what needs to happen beyond the two states you are considering, you can deal with that later. Continue to add intermediary states until transformation from one state to the next feels more like a step than a leap. This is an iterative process. It is okay to revisit steps if you realize adding an intermediary state would be beneficial down the line.

Once you have a series of intermediary states defined, it becomes easier to implement the entire pipeline. Once all the components have been implemented, they can be connected together, with the output from one becoming the input to another. This pipeline becomes the data science equivalent of the instruction booklet for assembling furniture. At each step in the pipeline, you can concentrate on using a single tool to accomplish a single task, trusting that the collection of individual steps will result in a fully assembled piece of furniture at the end.