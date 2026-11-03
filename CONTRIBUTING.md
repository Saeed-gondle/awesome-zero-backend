# Contributing

Thanks for helping make **awesome-zero-backend** more useful. Small, well-sourced fixes are welcome. You do not need permission to open a pull request.

## The 60-second contribution

1. Open the relevant section of `README.md`.
2. Use GitHub's **Edit** button (pencil icon).
3. Add or correct one entry, then open a pull request.
4. Paste the official source you used in the PR description.

For larger changes, open an issue first so we can agree on scope.

## What belongs here

Browser-native and local-first tools that replace a backend service you would otherwise operate. Entries must run in the browser, on-device, or peer-to-peer, and must link to official project documentation.

## Entry contract

Every new entry must include:

- A working link to the **official** page, repository, documentation, or paper.
- A one-sentence, plain-English explanation of why a busy developer should care.
- The license, price tier, platform, or other comparable attribute when relevant.
- An honest limitation, trade-off, or requirement. No hype-only descriptions.
- No affiliate, referral, tracking, or shortened links.

Use the existing table or section format. Keep entries alphabetized only when the section is explicitly alphabetical. Do not add a project you maintain without disclosing that relationship.

## Quality bar

- **Primary sources beat summaries.** Link to documentation, source code, papers, or first-party post-mortems.
- **Specific beats broad.** "Runs a 7B model at 4-bit quantisation on an 8 GB GPU" is better than "fast AI".
- **Stale claims get removed.** Prices, limits, benchmark numbers, and licenses change. Include an `as of` date when a number is central to the entry.
- **No duplicate links.** One canonical URL per project or resource.
- **Respect licences and trademarks.** Linking is fine; copying large excerpts is not.

## Review checklist

Confirm the project still builds for the browser or runs locally without a mandatory hosted backend.

## Local checks

If you have [lychee](https://github.com/lycheeverse/lychee) installed:

```bash
lychee --config lychee.toml --no-progress './**/*.md'
```

The same check runs on pull requests and weekly on a schedule. A link that blocks automated requests may be exempted in `lychee.toml` with a short reason.

## Editorial policy

The maintainer makes the final call on inclusion. A submission can be accurate and still be out of scope. Paid placement is not accepted. Projects are never ranked by payment, affiliation, or reciprocal links.

By contributing, you agree that your original contribution is licensed under the repository's MIT licence.