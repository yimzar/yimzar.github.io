Morgan Albright

TryHackMe Room: Packets & Frames

Difficulty Level: Walkthrough

1/9/2026

Task 1: What are Packets and Frames

1\. What is the name for a piece of data when it does have IP addressing information?

In the first paragraph it says.

"A ______ is a piece of data from Layer 3 (Network Layer) of the OSI model, containing information such as an IP header and payload."

2\. What is the name for a piece of data when it does not have IP addressing information?

"A _____, however, is used at Layer 2 (Data Link) of the OSI model, which, encapsulates the packet and adds additional information such as MAC addresses."

Task 2: TCP/IP (The Three-Way Handshake)

1\. What is the header in a TCP packet that ensures the integrity of data?

In the list of headers the one that fits this description the most is ________. The description listed for it is as follows.

"This value is what gives TCP integrity. A mathematical calculation is made where the output is remembered. When the receiving device performs the mathematical calculation, the data must be corrupt if the output is different from what was sent."

2\. Provide the order of a normal Three-way handshake (with each step separated by a comma)

The best answer for this is _______________. I came to this conclusion by looking at the first diagram and reading the paragraph underneath it.

"Any sent data is given a random number sequence and is reconstructed using this number sequence and incrementing by 1. Both computers must agree on the same number sequence for data to be sent in the correct order. This order is agreed upon during three steps:

___ - Client: Here's my Initial Sequence Number(ISN) to ___chronise with (0)

_______ - Server: Here's my Initial Sequence Number (ISN) to ___chronise with (5,000), and I ___nowledge your initial number sequence (0)

___ - Client: I ___nowledge your Initial Sequence Number (ISN) of (5,000), here is some data that is my ISN+1 (0 + 1)"

Task 3: Practical - Handshake

1\. What is the value of the flag given at the end of the conversation?

The flag I got was THM{___________} I got this after completing the static website attached to the task.

Task 4: UDP/IP

1\. What does the term "UDP" stand for?

The answer I came to was the ____ ________ ________. It was literally the first words in the task.

2\. What type of connection is "UDP"?

UDP is a _________ protocol because it doesn't require a constant connection for data being sent.

3\. What protocol would you use to transfer a file?

You would typically use ___ to transfer a file so that it ensures everything gets sent over properly.

4\. What protocol would you use to have a video call?

___ is the best protocol for this because it keeps sending regardless of it's verification which is much better when not sending files.

Task 5: Ports 101 (Practical)

1\. What is the flag received from the challenge?

To get the flag, I just connected the IP address to 8.8.8.8 on port 1234. This got me THM{______________}.

Task 6. Continue Your Learning: Extending Your Network

1\. Terminate the static site lab deployed in tasks 3 and 5.

Self explanatory, just exit out of them.

2\. Join the "Extending Your Network" room to continue your learning.

Continue on to the next room.
