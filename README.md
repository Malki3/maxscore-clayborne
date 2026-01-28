# README for Maxscore Validation Script

## Author Information
- **Name:** Malcolm Clayborne
- **Course:** CPSC-298-01
- **Assignment:** Maxscore Assignment
- **Date:** 01/27/25

## Program Description
This script prompts the user to enter five numerical scores and determines the highest score entered. It stores the scores in an array and compares each value to find the maximum. The script then displays the highest score and shows how much each score differs from that maximum.

## Usage
To run the script interactively:
```bash
./maxscore.sh
```

To test with the provided input file:
```bash
./maxscore.sh < maxscore-input
```

## How the Script Works
The script first creates an empty array and asks the user to input five scores, storing each value in the array. It initializes the maximum score using the first value and then uses a for loop to compare each subsequent score to the current maximum, updating it when a higher value is found. Finally, another loop calculates and prints the difference between each score and the highest score.

## Testing Results
[Describe your testing process and results. Include:]
- Example successful inputs and results
- How you used the maxscore-input file to test

## Challenges and Solutions
[Optional: Describe any challenges you encountered while creating this script and how you solved them. This could include debugging issues, arrays, or Git workflow problems.]

## Resources
[List any resources you used (class slides, ChatGPT, etc.). Please refer to the course syllabus for more details on citations.]

## License
This project is part of coursework for Chapman University and is intended for educational purposes.
