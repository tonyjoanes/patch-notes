# Patch Notes

A weekday digest of actively exploited and notable vulnerabilities for .NET, Azure, container and DevOps teams.

**Site:** [tonyjoanes.github.io/patch-notes](https://tonyjoanes.github.io/patch-notes/)

Each item includes who should care, a recommended fix, and a source. The briefings are written with AI assistance and reviewed by Tony Joanes.

This is not professional security advice. Always verify the details against the vendor advisory before you act.

## Subscribe

- Site: <https://tonyjoanes.github.io/patch-notes/>
- RSS: <https://tonyjoanes.github.io/patch-notes/feed.xml>

## Severity labels

Use these HTML snippets on the line immediately after each item heading. They render as coloured pills.

```html
<span class="sev sev-critical">Critical · CVSS 9.8</span>
<span class="sev sev-high">High · CVSS 8.1</span>
<span class="sev sev-moderate">Moderate · CVSS 6.5</span>
<span class="sev sev-medium">Medium · CVSS 5.0</span>
<span class="sev sev-low">Low · CVSS 3.1</span>
<span class="badge exploited">Exploited</span>
```

Every item in the Actively exploited section should also get the Exploited badge. An optional count row at the top of a post:

```html
<div class="sev-summary" aria-label="Severity counts">
  <span class="sev sev-critical">5 Critical</span>
  <span class="sev sev-high">2 High</span>
  <span class="sev sev-moderate">1 Moderate</span>
  <span class="badge exploited">3 Exploited</span>
</div>
```

Section heading colours (optional, immediately after the heading):

```markdown
## Actively exploited
{: .section-exploited}

## .NET & Azure
{: .section-dotnet}

## DevOps & CI
{: .section-devops}

## Wider industry
{: .section-industry}
```
