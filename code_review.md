# Project code review


Discuss within your team which files need to be reviewed. Decide on the scope, granularity, and the priorities. Keep in mind considerations shared on the slides.

On GitHub, in the repository for your project, initiate code review by issuing Pull Requests (PR). Everybody on the team should participate by either submitting a PR or reviewing one. Use the guidelines that are shared below.

For the sake of accountability, submit on Canvas the link to the pull request that the team worked on. If there was more than one PR, share additional links as a comment in your submission.


# Code Review Considerations and Comments

* Have a formal style guide.
  * Having an official policy on issues will help in keeping the process impersonal (“Does this follow the style guide” vs. “Who’s opinion on this matters”) and also serves to document what issues should be left to the discretion of the author.
* Be kind, keep it professional.
  * Good engineering happens when everyone is calm and happy.  If you trigger an emotional reaction by making your teammate feel attacked, you’ve reduced team productivity. We are all humans, and humans have emotions.
  * Use phrases “this code does X, which has the following drawbacks...” instead of “you have done X, which is bad”.  The code or design is being reviewed, not the author.
* Explain your reasoning.
  * Cite sources (style guides, references, past reviews, mailing lists, stackoverflow). Be clear on the difference between “this is a bug", “this violates our established guidelines”, "this could be done in less complexity, less code", and “this is just my preference”. Don’t force your preferences - but feel free to explain the reasoning behind them.
* Coding is an exercise in compromise.
  * It is common to end up with multiple different totally valid goals that are in conflict and can’t all be satisfied at onces. Don’t be afraid to pointing these out and invite discussion on the best balance.
* Balance giving explicit directions with just pointing out problems and letting the developer decide.
  * It is likely the case that they have spent more time thinking about the problem and may be aware of additional constraints. Solutions you make up on the fly are not always going to be the right answer - identifying the problem and discussing from there goes a long way.
* Encourage developers to simplify code, have better names, extract named helper functions, or add code comments instead of just explaining the complexity to you. 
  * If you have to ask questions in review for it to be clear, future readers will likely be confused as well.
* Snippets show care. Write a snippet, suggest a better name, avoid passive and non-actionable comments.

## Comments That Could be Improved
* “Why don't you use X? It's meant exactly for this scenario (link to that API):”
* “Why don’t you” is inherently personal - it isn’t the person being reviewed, it is the code. Something like “Can this be X?” is less aggressive. 
  * <soapbox, but a potentially useful counterargument> I often hear folks who leave comments like this complain that "I'm only asking a question, why is the reader getting defensive?" Underrepresented groups in software engineering often hear these words in person, with the tone of "you obviously don't belong here," and we tend to read them the same way. It's on the speaker to communicate what they actually mean ("here's an alternate API to consider") **as well as** the listener to hear it as such. </soapbox>
  * Indeed I often catch myself editing code review responses to remove "you" references and rephrasing them as a description of what the code does, or other properties of the design. From there it is easy to describe suggested changes in terms of more abstract and technical pros/cons, rather than whether the author made a good/bad choice or did a good/bad job.
  * … I tend to use **we**, to emphasize that this is a team effort, and that at the minimum after the review it's not "your" code any more, it's now code that "we" produced together.

* Add space, format as …, move brace, etc. 
Prefer to automate whenever possible - auto-formatting tools exist for many languages. Decide on one and leave code-review to the more important / high level concerns.


* (in response to comment from engineer not explicitly listed as a reviewer)
"You weren't in the discussion. This was exactly why Daniel chose to[...] Thanks for playing."
  * Sarcasm and snark does not help in code reviews, and it will discourage teammates from offering their thoughts in the future.


### Activity:
github.com/hmc-cs121-admin/git-pm-workflow/blob/master/code-review-dance-activity.md 

### Links:
https://medium.com/@sandya.sankarram/unlearning-toxic-behaviors-in-a-code-review-culture-b7c295452a3c
https://jml.io/pages/your-code-sucks-and-i-hate-you.html


