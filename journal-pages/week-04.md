---
layout: default
---

# Week 4 – Artificial Intelligence

[← Back to Home](../index.md)

## Overview

Week 4 marked a shift in the course from working with real-time data to a more critical and practical exploration of artificial intelligence as a design tool. The session began with a brief review of real-time data visualization and an update on the progress of Making Journal, followed by **Experiment 4: Artificial Intelligence**. This segment covered discussions on ambient coding, ethical issues surrounding AI, data sovereignty, local AI tools (such as Ollama), and cloud-based tools (such as NotebookLM), and concluded with the drafting of reflective proposals for the next phase of the course.

## In-Class Activity – Live Data Review and Progress Check

At the start of the class, we reviewed **Experiment 3: Live Data**. Working in pairs, we shared our real-time data visualization projects (or our plans, if the projects weren’t yet complete) and discussed the creation process, the real-time data sources we used, what our projects revealed, and what we would develop further if we had more time. This approach provided a satisfying conclusion to the previous experiment, as it prompted me to explain the technical implementation and reflect on the design decisions behind the work. It also made me realize that the weekly experiments are not just about creating a final product, but also about documenting the process clearly so that others can understand the reasoning behind it.

The class then moved into a broader progress check on the Making Journal. The slides emphasised that by this point the journal should include the in-class and independent study work for Experiments 1, 2, and 3, and that technical details such as file structure, asset folders, consistent Markdown formatting, and correct publishing through GitHub Pages also mattered. This reinforced the idea that documentation is itself a design practice rather than something added at the end.

## In-Class Activity – Vibe Coding and Artificial Intelligence in Design

Following the progress review, the course introduced **Experiment 4: Artificial Intelligence**. One of the key concepts is **vibe coding**, which the slides describe as building software by describing requirements in natural language and using large language models to generate code. The slides also emphasize foundational best practices, including clearly defining tasks, reviewing the generated code, conducting tests, optimizing prompts, and starting with a small feature before gradually expanding. This framework is particularly useful because it positions AI as a conversational, iterative tool that requires the designer’s judgment and guidance, rather than an all-knowing, all-powerful replacement.

The discussion then expanded to broader questions: how artificial intelligence will transform design practice, and what concerns it may raise. The lecture highlighted the distinction between “agentive artificial intelligence” and “generative artificial intelligence,” linking these concepts to the skills needed in the future, such as AI literacy, creative thinking, resilience, curiosity, and analytical thinking. These perspectives broadened the scope of the discussion beyond mere software or convenience. AI was presented as a force capable of transforming how designers work, determining which skills are essential, and defining the responsibilities that come with using these tools.

## In-Class Activity – Ethics, Labour, and Data Sovereignty

A major part of the class focused on the ethical dimensions of artificial intelligence. The lecture used Trevor Paglen’s *From ‘Apple’ to ‘Anomaly’* to show how systems such as ImageNet rely on large-scale classification practices that include problematic and biased labels, as well as significant hidden labour from poorly paid workers. This made the issue of artificial intelligence feel less abstract and more material, because it connected machine learning to both human labour and the politics of categorisation.

The slides then turned to the **ethical use of artificial intelligence in design**, including considerations regarding consent, the reuse of creative works in training datasets, and the importance of using one’s own images or data for prompts—rather than borrowing an artist’s name or style. These points tie into a broader sense of responsibility: the use of generative tools is not neutral, and design decisions regarding prompts, tools, and data sources have ethical consequences.

This discussion expanded further through **data sovereignty** and **Māori data sovereignty**, which raised questions about who controls data, where it is stored, who can access it, and under which legal and cultural frameworks it is governed. This was especially important because it shifted the conversation away from artificial intelligence as just a creative shortcut and toward artificial intelligence as a system embedded within ownership, governance, and power. The examples from the slides encouraged me to think more critically about where data comes from and who has authority over it.

## In-Class Activity – Local Artificial Intelligence with Ollama

The session then shifted to **local artificial intelligence**, beginning with an introduction to Ollama. The slides described Ollama as a free, open-source tool that allows users to run AI models on their own computers without requiring an account or cloud processing, and to save prompts and output results locally on their devices. At the same time, the slides noted that models capable of running locally on personal computers do not perform as well as large-scale cloud systems.

Following the instructions in class, I completed the entire process of downloading Ollama, installing it, and configuring it in the terminal. The slides clearly outlined the workflow: download Ollama, open the terminal, fetch a model (such as `qwen3:1.7b`), and then run it locally. After following this process, I gained a firsthand understanding of the difference between local AI and web-based tools. Unlike opening a browser and logging into a cloud service, this interaction is much more direct, as it is facilitated by software installed on my own computer.

![Class Image](../assets/week-04/design240(p5).png)
*Downloading Ollama and preparing the local artificial intelligence workflow.*

After installation, I used the local model and tried asking it questions. One of the things I tested was asking for information about Auckland—something that’s obviously available online—but it took 61.8 seconds and the output was rather sparse. This made me realize that while local tools may seem more technical compared to cloud-based ones, they lack polish. However, they also provide a more intuitive view of the underlying architecture of artificial intelligence. Instead of interacting with an invisible remote service, you’re interacting with a model that’s clearly running on your own device. This makes the relationship between software, hardware, and functionality much more concrete.

![Class Image](../assets/week-04/design240(p16).png)
*Early interaction with a local model through the terminal and local artificial intelligence interface.*

## In-Class Activity – Experimenting with Local Model Output

The next part of the activity involves spending some time interacting with the local model and testing the limits of its capabilities. The presentation suggests having it describe previous experimental data, write a short piece of p5.js code, or answer some questions typically asked of ChatGPT, and then comparing the quality of the responses.

I used a local model to generate a simple example website. I entered a natural language prompt asking it to write code for a website, and it returned a basic structure consisting of HTML, Cascading Style Sheets (CSS), and JavaScript. I then copied this content into a local file and opened it in a browser to test the results. This vividly demonstrates the practical application of “atmosphere programming.” It shows that the model can generate working code based on broad prompts, but it also clearly indicates that designers still need to test and interpret the output to determine whether it is truly suitable. While the generated results are usable, they are fairly generic, which led me to reflect on the trade-off between speed and originality.

![Class Image](../assets/week-04/design240(p10).png)
*Prompting a local model to generate simple website code.*

![Class Image](../assets/week-04/design240(p11).png)
*The generated website opened and tested in the browser.*

## In-Class Activity – Cloud Artificial Intelligence and NotebookLM

After working with local artificial intelligence, the class contrasted this with **cloud-based artificial intelligence**. The slides explained that tools such as ChatGPT, Copilot, and Gemini send prompts to remote servers, rely on internet connectivity, and use larger, more capable models, but also involve data leaving the user’s machine. The slides also compared university-supported tools and then introduced **NotebookLM** as a research tool that works by drawing on the sources users upload. It can synthesise across documents, websites, and media, and can generate outputs such as text summaries, tables, mind maps, and audio overviews.

![Class Image](../assets/week-04/design240(p7).png)
*Creating a NotebookLM `notebook` using Making Journal*

In class, I created a NotebookLM notebook using my own course materials. The course materials required us to upload relevant materials from our experiments to date, combine Making Journal with other related materials, and then create a `context.md` file to summarize the project by answering three questions: the most interesting experiment, a recurring theme, and areas yet to be explored. I completed this process by following these steps: creating the context file in Markdown format, previewing it, and then uploading it to NotebookLM along with my journal source files.

![Class Image](../assets/week-04/design240(p12).png)
*Creating and previewing the `context.md` file used to frame the notebook.*

After setting up the notebook, I used the NotebookLM chat feature to ask a few questions, such as: If I treat this data as documentation for a design project, what would the final design outcome look like? And what aspects should I focus on based on this data? The responses were very helpful because they highlighted recurring themes, particularly regarding personal data, digital workflows, and the transition from physical to digital processes. Unlike interactions with generic chatbots, what made this exchange unique was that the responses were based on the materials I provided, making the conversation more focused and project-specific.

![Class Image](../assets/week-04/design240(p13).png)
*Update `context.md` file to notebook.*

![Class Image](../assets/week-04/design240(p14).png)
*Asking source-based questions inside NotebookLM and reading the responses.*

![Class Image](../assets/week-04/design240(p15).png)
*Asking source-based questions inside NotebookLM and reading the responses.*

## In-Class Activity – Reflective Proposal and Ideation

The final section of the course shifts to the next phase of assessment: the **Reflective Proposal**. The slides explain that this proposal marks a transition from a broad experimental phase to a focused design direction, requiring students to define the thematic focus, data sources, future scenarios, and anticipated impact for their final data-driven visualization project. The slides also emphasize that a strong proposal must be concise, feasible, and clearly connect to previous experiments and relevant concepts regarding data presentation.

This session included an **ideation activity** and a **pair interview**. We were encouraged to review our journals, identify the experiments that felt most meaningful, and begin outlining potential project directions. NotebookLM and the context files played a crucial role at this stage, as they provided me with a fresh perspective on my own work. Not only could I manually review my past work, but I could also observe how AI tools interpreted the patterns in my various experiments. While this cannot replace my personal reflection, it does help generate directions and questions that may support the proposal-writing phase.

## Reflection on In-Class Activities

Week 4 has been the most conceptually broad week so far, as it combines technical experimentation with ethical and critical issues. In previous weeks, the course focused more directly on practical tasks: plotting data, building interactions, and visualizing real-time data. While this week still involves hands-on work, it also explores the systems on which AI relies, whose labor underpins it, what happens to our data when we use cloud systems, and how to use AI more responsibly in design. This shifts the focus of this week’s course from a tutorial on new tools to a broader reflection on how to use these tools critically.

The comparison between **local** and **cloud** AI is particularly insightful. When using Ollama, I feel that while the AI’s capabilities are somewhat limited, it is also more transparent, as I can clearly see that the model is installed locally and runs on my own hardware. In contrast, NotebookLM appears more powerful and mature, especially given its ability to integrate information from multiple sources and generate more structured feedback. Comparing these two approaches has made me realize that different AI tools are not interchangeable. They differ in terms of functionality, workflow, privacy protection, and intended use.

Another key insight gained this week is that artificial intelligence works best when used as part of a reflective process, rather than simply as an automatic answer generator. The most compelling moments in the classroom did not arise from directly adopting the first results generated, but rather from testing, comparing, and questioning the tool, and considering it within my own design process. This became particularly important as the course entered the proposal phase—at which point the goal was no longer to experiment broadly, but to identify a meaningful and viable direction to move forward.

## Independent Study – AI-Assisted Data Exploration

For my independent research project in Week 4, I selected the **[DOC Campsites](https://catalogue.data.govt.nz/dataset/doc-campsites4)** dataset from the New Zealand Open Data Catalog. This dataset focuses on campsites managed by the Department of Conservation and addresses a very real aspect of life in New Zealand (Aotearoa): outdoor recreation, travel, public land, and the use of conservation infrastructure. I chose this dataset because it is both practical and culturally distinctive. Campsites are not merely tourist facilities; they are an integral part of how people experience nature, travel, and public spaces in New Zealand. I was curious to see how AI tools would interpret such a dataset and which stories or representations they would prioritize.

![Independent Study](../assets/week-04/design240(p17).png)
*Select dataset from the New Zealand Open Data Catalog*

## Understanding the Data with AI

I uploaded the CSV file to Gemini and first asked it to explain the contents of the dataset: the meaning of each column, what the values represent, the total volume of data, and which data points are missing or incomplete. As a first step, this response was extremely helpful because it quickly summarized the structure of the dataset and highlighted key categories such as site name, region, campground type, coordinates, transportation information, and capacity. Gemini also helped me realize that the dataset contained hundreds of records and multiple columns, making it far more complex than I had initially anticipated when I set out to interpret it manually.

I think the most valuable aspects here are speed and the big-picture perspective. This AI tool can convert raw CSV files into easy-to-understand insights much faster than I could ever do manually. It gives me a practical starting point for thinking about the stories that might be hidden in the data—especially regarding regional distribution, accessibility, capacity, and the level of services at campsites.

At the same time, I noticed that this explanation remains rather general. While it helps describe the content of the dataset, it does not fully explore the dataset’s purpose, how the classifications were constructed, or what might be missing from it. For example, the data describes campsites as structured entries, but it may not capture the actual experience, environmental conditions, cultural significance, or the people who use these sites and why. This made me realize that while artificial intelligence can help us understand structure, it does not automatically provide deeper critical interpretations.

![Independent Study](../assets/week-04/design240(p18).png)
*Using Gemini to explain the structure and contents of the DOC Campsites dataset.*

## First Visualisation and Initial Limitations

After analyzing the dataset, I asked Gemini to **produce a visualisation of the data**. The first result was a simple chart. While it was technically useful, I did not accept it as the final answer because the assignment required a more in-depth dialogue and the generation of multiple visual representations, rather than stopping at the first result.

This initial experiment immediately revealed a common tendency among AI tools: when asked to visualize data, they often default to standard chart formats. While the generated charts are concise and easy to read, they also tend to look very similar. They resemble an automatically generated summary rather than a carefully designed presentation. This is important because it made me realize that simply obtaining a result does not mean obtaining an interesting or appropriate one.

![Independent Study](../assets/week-04/design240(p20).png)
*The first visualisation generated by Gemini, which I did not accept as the final response.*

## Iterating Different Representations

Next, I asked Gemini to generate **three distinctly different representations of the same dataset** for the same dataset. In response, it produced several chart-based outputs, including pie charts, bar charts, heatmaps, and box plots. These charts were very useful because they highlighted different aspects of the data. For example, the pie chart makes it easy to compare proportions, the bar chart highlights the distribution across categories, the heat map clearly illustrates the relationship between regions and categories, and the box plot reveals differences in campground capacity.

These results are helpful because they demonstrate that the same dataset can be interpreted differently depending on how it is presented. Bar charts emphasize comparisons, while heatmaps highlight patterns and clusters. This reinforces a key point of this task: the way data is presented shifts the observer’s focus. The dataset itself remains unchanged, but the story it tells evolves depending on the presentation format.

However, I have also noticed that even when I request a different presentation style, Gemini’s outputs mostly remain confined to the logical framework of standard data charts. While these results are useful, they lack a sense of innovation. They are closer to traditional visual analytics than to experimental design outcomes.

![Independent Study](../assets/week-04/design240(p23).png)
*One of the alternative chart-based representations generated from the same dataset.*

![Independent Study](../assets/week-04/design240(p25).png)
*One of the alternative chart-based representations generated from the same dataset.*

![Independent Study](../assets/week-04/design240(p24).png)
*One of the alternative chart-based representations generated from the same dataset.*

## Redirecting the AI Beyond Standard Charts

Because the assignment encouraged formats beyond only charts, I then redirected Gemini by asking it to use broader representation types such as **code-based, textual, visual, and physical or analogue translations**. This changed the direction of the conversation. Instead of only returning charts, Gemini began describing possibilities such as an interactive map, a narrative or textual catalogue, and a physical installation or analogue translation.

This part of the process was quite enlightening, as it highlighted both the tool’s strengths and its limitations. On the one hand, artificial intelligence is invaluable for quickly generating ideas and transforming data into various conceptual forms; on the other hand, it cannot directly produce a complete document in the format I need. The tutorials and guidance it provides are often very basic, and the results it generates are closer to conceptual proposals than to final products. This means I have to constantly adjust how I use the tool and determine which ideas are truly useful.

One of the more interesting outcomes from this stage was the idea of representing the DOC campsite data through a physical or tactile translation. This moved the dataset away from the screen and suggested that information about accessibility, density, or facilities could be felt materially rather than only read as numbers. Even though this was not produced as a real object, it was valuable as a conceptual shift because it expanded the way I thought about what a dataset could become.

![Independent Study](../assets/week-04/design240(p26).png)
*An example of the Digital Representation direction suggested by Gemini.*

![Independent Study](../assets/week-04/design240(p28).png)
*An example of the analogue translation direction suggested by Gemini.*

## Critical Evaluation

This process made it much easier to critically evaluate how artificial intelligence behaves as a design tool.

### What did the AI default to?

By default, this AI system uses common data visualization charts to present datasets. While it generates a variety of charts to visualize data—which is certainly useful—the results tend to follow standard chart conventions rather than adopting more experimental designs or formats tailored to specific audiences. This suggests that when tasked with visualizing data, the tool tends to prioritize familiar analytical formats.

### What did I have to override or redirect?

I had to guide the AI to stop generating only standard charts. I also asked it to change the format and presentation style, as the initial results it generated were not what I had in mind. Specifically, I needed to guide it to adopt an approach based on code, text, and analogies, rather than simply accepting the initial chart-based output.

### What assumptions did the AI make about the data or the audience?

This AI appears to believe that datasets should primarily be understood through quantifiable categories, such as animals, numbers, regions, types of campsites, and other variables that can be clearly counted. It also seems to assume that the audience is seeking clear summaries rather than more imaginative or critical interpretations of the data. This means that its outputs are often informative but lack depth of thought and fail to reflect cultural context.

### Which representation was the most interesting, and why?

At this stage, the main outputs I actually received were still image-based visual representations. Out of the directions suggested by the artificial intelligence, I think a **website or interactive interface** would probably be the most interesting representation, because it could combine images, categories, and information together rather than only presenting isolated statistics. A web-based format could allow users to explore the data more actively and connect campsite information to place, access, and experience in a richer way.

### What would I do differently without AI?

If I weren’t using AI to build this project, I would first spend more time researching existing visual styles and data visualization methods, and then select the most appropriate one based on the dataset. Next, I would develop the visual style according to my own design intent, rather than simply adopting the AI’s default output. AI is very useful for speeding up the process and sparking creativity, but without it, I believe the entire process would be slower and more deliberate from the very beginning.

## Reflection

This independent study made me realize that while AI is very useful for **exploration**, it may not necessarily produce polished design outcomes without clear guidance. Gemini helped me quickly grasp the structure of the dataset and generated several possible presentation options, which saved time and made it easier for me to explore different directions. At the same time, its outputs tend to be rather general, so when I wanted more specific or unconventional content, I had to constantly refine its direction.

**Data Feminism** puts forward an important point: data is by no means neutral; the choice of visualization determines whose experiences are represented. This raises thought-provoking questions about my dataset. While the DOC campground data appears practical and objective, it still reflects institutional categorizations and priorities. The data records campgrounds as entries with quantifiable characteristics but fails to capture all the social, cultural, or environmental dimensions involved in camping, land use, or public access.

Kirikowhai Mikaere’s framing of data as a strategic asset for Māori development also shifts how I think about this dataset. Even when a dataset appears public and straightforward, it still exists within wider questions of ownership, stewardship, and benefit. A dataset about land, facilities, and movement across Aotearoa should not be treated as culturally neutral. It raises questions about whose relationships to land are being represented, whose values are prioritised, and who benefits from how this information is collected and used. This made me more aware that artificial intelligence-assisted analysis should not only focus on efficiency, but also on responsibility.

Overall, my experience using artificial intelligence as a design tool has been mixed but valuable. It was highly effective in quickly understanding CSV files, identifying patterns, and generating multiple starting points. However, when I wanted more refined, specific, or original design outcomes, its performance was less satisfactory. This process taught me that artificial intelligence works best when treated as an object that needs to be questioned, guided, and critiqued rather than simply obeyed. If I had more time, I would like to further develop one of the non-graphical displays, especially a website-based or interactive version, to connect the campsite data with a more exploratory user experience.

## Next Steps

The next step is to complete Experiment 4: Artificial Intelligence as an independent research project and finalize the Making Journal before submission. Based on the classroom activities from Week 4, I now have a deeper understanding of how local and cloud-based AI tools can support research, reflection, and making, as well as the ethical considerations that must be taken into account when using these tools. In addition, I have a clearer starting point for my Reflective Proposal, particularly regarding the themes and experiments that have proven most meaningful in my Making Journal so far.

