# Unix Timestamp Converter

Convert Unix epoch time to human-readable dates and back, in your local timezone or UTC.

**Live:** <https://unix-timestamp-converter.slippylabs.com/>

## What it does

- Epoch seconds or milliseconds to a human-readable date, and back again.
- Local timezone or UTC, with a `Now` button for the current instant.

## Run it locally

A static site. No build step, no package manager, no dependencies:

```
git clone git@github.com:slippylabs/unix-timestamp-converter.slippylabs.com.git
cd unix-timestamp-converter.slippylabs.com
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

---

Part of [Slippy Labs](https://slippylabs.com). Every tool is indexed at
[projects.slippylabs.com](https://projects.slippylabs.com).
