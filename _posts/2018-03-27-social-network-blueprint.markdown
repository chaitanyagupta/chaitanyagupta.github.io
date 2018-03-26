---
layout: post
title: "A blueprint for the next social network"
permalink: /social-network-blueprint
---

What will the next social network look like? I hope it is one that
places the privacy and interests of its users first. One that won't
exploit their personal data for its own gain. One that doesn't try to
infer personality traits, sexual orientation, political views, etc. of
its own users.[^1]

A few thoughts on what it must do.

* First, privacy. Keep it simple: provide greatest privacy by default
  for the user's profile and timeline. More importantly, make it easy
  for the user to know who can see what and also make it easy for them
  to change their privacy settings.

* Collect only as much data as the user chooses to provide. Don't
  record what your users are browsing on the web (via a "Like" button
  or similar). Don't create shadow profiles of nonusers, etc. Don't
  try to read user data (call log, SMS, address book, etc.) that you
  don't need.

* Don't retain anything indefinitely apart from things like profile
  data, preferences, posts, pictures, etc. (all of which the user
  explicitly provides and does expect to be retained
  indefinitely). One may need to retain a few additional data points
  like IP addresses or device details for account security and spam
  prevention. That's fine, but this should be the only reason to
  retain them.

* Don't analyze user data for the network's gain (e.g. don't infer
  personality traits, etc.). Analysis for things like spam detection
  is fine, but almost nothing else is.

* Don't use AI or a recommendation engine to decide what a user sees
  in their timeline[^2]. Keep it simple and show everything that is
  not spam chronologically. If you have to filter content on the
  timeline, make it clear to users what's being filtered (popular
  posts, etc.) and allow users to clear any filters.

* Maintain strict control over user data given out to apps and
  integrations. Manually review apps that request sensitive user data
  (posts, friend list, photos, etc.). Allow users control over app
  permissions. Encourage apps to make minimal use of permissions.
  
* I don't like ads, but I think its unavoidable if you want to bulid a
  social network that is free to use. That said, don't build an ad
  profile of your users, nor allow advertisers to do the same. Take
  steps to prevent advertisers from tracking your users. Provide
  contextual ads, but don't run third party scripts. An alternative
  revenue stream might be to allow users to pay to get ads removed.

* Protecting against nation states is a really tough one. On one hand
  the service has to operate within the law of the land where its
  users are located, but on the other hand it must take a principled
  stand around protecting user data. That means don't build a PRISM
  like tool without fighting for your users. And the lesser data you
  collect on your users the lesser you need to reveal in courts.

Most importantly, I don't think a for-profit company is a good fit for
these goals. A **non-profit** would be a better fit, that said I am
not sure it is financially viable.

*Acknowledgement*: Thanks to [@zeynep](https://twitter.com/zeynep),
whose articles on the digital surveillance infrastructure built by
Facebook, Google, etc. helped shape my thoughts around this.

---

[^1]: [Facebook's Surveillance Machine](https://www.nytimes.com/2018/03/19/opinion/facebook-cambridge-analytica.html)

[^2]: Even Google has a hard time preventing YouTube from turning into
    a [giant radicalizing engine](https://www.nytimes.com/2018/03/10/opinion/sunday/youtube-politics-radical.html)
