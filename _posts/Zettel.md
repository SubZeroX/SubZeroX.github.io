* Number pages with alphanumeric strings, so that pages can be sorted hierarchically rather than linearly -- 11a goes between 11 and 12, 11a1 goes between 11a and 11b, et cetera. This allows pages to be easily inserted between other pages without messing up the existing ordering, which makes it much easier to continue topics.
* The essence of the Zettelkasten approach is the use of repeated decimal points, as in “22.3.14” -- cards addressed 2.1, 2.2, 2.2.1 and so on are all thought of as “underneath” the card numbered 2, just as in the familiar subsection-numbering system found in many books and papers. This allows us to insert cards anywhere we want, rather than only at the end, which allows related ideas to be placed near each other much more easily. 
* ![](Imagens/Pasted%20image%2020200925104040.png)

Hey,

I have been trying to implement a Zettelkasten for many years without much success. I've tried a handful of software from massive implementations like Evernote all the way down to individual .txt notes (which had been far more successful). However, my most recent workflow is working wonderfully and so far I am able to keep on top of everything.

Before I get into it, you should know what I am trying to accomplish with this system and the basic rules I follow;

Rules

*   **I don't Anki anything I have not understood at least once before.** I say *at least once* because it's ***very*** easy to understand something completely and then forget later.

*   **I don't put anything into my Zettlekasten I haven't understood to a high level & internalised.** I don't need to understand a concept absolutely, because that's not possible, but I do need to be able to explain whatever the concept is to a layman (Feynman Technique).

*   **Anki Cards should be as simplistic as possible.** Although they could test multiple thoughts. The reasoning behind this is because I don't want to spend hours making cards.

Goals

*   **Understand the subject matter I am committing to memory.** Too many years have gone by with me cramming last minute for an exam and then forgetting everything I learned 30 seconds after I leave the exam hall.

*   **Connect ideas from different disciplines.** The reason being, teaching people things is a passion of mine and I have found explaining things through connecting ideas (in other words, [metaphors](https://www.youtube.com/watch?v=A0edKgL9EgM)) especially useful.

    The other reason that connecting disparate ideas is important for me is I struggle with severe dyslexia and ADHD \- and through lots of trial and error I found, visual, physical & example\-based learning is the most effective for me.

My Workflow

Learning New Material

Forgive the basic example but let's follow a portion of the [Official Python Tutorial; Strings](https://docs.python.org/3/tutorial/introduction.html#strings).

So I start reading the tutorial and on Evernote (substitute for preferred note\-taking software/pencil) write the title STRINGS.

Under the title, I write bullet points of questions that I have just read the answers to. DO NOT write any answers. So, for example the first paragraph of that page is:

> Besides numbers, Python can also manipulate strings, which can be expressed in several ways. They can be enclosed in single quotes ('...') or double quotes ("...") with the same result 2. \\ can be used to escape quotes

My first bullet question would be:

*   How can strings be expressed in Python?

I do that for the whole section/subject, in the end, I normally have massive long fuck off list of unanswered questions. The reason it's so long is that I try and break the questions down into the smallest idea possible.

At the end of the study session, I will mentally work my way through the list and answer the questions. If I struggle with any I will revisit that place in the lesson and try again, seeing in particular if I can break the concept down into smaller chunks (questions). I will NOT write out the answers yet.

I then tag the note with the subject, other relevant tags, and two specific tags `for_ANKI` & `for_ZETTLR`

A few days later, I open up the note and write out the answers to the questions \- any I struggle with, I revisit. So now I have a long list of fuck off ANSWERED questions.

Without a shadow of a doubt, this is the best thing my Dad ever taught me (and he taught me a fucking lot) but in case you don't have a dad as cool as mine was; [Ali Abdaal has done a brilliant explanation of this method.](https://www.youtube.com/watch?v=fBXnxlLR0PY&t=346s)

Memorising the information.

Every morning, at about 6am my daughter wakes me up and replaces me in my bed \- I get up and run through my Anki cards for the day. After I am done I crack open Evernote search by the tag `for_ANKI` and type up as many questions & answers as I can before 8:00 (normally 100ish \- if standard question types). I then strikethrough Ankified questions and answers on the note and if a whole note is complete I remove the `for_ANKI` tag.

Gaining a deeper understanding and making connections.

My thinking behind it.

Historically, for me, this has been the most difficult part \- It's getting a lot better because of an opensource software called [ZETTLR](https://github.com/Zettlr/Zettlr) created by [/u/nathan\_lesage](https://www.reddit.com/u/nathan_lesage/). I'm sure there are others that could be used, I've tried a lot and found this to be the best for this use case (It does have a few teething issues, but the developer is clearly passionate and hardworking). It can be used for lots of things \- but fits my use case perfectly.

It's important to understand, whatever I am looking to make connections to or gain a deeper understanding of is something I am very interested in \- things I am learning ONLY for exams, that are not going to help me or do not interest me do not make it to this part of the workflow, they stay in the memorisation part.

Also, the original textbook/tutorial should be absolutely nowhere in sight when I'm doing this bit, if I need to look something up at this point, I do not understand it well enough to be putting it in Zettlr.

For this part of the workflow to be effective \- I need contentment, peace, quiet and I need to be well\-rested.

The process

*   Step 1 \- Encapsulate a key question into a single thought.

*   Step 2 \- Think of a title for the thought.

*   Step 3 \- Explain it to a 5\-year\-old. (Feynman)

*   Step 4 \- Tag the note.

*   Step 5 \- Link the note.

*   Step 6 \- Put my favorite connections & Feynman explanations back on to ANKI.

Normally, in the evening I'll sit with Zettlr on dark mode \- open up EN, search the tag `for_ZETTLR`, and think deeply about key bullet points. I'm thinking about the concept or idea behind the bullet point. Let's use me as an example;

I am studying Chartered Accountancy \- one of the chapters of one of the modules is about Managing a Business. In that chapter, they talk about a managers authority & power etc. In the EverNote study session note, the first paragraph turned into 6 questions. A key/interesting one of those was '`What does power depend on?`', this is a useful question as it could come up in a similar way in an exam, but it has a simple answer that will do nothing but get you the marks. The answer I typed up was `Subordinates recognising the power a manager has over them.`, simple enough right? But I'll never think about this outside the boundries of that discipline.

(Step 1) So, I'd sit with it and think about it for a while (to be able to think about it, you'll already need to understand it pretty well as we discussed above) and I would come up with a single thought that encapsulates the idea:

> *A persons power comes from the recognition of their power, by the people they are in control of. If those people do not recognise an individuals power \- the individual holds no real power.*

(Step 2) An appropriate title might be;

> *Source of an individuals Power.*

(Step 3) Use the Feynman Technique and underneath your main idea type up a longer, simpler explanation \- that would explain the idea to someone who did not have your contextual understanding;

> *If Adam controls the actions of Barbra and Charlie it is important that Barbra and Charlie feel as though they have to listen. If they don't feel like they have to listen, why would they do anything that didn't benefit them directly?*

> *The second they felt as though they didn't have to listen, Adam can no longer assert any control \- and therefore doesn't have any power anyway.*

(Step 4) Now, I come up with tags. This can be difficult and easy to screw up. When I think of tags \- I'm not thinking about the subject this relates to, so I shouldn't tag this Manager or business\_managment. My best tags are always abstract.

So, it's clear that *Power* as described above is fragile in nature. So one of my tags is#fragile . power isn't a brilliant tag, but it's not as bad as business\_managment.

The idea is that we connect thoughts from completely different disciplines \- so to do this effectively we need to abstract the ideas pretty significantly.

(Step 5) \- Have a look through notes with those same tags and see if you can combine ideas. More points for distantly related ideas.

(Step 6) \- When I absolutely love an explanation I have come up with, or a connection I will put it back on to ANKI. Very, very few ideas get back to ANKI here.

#comeback

- [x] Processo 
