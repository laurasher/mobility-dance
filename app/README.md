# Dust and Magnet d3 Implementation #

## To run
```git clone git@gitlab.jhuapl.edu:asherlk1/dust-and-magnet.git```

```cd dust-and-magnet```

```python -m http.server ```

[Localhost](http://127.0.0.1:8000/)

## Premise ##

The purpose of dust and magnet is to represent multivariate data using the prinicles of iron filings and magnets.

Basically, each data point is represented as a particle and each property of the data point is represented as a magnet.

When activated, the dust particles to the magnets depending on the relative magnitude of the magnet's property of the dust.

## Example ##

Here, the dust are cars and the magnets are numerical properties of the cars such as highway mpg, price, city mpg etc. When the
highway mpg magnet is selected, the dust rearrange themselves so that the ones with low highway mpg are further away from the 
highway mpg magnet than those that have a high highway mpg.

What is cool is that when more magnets are added, the data will automatically rearrange as well thereby allowing a user to view
multivariate relationships within the data!
