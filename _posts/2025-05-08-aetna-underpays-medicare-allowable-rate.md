---
layout: post
title: Aetna Reimburses Exactly 25% Less Than What They Claim (Fun Investigation)
---

![img](/img/140-claim.png)

This is some fun digging at the the above statement regarding out-of-network medical reimbursement.

I normally wouldn't take the time, but after being reimbursed what appeared to be the wrong number for months (but _nearly_ close enough) I needed to do the math for myself.

Let's take a look at this claim:

_"We pay for services based on your plan's out-of-network rate for the location where you received it. __That rate is 140% of the Medicare Allowable Rate__"_

Before we get to what the number should actually is, let's start with what they say it is.

![img](/img/aetna-breakdown.png)

If you do the math: $205-$85.06 you end up with __$119.94__ which is what went to my deductible.

So how did they get to that number? Let's find the Medicare allowable rate first.

### Medicare Allowable Rate

On the [cms.gov](https://cms.gov) site at this [URL for searching](https://www.cms.gov/medicare/physician-fee-schedule/search?Y=0&T=0&HT=0&CT=2&H1=90834&C=97&M=1) you can type in your HCPCS code (code for the service) and MAC locality (your location) and it will appear to you.

In my exact case, these values are:
* `90834` for the HCPCS code
* `1320201` for the MAC code (Manhattan)

Here's the search:

![search](/img/cms-search.png)

And here's the result:

![result](/img/cms-result.png)

Taking the non-facility price (for an in-office visit, which mine are) of $114.23 and multiplying by 1.4 you end up with __$159.92__. This is the amount that should have gone to my deductible. 

When I called Aetna and spoke to a rep on the phone they also __confirmed this exact amount $159.92 (as of today 5/8/2025)__, but said the numbers were subject to change over time. So maybe that explains it! 

However the number has been wrong every month in 2025 since February. And the wrong number has not changed. It's been $119.94 for each appointment. I'm also fairly certain the HCPCS codes change yearly (or possibly quarterly) and you can only search for them by year in the above link.

They also mentioned "internal" calculation tools (to calculate a publicly listed number). I wonder what those tools are doing?

### 25% Reduction

So what may the "internal" calculation tools be doing exactly?

If some group were interested in reimbursing a bit less, they may use a legimate number from the government as a starting point (like $159.92). Then, decide on some arbitrary percentage that people like to pick (let's say 25%) to get a number that's a bit lower, but close to the real one.

Let's try doing that:

$159.92 * 0.75 = __$119.94__

That is very strange! If I take the very real number from the government website, and reduce it by 25% I get the exact number (down to the cent) $119.94 that they actually reimburse.

What a strange coincidence! If this were even off by a few cents or a dollar I would have ignored it (if it was even a bit randomly off).


### Caveat

I can't see anything that says Aetna is required by law to pay 140% of the "Medicare allowable rate" for out-of-network medical claims. 

I am simply investigating whether or not they actually stick to their own claims that they post publicly on their website.