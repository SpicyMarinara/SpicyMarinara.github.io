---
layout: default
---

<link rel="stylesheet" href="assets/css/custom.css">
<script>
function showTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tab-content");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].classList.remove("active");
  }
  tablinks = document.getElementsByClassName("tab-link");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].classList.remove("active");
  }
  document.getElementById(tabName).classList.add("active");
  evt.currentTarget.classList.add("active");
}

// Set first tab as active by default
document.addEventListener('DOMContentLoaded', function() {
  document.querySelector('.tab-link').click();
});
</script>

<div class="neon-title">
  <h1 class="neon-text">Marinara's LLM Hub</h1>
</div>

![The Official Dottore Schizo Gooner](https://i.imgur.com/Qsszm6i.gif){: style="max-width: 400px; height: auto; display: block; margin: 0 auto 2rem auto; border-radius: 8px;"}

<div class="tab-container">
  <div class="tab-nav">
    <button class="tab-link active" onclick="showTab(event, 'downloads')">Downloads</button>
    <button class="tab-link" onclick="showTab(event, 'about')">About</button>
    <button class="tab-link" onclick="showTab(event, 'lexicon')">Lexicon</button>
    <button class="tab-link" onclick="showTab(event, 'guides')">Guides</button>
    <button class="tab-link" onclick="showTab(event, 'faq')">FAQ</button>
    <button class="tab-link" onclick="showTab(event, 'recommendations')">Recommendations</button>
    <button class="tab-link" onclick="showTab(event, 'support')">Support</button>
    <button class="tab-link" onclick="showTab(event, 'contact')">Contact</button>
    <button class="tab-link" onclick="showTab(event, 'fanarts')">Fanarts</button>
  </div>

  <div id="downloads" class="tab-content active">
    <img src="https://i.imgur.com/p9xhDD8.png" alt="Dottore Banner" style="max-width: 100%; height: auto; margin: 0 auto 2rem auto; border-radius: 8px; display: block;">
    
    <h1>Downloads</h1>

    <div class="notification-box note">
      <div class="notification-title">Note</div>
      <div class="notification-content">The newest version is 6.0.</div>
    </div>

    <div class="notification-box tip">
      <div class="notification-title">Tip</div>
      <div class="notification-content">The preset below is for Chat Completion only. For my older Text Completion presets, visit my <a href="https://huggingface.co/MarinaraSpaghetti/SillyTavern-Settings">HuggingFace</a>.</div>
    </div>

    <div class="notification-box warning">
      <div class="notification-title">Warning</div>
      <div class="notification-content">My presets are designed for chatting, roleplaying, and fiction writing with LLMs. Due to their uncensored nature, they are intended for adults only. <ins>By downloading the files below, you confirm that you are 18 years of age or older and acknowledge that I am not responsible for any content you create or share using these presets.</ins></div>
    </div>

    <table>
      <thead>
        <tr>
          <th>Link</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><a href="https://github.com/SpicyMarinara/SillyTavern-Settings/blob/main/Marinara's%20Essentials.zip">Master Download</a></td>
          <td>Downloads the entire .zip file that includes the preset, regexes, logit bias, and character cards</td>
        </tr>
        <tr>
          <td><a href="https://github.com/SpicyMarinara/SillyTavern-Settings/tree/main/Marinara's%20Essentials/Preset">Preset</a></td>
          <td>Universal preset alone</td>
        </tr>
        <tr>
          <td><a href="https://github.com/SpicyMarinara/SillyTavern-Settings/tree/main/Marinara's%20Essentials/Regexes">Regexes</a></td>
          <td>Regexes that clean formatting errors, remove em dashes, and unify formats</td>
        </tr>
        <tr>
          <td><a href="https://github.com/SpicyMarinara/SillyTavern-Settings/tree/main/Marinara's%20Essentials/Logit%20Bias">Logit Bias</a></td>
          <td>Logit bias for OpenAI models</td>
        </tr>
        <tr>
          <td><a href="https://github.com/SpicyMarinara/SillyTavern-Settings/blob/main/Marinara's%20Essentials/Cards/Professor%20Mari.png">Professor Mari</a></td>
          <td>Professor Mari's character card, an assistant who will teach you all about LLMs and help you out with creating character cards</td>
        </tr>
        <tr>
          <td><a href="https://github.com/SpicyMarinara/SillyTavern-Settings/blob/main/Marinara's%20Essentials/Cards/Dottore.png">Dottore</a></td>
          <td>Dottore's character card, the Second of the Eleven Fatui Harbingers from Genshin Impact</td>
        </tr>
      </tbody>
    </table>

    <img src="https://i.imgur.com/G610Q95.png" alt="How to download" style="max-width: 100%; height: auto;">
  </div>

  <div id="about" class="tab-content">
    <h1>About</h1>
    
    <p>Howdy, I'm Marinara!</p>

    <p>An LLM enthusiast, teacher, merger, and prompt engineer since late 2023. Additionally, an artist and coder on occasion. I'm the author of models such as <a href="https://huggingface.co/MarinaraSpaghetti/NemoMix-Unleashed-12B">NemoMix Unleashed</a> and many universal prompts, including professional ones for companies like <a href="https://www.tolans.com/">Tolan</a>, <a href="https://www.mydreamcompanion.com/">MyDreamCompanion</a>, or <a href="https://toffee.ai/">Toffee.ai</a>. I consult for various AI services and offer commissions for cards, prompts, and artworks.</p>

    <p>Here you can find my roleplaying and creative writing presets, as well as recommendations, cards, and guides. All related to LLMs. Feel free to suggest new sections to add or models to test. I hope you'll find it informative, helpful, and fun to read.</p>

    <p>Cheers and happy gooning!</p>
  </div>

  <div id="lexicon" class="tab-content">
    <h1>Lexicon</h1>
    
    <table>
      <thead>
        <tr>
          <th>Term</th>
          <th>Definition</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>LLM</td>
          <td>Large Language Model (AI Model)</td>
        </tr>
        <tr>
          <td>SillyTavern</td>
          <td>Frontend for AI use, the one I create my presets for (<a href="https://github.com/SillyTavern/SillyTavern">https://github.com/SillyTavern/SillyTavern</a>)</td>
        </tr>
        <tr>
          <td>Prompt</td>
          <td>What you send to the model. This includes everything: instructions, cards, lorebook entries, example messages, and the chat history</td>
        </tr>
        <tr>
          <td>Jailbreak</td>
          <td>Part of the prompt that is responsible for "jailbreaking," aka "removing censorship" from the model</td>
        </tr>
        <tr>
          <td>Preset</td>
          <td>A pre-set format of how you send the prompt to the model. These typically involve instructions, optional jailbreaks, and sampler settings</td>
        </tr>
        <tr>
          <td>(Character) Card</td>
          <td>Typically a description of a character that may include their image, personality, and example message</td>
        </tr>
        <tr>
          <td>Persona</td>
          <td>Like a character card, but for the character you play as</td>
        </tr>
        <tr>
          <td>Scenario</td>
          <td>An outline of what happens in the roleplay</td>
        </tr>
        <tr>
          <td>Lorebooks (World Info)</td>
          <td>Prompt entries that trigger based on activated keywords</td>
        </tr>
        <tr>
          <td>Samplers</td>
          <td>Algorithms or methods used to decide which token the model should pick next when generating text</td>
        </tr>
        <tr>
          <td>Temperature</td>
          <td>One of the samplers that controls how creative the output is allowed to be. Numbers closer to zero produce more deterministic outputs, while those closer to 1 and above are more creative</td>
        </tr>
        <tr>
          <td>Tokens</td>
          <td>Building blocks of text sent to the models. These include symbols, letters, words, and codes</td>
        </tr>
        <tr>
          <td>Context</td>
          <td>How many tokens the model can process at once, e.g., 32k. The larger the number, the more it remembers</td>
        </tr>
        <tr>
          <td>Chat Completion</td>
          <td>Format of sending the prompt as a structured conversation, with clear distinctions between different roles (user, assistant, system). Used when you access models via API</td>
        </tr>
        <tr>
          <td>User</td>
          <td>All the messages that count as being sent from the human (you)</td>
        </tr>
        <tr>
          <td>Assistant</td>
          <td>All the messages that count as being sent from the AI (model)</td>
        </tr>
        <tr>
          <td>System</td>
          <td>Instructions for the model, appended before the start of the conversation</td>
        </tr>
        <tr>
          <td>Text Completion</td>
          <td>Format of sending the prompt to the model as a big wall of text, and asking it to "complete it" (hence the name). Used with locally run models</td>
        </tr>
        <tr>
          <td>Input</td>
          <td>Your last sent message to the model</td>
        </tr>
        <tr>
          <td>Output</td>
          <td>Model's response</td>
        </tr>
        <tr>
          <td>Logit Bias</td>
          <td>A way to manipulate the probability of specific tokens by either banning them completely or encouraging the model to use them more often</td>
        </tr>
        <tr>
          <td>Regex</td>
          <td>Search language for string, capable of finding specific symbols, words, or phrases, and editing them</td>
        </tr>
        <tr>
          <td>Proxy</td>
          <td>A way for accessing models via a "middleman"</td>
        </tr>
        <tr>
          <td>Function Calling</td>
          <td>Models can call actual functions you've defined and programmed, and pass structured data to them</td>
        </tr>
        <tr>
          <td>Prefill</td>
          <td>Forcing the model to start its output with a specified text. Useful for jailbreaking</td>
        </tr>
        <tr>
          <td>Reasoning</td>
          <td>Model thinking goes brrr</td>
        </tr>
        <tr>
          <td>Refusal</td>
          <td>Skill issue</td>
        </tr>
      </tbody>
    </table>
  </div>

  <div id="guides" class="tab-content">
    <h1>Guides</h1>

    <h2>How To Import A Preset?</h2>

    <div class="notification-box tip">
      <div class="notification-title">Tip</div>
      <div class="notification-content">Presets include instructions and settings for models. Different ones offer different experiences. There is no "best" or "worst" preset; it's all a matter of your personal preference. Use the one you like best, and feel free to write your own, custom ones!</div>
    </div>

    <img src="https://i.imgur.com/liAlNTz.gif" alt="How to import a preset" style="max-width: 100%; height: auto;">

    <ol>
      <li>Open SillyTavern.</li>
      <li>Go to the Chat Completion Presets tab by clicking the first icon from the left (sliders) at the top of the page.</li>
      <li>Click the Import preset button (the one with the little arrow pointing at paper) at the top of the screen.</li>
      <li>Select the file you want to import.</li>
      <li>Open it.</li>
    </ol>

    <p>You can access all of your imported presets at any time.</p>

    <h2>How To Import A Regex?</h2>

    <div class="notification-box tip">
      <div class="notification-title">Tip</div>
      <div class="notification-content">Regexes aren't required, but they can improve formatting and fix errors in the outputs. For example, my regexes remove overused em-dashes, fix quotation marks, and turn <code>...</code> into <code>…</code>, reducing the overall token count.</div>
    </div>

    <img src="https://i.imgur.com/t0GV1iq.gif" alt="How to import a regex" style="max-width: 100%; height: auto;">

    <ol>
      <li>Open SillyTavern.</li>
      <li>Go to the Extensions tab by clicking the third icon from the right (cubes) at the top of the page.</li>
      <li>Click on Regex.</li>
      <li>Click the Import button (the one with the little arrow pointing at paper).</li>
      <li>Select the file you want to import.</li>
      <li>Open it.</li>
    </ol>

    <h2>How To Import A Logit Bias?</h2>

    <div class="notification-box warning">
      <div class="notification-title">Warning</div>
      <div class="notification-content">Logit Bias works <strong>ONLY</strong> with OpenAI models (GPTs). I based mine on <a href="https://rentry.org/avaniJB">Avi's</a>, so all credit goes to them. <ins>Logit Bias is a must if you want to use OAI models.</ins></div>
    </div>

    <div class="notification-box tip">
      <div class="notification-title">Tip</div>
      <div class="notification-content">Logit Bias allows you to control which tokens are more or less likely to appear in the model's output. The values can be set between -100 (semi-banning the specified token) and 100 (encouraging the model to use a token at every opportunity). Number 0 is neutral. <a href="https://help.openai.com/en/articles/5247780-using-logit-bias-to-alter-token-probability-with-the-openai-api">Read more about it here</a>.</div>
    </div>

    <img src="https://i.imgur.com/gomeFrY.gif" alt="How to import a logit bias" style="max-width: 100%; height: auto;">

    <ol>
      <li>Open SillyTavern.</li>
      <li>Go to the Chat Completion Presets tab by clicking the first icon from the left (sliders) at the top of the page.</li>
      <li>Slide all the way down to the Logit Bias section.</li>
      <li>Click the Import preset button (the one with the little arrow pointing at paper).</li>
      <li>Select the file you want to import.</li>
      <li>Open it.</li>
    </ol>

    <h2>How To Import A Character Card?</h2>

    <div class="notification-box tip">
      <div class="notification-title">Tip</div>
      <div class="notification-content">Character cards are characters you chat or roleplay with. These don't necessarily have to be characters; they can also include assistants, narrators, and even entire worlds.</div>
    </div>

    <img src="https://i.imgur.com/VULGDg2.gif" alt="How to import a character card" style="max-width: 100%; height: auto;">

    <ol>
      <li>Open SillyTavern.</li>
      <li>Go to the Character Management tab by clicking the first icon from the right (card) at the top of the page.</li>
      <li>Click the Import Character From File button (the one with the little arrow pointing at paper).</li>
      <li>Select the character you want to import.</li>
      <li>Open it.</li>
    </ol>

    <h2>How To Edit & Toggle Prompts?</h2>

    <div class="notification-box tip">
      <div class="notification-title">Tip</div>
      <div class="notification-content">My prompt is plug-and-play, but you may want to edit it or toggle some optional stuff.</div>
    </div>

    <img src="https://i.imgur.com/jupZFMm.gif" alt="How to edit and toggle prompts" style="max-width: 100%; height: auto;">

    <ol>
      <li>Open SillyTavern.</li>
      <li>Go to the Chat Completion Presets tab by clicking the first icon from the left (sliders) at the top of the page.</li>
      <li>Slide all the way down to the Prompts section.</li>
      <li>Click on the small pencil icon on the right side of the prompt to view its contents and edit it.</li>
      <li>Click on the small toggle button on the right side of the prompt to enable/disable it.</li>
    </ol>
  </div>

  <div id="faq" class="tab-content">
    <h1>FAQ</h1>

    <div class="notification-box note">
      <div class="notification-title">Q: I see some parts of your prompts in {{// this format. }}{{trim}} What does it mean? Won't it confuse the models?</div>
      <div class="notification-content">A: This is formatting for comments on SillyTavern. Any text rendered like that won't be sent to the LLM with your request. Only you can read it. The trim part ensures no empty new lines are sent.</div>
    </div>

    <div class="notification-box note">
      <div class="notification-title">Q: Why are some of your prompts empty, but left enabled anyway?</div>
      <div class="notification-content">A: Some shared character cards include custom prompts and jailbreaks. They will be placed in those empty prompts.</div>
    </div>

    <div class="notification-box note">
      <div class="notification-title">Q: What preset should I use?</div>
      <div class="notification-content">A: Use whatever works for you. If you get too many refusals with mine, try someone else's or write your own. I can't test my prompt with every model in existence, in every possible scenario, with every possible character card.</div>
    </div>

    <div class="notification-box note">
      <div class="notification-title">Q: Can I edit your preset?</div>
      <div class="notification-content">A: Of course! I highly encourage it! You can use it as a base to build something personalized, or steal its parts to inject into other prompts. Experiment and find out what works best for you.</div>
    </div>

    <div class="notification-box note">
      <div class="notification-title">Q: Why do you recommend turning off reasoning?</div>
      <div class="notification-content">A: Because it's been <a href="https://ml-site.cdn-apple.com/papers/the-illusion-of-thinking.pdf">proven</a> that models do not reason the way we think. Reasoning is obsolete for roleplay/creative writing purposes, and eats up many tokens. It was created with solving complex issues, not gooning in mind, which severely limits creativity and makes the outputs more deterministic. Nowadays, models are smart enough to track the current scene well enough to not have to think about all the details before responding.</div>
    </div>

    <div class="notification-box note">
      <div class="notification-title">Q: What is the best format for writing character cards?</div>
      <div class="notification-content">A: Plain text, though, again, everything that works, works. Personally, I've noticed the best results with well-structured descriptions in paragraphs. You can also enclose parts in respective XML tags, such as:<br><br><code>&lt;appearance&gt;<br>Your character's appearance here.<br>&lt;/appearance&gt;</code></div>
    </div>

    <div class="notification-box note">
      <div class="notification-title">Q: Can I use AI to generate my cards/lorebooks/presets?</div>
      <div class="notification-content">A: Yes, though expect subpar results. The more effort you put into writing these yourself, the better the quality of output you'll get. By using synthetic data, you're encouraging models to fall into established patterns and get 'lazier'. You can always outline your ideas to the model or provide them with an example you want them to follow when generating stuff for you. Except, don't ever use AI-generated prompts; models <strong>do not</strong> know how to prompt themselves.</div>
    </div>

    <div class="notification-box note">
      <div class="notification-title">Q: Which Prompt Post-Processing do I use?</div>
      <div class="notification-content">A: Merge consecutive roles (no tools).</div>
    </div>
  </div>

  <div id="recommendations" class="tab-content">
    <h1>Recommendations</h1>

    <h2>Recommended Models</h2>

    <div class="notification-box note">
      <div class="notification-title">Note</div>
      <div class="notification-content">Last updated on 07.09.2025</div>
    </div>

    <div class="notification-box tip">
      <div class="notification-title">Tip</div>
      <div class="notification-content">It's safe to assume the first model on the list is the one I'm currently using for main roleplay. Please keep in mind this is my subjective ranking, based on my own preferences.</div>
    </div>

    <div class="notification-box warning">
      <div class="notification-title">Warning</div>
      <div class="notification-content"><strong>ChatGPT-4o</strong> and <strong>GPT-4o</strong> are <ins>two different models!</ins> I know, not confusing at all. The one I recommend is <code>chatgpt-4o-latest</code> ('Latte'). The other one, GPT-4o, is pretty bad.</div>
    </div>

    <table>
      <thead>
        <tr>
          <th>Position</th>
          <th>Model</th>
          <th>Context</th>
          <th>Censorship</th>
          <th>Strengths</th>
          <th>Weaknesses</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td><a href="https://openrouter.ai/anthropic/claude-opus-4.1">Claude Opus 4.1</a></td>
          <td>200k</td>
          <td>Low</td>
          <td>Smartest one on the list, has a unique writing style and creativity</td>
          <td>~~Screw it, Opussy won, the only downside is it costs you a liver to use it.~~ Opus can't be beat. It's impossible. The writing is too good. The smarts even more so. Nothing else compares right now</td>
        </tr>
        <tr>
          <td>2</td>
          <td><a href="https://openrouter.ai/openai/gpt-5">GPT-5</a> <strong>ᴺᴱᵂ</strong></td>
          <td>400k</td>
          <td>Low</td>
          <td>A true endgame boss for prompters, once you figure it out, it's a real beast. Will do anything you ask it to do</td>
          <td>Again, a nightmare to prompt, and without a good one, it simply doesn't work. Works better in higher contexts than Opus, but lacks its emotional intelligence. Also, needs high thinking to be decent</td>
        </tr>
        <tr>
          <td>3</td>
          <td><a href="https://openrouter.ai/openai/chatgpt-4o-latest">ChatGPT-4o</a></td>
          <td>128k</td>
          <td>Low</td>
          <td>Best conversational style, big knowledge base, very smart, funny</td>
          <td>Unusable without proper regexes and a logit bias</td>
        </tr>
        <tr>
          <td>4</td>
          <td><a href="https://openrouter.ai/openai/gpt-5-chat">GPT-5 Chat</a></td>
          <td>128k</td>
          <td>Low</td>
          <td>A terrible disappointment at first, but they fixed it, especially with how good the prose feels; now it's a smarter ChatGPT-4o</td>
          <td>As all the other OAI models, it requires regexes and a logit bias to be good, plus its prose is slightly worse than ChatGPT-4o's</td>
        </tr>
        <tr>
          <td>5</td>
          <td><a href="https://openrouter.ai/anthropic/claude-sonnet-4">Claude Sonnet 4</a></td>
          <td>200k</td>
          <td>Low</td>
          <td>Good style, very smart</td>
          <td>Lacks 3.7's creative spark and is very passive</td>
        </tr>
        <tr>
          <td>6</td>
          <td><a href="https://openrouter.ai/anthropic/claude-3.7-sonnet">Claude Sonnet 3.7</a></td>
          <td>200k</td>
          <td>None</td>
          <td>Excellent at both writing and roleplaying, works great on higher contexts (above 32k)</td>
          <td>A little outdated</td>
        </tr>
        <tr>
          <td>7</td>
          <td><a href="https://openrouter.ai/moonshotai/kimi-k2">Kimi K2</a></td>
          <td>65k</td>
          <td>Low</td>
          <td>Concise, original, novel</td>
          <td>Not so smart and struggled at higher contexts (above 32k)</td>
        </tr>
        <tr>
          <td>8</td>
          <td><a href="https://openrouter.ai/google/gemini-2.5-pro">Gemini 2.5 Pro</a>/<a href="https://openrouter.ai/google/gemini-2.5-flash">Flash</a></td>
          <td>1mln</td>
          <td>Medium</td>
          <td>Very smart and good at instruction following</td>
          <td>Echoing hell ("echoing?"), stiff prose with no logit bias to control some tokens' usage (prepare for a lot of "then" and "didn't"), it's a 50/50 chance the model is lobotomized on the day you use it</td>
        </tr>
        <tr>
          <td>9</td>
          <td><a href="https://openrouter.ai/deepseek/deepseek-r1-0528">DeepSeek R1</a>/<a href="https://openrouter.ai/deepseek/deepseek-chat-v3-0324">V3</a></td>
          <td>163k</td>
          <td>None</td>
          <td>Creative and wild</td>
          <td>Hard to control and struggles with repetition</td>
        </tr>
        <tr>
          <td>10</td>
          <td><a href="https://openrouter.ai/openai/gpt-4.1">GPT-4.1</a></td>
          <td>1mln</td>
          <td>Low</td>
          <td>Good style, doesn't have an annoyingly positive bias, has a large working context window</td>
          <td>Unusable without proper regexes and a logit bias, somewhat lacking in smarts</td>
        </tr>
        <tr>
          <td>11</td>
          <td><a href="https://openrouter.ai/x-ai/grok-4">Grok 4</a></td>
          <td>256k</td>
          <td>None</td>
          <td>Grok, is this true?</td>
          <td>It's like a teenager going through puberty, so horny and not very smart</td>
        </tr>
        <tr>
          <td>12</td>
          <td><a href="https://openrouter.ai/deepseek/deepseek-chat-v3.1">DeepSeek V3.1</a> <strong>ᴺᴱᵂ</strong></td>
          <td>165k</td>
          <td>Low</td>
          <td>It just works</td>
          <td>Worse than V.3 and R1 in every single aspect. What were they thinking</td>
        </tr>
        <tr>
          <td>Extra</td>
          <td><a href="https://huggingface.co/MarinaraSpaghetti/NemoMix-Unleashed-12B">NemoMix-Unleashed-12B</a></td>
          <td>128k</td>
          <td>None</td>
          <td>Obligatory shill of my model, some claim it still holds up</td>
          <td>Old and small</td>
        </tr>
      </tbody>
    </table>

    <div class="notification-box warning">
      <div class="notification-title">Warning</div>
      <div class="notification-content">~~I noticed some underlying issues with GPT-5. I'm barely able to control it; it feels like every time I get a generation, it's like a different model responding. Requires further testing. It may be awful, actually. It's just shit. Stick to ChatGPT-4o while you can.~~ They fixed GPT-5 at last, so I've added it to the ranking officially.</div>
    </div>

    <h2>Model Providers</h2>

    <div class="notification-box note">
      <div class="notification-title">Note</div>
      <div class="notification-content">If a proxy is listed here, it means I personally tested it and its owner agreed to being mentioned on this page.</div>
    </div>

    <table>
      <thead>
        <tr>
          <th>Provider</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><a href="https://crystalsraw.me/models">Crystal Proxy</a></td>
          <td>Proxy of my trusted friend. For just $20 a month, you can get access to every big model out there. I highly recommend checking it out, even if it's to hang out with us on her Discord server</td>
        </tr>
        <tr>
          <td><a href="https://rentry.org/anas_proxy">Anas Proxy</a></td>
          <td>Proxy recommended by a friend. It offers a few models to choose from, including Opus and Sonnet with unlimited contexts. You pay either around $1 for unlimited requests per day of use, or for $2, you can buy 100 requests to use whenever you like. Tested, and everything works</td>
        </tr>
        <tr>
          <td><a href="https://discord.gg/G3qVMhDZTe">4risu</a> <strong>ᴺᴱᵂ</strong></td>
          <td>I accidentally stumbled upon this proxy, but it proved awesome, and the owners are kind. Has a free tier and a paid tier with less downtime and more models to choose from. Just remember to grab an English role if you don't speak Spanish</td>
        </tr>
        <tr>
          <td><a href="https://openrouter.ai/">OpenRouter</a></td>
          <td>I hope this one needs no introduction. This is currently the safest and easiest way to access all the models. Pay-as-you-go when using them</td>
        </tr>
      </tbody>
    </table>

    <h2>Preset Creators</h2>

    <table>
      <thead>
        <tr>
          <th>Creator</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><a href="https://rentry.org/avaniJB">AvaniJB</a></td>
          <td>Good prompts, regexes, and logit biases (the last one, I shamelessly stole from them). Also, I love their little cat character</td>
        </tr>
        <tr>
          <td><a href="https://pixibots.neocities.org/">Pixi</a></td>
          <td>The grandparent of prompting. One of my biggest inspirations</td>
        </tr>
        <tr>
          <td><a href="https://github.com/NemoVonNirgend/NemoPresetExt">Nemo Preset</a></td>
          <td>Personally, I find this preset too big and unnecessarily bloated, but it's still a very well-written and well-thought-out preset! If large token numbers and customization options don't scare you, I suggest checking this one out</td>
        </tr>
        <tr>
          <td><a href="https://leafcanfly.neocities.org/">Celia</a></td>
          <td>Customizable, creative, overall a great prompt. Plus, Celia is cute</td>
        </tr>
        <tr>
          <td><a href="https://discord.gg/GxwmKtSJV2">AI Presets</a> <strong>ᴺᴱᵂ</strong></td>
          <td>Discord server containing many great prompts from amazing creators such as Loggo, Gerodot, Ashu, Chi-Bi, Nara, and others.</td>
        </tr>
      </tbody>
    </table>

    <h2>SillyTavern Themes</h2>

    <table>
      <thead>
        <tr>
          <th>Theme</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><a href="https://github.com/RivelleDays/SillyTavern-MoonlitEchoesTheme">MoonlitEchoes</a></td>
          <td>It's the one I'm currently using, and the one you can see on my screenshots! It's beautiful, I absolutely recommend it</td>
        </tr>
        <tr>
          <td><a href="https://github.com/NemoVonNirgend/NemoPresetExt/">NemoEngine</a></td>
          <td>Very convenient for prompt management, allows you to play videos and streams as a background for your chats (with sound), and improves on tabs' design.</td>
        </tr>
      </tbody>
    </table>

    <h2>Discord Buddy</h2>

    <p>Hey, while you're here, perhaps you could also check out my <a href="https://github.com/SpicyMarinara/Discord-Buddy">Discord Buddy</a> project? It's an LLM-powered Discord bot you can host. Open-source, free, with many, many great features. Check it out!</p>

    <img src="https://camo.githubusercontent.com/e0a197fb672dc840d4b9e1a13887855ec3fff93a3bc820dc9afef0e0fe549153/68747470733a2f2f692e696d6775722e636f6d2f4d5a47776937632e6a706567" alt="Sevequiem" style="max-width: 100%; height: auto;">
  </div>

  <div id="support" class="tab-content">
    <h1>Support Me</h1>
    
    <p>Enjoy what I do? Please, consider supporting me on Ko-fi! These donations help fund my models' testing and my prompt engineering endeavors!</p>

    <p><a href="https://ko-fi.com/marinara_spaghetti">Ko-fi</a></p>

    <p>Thank you!</p>

    <p>💙</p>
  </div>

  <div id="contact" class="tab-content">
    <h1>Contact</h1>
    
    <h2>Discord:</h2>
    <p><code>marinara_spaghetti</code></p>

    <h2>E-mail:</h2>
    <p><code>mgrabower97@gmail.com</code></p>

    <h2>Socials:</h2>
    <p><a href="https://linktr.ee/Spicy_Marinara">https://linktr.ee/Spicy_Marinara</a></p>
  </div>

  <div id="fanarts" class="tab-content">
    <h1>Fanarts</h1>
    
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; margin: 2rem 0;">
      <img src="https://i.imgur.com/p6rhYTF.gif" alt="Huxnt3rx" style="width: 100%; border-radius: 8px;">
      <img src="https://i.imgur.com/SjQYnZD.png" alt="Vynocchi" style="width: 100%; border-radius: 8px;">
      <img src="https://i.imgur.com/NbRDrCt.jpeg" alt="Huxnt3rx" style="width: 100%; border-radius: 8px;">
      <img src="https://i.imgur.com/cKRfHeM.png" alt="Huxnt3rx" style="width: 100%; border-radius: 8px;">
      <img src="https://i.imgur.com/t4vn272.png" alt="Xixica" style="width: 100%; border-radius: 8px;">
      <img src="https://i.imgur.com/dhGFKvc.png" alt="Xixica" style="width: 100%; border-radius: 8px;">
      <img src="https://i.imgur.com/5X67Oks.jpeg" alt="s0lu" style="width: 100%; border-radius: 8px;">
      <img src="https://i.imgur.com/OG9jwmB.gif" alt="Huxnt3rx" style="width: 100%; border-radius: 8px;">
    </div>
  </div>

</div>
