Welcome, my name is Dwight and in this ReadMe, I'll discuss how I went about building my website
using the <span><a href="https://cloudresumechallenge.dev/">Azure Resume Challenge</a></span>.
This project entails creating a Static Webpage in Azure using Blob Storage and incorporating several Networking principles. Overall, it is a process that encopasses 4 subjects: the front end building of what you see when you actually navigate to <span><a href="https://dwightjohnson.net">www.dwightjohnson.net</a></span>, the backend Azure Blob Storage, the DNS configuration between my Azure resources and the purchased custom domain (Thanks GoDaddy) via Azure Front Door and a CDN profile, and finally the CI/CD relationship created in GitHub to make any changes an automated process.

My journey in completing this project involved several tries and an eventual several month mental break before completing it as shown in the age of the some of the files and folders uploaded to this GitHub repository. I would say that from the start of this attempt to the actual completion of what you see right now was about 4 hours of work including all the waiting times of resources populating in Azure and the Domain Server. Everything is completed in the Azure Portal, Visual Studio Code, and GitHub mainly.

The process of completing the project to where I did involves the following:
1. Creating a HTML/CSS frontend website (Granted, this isn't much heavy lifting as the focus is moreso on the backend structure). The style and formatting was borrowed from <span><a href="<span><a href="https://cloudresumechallenge.dev/">A Cloud Guru</a></span>'s version of completing this project.
2. Deploying an Azure Static Website which is generated via Azure Blob Storage. This is where the real meat of the project stems. Being able to create this portion of the project in the Azure portal, CLI or PowerShell commands, or even Terraform was the quickest portion to complete but was fun to learn as there are obviously different ways to complete this portion to show my own versitility in navigating creating and customizing services in Azure.