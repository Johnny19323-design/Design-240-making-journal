---
layout: default
---

# Week 3 – Live Data

[← Back to Home](../index.md)

## Overview

This week introduced live data as the next stage in designing with data. The class began with a short review of interactive data portraits and a check-in on the Making Journal, then shifted into **Experiment 3: Live Data**. The main focus was learning how to retrieve live information from the internet using the command line and APIs, and then thinking about how those data streams could be visualised in p5.js. The second half of the class broadened this discussion by connecting live and procedural systems to ideas from generative art and conditional design.

## Interactive Data Portraits and Pair Exchange

At the start of the class, we reviewed the interactive data portraits we created in Week 2. Working in pairs, we shared our p5.js sketches and discussed what insights or experiences viewers might gain by interacting with them. We also reflected on whether we had used Vibe Coding or other tools, and what we would have developed further if we’d had more time. This session was very helpful; it allowed me to evaluate my Week 2 work more critically and think about how interaction changes the audience’s relationship with data.

This opening session also made me realize that Making Journal is not just about documenting outcomes, but also about tracing the evolution of the experiment. The slides repeatedly emphasized that excellent journal entries require a clear balance between visual elements and text, focusing on both the process and learning while maintaining consistent Markdown formatting and properly setting up the journal via GitHub Pages.

## Making Journal Check-In

Another part of the class focused on checking the technical setup of the Making Journal. The slides outlined the expected workflow: writing entries in Visual Studio Code, storing media inside the matching `assets/week-XX/` folders, committing changes in GitHub Desktop, and pushing them so the GitHub Pages site updates automatically. The file structure was also reviewed, including the weekly Markdown files and the correct relative path for embedding images.

This was helpful because it made the journal feel less like a loose collection of files and more like a structured design system. It also reminded me that technical organisation is part of the assignment quality. The site itself is part of the design outcome, not just a container for text and images.

## Experiment 3 – Live Data

The main new concept this week was **live data**. The class looked at practitioner examples such as Natalie Jeremijenko’s *Dangling String*, which made internet traffic visible through movement, and David Bowen’s *Tele-Present Wind*, which used live wind data from Mars to drive a physical installation on Earth. We also looked at *Listening Post* by Mark Hansen and Ben Rubin, which visualised fragments of online conversations on multiple displays. These examples showed that live data does not need to be presented as a conventional chart. It can become motion, sound, or a constantly changing environment that draws attention in different ways.

What interested me most in these examples was the idea that data can be encountered indirectly. Instead of reading a graph, a viewer might feel data through motion, repetition, fragmentation, or atmosphere. This made live data feel less like a technical category and more like a design material.

## Learning the Command Line

To get us started working with real-time data, the course introduced the command line—a text-based way of interacting with a computer. The slides explained that instead of clicking through menus and web pages, we can simply type commands to browse folders, create files, run programs, and retrieve data from the internet. The course introduced commands for navigating folders, such as `pwd`, `ls`, and `cd`, and demonstrated a simple example of creating a file using `echo “Hello” > hello.txt`.

I practiced these steps in the terminal by navigating from the home directory to the desktop, creating a text file, and then checking to see if the file had been generated. Although this was a simple task, it made me realize that the terminal isn’t just for programmers; it’s also an interface for directly managing files and retrieving information in plain text.

![Class Image](../assets/week-03/design240(p1).png)
*Class activity - Creating a text file in the terminal using `echo "Hello" > hello.txt`.*

![Class Image](../assets/week-03/design240(p2).png)
*Class activity - Listing Desktop contents in the terminal using `ls`.*

![Class Image](../assets/week-03/design240(p3).png)
*Class activity - Listing Desktop contents*

## Retrieving Data with curl

After mastering basic terminal operations, the course shifted its focus to using `curl` to retrieve real-time data. The course materials describe `curl` as a command-line tool used to transfer data over the internet. Unlike opening a webpage in a browser and reading information through menus and visual interface elements, `curl` returns the raw response directly. The class demonstrated ASCII art, weather reports from `wttr.in`, and JSON data from a dictionary API.

I tried using `curl` to request the definition of the word “design” from the Free Dictionary API to practice this process. The terminal returned a large chunk of JSON code. While it wasn’t particularly easy to read as plain text, it clearly demonstrated the structure of the data. This was a pivotal moment for me, as it highlighted the difference between reading information as a user and retrieving data as design material. I no longer saw just the final webpage; instead, I saw the raw information that could later be parsed, filtered, and visualized.

![Class Image](../assets/week-03/design240(p7).png)
*Using `curl` to retrieve raw JSON data for the word “design” from the dictionary API.*

## APIs and Weather Data in p5.js

The next step was to connect live data to p5.js. The slides introduced the idea of an **Application Programming Interface**, explaining that an API is a structured way for programs to communicate and exchange data. The class used the Open-Meteo API as an example because it is free, open source, does not require an account, and returns JSON weather data. In p5.js, this data can be loaded with `loadJSON()`, stored in an object, and then accessed through dot notation such as `weather.current.temperature_2m`. 

This section helped me understand how the various components are connected. First, a request is sent to a specific URL. Then, the JSON data is loaded into the sketch. Afterward, specific values such as temperature, wind speed, and humidity can be extracted and mapped to visualization properties. The course slides suggest mapping temperature to the size of an ellipse, wind speed to line thickness, and humidity to background color. Additionally, the course emphasizes that you should first check the values using the `print()` function in the console before attempting any visualization.

## In-Class Activity – Weather API Sketch

I applied this process in p5.js to create a simple weather sketch using Auckland weather data from the Open-Meteo API. In my sketch, humidity controls the blue background, temperature affects the size of a large white circle, and wind speed affects the width of the red rectangle at the bottom of the canvas. The console displays the values in real time, which helps me verify that the data is loading correctly before mapping it to the layout.

Although this small program is visually simple, it helped me understand the logic behind real-time data visualization. It no longer involves manually setting values, but rather responding to values from an external source. This changes the role of drawing—it is no longer just composing a static image, but designing a system capable of responding to constantly changing information.

![Class Image](../assets/week-03/design240(p8).png)
*p5.js - weather sketch using live Open-Meteo data for temperature, wind speed, and humidity.*

## Reflection on Digital Live Data

The biggest takeaway for me this week was the shift from manually collecting data to using real-time data from external sources. In Weeks 1 and 2, I worked with data I had collected myself and converted it into static or interactive formats. By Week 3, the data was no longer entirely under my control. It came from sources outside my daily life and was presented in a structured yet constantly evolving format. This made the process more technical, but it also opened up new possibilities for responsiveness and real-time adaptation.

Working with real-time data has also made me more aware of the importance of structure. The raw JSON data returned by an API cannot be immediately visualized or directly interpreted. It requires parsing, validation, and careful mapping before it can be transformed into a visual format. This has made me realize that even when the source data is real-time and comes from external sources, visualizations are always shaped by design choices.

## Analogue Tools, Generative Art, and Conditional Design

The latter half of the course expands the scope of discussion beyond digital APIs by introducing generative art and conditional design. The slides cite Philip Galanter’s definition of generative art as an artistic practice in which the artist cedes partial control to a system with functional autonomy. Examples range from ancient pattern-making to pseudocode systems, Sol LeWitt’s wall drawings, and the concept of “conditional design,” which emphasizes controlled processes, chance, logic, time, relationships, and change.

This part of the lecture was significant because it connected real-time data sketching to broader design thinking. Real-time data sketching is not merely a technical exercise; it is a system that generates results over time. This means it can be considered on par with generative and process-oriented practices. I found this insight useful because it shifted my perspective away from viewing “coding” as a standalone technical skill and toward a focus on process design: setting conditions, defining relationships, and allowing outcomes to emerge naturally.

## Process Documentation

I also documented parts of the process using screenshots and videos. The screenshots include terminal commands, raw API responses, and the p5.js weather program. The videos serve both to track the program’s progress over time and to showcase dynamic behaviors that are difficult to capture in static images. This approach is particularly well-suited for Week 3, as real-time data involves changes and duration to some extent, and videos are more effective than individual screenshots at conveying these characteristics.

## Independent Study – Live Data Visualisation

For the Week 3 independent study, I chose a **digital approach** and created a p5.js sketch that responds to live earthquake data. I wanted to continue the ideas from class about APIs and live data, but instead of repeating the weather example from the lecture, I looked for a different data source that was still public, structured, and suitable for visualisation. I decided to use the **USGS Earthquake Catalog API** because it provides earthquake event data in GeoJSON format and allows the query to be customised through parameters. This made it a good source for experimentation, because I could control the time range, the minimum magnitude, and the order of the results while still working with an external live dataset. ([earthquake.usgs.gov](https://earthquake.usgs.gov/fdsnws/event/1/))

To access the data, I first looked through the official USGS Earthquake Catalog API documentation and used the query structure shown there to build my own URL. I chose the `query` method because it returns the earthquake events themselves rather than only a count. I used `format=geojson` so the data would come back as structured geographic JSON, then added `starttime=2026-03-23`, `minmagnitude=5`, and `orderby=time`. This meant the sketch would use recent earthquake events above magnitude 5 and display the newest ones first. What I found useful about this process was that it made the API feel less like a single fixed link and more like a flexible system that could be shaped through different parameters. ([earthquake.usgs.gov](https://earthquake.usgs.gov/fdsnws/event/1/))

*API:https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&starttime=2026-03-23&minmagnitude=5&orderby=time*

### Accessing and Understanding the Data

Before visualizing data in p5.js, I first needed to understand the structure of the response data. The GeoJSON result contains an `features` array, and each earthquake event includes `properties` and `geometry`. Based on this structure, I focused on several key values: magnitude, location, time, longitude, latitude, and depth. This is closely related to the lecture on JSON and point notation from Week 3, where we learned that before visualizing data on a map, we must access the data step by step through its nested structure.

During the course, I also used the command line and `curl` to gain a more intuitive understanding of how API requests work. In class, we learned that `curl` can retrieve raw data directly from the internet without relying on a web interface, which helped me view APIs as data rather than ordinary websites. Although the final visualization was implemented using `loadJSON()` in p5.js, the command-line phase played a crucial role in testing and understanding that APIs actually return structured, machine-readable data rather than pre-designed web pages.

![Independent Study](../assets/week-03/design240(p11).png)
*Terminal - Testing and understanding the earthquake API response before building the visualisation.*

### Mapping Data to Visual Form

In this sketch, I have transformed earthquake data into a visualization system based on spatial location, scale, and color. I use **longitude and latitude** to plot each earthquake on the canvas, allowing the image to reflect the global distribution of seismic events. I use **magnitude** to control the size of the circles, making earthquakes with higher magnitudes stand out more prominently. Additionally, I use **depth** to influence the color, allowing the image to distinguish between shallow-focus and deep-focus earthquakes.

This mapping makes the data easier to compare visually. In the raw JSON format, viewers can only make sense of the data by carefully sifting through lengthy lists of numbers. In the sketch, however, the information takes on a spatial quality and becomes immediately apparent. People can instantly perceive data clusters, relative strengths, and general geographic distributions. In this sense, visualization is more than just displaying numbers. It gives data a form and rhythm that can be interpreted quickly and intuitively.

### Iteration and Refinement

Although the first draft I created was technically sound, it appeared too abstract visually. The earthquake epicenters were depicted as scattered glowing circles against a dark background; while the data was loaded correctly, the visualization failed to provide sufficient structure for interpretation. Without reference lines or labels, the image resembled a cloud of floating particles rather than a clear visualization of the earthquake.

Because of that, I refined the sketch by adding a **grid**, clearer **longitude and latitude reference markers**, a more explicit **title**, and a simple **legend** explaining the visual mapping. I also adjusted the colour treatment and hierarchy so the image felt more deliberate and easier to read. This second version was much more effective because it gave the viewer a framework for understanding what they were seeing. It also made the work feel closer to a data visualisation rather than an abstract generative composition.

![Independent Study](../assets/week-03/design240(p12).png)
*[P5.JS - Early version of the earthquake sketch, showing the basic mapping of position, size, and colour.](https://editor.p5js.org/Johnny19323-design/sketches/ITqemwCTy)*

![Independent Study](../assets/week-03/design240(p13).png)
*[P5.JS - Refined version with grid lines, clearer title, and a legend to improve readability.](https://editor.p5js.org/Johnny19323-design/sketches/4cy1WTCDU)*

### What the Work Reveals

This study provides the most intuitive representation of the **distribution and intensity** of recent major earthquakes. These points are not randomly distributed; their locations reflect the regions where seismic activity occurs, while the size of the circles facilitates comparison of seismic events of varying intensities. The visual contrast created by the colors offers a dimension of information that is difficult to perceive through numerical data alone.

This project also highlights another point: real-time data visualization is not merely about displaying the latest figures. In this case, the API query constructs a dynamic time window reflecting recent seismic activity, meaning the image is linked to an actively running external system rather than based on a static dataset. Even though the sketch does not update every second like a sensor data stream, it still responds to a real-time, ever-changing data source that returns different results at different times. This gives the work a provisional and open-ended feel, rather than a final, fixed one.

### Process and Tools

I wrote this program using p5.js and imported the earthquake data into the program using the `loadJSON()` function. The p5.js reference documentation and tutorials were extremely helpful in checking the syntax and understanding the program’s structure. While coding, I also used the console to inspect data values, following the exact same process we used when practicing the weather API example in class. This step was crucial because it helped me first understand the scale and scope of the data before deciding how to visualize it.

Throughout this process, I also relied on language models for assistance. This helped me organize the code structure, parse the GeoJSON response, and determine how to link earthquake attributes with visual features. The most valuable part of this workflow lies not only in generating code, but also in testing it, identifying visual issues, and optimizing the results. This process made me realize that even with the assistance of large language models (LLMs), designers still need to make critical decisions regarding clarity, hierarchy, and meaning.

### Relation to Practitioner Examples

This project connects well to the practitioner examples from class. It relates to **David Bowen’s** *Tele-Present Wind* because both works take external live data and translate it into a visual or material system rather than simply presenting a text readout. It also connects to **Natalie Jeremijenko’s** *Dangling String* in the sense that the data becomes something to perceive rather than something only to read. At another level, the project also relates to ideas from **generative art** and **conditional design**, because the final image is produced by a system of rules: incoming data is filtered, variables are mapped to visual properties, and the final composition emerges from that logic rather than being manually arranged point by point.

### Reflection

This independent research project has taught me that real-time data visualization relies not only on technical access but also on design interpretation. Searching for APIs, reading documentation, writing query statements, and loading JSON files are all part of the design process. I must first understand the structure of the data source before I can decide how to visualize it. This made this week’s exploration more investigative than my previous experiments, because I wasn’t just creating visuals; I was also learning how to access and organize the data itself.

I also realized that technical success does not necessarily equate to visual success. Although my first version was fully functional, the presentation did not achieve the level of readability I had hoped for. As I refined the prototype, I came to understand that real-time data still requires careful composition, hierarchical planning, and visual interpretation. Data alone does not automatically produce excellent visualizations. Design decisions are the key to effectively conveying information.

At the same time, this project changed my perspective on data as a material. In the preceding weeks, I had been working with datasets I had collected myself—ones with a more personal character. In this project, however, I was dealing with an external system that was larger, more unstable, and beyond my control. This created a closer connection between the sketches and the world outside the studio, which I found fascinating. It also made me more acutely aware that real-time data possesses both informational value and inherent uncertainty.

### What I Would Develop Further

If I had more time, I would like to refine this design sketch by adding more advanced exploration features, such as hover labels with clearer typography, filters for magnitude ranges or date ranges, and perhaps even an animation to show how events change over time, rather than displaying everything at once. I’d also like to experiment with a background that more closely resembles a map or a more atmospheric visual style, striking a balance between clarity and expressiveness.

Overall, this project has broadened my understanding of real-time data—it can not only be accessed, filtered, and interpreted, but also transformed into a dynamic visual system. It has made me realize that design based on real-time data is not just about receiving information, but also about deciding how that information should be presented and given meaning.

## Next Steps

My next step is to explore how to make real-time data more visually expressive. While my current weather sketch works as a proof of concept, its presentation remains somewhat straightforward and literal. If I had more time, I would like to experiment with more expressive mapping techniques, more dynamic visual effects, or richer visual feedback. Additionally, I am quite interested in the relationship between real-time data and generative systems, particularly how to combine external information with randomness, noise, or procedural rules to create a presentation that no longer resembles a chart but rather an ever-evolving visual environment.
