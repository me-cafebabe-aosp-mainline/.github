# Introduction

Welcome to the home of AOSP Mainline device trees by me-cafebabe!

Most of the repositories here are submitted to
[LineageOS organization](https://github.com/LineageOS)
and no longer gets updated here. For these repositories,
the development happens on [LineageOS Gerrit](https://review.lineageos.org).

However, the repositories with `-ext` suffix are supposed to stay here,
and never get submitted into LineageOS organization.

## Why are repositories with `-ext` suffix supposed to stay here

It sounds like a shame but I have to admit that:

I really does not understand some of the stuff (mostly for the HAL codes),
and I complete rely on the help from AI coding agent for these stuff.

It's still too far for me (and maybe you too?) to get in-depth understanding
of everything that we need to keep making meaningful progress.

However, LineageOS recently arose some [rules](https://review.lineageos.org/c/LineageOS/charter/+/502008)
to further restrict usage of AI tools. These are:

> - Inline comments MUST focus on non-obvious logic, complex algorithms,
>   or non-trivial side effects. MUST not contain self-evident explanations or narrative comments
> - Commit messages MUST be concise and meaningful. Long winded explanation SHOULD only be used to annotate the non-obvious.
> - All code submitted MUST be understood and explainable by the human submitter during the review process

The first two rules will effectively reduce some informations, for more or less.

The last rule, is the one which prevents our progressive development to happen.

While I'm not fully understanding the code yet, I still do try to inspect the
code as much as I can, and verify the functionality on every eligible targets.

Unfortunately, rules is rules, which they'll enforce...

Therefore, we keep these kind of development going on, in repositories with the
`-ext` suffix, hosted at outside of LineageOS organization.

## Getting started

To get our device trees in place, sync your work tree using our
[local_manifests](https://github.com/me-cafebabe-aosp-mainline/local_manifests).

Note that we currently focus on support for latest version of LineageOS.

The other Android distributions usually have lack of the necessary patches
which we've got merged into LineageOS.

## Our community

- Telegram: https://t.me/aosp_mainline_playground
