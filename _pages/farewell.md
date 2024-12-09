---
layout: page  
title: Farewell  
include_in_header: true  
---

# Farewell

## Mailo is Shutting Down

If you're reading this, you probably updated to the latest version of Mailo and saw the message that Mailo is shutting down. There is nothing we can do about it.

## Why

TL;DR: Google implemented a new policy that doesn't allow apps to access the Gmail API unless they are verified by "trusted third parties," which costs time and money. We don't have either.

Longer version - we created Mailo not because the idea for a "mail to self" app was novel, but because we didn't like the existing apps, and specifically the way they handled privacy. You see, there are a couple of ways to do what Mailo does (sends an email to yourself):
-  An app could send the email from their own server, using their own address. This is the easiest way, but it means that the app has access to all the emails you send to yourself. We didn't like that.
-  An app could send the email from your own address, but that means that the app has access to your email password. We didn't like that either.
-  If you restrict usage to Gmail, you can use the Gmail API, which allows the app to send emails more privately. This is what we did.

What exactly do we mean by "more privately"? Here is what Mailo could do:
-  See your email address, name, and avatar (to show in the app)
-  Fetch a list of your labels (to offer you options to send with a specific label)
-  Insert an email into your mailbox. This one is the most important. This is the only thing that Mailo could do - send (insert) an email to yourself, not read your emails, not send emails on your behalf, not delete emails, and not do anything else.

Isn't that neat? We thought so too.

## We're Not Alone

Google has had an annual security audit of the apps using its API for a while now. What changed this year is that instead of Google doing it themselves for free, they outsourced it to "partners." And these partners charge for the service. And they are not cheap.

Here are some other apps that were affected by this:
-  [End of the Road for Google Drive in Transmit](https://blog.panic.com/end-of-the-road-for-google-drive-and-transmit/)
-  [Our Android App is Frozen in Carbonite](https://ia.net/topics/our-android-app-is-frozen-in-carbonite)

## We’re Very Sorry!

Google effectively killed the only way we wanted Mailo to work, so there is no reason for it to continue to exist. We're sorry for this disruption in your workflows; we know it sucks.

Thanks for using Mailo, and thanks for all the feedback you gave us.
