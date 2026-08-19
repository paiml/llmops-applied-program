# The Project

This program is built around one project you start in Week 1 and ship in
Week 8: **an application that solves a real problem using a local or
self-deployed LLM (or SLM).**

> [!IMPORTANT]
> **Do not build or train a model.** Your job is to build the application
> around one. Pick an existing model and an existing serving tool —
> [Llamafile](https://github.com/Mozilla-Ocho/llamafile),
> [Ollama](https://ollama.com/), [llama.cpp](https://github.com/ggml-org/llama.cpp),
> [vLLM](https://github.com/vllm-project/vllm), or anything else that runs a
> model locally or on infrastructure you control — and build something on
> top of it.

## What "an application" means here

The model is a component, not the deliverable. The project is done when
someone else can run it and it does something useful for them. A model
sitting behind a `curl` command is not a finished project; a tool with a
purpose, an interface, and error handling around that model is.

Concretely, your application should:

* **Solve a specific problem** for a specific kind of user — not "a chatbot"
  in the abstract. Narrow it down: who is this for, and what do they get
  from it that they didn't have before?
* **Wrap the model with real logic** — input validation, prompt
  construction, output parsing, retries, error handling. The interesting
  engineering is what happens before and after the inference call, not the
  call itself.
* **Have an interface a user actually interacts with** — this could be a
  CLI, a web API, a small web UI, a Slack/Discord bot, a browser extension,
  or something else entirely. Pick what fits the problem.
* **Run on a local or self-deployed model.** A cloud LLM API can be a
  fallback or a point of comparison later (see Week 8), but the core
  project runs against a model you host yourself.

## Some directions (not a menu — pick your own)

These are here to show the shape of a good project, not to be copied
directly:

* A CLI that summarizes or tags a folder of documents/notes on a schedule
* An API that classifies or routes incoming support tickets
* A tool that extracts structured data (JSON) from messy text — logs,
  invoices, emails
* A small service that answers questions about a specific, bounded set of
  documents (this is where Week 5's RAG content becomes relevant, if your
  project needs it)
* A code-review or commit-message assistant that runs against a local repo
* An automation that watches for an event (a new file, a webhook, a queue
  message) and uses the model to act on it

If your idea doesn't look like any of these, that's fine — the test is
"does this solve a real problem for someone," not "does it match this
list."

## Scoping it to 8 weeks

You don't need the full idea working in Week 1. The syllabus is built so
the project grows with you:

1. **Weeks 1-2** — Pick the problem and the language (Python or Rust).
   Get comfortable calling a model and reasoning about its output.
2. **Week 3** — Choose your local model/SLM and serving tool, and get it
   running.
3. **Week 4** — Build the application logic around the model: the part that
   makes it yours, not a demo of the serving tool.
4. **Week 5** — Decide if RAG belongs in your project. Many good projects
   don't need it — don't add it just because it's on the syllabus.
5. **Week 6** — Put a web framework in front of it if your interface calls
   for one (skip this if your interface is a CLI).
6. **Week 7** — Containerize it, add CI, and apply basic DevOps and
   responsible-AI practices.
7. **Week 8** — Ship it, evaluate what a cloud LLM platform would change,
   and record the final demo.

If by Week 4 your project still doesn't touch a real problem for a real
user, that's the moment to narrow or pivot — not Week 8.

## What "done" looks like

See the [self-assessment checklist](./SELF_ASSESSMENT.md) for the concrete
bar: documented, tested, automated, public, and built on a model you didn't
train.
