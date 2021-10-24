### Hi there 👋

Since you see my profile, probably you are interested to know who am I. I can tell a lot, but because both of us are short of time, I'll give quick intro. By time, maybe I wrote about me a little more. I'll keep updating this page. 😃

So, I'm a software professional with +20 years of experience, where 15 years worked as a freelancer in big and midsize projects of German atutomotive, medical and biology industries, mainly developed embedded applications. I had an excellent chance to learn a lot. Almost no single project in my carrier was using same technology. The exception was AUTOSAR, which is a standard. I had a excellent chance to compare different technologies, to understand what are the advantages and disadvantages. Based on my experience I can say that there is no perfect technology or perfect solution. Everything has positive and negative sides. My personal advise to everyone, your major criterial to chose a technology for your project should be whether you can live with the disadvantages, do you have solution(s) to cover the negative side, do you have enough resource for that and will the fix pass without stressing developers? 
* If your answer to these questions is _"yes"_, you've chosen right technology.
* If your answer to these questions is _"maybe"_ or _"I don't know"_, it is because you didn't make the choice, you've taken a technology because professional marketer from the technology prvider company made his job good, he made a choice for you and you've taken his offer.
* If your answer to these equestions is _"no"_... well, maybe you need a vacation, I hope you didn't make your choice to kill the company business, right?

Whatever... working with different technologies that provide IPC and multithreading, I've seen projects where developers had fun to work, and developers that reasonably complained that have issues and don't know yet how to fix it. Here are some list of problems that were periodically discussed:
1. While obsorver was instantiating, it missed important data update message and does not know the valu of an object.
2. Avoid multithreading, because sending and receiving messages in parallel cause unpredicted behaviour.
3. While polling and processing a message, the TCP socket stack grows and kills the RAM.
4. While Subscriber polls the TCP/IP stack to reach message, which waits, the other messages for other components are thrown away.
5. After sending a message, wait a little to receive a reply. Othewise, some other object will poll it out and drop.
6. Because of per-to-peer connection, creating a network of distributed service is not an easy task.
7. Every service provider is a standalone application to avoid complication of messaging and dispatching.
8. Cross-dependant processes have issues to start and connect, because it comes a question 'Who starts first and who waits for the connection to succeed'.

[tbd]

<table>
  <tr>
    <td><strong>Follow us</strong></td>
    <td><a href="https://twitter.com/intent/follow?screen_name=aregtech"><img src="https://img.shields.io/twitter/follow/aregtech.svg?style=social" alt="Follow us on twitter"/></a> &nbsp; <a href="https://www.linkedin.com/company/aregtech/"><img src="https://img.shields.io/badge/LinkedIn-Aregtech-blue?style=flat&logo=linkedin&logoColor=b0c0c0&labelColor=363D44" alt="Follow us on LinkedIn"/></a></td>
  </tr>
  <tr>
    <td><strong>Since 20 Oct. 2021<strong></strong></td>
    <td><img src="https://gpvc.arturio.dev/aregtech" alt="Viewers"/> &nbsp; <!-- img src="https://img.shields.io/github/downloads/aregtech/areg-sdk/total.svg"/ --></td>
  </tr>
</table>

![Repo status](https://github-readme-stats.vercel.app/api?username=aregtech&theme=blue-green)
