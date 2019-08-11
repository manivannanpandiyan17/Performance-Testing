# Performance-Testing
Assessment for Performance Testing

Performed the load test using JMETER

Under test script folder, Test script (i.e. JMX) and Test data (i.e. CSV format) are available

Configured to run with 1 user hitting the application 10 times in 1 minute duration 

In the CSV Test data file (i.e. CSV Format) , add the required parameters (i.e Parameters such as Latitude, Longitude, Postal Code and Key)

Under Reports folder, Test report will be generated in the HTML Format after each execution

# Execute test

To execute the test from JMETER, import the jmx file and run directly. Response can be validated in the JSON response

To execute in cmd, run the following cmd 
jmeter -n -t script path(i.e. Path where the jmx file is available -l Path name for the  CSV file -e -o directory for generating html report
e.g. jmeter -n -t E:\Softwares\apache-jmeter-5.1.1\bin\Scripts\ApiPerformanceTests.jmx -l E:\Softwares\apache-jmeter-5.1.1\bin\Scripts\Reports\TestResults.csv -e -o E:\Softwares\apache-jmeter-5.1.1\bin\Scripts\Reports

Report will be generated and all graphs are available in the reports folder
