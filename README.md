# AI Tools Catalogue
> A categorized list of AI tools with descriptions and links.
> Feel free to contribute via issues or pull requests!

Hello! I have over time gathered and categorized a list of AI Tools. I will also describe some of the workflows that can be used for awesome end results.

## Contributing

* Please open a [PR](https://guides.github.com/activities/forking/) for list of top AI tools to be added.
* Use the format below.

## Format

Categorized list of AI Tools.

Format for tools:
```

| Tool | Description |
|----- | ----------- |
|[ChatGPT](https://chatgpt.com/)|Generative AI chatbot, supports omni and reasoning models|
|[]()||
```

Format for workflows:
```
| Name | Workflow (name the tools) | Example |
|----- | ------------------------- | ------- |
|Music video|A -> B -> C| example |
```

## Contents

- [Workflows](#workflows)
- [Companion chatbots](#companion-chatbots)
- [Image generation](#image-generation)
- [Video generation](#video-generation)
- [Audio generation and tools](#audio-tools)
  - [Voice tools](#voice-tools)
  - [Music creation](#music-creation)
- [Software engineering tools](#software-engineering-tools)
  - [Models for software engineering](#best-models-for-software-engineering)
  - [API Providers](#api-providers)
- [Agents and automation](#agents-and-automation)
- [Research tools](#research-tools)
- [Presentation and design tools](#presentation-and-design-tools)
- [Various tools](#various-tools)
  - [Business tools](#business-tools)
  - [Automated caller](#automated-caller)
  - [Photo editing](#photo-editing)
  - [Writing](#writing)
  - [3D Models and texture generation](#3d-models-and-texture-generation)
- [How to run models locally](#how-to-run-models-locally)
  - [List of models that can be run locally](#list-of-models-that-can-be-run-locally)
- [Other AI tools list providers](#ai-tools-list-providers)
- [Some literature and articles](#literature-and-articles)
- [Helping services (not AI)](#helping-services)


## Workflows
| Name | Workflow (name the tools) | Additional notes |
|----- | ------------------------- | ---------------- |
|Animations|Generate images in Midjourney and turn it to video clips in Luma Ray 2; Sound: MMAudio, Music: Suno AI|For Japanese-style animation use Midjourney Niji mode|
|Coding with Bot agent|VS Code + Cline bot|This is the most popular way|
|Coding with Bot agent|VS Code + Roo Code bot|Roo Code has become very popular spinoff from Cline|
|Coding with Bot agent|VS Code + Github Copilot|The oldest coding assistant has evolved into Agent territory|

## Companion Chatbots
| Tool | Description |
|----- | ----------- |
|[ChatGP by OpenAI](https://chatgpt.com/)|Generative AI chatbot, omni and reasoning model, API, enterprise solutions|
|[Google Gemini](https://gemini.google.com/app)|Google's Gemini chatbot|
|[Grok by xAI](https://x.ai/grok)|Unfiltered answers with advanced capabilities in reasoning, coding, and visual processing.|
|[DeepSeek](https://www.deepseek.com/)|Generative AI chatbot, omni (V3), reasoning (R1) and API. This is open source!|
|[Claude by Anthropic](https://www.anthropic.com/)|Advanced companion, one of the best for coding, enterprise, API|
|[Mistral Le Chat](https://mistral.ai/products/le-chat)|Le Chat combines powerful AI with extensive information access to help you get any job done, from cooking to coding.|
|[Huggingface Chat](https://huggingface.co/chat/)|Chatbot with open source models - Llama, Deepseek R1|
|[T3 chat](https://t3.chat/chat)|Chat with different model - Gemini 2.0 Flash, gpt-4o, o3-mini, claude 3.5 sonnet, DeepSeek V3 & R1|
|[Groq](https://groq.com/)|Chat with various Open-source AI models, API, possibly the fastest service!|

## Image generation
| Tool | Description |
|----- | ----------- |
|[Midjourney](https://www.midjourney.com/)|Probably the best image generation tools available. Check out the [Niji mode!](https://runtheprompts.com/resources/midjourney-info/what-is-midjourney-niji-mode-plus-examples/) and also this [Niji mode tutorial](https://cheatsheet.md/midjourney/what-is-midjourney-niji)|
|[Flux AI 1.1 Pro Ultra](https://flux1.ai/features/flux1-pro-ultra)|Generate ultra-high resolution images up to 4MP while maintaining incredibly fast 10-second generation times.|
|[Stable Diffusion](https://stability.ai/news/introducing-stable-diffusion-3-5)|Amazing image generation tool, can be run locally as well|
|[Imagen 3](https://deepmind.google/technologies/imagen-3/)|Google: Our highest quality text-to-image model|
|[Janus Pro 7B](https://januspro.org/)|One of the best tools for local image generation - [Janus github link](https://github.com/deepseek-ai/Janus) |
|[Leonardo AI](https://leonardo.ai/)|Leverage generative AI with a unique suite of tools to convey your ideas to the world.|
|[LensGo](https://lensgo.ai/)|Image generation platform, last time i tried it was slow|
|[Krea AI](https://www.krea.ai/home)|Very nice image creation platform|
|[ImageBind by Meta](https://imagebind.metademolab.com/)|AI model capable of binding data from six modalities at once, without the need for explicit supervision. By recognizing the relationships between these modalities — images and video, audio, text, depth, thermal and inertial measurement units (IMUs) — this breakthrough helps advance AI by enabling machines to better analyze many different forms of information, together.|
|[Ideogram](https://ideogram.ai/)|Ideogram is a free-to-use AI tool that generates realistic images, posters, logos and more.|
|[Skybox AI by Blockade Labs](https://www.skyboxai.net/)|Create stunning 360° skybox environments quickly and effortlessly.|
|[Human Generator](https://generated.photos/human-generator)|Generate realistic photos of humans|
|[Huggingface](https://huggingface.co/tasks/text-to-image)|Text to image models at Huggingface platform|

## Video generation
| Tool | Description |
|----- | ----------- |
|[Luma Labs Ray2](https://lumalabs.ai/ray)|Ray2 is a large–scale video generative model capable of creating realistic visuals with natural, coherent motion. It has strong understanding of text instructions and can take image and video as input.|
|[Kling 1.6](https://klingai.com)|AI creative studio, generate video and images|
|[Google Veo 2](https://deepmind.google/technologies/veo/veo-2/)|State-of-the-art video generation model|
|[Viggle AI](https://www.viggle.ai/)|Move your character, swap etc|
|[Heygen](https://www.heygen.com/)|Video avatar - produce studio-quality videos in 175 languages without a camera or crew.|
|[Hailuo AI](https://hailuoai.video/)|Reimagine video creation, unleash your creativity|
|[Stable Video Diffusion](https://stability.ai/stable-video)|Generate video from image|
|[Runway](https://runwayml.com/)|Text, Image and Video to Video. Allows to generate 3D object and change perspective of an image|
|[Moonvalley](https://moonvalley.ai)|Text to cinematic video|
|[Klap](https://klap.app/)|Turn videos into viral shorts/tiktok|
|[Animate Anyone](https://humanaigc.github.io/animate-anyone/)|Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation|
|[Akool](https://akool.com/)|Cutting-Edge Gen AI Platform for Avatar Creation, Marketing, Sales, Film Production, Education, Video Production|

## Audio generation and tools
| Tool | Description |
|----- | ----------- |
|[NotebookLM](https://notebooklm.google/)|Voiceover and video-avatar speaker, podcast|
|[MMAudio](https://mmaudio.net/)|Revolutionary AI-Powered Video to Audio Generation|

### Voice tools
| Tool | Description |
|----- | ----------- |
|[Eleven Labs](https://elevenlabs.io/)|AI voice generator, Text to speech, voice cloning & changer, dubbing, text to sfx, 32 languages, APIs, Agents|

### Music creation
| Tool | Description |
|----- | ----------- |
|[Suno](https://suno.com/)|Suno is building a future where anyone can make great music. |
|[MusicLM](https://musiclm.com/)|MusicLM can create original music across various genres and styles based on text prompts.|

## Software engineering tools
| Tool | Description |
|----- | ----------- |
|[Google Gemini Code Assist](https://codeassist.google/products/business?hl=en)|AI-assisted development for your business. Get generative AI coding assistance across the SDLC with enterprise security and privacy protection. For individuals now available in public preview.|
|[Github Co-pilot](https://github.com/features/copilot)|The AI editor for everyone|
|[Cline Bot](https://cline.bot/)|The collaborative AI partner for serious engineering|
|[Roo Code](https://docs.roocode.com/)|Roo Code (formerly Roo Cline) is an AI-powered autonomous coding agent that lives in your editor.|
|[Cursor](https://www.cursor.com/)|The AI Code Editor|
|[Codeium Windsurf](https://codeium.com/windsurf)|The first agentic IDE, and then some.|
|[Google Project IDX](https://idx.google.com/)|Work quickly and efficiently with built-in AI assistance from Gemini, Google’s largest and most capable AI model. Generate code, access inline coding suggestions, and get help understanding complex code in real time.|
|[v0 by Vercel](https://v0.dev/)|Chat with v0. Generate UI with simple text prompts. Copy, paste, ship.|
|[Lovable](https://lovable.dev/)|Lovable is your superhuman full stack engineer.|
|[Bolt](https://bolt.new/)|Prompt, run, edit, and deploy full-stack web and mobile apps.|
|[Softgen](https://softgen.ai/)|Softgen is your AI Web App Developer. Describe your vision, give instructions, and build full-stack web apps. No coding required.|
|[Replit](https://replit.com/)|Turn your ideas into apps with AI.|
|[Devin](https://devin.ai/)|Devin is a collaborative AI teammate|
|[Continue](https://www.continue.dev/)|The leading open-source AI code assistant. You can connect any models and any context to create custom autocomplete and chat experiences inside the IDE|
|[Sourcegraph](https://sourcegraph.com/)|Sourcegraph accelerates how software gets built, helping developers search, understand, and write code in complex codebases with AI|

### Models for software engineering
| Tool | Description |
|----- | ----------- |
|[Claude 3.7](https://www.anthropic.com/claude/sonnet)|Hybrid reasoning model, state-of-the-art coding skills, computer use, and 200K context window|
|[Gemini 2.0 Flash](https://deepmind.google/technologies/gemini/flash/)|Probably the best combination of speed, intelligence and cost for coding, can handle larger codebases|
|[o3-mini](https://platform.openai.com/docs/overview)|OpenAI o3-mini is pretty good in coding|
|[Qwen 2.5 32b](https://huggingface.co/Qwen/Qwen2.5-32B)|Perfect for coding|
|[Llama 3.3](https://huggingface.co/meta-llama/Llama-3.3-70B-Instruct)|Very good at coding as well|
|[DeepSeek R1 distill Qwen 32b](https://huggingface.co/deepseek-ai/DeepSeek-R1-Distill-Qwen-32B)|Should be good at coding|

### API Providers
| Tool | Description |
|----- | ----------- |
|[PiAPI](https://piapi.ai/)||
_todo_

## Agents and automation
| Tool | Description |
|----- | ----------- |
|[Datavist](https://datavist.xyz/)|Extract structured data from web pages. No code, prompts or schema required.|
|[Stagehand](https://docs.stagehand.dev/)|Stagehand is the easiest way to build browser automations. It is completely interoperable with Playwright and has seamless integration with Browserbase. [Demo video](https://youtu.be/uF67TGbFfRc?t=273)|
|[OpenAI Operator](https://openai.com/index/introducing-operator/)|An agent that can use its own browser to perform tasks for you|
|[Autogen](https://github.com/microsoft/autogen)|AutoGen is a framework for creating multi-agent AI applications that can act autonomously or work alongside humans.|
|[Camel](https://github.com/camel-ai/camel)|Customize Agents, Build Multi-Agent Systems, Practical Applications|
|[ChatDev](https://github.com/OpenBMB/ChatDev)||

## Research tools
| Tool | Description |
|----- | ----------- |
|[NotebookLM](https://notebooklm.google/)|Your Personalized AI Research Assistant|
|[Google Gemini Pro with Deep Research](https://gemini.google.com/app)|Deep research|

## Presentation and design tools
| Tool | Description |
|----- | ----------- |
|[Gamma](https://gamma.app/)|Beautiful presentations, documents, and websites. No design or coding skills required.|
|[Magic Slides](https://www.magicslides.app/)|AI creates presentation from text, video, pdf or url|

## Various tools
| Tool | Description |
|----- | ----------- |
_todo_

### Business tools
| Tool | Description |
|----- | ----------- |
|[Ifttt](https://ifttt.com/)|Automation for business and home. choose from 900+ services|
|[Zapier](https://zapier.com/)|Automate without limits. Turn chaos into smooth operations by automating workflows yourself—no developers, no IT tickets, no delays. The only limit is your imagination.|
|[Tray AI](https://tray.ai/)|The fastest, most flexible and safest way to turn AI into business performance|
|[Make](https://www.make.com/)|Automation you can see, flex, and scale. Realize your business’s full potential with Make’s intuitive no-code development platform.|
|[Pipedream](https://pipedream.com/)|Connect APIs, AI, databases, and more. Build powerful applications that connect all the services in your stack. Code-level control when you need it.|
|[n8n](https://n8n.io/)|Secure, AI-native workflow automation. The world's most popular workflow automation platform for technical teams|
|[Relvance AI](https://relevanceai.com/)|Build teams of AI agents that deliver human-quality work. Ops teams can build and manage an entire AI workforce in one powerful visual platform.|
|[Workato](https://www.workato.com/)|Integration + Automation + AI = Enterprise Orchestration.|
|[Napkin AI](https://www.napkin.ai/)|Napkin turns your text into visuals so sharing your ideas is quick and effective.|
|[Conversion AI](https://conversion.ai/)|AI marketing teammates, optimized to convert.|
|[Daily AI](https://daily.ai/)|Supercharge Your Email Marketing With Daily.ai|
|[Bubble](https://bubble.io/)|Build a professional product, launch to customers, and grow without limits. Join millions of people who’ve built their dreams with Bubble.|
|[ClickUp](https://clickup.com/integrations)|The everything app, for work. Connect over 1,000+ tools to ClickUp for free.|
|[Browse AI](https://www.browse.ai/)|The easiest way to extract and monitor data from any website. Train a robot in 2 minutes. No coding required.|
|[SeonaAI](https://seonaai.com/)|SeonaAI is a free SEO tool|
|[Monday - work management](https://monday.com/work-management)|Bring your strategy to life. Gain the clarity and control you need to connect your everyday work to business goals across projects and processes.|
|[Monday - Dev](https://www.monday.com/w/dev)|Develop with precision and speed. Plan roadmaps, manage sprints, and release products fast - on one flexible platform.|
|[Stripe](https://stripe.com/en-ee)|Financial infrastructure to grow your revenue. (Payments)|
|[Uptime Robot](https://uptimerobot.com/)|Checks if your product/website is up or down|
|[Finta](https://www.trustfinta.com/)|Finta - raise money for startup|

### Automated caller
| Tool | Description |
|----- | ----------- |
|[Bland AI](https://www.bland.ai/)|Your platform for making ultra-realistic AI Phone Calls|
|[Poly AI](https://poly.ai/)|Resolve over 50% of calls and consistently deliver your best brand experience.|
|[Vapi AI](https://vapi.ai/)|Voice AI for developers. Vapi lets developers build, test and deploy voice agents in minutes rather than months.|
|[Retell AI](https://www.retellai.com/)|Supercharge your Call Operations with Voice AI|
|[Synthflow](https://synthflow.ai/)|Effortless Human-Like AI Phone Calls|
|[Curious Thing](https://curiousthing.io/)|Phone AI agents for you or your businesses|
|[Simple Phones](https://www.simplephones.ai/)|Never miss a call from a customer.|

### Photo editing
| Tool | Description |
|----- | ----------- |
|[Google Magic Editor](https://www.google.com/photos/editing/)|Reimagine all your favorite moments with the help of generative AI.|
|[Clipdrop](https://clipdrop.co/)|Create stunning visuals in seconds|
|[Runway](https://runwayml.com/)|Image to Image. Text to Image. Transform an existing image to a modified image. Easily create an image from scratch.|

### Writing
| Tool | Description |
|----- | ----------- |
|[GPTyper](https://gptype.app/)|Using ChatGPT to suggest while typing|
|[Rytr](https://rytr.me/)|Generate text, check grammar and much more|
|[Jenni](https://jenni.ai/)|The AI-powered workspace to help you read, write, and organize research with ease.|

### 3D Models and texture generation
| Tool | Description |
|----- | ----------- |
|[Meshy AI](http://meshy.ai)|AI 3D Model Generator for creators.|
|[Odyssey Explorer](https://odyssey.world/introducing-explorer)|World models for film, gaming, and beyond.|
|[Hunyuan 3D 2.0](https://github.com/Tencent/Hunyuan3D-2)|An advanced large-scale 3D synthesis system for generating high-resolution textured 3D assets|
|[Stable-Dreamfusion](https://github.com/ashawkey/stable-dreamfusion)|A pytorch implementation of the text-to-3D model Dreamfusion, powered by the Stable Diffusion text-to-2D model.|

## How to run models locally
| Tool | Description |
|----- | ----------- |
|[Ollama](https://ollama.ai/)|Run Llama 3.3, DeepSeek-R1, Phi-4, Mistral, Gemma 2, and other models, locally.|
|[Zylon AI](https://www.zylon.ai/)|The truly Private AI platform for the Enterprise. The only self-contained and ready-to-go AI platform that runs in your own servers, allowing you to maintain data sovereignty.|
|[FastChat](https://github.com/lm-sys/FastChat)|FastChat is an open platform for training, serving, and evaluating large language model based chatbots.|
|[PrivateGPT](https://github.com/zylon-ai/private-gpt)|PrivateGPT is a production-ready AI project that allows you to ask questions about your documents using the power of Large Language Models(LLMs), even in scenarios without an Internet connection. 100% private, no data leaves your execution environment at any point.|

### List of models that can be run locally
| Tool | Description |
|----- | ----------- |
|[R1 1776](https://huggingface.co/perplexity-ai/r1-1776)|R1 1776 is a DeepSeek-R1 reasoning model that has been post-trained by Perplexity AI to remove Chinese Communist Party censorship. The model provides unbiased, accurate, and factual information while maintaining high reasoning capabilities.|
|[DeepSeek R1](https://github.com/deepseek-ai/DeepSeek-R1)|DeepSeek-R1 is open source, rivaling OpenAI's Model o1.|
|[Llama 3.3](https://www.llama.com/docs/model-cards-and-prompt-formats/llama3_3/)|The open-source AI models you can fine-tune, distill and deploy anywhere.|
|[Gemma](https://ai.google.dev/gemma)|A family of lightweight, state-of-the art open models built from the same research and technology used to create the Gemini models|
|[Qwen2](https://qwen2.org/)|Qwen2 is an advanced suite of foundational and instruction-tuned language models, with parameters ranging from 0.5 to 72 billion. It includes both dense models and a Mixture-of-Experts model.|
|[Trending models](https://huggingface.co/models)|Trending models on Huggingface. Check them out, world changes fast.|

## Other AI tools list providers
| Tool | Description |
|----- | ----------- |
|[Textblaze Chrome plugin](https://blaze.today/)|Speed up typing in Gmail, Office365 etc|
|[Rows AI](https://rows.com/ai)|Your personal Data Analyst. Unlock the power of AI to analyze, summarize, and transform data – without scripts or code.|

## Some literature and articles
_todo_

## Helping services (not AI)
_todo_
