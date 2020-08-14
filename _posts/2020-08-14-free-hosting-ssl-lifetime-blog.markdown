---
layout: post
title: "FREE HOSTING and SSL for LIFETIME | GITHUB PREMIUM QUALITY| STEP by STEP WEBSITE CREATION 2020"
categories: [Blogs and Website]
image: assets/images/heading.png
tags: [featured]
---

Whenever you want to start a blog or a site, you will always need a hosting where you will host the website and an SSL certificate for authentication. For a beginner, the hosting costs around Rs. 4000 to 6000 a year and increases after that. An SSL cost also around 1000 per year.

> What if I tell you that you can get this for free for your life with premium quality and no charges(not even a penny)?🔥🔥

Yes, you heard it right you can get free hosting and SSL for a lifetime. This service is given by none other than Github. It is a corporation that provides hosting for software development and version control using Git. It has been a subsidiary of Microsoft since 2018.

> So how can we use this service for our needs?

Steps:-

1.) Go and make an account on Github.<br/>
2.) Create a new repository named `username.github.io`, where username is your username (or organization name) on GitHub as shown below.
![image tooltip here](/assets/images/makerepo.png)
Note:-

> If the first part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.

3.) Search for the project or theme for your blog on the net which you want to host on Github<br/>
4.) Download the project<br/>
5.) Open the project in the terminal and initialize `git` in the project as below<br/>

Here I have a project called `personal-website` which is located on `Desktop`
{% highlight ruby %}
knowledgehuman@LTPLD545:~/Desktop/personal-website\$ git init
{% endhighlight %}

> Git is a free and open-source distributed version control system which is designed to handle everything type of projects with speed and efficiency. You can learn more about it on the net

6.) Now you will have to commit this project and push the project the repository, which you made in the 2nd step, like in the next snippet.
{% highlight ruby %}
knowledgehuman@LTPLD545:~/Desktop/personal-website$ git remote add origin <YOUR_REPOSITORY_LINK>
knowledgehuman@LTPLD545:~/Desktop/personal-website$ git add .
knowledgehuman@LTPLD545:~/Desktop/personal-website$ git commit -m <COMMIT_MESSAGE>
knowledgehuman@LTPLD545:~/Desktop/personal-website$ git push origin master
{% endhighlight %}

7.) After the last command the project will get pushed in the repository. You can check this by visiting [GitHub][git].<br/>
8.) Now go to the `Settings` option on the GitHub repository page as in the image.<br/>
![image tooltip here](/assets/images/settings.png)

9.) Scroll down to `Github Pages`<br/>

> Voila!! Your site is published at https://username.github.io/

10.) You can observer that the website is published in `https`. So no need to buy the SSL certificate🔥<br/>
11.) If you have your domain, GitHub also allows you to serve your site from a domain other than `username.github.io`. For that, write your domain name in the Github Page section, and your website or blog will get serve at your domain name.<br/>

> Hey Guys, If you liked the article, do share it with your friends, and you can also follow me for regular updates.

> I have also shown the steps in the visual format in this youtube video. Do check that out if you need any help.

<p><iframe width="560" height="315" src="https://www.youtube.com/embed/-wXipUa8Nas" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>

[git]: https://github.com