# **GitHub Enterprise Cloud**

[GitHub Enterprise](https://repo.roche.com) is a software development and version control using Git. It offers the distributed version control and source code management functionality of Git, plus its own features.

## Why use GitHub?

1.Setting up secure workflows  
2.Understanding the GitHub Flow  
3.Reviewing and discussing work  
4.Planning and tracking work  
5.Automating with GitHub Actions  
6.Integrating apps with GitHub  
7.Using the GitHub API  


## How to get Read Access

Reader access to GitHub can be provided to your team by subscribing to the group [GLOAZUGHAdmin_ReadOnly](https://gds-selfsubscription.roche.com/#/group/GLOAZUGHAdmin_ReadOnly).  
  
  **Note** : This group will be only used for Reader access and no other purpose, once innersource is enabled we will plug out this group and everyone would have the same access as this group by default.
  
  **Usage**: Once added you will have access to read internal respositories only of any organization in the enterprise
  

Remember to remove all non-platform people from the ldap groups you are managing.

## How to use AD group to manage members?

AD group prefix is provided to teams when they are onboarded into GitHub. Once the AD group is made, it  needs to go through a one time sync so that they are synced into GitHub, once that is done we can visit our organization and go to teams, here we create a new team and in the identity provider drop down we select the AD group that we want to link the team with.  
  
Now these teams are synced with AD groups and users can be onboarded directly into GitHub without having to provision the user seperately. This user sync might take 30-40 minutes so please wait after users are added into GitHub.

## How to use AD group prefix to create groups?

1. Login to Rada
2. Go to Groups and select create new group
3. Select a prefix and then choose create group
4. Enter the group name, group description, select the group manager and create group
5. After the group is created, please provide us with the Group name and your groups should sync with Github as soon as possible.

You can also [visit](https://docs.google.com/document/d/1IMLTs6qapOfHo2gokKLEDVINCBX_qaHh3L_X2a0Gm5E/edit?usp=sharing) this document.

## Raising a Support Ticket

- [Service Request](https://roche.service-now.com/rose?id=sc_cat_item&sys_id=548ad5afdb8181104ae70028f4961988)   
- [Incident](https://roche.service-now.com/rose?id=sc_cat_item&sys_id=612a9d8fdb8d05904ae70028f49619ca)
