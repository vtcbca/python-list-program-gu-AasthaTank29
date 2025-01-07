# ✨ LIST-PROGRAM ASSIGNMENT GUIDE ✨

This repository contains exercises related to **Python Lists**. Please follow the instructions carefully to complete your assignments and participate in peer reviews.

---

## ❓ ISSUE CREATION

If you have any queries related to the program or assignment, please create an **Issue** in this repository. Follow the guidelines below when creating an issue:

1. **Issue Title**:
   - Use the format `Assignment-1`, `Assignment-2`, etc., as the prefix for the issue title.

   Example:
   ```
   Assignment-1: Unable to understand list indexing
   ```

2. **Description**:
   - Provide a clear and detailed description of your query or problem.
   - Include code snippets, screenshots, or error messages if applicable.

   Example:
   ```
   I'm having trouble understanding how negative indexing works in Python lists. Here's my code:

   ```python
   my_list = [10, 20, 30, 40]
   print(my_list[-1])
   ```

   The output is correct, but I don't understand why it's fetching the last element.
---

## 📊 PEER CODE REVIEW

As part of this assignment, **review the code of 5 other students**. Follow the steps below:

### 1. **Pull Request Workflow**
- When a student submits their assignment, they should create a **Pull Request** from their branch to the main branch.
- Peer reviewers can then:
  - Review the code changes.
  - Leave line-by-line comments on specific parts of the code.
  - Ask questions as part of their review.

### 2. **Instructions for Reviewers**

#### Review the Code:
- Use the "Files changed" tab in the Pull Request to view the submitted code.
- Identify areas where you have questions, need clarification, or see room for improvement.

#### Leave Comments or Questions:
- Click the **+** icon next to a specific line of code to add a comment.
- In the comment, ask questions like:
  - "Why did you choose this approach?"
  - "Can you explain how this part of the code handles edge cases?"
  - "Would a different algorithm work here? Why or why not?"

#### Example:
```markdown
I noticed that you're using a `while` loop here. Could you explain why you chose it over a `for` loop? Are there any specific advantages in this case?
```

#### Submit the Review:
- After adding comments, click **Review changes** and submit your review. You can:
  - Approve the PR.
  - Request changes.
  - Leave it as a general comment.

### 3. **Instructions for Reviewees**

#### Respond to Questions:
- Review the comments left by the reviewer in the Pull Request.
- Reply to each comment directly by clicking **Reply** under the specific question.

#### Example Response:
```markdown
I used the `while` loop because the number of iterations depends on user input, which is not fixed. A `for` loop wouldn’t work well in this scenario.
```

#### Make Changes if Needed:
- If the reviewer suggests changes, update your code and push the changes to the same branch. The PR will automatically reflect the updates.

---


