# UFO Sightings Challenge

## [Available at this Github Page](https://hsp910.github.io/UFO-Sightings-Challenge/)


## Background 
This project was done in hopes of being able to use scripting from a javascript file to help filter data stored in a separate javascript file. By using this scripting with a combination of some css styling from bootstrap and a minor amount from a separate stylesheet stored in the project we are able to create a simple yet attractive website that has a responsive filtering tool on the side to display our data. With this we are able to show the power of javascript to change and react to user input on the fly by allowing it to react to any user input and change the data it's showing to match what the user is looking for at the time. The actual website is about ufo sightings that were reported primarily in the US and within a two week span of January 2010. 


## Results
Now for the actual website we will look at a few different screenshots to show off the entirety of the website and the filtering functions.

![Overall website](https://i.imgur.com/y1YwsMz.png)

- From here we can see the overall look of the website including how we used bootstrap to layout the entire website in a small grid format. We kept the filters on the left and all of the actual data in a list on the right of the website. 

![Only using Date Filter](https://i.imgur.com/zoC2oib.png)

- Now as we look closer we can see all the possible filters to choose from in the data. They include date, city, state, country, and shape. Shape being the shape of the UFO seen at the incident in question. 
- We also see how the filtering works compared to the first image as we have now eliminated all incidents outside of 1/2/2010
- Now we can choose to filter down even more by something as simple as the state the incident took place in.

![Using both date and state filter](https://i.imgur.com/BkXaVFp.png)

- Here we see that we have narrowed down the search by including only two filters in our search, the date of 1/2/2010 and the state of California.
- We could choose to narrow it down even further if we wanted to with more filters using city, country, or shape; however, this would be largely the same as the two previous screenshots so I will omit those for this breif introduction.

## Summary and Suggestions

While the website is fully functional and is able to be used at the moment there are many improvements that can be made. The data set used in this website is heavily limited only including incidents within the US and within the month of January 2010. If we were to expand the data by adding directly to the data.js file in the repository we would be able to search larger swaths of data with ease, but we would also be slowing down the page on the whole as there is no limit on how many data entries are shown in the web page initially. The lack of outside US incidents in the webpage would be a larger issue if there was more interest in this website from countries other than the United Sates. We could also, as mentioned previously, make the website only display the top 10 or 20 incidents in a given dataset after beign filtered to help reduce the load times on the website. There is also always the need to help clean up the styling of the webpage. The CSS used inthis webpage is very basic and not unique in any way. Adding more personal flair would belp differentiate this website from others of a similar nature.
