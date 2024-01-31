# HR Analytics Dashboard
![HR Dashboard](https://github.com/goyalvinayak/Power-BI-Projects/assets/110285605/eb46aaa8-1312-4f67-96d7-00f8c020d39d)
![HR Dashboard1](https://github.com/goyalvinayak/Power-BI-Projects/assets/110285605/83af5421-6152-474f-af4b-fffedfbceb14)
![HR Dashboard2](https://github.com/goyalvinayak/Power-BI-Projects/assets/110285605/7b1657c0-e572-46e6-bbda-05272cd09825)

### Problem Encountered
Ratio of Male and Female Employees
Solution-
'''
Ratio = CALCULATE(COUNTROWS(data), data[Gender] = "Male")/ CALCULATE(COUNTROWS(data), data[Gender]= "Female")

'''
