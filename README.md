# Rephrase AI for Gemini CLI

[Rephrase AI](https://www.rephraseai.com) rewrites your text so it says what you meant, in the tone you want, and keeps the meaning the same. This extension brings Rephrase AI into Gemini CLI, Google's coding tool for the terminal. Ask Gemini to rephrase a line, a paragraph or a commit message, and you get the rewrite back without leaving the terminal.

## Install

```
gemini extensions install https://github.com/rephraseai/gemini-cli-extension
```

## Sign in

You need a Rephrase AI account. The first time you use the extension, Gemini CLI opens your browser to the usual Rephrase AI sign-in page. Log in or create an account, approve access, and go back to the terminal. You stay signed in after that.

To sign in again by hand, run this in Gemini CLI:

```
/mcp auth rephraseai
```

## Use it

Ask Gemini in plain words. For example:

```
Rephrase this in a professional tone: "hey, can we push the demo to thursday? the build isn't ready."
```

Gemini calls Rephrase AI and shows you the rewritten text. You can name a tone or a style, or ask Gemini which ones are available.

The extension adds two tools:

- `rephrase_text` rewrites the text you give it.
- `get_rephrase_options` lists the tones and styles you can choose from.

## Usage and history

Each rewrite counts toward your Rephrase AI plan's limits, the same as in the Rephrase AI app, ChatGPT and Cursor. Your requests show up in your Rephrase AI History, labeled "Gemini CLI".

## Help

Questions or problems? Visit [Rephrase AI support](https://www.rephraseai.com/support). Don't have an account yet? Create one at [rephraseai.com](https://www.rephraseai.com).
