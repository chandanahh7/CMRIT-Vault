# <img width="50" height="50" alt="book_icon" src="https://github.com/user-attachments/assets/5447f3d4-2290-451a-b37d-2e1a4940ec97" />  CMRIT-Vault 


## Objective
CMRIT-Vault is an open-source repository of academic files for CMRIT college students. These resources include lecture notes, question papers, course projects, study materials, tutorial solutions, etc. This repository aims to crowdsource said resources from the student body and create a common reference point to access academic resources. 

## Project Structure
This repository has been designed to ensure maintainability and accessibilty. It aims to provide simplicity and avoid overheads associated with maintainence edits and fixes.<br>

**Directory Structure**<br>
- ```CS``` Course Domain Prefixes such CS, CI, CD, AD, AI, IS, EC, EE, ME, etc.
  - ```BCS301_mathematics``` Course code and name joined with an underscore. Refrain from abbreviations.
     - ```exam_papers```
     - ```lecture_notes```
     - ```internal_assessment_papers```
         - ```2025_*``` File names should always start with appropriate year.
     - ```lab_sessions```
     - ```reference_materials```
     - ```misc``` Uncategorized Materials
    
## Directory Nomenclature
This repository follows a ```snake_case``` naming convention for directories throughout the project. No capital letters must be used. No exceptions. Course Domain and Course Code should be according to VTU model conventions.

## File Nomenclature
All filenames must have a unique and appropriate name to their files among the material.

## Contribution
All Contributions are welcome and it is advised to upload resources in an organized manner. While contributing please take care of the following points -

- Ensure that files are contributed to the exact folder where they belong.
- Ensure that no duplicates are being uploaded.
- In case of new courses, ensure that the contribution conforms to directory sturucture.
- Follow the above structure and nomenclature.
  
To contribute resources fork this repository and open a PR with the title ```Add resources [your github username]```. A project maintainer will guide you through the PR process suggesting modifications required (if any) to conform with the project guidelines. Please open an issue in case you want suggest an enhancement, file a bug report or reach out to the maintainers any queries.

Please keep in mind that material is obtained with the permission of the author or is declared free-to-use. If you see your material that belongs to you but you did not intend to share, please file an issue describing the situation and it will be taken down.

## How to Contribute
- Option - 1 : Fork and Upload.
   1. Fork this repository.
   2. Create a branch in ```YOUR FORKED REPO```.
   3. Upload files to that branch.
   4. Open a pull request from YOUR BRANCH to this repo.

- Option - 2 : Clone and PR
   If you have files larger than 100 Mb or not able to upload directly from browser you can use this method.
   ```Fork this repository```
   1. Clone your forked repository
      ```git clone https://github.com/Sivaani-Janaswamy/CMRIT-Vault.git```
   2. Create a branch in your local system with your branch name
      ```git checkout -b [name_of_your_new_branch]```
   3. Add materials
      ```git add . ```
   4. Commit changes
      ```git commit -m "add your message"```
   5. Push into the branch
      ```git push origin [name_of_your_new_branch]```
   6. Open a PR with the title ```Add resources [your github username]```

## Contributors

![Contributors](CONTRIBUTORS.svg)

