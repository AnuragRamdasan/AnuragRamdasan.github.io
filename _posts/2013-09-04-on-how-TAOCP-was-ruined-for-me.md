---
layout: post
title: "on how TAOCP was ruined for me"
date: 2013-09-04 20:52:00
---

A few weeks back, I ordered ['The Art of Computer Programming' by Donald Knuth](http://en.wikipedia.org/wiki/The_Art_of_Computer_Programming). After hearing so much about it all this while, I was quite excited about giving it a shot. I made the order from Flipkart. Flipkart being an Indian e-commerce store, made the Indian edition of the book available on their website. This was good because ordering the original edition of the book costs somewhere around Rs. 5000 in India while the Indian edition is available for Rs. 400(approx) largely because it is printed locally and on low quality paper. This is where the trouble began.

I ordered all three books at once, since they were offering a combo on their website. As soon as I ordered, they said *Volume 3* wasn't in stock and will be delivered a few days late. It would have anyways taken me more than just a few days to get through the first two books, so that was ok. As soon as I got the first two books, I started off. Volume one was interesting. And in a couple of days I found an error, on page 53. I found an error in The Art of Computer Programming(TAOCP).

For those who don't know about this book, it is often considered as a seminal work in Computer Science and one of the most difficult books to understand in this field. The author, Dr. Knuth, gives anyone who finds an error in his book a cheque of *$2.56*. This over time, has been considered to be [one of the most prized tophies in computer science.](http://en.wikipedia.org/wiki/Knuth_reward_check). So for the 40 years since the book was first published, people have been trying to find an error in it but somehow missed the one that I found. Quite frankly, I was confused at this point and I immediately looked at the errata for *Volume 1 Edition 3* maintained at the *TAOCP* website. There was no mention of the error. This was a simple error, someone should have noticed it by now.

Anyway, I decided to let Dr. Knuth know about this error and dropped an email. Dr. Knuth's website claims that any mail sent to him will be replied to within 6 months to 3 years. So I was pleasently surprised to recieve a response within a week. The contents of the response surprised me even more.


*"I can't understand your letter at all! Page 53 of Volume 1 edition 3 has no formula even close to what you mentioned. On page 33 there is something similar five lines from the bottom but the formulas there*
>    [1 <= i <= n][1 <= j <= i]

>    and

>    [1 <= j <= n][j <= i <= n]

*look 100% OK to me."*


What? I didn't even read the rest of the mail and went straight to the book to confirm this. It was still there, right on page 53, exactly as I had mention. I was already prepared to reply with justification. I continued to read the rest of the  mail.


*"Indian publishers have been messing around and printing strange ripoffs of my books for some time. Last year I learned about an appalling version of Concrete Mathematics in which they had ripped out many of the pages (including the preface and bibliography) and changed page numbers on individual pages but not in the index!"*


This wasn't expected. Someone is selling messed up copies of a book online and no one has issues with it. Interestingly, the Indian Edition of *TAOCP* was published by *Dorling-Kindersley*, the same guys who published the above mentioned copies of *Concrete Mathematics*. *Dorling-Kindersley* is a subsidiary of PearsonEd, the original publishers of TAOCP. Last I heard from Dr Knuth, he had asked them to shred all of the copies of that print of *Concrete Mathematics*. Whether they did it or not was unknown. At this point, the third volume hadn't yet been delivered. My first instinct was to cancel the order. After that, I contacted the retailer. Flipkart was quick to reply when I asked for the book to be returned, excerpt from their reply:


*"We would like to inform you that the above book is a Reprint Edition. As per our records, we see that you have placed an order for the above book and the same has been delivered to you. Therefore, we will not be able to take this book back."*


Well, they are only retailers. They can't be blamed for the book being a reprint edition. Although, I had no idea what a 'Reprint Edition' was. A little searching on the internet gave me some clues. I went back to the *TAOCP* web page and searched through all of the existing erratas. As it turns out, the errors in my book were present in the early errata of *Volume 1 Edition 3*. So it hasn't been updated since the early errata of Edition 3 was made? How old is this version? In another one of his emails, Dr Knuth mentions,


*"Nobody should be reprinting any version of The Art of Computer Programming without official permission from Addison-Wesley (or from Pearson Education, since A-W is a subsidiary of PE). And when they do, they should make no changes to editions  printed by Addison-Wesley, except on the copyright page (and they may also add a page or two about an Indian Student Edition)."*

*The error you said that you found on page 53 was actually on page 33 of an early printing of the third edition; but the old errata page says that it was corrected in July 1997. So the publisher must have been using an obsolete copy
-- which I should think would be extremely unprofessional, since the 31st printing is now being sold! Also, if they really did change the page number from 33 to 53, they would have to change thousands of other page numbers, especially in the index. I don't think such a reprint should make any changes to page numbers."*


So maybe Flipkart just 'said something' to get done with it? I do not care about them. But this whole incident had started to annoy me now. Books are my main source of learning new stuff and now I have to look out on every single page for errors, missing pages, wrong page numbers etc. Also I respect Dr Knuth for his work, and ill treatment of such fine works is annoying. Dr. Knuth doesn't own copyright to the content either, so all he can do is deliver the content and hope it is executed well.

Anyway, at this point I decided to contact *PearsonEd*, the original publishers for the book. I thought I would at least point out the error so that they can rectify it in future prints. After locating the representatives I was able to get some of my questions answered. The reponses are separated here as they were sent out as separate emails.


*"This book was reprinted in 2006 in India. By reprint I mean a straight copy of the original book which was published in the US except for a change in the cover. We do not change any content in the book in case of a reprint. Any content change will be done/undertaken by the US editorial during a revision or added to errata. This 3rd edition of this book was originally published in 1997 with no new edition is available, and I don't think there will be a new edition."*

*"The corrections/errata were incorporated in the US version after the stocks get exhausted there. That is the general practice. If one wants to incorporate any changes after the book is published, we wait for the initial stock to get
exhausted, then incorporate the changes/corrections before it goes for printing again. When we reprinted the book, we might have used the original book which had the errors. The changes/corrections do not reflect as we kept on printing from the same old files/negatives which we have. For a reprint title, we only change files, if something comes to our notice or there is a change in the edition.*

*Unfortunately, neither happened and we have kept on printing the old files."*


I was also offered an option to buy an original for $80 (roughly translates to Rs 5000), but no mention of replacing this copy was made. I didn't emphasize on it. Since there is not going to be a 4th Edition, does that mean none of the errors of 3rd edition will ever be corrected? Also because someone made an initial guess about how many copies were to be sold, and since they never sold all of it even after the update was made , no new versions are expected to be printed? Also most of these stuff are also called general practice. I wasn't even sure how to reply to this mail. My biggest concern was that if in the future I end up buying a new book, how can I be sure it is the same book that I expected to be delivered, without any page messups or other oddities. I thought I'd just ask if there were a way to prevent this. I sent out this mail.


*"So if I were to order a book online maybe, is there any way for me to figure out if it is the latest print? So that I can make a wise decision about whether to buy an Indian edition or the original one. Any person I can contact or someone I can call before making the purchase?"*


This is when I stopped getting replies. It would seem that if you are from India, there is no way for you to pay for a book and be completely sure that you would be delivered the correct product. Right now I have two books which have errors that should have been updated more that a decade ago. I just happen to know of two such books, there may be many other books that have been mistreated. Atleast for now, I have resorted to buying the original editions from Amazon and an insanely high price(after dollar to rupee conversion) and shall continue to do so unless there is some better way be sure of the quality of the book.

I wouldn't know about other books as I don't read far too many of those, but technology books are something that definitely needs to be distributed in proper condition and such unprofessional behavior is a huge concern for the readers who invest a huge amount of time reading these books. At this point, all I hope is that PearsonEd makes the changes and fixes the pages in the new version and releases it. Until then, I shall have to fix my copy of *TAOCP* on my own or buy an expensive original edition.
