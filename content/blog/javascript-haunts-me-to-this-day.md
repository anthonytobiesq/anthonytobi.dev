---
title: "JavaScript Haunts Me Till This Day"
date: 2026-03-27T08:00:00+02:00
summary: "A story about passing on JavaScript years ago, choosing football and law instead, and why I now think more lawyers should learn a little code."
---

*Prefer to listen instead? Here is the audio version of the article.*

<audio controls preload="metadata" style="width: 100%; margin: 1rem 0 2rem;">
  <source src="/audio/javascript-haunts-me-to-this-day.wav" type="audio/wav">
  <source src="/audio/javascript-haunts-me-to-this-day.aiff" type="audio/aiff">
  Your browser does not support the audio element.
</audio>

Every Sunday, I have a ritual I do my best to keep: I try to write JavaScript for a couple of hours.

That sentence alone will probably sort readers into two groups:

1. People who know what JavaScript is.
2. People who are wondering why anyone would voluntarily spend their Sunday doing that.

For the second group, JavaScript is one of the languages that powers a huge part of the modern web. It helps make websites interactive, dynamic, and, depending on the day, either delightful or mildly annoying.

Here is the kind of JavaScript joke that makes the point:

```js
const governmentWebsite = () => {
  let server = Math.random() > 0.5 ? "online" : "offline";

  try {
    if (server === "offline") throw "Server is down... again.";

    let form = {
      step1: "Fill form",
      step2: "Upload documents",
      step3: "Session expired"
    };

    return Object.values(form).map(step => {
      if (step.includes("expired")) throw "😂 Please start again.";
      return step;
    });

  } catch (e) {
    return `Welcome to the Nigerian Government Portal 🇳🇬\nError: ${e}\nTip: Try again at 3:17am.`;
  }
};

console.log(governmentWebsite());
```

For anyone reading this and still wondering what JavaScript is supposed to feel like, these screenshots help more than my explanation probably will.

Here is the Star Wars version:

![ChatGPT explaining JavaScript in Star Wars terms](/images/javascript-haunts-me/star-wars-reference.png)

Funny, yes. Completely practical, maybe not.

Here is the simpler version:

![ChatGPT explaining JavaScript like I am five years old](/images/javascript-haunts-me/explain-js-like-im-5-years-old.png)

I will be honest: JavaScript is probably my least favorite language to write. But that is not the story today.

This is the story of the first time I remember seeing something about JavaScript, and how I had absolutely no interest in learning it.

At the time, I was a baby lawyer. Why would I care about JavaScript when FIFA had my pride at stake?

## The Book I Ignored

I cannot remember the exact year, but I do remember this much: we were probably playing FIFA 09 or FIFA 10 at my friend's house. Let's call him X.

X had the only PlayStation 2 on my block at the time, and he was absurdly good at it. He used Chelsea FC to torment and humiliate the rest of us. Goal after goal. Didier Drogba celebration after Didier Drogba celebration. It was a terrible time for everyone except X.

One day, I saw him reading this big book.

I was probably half-distracted by a game of FIFA or Batman when X's brother asked for a turn with the book. Someone joked about how serious the book looked, and I vaguely remember hearing that it was a popular resource for learning JavaScript.

That moment has stayed with me.

Not because I suddenly became curious, but because I did not.

I saw a possible doorway into tech and kept walking right past it.

## Why I Did Not Care

In my defense, I had other things going on.

Law had my attention. Life had my attention. Football had my attention. If you had told me that years later I would be paying a monthly subscription to learn how to write better JavaScript, I probably would have laughed and gone back to trying to beat X at FIFA.

And yet here we are.

That old moment still haunts me a little. I could have started learning JavaScript way back then.

Instead, I chose FIFA, a life of lawyering, long days with property law and contracts, and all sorts of other adventures I do not regret.

## Why It Still Matters

I do not regret the path I took, but I do think more people should give themselves permission to learn technical skills earlier, even if they do not plan to become full-time developers.

Maybe you are a lawyer.

Maybe you work in a company where your job description sounds like "tomato nuclear science" because somehow you are expected to do everything.

Maybe you do not think learning HTML, CSS, or JavaScript has anything to do with your career.

I think it does.

Not because everyone needs to become an engineer, but because technology now touches almost every profession. The people who understand even a little of how digital products work tend to make better decisions, ask better questions, and spot better opportunities.

If you are still on the fence about whether learning a programming language is worth your time, this last screenshot captures the spirit of what I mean:

![Why you should learn a programming language](/images/javascript-haunts-me/why-you-should-learn-a-programming-language.png)

## A Note to Lawyers and Other Busy People

If you work in law, this matters even more.

Legal work is full of systems, text, logic, structure, and workflows. Those things overlap with technology more than many people realize. You do not need to become a senior engineer to benefit from learning how the web works. Even a small amount of technical literacy can change how you think about your work.

You start seeing repetitive tasks differently.

You start noticing what can be automated.

You start understanding the products your clients use, the tools your company buys, and the systems your team complains about every week.

## Maybe Do Not Be Like Me

So this is my gentle warning.

If you get the chance to learn something technical, do not dismiss it too quickly.

Do not wait for the perfect time.

Do not assume it is only for people with computer science degrees.

And if a friend on your block is reading a giant JavaScript book while you are busy getting cooked on FIFA, maybe at least ask to borrow the book for a weekend.

It might save you years of playing catch-up later.
