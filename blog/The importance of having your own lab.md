# The importance of having your own lab!

This is my first post on VSec and hopefully not my last. I hope we can use this space to start to encourage others to write posts based on their areas of expertise. It is very exciting that we now have a space that is dedicated for the Danish Cyber Security community. So I am also quite excited to try to kick it off with this post.

Recently I have been getting more and more involved in education, helping create content for the incident response course at Aarhus Business Academy and giving various talks and lectures around other education houses too. My most recent talk focused heavily on some of the lower hanging fruits for students to get involved in whilst they are still new in the field. A few of the things I have been discussing having been, using a 2nd brain technique to gather public Cyber Threat Intelligence (something I will be blogging about too) and also building a lab for learning and eventually purple teaming. So I thought my first post should focus on how important it is to have your own lab and what you can do with it once it is built.

![Saga Lab Map](https://github.com/Combitech-DK/public/blob/main/blog/images/SagaLab.jpg)
This is a drawing of the "Saga Lab" that was built for Aarhus Business Academy, it is currently in use as a great teaching aid on the incident response course.

## 1. Gaining experience
It can often feel quite daunting applying for your first role in a SOC or incident response team, as a newborn cyber security analyst you simply won't have had the chance to get the experience to walk right into that first interview and dazzle the hiring manager with deep knowledge based on real incidents. But this doesn't mean that you don't have the chance to get some experience from real life threats. By building your own lab you will eventually be able to download the latest and "hottest" malware and analyze it within a safe environment (emphasis on the safe, never fire off real malware without taking precautions that your lab is fully isolated from your home network). Then when you walk into that first interview, you can tell the hiring manager and their technical advisor who will no doubt be present at some point in the interview process, all about the latest techniques that you have been testing out inside your lab. It really will set you apart from most other candidates! And as a bonus you will already have some interesting experience gained for when you start in your new role, so you won't just walk in completely new to the cyber security world!

## 2. Something to fill your time
I often take virtual coffee meetings with students, to give advice and try to just be a sounding board for their ideas. A lot of the time I find students who are a bit stuck in their routine of applying for jobs and then wasting the rest of their day by doing something unrelated to Cyber Security. If you want to succeed in any industry this is not the right approach, you should break up your day and live it as if you were already started in your career. Use the morning for job applications and then use the rest of the time for concentrating on your lab. Maybe you could spend your afternoon building new detections for Qbot malware, or you could spend your Tuesday morning working on some new log parsing for Elasticsearch. The possibilities are quite endless when you organize your day like this and it gives you a way of already behaving like you are working!

## 3. Something to give back to the community
A very easy way to get noticed in the Danish Cyber Security community is by playing an active part in it. When we look at how having your own lab could benefit this, you could open source your work. Setting up a community Github repository on VSec of detection rules or log parsing or any other interesting contribution to the community. You could blog about your progress with your lab, or some lessons learned from labbing. The possibilities are quite endless!

## Outro
There are many other benefits of having your own lab, I have just focused on a few of the more key ones. You could Purple team in your lab, you could build a full blown sandbox
environment with automated detonaton of malware. Your imagination is the only limiting factor. So go forth and lab and please write and share your experiences with others!

## Bonus Round
If you want to take a few shortcuts in the building of your lab you can always look for open source alternatives, there is quite a large number of projects out there where you can simply download some Docker images and get going.

[[HELK]](https://github.com/Cyb3rWard0g/HELK) - The Hunting ELK or simply the HELK
[[Security Onion]](https://github.com/Security-Onion-Solutions/securityonion) - Security Onion is a free and open Linux distribution for threat hunting, enterprise security monitoring, and log management.
