1. what is refractoring? give three examples of refractoring techniques/

Refractoring is reorganizing code without changing its functionality. Ex. changing a variable name, altering the contract (input, output) of a function, changing the data type used in a particular spot, changing the library you're using, extracting functions, removing redundant code.

2. In data science project, why does code naturally go through "phases" of messiness?

Because real-world data is complex and often contains inconsistencies, missing values, and unexpected patterns. As data sceintists explore the data, they need to experiment with different approaches, revise assumptions, and add or modify code as new problems arise.

3. What are three techniques for creating more modular code?

#1  creating reusable functions for operations performed repeatedly, reducing code duplication (redundancy)
#2 grouping related operations together ex. separating data preprocessing from data vsualization
#3 separating code into separate modules (python files), each with a specific responsibility, which can then be imported and reused in other scripts
