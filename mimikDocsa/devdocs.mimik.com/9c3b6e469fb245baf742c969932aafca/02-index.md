---
title: "Getting the edgeEngine license and Identity server values from mimik Developer Portal"
metaTitle: "Learn how to get the edgeEngine license and Identity server values from mimik Developer Portal"
metaDescription: "License and identity server"
seo: "mimik, edge, edgeEngine, tutorial, microservice, software development, license server, identity server"
---

# Objective

The objective of is tutorial is to demonstrate how to get an edgeEngine license and values for the mimik Identity server from the mimik Developer Portal web page.

# Intended Readers

The intended readers of this document are developers who will be doing application development on the iOS or Android platforms.

# What You'll Be Doing

Starting an edgeEngine Runtime instance requires a license. This is a developer-specific, non-expiring edgeEngine license that works with the edge projects registered by the developer.

In this tutorial you'll learn how to get a **edgeEngine License** and a URL to mimik **Identity server** from the mimik Developer Portal. Also, you'll learn how to get a **Client ID** and a **Developer ID**.

# Getting the edgeEngine license and Identity server values from mimik Developer Portal

 
**Step 1:** In a separate web browser, go to the Developer Console by clicking on the link below:

[https://console.mimik.com/](https://console.mimik.com/)

---

**Step 2:** You will be presented with the mimik Developer login dialog. If you don't have a developer account, create one on mimik by clicking the **Create Account** button as shown in the illustration below.

![Developer Account](../images/tutorials/quickstart/create-account-01.png) 

Then enter your email address and password. Confirm your password and click the Create Account button as shown in the figure below.

![Create Account](../images/tutorials/quickstart/create-account-02.png) 

Otherwise, log in by entering the email address and password pair associated with your Developer account. Once you have a mimik account, you'll need to create a mimik Project.

---

**Step 3:** Get the URL to the Identity Server and the Edge License

Click the **Edge Projects** tab on the left side vertical menu bar. The Identity server (mID) and Edge License will appear.

![mID and License](../images/tutorials/iOS-01/iOS-edgeEngine-license.png)

To get the URL to the Identity Server (mID), click the copy icon on the right side of the section titled Identity Server (mId) as shown in the figure above. Paste that value to a safe location.

To get the Edge License, click the copy icon on the right side of the section titled Edge License. Also, paste that value to a safe location.


# Create a mimik Project


**Step 4:** Register a new edge project at the mimik Developer Portal

Developers need to create a new edge Engine project in order to generate their **developer ID Token**.

A mimik Project is a mechanism you'll use to organize your edgeEngine microservices together. The following steps show you how to create a mimik Project.

---

**Step 5:** In the mimik Developer Console, you can choose to create an Edge Project or a Hybrid Project. The scope of this track is to create an Edge Project. Click the block for Edge Project as shown at callout (1) in the figure below.

![Create Project](../images/tutorials/quickstarts/../quickstart/select-edge-project.png)

The dialog to create a new Edge project will appear.

---

**Step 6:** Enter the name of the project in the  **Project Name** text box and then click the Create button as shown in the figure below.

![Enter project name](../images/tutorials/quickstart/new-project-01.png)

Next, you'll create a Client ID and a Developer ID token.


# Getting the developer ID Token and client ID from mimik Developer Portal

A **developer ID Token** is generated from within the edge projects that a developer registers from within the mimik Developer Portal. By selecting a particular edge project developer gains access to the **developer ID Token** generator tool. As well as the **client ID**. These values are specific to the selected edge project.

The process of generating the Access Token that's used for various APIs within the mimik Client Library is shown in the illustration below:

---

**Step 7a:** Create the Client ID and Developer ID token.

Enter the new project you created. You'll see fields for Client ID and Get ID Token as shown in the figure below.

![Developer ID Token](../images/tutorials/iOS-01/iOS-dev-id-token.png)

**Step 7b:** Get the Client ID**

Click the copy icon to the right of the Client ID field to copy the Client ID. Paste that value to a safe location.

**Step 7c:** Get the Developer ID token

Click the button labeled, `Get ID Token` as shown at the right of the figure above. This will generate the Developer ID token. Click the copy icon to copy the Developer ID Token. Paste the Developer ID token to a safe location for later use.