<link rel="stylesheet" href="assets/css/custom.css">

1. [Downloads](#downloads)  
2. [About](#about)  
3. [Lexicon](#lexicon)  
4. [Guides](#guides)  
   - [How To Import A Preset?](#how-to-import-a-preset)  
   - [How To Import A Regex?](#how-to-import-a-regex)  
   - [How To Import A Logit Bias?](#how-to-import-a-logit-bias)  
   - [How To Import A Character Card?](#how-to-import-a-character-card)  
5. [FAQ](#faq)  
6. [Recommendations](#recommendations)  
   - [Top 10 Models](#top-10-models)  
   - [Model Providers](#model-providers)  
   - [Preset Creators](#preset-creators)  
   - [SillyTavern Themes](#sillytavern-themes)  
   - [Discord Buddy](#discord-buddy)  
7. [Support Me](#support-me)  
8. [Contact](#contact)  
9. [Fanarts](#fanarts)  

# Downloads

> 📌 **Note**
> The newest version is 5.0.

> ⚠️ **Warning**
> The preset below is for Chat Completion only. For my older Text Completion presets, visit my [HuggingFace](https://huggingface.co/MarinaraSpaghetti/SillyTavern-Settings).

[Master Download](https://github.com/SpicyMarinara/SillyTavern-Settings/blob/main/Marinara's%20Essentials.zip) | [Preset](https://github.com/SpicyMarinara/SillyTavern-Settings/tree/main/Marinara's%20Essentials/Preset) | [Regexes](https://github.com/SpicyMarinara/SillyTavern-Settings/tree/main/Marinara's%20Essentials/Regexes) | [Logit Bias](https://github.com/SpicyMarinara/SillyTavern-Settings/tree/main/Marinara's%20Essentials/Logit%20Bias) | [Professor Mari](https://github.com/SpicyMarinara/SillyTavern-Settings/tree/main/Marinara's%20Essentials/Card) | [Dottore](https://github.com/SpicyMarinara/SillyTavern-Settings/blob/main/Marinara's%20Essentials/Cards/Dottore.png) **ᴺᴱᵂ** 
:----: | :----: | :----: | :----: | :----: | :----:
Downloads the entire .zip file that includes the preset, regexes, logit bias, and character cards | Universal preset alone | Regexes that clean formatting errors, remove em dashes, and unify formats | Logit bias for OpenAI models | Professor Mari's character card; an assistant who will teach you all about LLMs and help you out with creating character cards | Dottore's character card, the Second of the Eleven Fatui Harbingers from Genshin Impact

![How to download](https://i.imgur.com/G610Q95.png)

# About

Howdy, I'm Marinara!
An LLM enthusiast, teacher, merger, and prompt engineer since late 2023. Additionally, an artist and coder on occasion. I'm the author of models such as [NemoMix Unleashed](https://huggingface.co/MarinaraSpaghetti/NemoMix-Unleashed-12B) and many universal prompts, including professional ones for companies like [Tolan](https://www.tolans.com/), [MyDreamCompanion](https://www.mydreamcompanion.com/), or [Toffee.ai](https://toffee.ai/). I consult for various AI services and offer commissions for cards, prompts, and artworks.

Here you can find my roleplaying and creative writing presets, as well as recommendations, cards, and guides. All related to LLMs. Feel free to suggest new sections to add or models to test. I hope you'll find it informative, helpful, and fun to read.

Cheers and happy gooning!

# Lexicon

Term | Definition
:----: | :----:
LLM | Large Language Model (AI Model)
SillyTavern | Frontend for AI use, the one I create my presets for (https://github.com/SillyTavern/SillyTavern)
Prompt | What you send to the model. This includes everything: instructions, cards, lorebook entries, example messages, and the chat history
Jailbreak | Part of the prompt that is responsible for "jailbreaking," aka "removing censorship" from the model
Preset | A pre-set format of how you send the prompt to the model. These typically involve instructions, optional jailbreaks, and sampler settings
(Character) Card | Typically a description of a character that may include their image, personality, and example message
Persona | Like a character card, but for the character you play as
Scenario | An outline of what happens in the roleplay
Lorebooks (World Info) | Prompt entries that trigger based on activated keywords
Samplers | Algorithms or methods used to decide which token the model should pick next when generating text
Temperature | One of the samplers that controls how creative the output is allowed to be. Numbers closer to zero produce more deterministic outputs, while those closer to 1 and above are more creative
Tokens | Building blocks of text sent to the models. These include symbols, letters, words, and codes
Context | How many tokens the model can process at once, e.g., 32k. The larger the number, the more it remembers
Chat Completion | Format of sending the prompt as a structured conversation, with clear distinctions between different roles (user, assistant, system). Used when you access models via API
User | All the messages that count as being sent from the human (you)
Assistant | All the messages that count as being sent from the AI (model)
System | Instructions for the model, appended before the start of the conversation
Text Completion | Format of sending the prompt to the model as a big wall of text, and asking it to "complete it" (hence the name). Used with locally run models
Input | Your last sent message to the model
Output | Model's response
Logit Bias | A way to manipulate the probability of specific tokens by either banning them completely or encouraging the model to use them more often
Regex | Search language for string, capable of finding specific symbols, words, or phrases, and editing them
Proxy | A way for accessing models via a "middleman"
Function Calling | Models can call actual functions you've defined and programmed, and pass structured data to them
Prefill | Forcing the model to start its output with a specified text. Useful for jailbreaking
Reasoning | Model thinking goes brrr
Refusal | Skill issue

# Guides

## How To Import A Preset?

> 💡 **Tip**
> Presets include instructions and settings for models. Different ones offer different experiences. There is no "best" or "worst" preset; it's all a matter of your personal preference. Use the one you like best, and feel free to write your own, custom ones!

![How to import a preset](https://i.imgur.com/liAlNTz.gif)

1. Open SillyTavern.
2. Go to the Chat Completion Presets tab by clicking the first icon from the left (sliders) at the top of the page.
3. Click the Import preset button (the one with the little arrow pointing at paper) at the top of the screen.
4. Select the file you want to import.
5. Open it.

You can access all of your imported presets at any time.

## How To Import A Regex?

> 💡 **Tip**
> Regexes aren't required, but they can improve formatting and fix errors in the outputs. For example, my regexes remove overused em-dashes, fix quotation marks, and turn `...` into `…`, reducing the overall token count.

![How to import a regex](https://i.imgur.com/t0GV1iq.gif)

1. Open SillyTavern.
2. Go to the Extensions tab by clicking the third icon from the right (cubes) at the top of the page.
3. Click on Regex.
4. Click the Import button (the one with the little arrow pointing at paper).
5. Select the file you want to import.
6. Open it.

## How To Import A Logit Bias?

> ❗**Important**
> Logit Bias works **ONLY** with OpenAI models (GPTs). I based mine on [Avi's](https://rentry.org/avaniJB), so all credit goes to them. !~ Logit Bias is a must if you want to use OAI models. ~!

> 💡 **Tip**
> Logit Bias allows you to control which tokens are more or less likely to appear in the model's output. The values can be set between -100 (semi-banning the specified token) and 100 (encouraging the model to use a token at every opportunity). Number 0 is neutral. Read more about it [here](https://help.openai.com/en/articles/5247780-using-logit-bias-to-alter-token-probability-with-the-openai-api).

![How to import a logit bias](https://i.imgur.com/gomeFrY.gif)

1. Open SillyTavern.
2. Go to the Chat Completion Presets tab by clicking the first icon from the left (sliders) at the top of the page.
3. Slide all the way down to the Logit Bias section.
4. Click the Import preset button (the one with the little arrow pointing at paper).
5. Select the file you want to import.
6. Open it.

## How To Import A Character Card?

> 💡 **Tip**
> Character cards are characters you chat or roleplay with. These don't necessarily have to be characters; they can also include assistants, narrators, and even entire worlds.

![How to import a character card](https://i.imgur.com/VULGDg2.gif)

1. Open SillyTavern.
2. Go to the Character Management tab by clicking the first icon from the right (card) at the top of the page.
3. Click the Import Character From File button (the one with the little arrow pointing at paper).
3. Select the character you want to import.
4. Open it.

# FAQ

- Q: What preset should I use?
	- A: Use whatever works for you. If you get too many refusals with mine, try someone else's or write your own. I can't test my prompt with every model in existence, in every possible scenario, with every possible character card.

- Q: Can I edit your preset?
	- A: Of course! I highly encourage it! You can use it as a base to build something personalized, or steal its parts to inject into other prompts. Experiment and find out what works best for you.

- Q: Why do you recommend turning off reasoning?
	- A: Because it's been [proven](https://ml-site.cdn-apple.com/papers/the-illusion-of-thinking.pdf) that models do not reason the way we think. Reasoning is obsolete for roleplay/creative writing purposes, and eats up many tokens. It was created with solving complex issues, not gooning in mind, which severely limits creativity and makes the outputs more deterministic. Nowadays, models are smart enough to track the current scene well enough to not have to think about all the details before responding.

- Q: What is the best format for writing character cards?
	- A: Plain text, though, again, everything that works, works. Personally, I've noticed the best results with well-structured descriptions in paragraphs. You can also enclose parts in respective XML tags, such as:

```
<appearance>
Your character's appearance here.
</appearance>
```

- Q: Can I use AI to generate my cards/lorebooks/presets?
	- A: Yes, though expect subpar results. The more effort you put into writing these yourself, the better the quality of output you'll get. By using synthetic data, you're encouraging models to fall into established patterns and get 'lazier'. You can always outline your ideas to the model or provide them with an example you want them to follow when generating stuff for you. Except, don't ever use AI-generated prompts; models **do not** know how to prompt themselves.

# Recommendations

## Top 10 Models

> 📌 **Note**
> Last updated on 19.08.2025

> 💡 **Tip**
> It's safe to assume the first model on the list is the one I'm currently using for main roleplay. Please keep in mind this is my subjective ranking, based on my own preferences.

> ⚠️ **Warning**
> **ChatGPT-4o** and **GPT-4o** are !~ two different models! ~! I know, not confusing at all. The one I recommend is `chatgpt-4o-latest` ('Latte'). The other one, GPT-4o, is pretty bad.

Position | Model | Context | Censorship | Strengths | Weaknesses
:----: | :----: | :----: | :----: | :----: | :----:
1 | [Claude Opus 4.1](https://openrouter.ai/anthropic/claude-opus-4.1) **ᴺᴱᵂ** | 200k | Low | Smartest one on the list, has a unique writing style and creativity | ~~Screw it, Opussy won, the only downside is it costs you a liver to use it.~~ Opus can't be beat. It's impossible. The writing is too good. The smarts even more so. Nothing else compares right now
2 | [GPT-5 Chat](https://openrouter.ai/openai/gpt-5-chat) **ᴺᴱᵂ** | 128k | Low | A terrible disappointment at first, but they fixed it, especially with how good the prose feels; now it's a smarter ChatGPT-4o | As all the other OAI models, it requires regexes and a logit bias to be good, plus there's no saying whether the upgrades are temporary
3 | [ChatGPT-4o](https://openrouter.ai/openai/chatgpt-4o-latest) | 128k | Low | Best conversational style, big knowledge base, very smart, funny | Unusable without proper regexes and a logit bias
4 | [Claude Sonnet 3.7](https://openrouter.ai/anthropic/claude-3.7-sonnet) | 200k | None | Excellent at both writing and roleplaying, works great on higher contexts (above 32k) | A little outdated
5 | [Kimi K2](https://openrouter.ai/moonshotai/kimi-k2) | 65k | Low | Concise, original, novel | Not so smart and struggled at higher contexts (above 32k)
6 | [Gemini 2.5 Pro](https://openrouter.ai/google/gemini-2.5-pro)/[Flash](https://openrouter.ai/google/gemini-2.5-flash) | 1mln | Medium | Very smart and good at instruction following | Echoing hell ("echoing?"), stiff prose with no logit bias to control some tokens' usage (prepare for a lot of "then" and "didn't"), it's a 50/50 chance the model is lobotomized on the day you use it
7 | [DeepSeek R1](https://openrouter.ai/deepseek/deepseek-r1-0528)/[V3](https://openrouter.ai/deepseek/deepseek-chat-v3-0324) | 163k | None | Creative and wild | Hard to control and struggles with repetition
8 | [Claude Sonnet 4](https://openrouter.ai/anthropic/claude-sonnet-4) | 200k | Low | Good style, very smart | Lacks 3.7's creative spark and is very passive
9 | [GPT-4.1](https://openrouter.ai/openai/gpt-4.1) | 1mln | Low | Good style, doesn't have an annoyingly positive bias, has a large working context window | Unusable without proper regexes and a logit bias, somewhat lacking in smarts
10 | [Grok 4](https://openrouter.ai/x-ai/grok-4) | 256k | None | Grok, is this true? | It's like a teenager going through puberty, so horny and not very smart
Extra | [NemoMix-Unleashed-12B](https://huggingface.co/MarinaraSpaghetti/NemoMix-Unleashed-12B) | 128k | None | Obligatory shill of my model, some claim it still holds up | Old and small

> ⚠️ **Warning**
> ~~I noticed some underlying issues with GPT-5. I'm barely able to control it; it feels like every time I get a generation, it's like a different model responding. Requires further testing. It may be shit, actually. It's just shit. Stick to ChatGPT-4o while you can.~~ They fixed GPT-5 at last, so I've added it to the ranking officially.

## Model Providers

Provider | Description
:----: | :----:
[Crystal Proxy](https://crystalsraw.me/models) | Proxy of my trusted friend. For just $20 a month, you can get access to pretty much every big model out there. I highly recommend checking it out, even if it's to hang out with us on her Discord server
[Anas Proxy](https://rentry.org/anas_proxy) **ᴺᴱᵂ** | New proxy, recommended by a friend. It offers a few models to choose from, including Opus and Sonnet with unlimited contexts. You pay either around $1 for unlimited requests per day of use, or for $2, you can buy 100 requests to use whenever you like. Tested, and everything works
[OpenRouter](https://openrouter.ai/) | I hope this one needs no introduction. This is currently the safest and easiest way to access all the models. Pay-as-you-go when using them

## Preset Creators

Creator | Description
:----: | :----:
[AvaniJB](https://rentry.org/avaniJB) | Good prompts, regexes, and logit biases (the last one, I shamelessly stole from them). Also, I love their little cat character
[Pixi](https://pixibots.neocities.org/) | The grandparent of prompting. One of my biggest inspirations
[Nemo Preset](https://github.com/NemoVonNirgend/NemoPresetExt) | Personally, I find this preset too big and unnecessarily bloated, but it's still a very well-written and well-thought-out preset! If large token numbers and customization options don't scare you, I suggest checking this one out
[Celia](https://leafcanfly.neocities.org/) | Customizable, creative, overall a great prompt. Plus, Celia is cute

## SillyTavern Themes

Theme | Description
:----: | :----:
[MoonlitEchoes](https://github.com/RivelleDays/SillyTavern-MoonlitEchoesTheme) | It's the one I'm currently using, and the one you can see on my screenshots! It's beautiful, I absolutely recommend it
[NemoEngine](https://github.com/NemoVonNirgend/NemoPresetExt/) **ᴺᴱᵂ** | Very convenient for prompt management, allows you to play videos and streams as a background for your chats (with sound), and improves on tabs' design.

## Discord Buddy

Hey, while you're here, perhaps you could also check out my [Discord Buddy](https://github.com/SpicyMarinara/Discord-Buddy) project? It's an LLM-powered Discord bot you can host. Open-source, free, with many, many great features. Check it out!

![Sevequiem](https://camo.githubusercontent.com/e0a197fb672dc840d4b9e1a13887855ec3fff93a3bc820dc9afef0e0fe549153/68747470733a2f2f692e696d6775722e636f6d2f4d5a47776937632e6a706567)

# Support Me

Enjoy what I do? Please, consider supporting me on Ko-fi! These donations help fund my models' testing and my prompt engineering endeavors!

[Ko-fi](https://ko-fi.com/marinara_spaghetti)

Thank you!

💙

# Contact

Discord:

`marinara_spaghetti`

E-mail:

`mgrabower97@gmail.com`

Socials:

`https://linktr.ee/Spicy_Marinara`

# Fanarts

<div align="center">
  <img src="https://i.imgur.com/SjQYnZD.png" alt="Vynocchi" style="width:18%; max-width:200px;">
  <img src="https://i.imgur.com/NbRDrCt.jpeg" alt="Huxnt3rx" style="width:18%; max-width:200px;">
  <img src="https://i.imgur.com/cKRfHeM.png" alt="Huxnt3rx" style="width:18%; max-width:200px;">
  <img src="https://i.imgur.com/t4vn272.png" alt="Xixica" style="width:18%; max-width:200px;">
  <img src="https://i.imgur.com/dhGFKvc.png" alt="Xixica" style="width:18%; max-width:200px;">
</div>
