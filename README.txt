Project Idea
The Easy Couple Compatibility Tracker is a tool designed to assess and analyze the compatibility between couples based on their responses to a series of questions. The tracker aims to provide valuable insights into various aspects of the relationship, helping couples understand their compatibility and identify areas for improvement.

Compatibility Tester
The compatibility tester consists of two main components: the Google Forms for collecting responses and the Python script for analyzing the responses and calculating compatibility scores.

Pseudo Working
Google Form Filling:

Separate Google Forms are created for females and males, each containing 30 questions divided into groups of 5 questions representing 6 main traits.
Each question in the form requires a response of either "Yes" or "No".
Upload Female CSV to Python:

After filling out the female form, the responses are exported to a CSV file.
The CSV file is then uploaded to the Python script for further processing.
In the Python script, "Yes" responses are converted to 1, and the sum of "1" is calculated for each row representing a female participant.
The average of the sums is then calculated to determine the compatibility percentage of females, stored as compatibility_female.
Upload Male CSV to Python:

Similarly, after filling out the male form, the responses are exported to a CSV file and uploaded to the Python script.
"Yes" responses are converted to 1, and the sum of "1" is calculated for each row representing a male participant.
The average of the sums is calculated to determine the compatibility percentage of males, stored as compatibility_male.
Calculate Couple Compatibility:

The average compatibility percentages of both males and females are combined to calculate the couple's compatibility.
The overall compatibility percentage is printed as couple_compatibility.
Provide Feedback:

Based on the calculated compatibility percentage, appropriate feedback is provided to the couple, highlighting areas of strength and areas for improvement in their relationship.
Usage
Fill out the Google Forms for both females and males with responses to the provided questions.
Export the responses to CSV files.
Run the Python script and upload the CSV files for analysis.
Review the compatibility percentage and feedback provided by the script.
Contributors
Yagnam Joshi
joshiyagnam@outlook.com
