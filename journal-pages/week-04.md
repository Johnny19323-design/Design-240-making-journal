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

After installation, I used the local model and experimented with asking it questions. One of the things I tested was asking the model about model lists and installed versions, which helped me understand that local tools feel more technical and less polished than cloud tools, but they also make the infrastructure of artificial intelligence more visible. Rather than interacting with an invisible remote service, I was interacting with a model that was explicitly running on my own device. This made the relationship between software, hardware, and capability much more concrete.

![Class Image]()
*Early interaction with a local model through the terminal and local artificial intelligence interface.*

## In-Class Activity – Experimenting with Local Model Output

The next part of the activity was to spend time chatting with the local model and testing its limits. The slides suggested asking it to describe previous experiment data, write a short p5.js sketch, or answer something one might normally ask ChatGPT, then comparing the quality of the response. :contentReference[oaicite:11]{index=11}

I used the local model to generate a simple website example. I typed a natural language request asking it to write code about a website, and it returned a basic HTML, Cascading Style Sheets, and JavaScript structure. I then copied this into a local file and opened it in the browser to test the result. This was a useful demonstration of vibe coding in practice. It showed that the model could produce something functional from a broad prompt, but it also made clear that the designer still needs to test, interpret, and decide whether the output is actually appropriate. The generated result was usable, but also generic, which made me reflect on the difference between speed and originality. :contentReference[oaicite:12]{index=12}

![Insert image here](your-image-path-here)

*Figure X. Prompting a local model to generate simple website code.*

![Insert image here](your-image-path-here)

*Figure X. The generated website opened and tested in the browser.*

## In-Class Activity – Cloud Artificial Intelligence and NotebookLM

After working with local artificial intelligence, the class contrasted this with **cloud-based artificial intelligence**. The slides explained that tools such as ChatGPT, Copilot, and Gemini send prompts to remote servers, rely on internet connectivity, and use larger, more capable models, but also involve data leaving the user’s machine. The slides also compared university-supported tools and then introduced **NotebookLM** as a research tool that works by drawing on the sources users upload. It can synthesise across documents, websites, and media, and can generate outputs such as text summaries, tables, mind maps, and audio overviews. :contentReference[oaicite:13]{index=13}

In class, I built a NotebookLM notebook using my own course materials. The slides instructed us to upload sources representing our experimentation so far, mixing our Making Journal with other relevant material, then create a `context.md` file that frames the project by answering three questions: the experiment found most interesting, a recurring theme, and something not yet explored. I completed this process by creating the context file in Markdown, previewing it, and then uploading it into NotebookLM alongside my journal source. :contentReference[oaicite:14]{index=14}

![Insert image here](your-image-path-here)

*Figure X. Creating and previewing the `context.md` file used to frame the notebook.*

Once the notebook was set up, I used the NotebookLM chat to ask questions such as what the final design outcome might be if the sources were treated as documentation for a design project, and what the sources suggested I cared about. The responses were useful because they reflected recurring themes back to me, especially around personal data, digital workflow, and the shift from physical to digital processes. This exercise felt different from asking a general-purpose chatbot because the responses were grounded in the sources I had provided, making the conversation more focused and project-specific. :contentReference[oaicite:15]{index=15}

![Insert image here](your-image-path-here)

*Figure X. Building a NotebookLM notebook with journal-related sources.*

![Insert image here](your-image-path-here)

*Figure X. Asking source-based questions inside NotebookLM and reading the responses.*

## In-Class Activity – Reflective Proposal and Ideation

The final part of the class shifted toward the next assessment stage: the **Reflective Proposal**. The slides explained that this proposal marks the transition from broad experimentation toward a focused design direction, asking students to identify a thematic focus, data source, future scenario, and intended impact for a final data-driven visualisation project. They also emphasised that strong proposals need to be concise, feasible, and clearly connected to prior experiments and relevant ideas about data representation. :contentReference[oaicite:16]{index=16}

The class included an **ideation activity** and **pair interview** process, where we were encouraged to review our journal, identify the experiments that felt most meaningful, and begin articulating possible project directions. The use of NotebookLM and the context file fed well into this stage because it provided a different way to reflect on my own work. Rather than only looking back manually, I could also see how an artificial intelligence tool interpreted patterns across my experiments. This did not replace my own reflection, but it did help generate directions and questions that might support the proposal-writing stage. :contentReference[oaicite:17]{index=17}

## Reflection on In-Class Activities

Week 4 was one of the most conceptually broad weeks so far because it combined technical experimentation with ethical and critical questions. In earlier weeks, the focus had been more directly on making: drawing data, building interaction, and visualising live data. This week still involved making, but it also asked what kinds of systems artificial intelligence depends on, whose labour supports it, what happens to our data when using cloud systems, and how artificial intelligence might be used more responsibly in design. That made the week feel less like a tutorial on new tools and more like a wider reflection on what it means to work with these tools critically. :contentReference[oaicite:18]{index=18}

The contrast between **local** and **cloud** artificial intelligence was especially useful. Working with Ollama made artificial intelligence feel more limited but also more transparent, because I could see that the model was installed locally and that the process depended on my own hardware. NotebookLM, by contrast, felt more powerful and polished, especially because it could synthesise across multiple sources and return more structured reflections. Comparing these two approaches helped me understand that different artificial intelligence tools are not interchangeable. They differ in capability, workflow, privacy, and purpose. :contentReference[oaicite:19]{index=19}

Another important insight from this week was that artificial intelligence works best when used as part of a reflective process rather than as an automatic answer machine. The best moments in class came not from accepting the first output, but from testing, comparing, questioning, and situating the tools in relation to my own design process. This feels especially relevant as the course moves into the proposal stage, where the goal is no longer just to experiment broadly, but to identify a meaningful and feasible direction to carry forward.

## Next Steps

The next step is to complete **Experiment 4: Artificial Intelligence** as the independent study and then finalise the Making Journal before the hand-in. Based on the Week 4 class activities, I now have a stronger understanding of how local and cloud artificial intelligence tools can support research, reflection, and making, as well as the ethical questions that need to be considered when using them. I also have a clearer starting point for the Reflective Proposal, especially in relation to the themes and experiments that seem most meaningful in my journal so far. :contentReference[oaicite:20]{index=20}