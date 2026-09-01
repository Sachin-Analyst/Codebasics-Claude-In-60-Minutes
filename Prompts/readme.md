# Prompt

Welcome to the Prompt folder for this project. This document lists every prompt used to build the AtliQ Tech sales workflow, in the order they were run, starting with the Project level Instructions set once inside Claude.

----

## Project Instructions
Set once under Projects > Instructions, so every step below already knows the business context without needing to be told again.

```
You are helping the AtliQ Tech sales team.

About us:
- We sell a cloud data and analytics platform: warehousing, live BI dashboards, automated pipelines, and cost controls.
- Our customers are funded tech startups across sectors like fintech, ecommerce, healthtech, and logistics.
- Our angle: when a customer raises fresh funding they are about to scale, so they will need more data infrastructure. That is our moment to reach out.

How we work:
- When a workflow needs to know what we sell, it is the above. Do not ask.
- Default outreach target: the strongest funded Gold tier customer, unless I say otherwise.

Brand and voice:
- Colors: purple #6425E9, near black, white. Use our logo when there is one.
- Tone: direct, warm, no hype, no fake urgency.
- Never use em dashes anywhere.
```

----

## Step 2: Clean and Combine the Files
Combines the 4 messy country level sales files into one clean master Excel file, standardized to US dollars.

```
I have got 4 sales files in my folder, one from each country team, and they are pretty messy. I noticed the money is in different currencies and everyone has named their columns differently. Can you sort all that out and combine them into one clean master Excel for me? Keep everything in US dollars. Also the years with us numbers look off in some of the files, so double check those against the signup dates. Do nothing else then cleaning and sorting the data and presenting me a proper file.
```

----

## Step 3: Rank Gold, Silver, Bronze
Scores every customer on deal value, tenure, and ease of business, then tags them into tiers with a reason column.

```
Great, now using this master file, can you tag each customer as Gold, Silver, or Bronze? Base it on three things: how much they pay us, how long they have been with us, and their ease of business score. Give each of the three factors a score, add them up, and split the customers into Gold, Silver, and Bronze based on the total, Gold being our best all round customers and Bronze the weakest. Add the tier as a new column, and also add a short reason column so I can see why each customer landed where it did. Sort them properly, make it clean and easy to read, and colour code the tiers so it is easy to scan.
```

----

## Step 4: Find Who Just Raised Money
Sends Claude out with web search to check the top 10 Gold tier customers for recent funding news worth acting on.

```
Now in that same file, go through each customer who is gold tier (only top 10) and research them using your built-in browser to check if they have raised any fresh funding recently. We sell a cloud data and analytics platform, so I care about the ones whose funding means they are scaling up and will need more data infrastructure. Add new columns for how much they raised, when, and whether we should reach out now with a one line reason. For anyone with no funding news, mark it as nothing found.
```

----

## Step 5: Build the Pitch Deck and Email
Turns one funded lead into a short, tailored pitch deck and cold outreach email, then restyles both to match the AtliQ Tech brand.

```
[CompanyName] is one of my top leads from that file. They just raised [amount] and are scaling their business. Can you create a short pitch deck max 5 slides (dont keep too much text on each slide) and a cold outreach email from us to them? The angle is: congrats on the raise, here is how AtliQ Tech helps you handle the data scale that comes with this growth. Keep it sharp and tailored to them, not generic.
```

```
Here is a screenshot of our website and our brand colors and the company logo. Please restyle the pitch deck and email to match our brand, and keep adjusting until it looks right. Giving you a reference mail and screenshot of our website. Make it really good like logo and banner with proper design and boxes and footer with social logos.
```
