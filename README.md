
# Assignment 1 - FIT5222 Planning and automated reasoning

## Assignment 1: Flatland Challenge

In this assignment, your job is to schedule a set of trains through a railway network. You need to coordinate every train from its starting station to its destination as quickly as possible, while ensuring that each path is collision-free.

The assignment has three sections, in increasing order of difficulty. The amount of points relative to each question is stated in the question heading. A passing grade is 50%.

Before starting the assignment, make sure to:
- Watch the introductory video on Moodle
- Read the Introduction to Flatland documentation
- Update your flatland code and installation:
  - Under flatland folder, run `git pull`
  - Run `python setup.py install`
  - Run `python -m pip list` and ensure the flatland-rl version is updated to 2.2.4

Instructions to get the code base (in the `assignment1_2024` branch of the piglet repo) for the assignment are in the Introduction to Flatland documentation.

When the contest server is ready, you will see your score upon submission.

### QUESTION 1: Warm up (15 points)

In this question, you need to route each train independently from all the rest. Collisions are not possible, and there is no time dimension.

You need to implement a successor function for the Flatland domain and choose an algorithm to find the paths.

Your solution will be evaluated on 40 evaluation instances (only staff have these instances) with a 2-hour time limit, and each instance has 1 agent. Your score will be calculated based on the sum of individual costs (SIC) and success rate, compared to an optimal solution implemented by the teaching team.

Your final score will be calculated as `(p_score / p_optimal) * 15`.

### QUESTION 2: Easy mode (25 points)

In this question, you need to route each train individually while avoiding collisions with all the rest. You are given start and target locations, as well as a set of existing paths for trains that are already moving.

You need to modify your successor function to account for time, and handle the situation where the search algorithm fails to find a feasible solution due to dynamic obstacles.

Your solution will be evaluated on 56 instances with a 2-hour time limit, and your score will again be computed as the sum of individual path costs (SIC) and compared to the best solution from students (and staff).

Your score will be calculated as `(SIC_optimal / SIC_yours) * 25`, where `SIC_optimal` is the best solution from students (and staff).

### QUESTION 3: Challenge (60 points)

In this question, you need to route all the trains simultaneously in a way that is collision-free. Each agent has an expected arrival time, and late arrival will result in a penalty.

You also need to implement the `replan` function to handle agent malfunctions during execution.

Your solution will be evaluated on 56 instances with different difficulty levels in 2 hours, and your score will again be computed as the sum of individual path costs (SIC) and compared to the best solution from students (and staff).

Your score will be calculated as `(0.5 * (SIC_baseline / SIC_yours) + 0.5 * (SIC_advanced / SIC_yours)) * 60`, where `SIC_baseline` and `SIC_advanced` are the baseline and advanced implementations, respectively.

### Report (50 points)

You need to create a report that describes your approach to each of the questions. This includes a textual description of your approaches, why you adopted that particular approach, and a thorough discussion along with any supplementary material required (such as pseudo-code, images, graphs, tables, etc.).

The report will be marked based on the following rubric:

| Criteria | N (0%-49%) | P (50%-59%) | C (60%-69%) | D (70%-79%) | HD (80%-100%) |
| --- | --- | --- | --- | --- | --- |
| Description of your approach (35 points) | Incomplete or insufficient description of the approach and/or pseudo-code | High-level description of the approach and pseudo-code | + Discussion and algorithmic analysis. E.g., time, space, completeness, optimality. | + Reflections: advantages and disadvantages of your approach(es) | + Numerical experiments, analysing the efficiency of your implementations (e.g. on standard benchmarks 

# FIT5222 Planning and automated reasoning Assignment 1

# 程序代做代写 CS编程辅导

# WeChat: cstutorcs

# Email: tutorcs@163.com

# CS Tutor

# Code Help

# Programming Help

# Computer Science Tutor

# QQ: 749389476
