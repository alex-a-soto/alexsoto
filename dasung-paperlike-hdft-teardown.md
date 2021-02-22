---
date: 2021-02-20T16:02
unlisted: true
---

# Dasung Paperlike HD-FT teardown
A series where I’m documenting my process of designing and building an eink laptop.[^dm]

This post is inspired from Kev Zettler's, [Dasung Paperlike Pro Teardown](https://kevzettler.com/2018/02/11/dasung-paperlike-pro-teardown/).

### Opening the Dasung Paperlike HD-FT
|![Prying open the outer bezel of the display.](static/building-an-e-ink-laptop/IMG_20210216_194558.jpg){#avatar .ui .centered .large .image}|
|:--:|
|*Pyring open the outer bezel of the display*|

Using a knife I was able to pry out the plastic part of the Dasung Monitor where it's glued. As I pryed everything open it I noticed the screws of different sizes that are a part of the monitor / panel, keeping it in place.


|![Removed the outer bezel of the display](static/building-an-e-ink-laptop/IMG_20210216_194714.jpg){#avatar .ui .centered .large .image}|
|:--:|
|*Removed the outer bezel of the display*|

Removed all of the screws from the dasung monitor



After removing the screws was able to remove the piece that keeps it all together.

|![](static/building-an-e-ink-laptop/IMG_20210216_203519.jpg){#avatar .ui .centered .large .image}|
|:--:|
|**|

I was able to open it and take a closer at the PCB's similar to Zettler's observation the chip's components were chemically peeled off to prevent reverse engineering. and similarly there were two pcb's, one for the eink display and another one to control the modes of the monitor.


|![](static/building-an-e-ink-laptop/IMG_20210216_201152.jpg){#avatar .ui .centered .large .image}|
|:--:|
|**|




|![](static/building-an-e-ink-laptop/IMG_20210216_201158.jpg){#avatar .ui .centered .large .image}|
|:--:|
|**|

|![](static/building-an-e-ink-laptop/IMG_20210216_201203.jpg){#avatar .ui .centered .large .image}|
|:--:|
|**|


|![](static/building-an-e-ink-laptop/IMG_20210216_201211.jpg){#avatar .ui .centered .large .image}|
|:--:|
|**|


|![](static/building-an-e-ink-laptop/IMG_20210216_201821.jpg){#avatar .ui .centered .large .image}|
|:--:|
|**|

|![](static/building-an-e-ink-laptop/IMG_20210216_202037.jpg){#avatar .ui .centered .large .image}|
|:--:|
|**|

|![](static/building-an-e-ink-laptop/IMG_20210216_202024.jpg){#avatar .ui .centered .large .image}|
|:--:|
|**|

|![](static/building-an-e-ink-laptop/IMG_20210216_202009.jpg){#avatar .ui .centered .large .image}|
|:--:|
|**|

|![](static/building-an-e-ink-laptop/IMG_20210216_202020.jpg){#avatar .ui .centered .large .image}|
|:--:|
|**|


|![](static/building-an-e-ink-laptop/IMG_20210216_201921.jpg){#avatar .ui .centered .large .image}|
|:--:|
|**|

According to the panel that was disassembled, this appears to be the e-ink panel that seems to be used: ES133TT3 [^ES133TT3]:

### The Dasung E-Ink display module

### The Control Boards

[^dm]: If you think this post resonated, be it positive or negative, Send me a [direct message](https://twitter.com/messages/compose?recipient_id=4648173315) on [Twitter](https://twitter.com/alexsotodev) and we can talk. Also ping if you'd like to know the updates on this post.

[^ES133TT3]: [Panelook E Ink ES133TT3](https://www.panelook.com/ES133TT3_E%20Ink_13.3_EPD_overview_31869.html)
