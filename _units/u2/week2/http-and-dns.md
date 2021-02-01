---
title: 2.A HTTP and DNS
unit: The Internet
order: 6
is_assignment: true
objectives:
  - Describe how HTTP is used for sharing the files and pages that make up the World Wide Web
  - Describe how the Domain Name System helps the Internet scale by allowing devices to find the IP addresses associated with a domain name
  - Explain how different layers of protocols on the Internet build upon and rely on one another
dropbox:
  title: 2.A Unit 2 Digital Journal
  url: https://kingsport.instructure.com/courses/21067/discussion_topics/34829
---

## Warm-Up

Today we're going to finish our study of the layers of the Internet and learn about two final protocols. 

When you joined today, I gave each of you a number. This is your IP address. We know that in order to communicate on the internet you need to know the IP address of the other computer. So far we've let you ask one another's addresses when communicating on the Internet Simulator, but this can be tricky.

**Do This:** Your goal is to create a list of every one of your classmates IP addresses. The only rules:

- You may walk around the room or use the chat
- You may share information with classmates
- You may talk / share information with only ONE classmate at a time

Go! You have 5 mins.

**Do This:** Discuss with your classmates the following prompts:

- Why do you think I was switching IP addresses?
- If IP addresses can change, is there a better way for everyone to know everyone else’s IP address?

If we want the Internet to scale up to billions of devices, then we need a better way to figure out one another's IP addresses!

## DNS

**Do This:** As we watch the following video take notes on:

- How does the DNS solve the problem of translating domain names like example.com into IP addresses?
- How does the DNS help the Internet scale?

{% include responsive.html source="https://www.youtube.com/embed/5o8CwafCxnU?start=142" %}

**Do This:** Discuss the following prompts with a partner:

- How does the DNS solve the problem of translating domain names like example.com into IP addresses?
- How does the DNS help the Internet scale?

## DNS Simulator

Let's go get on the Internet Simulator one last time to see how all the different pieces we've learned about will fit together.

**Do This:** Log into this version of the Internet Simulator

- No talking at all, not even to get your partner’s IP address
- Ask the DNS for the IP address of a user by sending GET username
- Use the IP address you get back to communicate with at least 2 friends. You can talk about: In your ideal world what time would school start? or What would you eat for your perfect meal?

As we can see here on the Internet Simulator, thanks to the DNS we can talk to other people even if we don't know their IP addresses. Additionally, this system is built entirely on all the other layers below it. When you talk to the DNS you're still sending information over the network, you still need to know the IP address of a DNS server, and you still send a message that gets turned into packets and routed using UDP (or occasionally TCP) and IP.

## HTTP and the World Wide Web

We've got our heads wrapped around how DNS works. Let's learn about the last piece of the puzzle here, a protocol called HTTP. In this video we'll learn what happens when you actually visit a website and the language used to send those files around.

**Do This:** As we watch this video take notes on the HTTP protocol.

- What problem is HTTP solving?
- What is a GET request and what are your requesting?
- How does HTTP rely on the other layers of the Internet?
- Why are SSL/TLS, and HTTPS necessary?
- What do certificate authorities do and why are they necessar

{%include responsive.html source="https://www.youtube.com/embed/kBXQZMmiA4s" %}

**Do This:** Review these questions with a partner about HTTP:

- What problem is HTTP solving?
- What is a GET request and what are your requesting?
- How does HTTP rely on the other layers of the Internet?
- Why are SSL/TLS, and HTTPS necessary?
- What do certificate authorities do and why are they necessary?

### Cool Fact

![The Original Web Server](../../images/cern.jpg)
<small>Image Source: https://www.thejournal.ie/where-is-the-worlds-first-ever-web-page-945790-Jun2013/</small>

Tims Berners Lee invented the internet in 1989. The entire web sat on his computer in CERN. Eventaully the World Wide Web went on to be the dominant method for accessing information on the internet.

You can check out the first web at [http://info.cern.ch/](http://info.cern.ch/).

## Wrap-Up

{% include responsive.html source="https://docs.google.com/document/d/1YangRH0MB-HFSsXuv0QCgCae6YDG2GSNFmhtK3dU2No/preview" %}
<small>**Note:** The document above will only appear if you are logged in using your k12k.com email address. If you are unable to view it, visit [https://docs.google.com/document/d/1YangRH0MB-HFSsXuv0QCgCae6YDG2GSNFmhtK3dU2No/edit?usp=sharing](https://docs.google.com/document/d/1YangRH0MB-HFSsXuv0QCgCae6YDG2GSNFmhtK3dU2No/edit?usp=sharing) and make sure you are logged in to the correct account.</small>

**Journal:** Using the Layers of the Internet activity guide above to help you, explain how each of the different layers is involved when you go to a link like code.org?

At this point you all know a LOT more about the Internet then the average person. For our unit project, we're going to turn our attention to thinking through how we can use this knowledge to make good decisions about the Internet's impact on our everyday lives.
