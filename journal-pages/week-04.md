---
layout: default
---

# Week 4 – Artificial Intelligence

[← Back to Home](../index.md)

## Overview

Week 4 marked a shift in the course from working with real-time data to a more critical and practical exploration of artificial intelligence as a design tool. The session began with a brief review of real-time data visualization and an update on the progress of Making Journal, followed by **Experiment 4: Artificial Intelligence**. This segment covered discussions on ambient coding, ethical issues surrounding AI, data sovereignty, local AI tools (such as Ollama), and cloud-based tools (such as NotebookLM), and concluded with the drafting of reflective proposals for the next phase of the course.

## In-Class Activity – Live Data Review and Progress Check

The class opened by revisiting **Experiment 3: Live Data**. In pairs, we were asked to share our live data visualisation, or our plan if it was still unfinished, and discuss how we made it, what live data source we used, what the work revealed, and what we would develop further with more time. This was a useful way to close the previous experiment because it encouraged me to explain my technical process and reflect on the design decisions behind the work. It also reminded me that each weekly experiment is not only about making something, but about documenting it clearly enough that another person can understand the thinking behind it. :contentReference[oaicite:2]{index=2}

The class then moved into a broader progress check on the Making Journal. The slides emphasised that by this point the journal should include the in-class and independent study work for Experiments 1, 2, and 3, and that technical details such as file structure, asset folders, consistent Markdown formatting, and correct publishing through GitHub Pages also mattered. This reinforced the idea that documentation is itself a design practice rather than something added at the end. :contentReference[oaicite:3]{index=3}

## In-Class Activity – Vibe Coding and Artificial Intelligence in Design

After the progress check, the class introduced **Experiment 4: Artificial Intelligence**. One of the main ideas presented was **vibe coding**, described in the slides as building software by describing what you want in natural language and using a large language model to generate code. The slides also stressed good practice fundamentals, including describing the task clearly, reading the returned code, testing it, refining the prompt, and starting with a small feature before adding more. This framing was useful because it positioned artificial intelligence not as an all-knowing replacement for making, but as a conversational and iterative tool that still requires judgment and direction from the designer. :contentReference[oaicite:4]{index=4}

This was followed by broader questions about how artificial intelligence might change design practice and what concerns it raises. The lecture introduced distinctions between agentive artificial intelligence and generative artificial intelligence, and connected this to future skills such as artificial intelligence literacy, creative thinking, resilience, curiosity, and analytical thinking. These ideas made the discussion feel larger than just software or convenience. Artificial intelligence was presented as something that changes how designers work, what kinds of skills matter, and what responsibilities come with using these tools. :contentReference[oaicite:5]{index=5}

## In-Class Activity – Ethics, Labour, and Data Sovereignty

A major part of the class focused on the ethical dimensions of artificial intelligence. The lecture used Trevor Paglen’s *From ‘Apple’ to ‘Anomaly’* to show how systems such as ImageNet rely on large-scale classification practices that include problematic and biased labels, as well as significant hidden labour from poorly paid workers. This made the issue of artificial intelligence feel less abstract and more material, because it connected machine learning to both human labour and the politics of categorisation. :contentReference[oaicite:6]{index=6}

The slides then moved into **ethical use of artificial intelligence in design**, including concerns about consent, the reuse of creative work in training datasets, and the importance of prompting with one’s own imagery or data rather than borrowing the names or styles of artists. These points were linked to a wider idea of responsibility: using generative tools is not neutral, and design decisions about prompts, tools, and data sources have ethical consequences. :contentReference[oaicite:7]{index=7}

This discussion expanded further through **data sovereignty** and **Māori data sovereignty**, which raised questions about who controls data, where it is stored, who can access it, and under which legal and cultural frameworks it is governed. This was especially important because it shifted the conversation away from artificial intelligence as just a creative shortcut and toward artificial intelligence as a system embedded within ownership, governance, and power. The examples from the slides encouraged me to think more critically about where data comes from and who has authority over it. :contentReference[oaicite:8]{index=8}

## In-Class Activity – Local Artificial Intelligence with Ollama

The class then moved into **local artificial intelligence**, beginning with Ollama. The slides described Ollama as a free, open-source tool that lets users run artificial intelligence models on their own computers, without an account or cloud processing, keeping prompts and outputs on the local device. At the same time, the slides also noted that the models that can run locally on a personal computer are less capable than large cloud-based systems. :contentReference[oaicite:9]{index=9}

Following the in-class instructions, I went through the process of downloading Ollama, installing it, and preparing it for use in the terminal. The slides outlined the workflow clearly: download Ollama, open the terminal, pull a model such as `qwen3:1.7b`, and then run it locally. I worked through this process and was able to see how local artificial intelligence differs from web-based tools. Instead of opening a browser and logging into a cloud service, the interaction happened more directly through software installed on my own computer. :contentReference[oaicite:10]{index=10}

![Insert image here](your-image-path-here)

*Figure X. Downloading Ollama and preparing the local artificial intelligence workflow.*

After installation, I used the local model and experimented with asking it questions. One of the things I tested was asking the model about model lists and installed versions, which helped me understand that local tools feel more technical and less polished than cloud tools, but they also make the infrastructure of artificial intelligence more visible. Rather than interacting with an invisible remote service, I was interacting with a model that was explicitly running on my own device. This made the relationship between software, hardware, and capability much more concrete.

![Insert image here](your-image-path-here)

*Figure X. Early interaction with a local model through the terminal and local artificial intelligence interface.*

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