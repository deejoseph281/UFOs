# UFOs_Javascript

## Objective
Using the basic Javascript code of UFO sightings, we are tasked to add code to the existing frame in order to filter by more than just the date.
The data is given via a script and we already have the webpage allowing us to filter by date.
We can see that the data in the webpage (and the subsequent script) is made of lists that inventory the sightings by Date, City, State, Country, Shape (of the sighting), Duration (of the sighting). There are also a column with the comments.

We have added the following filters to the webpage, city, state, country and shape.

## Results
We are now able to filter the data, without clicking anywhere but just entering the values we want to filter by in the cases.

For example, if we filter by date only (1/10/2020), we can see that there are 11 entries.
![image](https://user-images.githubusercontent.com/75656368/210272061-1858fd95-d26a-4e2a-a76e-147c5dcd9939.png)

None of these 11 entries are in Canada.
![image](https://user-images.githubusercontent.com/75656368/210272083-5bd15b03-e8df-4f68-8b97-556d22360830.png)

However, there were 2 sightings in Canada, as shown when we delete the entry in "Date" filter.
![image](https://user-images.githubusercontent.com/75656368/210272104-5f0c98bc-e7ea-4cd0-b04b-7cc917618139.png)

Lastly, 5 entries were for Disk Shape. But the shape with the most entry is "light".
![image](https://user-images.githubusercontent.com/75656368/210272198-ffcc2480-58be-4634-a020-f20e8e692e3e.png)


## Summary
### Inconvenient:
One drawback of this webpage is that it's lenghty. We have to scroll back and there is no summary data.
It would have been good to add another square in the storyboard (before the data). To have the summary of the data below.

### Recommendations:
We recommend Dana to add a summary table at the top (prior to the data). With the following values:
number of sightings: Count(rows)
How many cities: count_distinct(rows on City)
Avg Duration: Mean(Duration)

These values should also be taken into account whilst filters are applied.

Additionally, it would be interesting to have formatting on the comments to pull the most quoted sentences/text and add to the top of the webpage to entice the reader. 

Lastly, allowing multiple values in the filters (separated by commas) would also be useful as the data expands.


