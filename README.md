# Monster Trainer Management

## Objective

Develop a program to manage a team of monsters. Use arrays to store monster names and their corresponding attributes. Implement functionality to display the highest and lowest values for each attribute. Use loops to perform these operations efficiently.

## Requirements

### Data Storage

The program should use arrays to store:
- Monster names
- Corresponding attributes:
  - Speed
  - Attack Power
  - HP Level
  - Defense

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
- Include necessary headers (`<iostream>`, `<string>`, `<limits>`).

### 2. Define Variables

- Define arrays to store monster names and their attributes (Speed, Attack Power, HP Level, Defense).
- Define variables for the number of monsters, highest and lowest values for each attribute.

### 3. Initialize Arrays

- Initialize the arrays to store a fixed number of monsters (e.g., 30 monsters).

### 4. Find Highest and Lowest Attribute Values

- Use loops to find the highest and lowest values for each attribute and the corresponding monster names.

### 5. Display Results

- Display the highest values and lowest values for each attribute, and all monster names with their corresponding attributes.

## Example User Interaction

```plaintext
*******************************
*    Monster Trainer Manager   *
*******************************

Enter the number of monsters: 3

Enter monster 1 name: Dragoon
Enter monster 1 speed: 85
Enter monster 1 attack power: 90
Enter monster 1 HP level: 78
Enter monster 1 defense: 88

Enter monster 2 name: Phoenix
Enter monster 2 speed: 90
Enter monster 2 attack power: 95
Enter monster 2 HP level: 80
Enter monster 2 defense: 85

Enter monster 3 name: Hydra
Enter monster 3 speed: 78
Enter monster 3 attack power: 88
Enter monster 3 HP level: 82
Enter monster 3 defense: 80

Team Attributes:
Highest Attribute Values:
Speed: 90 (Phoenix)
Attack Power: 95 (Phoenix)
HP Level: 82 (Hydra)
Defense: 88 (Dragoon)

Lowest Attribute Values:
Speed: 78 (Hydra)
Attack Power: 88 (Hydra)
HP Level: 78 (Dragoon)
Defense: 80 (Hydra)

All Monsters and Attributes:
Dragoon: Speed: 85, Attack Power: 90, HP Level: 78, Defense: 88
Phoenix: Speed: 90, Attack Power: 95, HP Level: 80, Defense: 85
Hydra: Speed: 78, Attack Power: 88, HP Level: 82, Defense: 80
```
## Submission Details

### 1. Complete the project and ensure it is bug-free.

### 2. Add the completed project to your GitHub repository.

### 3. Submit the link to your repository through your program dashboard to continue the program.

### 4. A code review will be processed once the submission is received.
