# What a 2016 Book About the Grid Taught Me in 2025

I just started a new role as a Senior Software Engineer at [ElectronX](https://www.electronx.com), working at the intersection of energy infrastructure and technology. I have worked in the HFT/Market Making space for years, but my interests have shifted toward something more fundamental: the infrastructure powering our increasingly electrified world.

So I did what any newly curious engineer does. I picked up a book. *The Grid: The Fraying Wires Between Americans and Our Energy Future* by Gretchen Bakke came highly recommended. Published in 2016, it's a deep dive into how America's electrical grid actually works and why modernizing it is so challenging.

Here's what surprised me: reading a nearly decade-old book about the grid was more interesting *because* it's dated. The changes since 2016 are so dramatic that the book serves as an accidental time capsule, showing just how rapidly the energy transition is accelerating. This post captures what I learned and, more importantly, what's changed since publication.

## How the Grid Actually Works (The Basics I Didn't Know)

Before diving into what's changed, I needed to understand what the grid actually *is*. 

The grid is essentially an interconnection of machines and wires spread across regions. There are multiple grids in the U.S., separated geographically. Its purpose is deceptively simple: deliver electrons from power producers to consumers, instantaneously.

The critical constraint that governs everything: **supply must always match demand**. Not approximately. Not on average. Always.

When you plug something into an outlet, you're creating a new path for electrons to flow. Electrons flow through all available paths simultaneously, and the system must respond in real-time. If demand spikes and utilities aren't prepared to ramp up generation, we get blackouts. If plants are ramped up and demand drops unexpectedly, that also causes problems.

This fundamental requirement is why the grid is so complex and why adding renewables has been challenging.

## The Renewables Integration Challenge

Renewables (solar, wind, hydro) are transformative because they generate electricity without emitting CO2 or consuming finite resources. But they introduce a problem the grid wasn't designed to handle: **variability**.

A coal plant can generate electricity regardless of weather or time of day. Solar panels cannot. The grid was designed for consistent, predictable loads from dispatchable generation sources. Variable generation doesn't mesh well with this architecture.

Bakke emphasized that without a solution to store energy when renewables overproduce and release it when they underproduce, renewables would remain limited. In 2016, she noted that grid-scale batteries weren't economically viable or performant enough to solve this problem.

**This is perhaps the biggest thing that's changed since publication.**

An interesting benchmark from the book: coal plants can ramp up to 50% of capacity in 5 minutes, natural gas in 10 minutes, and nuclear in 24 hours. This explains why coal and gas have been so valuable for grid stability, they're flexible and responsive.

But here's the sobering fact that really landed with me: coal-burning power plants are the largest producers of CO2 emissions in the United States. Not transportation. Not industrial manufacturing. Coal power plants.

I knew coal plants emitted CO2, but understanding they're the *biggest* contributor fundamentally changed how I think about the energy transition. Yes, manufacturing solar panels produces emissions. But what they're replacing operates at such a vastly greater scale of emissions that it's not even close. Solar isn't perfect, but it's objectively better when optimizing for CO2 reduction.

## What's Changed Since 2016: The Numbers Are Stunning

When Bakke wrote the book, renewables represented approximately 13% of U.S. electricity generation capacity. 

By 2023, that jumped to **21.4%**. As of 2024, it's **24.4%**. ([2023](https://www.eia.gov/tools/faqs/faq.php?id=427&t=3), [2024](https://electrek.co/2025/02/27/renewables-generated-24-percent-us-electricity-2024-eia-data/#:~:text=Utility%2Dscale%20and%20%60%60estimated%27%27%20small%2Dscale%20(e.g.%2C%20rooftop)%20solar,reviewed%20EIA%27s%20%60%60Electric%20Power%20Monthly%27%27%20report%20data.))

Let me repeat that: nearly a quarter of America's electricity now comes from renewable sources. That's remarkable progress in less than a decade, and probably much higher than most people realize.

But the acceleration story gets even more interesting when you look at *new* generation capacity:

- **2014**: 53.3% of new generation capacity came from wind or solar
- **2024**: 90% of new generation capacity came from renewables, with solar accounting for 78% [Source](https://environmentamerica.org/center/updates/90-of-new-electricity-capacity-in-2024-to-date-comes-from-renewables/)

This is exponential acceleration. Not only are we generating more electricity from renewables, but the rate at which we're adding renewable capacity is increasing dramatically. This suggests the next decade could see even more rapid adoption.

Two major factors driving this:

1. **Solar costs have continued to plummet**. The cost curve since 2016 has been even steeper than optimistic projections.

2. **Battery technology has transformed**. The economically unviable grid-scale batteries of 2016 are now being deployed at scale. Prices per kWh have dropped dramatically, and new chemistries have improved performance and longevity.

## The Wild Card: AI and Datacenter Demand

Here's where things get complicated and directly relevant to my new role.

For the first time in years, [electricity demand in the U.S. is increasing](https://www.eia.gov/todayinenergy/detail.php?id=65264#) and it's accelerating rapidly. The primary driver is AI and the associated buildout of datacenters and compute infrastructure. This demand spike is unprecedented in its pace and scale.

This creates tension in the energy transition. When utilities need to add capacity quickly to meet surging demand, they often reach for the fastest, easiest option: natural gas or even coal. But the demand spike is also driving renewed interest in nuclear power, with tech companies exploring everything from traditional plants to Small Modular Reactors (SMRs).

Interestingly, the same battery improvements that enable renewable integration could also enable datacenters to pair on-site solar farms with grid-scale battery storage—generating during peak sun hours and drawing from batteries overnight. Whether this becomes standard practice or whether the urgency drives us back toward fossil fuels remains one of the most important questions in energy right now.

## What I'm Investigating Next

My biggest takeaway from this book is how much I *don't* know about grid-scale battery storage. The technology has clearly advanced since 2016, but I have many unanswered questions:

- What is the actual lifetime of modern solar arrays and battery systems?
- What happens at end-of-life? How much can be recycled versus disposed of?
- Where are materials sourced, and what are the geopolitical and environmental implications?
- What are the real-world economics of solar + storage projects today versus five years ago?

I also want to dig deeper into the nuclear renaissance. Bakke seemed to write off nuclear in 2016, but sentiment has shifted dramatically. Understanding why feels important.

Finally, I'm curious about the intersection of software and grid management. How are modern grid operators using software to handle variable generation? What does a virtual power plant actually look like? How are datacenters negotiating power purchase agreements?

These questions will form the basis of my next several posts. I'm learning in public here, so if you have expertise in any of these areas or recommendations for what to read next, I'd love to hear from you.

---

**Coming next**: A deep dive into the battery revolution—how costs, chemistry, and deployment have changed from 2016 to 2025, and why this matters for the future of renewables and the grid.