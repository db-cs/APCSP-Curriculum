---
title: 2.A Packets
unit: The Internet
order: 5
is_assignment: true
objectives:
  - Describe how information flows through the Internet as a datastream of packets
  - Explain how packet numbering and re-ordering can allow for large messages to reliably be sent even if packets are dropped or arrive out of order
  - Explain the differences between the Transmission Control Protocol (TCP) and User Datagram Protocol (UDP)
dropbox:
  title: 2.A Unit 2 Digital Journal
  url: https://kingsport.instructure.com/courses/21067/discussion_topics/34829
---

## Warm-Up

**🤔 Reflect:** Suppose our school library is moving to a new building on campus and the librarian has asked for your help.

- What approach would you take if you just needed to clear out the space by the end of the day?
- How would your approach change if you had more time and wanted to check that every book made it safely and was on the same shelf it was on before the move?

 In the last lesson we learned that messages can take different paths to get to the same place on the Internet. Sometimes, we need to send really large messages over the internet, like movies or large pictures. Just like moving your entire school library, there are problems that arise when we want to send large messages on the internet. Today we're going to learn about two different protocols for sending information online, one that's used when all we care about is speed, and one that's used when accuracy is more important.

## Internet Simulator

You'll be working in pairs for the beginning of this activity.

[Open the Internet Simulator](https://studio.code.org/s/csp2-2020/stage/5/puzzle/2){: style="border: 1px solid #ccc; border-radius: 5px; padding: 8px 10px; background: #efefef;" target="\_blank"}

**Do This:** Follow the steps below to get familiar with this new version of the Internet Simulator.

1. Join a different router than your partner
1. Ask your partner for their IP address.
1. Using only the simulator, have a conversation about one of these topics: Your favorite movie, Your favorite band/artist, The one superpower you wish you had
1. Try to discover every way the simulator is different than last time.

### Protocol 1

You'll need to open the activity guide below and make a copy. Be sure to share this with me (dbailey@k12k.com).

[Make a Copy of the Packets Activity Guide](https://docs.google.com/document/d/1SAycpvSaXUEgJQhw8efjRok-DHbtP7_avg8i0lv7oTU/copy){: style="border: 1px solid #ccc; border-radius: 5px; padding: 8px 10px; background: #efefef;" target="\_blank"}

#### Why Packets?

When you send messages over the Internet there’s always a chance for errors. If you’re sending a huge file, and in the middle of the transmission you have a single error, you’d need to resend the entire file. The solution to this problem is to split the message into smaller chunks called packets. While errors could still occur, now they’ll only affect the single packet, rather than the entire message. This of course introduces new challenges that we’ll explore in this activity.

#### Just Send All The Packets

Write a single sentence that uses 5 - 10 packets. Send all the packets at once to your partner. Then click “Log Browser”. Set the Router logs to “show my traffic” and “show all routers”

**Do This:** Record your observations in the Activity guide.

### Protocol 2

You'll have 10 minutes to develop a protocol that can address the challenges you indentified in Protocol 1. Just as before you should construct a multi-packet message and send them all at once. After that initial message, however, the receiver and sender can continue to communicate to ensure the full message is received and correctly ordered. Be sure you test your protocol.

**Do This:** Record your protocol in the Activity guide.

### Submitting

Open your 2.A Unit 2 Digital Journal and attach your activity guide. Then record your response to the following prompt:

**✍️ Journal:** How do these new protocols build upon the Internet Protocol(IP)? How do packets build upon the way information is routed accross the network?

## Wrap-Up

The first protocol we looked (UDP) at was simple, but it had some problems. The second protocol we just invented (TCP) is much more accurate, but it takes longer. Depending on the situation, websites will choose the protocol that makes sense. Let's watch a video that teaches us more about how packets really work on the Internet with TCP.

{% include responsive.html source="https://www.youtube.com/embed/AYdF7b3nMto" %}

### Key Vocabulary

- Datastream: Information passed through the internet in packets. 
- Packet:  A chunk of data sent over a network. Larger messages are divided into packets that may arrive at the destination in order, out-of-order, or not at all. 
- Packet Metadata: Data added to packets to help route them through the network and reassemble the original message.
- Transmission Control Protocol (TCP):  A protocol for sending packets that does error-checking to ensure all packets are received and properly ordered
- User Datagram Protocol (UDP):  A protocol for sending packets quickly with minimal error-checking and no resending of dropped packets
