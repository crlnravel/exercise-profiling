Nama: Carleano Ravelza Wongso

NPM: 2306213022

Kelas: Adpro-B

# Java Profiling

## JMeter Result

### Before

 #### /all-student-name
- View Results Tree
![img.png](img.png)
- View Results Table
![img_1.png](img_1.png)
- Aggregate Report
![img_2.png](img_2.png)
- Graph Results
![img_3.png](img_3.png)

#### /highest-gpa
- View Results Tree
![img_4.png](img_4.png)
- View Results Table
![img_5.png](img_5.png)
- Aggregate Report
![img_6.png](img_6.png)
- Graph Results
![img_7.png](img_7.png)

#### /all-student
- View Results Tree
![img_8.png](img_8.png)
- View Results Table
![img_9.png](img_9.png)
- Aggregate Report
![img_10.png](img_10.png)
- Graph Results
![img_11.png](img_11.png)

### CLI
- /all-student-name
```
timeStamp,elapsed,label,responseCode,responseMessage,threadName,dataType,success,failureMessage,bytes,sentBytes,grpThreads,allThreads,URL,Latency,IdleTime,Connect
1741957785786,102,HTTP Request,200,,highest-gpa 1-1,text,true,,268,127,3,3,http://localhost:8080/highest-gpa,96,0,31
1741957785786,104,HTTP Request,200,,highest-gpa 1-2,text,true,,268,127,3,3,http://localhost:8080/highest-gpa,103,0,31
1741957785863,48,HTTP Request,200,,highest-gpa 1-3,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,48,0,1
1741957785963,38,HTTP Request,200,,highest-gpa 1-4,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,38,0,1
1741957786063,39,HTTP Request,200,,highest-gpa 1-5,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,39,0,1
1741957786167,67,HTTP Request,200,,highest-gpa 1-6,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,67,0,4
1741957786262,42,HTTP Request,200,,highest-gpa 1-7,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,42,0,1
1741957786362,39,HTTP Request,200,,highest-gpa 1-8,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,39,0,1
1741957786462,36,HTTP Request,200,,highest-gpa 1-9,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,36,0,0
1741957786561,37,HTTP Request,200,,highest-gpa 1-10,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,37,0,1
```

- /highest-gpa
```
timeStamp,elapsed,label,responseCode,responseMessage,threadName,dataType,success,failureMessage,bytes,sentBytes,grpThreads,allThreads,URL,Latency,IdleTime,Connect
1741957739929,261,HTTP Request,200,,all-student-name 1-2,text,true,,78073,132,5,5,http://localhost:8080/all-student-name,250,0,57
1741957739978,212,HTTP Request,200,,all-student-name 1-3,text,true,,78073,132,5,5,http://localhost:8080/all-student-name,209,0,8
1741957739932,258,HTTP Request,200,,all-student-name 1-1,text,true,,78073,132,5,5,http://localhost:8080/all-student-name,247,0,54
1741957740093,215,HTTP Request,200,,all-student-name 1-4,text,true,,78073,132,3,3,http://localhost:8080/all-student-name,214,0,4
1741957740180,153,HTTP Request,200,,all-student-name 1-5,text,true,,78073,132,2,2,http://localhost:8080/all-student-name,153,0,9
1741957740281,155,HTTP Request,200,,all-student-name 1-6,text,true,,78073,132,2,2,http://localhost:8080/all-student-name,154,0,10
1741957740372,159,HTTP Request,200,,all-student-name 1-7,text,true,,78073,132,2,2,http://localhost:8080/all-student-name,159,0,1
1741957740472,176,HTTP Request,200,,all-student-name 1-8,text,true,,78073,132,2,2,http://localhost:8080/all-student-name,176,0,1
1741957740572,92,HTTP Request,200,,all-student-name 1-9,text,true,,78073,132,1,1,http://localhost:8080/all-student-name,92,0,1
1741957740671,80,HTTP Request,200,,all-student-name 1-10,text,true,,78073,132,1,1,http://localhost:8080/all-student-name,79,0,1
```

- /all-student
```
timeStamp,elapsed,label,responseCode,responseMessage,threadName,dataType,success,failureMessage,bytes,sentBytes,grpThreads,allThreads,URL,Latency,IdleTime,Connect
1741957677550,28289,all-student request,200,,Thread Group 1 1-4,text,true,,718455,127,10,10,http://localhost:8080/all-student,28268,0,1
1741957677413,28470,all-student request,200,,Thread Group 1 1-2,text,true,,718455,127,9,9,http://localhost:8080/all-student,28465,0,28
1741957677451,28445,all-student request,200,,Thread Group 1 1-3,text,true,,718455,127,8,8,http://localhost:8080/all-student,28440,0,3
1741957677413,28490,all-student request,200,,Thread Group 1 1-1,text,true,,718455,127,7,7,http://localhost:8080/all-student,28486,0,28
1741957677649,28424,all-student request,200,,Thread Group 1 1-5,text,true,,718455,127,6,6,http://localhost:8080/all-student,28418,0,2
1741957677747,28327,all-student request,200,,Thread Group 1 1-6,text,true,,718455,127,6,6,http://localhost:8080/all-student,28322,0,2
1741957678047,28300,all-student request,200,,Thread Group 1 1-9,text,true,,718455,127,4,4,http://localhost:8080/all-student,28297,0,1
1741957677848,28530,all-student request,200,,Thread Group 1 1-7,text,true,,718455,127,3,3,http://localhost:8080/all-student,28526,0,2
1741957678145,28280,all-student request,200,,Thread Group 1 1-10,text,true,,718455,127,2,2,http://localhost:8080/all-student,28277,0,2
1741957677946,28479,all-student request,200,,Thread Group 1 1-8,text,true,,718455,127,2,2,http://localhost:8080/all-student,28476,0,2
```


### After

#### /all-student-name
- View Results Tree
![img_16.png](img_16.png)
- View Results Table
![img_17.png](img_17.png)
- Aggregate Report
![img_18.png](img_18.png)
- Graph Results
![img_19.png](img_19.png)

#### /highest-gpa
- View Results Tree
![img_20.png](img_20.png)
- View Results Table
![img_21.png](img_21.png)
- Aggregate Report
![img_22.png](img_22.png)
- Graph Results
![img_23.png](img_23.png)

#### /all-student
- View Results Tree
![img_12.png](img_12.png)
- View Results Table
![img_13.png](img_13.png)
- Aggregate Report
![img_14.png](img_14.png)
- Graph Results
![img_15.png](img_15.png)

### CLI
- /all-student-name
```
timeStamp,elapsed,label,responseCode,responseMessage,threadName,dataType,success,failureMessage,bytes,sentBytes,grpThreads,allThreads,URL,Latency,IdleTime,Connect
1741961210302,706,HTTP Request,200,,all-student-name 1-2,text,true,,78073,132,9,9,http://localhost:8080/all-student-name,696,0,39
1741961210619,544,HTTP Request,200,,all-student-name 1-6,text,true,,78073,132,9,9,http://localhost:8080/all-student-name,543,0,1
1741961210301,875,HTTP Request,200,,all-student-name 1-1,text,true,,78073,132,8,8,http://localhost:8080/all-student-name,874,0,39
1741961210323,858,HTTP Request,200,,all-student-name 1-3,text,true,,78073,132,7,7,http://localhost:8080/all-student-name,857,0,18
1741961210421,762,HTTP Request,200,,all-student-name 1-4,text,true,,78073,132,6,6,http://localhost:8080/all-student-name,761,0,1
1741961210519,701,HTTP Request,200,,all-student-name 1-5,text,true,,78073,132,5,5,http://localhost:8080/all-student-name,700,0,1
1741961210832,390,HTTP Request,200,,all-student-name 1-8,text,true,,78073,132,4,4,http://localhost:8080/all-student-name,390,0,2
1741961210722,520,HTTP Request,200,,all-student-name 1-7,text,true,,78073,132,3,3,http://localhost:8080/all-student-name,519,0,2
1741961210951,345,HTTP Request,200,,all-student-name 1-9,text,true,,78073,132,2,2,http://localhost:8080/all-student-name,344,0,2
1741961211049,282,HTTP Request,200,,all-student-name 1-10,text,true,,78073,132,1,1,http://localhost:8080/all-student-name,282,0,2
```

- /highest-gpa
```
timeStamp,elapsed,label,responseCode,responseMessage,threadName,dataType,success,failureMessage,bytes,sentBytes,grpThreads,allThreads,URL,Latency,IdleTime,Connect
1741961241278,83,HTTP Request,200,,highest-gpa 1-3,text,true,,268,127,3,3,http://localhost:8080/highest-gpa,83,0,4
1741961241207,150,HTTP Request,200,,highest-gpa 1-2,text,true,,268,127,3,3,http://localhost:8080/highest-gpa,145,0,32
1741961241207,150,HTTP Request,200,,highest-gpa 1-1,text,true,,268,127,3,3,http://localhost:8080/highest-gpa,145,0,32
1741961241374,46,HTTP Request,200,,highest-gpa 1-4,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,46,0,1
1741961241473,64,HTTP Request,200,,highest-gpa 1-5,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,64,0,1
1741961241572,48,HTTP Request,200,,highest-gpa 1-6,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,48,0,1
1741961241671,49,HTTP Request,200,,highest-gpa 1-7,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,48,0,1
1741961241773,74,HTTP Request,200,,highest-gpa 1-8,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,74,0,2
1741961241871,68,HTTP Request,200,,highest-gpa 1-9,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,68,0,2
1741961241969,77,HTTP Request,200,,highest-gpa 1-10,text,true,,268,127,1,1,http://localhost:8080/highest-gpa,76,0,1
```

- /all-student
```
timeStamp,elapsed,label,responseCode,responseMessage,threadName,dataType,success,failureMessage,bytes,sentBytes,grpThreads,allThreads,URL,Latency,IdleTime,Connect
1741961137326,36980,all-student request,200,,Thread Group 1 1-3,text,true,,718455,127,10,10,http://localhost:8080/all-student,36962,0,1
1741961137250,37141,all-student request,200,,Thread Group 1 1-1,text,true,,718455,127,9,9,http://localhost:8080/all-student,37136,0,24
1741961137250,37301,all-student request,200,,Thread Group 1 1-2,text,true,,718455,127,8,8,http://localhost:8080/all-student,37295,0,24
1741961137424,37351,all-student request,200,,Thread Group 1 1-4,text,true,,718455,127,7,7,http://localhost:8080/all-student,37333,0,2
1741961137726,37067,all-student request,200,,Thread Group 1 1-7,text,true,,718455,127,6,6,http://localhost:8080/all-student,37061,0,8
1741961137630,37346,all-student request,200,,Thread Group 1 1-6,text,true,,718455,127,5,5,http://localhost:8080/all-student,37342,0,5
1741961137524,37535,all-student request,200,,Thread Group 1 1-5,text,true,,718455,127,4,4,http://localhost:8080/all-student,37530,0,3
1741961137820,37512,all-student request,200,,Thread Group 1 1-8,text,true,,718455,127,3,3,http://localhost:8080/all-student,37507,0,3
1741961137920,37842,all-student request,200,,Thread Group 1 1-9,text,true,,718455,127,2,2,http://localhost:8080/all-student,37837,0,11
1741961138019,38017,all-student request,200,,Thread Group 1 1-10,text,true,,718455,127,1,1,http://localhost:8080/all-student,38013,0,5
```

#### Conclusion 
After optimization, the profiling elapsed time is noticeably reduced. This enhancement highlights the impact of the applied optimizations, leading to improved performance and greater efficiency of the application.

# Reflection

### What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
Performance testing with JMeter focuses on simulating user load and measuring the application's response times, throughput, and error rates under various conditions. It helps identify performance issues from an end-user perspective. Profiling with IntelliJ Profiler, on the other hand, involves analyzing the application's internal behavior, such as CPU usage, memory allocation, and method execution times, to pinpoint specific code-level bottlenecks.

### How does the profiling process help you in identifying and understanding the weak points in your application?
Profiling provides detailed insights into the application's runtime behavior, allowing you to identify inefficient code paths, memory leaks, and resource-intensive operations. By examining the profiling data, you can understand which parts of the code are consuming the most resources and causing performance degradation.

### Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?
Yes, IntelliJ Profiler is effective in analyzing and identifying bottlenecks. It offers a comprehensive set of tools to visualize and measure various performance metrics, making it easier to locate and address performance issues at the code level.

### What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?
The main challenges include the time required to seed and access the database for each endpoint due to the large amount of data. Additionally, variations in computer environments and elapsed times can pose significant challenges. To overcome these, I optimize the application code to reduce the time needed to seed and access the database. I also ensure to run the test, both JMeter and IntelliJ Profiler, several times to account for variations and validate the results.

### What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?
The main benefits include the ability to identify and fix performance bottlenecks, optimize resource usage, and improve overall application efficiency. IntelliJ Profiler's integration with the development environment also streamlines the profiling process, making it more accessible and easier to use.

### How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?
Of course, the results can vary due to differences in the testing and profiling methodologies. Performance testing with JMeter simulates user load and measures response times, throughput, and error rates, providing a high-level view of the application's performance under various conditions. Profiling with IntelliJ Profiler, however, offers a more granular analysis of the application's internal behavior, such as CPU usage, memory allocation, and method execution times.

Despite these differences, the results from both methods should generally align if the application is performing consistently. Discrepancies might arise due to factors like environmental differences, test configurations, or the specific aspects of performance being measured. To reconcile these differences, it's important to cross-reference findings from both tools, validate them against real-world scenarios, and ensure that any optimizations made improve performance across the board without introducing new issues.

### What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?
To optimize application performance, I use tools like JMeter and IntelliJ Profiler for analysis. JMeter simulates user load and measures response times, while IntelliJ Profiler provides insights into CPU usage and memory allocation. By using these tools, I identify performance bottlenecks and inefficiencies. My optimization efforts focus on removing unused and redundant functions, ensuring the application runs efficiently without compromising functionality. This approach helps in understanding and resolving performance issues effectively.
