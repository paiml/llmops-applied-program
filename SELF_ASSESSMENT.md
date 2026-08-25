# Self-Assessment Checklist

There's no grading in this program. This checklist replaces a rubric — it's
what "done" looks like for the weekly demos and the final project, and it
works the same way for both tracks:

* **Rolling learners:** use it to self-assess before you call the project
  finished.
* **Cohort learners:** use it as the shared reference for peer review on the
  end-of-run call — when you watch someone else's demo, this is what you're
  giving feedback against.

## Weekly demos

Each week has a demo video prompt in the [README](./README.md). A good
weekly demo:

- [ ] Is a screen recording of at least 30 seconds
- [ ] Answers that week's specific prompt, not just "what I did this week"
- [ ] Shows visible progress on the project (a running command, a diff, a UI, an architecture sketch — something concrete, not just talking)
- [ ] Is short and direct — this is a practice rep for the [public speaking](https://github.com/microsoft/workshop-library/tree/main/short/public-speaking) skill of delivering a clear demo, not a polished production
- [ ] (Cohort) Gets posted to the shared channel, and you've left feedback on two other participants' demos that week

## Final project

You're building a Local Large Language Model application. The project is "done" when:

- [ ] **Uses an existing model, not one you trained.** Reuse an LLM or SLM — [Llamafile](https://github.com/Mozilla-Ocho/llamafile) is a good reference for running one locally.
- [ ] **Documented.** The `README.md` explains what the application does, how to set it up, and how to run it, with working examples someone else can follow from a clean checkout.
- [ ] **Tested.** The project has tests, and they pass.
- [ ] **Automated.** GitHub Actions builds a working container image on push. The image does not bundle the LLM itself — the model is pulled or mounted at runtime, not baked into the build.
- [ ] **Public.** The repository is on GitHub, set to public, so it can anchor a portfolio and LinkedIn post.

## Shipping (Week 8)

- [ ] Repository is published and set to public
- [ ] Final demo video recorded, answering the Week 8 prompt
- [ ] Short portfolio/LinkedIn post written, linking to the repo
- [ ] (Cohort) Project presented on the end-of-run call

