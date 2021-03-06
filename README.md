# Anchorage Single-Family Home Energy System Type

# Overview

Anchorage is a city of nearly 300,000 people located on the coast of southcentral Alaska with a subarctic climate. Homes in this city do not have air conditioners due to the mild summer temperatures, and typically rely on natural ventilation for the hottest summer days.
Heating homes is typically done nearly year-round, and most commonly burn natural gas, with some homes using oil or electricity as the energy source for heating. Anchorage residential heating systems can be divided into four different categories.

* **Radiant** - Characterized by radiant floor heating, which is expensive to install, but is a very efficient way of distributing heat.

* **Forced Air** - Uses ducts and vents to distribute hot air through the home. Can make occupants uncomfortable due to lack of moisture and can worsen allergies.

* **Hot Water** - Hot water baseboards are installed along the base of walls. They are slow to increase the room temperature and are known to not evenly heat large-sized rooms.

* **Electric** - Use baseboards to distribute heat, and have the same problems as hot water baseboards. Pros include quiet operation and low maintenance.

Using public data from the Anchorage government, this project will evaluate the changes in the share of heating systems for new signle-family homes from 1960 to 2019.

# Method

The Municipality of Anchorage manages public data in a csv file for every single property in the city, including the type of heating system. Using python, the data was filtered based on the criteria of a single-family residential property. The share of each heating system type for every year was determined by summing the total number of each heating system and dividing it by the total number of new single-family homes for each year.

# Results and Analysis

The figure below shows the annual share of heating systems installed in new single-family homes, as well as the number of new single-family homes per year. During the housing boom in the 1970s and 1980s, hot water baseboards were the overwhelming favorite by homebuilders, and are a coomon sight in older Anchorage homes. Electric baseboards were occasionally installed for a brief period in the 1970s as a result of the oil crisis, and have rarely been used since. The 1980s also saw a surge in forced air systems, and have maintained a a steady and significant share of the installed heating system share since the switch from hot water. Radiant floor heating has been shown some favor by homebuilders, taking in a share of 15% to 25% since 2005.

![image](/png/Figure_1.png)
