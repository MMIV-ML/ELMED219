# Lab 3: Generative AI and Large Language Models

This lab is part of our journey through computational modeling techniques and AI in biomedical and clinical applications. It is designed to give you a comprehensive understanding of how generative AI is transforming society in general and healthcare in particular and the role it will play in the future of medicine.<br>  _update: 2024-01-02_


<!-- ![img](../assets/GPT-MedAI.png)<br> -->
<img src="../assets/GPT-MedAI.png" width="600"><br>
If you have a subscription to [ChatGPT Plus](https://openai.com/blog/chatgpt-plus), you can also try out the the [**Medical AI Assistant (UiBmed - ELMED219 & BMED365)**](https://chat.openai.com/g/g-d90dfN17H-medical-ai-assistant-uibmed-elmed219-bmed365) <br> [GPT](https://openai.com/blog/introducing-gpts) and see if you can get it to answer some of your questions. See also [_Q&A-in-the-wild_](./Q&A-in-the-wild.md)

## Learning motivations - watch these
(in the order of duration ...)

- _Foundation Models: An Explainer for Non-Experts_ by [**Stanford HAI**](https://crfm.stanford.edu) [[link](https://youtu.be/kK3NmQT241w)] (2:08 min)
   - see also Stanford Center for Research on Foundation Models [code](https://github.com/stanford-crfm)
   - and get informed and be inspired by [Azeem Azhar](https://www.linkedin.com/in/azhar/?originalSubdomain=uk)’s 2020 conversation with the pioneering AI scientist [Fei-Fei Li](https://en.wikipedia.org/wiki/Fei-Fei_Li), professor of computer science at Stanford University and the founding co-director of Stanford’s Human-Centered AI Institute [[link](https://hbr.org/podcast/2023/11/azeems-picks-the-promise-of-ai-with-fei-fei-li)] (37:46 min)

- _Introducing GPT-4_ by [**OpenAI**](https://openai.com) [[link](https://www.youtube.com/watch?v=--khbXchTeE)] (3:12 min)

- _What ChatGPT is and what it's not: A three minutes guide_ by [Richard Van Noorden](https://www.linkedin.com/in/richard-van-noorden), Features Editor, _Nature_  [[link](https://youtu.be/f70ME-IfeMU)] (3:51 min)
  
- _The Exciting, Perilous Journey Toward AGI_, **TED talk** by [Ilya Sutskever](https://en.wikipedia.org/wiki/Ilya_Sutskever) (OpenAI) [[link](https://www.youtube.com/watch?v=SEkGLj0bwAU)] (12:25 min)

- _Can AI Catch What Doctors Miss?_,  **TED talk** by [Eric Topol](https://www.scripps.edu/faculty/topol) [[link](https://www.youtube.com/watch?v=ll5LY7wI_Xc)] (14:06 min)

- _Introduction to large language models_ by [John Ewald](https://www.linkedin.com/in/ewaldjohn) Google Cloud Tech [[link](https://www.youtube.com/watch?v=zizonToFXDs)] (15:45 min)

- _Large Language Models for Health 101_ by [Nigam Shah](https://profiles.stanford.edu/nigam-shah),  **Stanford HAI**  [[link](https://www.youtube.com/watch?v=b88FZYNJdIk)] (16:44 min)
  - see also his "A framework for shaping the future of AI in health care" [[link](https://shahlab.stanford.edu)]

- _GTP-4 - Complete Beginners Guide_ by   [[link](https://www.youtube.com/watch?v=T4GA0z6ccmo)]  (19:12 min)
  
- _Introduction to Generative AI_ by [Gwendolyn Stripling](https://www.linkedin.com/in/gwendolyn-stripling)  Google Cloud Tech [[link](https://www.youtube.com/watch?v=G2fqAlgmoPo)]   (22:07 min)
  - see also her [_Low-code AI_](https://www.amazon.com/dp/1098146824/ref=tsm_1_fb_lk) book with [code](https://github.com/maabel0712/low-code-ai)

- _New APPLE AI_ by [TheAIGRID](https://theaigrid.com)  (Apples New Multimodal AI BEATS GPT-4 Vision) **NOT an Apple production** [[link](https://youtu.be/utTtrwW9GpM)] (22:24 min)
  - see also Ferret: "An End-to-End MLLM that Accept Any-Form Referring and Ground Anything in Response" [[paper](https://arxiv.org/abs/2310.07704)] [[code](https://github.com/apple/ml-ferret)] [license](https://github.com/apple/ml-ferret/blob/main/LICENSE)

- _Geoffrey Hinton: Large Language Models in Medicine. They Understand and Have Empathy_ by [Eric Topol](https://en.wikipedia.org/wiki/Eric_Topol), [Ground Truth](https://erictopol.substack.com/about) (highly recommended podcast, with transcript)  [[link](https://erictopol.substack.com/p/geoffrey-hinton-large-language-models)] (36:33 min)

- _Embeddings: What they are and why they matter_ by [Simon Willison](https://simonwillison.net/about) [[link](https://youtu.be/ArnMdc-ICCM?si=NodSkzQ8tpLUMPnS)] (38:37 min)
  - see also his informative [[Webblog](https://simonwillison.net/2023/Oct/23/embeddings)] on the same topic, and his [... AI in 2023](https://simonwillison.net/2023/Dec/31/ai-in-2023) + this [Crash Course in Embeddings](https://youtu.be/ySus5ZS0b94?si=TeU2VNUjlSgfVT3L) (18:40 min)

- _Intro to Large Language Models_ by [Andrej Karpathy](https://en.wikipedia.org/wiki/Andrej_Karpathy) [[link](https://www.youtube.com/watch?v=zjkBMFhNj_g)] (59:47 min)

  - Slides as PDF [[link](https://drive.google.com/file/d/1pxx_ZI7O-Nwl7ZLNk5hI3WzAsTLwvNU7/view)] (42MB)
  - Slides as Keynote [[link](https://drive.google.com/file/d/1FPUpFMiCkMRKPFjhi9MAhby68MHVqe8u/view)] (140MB)
  - The repo: https://github.com/karpathy
 
- _Large Language Models and The End of Programming_, CS50 Tech Talk with [Matt Welsh](https://en.wikipedia.org/wiki/Matt_Welsh_\(computer_scientist\)) [[link](https://www.youtube.com/watch?v=JhCl-GeT4jw)]  (66:55 min)
  - [CS50](https://www.edx.org/cs50) is Harvard University's introduction to the intellectual enterprises of computer science and the art of programming

- _Large Language Models (LLMs) Concenpts_, [DataCamp](https://app.datacamp.com) interactive course, Beginner (+ [Understanding Machine Learning](https://app.datacamp.com/learn/courses/understanding-machine-learning)), **15 videos**, **50 exercises**, [[link](https://app.datacamp.com/learn/courses/large-language-models-llms-concepts)] (~120 min)

  
### Readings:
(in the order of most recent ...)

- Oniani D et al. _Adopting and expanding ethical principles for generative artificial intelligence from military to healthcare_ (perspective article published 2 Dec 2023). npj Digital Medicine 2023;6:225. Addresses the ethical dilemmas and challenges posed by the integration of generative AI into healthcare practice, compared with genAI in military use. CC-BY-4.0 [[link](https://www.nature.com/articles/s41746-023-00965-x)] [[pdf](https://www.nature.com/articles/s41746-023-00965-x.pdf)]
  
- Toma A et al. _Generative AI could revolutionize health care — but not if control is ceded to big tech_ (comment published 30 Nov 2023). Nature 2023;624:36-38. [[link](https://www.nature.com/articles/d41586-023-03803-y)]

- Thirunavukarasu AJ et al. _Large language models in medicine_   (review article published 17 Jul 2023) Nature Medicine 2023;29:1930–1940. [[link](https://www.nature.com/articles/s41591-023-02448-8)]

- Moore M et al. _Foundation models for generalist medical artificial intelligence_ (perspective article published 12 Apr 2023) Nature 2023;616:259–265. A seminal paper on foundation models in medicine (GMAI). [[link](https://www.nature.com/articles/s41586-023-05881-4)]
  

## OpenAI: Prompt engineering guide

This **guide (https://platform.openai.com/docs/guides/prompt-engineering)** is highly recommended and shares strategies and tactics for getting better results from large language models like GPT-4. The methods (Six strategies, each with a set of tactics) described in this guide can sometimes be combined for greater effect. Experimentation is encouraged to find the methods that work best for your intentions.

### The Six strategies for getting better results:

- **Write clear instructions** [[link](https://platform.openai.com/docs/guides/prompt-engineering/strategy-write-clear-instructions)]
- **Provide reference text** [[link](https://platform.openai.com/docs/guides/prompt-engineering/strategy-provide-reference-text)]
- **Split complex tasks into simpler subtasks** [[link](https://platform.openai.com/docs/guides/prompt-engineering/strategy-split-complex-tasks-into-simpler-subtasks)]
- **Give the model time to "think"** [[link](https://platform.openai.com/docs/guides/prompt-engineering/strategy-give-models-time-to-think)]
- **Use external tools** [[link](https://platform.openai.com/docs/guides/prompt-engineering/strategy-use-external-tools)]
- **Test changes systematically** [[link](https://platform.openai.com/docs/guides/prompt-engineering/strategy-test-changes-systematically)]


### Other OpenAI resources

- Experiment with [ChatGPT](https://chat.openai.com)
- Stay updated with the [OpenAI Blog](https://openai.com/blog)
- Try the API in the [OpenAI Playground](https://beta.openai.com/playground) (a platform to interact with AI models)
- Read about the API in the [OpenAI Documentation](https://beta.openai.com/docs/introduction)
- Get help in the [OpenAI Help Center](https://help.openai.com/en)
- Discuss the API in the [OpenAI Community Forum](https://community.openai.com/top?period=monthly) or [OpenAI Discord channel](https://discord.com/invite/openai)
- See example prompts in the [OpenAI Examples](https://beta.openai.com/examples)

---------------

## Slides

<!--
<a href="https://docs.google.com/presentation/d/e/2PACX-1vREHZA9OSvQa2fOGGDikHF_gDZz0tzgaARVmsjXq7xjFlwDDlkmMSDEvZ5Sa9GflbTybFJLQ3IqltjR/pub?start=false&loop=false&delayms=3000"><img src="assets/lab0-slides.png"></a>
-->

<img src="assets/lab3-slides.png">


<!-- Here's a short extra video that goes through a very similar notebook to the one we use in this lab: https://www.youtube.com/watch?v=OhxUgFNnj1U. You may want to watch this as well. -->

-----
### Other sources of inspiration:

- [PCBBE 2023](https://pcbbe.p.lodz.pl) "Will AI be going to replace a medical doctor?" [[link](https://github.com/arvidl/PCBBE-2023-explore/blob/main/PCBBE_2023-PLEN-04-Debate-AL.md)]
