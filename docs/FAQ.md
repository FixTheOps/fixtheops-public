# FAQ

## 💻 Technical 

### Why is it not possible to use PVC?

FixTheOps is a costly project, and to save resources the PVC are disabled by default (As each of them is a cost increase). So if you need to install some helm charts for a challenge, or Kubernetes resources using Persistent Volumes, you will need to disable them.

You can still use the `emptyDir` volume type if needed in the pods.

### How to connect to a cluster challenge?

[Go to page](https://github.com/FixTheOps/fixtheops-public/blob/main/docs/how-to-connect-with-kubeconfig.md)

--- 

## 🌍 Website

### Why do I need to share my Github account to use the website?

The website is using Github OAuth to authenticate users. As FixTheOps is spawning cloud resources, it can become costly and I need to limit the number of users that can create resources. 


### What can the other users see about me?

Once you set a pseudo, you get visible on the leaderboard to other users. Only your pseudo and description are visible, no other personal information is shared. Your email & name from github stay private.

### How are you using my email?

I only use your email to send you a notification when you are invited to join the platform, and to distribute invitation codes. No email address is shared or sold.

In the futur I might allow opt-in for newsletter and/or updates about FixTheOps.

### Analytics

To get feedback on how the website is used, I am using Google Analytics and Vercel Analytics. This is only for internal use and no data is shared with third parties.

It helps to know how the users are reaching the landing page, and in general which pages are accessed the most.

If you have don't like sharing analytics to improve the website, https://ublockorigin.com/ is a good browser extension that blocks trackers, I use it myself.

--- 

## 🤝 Collaboration

### Can I share challenges answers with others?

It is not advised. The goal is to learn and improve your skills, and sharing answers will not help you to achieve that goal, or help others achieve that goal.

### I have a great idea for a challenge, how can I share it?

You can open an issue on this repository or send me a message from fixtheops.dev where you can find several ways to contact me (email, discord, twitter, etc.) Be aware that issues are public, so don't disclose solutions on GitHub.

### I am a company and wants to create a challenge related to an open source tool

I am open to discuss about it, especially for tools related to the CNCF landscape!

----

> Note: As the platform is in rapid development, this FAQ might not be up to date. If you have any questions, feel free to open an issue or contact me on the website.