# Trip Planner Technical Exercise

This repository contains code for a WordPress block plugin that defines a 'trip planner' block, which can be added to a page or post from the block editor. It serves as the foundation for this technical exercise.

*Follow the setup instructions below. Do not submit your exercise as a pull request against this repository.*

## WordPress Environment

Instructions for running WordPress and seeing the block involved in this exercise are found in [trip-timer-plugin/README.md](trip-timer-plugin/README.md).


## Exercise Instructions

There are two parts to this exercise:

1. Performing a code review 
2. Modifying existing code

You will complete both parts in a GitHub repository that you create. Submission will be via a pull request and direct commit links.

We expect the total time to take between 30–90 minutes.

An optional extra credit task is available if you’d like to go further.


### 1. Performing a Code Review

Review the code as if this WordPress block were being added to our actively maintained block library. Evaluate it for accessibility, maintainability, documentation, and overall correctness. Leave comments with your suggestions, recommendations, and general assessment.

#### GitHub Setup
1. **Create a new repository** (do not fork this one).
2. **Create a `code-review` branch** and commit the assessment files to it.
3. **Open a pull request** from `code-review` into `main`.
4. **Review your own PR,** leaving comments on issues and potential improvements as you would in a real code review.


### 2. Modifying Existing Code

There is a bug in the existing code: after the timer counts down to zero, it continues into negative numbers. The expected behavior is to stop at zero and not display negative time.

For the modification portion of this exercise, your task is to fix this bug.

Please approach this as you would any production-ready code change.

#### GitHub Setup
> Make sure you have completed steps 1–5 of the **GitHub Setup** from the previous section.

1. **Create an `improvements` branch** from `main`.
2. **Commit the original assessment files to the `improvements` branch.** This will make your fixes clearly visible in the diff. 
3. **Make code improvments,** commit your changes, and push.

### Extra Credit

Our evaluation will focus primarily on your code review and bug fix. If you finish early and want an extra challenge, try enhancing the "Encouragement Area" of the countdown screen. Currently, it always says “Let’s go!” Update the message based on the following criteria:

- "Let's go!" by default.
- "Almost time to leave!" when 5-10 minutes remain.
- "Time to go!" under 5 minutes.

You are welcome to make any additional changes, fixes, or enhancements as you see fit.

#### GitHub Setup
> If you choose to complete the extra credit, continue working on the same `improvements` branch used in the previous section.

1. **Make your extra credit changes** directly on the `improvements` branch.
2. **Commit and push** your changes.

### Submitting Your Completed Exercise
When you're finished, add the send us the following:

1. **A link to your pull request** from `code-review` into `main`. 
2. **Links to your commits** on the `improvements` branch, with brief explanations of what you changed in each commit and why.
3. Include the total time it took you to complete the exercise.
4. **Ensure the repository is private** and that the GitHub reviewers, as provided in the email, have access.


## Disclaimers

*This application was written specifically as an interview exercise, and is not representative of our typical code.*
