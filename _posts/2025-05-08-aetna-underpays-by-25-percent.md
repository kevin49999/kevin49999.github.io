---
layout: post
title: Aetna Reimburses 25% Less Than What They Claim (Fun Investigation)
---

__tl;dr - Aetna says they'll reimburse 140% of the "Medicare Allowable Rate" for out-of-network medical expenses. In my case they find that number and reduce it by 25%.__

![img](/img/140-claim.png)

Let's investigate the above statement regarding out-of-network medical reimbursement.

I normally wouldn't take the time, but after being reimbursed what _felt_ like the wrong number for months (but _nearly_ close enough) I needed to do the math myself.

Let's take a look at this claim:

_"We pay for services based on your plan's out-of-network rate for the location where you received it. __That rate is 140% of the Medicare Allowable Rate__"_

Before we get to what the number actually is, let's start with what they say it is:

![img](/img/aetna-breakdown.png)

If you do the math ($205-$85.06) you end up with __$119.94__ which is what went to my deductible. 

![deductible](/img/deductible.png)

For 45 minutes of psychotherapy in Manhattan that's sounding a bit low already. Let's see what the government thinks you should pay and then apply Aetna's 140% multiple.

### Medicare Allowable Rate

On the [cms.gov](https://cms.gov) site at this [URL for searching](https://www.cms.gov/medicare/physician-fee-schedule/search?Y=0&T=0&HT=0&CT=2&H1=90834&C=97&M=1) you can type in your HCPCS code (for the service) and MAC code (your location) and it will appear.

In my case, these values are:
* `90834` for the HCPCS code
* `1320201` for the MAC code

Here's the search:

![search](/img/cms-search.png)

And here's the result:

![result](/img/cms-result.png)

Taking the non-facility price (in-office visit) of $114.23 and multiplying by 140% you end up with __$159.92__. This is the amount that should have gone to my deductible.

That's already sounding much better! Like a lower government number with a decent multiple applied.

When I called Aetna and spoke to a rep on the phone (today 5/8/2025) __they confirmed the number I found__. They said their internal system (for a publicly available number) also "calculated" that the __reimbursement amount was exactly $159.92__ down to the cent. 

How could that be? The only excuse they managed to offer was "these rates change". So maybe that explains the lower numbers in the previous claims?

However the number has been wrong every month in 2025 since February. And the wrong number has not changed ($119.94 has gone to my deductible for each appointment).

I'm also fairly certain the HCPCS codes change yearly (or possibly quarterly though that still wouldn't explain this case). You can only search for them by year in the above link.

I think what changed was me calling with this information.

### 25% Reduction

If some group were interested in reimbursing a bit less, they may use the calculated number (the government number * the 140% multiple, which was $159.92) as a starting point. 

Then, decide on some arbitrary percentage to reduce it by (let's say an extremely obvious one, like 25%) to get a number that's a bit lower, but close to the real one.

Let's try doing that:

$159.92 * 0.75 = __$119.94__

What a strange coincidence! I almost wouldn't believe it if the person on the phone didn't confirm what I suspected the number should actually be. The adjustment was also done at a predictable percentage.

### Result

So what will happen to the past claims? It didn't sound like they would fix them. 

I received a PDF in my email to write out and mail my complaint.

I didn't receive any information that backs up the number they came up with.

It sounded like my submissions going forward will be fixed, but I received no confirmation of that either. Only a verbal confirmation the correct amount is what I found it to be.

Hopefully someone else reading this can save 25% on their out-of-network submissions with Aetna.

### Caveat

I can't see anything that says Aetna is required by law to pay 140% of the "Medicare Allowable Rate" for out-of-network medical claims. 

I am simply investigating whether or not they actually stick to their own claims that they post publicly on their website.