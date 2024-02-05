| [Home page](https://xujinyun.github.io/MyDataStory/) | [Visualizing government debt](visualizing-government-debt) | [Critique by design](critique-by-design) | [Final project I](final-project-part-one) | [Final project II](final-project-part-two) | [Final project III](final-project-part-three) |


# General government debt from [website](https://data.oecd.org/chart/7kaf) example
This is the visualization from The Organization for Economic Co-operation and Development (OECD). The website has not only intesresting data but also cool visualization. In this example, I choose general government debt data in 2022 around the world suing bar chart.

<iframe src="https://data.oecd.org/chart/7kaf" width="989" height="742" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7kaf" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2022</a></iframe>

# General government debt from [Tableau](https://public.tableau.com/views/Book1_17061572866280/Sheet1?:language=zh-CN&publish=yes&:display_count=n&:origin=viz_share_link)

This is the visualization from the Tableau tutorial. World's government debt data is listed in the table from 1995 to 2022. Ratio higher than 100 is specially marked with orange color. We can view the whole history easily.

<div class='tableauPlaceholder' id='viz1706547674108' style='position: relative'><noscript><a href='#'><img alt='World Debt-to-GDP Ratio History ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17061572866280&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book1_17061572866280&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17061572866280&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>       

<script type='text/javascript'>                    
    var divElement = document.getElementById('viz1706547674108');                    
    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
    var scriptElement = document.createElement('script');                    
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>



# My [Tableau](https://public.tableau.com/views/Book2_17065473969110/Sheet1?:language=zh-CN&publish=yes&:display_count=n&:origin=viz_share_link) design of government debt

This is the visualization of the same set of data from my Tableau design. Unlike the previous example, I aim to depict the changing trend in this chart. Initially, I opted for an area chart and found it visually appealing. However, it is more effective to showcase the sum rather than displaying the attributes of each year. Consequently, I switched to a bar chart with no edge border to emphasize the trend. I did not select the line chart because I couldn't utilize color to highlight high values. Therefore, the bar chart with color became my final choice.

I appreciate the blue-orange color scheme, as it makes logical sense to me. Just for experimentation, I decided to explore other combinations and chose a blue-red color scheme this time.

<div class='tableauPlaceholder' id='viz1706547409855' style='position: relative'><noscript><a href='#'><img alt='World Debt-to-GDP Ratio Trend ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book2_17065473969110&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Book2_17065473969110&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book2_17065473969110&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                

<script type='text/javascript'>                    
    var divElement = document.getElementById('viz1706547409855');                    
    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
    var scriptElement = document.createElement('script');                    
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>