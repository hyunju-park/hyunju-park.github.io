---
layout: post
title:  "Install e-mail server on the raspberry pi2"
date:   2015-07-09 17:20:00
categories: install
---

<h3> install e-mail server on the raspberry pi2 </h3>

<li>sudo apt-get install ssmtp</li>

<br>

<h3> setup /etc/ssmtp/ssmtp.conf </h3>
<li>user name=mail address ex)pi=test@gmail.com</li>
<li>mailhub=server smtp address:port ex)mailhub=smtp.gmail.com:465</li>
<li>rewriteDomail=mail domain ex)rewriteDomain=gmail.com</li>
<li>AuthUser=mail id ex)AuthUser=testuserid</li>
<li>AuthPass=mail password ex)AuthPass=testuserpasswd</li>
<li>hostname=hostmane ex)hostname=raspberrypi</li>
<li>FromeLineOverride=YES</li>
<li>UseTLS=YES</li>

