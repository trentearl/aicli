# aicli - Ai interface to the command line


This is a collection of scripts (currently just one) to allow you to use Ai as an interface to your shell

## `aibash`

aibash - Drive command line with Ai prompts

```
Usage: aibash [-y|--yes] [-s|--simulate] [<text>]

Arguments:
-y, --yes:     Execute the command without prompting for confirmation
-s, --simulate:    Simulate the command without actually executing it
<text>:    Any amount of text to be passed as prompt to ai
```

[My blog post on this](https://earlearlearl.com/posts/aibash-openai-command-line)

---

**Warning**: this can have a destructive impact on your system, please don't blame me if you it overwrites or deletes a file you didn't expect or something similar.

---


## Demo

![demo](https://i.imgur.com/QVlHbwl.gif)


---

## Examples

- `aibash search github for repos owned by facebook, sort by number of stars, output top 3 like: stars, repo`
- `aibash find all files over 500kb`
- `aibash cwd is a git repo, list all commiters by number of commits, output top 3`
- `aibash using iphone user agent, use reddit json api, curl /r/news, extract tite of the posts`




