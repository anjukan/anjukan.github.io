---
title: "Building in Scalabity - Exchange in Singapore"
layout: post
date: 2019-06-26 11:00
tag: 
- Feature Selection
- Building Data Genome Project
- Building and Urban Systems
- Sustainability
image: /assets/images/Singapore_1.jpg # use my singapore city skyline picture
headerImage: false
hidden: false # don't count this post in blog pagination
description: "Does your data-science technique actually scale across hundreds of buildings? The need for a open benchmarking dataset for buildings."
category: blog
author: anjukankathirgamanathan
externalLink: false
---
<div style="text-align: justify">


<p> The "Internet of Things" (IOT) revolution has led to a significant rise in the use of sensors in building and urban systems and increasing amounts of building 
data being collected. This data includes HVAC system data, thermal comfort and indoor air quality, power consumption, external weather and occupancy data. 
Given the particular challenges of the urban environment, for data-driven approaches and studies, the question arises of which features or variables are 
the most useful and relevant to the problem at hand. Feature selection is the process in machine learning and statistics of selecting a subset of relevant 
features for building an efficient and accurate predictive model. I had implemented this process for simulation data from a building in a conference paper that I am presenting at 
<a href="http://buildingsimulation2019.org/">IBPSA BS2019</a> in September (which you can read <a href="/assets/documents/C2.pdf">here</a>, although I will dedicate another 
blog to this topic) but I am interested in the scalability of these techniques given real buildings of varying types, climates, systems and operation. To help answer this, 
I spent two weeks last month on research exchange at the <a href="http://www.budslab.org/">Building and Urban Data Science (BUDS) lab</a> at the National University of Singapore. 
I was kindly hosted by Associate Professor Dr Clayton Miller who is the head of this research group. </p>

<p> Whilst the IoT revolution is ensuring that more data is being collected, that doesn't neccessarily mean that as a researcher there is easy accessibility 
to open-access and quality building data. I have been promised building data several times only for emails to then go unanswered. At scale, it is even harder 
to find datasets of real building data and this is an issue in the research community as researchers apply data-driven techniques in problems such as building 
energy prediction, classification and clustering, often on individual case studies. However, the scalability and validity of the results if applied to a 
large heterogenous data set is often questionable in these studies. Started by Dr Miller, the <a href="https://github.com/buds-lab/the-building-data-genome-project">
Building Data Genome Project</a> looks to provide an open-access benchmarking dataset of non-residential buildings to the research community. It currently features 
hourly whole building electrical meter data for one year for 507 buildings. I would like to extend this dataset to include further meter data including zonal temperature, 
detailed HVAC meter data and weather and occupancy data. This will allow me to test the feature assessment methodology I have developed for scalability and robustness. 
The Building Data Genome Project is open-access so anyone is welcome to add new datasets to it or use it for your own research or academic purposes. </p>

</div>

<div style="text-align: center">

<img src="/assets/images/Oldway.png" width="275" height="300" />
<img src="/assets/images/Newway.png" width="275" height="300" />
<em>The need for a benchmarking data set for non-residential building data analytics, Left: Current approach, Right: Recommended approach.</em> <a href="https://github.com/buds-lab/the-building-data-genome-project">[1]</a>

</div>

<div style="text-align: justify">

<p> The BUDS Lab is a scientific research group that leverages data sources from the built and urban environment to improve the energy efficiency and 
conservation, comfort, safety and satisfaction of humans. The projects that they are working on range from the SDE Learning Trail, a web application that 
collects thermal and environmental comfort assessments from occupants to '3for2' Buildings. a project which aims to achieve material, energy and space efficiency 
in buildings. The BUDS lab is based in SDE4, a net-zero energy building and in fact Singapore's first.
 A net-zero building is one that has zero net energy consumption, i.e. the total amount of energy used by the building on an annual basis is roughly equal to or less
 than the amount of renewable energy created on site. Highlights of my time at BUDS included the workshop on the first day centered around "Wild Ideas". Dr Prageeth 
 Jayathissa led the session with started with a short intro to Qigong, which derives from Chinese medicine, philosophy and martial arts, and is a system of 
 coordinated movements, breathing and meditation. I also spent time in the BEARS (Berkeley Education Alliance for Research in Singapore) Centre at the CREATE 
 tower. Thank you to Samy and Seshadhri who were great hosts at BEARS!</p>

</div>

<div style="text-align: center">

<img src="/assets/images/Singapore_3.jpg" width="400" height="400" />
<br>
<em>Dr Prageeth Jayathissa (original Sri-Lankan Kiwi at BUDS) leading a "Wild Ideas" workshop</em>

</div>

<div style="text-align: justify">

<p> The time in Singapore also let me explore some of the other ways Singapore has earned the title of "Asia's Greenest City". What's makes this more impressive is that 
the city manages to accomodate 5.6 million people on an island just larger in size than Auckland. Featuring a year around tropical climate, 
keeping people cool dominates the energy consumption of buildings. The Oasia hotel sticks out in the Singapore skyline, its green (or should I say red) facade consisting
of 21 species of creepers, plants and flowers creating a massive vertical garden. Sky gardens (an open-air atrium) allows cross-ventilation through the space,
 reducing the need for artificial cooling. Green roofs even made it onto public buses with a trial taking place when I was there. Advised by NUS, the "Garden on the Move" campaign is a 
 three-month study to test whether the greenery can reduce the air-conditioning loads of the buses and hence reduce fuel consumption. </p>

</div>
<div style="text-align: center">
<img src="/assets/images/Singapore_2.jpg" width="1040" height="780" />
<em>Oasia Hotel Downtown, Singapore</em>
</div>

<div style="text-align: justify">

<p> This exchange was financially supported by a Universitas-21 network travel grant (both UCD and NUS (and the University of Auckland as well in fact) are part of 
this global network of universities) and I am very grateful for this award. Although a short exchange, and having visited Singapore on short trips before (being a common 
transit stop from New Zealand), this experience was hugely rewarding and has opened up many news avenues of collaboration and further opportunities. The perspectives I 
gained on scalability and how this applies to my research gave me a lot to think about and I enjoyed the chance to see the unique ways that Singapore is staying green. </p>

</div>

# References

1. Clayton Miller, Forrest Meggers, The Building Data Genome Project: An open, public data set from non-residential building electrical meters, Energy Procedia, Volume 122, 
September 2017, Pages 439-444, ISSN 1876-6102, https://doi.org/10.1016/j.egypro.2017.07.400.