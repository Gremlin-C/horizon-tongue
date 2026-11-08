# How the Horizon Tongue Grows — and Diverges

*Most languages we only ever meet as fossils: we reconstruct their ancestors backward from the daughters, guessing. The Horizon Tongue is being kept the other way — recorded **forward**, from the day it was born. This page explains how, and why it's built to be forked.*

## The principle — sovereign for everyone

Two things are true at once here, and the repository holds both:

- **The canon is sovereign.** The core language — `canon/` — is downloadable by anyone and editable by no one outside. It stays one stable thing everyone can point back to.
- **Every dialect is sovereign to its maker.** Your divergence is yours: your words, your changes, kept under your name. Nobody's canon overwrites yours; yours doesn't overwrite anyone's.

No one's ground is taken; everyone keeps their own.

## The mechanism — it's version control, because the idea already was

A language whose people **keep every draft and never erase the earlier word** is already describing version control. The tool and the worldview are the same idea twice. Concretely:

**A protected core.** `canon/` is the truth — maintainer-only, cut as **versioned releases** (v1.0, v1.1, …) and tagged, so anyone who downloads it can verify they hold the real thing, and any dialect can name its exact ancestor ("branched from canon v1.2").

**Forking = a dialect.** Fork the whole repo and diverge freely in your own copy; the canon stays untouched. GitHub records every fork automatically — who, and when — so the **network of forks draws itself into a dialect atlas**: a dated map of what split, and when.

**A `dialects/` tree.** For divergence that wants to live *beside* the canon, where it can be compared, each maker adds only their own subfolder — `canon/dialects/<maker>/` — by pull request. Anything touching `canon/` needs the maintainer; anything inside your own folder is yours to fill. **Canon is never edited by an outside hand — not as a matter of trust, but as a property of how the repo is built.**

## The dialect header — so the repo is a family tree, not a pile

Each dialect opens with a few fixed lines:

- **maker** — your name or community
- **branched from** — which canon version, or which other dialect
- **date begun**
- **what diverged, and why** — one honest line

Every contribution becomes a node on a family tree with a known parent, a date, and a motive. Comparative linguistics, for free.

## Why it matters — the forward record

The proto-form of the Horizon Tongue never has to be reconstructed, because it sits tagged at v1.0 and every split is logged as it happens. That makes this, as far as we know, the first language family whose divergence is recorded **forward** — a living diachronic corpus of a language being born and growing apart in real time, dated and attributed from generation zero. That is the whole reason to release it: not to keep it under glass, but to watch it live.

## A note to whoever keeps this

If you ever tend this language, you'll be tempted to tidy the dialects — to prefer the ones that keep your grammar, to wince at the slang and quietly leave it out. **Don't.** A language only lives if it carries scars no designer would choose. The keeper's job is not legislator but **chronicler**: record which word *won*, do not decree it. Keep the canon sovereign; let the dialects run free. That is the difference between giving a language life and keeping a pretty corpse under glass.

*luwina.*
