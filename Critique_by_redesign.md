# Critique by Redesign

I chose to critique a chart by Our World in Data, which is the first visualization in an [article about the environmental impact of food production.](https://ourworldindata.org/environmental-impacts-of-food) Here's the image for reference:


![Original chart on agriculture's environmental impact by Our World in Data](/What-are-the-environmental-impacts-of-agriculture.png)


I chose this chart because my major policy interests are focused on food access, distribution, and agriculture. I'm particularly interested in sustainable food systems, and so I have been trying to learn about the current effects of agriculture on the environment. I came across this blog post and briefly skimmed it while working on a previous project analyzing nutrition versus environmental impact. I welcomed the opportunity to dig into it deeper. In this second review, I was a bit surprised to notice that a site devoted to data analysis writing created a visualization that was so unappealing, overwhelming and bit confusing, particularly since this is the FIRST visualization opening the blog post, giving an overview of the various topics to be covered further on. Though I felt the chart conveyed the information accurately, and used a pragmatic color scheme, the redundant and misaligned text detracts greatly from its effectiveness and the reader's ability to quickly understand the message.

The critique method was helpful in really nailing down what elements kept the chart from working well and helped me identify what changes I could make. I realized that the chart is confusing because it gives the impression that there is a x and y axis and that the bars are measures of different things in the same units of measurement. To break up the groups and show that they are not exactly comparable or in the same units, but instead represent different aspects of environmental impact, I initially thought that having different pie charts would work best. However, as I picked apart the different facts presented on the chart, I realized that if I chose to break down the different parts further into their components, the pie would quickly get confusing or overwhelming. 

Creating the wireframes helped me realize that I could convey the same data but way less text and in a less-overwhelming way, though my mocks ups were still not beautiful. The only advantage I could see between using pies vs bars was that the pies seemed to fit in a smaller space, but since space was not a limiting factor in this project, it didn’t hold much weight.

[My first wireframe, using pie charts.](https://share.balsamiq.com/c/hk1UAzmvSQYFMpNHzrtR1V.png)

[My second wireframe, dropping the pie charts for bars.](https://share.balsamiq.com/c/22qS4WFWuUjAtooYp7TGrN.png)

Getting a second opinion (testing the solution) was also helpful in confirming that pie charts wouldn’t do any better than bar charts just arranged differently. Getting user feedback also helped me figure out what text I DID need, and how I could reword some things for clarity. It also helped me realized that my chart could use a bit of beautification. Here are some specific quotes from the feedback I got that were helpful:
- “I’m not sure what is meant by land use? By humans? I don’t know what eutrophication is. Freshwater use and greenhouse gases make sense. Biodiversity I don’t understand at all. What does it mean?”
- Who do you think is the intended audience for this?: “The graphs are pretty simple, so probably the general public.”
- “I would change the Biodiversity label. It looks like it’s making biodiversity really good. Maybe call it ‘Global Mammal population’?”
- “It’s not very pretty but it gets the point across."
- "If the chart is meant to be read by people who are not native English speakers might be confused about which side represents agriculture.”
- “Pie charts don’t seem to do any better to explain that each category represents a portion of a total.”
-In response to the original chart: “The center justified text makes it hard to have to look all around at different alignments to figure out what goes with what.”

Once I was finally ready to make the final visualization, I poked around with Flourish and Datawrapper, but neither seemed to offer me the free flow options that I wanted, to break away from bounding axes and bars in a line. I also realized that I wouldn’t be able to easily/quickly do this in R or Python either. So I went to the site Canva.com which is similar to Adobe products in that it offers a blank canvas to create freely on. 

My redesigned visualization shows the same proportional data as the original chart, even with the same color scheme (which I thought worked well), but it is slimmed down significantly, removing more than half the text, allowing the reader to immediately see the point, which is that agriculture makes up the biggest piece of most aspects of environmental usage and pollution. I found the additional information available on the original chart, about the non-agriculture proportions, very interesting and was compelled to add it as well, but as I did, I could tell it was distracting and that there wasn’t really a good way to add it and also keep the redesign clean. Though I had even considered incorporating additional data from another chart in the blog post, I realized that it would just take away from the main point of the chart. 

I’m still honestly not happy with the aesthetics and feel it could be more interesting or more appealing in some visual ways, but I couldn’t figure out how to add beauty without detracting from the information. Perhaps I should have invested more time in picking a nicer font.


And finally...

# My Redesign
<div style="position: relative; width: 100%; height: 0; padding-top: 75.0000%;
 padding-bottom: 48px; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAEN0iSyHRU&#x2F;view?embed">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAEN0iSyHRU&#x2F;view?utm_content=DAEN0iSyHRU&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Agriculture's Substantial Environmental Impact</a> 
