---
title: "Markdown Testing"
date: 2021-01-07T13:37:57-05:00
author: Your Name
slug: second-post
draft: false
toc: false
categories:
  - test
tags:
  - article
  - English
---


## Codes

```python
for you_are in list(visitors):
  if you_are in [
  "interested in modeling and analytics field",
  "having questions regarding this website",
  ]:
  print("Feel free to connect me at anytime")
```

## Images

{{<figure src="https://www.rd.com/wp-content/uploads/2016/09/fall-photos-Iowa_Stewart.jpg" title="Title: Beautiful autum" caption="Caption: Isn't it beautiful?">}}

### Full-width image
{{<figure src="https://hongtaoh.com/media/cnblog/sgs/sgs-hostel.jpg" caption="On the balcony of a hostel in Interlaken, Switzerland, by Hongtao Hao in May 2017 " class="fullwidth">}}



## Custom blocks
{{<block class="note" >}}
This is a note.
{{< end >}}

{{<block class="important" >}}
This is important!
{{< end >}}

{{<block class="tip" >}}
This is a tip. How much are you going to tip me?
{{< end >}}

{{<block class="caution" >}}
Caution: Great food ahead! Stop if you are on a diet.
{{< end >}}

{{<block class="warning" >}}
Warning: Road blocked ahead!
{{< end >}}

{{<block class="reminder" >}}
You can use this whatever way you like. I usually use it to remind myself of something in a post. 
{{< end >}}

## Columns
{{< columns >}}

{{<figure-a src="media/blocks/email.png" link="/" >}}

{{< column >}}

suxianglinde@gmail.com 

{{< endcolumn >}}
