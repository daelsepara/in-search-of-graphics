# In Search of Graphics: Adventures in Computer Art

This is a source code repository of the Logo and Basic programs in the 1984 book, **In Search of Graphics: Adventures in Computer Art** by William and Sandra Markle of CompuQuill, Atlanta Georgia

## In the beginning it was BASIC

In 1991, our school started a computer class just as we started in 6th grade. 8-bit home computers have been available for more than a decade and while it was offered as a class in other highschools (or colleges), ours may have gotten the budget to put up a computer lab only recently. Amazing, despite being, primarily, a catholic school, we still had good science, art, and mathematics teachers and subjects.

C and Pascal computer languages were much more powerful and advanced, but the school chose to start us BASIC programming language. I soon fell in love with programming and have performed better in this class than in others. We were doing rudimentary text-based GUIs and math with BASIC. One day, our Dad asked about what we were learning in class and he thought that there was was much more to learn. So he got us this book, **In Search of Graphics: Adventures in Computer Art**.

|Front Cover|Back Cover|
|-----------|----------|
|![Front](/screenshots/book-front.png)|![Back](/screenshots/book-back-cover.png)|

It didn't matter that the book was (almost) outdated at this time, i.e. 1984. It fired my imagination so much that I had spent our "computer time" at home, typing-in and running programs from this book, rather than playing DOS games.

### Bird
![Bird](/screenshots/bird.png)
**source**: [BIRD.BAS](https://github.com/daelsepara/in-search-of-graphics/tree/main/src/bird/BIRD.BAS)

### Skyship
![Skyship](/screenshots/skyship.png)
**source**: [SKYSHIP.BAS](https://github.com/daelsepara/in-search-of-graphics/tree/main/src/skyship/SKYSHIP.BAS)

### Hat
![Hat](/screenshots/hat.png)
**source**: [HAT.BAS](https://github.com/daelsepara/in-search-of-graphics/tree/main/src/hat/HAT.BAS)

## Lost in the rat race called life

I've since moved on to other programming languages and other pursuits, but the book remained one of my favourites. Unfortunately, having moved to different locations, houses, and experiencing various natural calamities, I've eventually lost this book in a flood. I did not even manage to save any of my old source codes. This was before I encountered the internet cloud. Everything I created, was stored in flimsy 5.25 and/or plastic 3.5 disks. Worse, I could not find a copy of my old books in any of the bookstores and marked-down outlets that I frequent. They never got reprinted. My heart broke.

## Dark and obscure corners of the internet where old ghosts are digitized

Fast forward to 2024, it had never occured to me that there were numerous book-scanning inititives by several universities, various public and private businesses and corporations (e.g. Google). Early books were printed on material that do not age well, so preserving them, meant that they needed to be digitized. I bet on a chance that my lost books would be among those scanned for digital preservation in digitial online libraries. In one such site (similar to [archive.org](https://archive.org)), I casually typed in book titles in the search box. Immediately, **In Search of Graphics: Adventures in Computer Art** was the top-ranked match. My heart sank again from the flood of nostalgic emotions.

## Retro is cool now

Fortunately, old technology is somewhat new again. The codes in the book ran well in period-accurate hardware that are expensive to acquire. One of the benefits of modern technology is the ability to emulate old hardware and software. I stumbled upon [https://robhagemans.github.io/pcbasic/](https://robhagemans.github.io/pcbasic/) while looking for a way to avoid the VirtualBox->DOS->GWBASIC route to get old code to run on modern hardware. It promised bug-for-bug fidelity to the old GW-BASIC, but with the added convenience on being able to run-out-of-the-box in several platforms.

### PC-Basic 2.0
![PC-Basic 2.0](/screenshots/pc-basic.png)
**source**: [https://robhagemans.github.io/pcbasic/](https://robhagemans.github.io/pcbasic/)

## This is your home (now)

I've set about the task of typing-in the source codes in its pages. Thus, this repository is born. Some codes needed further adjustments to work with modern emulators. Some needed tweaks to the math due the differing number precisions between the old machine and the new one that's emulating it. The [FATPIXS](https://github.com/daelsepara/in-search-of-graphics/tree/main/src/fat-pixels/FATPIXS.BAS) program needed adjustment in its file handling routines since modern computers don't do floppy drives now. I've tried to be completely faithful, but my overriding goal to be able to run these (accurately) in PCBASIC.

### Fat Pixels
|Scanned Page|Source Code|Running in PC Basic|
|-----------|----------|
|![Scan](/screenshots/fatpixs-src.png)|![Source](/screenshots/fatpixs-pcbasic.png)|![In Action](/screenshots/fatpixs.png)|

## Acknowlegement

I've like to thank William and Sandra Markle for writing such an enjoyable book. There's a lot of gems in there that (I think) are still applicable today. Sandra Markle is a beloved educator and children's book author, both the past and inner child in me are forever grateful for **In Search of Graphics: Adventures in Computer Art**.