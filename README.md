# AIs.txt

`AIs.txt` is a mental model of a machine learning permission system. Intuitively, question this: what if we could make a human-readable file that declines machine learning (a.k.a. GitHub Copilot use)? It's like robots.txt, but for machine learning.

```txt
User-agent: OpenAI
Disallow: /some-proprietary-codebase/

User-agent: Facebook
Disallow: /no-way-mark/

User-agent: Copilot
Disallow: /expensive-code/

Sitemap: /public/sitemap.xml
Sourcemap: /src/source.js.map
License: MIT

# SOME LONG LEGAL STATEMENTS HERE
```

<img src="https://user-images.githubusercontent.com/31657298/199075877-31d9f4a8-0741-428d-bd82-e16242705768.png" alt="Apple's ATT" width="100" align="right" />

## Key issues

### Would it be legally binding?

For now, no. It would be a polite way to mark my preference to opt-out of such data mining.

It's closer to the **Ask BigTechs Not to Track** option rather than a legal license. On the same vein, Apple's **App Tracking Transparency** can never technically ban all tracking activity.

### Why not `LICENSE` or `COPYING.txt`?

Both are mainly written in human language and cannot provide granular scraping permissions depending on the collector.

Also, GitHub Copilot _ignores_ `LICENSE` or `COPYING.txt`, claiming we consented to Copilot using our codes for machine learning by signing up and pushing code to GitHub.

We may expand the `LICENSE` system to include the terms for machine learning use, but that would bring even more edge case and chaotic licensing systems.

### Does machine learning purposes of copyrighted works require a license?

This question is still under debate.

Opt-out should be the default if it _requires_ a license, making such a license system meaningless. If it doesn't require a license, then which company would respect the license system, given that it is not legally binding?

### Is `robots.txt` legally binding?

No.

Even if you scrape the web prohibited under `robots.txt`, it is not against the law. See [HIQ LABS, INC., Plaintiff-Appellee, v. LINKEDIN CORPORATION, Defendant-Appellant.](https://cdn.ca9.uscourts.gov/datastore/opinions/2022/04/18/17-16783.pdf). `robots.txt` cannot make fair use illegal.

### Are there any industry trends?

[W3](https://www.w3.org/community/tdmrep/) has been working on `robots.txt` for machine learning, aligning with EU Copyright Directives.

> The goal of this [Community Group](https://www.w3.org/community/tdmrep/) is to facilitate TDM in Europe and elsewhere by specifying a simple and practical machine-readable solution capable of expressing the reservation of TDM rights. [w3c/tdm-reservation-protocol: Repository of the Text and Data Mining Reservation Protocol Community Group](https://github.com/w3c/tdm-reservation-protocol)

### Can we even draw the line?

No.

One could reasonably argue that AI is doing the same as humans, much better and more efficiently. However, that claim goes against the fundamentals of intellectual property.

If any [[IP]] is legally protected, machine-generated code must also have the same level of awareness system to respect it and prevent any plagiarism. Otherwise, they must bear legal duties.

### Maybe it can benefit AI companies too

... by excluding all hacky code and only opting for best-practice code. If implemented correctly, it can work as an effective data sanitation system.
