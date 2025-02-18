**ACTIVITY 1**

**1. The repository name is AppDev with a file containing the Activity1.java following template:**

// ACTIVITY1.JAVA

public class Activity1 {
    public static void main(String[] args) {
        System.out.println("List of Students:");
    
        // Collaborators: Add your names below using the format:
        // System.out.println("Your Full Name");
    }
}

**2. The Repository Link provided to the students:**
https://github.com/JUNTABIOSGIT/AppDev

**3. The student Collaborators will Fork the Repository**
The student collaborators should:
Click on Fork at the top right of the repository page.
This will create a copy under their own GitHub account.

**4. The Student Collaborators will Clone Their Fork Locally**
Student should clone their forked repository using:
git clone https://github.com/THEIR_USERNAME/AppDev.git
cd AppDev

**5. The student Collaborators Add Upstream Remote**
To keep their fork in sync with your repository:
git remote add upstream https://github.com/JUNTABIOSGIT/AppDev.git

**6. The student Collaborators Create a Branch Using Their Last Name**
The student should create a new branch using their last name in lowercase:
git checkout -b <their_last_name>
Example:
git checkout -b cruz

**7. The student Collaborators Edit Activity1.java**
The student will Open Activity1.java and add their name at the end, like this:
**System.out.println("Juan Cruz - BSIT 2C");**
Save the file.

**8. Collaborators Commit and Push Changes**
git add Activity1.java
git commit -m "Added name: juan Cruz"
git push origin cruz

**9. The student Collaborators Create a Pull Request (PR)**
On GitHub, Go to Pull Requests > New Pull Request.
Select JUNTABIOSGIT/AppDev as the base and their branch (using your last name) as the compare.
Create the PR and mention their full name.

**10. The Repository owner (PROF) will Review and Merge the PRs**
On gitHub repository by clicking the Pull Requests tab.
Review each PR to ensure they followed the instructions.
Merge the PR if correct. Request changes if needed.

**11. The student Collaborators will Sync Their Forks**
After merging by the repository owner, they should update their fork:
git checkout main
git pull upstream main
git push origin main

**12. Example of Activity1.java After Several Additions:**

public class Activity1 {
    public static void main(String[] args) {
        System.out.println("List of Students:");
     
        // Collaborators: Add your names below using the format:
        // System.out.println("Your Full Name");
    
        System.out.println("Juan Crus - BSIT 2C");
        System.out.println("John Doe - BSIT 2D");
        System.out.println("Jane Smith - BSIT 2A");
    }
}

**13. Important Notes:**
Ensure each student collaborators uses last name in lowercase for the branch name.

**14. Summary of activities**
update Activity1.java in AppDev.
repository link: https://github.com/JUNTABIOSGIT/AppDev.
Review and merge pull requests, ensuring branch names are correct.
Communicate instructions clearly to avoid conflicts.
