# **Exploring Serverless Computing and Cron Jobs in Azure, GCP, and GitHub**
---


# ☞ _**Deploying a Serverless Function**_
---

   - # 📌 GPC: Serverless Function
---

   - #### (1) Under the `Google Cloud Console`, I created a _**'Google Cloud Function'**_. See photos below for the steps, errors, and troubleshooting I performed to complete this section.
      
      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/1.jpg" alt="GCP" width="600" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/2.jpg" width="600" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/3%20-%20GCP%20error%20-%20API.jpg" width="400" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/5.jpg" width="400" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/6.jpg" width="400" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/7.jpg" width="500" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/8.jpg" width="500" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/10.jpg" width="600" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/11.jpg" width="600" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/12%20-%20hello%20raqs%20(successful%20execution).jpg" width="450" />.


   - #### (2) In this photo, I attempted to add 'Soriano' in the `last_name` field. However, I couldn't click the `RUN TEST` button. After multiple failed attempts to add the last_name, I opted to use only the first name. But, I persisted and tried again, only realizing after multiple attempts and troubleshooting that I had forgotten to add a comma (,) after typing 'Raqs' in the `firstname`. After this, I was able to run the test, the execution response appeared, and lastly, I deployed the test.
      
      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/16%20-%20%5BX%5D%20firstname%20only.jpg" width="650" /> ➙ ERROR

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/16%20-%20first%20%26%20lastname%20prob%20solved%20%26%20DEPLOY.jpg" width="650" /> ➙ ISSUE RESOLVED

   - #### (3) URL copied after deployment:
      
      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/17%20-%20copy%20URL%20(name).jpg" width="600" />.

   - #### (4) I opened `Google Colab` and followed the steps below:
      
      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/18%20-%20collab%20success.jpg" width="600" />.

   - #### (5) Going back to `Google Cloud Console` ➙ I navigaged to the newly created function `function-01` and click 'Code'. I copied Professor Hants' code from his GitHub repository under `HHA-504-2024` [gcp_function.py](https://github.com/hantswilliams/HHA-504-2024/blob/main/other/module5/gcp_function.py), and pasted it into my GCP `main.py`. See the photo below.
      
      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/19%20-%20copied%20cmds%20from%20professor.jpg" width="600" />.

   - #### _*Note:*_ The photo shown below is the error I encountered even before successfully resolving the issue in **step (2)**, which was forgetting to include a comma (,) after the _**systolic value**_ of "`130`"
      
      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/19%20-%20error%20-%20diastolic.jpg" width="600" />.

   - #### (6) After performing step (5), deploying `function-01` or 'the test' was successful, so I went ahead and copied the URL.
      
      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/20%20-%20copy%20url%20(BP).jpg" width="600" />.

   - #### (7) Same as in step (4) above, I opened `Google Colab`, followed the steps below, and the outcome was successful.🙂

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/GCP-functions/21%20-%20collab%20success%20(BP).jpg" width="700" />.


---

  - # 📌 Azure: Serverless Function
---
  
   - #### (1) Under the `Microsoft Azure` portal, I searched for the _**'Function App'**_. See the photos below for the steps I performed to complete this section.
      
      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/1.jpg" width="600" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/2.jpg" width="600" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/3.jpg" width="350" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/4.jpg" width="500" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/5.jpg" width="500" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/6.jpg" width="500" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/7.jpg" width="500" />

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/8%20-%20deployment%20section%20(Enable%20and%20Create).jpg" width="500" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/9%20Deployment%20Completed%201.jpg" width="650" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/9%20Deployment%20Completed%202.jpg" width="650" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/10.jpg" width="650" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/11%20-%20func%20overview%20%3A%3A%20CREATE%20in%20Azure%20Portal%20.jpg" width="650" />.

 - #### (2) Inside the **`Function App`**, I created an *'`HTTP trigger`'*, which I modified slightly by adding **"`Raqs Soriano`"** in the name field, and deployed the function, as shown below.
   
      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/12%20-%20HTTP%20trigger.jpg" width="500" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/13%20-%20Template.jpg" width="500" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/14%20-%20http%20trigger%20-%20overview.jpg" width="600" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/14%20-%20http%20trigger%20-%20successful.jpg" width="600" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/15%20-%20run%20input%201.jpg" width="350" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/15%20-%20output%201.jpg" width="350" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/16%20-%20run%20input%202.jpg" width="350" />.

      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/16%20-%20output%202.jpg" width="350" />.


 - #### (3) I attempted to test the function outside the Azure portal using **`Colab`** instead of Visual Studio Code.
     
      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/17%20-%20get%20func%20URL.jpg" width="660" />.


      <img src="https://github.com/raqssoriano/HHA504_assignment_functions/blob/main/Azure-functions/18%20-%20attempted%20in%20colab.jpg" width="650" />.



---

# ☞ _**Creating a Cron Job**_
---

  - # GitHub Actions
    
    - #### (1) Created a new GitHub repository named **[504-cron-job](https://github.com/raqssoriano/504-cron-job)** and opened my _**Visual Studio Code**_ and used the `git clone` command.


    - #### (2) Added a `requirements.txt` file, listing the necessary scripts/languages to complete to this assignment. I also added a `.venv` or virtual environment file.

        <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/1%20-%20soln%20to%20error%20(vsc).jpg" width="650" />.


    - #### (3) Created a new file named `.github` with a subfolder named `workflows`, containing a YAML file called **`pubmed_update.yaml`**. This file contains a _**scheduled task**_ that will be executed in a console.
      
        <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/2%20-%20yaml.jpg" width="650" />.


    - #### (4) Created a new file named **[pubmed_github_action.py](https://github.com/raqssoriano/504-cron-job/blob/main/pubmed_github_action.py)** containing a script that logs a _**scheduled task**_ to be executed in a console using GitHub actions.
      
        <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/3%20-%20pubmed%20file.jpg" width="650" />.


    - #### (5) I ran all scripts one at a time, encountering no errors until the final two lines: `email = resend.Emails.send(params)` and `print(email)`. I tried all available resources, I eventually ran out of options and felt so frustrated."
      
        <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/6%20-%20import%20-%20ok.jpg" width="400" />.

        <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/7%20-%20print-df.jpg" width="650" />.

        <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/8%20-%20pubmed.jpg" width="650" />.


    - #### *Note:* This is the part where I spent too much time troubleshooting due to repeated error messages like `API key is invalid` and other confusing errors. See the photo below that shows the error message I've been getting.
          
        <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/9%20-vsc%20-%20error%20-%20API.jpg" width="650" />.

        <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/11%20-%20github%20action3.jpg" width="650" />.


    - #### (6) Troubleshooting steps I have taken:
      
      - ran `pip install resend` command
      - checked for any punctuation errors and misspelled words
      - changed the email address included in the scripts inside `pubmed_github_action.py` file to match the one I used in GitHub
      - ensured that the `.env` file was created and contained the `API key` I received on the **Resend** website after creating a new account using my `stonybrook.edu` email. I also ensured that I copied the correct path in the `pubmed_action_github.py` file.
        
           ➙ This was prior to resolving the issue.
          <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/4%20-%20copy%20path%20to%20yaml.jpg" width="650" />


      - ensured that I created a repository secret containing my `RESEND_API_KEY`
          - [Creating an API Key through Resend](https://resend.com/home)
             <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/4%20-%20resend%20api%20key.jpg" width="650" />.
     
          - [Creating a repository secret in GitHub](https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/4%20-%20secret%20repository%20-%20api-key.jpg)
             <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/4%20-%20secret%20repository%20-%20api-key.jpg" width="650" />.
   
      - saved all changes to each file I modified, then used `git add`, `git commit -m "my commit message"`, and `git push`


    - #### (7) The latest update on troubleshooting the `**GitHub Action**` of the *Cron Job* section of this assignment after submitting it this morning (10/05/2024).
      
      - I have tried to change the path or link in [pubmed_github_action.py](https://github.com/raqssoriano/504-cron-job/blob/main/pubmed_github_action.py) where the data will be run using the GitHub action workflow of the [504-cron-job](https://github.com/raqssoriano/504-cron-job) repository. See the actions taken in the photos below, which I believe helped me successfully run the workflow in my GitHub repository. In the second photo, I slightly modified the scripts I have taken from my professor.

          <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/13%20-%201st%20soln.jpg" width="650" />.
        

          <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/13%20-%202nd%20soln.jpg" width="650" />.
        
      
      - After multiple attempts at troubleshooting each file in this repository and carefully checking for any mistakes I might have missed, I successfully ran the GitHub action workflow. You can see the results in the photos below.

          <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/12%20-%20pubmed%20github%20success.jpg" width="650" />.
        
        
          <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/12%20-%20pubmed%20-%20run%20data%20pipeline%201.jpg" width="650" />.
        

          <img src="https://github.com/raqssoriano/504-cron-job/blob/main/Cron%20Job/12%20-%20pubmed%20-%20run%20data%20pipeline%202.jpg" width="650" />.



---

# ☞ _**Exploring Functions as a Service (FaaS)**_
---

  - ### 📌 Benefits of FaaS in Azure & GCP:
     - ➙ Users, such as businesses or developers, write the code and provide the data, while Azure and GCP manage all the servers and infrastractures. FaaS platform like Azure Functions and Google Cloud Functions easily integrate with other cloud services from their respective providers--Azure & GCP.
     - ➙ Azure and GCP automatically adjust resources based on demand, so you only pay for the computing services you use.

  - ### 📌 Limitations of FaaS in Azure & GCP:
     - ➙ While Azure and GCP offer control over servers/infrastructures, users may have reduced flexibility when it comes to specific or larger configurations. I believe this limitation was also highlighted in the Microsoft Azure Virtual Training I attended last month, if I remember correctly.
     - ➙ If a business consistently runs applications at high volume, FaaS could be more expensive than traditional servers.
        
















