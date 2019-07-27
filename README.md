# Overview of project: #

1. Using Oura Ring API, access my general tracking data.
2. Using text file download, access my cycle tracking data.
3. Building out React/Frontend, enter and store other data points (type of food, if alchohol was consumed, mood/energy, if experimenting wither certain supplements..) to access.
4. Building out the Backend via Rails may be a good route to start to combine these into one place, but the primary goal of all this data is to run it through a pi and 'data science' it with Python (jupyter, pandas, numpy, etc) to get a more comprehensive cause-and-effect from life habits - more actionable insights than the trends each set of data offers on it's own.

## User Stories (For React): ##

* As a user, I can see a form that asks me to enter inputs - 
    * Date (type of data? select?)
    * Booze? (yes or no then opens up more options)
        * How much and what type (number entry, drop down for type)
    * How much did you eat? (not enough, enough, too much)
    * Did your diet consist of wheat? (y/n)
        * If y: How much? (nothing crazy, it was in every meal)
    * Did your diet consist of dairy? (y/n)
        * If y: How much? (nothing crazy, it was in every meal)
    * Carbs? (nothing crazy, about right, they were my main macro)
    * Protien? (nothing crazy, about right, they were my main macro)
    * Fat? (nothing crazy, about right, they were my main macro)
    * Other noteworthy? (y/n)
        * Text entry as a catchall
    * As a user, I can hit the submit button and view history, with a successful alert and the new line of data stored.
    
* As a user, I can click into View History from a navigation bar and see all prior entries.

* Icebox - as a user, there is a homepage to explain what to do, all views look nice and uniform


    
