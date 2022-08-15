# healthapp
Build Web App with Microsoft Azure

Step-1: Open a web browser and navigate to "portal.azure.com/#home" and then login with your credentials.

Step-2: You can see a home page once you logged in, Now go to "create a resource".

Step-3: Click on "Web App", It is just an App Service App.

Step-4: In the create page specify your Resource Group, app Service Plan and the App you want.

Step-5: Click "Apply" followed with "Review and Create", then review the details and finally click "Create".

Step-6: Reach the Management page of your new app service app by clicking "Go to Resource".

Step-7: The splash page opens by clicking on your App URL

Step-8: Deploy your code files and copy the HTTP clone URL from Github.

Step-9: Clone your Github repository from Azure Cloud Shell Terminal.

Step-10: Execute the following commands in Azure Cloud Shell Terminal

git config --global user.email ""

git config --global user.name ""

cd

Step-11: Initialize the git repository by:

git init

Step-12: Add the files through the command:

git add . (or) git add

Step-13: Commit the file using the following command:

git commit -m "Project"

Step-14: For deployment the command is:

az webapp deployment source config-local-git --name --resource-group

az web deployment list-publishing-credentials --name --resource-group

Step-15: The final step,

git remote add azure '

git push azure master

Step-16: The code is deployed, now open the Azure app link and refresh the page

The Web App has been Deployed
