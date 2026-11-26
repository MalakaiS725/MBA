# The Scoreboard Problem
### A podcast episode on audience signals, conversion actions, and why good targeting can still produce garbage leads

*Runtime: roughly 14 minutes. Two hosts. Swap the names for whatever you want.*

---

**HOST A:** So there's a thing that happens in Google Ads that I think is one of the best lessons in all of marketing, and it has almost nothing to do with marketing.

**HOST B:** Okay.

**HOST A:** A campaign is running. Conversions are climbing. Cost per conversion is dropping. Every number on the dashboard is green. And the sales team is quietly furious because the leads are worthless.

**HOST B:** And nobody can explain it, because the data says it's working.

**HOST A:** The data says it's working great. That's the whole trap. Today we're getting into why that happens, and it comes out of a class presentation on something called Performance Max.

**HOST B:** Let's set that up first, because Performance Max is a mouthful.

**HOST A:** Performance Max, PMax for short, is Google's automated campaign type. Instead of you building separate campaigns for Search, YouTube, Gmail, Display, Maps, and Shopping, you hand Google one campaign. You give it your budget, your headlines, your images, your video. And then Google's machine learning decides who sees what, where, and when.

**HOST B:** So you give up the steering wheel.

**HOST A:** Mostly, yeah. And that freaks people out, which is why the question everyone asks is, well, how do I tell it who to target? And the answer Google gives you is audience signals.

---

## Part one: what a signal actually is

**HOST B:** So audience signals are the targeting.

**HOST A:** This is the first place people get it wrong. They are not targeting. They're a suggestion.

**HOST B:** Explain the difference.

**HOST A:** In an old-school campaign, if you targeted men 25 to 34 in Honolulu, that was a fence. Nobody outside that fence sees your ad. Period. That's targeting.

**HOST B:** And a signal isn't a fence.

**HOST A:** A signal is you telling Google, here's who I *think* my good customer looks like. Start looking over here. Google's own documentation is upfront about this. It describes signals as a starting point, not a boundary. The system will absolutely serve your ads to people outside your signal if it thinks it'll find conversions there.

**HOST B:** So what goes into one?

**HOST A:** Four main layers. Your own customer list, which Google calls Customer Match. Your website visitors and app users. Custom segments, which you build out of search terms people use or websites they browse. And Google's own prebuilt audiences, the in-market and affinity stuff.

**HOST B:** And the customer list is the strongest one?

**HOST A:** It's the strongest because it's yours. It's real people who actually bought from you. Google needs at least a thousand matched users before it'll use the list, which trips up smaller advertisers, but if you clear that bar it's the highest quality input you have.

**HOST B:** Okay so I've got my signal. I've handed Google my best customers. What happens?

**HOST A:** Here's where it gets interesting. Google uses your signal to seed the model. It starts looking for people who resemble the folks you described. But almost immediately, it starts doing something else, which is watching what actually converts. And once it has real conversion data, that data starts to outweigh your signal.

**HOST B:** The signal fades.

**HOST A:** The signal fades. It's training wheels. Which is fine, that's the design. But it means the thing steering your campaign long term is not your signal. It's your conversion data.

---

## Part two: the scoreboard

**HOST B:** So let's talk about conversion actions, because that's the other half.

**HOST A:** A conversion action is you telling Google what winning looks like. Somebody submitted a form. Somebody called. Somebody bought. You pick the event, you put a tag on it, and you tell Google, that thing right there, that's the goal.

**HOST B:** And then it optimizes toward that.

**HOST A:** Relentlessly. And I want to be really precise about what optimizing means here, because people use that word loosely. Google is running an auction for every single impression, in real time, millions of times a day. For each one it's predicting how likely this specific person is to do the thing you said counts. If the prediction is high, it bids more. If it's low, it bids less or doesn't bid at all.

**HOST B:** So it's not picking audiences. It's pricing individuals.

**HOST A:** That's a really good way to say it. It's making a probability bet on every person, every time. And the thing it's predicting is the conversion action you defined. That's the target. Everything else is downstream of that.

**HOST B:** Which means if you point at the wrong thing.

**HOST A:** It will hit the wrong thing perfectly. With enormous efficiency. That's the part people don't sit with long enough. The system isn't going to catch your mistake. It's going to scale it.

---

## Part three: how it actually breaks

**HOST B:** Give me the failure.

**HOST A:** Let's use a real business. Say you've got a property restoration company. Water damage, fire, mold. Somebody's pipe bursts, they call you, you send a crew. Average job is a few thousand dollars.

**HOST B:** Sure.

**HOST A:** They want commercial clients, so they build a landing page offering a free emergency response plan. Fill out the form, get the plan. And they set that form submission as the conversion action. Any form fill counts as one conversion.

**HOST B:** That seems completely reasonable.

**HOST A:** It seems totally reasonable, and it is the whole problem. Because think about who fills out a form for a free thing. There's the facility director at a company managing twelve buildings, who is exactly who you want. And then there's a student doing a project. A competitor checking out your offer. Somebody who just likes free PDFs. A homeowner with no commercial property at all.

**HOST B:** And Google counts them all the same.

**HOST A:** Identically. One conversion each. So now Google's model is sitting there learning, and it notices something. The facility director is expensive to reach. Those people are rare, they're on LinkedIn, the auction is competitive. But the free-PDF crowd? They're everywhere and they're cheap.

**HOST B:** Oh no.

**HOST A:** So the algorithm does exactly what you asked. It goes and gets you more conversions at a lower cost, which means it drifts toward the cheap audience and away from the expensive one. It abandons your signal. Not because the signal was bad, but because you told it something better than the signal, and that something was wrong.

**HOST B:** And the dashboard.

**HOST A:** The dashboard looks incredible. Conversions doubled. Cost per conversion cut in half. If you're the marketer reporting to the boss, this is your best month of the year.

**HOST B:** Meanwhile sales is drowning in leads that go nowhere.

**HOST A:** And here's the kicker. Because the sales team's complaints live in a completely different system from the ad dashboard, those two facts never meet. Google literally does not know those leads were bad. Nobody told it.

---

## Part four: the misdiagnosis

**HOST B:** So what does everybody do when they finally notice?

**HOST A:** They blame the signal. Every time. The logic feels airtight: bad leads are a targeting problem, signals are the targeting lever, therefore fix the signal.

**HOST B:** And that does nothing.

**HOST A:** Worse than nothing, because it burns weeks. You rebuild the custom segment, you upload a cleaner customer list, you add negative keywords. And the campaign says thanks, takes your new suggestion, ignores it within about two weeks, and goes right back to the cheap conversions. Because you never changed the goal.

**HOST B:** You changed the advice and not the instruction.

**HOST A:** That's it exactly. The signal suggests. The conversion action decides. When they disagree, the conversion action wins, every single time. It's not close.

---

## Part five: the fix

**HOST B:** So how do you actually fix it?

**HOST A:** You make the scoreboard tell the truth. Three levels, roughly in order of how much work they take.

**HOST B:** Start easy.

**HOST A:** Easiest is to move the conversion action further down the funnel. Don't count the form fill. Count the booked walkthrough, or the qualified call, or whatever step only a serious person takes. You lose volume in your reporting, and people hate that, but now every conversion means something.

**HOST B:** What's the catch?

**HOST A:** Volume. These systems need enough conversions to learn from. If your deep event only fires twice a month, the model can't train on it and performance gets erratic. That's a real tension and there's no clean answer. You're trading signal quality against learning speed.

**HOST B:** Level two.

**HOST A:** Values instead of counts. Rather than every conversion being worth one, you assign different values. A form fill is worth ten. A booked walkthrough is worth two hundred. A signed agreement, two thousand. Then you switch the bidding strategy from chasing conversion count to chasing conversion value.

**HOST B:** So the math changes.

**HOST A:** Completely. Now a cheap junk lead is worth ten and an expensive real one is worth two thousand, and suddenly the algorithm's incentive flips. It'll happily pay a lot more for the good one because the payoff justifies it. You've aligned what the machine wants with what the business wants.

**HOST B:** And level three?

**HOST A:** Close the loop. This is the real one. You send your outcomes back to Google. Somebody fills out the form, Google tags them with a click identifier, that ID rides along into your CRM. Later, your sales team marks that lead qualified, or closed, or garbage. And you push that judgment back to Google.

**HOST B:** So the algorithm finds out what happened.

**HOST A:** For the first time. Now it's not optimizing toward form fills anymore. It's optimizing toward people who became actual customers, because it can finally see which ones did. Google calls the tooling for this enhanced conversions for leads and offline conversion import.

**HOST B:** That sounds like the version that actually works.

**HOST A:** It's the version that works and it's the version almost nobody does, because it requires marketing and sales to share a system and agree on definitions. It's an organizational problem wearing a technical costume.

---

## The close

**HOST B:** So bring it home. What's the one idea?

**HOST A:** Performance Max optimizes toward whatever you tell it to count. So the conversion action is the real control lever, not the targeting.

**HOST B:** And the takeaway people should actually remember.

**HOST A:** When your leads are bad, check what you're counting as a conversion before you touch the targeting. The instinct is to blame the audience. The audience is usually fine.

**HOST B:** Why does this hit so hard, do you think?

**HOST A:** Because it breaks an assumption everybody walks in with. We're trained to think you steer a campaign by choosing who sees it. In an automated system you barely steer at all. You define what winning means, and then the machine runs at that definition as hard as it can. Which is great when the definition is right, and genuinely dangerous when it isn't, because a bad definition doesn't produce a broken campaign. It produces a campaign that is efficiently, confidently, expensively wrong.

**HOST B:** Green dashboard, empty pipeline.

**HOST A:** Green dashboard, empty pipeline. And honestly this goes way past Google Ads. Any time you automate against a metric, the metric becomes the strategy whether you meant it to or not. The tool just makes it obvious fast enough to watch it happen.

**HOST B:** Good place to stop.

**HOST A:** The signal suggests. The conversion action decides. That's the episode.

---

*Notes for recording: the property restoration example in part three is the spine of the whole thing. If you trim for time, cut part five down to levels one and three and drop the values discussion. Do not cut the misdiagnosis section in part four, because the wrong answer is what makes the right one land.*
