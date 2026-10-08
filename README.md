# Briefmate

**Your daily feed, translated and read aloud.**

Briefmate is a personal hobby project with a local-first starting point: a daily
feed translated into Turkish, with audio for morning listening. The name and
product are independent of any one person or source.

## Current status

This repository contains only the initial project description and Git ignore
rules. The application has not been implemented. There is no collector,
translator, scheduler, audio pipeline, deployment, or working setup command
yet.

## Planned direction

- Start with Kun's public X posts as the first planned source. Briefmate is an
  independent project, with no affiliation with or endorsement by Kun or X.
- Translate the daily feed into Turkish. A translation component has not been
  selected or implemented.
- Use [EMA Lightning](https://huggingface.co/canberkkkkkk/ema-lightning) for
  Turkish text-to-speech and morning listening. EMA Lightning is the intended
  TTS model, not the translation component.
- Keep collected content and personal runtime data local rather than in this
  public repository.

These are plans, not working features. X source completeness and freshness
remain unverified, as does execution of EMA Lightning on Mac. No platform
compatibility or performance is promised.

## Privacy and content boundaries

Do not commit credentials, API keys, tokens, private configuration, downloaded
models, generated audio, or personal runtime data. `.gitignore` excludes common
local environment files, credential/key files, runtime folders, source
archives, caches, audio, model artifacts, and local tool state. Ignore rules are
a safeguard, not a guarantee: inspect staged files before committing. A future
`.env.example` may contain only obvious, non-secret placeholders, never working
credentials or personal values.

Keep any local collection of third-party posts, including exports and source
archives, out of this public repository. Public access to a post does not grant
redistribution rights. Respect source terms and applicable rights before
collecting, translating, or sharing content; planned translations and audio do
not imply permission to redistribute the originals or derivatives.

Any shared generated audio must be clearly disclosed as synthetic, AI-generated
speech. It must not be presented as the original author's voice or endorsement.

## License

The repository is public, but a software license has not yet been selected. No
open-source license is granted at this stage. Public visibility alone is not a
license to use, modify, or redistribute the code. A license will be added only
after an explicit decision.
