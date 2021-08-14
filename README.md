# Surf and Ice Cream Shop Analysis

Weather analysis for a potential surf and ice cream shop.

## Overview

The purpose of this analysis is to determine the viability of a new business that sells surf gear and ice cream on the island of Oahu, Hawaii.

## Results

The weather in Oahu is remarkably consistent, but there is some variation between June and December.

* As expected, the weather is colder in December, with the lowest temperature being 56 degrees, whereas the lowest for June is 64 degrees

* There appears to be more variation in temperatures in December with a standard deviation of 3.74, and a standard deviation of 3.26 for June.

* The June data has more instances of measurement at 1700, but only 1517 for December.

## Summary

So far, we have adequate data on the temperature range for Hawaii, but there are a few additional queries to gather more precise or useful data.

Precipitation data would be relevant for determining the conditions for the new surf shop. An equivalent analysis can be done by replacing the "Measurement.tobs" variable with "Measurement.prcp."

It might be helpful to find measurements from the station that is located the closest to the location of the potential new surf shop. This could be done by filtering for the specific station in the stations table.