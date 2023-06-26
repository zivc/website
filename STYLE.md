# Style Guide

To ensure the consistency of a comprehensive documentation like grammY’s, there must also be a set of rules for humans to follow.
This documents those rules.

If you contribute to grammY's documentation, you do not have to follow these rules.
We are going to fix up your contributions before merging them.
That way, you can focus on writing great content, yet we end up with great style, too.

Naturally, we are always happy if we see contributions that follow this style guide upfront.
Just be aware that we might do lots of nitpicking otherwise.

## 0

grammY’s name must always be written as “grammY”, regardless of its position in the sentence, the casing of its surroundings, and the language of its context.

```diff
- Grammy---the Telegram Bot Framework
+ grammY---the Telegram Bot Framework
```

## 1

The first letter of the names of grammY entities (e.g., plugin names, chat names) must be in lowercase, regardless of the casing of its surroundings.

```diff
- grammY Runner
+ grammY runner
```

## 2

Use American English.
This refers to both spelling and punctuation.
After all, the source code is written in American English, too.

## 3

In English, the the headings must be in title case and follow the rules of [AP Stylebook](https://en.wikipedia.org/wiki/Title_case#AP_Stylebook).

```diff
- ## With great style comes great responsibility
+ ## With Great Style Comes Great Responsibility
```

## 4

Articles must reside outside link texts unless they are part of the identity of the referred entity.

```diff
- See [the Bot API documentation](...).
+ See the [Bot API documentation](...).
```

## 5

Node.js, not Node.

```diff
- both Deno and Node
+ both Deno and Node.js
```

## 6

Smart punctuation must not be used in Markdown sources. 

```diff
- “” ‘’ … —
+ "" '' ... ---
```

## 7

Be consistent.

```diff
- Now that you have set the BOT_TOKEN env var, it's time to set the DENO_DEPLOY_TOKEN variable.
+ Now that you have set the BOT_TOKEN variable, it's time to set the DENO_DEPLOY_TOKEN variable.
```
