# UFOs


## Overview

Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. We'll be adding table filters for the city, state, country, and shape.
Main objective of this challenge is to create a web page that makes searching a more smoothly process for users. 

## Results

First, we add images to the head so visually is more attractive

![MainPage](https://user-images.githubusercontent.com/96633294/159615864-f136cfc4-50ee-4fca-a00b-b497e63c80c8.png)

We can check at the page, main information about UFOs and a short introduction to the topic wich is amazing to attrack the attention of the user 

As we can check with bellow part of the HTML code we can create a search filter with great funtion to get faster information in the same page linking this HTML wit our JavaScript codes: 

```
           <table class="table table-striped">
                <thead>
                  <tr style="color:grey">
                    <th>Date</th>
                    <th>City</th>
                    <th>State</th>
                    <th>Country</th>
                    <th>Shape</th>
                    <th>Duration</th>
                    <th>Comments</th>
                  </tr>
                </thead>
                <tbody style="color:grey"></tbody>
              </table>
          </div>
        </div>
      </div>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/4.11.0/d3.js"></script>
      <script src="./static/data.js"></script>
      <script src="./static/app.js"></script>
</body>

```

Finally, we get bellow filter bars: 

![filtersc](https://user-images.githubusercontent.com/96633294/159758571-6520cb7d-855c-4389-b1d1-53053273d64e.png)


This is where we can freely search all informations about certain region and displays a reefreshed table: 

![filter_function](https://user-images.githubusercontent.com/96633294/159758776-0e67e254-0161-4465-b7e5-2deebf4d151c.png)


## Summary

This kind of web development is very effective to show results of analysis and make users an easy way to find information. You will find that this kind of pages are very popular since users can search and find all they need in a single place.

Here are some suggetsions for future improvement of this web page: 

- Add more images to make it more user friendly and more interactive. 
- Adding links or more external pages so users can get deeper in the infromation that already provides the page. 
- adding a clear button so users can make new searching.
