### Hands-on Activity: Creating and Merging a Pull Request

To successfully complete the activity, attendees must perform the following steps:

1. **Clone the Repository**  
   - Fork the main repository to your GitHub account.  
   - Clone the forked repository to your local machine using:  
     ```bash
     git clone <your-forked-repo-url>
     ```

2. **Create a New Branch**  
   - Create a branch using your roll number as the branch name:  
     ```bash
     git checkout -b <your-roll-number>
     ```

3. **Add a New File**  
   - Navigate to the project directory and add a specific file (e.g., `your-roll-number.py`):  
     ```bash
     print("your-email-address")
     ```  
     - Replace `<your-email-address>` with your actual email.  

4. **Stash apply and Commit Changes**  
   - Stage the new file:  
     ```bash
     git add <your-roll-number>.py
     ```  
   - Commit the changes with a meaningful commit message:  
     ```bash
     git commit -m "Added file for email <your-roll-number>"
     ```

5. **Push Changes to Your Branch**  
   - Push the branch to your forked repository:  
     ```bash
     git push origin <your-roll-number_new>
     ```

6. **Create a Pull Request**  
   - Go to the original repository on GitHub.  
   - Click **Compare & Pull Request** for your branch.  
   - Add a description summarizing your changes and submit the pull request.

7. **Wait for Review and Merge**  
   - The pull request will be reviewed by the instructor or team.  
   - Once approved, it will be merged into the main repository.  

---

### Completion Criteria
- The pull request should include the correctly named file `<your-roll-number>.txt`.
- The file must contain your name, roll number, and a short introduction.
- The branch name must match your roll number.
- The pull request must not have merge conflicts with the main branch.
