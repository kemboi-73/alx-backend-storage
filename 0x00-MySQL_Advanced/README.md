# MySQL Advanced - Overview

This repository contains a set of MySQL scripts and tasks designed to enhance your skills in advanced MySQL concepts. Each task focuses on specific aspects of database management, SQL scripting, and optimization. Below is an overview of the tasks and their corresponding descriptions:

## Curriculum Overview

### 0x00. MySQL Advanced

#### 0. We are all unique!
- **Objective**: Create a table named `users` with specific attributes, constraints, and uniqueness.
- **Skills Gained**: Understanding table creation, uniqueness, and attribute constraints.

#### 1. In and not out
- **Objective**: Create a table named `users` with additional attributes, including an enumeration of countries.
- **Skills Gained**: Working with table attributes and enumerations.

#### 2. Best band ever!
- **Objective**: Rank the country origins of bands based on the number of fans.
- **Skills Gained**: Importing data, querying, and ordering results.

#### 3. Old school band
- **Objective**: List bands with Glam rock as their main style, ranked by their longevity.
- **Skills Gained**: Handling data with specific styles and calculating lifespan.

#### 4. Buy buy buy
- **Objective**: Create a trigger that decreases the quantity of an item after adding a new order.
- **Skills Gained**: Implementing triggers for data integrity.

#### 5. Email validation to sent
- **Objective**: Create a trigger that resets the attribute `valid_email` only when the email has been changed.
- **Skills Gained**: Using triggers for email validation.

#### 6. Add bonus
- **Objective**: Create a stored procedure `AddBonus` to add a new correction for a student.
- **Skills Gained**: Working with stored procedures.

#### 7. Average score
- **Objective**: Create a stored procedure `ComputeAverageScoreForUser` to compute and store the average score for a student.
- **Skills Gained**: Advanced stored procedure usage.

#### 8. Optimize simple search
- **Objective**: Create an index `idx_name_first` on the table `names` for optimizing simple searches.
- **Skills Gained**: Implementing index for performance improvement.

#### 9. Optimize search and score
- **Objective**: Create an index `idx_name_first_score` on the table `names` for optimizing searches based on name and score.
- **Skills Gained**: Advanced indexing for improved search and score queries.

#### 10. Safe divide
- **Objective**: Create a function `SafeDiv` to safely divide two numbers or return 0 if the second number is 0.
- **Skills Gained**: Writing SQL functions for safe operations.

#### 11. No table for a meeting
- **Objective**: Create a view `need_meeting` listing all students with scores under 80 and no recent meeting.
