# Overview of project:

1. Using Oura Ring API, access my general tracking data.
2. Using text file download, access my cycle tracking data.
3. Building out React/Frontend, enter and store other data points (type of food, if alchohol was consumed, mood/energy, if experimenting wither certain supplements..) to access.
4. Building out the Backend via Rails may be a good route to start to combine these into one place, but the primary goal of all this data is to run it through a pi and 'data science' it with Python (jupyter, pandas, numpy, etc) to get a more comprehensive cause-and-effect from life habits - more actinable insights than the trends each set of data offers on it's own.

# User Stories (For React):

1. As a user, I can see a form that asks me to enter inputs -
    a. Date (type of data? select?)
    b. Booze? (yes or no then opens up more options)
        i. How much and what type (number entry, drop down for type)
    c. How much did you eat? (not enough, enough, too much)
    d. Did your diet consist of wheat? (y/n)
        i. If y: How much? (nothing crazy, it was in every meal)
    e. Did your diet consist of dairy? (y/n)
        i. If y: How much? (nothing crazy, it was in every meal)
    f. Carbs? (nothing crazy, about right, they were my main macro)
    g. Protien? (nothing crazy, about right, they were my main macro)
    h. Fat? (nothing crazy, about right, they were my main macro)
    i. Other noteworthy? (y/n)
        i. Text entry as a catchall
    j. As a user, I can hit the submit button and view history, with a successful alert and the new line of data stored.
    
2. As a user, I can click into View History from a navigation bar and see all prior entries.

3. Icebox - as a user, there is a homepage to explain what to do, all views look nice and uniform


    
