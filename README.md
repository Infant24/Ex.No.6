# Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

# Date:
# Register no.
# Aim: Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools

#AI Tools Required:

# Explanation:
Experiment the persona pattern as a programmer for any specific applications related with your interesting area. 
Generate the outoput using more than one AI tool and based on the code generation analyse and discussing that. 

# Conclusion:
OUTPUT:Title: Framing Prompts for AI-Assisted Project Coding
Objective

To learn how to create effective prompts for AI tools that assist in coding tasks such as API integration, output comparison, and generating insights for mini and final-year projects.

Stage 1: Prompt for Generating Python Code for Multiple APIs
Student-Designed Prompt

Generate a Python program that fetches weather data from two different APIs. Use the requests library and display temperature, humidity, and weather conditions from both APIs. Include proper error handling and comments in the code.

AI-Generated Response
import requests

api1_url = "https://api.weatherapi.com/example"
api2_url = "https://api.openweathermap.org/example"
```
try:
    response1 = requests.get(api1_url)
    data1 = response1.json()

    response2 = requests.get(api2_url)
    data2 = response2.json()

    print("API 1 Data:")
    print(data1)

    print("\nAPI 2 Data:")
    print(data2)

except Exception as e:
    print("Error:", e)
```
Explanation
Uses the requests library.
Connects to two APIs.
Retrieves weather information.
Handles connection errors using try-except.
Displays API responses.
Stage 2: Prompt for Comparing API Outputs
Student-Designed Prompt

Compare the outputs received from the two weather APIs. Highlight differences in temperature, humidity, and weather conditions. Present the comparison in a table format and mention possible reasons for variations.

AI-Generated Response
Parameter	API 1	API 2	Difference
Temperature	30°C	29°C	1°C
Humidity	65%	68%	3%
Condition	Sunny	Clear Sky	Similar
Explanation

Possible reasons for differences:

Different data collection sources.
Different update frequencies.
Different geographical reference points.
Different prediction algorithms.
Stage 3: Prompt for Generating Insights
Student-Designed Prompt

Based on the comparison results, provide meaningful insights and suggest actions that can improve the accuracy and reliability of the weather monitoring system.

AI-Generated Response
Insights:
Both APIs provide similar weather information.
Small temperature differences indicate acceptable variation.
Humidity values are closely matched.
Suggested Actions
Use the average value from both APIs.
Implement data validation checks.
Add a third API as a backup source.
Store historical data for trend analysis.
Generate alerts when API values differ significantly.
Evaluation of Prompt Effectiveness
Evaluation Method: Quality Analysis
| Stage               | Prompt Quality | Accuracy of Response | Completeness |
| ------------------- | -------------- | -------------------- | ------------ |
| API Code Generation | Excellent      | High                 | Complete     |
| Output Comparison   | Excellent      | High                 | Complete     |
| Insight Generation  | Excellent      | High                 | Complete     |

Reflection Note: 
What Worked Well?
The prompts were specific and clearly stated the requirements.
AI generated usable Python code with explanations.
Comparison prompts produced structured outputs.
Insight prompts generated actionable recommendations.
Challenges Faced
Some API URLs needed manual replacement with actual endpoints.
Additional prompt details may be required for advanced error handling.
Different AI tools may produce different coding styles.
How the Prompts Can Be Improved
Specify exact APIs to be used.
Request visualization charts for comparisons.
Ask for modular and reusable code.
Include requirements for database storage and reporting.
Request unit testing and documentation.
Conclusion

This exercise demonstrated how carefully designed prompts can guide AI tools to:

Generate Python code for API integration.
Compare outputs from multiple APIs.
Provide meaningful insights and recommendations.

Well-structured prompts result in more accurate, detailed, and useful AI-generated solutions, making them valuable for mini-projects and final-year project development.

# Result: The corresponding Prompt is executed successfully.
