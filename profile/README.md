# Introduction

Welcome to the home of AOSP Mainline device trees by me-cafebabe!

All the mainline device tree repositories live here, and the
development happens here.

Some of these repositories used to be submitted to the
[LineageOS organization](https://github.com/LineageOS), with
development on [LineageOS Gerrit](https://review.lineageos.org). That
has stopped, and the copies there are no longer updated by us.

## Why we left the LineageOS organization

The LineageOS organization decided on three separate things:

- Further restrictions on AI-assisted contributions, whatever they are.
- Documentation is no longer allowed in device trees, no matter whether
  it is written by an AI or by a human.
- External inherits are no longer allowed in its repositories.

Content that breaks these rules is going to be removed massively from
the mainline device tree repositories hosted there.

We rely on all three, so we host everything in this organization now.

## About AI-assisted development

It sounds like a shame but I have to admit that:

I really do not understand some of the stuff (mostly the HAL code), and
I completely rely on the help of AI coding agents for it.

It's still too far for me (and maybe you too?) to get an in-depth
understanding of everything that we need to keep making meaningful
progress.

That does not mean we lower the bar. While I'm not fully understanding
every line yet, I still inspect the code as much as I can, and verify
the functionality on every eligible target. The quality requirements
still apply to everything here, whether or not an AI tool was used.
The rules from the
[LineageOS charter](https://review.lineageos.org/c/LineageOS/charter/+/502008)
are good rules, and we keep following them as our own:

> - Inline comments MUST focus on non-obvious logic, complex algorithms,
>   or non-trivial side effects. MUST not contain self-evident explanations or narrative comments
> - Commit messages MUST be concise and meaningful. Long winded explanation SHOULD only be used to annotate the non-obvious.
> - All code submitted MUST be understood and explainable by the human submitter during the review process

On top of that, every AI-assisted commit carries `Assisted-by` trailers.

## About the `-ext` trees

The `-ext` repositories that used to exist have been merged back into
the main repositories. The `-ext` inherits stay, as extension points
for **your own** extras: if a tree such as `device/mainline/common-ext`
exists in your source tree, the common device trees include it. See
[EXTENSIONS.md](https://github.com/me-cafebabe-aosp-mainline/android_device_mainline_common/blob/lineage-24.0/docs/EXTENSIONS.md).

## Getting started

To get our device trees in place, sync your work tree using our
[local_manifests](https://github.com/me-cafebabe-aosp-mainline/local_manifests).

Then read the
[bringup guide](https://github.com/me-cafebabe-aosp-mainline/android_device_mainline_common/tree/lineage-24.0/docs)
to make your own device tree, and the
[map of the repositories](https://github.com/me-cafebabe-aosp-mainline/android_vendor_mainline/blob/lineage-24.0/docs/REPOSITORIES.md)
to see how they fit together.

Note that we currently focus on support for latest version of LineageOS.

The other Android distributions usually have lack of the necessary patches
which we've got merged into LineageOS.

## Contributing

Send changes as pull requests to the repository concerned. Read
[DEVELOPING.md](https://github.com/me-cafebabe-aosp-mainline/android_device_mainline_common/blob/lineage-24.0/docs/DEVELOPING.md)
first.

## Our community

- Telegram: https://t.me/aosp_mainline_playground
