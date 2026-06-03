# Git & GitLab Practical Assignment

## Student Details

- Name: Abbas Baniyan
- Repository: git-practice-task

## Task 1: Create GitHub Repository

### Description
Created a GitHub repository named **git-practice-task** and initialized it with a README file.

---

## Task 2: Clone Repository

### Description
Cloned the repository to the local machine using Git Bash and opened it in VS Code.

<img width="1466" height="843" alt="Screenshot 2026-06-04 013945" src="https://github.com/user-attachments/assets/a78251c9-d73e-4159-941d-fba14bad58ad" />

##Task 3:Create Feature Branches (Feature-A and Feature-B)
Description

Created two separate branches named feature-A and feature-B from the main branch. Added and modified the index.html file in both branches, committed the changes, and pushed the branches to the remote GitHub repository.

Commands Used for Feature-A
git checkout -b feature-A
git add .
git commit -m "Added index.html in Feature A"
git push origin feature-A
Commands Used for Feature-B
git checkout main
git checkout -b feature-B
git add .
git commit -m "Modified index.html in Feature B"
git push origin feature-B

<img width="1550" height="897" alt="Screenshot 2026-06-04 014316" src="https://github.com/user-attachments/assets/ec550f2c-8630-4bd8-bd76-dae80b3450d3" />

<img width="890" height="717" alt="Screenshot 2026-06-04 015048" src="https://github.com/user-attachments/assets/ec9d7049-7e69-45a2-a8c5-4453e4972650" />
<img width="944" height="727" alt="Screenshot 2026-06-04 015101" src="https://github.com/user-attachments/assets/712bf8c3-334b-48a2-8d42-e6b5fe0812e8" />

##Task 5: Create Pull Requests for Feature-A and Feature-B
Description

Created Pull Requests for both feature-A and feature-B branches to merge their changes into the main branch. The Pull Requests were reviewed before merging.

Pull Request 1 (Feature-A)
Source Branch: feature-A
Target Branch: main
Title: Added index.html in Feature A
Pull Request 2 (Feature-B)
Source Branch: feature-B
Target Branch: main
Title: Modified index.html in Feature B
<img width="918" height="342" alt="Screenshot 2026-06-04 022928" src="https://github.com/user-attachments/assets/580a40ae-048f-4563-9d3f-16147479f20f" />


##Task 6: Merge Feature-A Pull Request
Description

Merged the Feature-A Pull Request into the main branch after reviewing the changes. This ensured that the new index.html file was successfully integrated into the main branch.

Steps Performed
Opened the Pull Request created from the feature-A branch.
Reviewed the changes made in the branch.
Clicked Merge Pull Request.
Confirmed the merge operation.
Verified that the changes were successfully merged into the main branch.
<img width="945" height="324" alt="Screenshot 2026-06-04 052022" src="https://github.com/user-attachments/assets/3bb054ed-3ad1-42d6-ad45-d5daee558495" />
<img width="886" height="425" alt="Screenshot 2026-06-04 052039" src="https://github.com/user-attachments/assets/611a6432-28e8-4d75-bb3a-da0adb0efaef" />

##Task 7: Merge Conflict Generation
Description

A merge conflict was intentionally created between the feature-B branch and the main branch. Both branches contained changes to the same file (index.html), which resulted in a conflict during the merge process.

Steps Performed
Modified the index.html file in the feature-A branch.
Modified the same index.html file differently in the feature-B branch.
Merged the feature-A branch into main.
Created a Pull Request for feature-B.
GitHub detected a merge conflict because both branches modified the same lines of code.
<img width="1550" height="897" alt="Screenshot 2026-06-04 014316" src="https://github.com/user-attachments/assets/77557c45-ce8e-42ae-917f-7e6d42d5be14" />

##
