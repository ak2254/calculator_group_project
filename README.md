``[![Build Status](https://travis-ci.org/tommywenjiezhang/is219_group_project.svg?branch=master)](https://travis-ci.org/tommywenjiezhang/is219_group_project)


[![Coverage Status](https://coveralls.io/repos/github/tommywenjiezhang/is219_group_project/badge.svg?branch=master)](https://coveralls.io/github/tommywenjiezhang/is219_group_project?branch=master)

[![dependencies Status](https://david-dm.org/tommywenjiezhang/is219_group_project/status.svg)](https://david-dm.org/tommywenjiezhang/is219_group_project) [![devDependency Status](https://david-dm.org/tommywenjiezhang/is219_group_project/dev-status.svg)](https://david-dm.org/tommywenjiezhang/is219_group_project?type=dev)

<h1>Group Project Assignment </h1>

To start
```
git clone https://github.com/tommywenjiezhang/is219_group_project.git
cd is219_group_project
git pull
git checkout -b newBranch
git status

```
To push the project once you finish
```
git commit -m"new feature"
git push newBranch
git request-pull https://github.com/tommywenjiezhang/is219_group_project.git master
```
<h1>Group Project Assignment </h1>
<h3>Group Names: Anjali Kumari and Wenjie Zhang</h3>
 
#  ` Documentation: `
    Outline: 
    1. Calculator Object
        1. Properties
            1. Result
        2. Methods
            1.BasicCalculation folder -> methods
                1. sum -> Calls sum static method from math operations
                2. Subtraction -> Call subtraction static method from Math operations
                3. Sanitization -> Checks if it is a number or not
                4. Divide -> Calls for  quotient static method  from the the math operations 
                5. multiply -> Calls for the product static method from the math operations 
                6. square  -> calls for the square static method from the math operations
                7. squareRoot ->  calls for the squareeRoot method from the math operations  
            2. random methods folder
                calls- RandomCalclator 
                1. genrateRandomList.js  -> calls genrateRandomList 
                2. rangeTwo.js -> calls rangeBetweenTwo 
                3. seedRandom.js -> calls seedRandom
                4. selectNitem.js -> calls selectNitem
                5. selectRandom.js  
            3. sampling methods folder
                calls- sampling methods class- methods calls  
               1. cocharn.js -> calls cochran method  
               2. confidenceInterval.js -> calls confidenceInterval method  
               3. SimpleSample.js 
               4. SystemSample.js -> calls  systemSampling method 
               5. marginofError.js -> calls marginOfError method 
                      
        3. Operation classes 
            1. MathOperations 
                1. static sum method - calls sum.js  
                    1. Adds two numbers  
                2. Static product method - calls multiply.js   
                    1. "*" two numbers 
                3. static  quotient- calls divide.js 
                    1. divides two numbers
                4. static sumlist 
                    1.adds two arrays 
                5. static square- calls square.js 
                    1. squares two numbers 
                6. static squareRoot- calls squareRoot.js 
            2. Calculator class 
                1. Calls MathOperations 
                    1. add 
                    2. divide
                    3. Multiply 
                    4. sumList 
                    5. square
                    6. sqaureRoot 
            3. SamplingMethods class in sampling folder 
                1. All calls 
                    1.basic calculator 
                    2. jStat Library 
                    3. StatisticsOperation class 
                2. simpleRandomTest -> calls SimpleSample.js 
                    1. simple ramdom sampling  
                3. confidenceInterval-> class ConfidenceInterval.js 
                    1. Confidence Interval For a Sample
                4. cochran -> calls Math.ceil
                    1. Cochran’s Sample Size Formula 
                5. clWidth 
                    1. Find a Sample Size Given a Confidence Interval and Width (unknown population standard deviation)
                6. sampleStd
                    1. Find a Sample Size Given a Confidence Interval and Width (known population standard deviation)
                7. systemSampling
                    1. System Sampling
                8. marginOfError
                    1. finds the margin of error of the sample given  
            4. StatisticsOperastions class 
                1. extends basic calculator 
                2. All calls external library
                3. Calls simple sample 
                methods :
                    1. mean 
                         - calculates the mean 
                    2. variance 
                        - calculates variance 
                    3. stddev 
                        -calculates statdarddivation 
                    4. median 
                         -calculates median 
                    5. mormPDF 
                         - calculates Log-normal distribution with paramters  
                    6. zScore 
                        -  calculates the Z-Score  
                    7. Qartilies
                        - calculates quartiles 
                    8. skewness 
                        -calculates skewness 
                    9. sampleCorrlation 
                        -calculates sample corrlation
                    10. populationCorrelation
                        -calculates population correlation
                    11. meanStdev 
                        -calculates Mean Deviation / Mean Absolute Deviation
                    12. mode 
                        -calculates mode 
             5. RandomCaluculator class in Random folder 
                methods:
                    1. rangeBetweenTwo:
                          - calls rangeTwo.js 
                          - Generate a random number without a seed between a range of two numbers - Both Integer and Decimal
                    2. generateRandomList
                           - calls generateRandomList.js
                            - genrates random list 
                    3. selectRandom
                          -calls selectRandom.js
                          - Select a random item from a list
                    4.  seedRandom()
                           -calls seedRandom.js 
                           -Set a seed and randomly.select the same value from a list
                    5.  selectNitem(arr,n)
                            -calls selectNitem.js 
                            -Select N number of items



<h1>Task list definations: </h1> 

<h2> Create fuctions and tests for all them below </h2>
<ol>
<li>
Simple random sampling --> is the basic sampling technique where one selects a group of subjects for study from a larger group of population.    
 <ul>
    <li> Fromula/ test provided in the tests 
    </ul>
</li>
<li>Systematic sampling --> statistical method involves selection of elements from ordered sampling frame. 
 <ul>
    <li> Fromula/ test provided in the tests 
    </ul>
</li>

<li>Confidence Interval For a Sample --> interval estimate combined with a probability statement.
 <ul>
    <li> Fromula/ test provided in the tests 
    </ul>
<li> Margin of Error--> a small amount that is allowed for in case of miscalculation
 <ul>
    <li> Fromula/ test provided in the tests 
    </ul>
<li>Confidence Interval --> type of estimate computed from the statistics from data given
 <ul>
    <li> Fromula/ test provided in the tests 
    </ul>
<li> Cochran’s Sample Size -->  an ideal sample size given a desired level of precision, desired confidence level, and the estimated proportion of the attribute in the data
<li>Mean --> mathematical expectation or average
<ul>
<li> formula/example - data set  { 1, 2, 3, 4, 5, 6} =  (1+2+3+4+5+6)/6 = 3.5 
</ul>
<li> Median --> denoting or relating to a value or quantity lying at the midpoint of a frequency distribution of the given data
  <ul>
  <li> formula/example - data set  { 1, 2, 3, 4, 5, 6} =  (3+4)/2 = 3.5
  </ul>
<li> Mode --> most frequently occurred value
<ul>
  <li> formula - data set  { 1, 2, 3, 4, 5, 6, 6} =  6
  </ul>
<li> Variance -->the expectation of the squared deviation of a random variable from its mean. 
  <ul>
    <li> Fromula/ test provided in the tests 
    </ul>
<li> Standard Deviation --> measure of the amount of variation or dispersion of a set of values.
 <ul>
    <li>Fromula/ test provided in the tests 
    </ul>
<li> Quartiles -->  type of quantile which divides the number of data points into four more or less equal parts. 
<ul>
    <li> { 1, 2, 3, 4, 5, 6, 6}  = q1 = 2, q2 = 4, q3 = 6   
    </ul>
<li> Skewness --> measure of the asymmetry of the probability distribution of a real-valued random variable about its mean
 <ul>
    <li> Fromula/ test provided in the tests 
    </ul>

<li> Sample Correlation --> measure of the strength of the linear relationship between the x and the y values of a data pair.
 <ul>
    <li> Fromula/ test provided in the tests 
    </ul>
<li> Population Correlation -->  measure the strength of association between two variables. 
 <ul>
    <li> Fromula/ test provided in the tests 
    </ul>
<li> Z-Score - numerical measurement  of a value's relationship to the mean of a group of values
 <ul>
    <li>Fromula/ test provided in the tests 
    </ul>
<li>Mean Deviation / Mean Absolute Deviation - the average of the absolute deviations from a central point. 
 <ul>
    <li>Fromula/ test provided in the tests 
    </ul>
<li> Random number without a seed between a range of two numbers
 <ul>
    <li> Fromula/ test provided in the tests 
    </ul>
<li> Random number with a seed between a range of two numbers
 <ul>
    <li> Fromula/ test provided in the tests 
    </ul>
</li>




</ol>




**Table for tasks performed**
<table style="width:100%">
  <tr>
    <th>Todo</th>
    <th>progressed by </th>
    <th>Reviewed By</th>
    <th>Done by<th>  
    <th>completion</th>
  </tr>
  <tr>
    <td>Create Descriptive Statistics Functions</td>
   <td> Wenjie Zhang  </td>
       <td>Anjlali Kumari </td>
       <td>Wenjie and Anjali </td>
       <td>completed</td>
  </tr>
  <tr>
    <td> Create Simple random sampling </td>
    <td>Wenjie Zhang </td>
    <td>Anjali </td>
    <td>Wenjie and Anjali </td>
    <td>completed</d>
  </tr>
   <tr>
      <td> ceate Systematic sampling  </td>
     <td> Wenjie and anjali </td>
         <td>Both </td>
         <td>Both</td>
         <td>completed</td>
    </tr>
    <tr>
          <td>create Confidence Interval For a Sample function</td>
          <td> wenjie </td>
              <td>Anjali</td>
              <td>Wenjie and Anjali</td>
               <td>completed</td>
        </tr>
        <tr>
                  <td> Create Margin of Error function 
 </td>
                  <td> Wenjie </td>
                      <td>Anjlai</td>
                      <td>both</td>
                       <td>completed</td>
                </tr>
                <tr>
                                  <td> Confidence Interval function </td>
                                  <td> Wenjie</td>
                                      <td>Anjali</td>
                                      <td>Both</td>
                                       <td>completed</td>
                                </tr>
                <tr>
                          <td> Write Cochran’s Sample Size Formula </td>
                          <td> Wenjie</td>
                              <td>Anjali </td>
                              <td>Both</td>
                               <td>completed</td>
                        </tr>
               <tr>
                                         <td>How to Find a Sample Size Given a Confidence Interval and Width (unknown population standard deviation)
 </td>
                                         <td> wenjie  </td>
                                             <td>Anjali</td>
                                             <td>Both</td>
                                              <td>completed</td>
                                       </tr>
<tr>
      <td>How to Find a Sample Size Given a Confidence Interval and Width (known population standard deviation)
 </td>
     <td> Wenjie </td>
         <td>Anjali</td>
         <td>Both</td>
          <td>completed</td>
    </tr>
    
 <tr>
 <tr>
       <td> Random Generator functions </td>
      <td>  Both </td>
          <td>Both /td>
          <td>Both</td>
           <td>completed</td>
     </tr>
     
  <tr> 
  <tr>
         <td> Create test suites </td>
        <td> Wenjie </td>
            <td>Both </td>
            <td>Both</td>
             <td>completed</td>
       </tr>
        <tr>
                <td> Create README.MD  </td>
               <td> Anjali</td>
                   <td>Wenjie</td>
                   <td>Both</td>
                    <td>completed</td>
              </tr>
       
    

</table>

                  

