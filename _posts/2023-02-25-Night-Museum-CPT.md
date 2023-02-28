---
title: CPT Writeup
toc: true
layout: post
description: Night of the Museum
categories: [markdown]
---

## 3a

3ai: This program presents a interactive platform that users can enter their goals (along with their difficulty and date) to help improve fitness by people attracting goals

3aii: The program allows the user to enter in the goals using a form, where they have to enter in key values (The goal name, date, and difficulty), where it is then saved and displayed in a table. If there is nothing present in any of the values, the program will prompt the user to fill in all variables before filling in.

3aiii: The inputs of the program are what the user types into the form, where the Difficulty must be an integer whle the Goal and Date are strings. Upon clicking the "Create" button, the program is ran and subsequently adds all of the users data to a list of goals (that is stackable) and is displayed in a table right below.

## 3b

3bi & ii:

The user's inputs are stored as a list in the database, where that said list is then sent to be displayed in the table in the frontend

![]({{ site.baseurl }}/images/InfoDB.png)

![]({{ site.baseurl }}/images/Calling.png)


3biii: The list being used in the code here is identified as "ResultContainer." The data represented in this list is formatted into the table for the visible eye to see.

## 3c

3c: There is simply only a single list being used here, and that is the Database that stores all of the information that is used, in the code, this is known as "ResultContainer." This manages the complexity by making sure that only valid responses are being recorded into the table and prevents confusion. Additionally, the specificity for each of the cateogires prevents confusion and therefore also manages complexity. Additionally, there are more parts that manage complexity, such as Modularity: The code is divided into functions with specific tasks, such as read_goal(), createGoal(), and add_row(), which makes it easier to understand and maintain.

![]({{ site.baseurl }}/images/real.png)

3c(iii): This function, keep in mind, is used from the list that is created with the backend data (as shown in images above) and uses that to convert into the table with the according variables.


## 3d

![]({{ site.baseurl }}/images/Procedural.png)

As shown from the code, this function is known to the program as "add_row" and is applied to the button that creates said data. The function will intake all of the user's inputs, and after the backend has it, will post it as a part of the table.
This program also has selection by giving options between whether formatting is valid or invalid, and iterates by checking whether any progress has been made to satify these requirements, which is then put as a sequence.

![]({{ site.baseurl }}/images/Grading.png)










