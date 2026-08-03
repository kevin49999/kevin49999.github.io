---
layout: post
title: Insurance
---

__tl;dr__ - Aetna says they'll reimburse 140% of the "Medicare Allowable Rate" for out-of-network medical expenses. In my case they find that number and reduce it by 25%.

![img](/img/140-claim.png)

_"We pay for services based on your plan's out-of-network rate for the location where you received it. __That rate is 140% of the Medicare Allowable Rate__"_

Let's investigate the above statement regarding out-of-network medical reimbursement.

### Out-of-Network Claims

Going out-of-network and submitting claims follows a different logic than going in-network. When you go in-network you want a high plan discount because you want to owe less. 

However, in my case I've already paid the full $205 to my provider. There is no real plan discount and they haven't negotiated with my provider. I've already paid and want that amount (or as much as possible) to go towards my deductible once I upload the [superbill](https://en.wikipedia.org/wiki/Superbill).

When going out-of-network you want to hit your deductible so insurance will start chipping in. Once you've hit it, you want the amount subject to coinsurance to be as high as possible.

![img](/img/aetna-breakdown.png)

If you do the math ($205-$85.06) you end up with __$119.94__ which is what went to my deductible.

For 45 minutes of psychotherapy in Manhattan that's feeling a bit low. A low amount means spending more to hit the deductible, and less reimbursement through coinsurance once it's hit. This can be a meaningful amount of money over time.

### Medicare Allowable Rate

On the [cms.gov](https://cms.gov) site at this [URL for searching](https://www.cms.gov/medicare/physician-fee-schedule/search?Y=0&T=0&HT=0&CT=2&H1=90834&C=97&M=1) you can type in your HCPCS code (for the service) and MAC code (your location) and it will appear.

In my case, these values are:
* `90834` for the HCPCS code
* `1320201` for the MAC code

Here's the search:

![search](/img/cms-search.png)

And the result:

![result](/img/cms-result.png)


Taking the non-facility price (in-office visit) of $114.23 and multiplying by 140% you end up with __$159.92__. This is the amount that should have gone to my deductible.

That's already sounding much better! Less than what I actually paid, but better. Like a lower government number with a decent multiple applied.

When I called Aetna and spoke to a rep on the phone (today 5/8/2025) __they confirmed the number I found__. They said their internal system (for a publicly available number) also "calculated" that the __reimbursement amount was exactly $159.92__ down to the cent. 

How could that be? The only excuse they managed to offer was "these rates change". So maybe that explains the lower numbers in the previous claims?

However the number has been wrong every month in 2025 since February. And the wrong number has not changed.

I'm also fairly certain the HCPCS codes change yearly (or possibly quarterly though that still wouldn't explain this case). You can only search for them by year in the above link.

### Reduction

If some group were interested in reimbursing a bit less, they may use the calculated number $159.92 as a starting point. 

Then, decide on some arbitrary percentage to reduce it by. Let's try 25%:

$159.92 * 0.75 = __$119.94__

What a strange coincidence!

### Result

So what will happen to the past claims? It didn't sound like they would fix them. 

I received a PDF in my email to write out and mail my complaint.

I didn't receive any information that backs up the number they came up with.

It sounded like my submissions going forward will be fixed, but I received no confirmation of that either. Only a verbal confirmation that I found the correct amount.

Hopefully someone else reading this can save 25% on their out-of-network submissions with Aetna. Godspeed.

__8/3/26__ - The number never changed after calling. My mailed complaint was unsuccesful over a year ago. Haven't submitted new claims in nearly that much time.

### Caveat

I can't see anything that says Aetna is required by law to pay 140% of the "Medicare Allowable Rate" for out-of-network medical claims. 

I am simply investigating whether or not they actually stick to their own claims that they post publicly on their website.

### Changelog

__5/8/25__ - Original post

__8/3/26__ - Edits for clarity, follow up on results