# PowerAPI

### What is it?

PowerAPI provides graphical information based on Projects deployed on Azure DevOps. The information which is provided is useful to Managers to better understand the scenarios and to improve collaboration in coming sprints.

**Steps :**

[PowerAPI](https://adoanalytics.azurewebsites.net/)

**Login** using your Microsoft credentials to view details.

![LoginCropped](https://user-images.githubusercontent.com/76027933/102349409-4b588180-3fc9-11eb-83cd-87bdb9219ef4.png)

### Description on Content:

1. Actionable Items:

- Total “Open pull requests” in selected project.
- Open pull requests with ‘No reviewers’.

![image](https://user-images.githubusercontent.com/76027933/102451351-4db8eb00-405e-11eb-8bdd-5692544ec84c.png)

2. Project Pull Requests:
-	All Open PRs details
-	PR’s with conflicts
-	PR’s with “No Reviewer”

![image](https://user-images.githubusercontent.com/76027933/102451440-7e008980-405e-11eb-9283-090ee641383b.png)

3. Open Pull Request Age:

- 	Shows how many days a pull request is in Open state.

![image](https://user-images.githubusercontent.com/76027933/102451538-ad16fb00-405e-11eb-957e-bbf292e4ae83.png)

4. Collaboration Trends Pull Request:

- 	PR’s submitted by each team member in last 3 months.
![image](https://user-images.githubusercontent.com/76027933/102451620-d46dc800-405e-11eb-9562-5a9b08e6e5c3.png)

5. Month Wise New Work Vs Code Rework View: 

- 	It shows details about rework happened within the team in selected period.

**How we calculate Rework?**

- 	Default “Rework in No of Days” window is 25 days(Configurable).
-	Team can change “Rework in No of Days” to mutually agreed value.
- 	Rework calculation example: - Rework is an existing file modified on selected “from” and “To” date.
- 	New work calculation example: - New work is a new file added on selected “From date”.
![image](https://user-images.githubusercontent.com/76027933/102451855-4fcf7980-405f-11eb-8652-c218f91903be.png)

6. Commit efficiency by month for each language:

- 	It shows 2 months data on the files that are committed based on technology. (example: typescript, class, json, html, etc.)
![image](https://user-images.githubusercontent.com/76027933/102451920-742b5600-405f-11eb-9130-2665b727f2c4.png)

7. Active coding days:

-       It shows number of commits done by a team member based on ‘From date and To Date’
![image](https://user-images.githubusercontent.com/76027933/102451997-97560580-405f-11eb-90b5-59cfc0f00616.png)

