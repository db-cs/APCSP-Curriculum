---
title: 01.D Lossless Compression
unit: Digtial Information
order: 13
is_assignment: true
objectives:
  - Create lossless compressions of text files
  - Analyze patterns in data to determine compression strategies
dropbox:
  title: 1.D Week 2 Digitial Journal
  url: https://kingsport.instructure.com/courses/21067/assignments/249176
---

## Warm-Up

**Prompt:** This list represents several common abbreviations used in text messages. Why might we use abbreviations when sending messages? What are the advantages?

```
lol
ty
c u soon
```

## Introduction to Compression

Take a look at the following text message:

```
Pitter_patter_pitter_patter_listen_to_the_rain_pitter_patter_pitter_
patter_on_the_window_pane
```

Now take a look at this compressed version.

```
★listen_to☀️rain_★on☀️window_pane★
```

```
☀️ _the_
☂ tter_
☃ Pi☂
☄ Pa☂
★ ☃☄☃☄
```

Using abbreviations and symbols is a form of compression, where we try to represent the same information with fewer characters. The original message had 93 characters, but the new message and key, also called a dictionary, have a total of 56 characters. We’re essentially sending the same information, but with fewer characters.

Our goal today will be to create our own text compressions using similar methods.

## Text Compression Widget

1. Open up the [Text Compression Widget](https://studio.code.org/s/csp1-2020/stage/9/puzzle/2)
2. Use the dictionary and symbols on the right to compress the text.
3. Let's spend the next 4 minutes trying to compress the text.

{% include responsive.html source="https://www.youtube.com/embed/LCGkcn1f-ms" %}

4. Now that we have some ideas of how lossless compression works, let's spend another 4 minutes trying to make the compression as efficent as possible.

## Wrap-Up

In your Digital Journal consider the following prompt.

**Prompt:** What made some messages "easier" to compress than others? What made some messages more "difficult" to compress than others?

There are many strategies we can use when creating lossless compressions and there isn’t a single best way to do it. Instead, our compression rate usually depends on which strategy we choose and the patterns in the text we’re compressing.

**Most importantly, even though the number of bytes is getting smaller, we're never actually losing information - we can always perfectly recreate the original message using our dictionary key.**

**Lossless Compression:** A process for reducing the number of bits needed to represent something without losing any information. This process is reversible.
