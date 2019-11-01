---
layout: pagefullwidth
title: "Join us"
description: "How to join"
logo:
header-img: "img/home-bg.jpg"
ordernumber: 8
---

# Become a member
## Why join
Join the OSCG! It is free, it is awesome! Being a member means you are want to promote open scholarship practices at your institute and want to stay up to date on events in this space in and around Galway. 

## How to join?
### Step 1, join the discussion
Join our slack channel

### Step 2, add yourself to the people page
To be added to the [people page]({{ site.baseurl }}/People/) you can provide a profile picture (or stick with the default picture), and if you like, provide links to items like your personal website and social media profiles. Here are 2 ways to be added (please ask one of our members for help if you get stuck):    
   
**Using GitHub:**. Sign into GitHub and edit the [`people.yml`](https://github.com/Open-Scholarship-Community-Galway/Open-Scholarship-Community-Galway.github.io/tree/master/_data/people.yml) file. Simply copy and paste the text below into the file and change by entering your information. Spaces and indents are important so do not add or remove spaces before the key-words. Also please ensure there is an empty line between yourself and the previous/next person. After editing the file you can commit the file change and submit a pull request for us to approve the change. Below are instructions to add your self using git and GitHub. 

```yml
- name: Your Name
  role: Your role
  affiliation: Your affiliation
  img: yourProfilePictureFileName.extension
  url: yourwebsite.com
  github_username: yourGitHubHandle
  twitter_username: yourTwitterHandle
  orcid_id: yourORCIDcode
  impactstory_id: u/yourORCIDcode
  linkedin_username: yourLinkedInProfileName
  email_address: your@email.address
  interests: A short plain text description of your interests (e.g. a tweet long)
  type: member (or lead if you are on the steering committee)
```

Also use a pull-request to add your profile picture to the [`.../img/people`](https://github.com/Open-Scholarship-Community-Galway/Open-Scholarship-Community-Galway.github.io/tree/master/img/people) folder. We recommend a square picture.    
   
**Email:** We highly encourage you to follow the GitHub route above. If all else fails however, you can the information to us instead and we will add your information for you. Send a reminder if the change is not made in a timely mannor. In your e-mail send us the requested YML data and also attach a profile picture if needed [kevin.moerman@nuigalway.ie](mailto:kevin.moerman@nuigalway.ie). 

### Detailed Git/GitHub instructions
You can join by using GIT/GitHub. If you are new to GIT have a look at these [learning resources](https://help.github.com/articles/git-and-github-learning-resources/) and this [10 min. GIT tutorial](https://try.github.io/levels/1/challenges/1).
 
Below is an example of how to add yourself as a member using GitHub. Assuming you have [git installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) do the following:

1. Clone the repository to your systems.   
`git clone https://github.com/Open-Scholarship-Community-Galway/Open-Scholarship-Community-Galway.github.io.git`   

2. Create a new branch in which you will propose changes.   
`git checkout -b add-me`

3. Add your profile picture.    
Profile pictures are found in the [`.../img/people`](https://github.com/Open-Scholarship-Community-Galway/Open-Scholarship-Community-Galway.github.io/tree/master/img/people) folder. Add your picture there. We recommend using a square profile picture. 

4. Add information about yourself to the  [`people.yml`](https://github.com/Open-Scholarship-Community-Galway/Open-Scholarship-Community-Galway.github.io/tree/master/_data/people.yml) file. See also the information provided above. 
   
5. Stage your proposed changes.  
`git add .`

6. Commit your changes. The `-m` flag stands for message. Please provide a useful commit message, e.g. Added myself to the OSCG.   
`git commit -m "Added myself to the OSCG"`

7. Push the committed changes to the GitHub repository in the branch you created.   
 `git push origin add-me`

8. Create a [`pull request`](https://help.github.com/articles/creating-a-pull-request/) for your branch

Ask us for help if you get stuck at any stage. 

# Become a partner
Join as a partner

