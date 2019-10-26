---
layout: page
title: "Join"
description: "Members of the Open Scholarship Community Galway"
logo:
header-img: "img/home-bg.jpg"
ordernumber: 8
---

# Why join
Join the OSCG! It is free, it is awesome! Being a member means you are an open science enthusiast/advocate/super hero, want to join the discussion, and help promote open science practices in your community.

# How to join?
You can join by using GIT/GitHub as described below (New to GIT? see these [learning resources](https://help.github.com/articles/git-and-github-learning-resources/) and this [10 min. GIT tutorial](https://try.github.io/levels/1/challenges/1)). Alternatively you can email the following to [kevin.moerman@nuigalway.ie](mailto:kevin.moerman@nuigalway.ie)`:
1. A profile picture
2. The information listed in the below [``template``](#YML_template).
Be sure to shoot that e-mail address a reminder if you do not receive a reply.

# Using GitHub to add yourself
Below is an example of how to add yourself as a member using GitHub. Assuming you have [git installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) do the following:

1. Clone the repository to your systems.   
`git clone https://github.com/Open-Scholarship-Community-Galway/Open-Scholarship-Community-Galway.github.io.git`   

2. Create a new branch in which you will propose changes.   
`git checkout -b add-me`

3. Add your profile picture.    
Profile pictures are found in the [`.../img/people`](https://github.com/Open-Scholarship-Community-Galway/Open-Scholarship-Community-Galway.github.io/tree/master/img/people) folder.

4. Add a markdown file about yourself to the folder [`_people`](https://github.com/Open-Scholarship-Community-Galway/Open-Scholarship-Community-Galway.github.io/tree/master/_people). You can do this by copying the file `https://github.com/Open-Scholarship-Community-Galway/Open-Scholarship-Community-Galway.github.io/tree/master/_people/New Person.md`, change the file name to `Firstname Lastname.md`, and fill in the fields at the top of the file by replacing the text with your information. Please ensure the text is aligned as shown so do not remove or introduce spaces. Underneath these YML fields, there is some code which should not be altered. Finally at the bottom of the file you can enter free markdown text where you may add a description of yourself e.g. a short bio.  
   

```markdown
---
title: New Person
name: New Person
role: Wizzard
affiliation: New person's affiliation
img: NewPerson.jpg
purl: personal_website
github_username: New-Person
twitter_username: NewPerson
orcid_id: 
impactstory_id: 
linkedin_username: 
email_address: 
type: member
---

<!--DO NOT CHANGE - HTML / LIQUID stuff to render picture and links -->
{% include addPersonalInfo.html name=page.name description=page.description role=page.role type=page.type affiliation=page.affiliation img=page.img purl=page.purl github_username=page.github_username twitter_username=page.twitter_username orcid_id=page.orcid_id impactstory_id=page.impactstory_id linkedin_username=page.linkedin_username email_address=page.email_address %}

<!-- START OF FREE MARKDOWN -->
Short bio in markdown format
```

5. Stage your proposed changes.  
`git add .`

6. Commit your changes. The `-m` flag stands for message. Please provide a useful commit message, e.g. Added myself to the OSCG.   
`git commit -m "Added myself to the OSCG"`

7. Push the committed changes to the GitHub repository in the branch you created.   
 `git push origin add-me`

8. Create a [`pull request`](https://help.github.com/articles/creating-a-pull-request/) for your branch
