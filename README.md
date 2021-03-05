# OSC Delft newsletters

Welcome! This is the GitHub repository where we will put the online versions of the [Open Science Community Delft (OSCD)](https://osc-delft.github.io) newsletters, and hopefully draft them too! 

This newsletter is sent to all OSCD members, once every 2 months. :incoming_envelope: The newsletter is currently curated and sent by Emmy Tsang, OSC Delft coodinator, with contributions from community members.

## How do I sign up to the newsletter?
[Join the Open Science Community Delft!](https://osc-delft.github.io/join) :hibiscus: You have to be employed/studying at TU Delft to be able to receive our newsletter in your inbox- but we welcome everyone interested to read the newsletter online, here in this repo. 

## Roadmap
We still have to upload some of our past newsletters (where possible), and come up with a process to use this GitHub repo to draft newsletters in the future.

## How can I contribute?
You can:
- Contribute newsletter content, you can do this either by:
  - Commenting on the [item collection issue](https://github.com/osc-delft/newsletters/issues);
  - Directly adding to the Hackmd file of the next draft. To access the Hackmd file:
      1. Switch to the branch named `write-[month]`
      2. There, go to the file `[year]-[month].md` (the year and month being the newsletter you'd like to edit, usually the latest one!)
      3. Click the "Collaborate on HackMD button"
      4. This will open the draft on HackMD, where you can edit/comment on the draft directly
- Let us know if you spot typos in our existing drafts, by opening an [issue](https://github.com/osc-delft/newsletters/issues)
- Check our [list of issues](https://github.com/osc-delft/newsletters/issues) and see if you can help fix some of them!
- Direct new members here so they know what they receive in their mailboxes when they become community members! :book:

# How do we draft these newsletters?
- Emmy Tsang, OSCD coordinator, starts a new branch for the next newsletter (named `write-[month]`, where `month` is whichever month the next newsletter will go out in). This is ususally done 2 months ahead of time (as an example, the last newsletter was sent on March 3, 2021; at the same time the new branch for the next newsletter was created - this next newsletter will be sent in the first week of May 2021)
- She also creates a draft on HackMD, using `newsletter-template.md`. This contains guidelines for all item adders and editors of the newsletter, as well as a deadline for adding items.
- The HackMD draft is pushed to `write-[month]`, linked to as `[year]-[month].md`
- 1-2 weeks before the newsletter is scheduled to go out, Emmy reminds key stakeholders like the TUD data stewards and open science programme team to add their items to the newsletter, using one fo the two ways laid out above in the "How can I contribute?" section
  - The items added to the item collection issue is copied into the HackMD draft upon review. 
- The day before the newsletter is sent, Emmy reviews all items proposed on the draft and in the relevant issues. 
- The newsletter is sent! The final draft on HackMD is pushed and the writing branch is merged into `main` then deleted. At the same time, a new `write-[month]` branch and HackMD draft is started for the next newsletter.
