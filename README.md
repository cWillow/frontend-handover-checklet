# Frontend Handover Checklist
A list of things I've learnt to check/discuss before or during handover from a design team

---

## Draft list:

* [ ] Always check if there are google analytics or other useful data that has informed or could inform the following decisions 
* [ ] Browser spec
---

* [ ] Will it be designed mobile first? - in general this should be yes unless the site will have low mobile traffic in which case it's debatable
* [ ] Responsive or Fluid design? - former gives more predictability but requires more designs - latter usually requires more awareness/discussion about how content behaves as screen size changes
* [ ] Exchange a list of specific breakpoints to target - best to agree this in advance so the project and designs are in sync even if mobile designs come in late
* [ ] Grid system - is there one? Shall we use one? Discuss how it will behave if the site is meant to be fluid (see above)
---

* [ ] Images - are there a lot? - does there need to be? Better to have this argument early on so you know what to expect and how much time to dedicate to this
* [ ] Images again - who is responsible for compressing them? This tends to vary from company to company.
* [ ] Images again again - will we have sources for 1x/2x and each target breakpoint? What about next-gen formats?
---

* [ ] Color pallette - is there one?
* [ ] Fonts stacks - make sure too many aren't used - and that you're not using a whole new font for a small number of use cases
* [ ] Font sizes - if there is a fixed set of font-size/line-height/letter-spacing combinations, is there a quick way to indicate which one is being used in a given text element? (looking at these values in the handover and comparing them to a set for every text element is time consuming)
---

## Gotchas to warn/watchout for:

* [ ] Image shadows! If an image has these - it can't be flush with the edge of the container without css hackery - always better to do this in css
---
