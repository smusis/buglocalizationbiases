buglocalizationbiases
=====================
This project is related to paper "Potential Biases in Bug Localization: Do They Matter?", which was accepted at the 29th IEEE/ACM International Conference on Automated Software Engineering (ASE), Vasteras, Sweden. Paper is available at : <a href="http://media.wix.com/ugd/775ac2_667c425ffca74c0db6d76966358fcc03.pdf">Biases in Bug Localization</a>

Description of files & folders: 

Fully Localized.xlsx - Fully Localized contains bug ids for which all the buggy files are specified in the bug report.

Partially Localized.xlsx - Partially Localized contains bug ids for which some of the buggy files are specified in the bug report.

Not Localized.xlsx - Not Localized contains bug ids for which none of the buggy files are specified in the bug report.

All the above three files contain bug ids from the projects: Apache HTTPClient, Apache Jackrabbit and Apache Lucene. 

OldNewCommits.csv - Contains all the buggy and bug-fix commits 
Format:
New (Bug-fix) Commit, Old (Buggy) Commit, Bug Id, Project

BugReports - All the bug reports