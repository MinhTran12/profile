# Avocado Connect

Have you ever wondered about avocados? More specifically, do you find yourself wanting to explore avocado pricing in massive quantities? Well, Avocado Connect is a web application created for that purpose. By utilizing interactive visual graphs, we aim to convey quick and concise information on the US avocado pricing trends and trade volume details.

I was responsible for handling the raw data and was one of the main coders for Avocado Connect, though I also contributed to the site's design.

## Data Exploration

The team got their avocado data from the Hass Avocado Board (HAB). The complete raw data we had were between 2021 and 2023, containing data points such as avocado types, price points, units sold in bulks and bags, cities/states, and more.
Each team member spent some time to analyze the data while creating some simple graphs (I used Python). At that point, we figured the data aspect of the avocados we wanted to focus on conveying, which was the price and and the trade quantity of avocados over time in big cities.

<div class="single-img">
    <img src="images/avocado-connect/python-avocado-plots.png">
</div>

## Design and Prototyping

After deciding on our core dataset, we began designing the user interfaces and the visualization of the data. Some simple sketches were made at first, and as the team discussed among ourselves, diagrams and then wireframes were developed and further refined them along the way.

Some ideas were scrapped later during development, such as having our interface behave like a storyboard as users scroll down the application, with airplanes and ships as part of the graphs to emulate the avocado trade; we opted for a dashboard design instead as we prioritized the users' speedy knowledge acquisition. Other ideas were kept, with one primary example being a map of the US with dynamic avocado icons in which their pits change color based on the price/amount of avocados at the given time.

<div class="double-img">
    <img src="images/avocado-connect/simple-sketches.png">
    <img src="images/avocado-connect/app-diagram.png">
</div>

<div class="single-img">
    <img src="images/avocado-connect/paper-wireframe.jpg">
</div>

## Implementation

We used html/css and javascript to program Avocado Connect. Python pandas was used to process the raw HAB data we got at the beginning, and the D3 javascript library was the main tool used to visualize the processed data. All our main functions from the design phase were translated successfully into deployment, and we ensured that our graphs could dynamically adapt to the user inputs.

Minor quality-of-life adjustments were made to the final version based on the feedback from volunteering participants where they were asked to complete specific tasks when interacting with Avocado Connect.

<div class="single-img">
    <img src="images/avocado-connect/web-app-1.png">
</div>
<div class="single-img">
    <img src="images/avocado-connect/web-app-2.png">
</div>

## Reflection

Building Avocado Connect taught me that an effective visualization is hard to master but transformative when done correctly. With proper techniques and novel approaches to designing, visual representations can elevate how a dataset is presented to an audience; after all, data is worth nothing if no one can understand it.

For me, the project also reinforced the idea that sometimes, less is more, as the team had to remove certain design choices which resulted in a stronger and more concise presentation in the end. As a result, I found myself paying much more attention to the existing functions and their details, which helped me better appreciate the value of thoughtful iteration and subtle refinements. This made me realize that impactful design doesn't always require adding new elements; in many cases, enhancing or simplifying what’s already there can be even more effective.
