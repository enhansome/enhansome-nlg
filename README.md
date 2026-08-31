# Awesome Natural Language Generation with stars

![Piscis Magnus from BL Harley 647](logo.png)

Natural Language Generation is a broad domain with applications in chat-bots, story generation, and data descriptions. There is a wide spectrum of different technologies addressing parts or the whole of the NLG process. This list aims to represent this deversity of NLG applications and techniques by providing links to various projects, tools, research papers, and learning materials.

## Contents

* [Datasets](#datasets)
* [Dialog](#dialog)
* [Evaluation](#evaluation)
* [Grammar](#grammar)
* [Libraries](#libraries)
* [Narrative Generation](#narrative-generation)
* [Neural Natural Language Generation](#neural-natural-language-generation)
* [Papers and Articles](#papers-and-articles)
* [Products](#products)
* [Realizers](#realizers)
* [Templating Languages](#templating-languages)
* [Videos](#videos)

## Datasets

* [The Schema-Guided Dialogue Dataset](https://github.com/google-research-datasets/dstc8-schema-guided-dialogue) ⚠️ Archived - The Schema-Guided Dialogue (SGD) dataset consists of over 20k annotated multi-domain, task-oriented conversations between a human and a virtual assistant.
* [Box-score data](https://github.com/harvardnlp/boxscore-data/) ⭐ 114 | 🐛 4 | 🌐 HTML | 📅 2022-03-21 - This dataset consists of (human-written) NBA basketball game summaries aligned with their corresponding box- and line-scores.
* [WebNLG](https://github.com/ThiagoCF05/webnlg) ⭐ 71 | 🐛 5 | 🌐 Python | 📅 2021-03-25 - The enriched version of the WebNLG - a resource for evaluating common NLG tasks, including Discourse Ordering, Lexicalization and Referring Expression Generation.
* [Alex Context NLG Dataset](https://github.com/UFAL-DSG/alex_context_nlg_dataset) ⭐ 22 | 🐛 0 | 📅 2016-09-18 - A dataset for NLG in dialogue systems in the public transport information domain.
* [Neural-Wikipedian](https://github.com/pvougiou/Neural-Wikipedian) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2018-08-26 - The repository contains the code along with the required corpora that were used in order to build a system that "learns" how to generate English biographies for Semantic Web triples.
* [E2E](http://www.macs.hw.ac.uk/InteractionLab/E2E) - This shared task focuses on recent end-to-end (E2E), data-driven NLG methods, which jointly learn sentence planning and surface realisation from non-aligned data.
* [WeatherGov](https://cs.stanford.edu/~pliang/data/weather-data.zip) - Computer-generated weather forecasts from weather.gov (US public forecast), along with corresponding weather data.
* [WikiBio - wikipedia biography dataset](https://rlebret.github.io/wikipedia-biography-dataset/) - This dataset gathers 728,321 biographies from wikipedia. It aims at evaluating text generation algorithms.
* [The Wikipedia company corpus](https://gricad-gitlab.univ-grenoble-alpes.fr/getalp/wikipediacompanycorpus) - Company descriptions collected from Wikipedia. The dataset contains semantic representations, short, and long descriptions for 51K companies in English.
* [YelpNLG](https://nlds.soe.ucsc.edu/yelpnlg) - YelpNLG provides resources for natural language generation of restaurant reviews.

## Dialog

* [Plato](https://github.com/uber-research/plato-research-dialogue-system) ⚠️ Archived - This is the Plato Research Dialogue System, a flexible platform for developing conversational AI agents.
* [Chatito](https://github.com/rodrigopivi/Chatito) ⭐ 889 | 🐛 24 | 🌐 TypeScript | 📅 2023-09-03 - Generate datasets for AI chatbots, NLP tasks, named entity recognition or text classification models using a simple DSL!
* [RNNLG](https://github.com/shawnwun/RNNLG) ⭐ 490 | 🐛 3 | 🌐 Python | 📅 2019-07-02 - RNNLG is an open source benchmark toolkit for Natural Language Generation (NLG) in spoken dialogue system application domains.
* [NNDIAL](https://github.com/shawnwun/NNDIAL) ⭐ 353 | 🐛 7 | 🌐 Python | 📅 2017-06-14 - NNDial is an open source toolkit for building end-to-end trainable task-oriented dialogue models.
* [TGen](https://github.com/UFAL-DSG/tgen) ⭐ 207 | 🐛 5 | 🌐 Python | 📅 2021-12-05 - Statistical NLG for spoken dialogue systems.

## Evaluation

* [NLG-eval](https://github.com/Maluuba/nlg-eval) ⭐ 1,391 | 🐛 32 | 🌐 Python | 📅 2024-08-20 - Evaluation code for various unsupervised automated metrics for Natural Language Generation.
* [BLEURT: a Transfer Learning-Based Metric for Natural Language Generation](https://github.com/google-research/bleurt) ⭐ 793 | 🐛 22 | 🌐 Python | 📅 2023-08-04
* [compare-mt](https://github.com/neulab/compare-mt) ⭐ 471 | 🐛 5 | 🌐 Python | 📅 2025-09-22 - A tool for holistic analysis of language generations systems.
* [VizSeq](https://github.com/facebookresearch/vizseq) ⭐ 457 | 🐛 7 | 🌐 Python | 📅 2026-08-18 - A Visual Analysis Toolkit for Text Generation Tasks.
* [GEM](https://gem-benchmark.com/) - a benchmark environment for NLG with a focus on its Evaluation, both through human annotations and automated Metrics.

## Grammar

* [OpenCCG](https://github.com/OpenCCG/openccg) ⭐ 220 | 🐛 13 | 🌐 Java | 📅 2021-02-03 - OpenCCG library for parsing and realization with CCG.
* [EasyCCG](https://github.com/mikelewis0/easyccg) ⭐ 62 | 🐛 7 | 🌐 Java | 📅 2017-12-02 - CCG: All combinators, common grammar format, parsing to logical form, parameter estimation for probabilistic CCG.
* [CCG Lab](https://github.com/bozsahin/ccglab) ⭐ 27 | 🐛 0 | 🌐 Common Lisp | 📅 2025-12-12 - All combinators, common grammar format, parsing to logical form, parameter estimation for probabilistic CCG.
* [CCGweb](https://github.com/texttheater/ccgweb) ⭐ 5 | 🐛 4 | 🌐 Hack | 📅 2022-12-07 - A Web platform for parsing and annotation.
* [GrammaticalFramework](http://www.grammaticalframework.org/) - A programming language for multilingual grammar applications.

## Libraries

* [Cron Expression Descriptor](https://github.com/bradymholt/cron-expression-descriptor) ⭐ 1,113 | 🐛 0 | 🌐 C# | 📅 2026-07-07 - A .NET library that converts cron expressions into human readable descriptions.
* [Number Words](https://github.com/tokenmill/numberwords) ⭐ 199 | 🐛 1 | 🌐 Clojure | 📅 2021-01-20 - Convert a number to an approximated text expression: from '0.23' to 'less than a quarter'.
* [Writebot](https://docs.writebot.app) - A NodeJS library that makes it easier to use GPT-3 by using presets.

## Narrative Generation

* [Tracery](https://github.com/galaxykate/tracery) ⭐ 2,209 | 🐛 32 | 🌐 JavaScript | 📅 2024-11-03 - A story-grammar generation library for JavaScript.
* [Random Story Generator](https://github.com/aherriot/story-generator) ⭐ 63 | 🐛 1 | 🌐 JavaScript | 📅 2012-06-05 - Using Natural Language Generation (NLG) to create a random short story.

## Neural Natural Language Generation

* [Transformers](https://github.com/huggingface/transformers) ⭐ 164,670 | 🐛 2,407 | 🌐 Python | 📅 2026-08-31 - State-of-the-art Natural Language Processing for TensorFlow 2.0 and PyTorch.
* [textgenrnn](https://github.com/minimaxir/textgenrnn) ⭐ 4,922 | 🐛 145 | 🌐 Python | 📅 2022-07-17 - Easily train your own text-generating neural network of any size and complexity on any text dataset with a few lines of code.
* [Texar](https://github.com/asyml/texar) ⭐ 2,389 | 🐛 40 | 🌐 Python | 📅 2026-07-21 - Texar is a toolkit aiming to support a broad set of machine learning, especially natural language processing and text generation tasks.
* [aitextgen](https://github.com/minimaxir/aitextgen) ⭐ 1,837 | 🐛 133 | 🌐 Python | 📅 2023-07-14 - A robust Python tool for text-based AI training and generation using GPT-2.
* [PPLM](https://github.com/uber-research/PPLM) ⭐ 1,152 | 🐛 30 | 🌐 Python | 📅 2024-02-20 - Plug and Play Language Model implementation. Allows to steer topic and attributes of GPT-2 models.
* [Question Generation using hugstransformers](https://github.com/patil-suraj/question_generation) ⭐ 1,141 | 🐛 80 | 🌐 Jupyter Notebook | 📅 2024-04-05 - Question generation is the task of automatically generating questions from a text paragraph.
* [This Word Does Not Exist](https://github.com/turtlesoupy/this-word-does-not-exist) ⭐ 1,023 | 🐛 24 | 🌐 Python | 📅 2026-06-17 - This is a project allows people to train a variant of GPT-2 that makes up words, definitions and examples from scratch.
* [PaperRobot: Incremental Draft Generation of Scientific Ideas](https://github.com/EagleW/PaperRobot) ⭐ 480 | 🐛 0 | 🌐 Python | 📅 2024-03-09 - We present a PaperRobot who performs as an automatic research assistant.
* [Summary Generation From Structured Data](https://github.com/akanimax/natural-language-summary-generation-from-structured-data) ⭐ 186 | 🐛 4 | 🌐 Python | 📅 2019-03-12 - For converting information present in the form of structured data into natural language text.
* [graph-2-text](https://github.com/diegma/graph-2-text) ⭐ 153 | 🐛 10 | 🌐 Python | 📅 2019-07-12 - Graph to sequence implemented in Pytorch combining Graph convolutional networks and opennmt-py.
* [Image Caption Generator](https://github.com/neural-nuts/image-caption-generator) ⚠️ Archived - A Neural Network based generative model for captioning images using Tensorflow.
* [lightnlg](https://github.com/kasnerz/lightnlg) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2023-01-23 - A minimalistic codebase for finetuning and interacting with NLG models using PyTorch Lightning.

## Papers and Articles

* [2022: Repairing the Cracked Foundation: A Survey of Obstacles in Evaluation Practices for Generated Text](https://arxiv.org/abs/2202.06935)
* [2021: Vision: NLG Can Help Humanise Data and AI](https://ehudreiter.com/2021/03/17/vision-nlg-can-help-humanise-data-and-ai/)
* [2020: The Curious Case of Neural Text Degeneration](https://openreview.net/forum?id=rygGQyrFvH)
* [2020: A Gold Standard Methodology for Evaluating Accuracy in Data-To-Text Systems](https://arxiv.org/abs/2011.03992)
* [2020: Evaluating the state-of-the-art of End-to-End Natural Language Generation: The E2E NLG challenge](https://www.sciencedirect.com/science/article/pii/S0885230819300919)
* [2020: How to generate text: using different decoding methods for language generation with Transformers](https://huggingface.co/blog/how-to-generate)
* [2020: Natural language generation: The commercial state ofthe art in 2020](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/BA2417D73AF29F8073FF5B611CDEB97F/S135132492000025Xa.pdf/natural_language_generation_the_commercial_state_of_the_art_in_2020.pdf)
* [2020: Turing-NLG: A 17-billion-parameter language model by Microsoft](https://www.microsoft.com/en-us/research/blog/turing-nlg-a-17-billion-parameter-language-model-by-microsoft/)
* [2019: A Closer Look at Recent Results of Verb Selection for Data-to-Text NLG](https://www.inlg2019.com/assets/papers/178_Paper.pdf)
* [2019: A Personalized Data-to-Text Support Tool for Cancer Patients](https://www.inlg2019.com/assets/papers/28_Paper.pdf)
* [2019: Controlling Contents in Data-to-Document Generation with Human-Designed Topic Labels](https://www.inlg2019.com/assets/papers/79_Paper.pdf)
* [2019: Generated Texts Must Be Accurate!](https://ehudreiter.com/2019/09/26/generated-texts-must-be-accurate/)
* [2019: Hotel Scribe: Generating High Variation Hotel Descriptions](https://www.inlg2019.com/assets/papers/44_Paper.pdf)
* [2019: Revisiting Challenges in Data-to-Text Generation with Fact Grounding](https://www.inlg2019.com/assets/papers/32_Paper.pdf)
* [2017: Survey of the State of the Art in NaturalLanguage Generation: Core tasks, applicationsand evaluation](https://arxiv.org/pdf/1703.09902.pdf)
* [2016: Natural Language Generation enhances human decision-making with uncertain information](https://arxiv.org/pdf/1606.03254.pdf)

## Products

* [Accelerated Text](https://github.com/tokenmill/accelerated-text) ⭐ 807 | 🐛 9 | 🌐 JavaScript | 📅 2023-03-10 - Automatically generate multiple natural language descriptions of your data varying in wording and structure.
* [RosaeNLG](https://rosaenlg.org) - An open-source library for node.js or client side (browser) execution, based on the Pug template engine, to generate texts in English, French, German and Italian.
* [Twine](http://twinery.org/) - An open-source tool for telling interactive, nonlinear stories.

## Realizers

* [SimpleNLG](https://github.com/simplenlg/simplenlg) ⭐ 831 | 🐛 17 | 🌐 Java | 📅 2024-12-06 - Java API for Natural Language Generation.
* [JSrealB](https://github.com/rali-udem/JSrealB) ⭐ 27 | 🐛 0 | 🌐 HTML | 📅 2026-08-31 - A JavaScript bilingual text realizer for web development.
* [SimpleNLG-EnFr](https://github.com/rali-udem/SimpleNLG-EnFr) ⭐ 25 | 🐛 3 | 🌐 Java | 📅 2018-04-23 - SimpleNLG-EnFr 1.1 is a bilingual English/French adaption of SimpleNLG v4.2.
* [Genl](https://github.com/kowey/GenI) ⭐ 21 | 🐛 33 | 🌐 Haskell | 📅 2015-05-04 - Surface realiser (part of a Natural Language Generation system) using Tree Adjoining Grammar.
* [SimpleNLG DE](https://github.com/sebischair/SimpleNLG-DE) ⭐ 19 | 🐛 2 | 🌐 Java | 📅 2023-03-25 - German version of SimpleNLG 4.

## Templating Languages

* [calyx](https://github.com/maetl/calyx) ⭐ 64 | 🐛 10 | 🌐 Ruby | 📅 2022-11-01 - A Ruby library for generating text with recursive template grammars.
* [nalgene](https://github.com/spro/nalgene) ⭐ 55 | 🐛 3 | 🌐 Python | 📅 2019-04-30 - Natural language generation language.
* [StringTemplate](https://www.stringtemplate.org/) - Java template engine (with ports for C##, Objective-C, JavaScript, Scala) for generating source code, web pages, emails, or any other formatted text output.

## Videos

* [Data-To-Text: Generating Textual Summaries of Complex Data - Ehud Reiter](https://www.youtube.com/watch?v=kFRw-wk5YOA)
* [Imitation Learning and its Application to Natural Language Generation](https://slideslive.com/38922816/imitation-learning-and-its-application-to-natural-language-generation)
* [Natural Language Generation (Introduction)](https://www.youtube.com/watch?v=4fjM72lbJaw)
* [Strata Data Conference | The future of natural language generation: 2017-2027](https://www.youtube.com/watch?v=Ls7elVbN8bI)
* [The Quest for Automated Story Generation - Mark Riedl](https://www.youtube.com/watch?v=wgcDUX_BPpk)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [TokenMill](https://www.tokenmill.ai) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-31._
