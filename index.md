# Lab Report 2

## Part 1

![Image](code.png)
![Image](0729A363-A8B7-4F40-AFA7-DDFDEDC73686.jpeg)

The screenshots above show the code used. 

![Image](3295DBB4-1003-4F36-B183-A2ABE2BF27AA.jpeg)



![Image](B579E069-E089-42D1-B161-4DF30160D798.jpeg)

This was the result of using add-message

![Image](FF5A0DBA-6106-4BFB-A4C9-B09171BBB404.jpeg)

This is the way add-message was used. The same process was used to get hello initially.

**Which methods in your code are called?**
handleRequest is called.

**What are the relevant arguments to those methods, and the values of any relevant fields of the class?**
Relevant arguments are the url and what's added on the end of the url once the server is started. 
`num` is a relevant field as it helps creates a numbered list and is initially set to 0 and icnreases by one everytime someone adds a mesage.
`thewords` is also initally set to 0 and contains all the text displayed on the page.

**How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why.**
`num` increases by one everytime an add-message request is submitted to create a numbered list. For example after hello is added its value is 1 and then after hello again is added its value becomes 2.
`thewords` just becomes a longer string every time a message is added. The value fo the string after all the commands were performed was "1. hello\n 2. hello again\n".

## Part 2

![Image](Thekeys.png)

Above a screenshot of the public and private keys, created to log into the remote computer with.out a password, is displayed. The command ls was used.

![Image](withoutpasswword.png)

This screenshot shows proof of the keys working and logging in without a password 

## Part 3
**In a couple of sentences, describe something you learned from lab in week 2 or 3 that you didn’t know before.**
I learned how to remotely connect to the computer in week 2 by using our own personal code. Now, I am able to use this remote computer from anywhere, which I thought was extremely neat and impressive. You simply just have to use ssh and then the specific email and then enter your password. In fact, I don't even need the password due to the keys I created.
