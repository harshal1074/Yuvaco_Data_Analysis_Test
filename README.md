# Yuvaco_Data_Analysis_Test

Please consider yourself working as a data analyst at a firm that deals with delivery of goods and packages. They have their database through they calculate cost of expedition for each package which represents single row in the data. 

Task - Write a python script that calculates the same - ie cost of each package delivery in the dataset. The cost grid to calculate cost is provided as well. 

As a submission, share across a zip file containing the following - a google collab notebook as well as output of the script. Please only share code if it runs successfully. 

All the best to you! The deadline for this assignment is 24th September 6 P.m. No submissions will be considered post that!

Sample Data: 
Package ID	Weight (kg)	Distance (km)	Delivery Type
1	3	10	Express
2	5	25	Standard
3	2	5	Express
4	6	15	Standard
5	4	30	Express

Cost grid: 

cost_grid = {
    'Express': {
        'Base Cost': 10,
        'Cost per kg': 2,
        'Cost per km': 1,
    },
    'Standard': {
        'Base Cost': 5,
        'Cost per kg': 1.5,
        'Cost per km': 0.5,
    }
}
