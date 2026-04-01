---
layout: default
---

# Week 02

[← Back to Home](../index.md)


# Week 2 – Interactivity

## Overview

This week’s class shifted from hand-drawn data portraits to interactivity. We were introduced to **Experiment 2: Interactivity**, which asked us to consider how to explore, control, or manipulate data, rather than simply viewing it as a static image. We also began learning the basics of p5.js, including how sketches run in a browser, how to use coordinates to draw shapes, and how to connect interactive controls—such as buttons, sliders, and text input fields—to sketches. The overall focus this week was a shift from physical and handmade forms of data visualization to digital interactivity.

## In-Class Activity – Pair Exchange

At the start of the class, we revisited the individual data profiles we had completed in Week 1 through a pair-work activity. Working in pairs, we shared the content we had recorded, our data collection methods, the phenomena we observed, and the choices we made in our visualizations. This session served as an effective transition from last week’s content, as it not only prompted me to present my work but also required me to articulate the reasoning behind it. At the same time, it helped me think more clearly about which aspects of the first-week project could be transformed into an interactive format.

While discussing this project with others, I realized that data portraits can be understood on multiple levels. These include the data itself, the visual system used to encode the data, and the viewer’s interpretation. This conversation gave me an initial understanding of interaction design—in which the viewer no longer merely reads the data but actively participates in the process of exploring it. The course slides also addressed interactivity from this perspective, describing how, in projects such as **Data Strings**, **Cairn**, and **Let's Play with Data**, the audience participates in the data experience rather than simply observing it.

## Learning p5.js Basics

A major part of Week 2 was learning the basic structure of a p5.js sketch. The slides introduced the **setup()** function, which runs once at the beginning of the program, and the **draw()** function, which runs continuously while the sketch is active. We also learned how p5.js uses coordinate space, with `(0, 0)` at the top-left corner, `x` increasing to the right, and `y` increasing downward. These ideas were important because they gave me a clearer sense of how visual elements are placed and updated on the canvas.

![Class Image](../assets/week-02/design240(p8).png)
*P5.JS Tutorial Website*

![Class Image](../assets/week-02/design240(p7).png)
*P5.JS Tutorial Website*

The class also introduced basic drawing commands such as `background()`, `fill()`, `strokeWeight()`, and `circle()`, along with the use of comments to explain what parts of the code are doing. At this stage, the coding process felt very direct: each line had a visible result, and changing values immediately affected the composition. This made the structure of the sketch feel more understandable than I had expected.

![Class Image](../assets/week-02/design240(p1).png)
*P5.JS Exercise*

## In-Class Experiment – Simple Shape Composition

One of the classroom assignments was to create a simple composition using at least three different shapes, experimenting with color, size, position, and the order of the commands. My piece featured a black background with a green rectangle spanning the lower half of the canvas, behind which a yellow circle was partially hidden, creating a minimalist, landscape-like image. Although this sketch was very simple, it was helpful because it demonstrated how the principle of layering works in code. The order of instructions is crucial: drawing the circle before the rectangle would obscure the lower half of the circle, creating a sunrise or sunset effect. This made me realize that programming involves not only technical skills but also the art of composition.

This exercise also boosted my confidence in basic syntax. Writing these short sketches made it easier for me to understand how visual effects are built step by step. I no longer view code as an abstract concept, but rather as a way to construct images through sequence and logic.

![Class Image](../assets/week-02/design240(p1).png)
*P5.JS Exercise*

## DOM Elements and Interactivity

After completing the basic drawing exercises, the course moved on to an explanation of interactive controls. The class introduced DOM elements—web components that p5.js can create and connect to sketches, including buttons, sliders, and text input fields. I learned that these elements serve as digital representations of physical interactions, such as moving lines, placing markers, or rearranging objects. This provided a useful conceptual bridge to the examples of interactivity explored in the first half of the course through public data and physical data projects.

I found this section particularly important because it clarified what constitutes a truly interactive sketch, as opposed to mere animation effects. Interactivity is not only reflected in on-screen movement but also in giving the audience control over the progression of events and what they observe. In this sense, the interactive interface itself has become an integral part of the work’s meaning.

## Vibe Coding and Exploration

In the latter half of the course, we were introduced to **vibe coding**, which the slides described as: describing requirements in natural language and using language models to generate code for building software. The focus isn’t on blindly copying the results, but rather on starting small, testing the output, reading the code, refining the prompts, and acquiring enough knowledge to guide the entire process.

This concept really resonated with me because it made programming feel much more accessible as part of a design workflow. I didn’t need to memorize every command in advance; instead, I could focus on describing a specific effect, testing it, and learning from the results. During this process, I experimented with sketches that were more visually ambitious than my earlier shape exercises. These included dynamic particle-like compositions, as well as a whimsical underwater scene filled with schools of fish, jellyfish, bubbles, and controls for day-night cycles. Although these experiments weren’t directly based on the food data I collected in my first week, they helped me understand how interaction, animation, and control work together in p5.js.

![Class Image](../assets/week-02/design240(p3).png)
*AI-generated dynamic programs*

![Class Image](../assets/week-02/design240(p2).png)
*AI-generated dynamic programs*

## Reflection on In-Class Activity

The dynamic relationship (interaction) between the work and the audience during the second week completely transformed my understanding of data visualization. In the first week, I focused on collecting personal data and developing a hand-drawn visual language. By the second week, I began to realize how audiences explore, filter, or influence what they see. This made the data experience less static and more participatory.

I also learned that simple programming exercises remain conceptually valuable. Although the basic combinations of shapes seemed very minimalist, they helped me understand layers, sequencing, coordinates, and the relationship between code and visual form. The more challenging generative sketching experiments that followed made me realize that p5.js can support both structured interactions and more expressive outcomes. These activities made the programming environment feel less intimidating and more like a design space.

Another key takeaway from this week is that interactivity doesn’t need to be complex to be meaningful. Even a small control element—such as a button, slider, or key—can alter the way viewers interpret an image or interact with information. This is particularly important as I move on to the next phase of transforming the data portraits from Week 1 into interactive sketches. This course has not only provided me with a technical starting point but also a conceptual framework for thinking about “why interactivity matters.”

## Making Journal and Website Setup

The final section of this week focuses on the technical setup of Making Journal as a static website. The slides explain the differences between dynamic and static websites, introduce Git and GitHub, and demonstrate how to use GitHub Pages to copy, clone, edit, and publish the journal template. Additionally, the section outlines the journal’s file structure, including the weekly Markdown files and the resources folder for storing images.

Although this section involves fewer visual experiments and focuses more on workflow, it remains crucial because it establishes how Making Journal should function as a record of the design process. I’ve come to realize that documentation is inseparable from the project itself. The way I organize files, edit Markdown, add images, and push updates to GitHub is just as much a part of the overall design practice.

## Independent Study – Interactive Data Portrait

For my independent research project in Week 2, I transformed the hand-drawn data portrait I created in Week 1 into an interactive p5.js program. My original data portrait documented the colors of the foods I ate at every meal that week, organized by date and meal type. I chose to continue working with this dataset because it has a clear structure, including categories such as weekdays, breakfast/lunch/dinner, and color. This makes it ideal for interactive design, as viewers can focus on different aspects of the data through filtering and comparison.

I did not attempt to replicate every visual detail of the hand-drawn version, but instead focused on the elements that work best in a digital environment. In this sketch, the seven days of the week are arranged horizontally across the screen, while meal types are listed in rows. The color of each food item is represented by a colored circle, allowing viewers to quickly compare color patterns throughout the week. This design maintains consistency with the logic of the original portrait while simplifying the structure to make the interaction clear and user-friendly.

![Independent Study](../assets/week-02/design240(p4).png)
*P5.JS - Data Portrait*

## Designing the Interactive Elements

The primary goal of the interactive version is to allow viewers to actively explore the dataset, rather than simply viewing it as a static image. To achieve this, I utilized multiple DOM elements in p5.js and incorporated control types introduced in class, such as dropdown menus, checkboxes, and buttons. The program includes a dropdown menu for selecting a specific date, checkboxes to show or hide breakfast, lunch, and dinner, and a reset button to restore the full view. I also added a color filter so that viewers can focus on a single color at a time. These design choices closely follow the structure of the data, making the interaction feel purposeful rather than merely decorative.

This experience made me realize that interaction design works best when it aligns with the data’s logic. Including a date filter makes sense because my data was collected over time; similarly, including a meal filter makes sense because breakfast, lunch, and dinner form clear subcategories. The color filter provides a deeper dimension for exploration, allowing viewers to more easily spot recurring patterns and outliers in the data. Unlike presenting the entire dataset at once, this design enables viewers to explore the data in smaller, more focused chunks.

## What Interaction Adds

One of the key differences between hand-drawn portraits and interactive sketches is that the interactive version allows viewers to ask specific questions about the data. In the original artwork, while the overall picture for the entire week is immediately apparent, it is more difficult to identify patterns within it. In the digital sketch, viewers can quickly compare data from a single day, a specific meal category, or a particular color. This brings certain details into sharper focus, such as which colors recur frequently and which are relatively rare. It also transforms the relationship between the viewer and the visualization, as viewers are no longer passive recipients of images but actively shape what is visible. This reflects the broader concept of interactivity discussed in class, where engagement is viewed as an integral part of the work’s meaning.

For example, in my reflection from the first week, I noted that yellow and green appeared more frequently than expected, while purple appeared only occasionally. In the interactive version, this observation is easier to verify visually, as color filters can isolate a single color and display its distribution throughout the week. This makes the sketch more exploratory than the original sketch, which relied more on overall impressions and careful manual interpretation.

## Coding Process and Vibe Coding

I used a language model to assist me during the coding process, which echoed the discussion about “vibe coding” from the second week’s class. Rather than trying to write the entire program draft from memory, I described the kind of interaction I wanted and used the generated code as a starting point. I then pasted the generated code into the p5.js editor to test and refine it step by step. This process made me realize that “vibe coding” is most valuable when viewed as a dialogue rather than a shortcut. The key lies not only in getting the code to run, but also in reading the code, identifying the function of each part, and deciding which parts to keep and which to modify.

Through this process, I gained a deeper understanding of how p5.js is used to build interactive projects. I became more familiar with the object arrays used to store data, grasped the difference between `setup()` and `draw()`, and learned how to link DOM elements with filtering logic. I also learned that when building interactive sketches, an incremental development approach works best. Starting with a small, working system and then adding features one by one makes the project much easier to manage.

![Independent Study](../assets/week-02/design240(p6).png)
*P5.JS - Data Portrait*

## Reflection on Independent Study

This independent research helped me understand how the presentation of data changes when it is transformed from paper into code. My hand-drawn version is more expressive and personal, while the interactive version is more exploratory and analytical. The hand-drawn piece encourages a slow, contemplative reading experience, whereas the p5.js version allows viewers to directly manipulate the data and verify some initial observations. I believe these two approaches are not mutually exclusive, but rather highlight different strengths of the same dataset.

This project also made me more aware of the design decisions involved in the simplification process. In the hand-drawn portraits, I used background textures, shapes, and colors to create a richer visual language. In the interactive version, however, I reduced some of the complexity to ensure the interface remained legible and responsive. This means the digital version is clearer in some respects, but it also lacks some of the tactile quality and intimacy found in the original artwork. This trade-off is worth reflecting on, as it demonstrates that while interaction adds value in one area, it can diminish value in another.

This exercise also deepened the connection between my personal creative practice and the principles of data humanism. Although the sketch is digital, the data still stems from subtle observations of everyday life. The project retains its personal character because it is based on my own dietary habits and began with manually collected data and hand-drawn portraits. Transforming it into an interactive sketch has not diminished this personal quality; rather, it offers another way to engage with the same life experiences.

## What I Would Develop Further

If I had more time, I would refine this design sketch further, optimize the visual design, and incorporate more nuanced interactive effects. For example, I’d like to add tooltips with more detailed meal information, make the animation transitions between filter states smoother, and perhaps include an overview view showing which colors are most common overall. I’d also like to explore whether certain visual elements from the original hand-drawn portraits—such as textures or patterns—can be digitally reincorporated into the design without making the interface look cluttered.

Overall, this project helped me shift from static presentation to interactive exploration. It made me realize that interactivity isn’t just about adding dynamic effects or control elements; it’s about designing ways for users to discover connections within the data that might otherwise remain hidden.

## Next Steps

My next step is to create a more interactive sketch based on the data from the first week. This week’s classroom activities have given me a solid foundation, allowing me to master the basic structure of p5.js, its coordinate system, graphic rendering, and interactive controls. Moving forward, I will shift my focus away from general visual experiments and instead concentrate on how to use interactive design to enable viewers to explore the food color data in ways that the hand-drawn original cannot achieve.