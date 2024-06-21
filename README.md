# Monster Trainer Management

## Objective

Develop a program to manage a team of monsters using static arrays. Use a 2D array to store monster attributes and a 1D array to store monster names. Implement functionality to display the highest and lowest values for each attribute. Use loops to perform these operations efficiently.

## Requirements

### Data Storage

The program should use:
- A 1D array to store monster names
- A 2D array to store corresponding attributes:
  - Speed
  - Attack Power
  - HP Level
  - Defense

### Monster Data

Use the following table to initialize the arrays:

| Monster Name | Speed | Attack Power | HP Level | Defense |
| :----------: | :---: | :----------: | :------: | :-----: |
| Dragoon      |  85   |      90      |    78    |    88   |
| Phoenix      |  90   |      95      |    80    |    85   |
| Hydra        |  78   |      88      |    82    |    80   |
| Griffin      |  82   |      85      |    79    |    84   |
| Cerberus     |  88   |      92      |    81    |    86   |

### Functionalities

The program should implement the following functionalities:
- Display the highest and lowest values for each attribute along with the monster names.
- Display all monster names with their corresponding attributes.

### Display

The program should display:
- The highest and lowest values for each attribute with monster names.
- A list of all monsters with their corresponding attributes.

## Steps

### 1. Set Up Project

- Create a new C++ project and set up your development environment.
- Include necessary headers (`<iostream>`, `<string>`).

### 2. Define Variables

- Define a 1D array to store monster names.
- Define a 2D array to store monster attributes (Speed, Attack Power, HP Level, Defense).

### 3. Initialize Arrays

- Initialize the arrays with the provided monster data.

### 4. Find Highest and Lowest Attribute Values

- Use loops to find the highest and lowest values for each attribute and the corresponding monster names.

### 5. Display Results

- Display the highest values and lowest values for each attribute, and all monster names with their corresponding attributes.

## Example User Interaction

```plaintext
*******************************
*    Monster Trainer Manager   *
*******************************

Team Attributes:
Highest Attribute Values:
Speed: 90 (Phoenix)
Attack Power: 95 (Phoenix)
HP Level: 82 (Hydra)
Defense: 88 (Dragoon)

Lowest Attribute Values:
Speed: 78 (Hydra)
Attack Power: 85 (Griffin)
HP Level: 78 (Dragoon)
Defense: 80 (Hydra)

All Monsters and Attributes:
| Monster Name | Speed | Attack Power | HP Level | Defense |
| :----------: | :---: | :----------: | :------: | :-----: |
| Dragoon      |  85   |      90      |    78    |    88   |
| Phoenix      |  90   |      95      |    80    |    85   |
| Hydra        |  78   |      88      |    82    |    80   |
| Griffin      |  82   |      85      |    79    |    84   |
| Cerberus     |  88   |      92      |    81    |    86   |
```
## Submission Details

### 1. Complete the project and ensure it is bug-free.

### 2. Add the completed project to your GitHub repository.

### 3. Submit the link to your repository through your program dashboard to continue the program.

### 4. A code review will be processed once the submission is received.
