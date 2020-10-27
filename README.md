# Collections-of-Visual-Storytelling-StoryNLP
This repository aims to collect the articles and codes for the Visual Storytelling (VIST) task. VIST is a vision-and-language task. It aims to summarize the idea of a photo stream and tells a story about it (in natural language). Be careful about its difference from the "storytelling with data", which is more related to data visualization.

### [Visual Storytelling Task Website ←](http://www.visionandlanguage.net/workshop2019/)
More introduction and examples are shown in the site.

### [Dataset Website ←](http://visionandlanguage.net/VIST/)
Google Drive archived (313GB in total). If you have no access to google drive, maybe you should contact authors engaging in this task in your area for help. 

#### Useful Tool: 
To evaluate the generated story, metrics like BLEU, CIDEr, METEOR, ROUGE are most common used.

Evaluation Metrics Implementation: [vist eval](https://github.com/lichengunc/vist_eval).It works with [vist api](https://github.com/lichengunc/vist_api)

The task also needs human evaluation, usually in prespective of "Relevance", "Expressiveness" and "Concreteness", taking AREL(No Metrics Are Perfect, ACL 18) as a referebce.


- Please feel free to pull requests or open an issue to add papers.

----

### 2020
Title|Venue|Type|Code|Star
:--:|:--:|:--:|:--:|:--:
[Knowledge-Enriched Visual Storytelling](https://doi.org/10.1609/aaai.v34i05.6303)|AAAI20|KG|[Pytorch1.3](https://github.com/zychen423/KE-VIST)|17+| 
[What Makes A Good Story? Designing Composite Rewards for Visual Storytelling](https://doi.org/10.1609/aaai.v34i05.6305)|AAAI20|RL| | 
[Hide-and-Tell: Learning to Bridge Photo Streams for Visual Storytelling](https://aaai.org/ojs/index.php/AAAI/article/view/6780)|AAAI20|En\Decoder| | 
[Storytelling from an Image Stream Using Scene Graphs](https://aaai.org/ojs/index.php/AAAI/article/view/6455)|AAAI20|SceneGraph| | 
[Topic Adaptation and Prototype Encoding for Few-Shot Visual Storytelling](https://dl.acm.org/doi/10.1145/3394171.3413886)|ACMMM20|Few-Shot| | 

### 2019
Title|Venue|Type|Code|Star
:--:|:--:|:--:|:--:|:--:
[Visual Story Post-Editing](https://www.aclweb.org/anthology/P19-1658/)|ACL19|Post-Editing|[Dataset](https://github.com/tingyaohsu/VIST-Edit)|10+ 
[Hierarchically Structured Reinforcement Learning for Topically Coherent Visual Story Generation](https://aaai.org/ojs/index.php/AAAI/article/view/4863)|AAAI19|RL| | 
[Hierarchical Photo-Scene Encoder for Album Storytelling](https://aaai.org/ojs/index.php/AAAI/article/view/4918)|AAAI19|En\Decoder| | 
[Informative Visual Storytelling with Cross-modal Rules](https://dl.acm.org/doi/10.1145/3343031.3350918)|ACMMM19|ATT|[Pytorch 0.3](https://github.com/passerby233/VSCMR-Visual-Storytelling-with-Corss-Modal-Rules)|3
[Knowledgeable Storyteller: A Commonsense-Driven Generative Model for Visual Storytelling](https://www.ijcai.org/Proceedings/2019/744)|IJCAI19|KG|[No Source](https://github.com/lancopku/CVST)|7+ 
[Emotion Reinforced Visual Storytelling](https://dl.acm.org/doi/10.1145/3323873.3325050)|ICMR19|RL|Other| |
[Dixit: Interactive Visual Storytelling via Term Manipulation](https://dl.acm.org/doi/10.1145/3308558.3314131)|WWW19|Other| | 
[A Hierarchical Approach for Visual Storytelling Using Image Description](https://link.springer.com/chapter/10.1007%2F978-3-030-33894-7_30)|ICIDS19|En\Decoder| | 
[The Steep Road to Happily Ever After: An Analysis of Current Visual Storytelling Models](https://arxiv.org/abs/1904.03366)|NAACL19 StoryNLP workshop|Analysis| | 
[Character-Centric Storytelling](https://arxiv.org/abs/1909.07863)|NAACL19 StoryNLP workshop|Other| |
["My Way of Telling a Story": Persona based Grounded Story Generation](https://arxiv.org/abs/1906.06401)|NAACL19 StoryNLP workshop|Other| | 
[Keep it Consistent: Topic-Aware Storytelling from an Image Stream via Iterative Multi-agent Communication](https://arxiv.org/abs/1911.04192)|ASLP19|Topic| | 
[Visual Storytelling via Predicting Anchor Word Embeddings in the Stories](https://arxiv.org/abs/2001.04541)|ICCV19 workshop|Other| | 
[Incorporating Textual Evidence in Visual Storytelling](https://arxiv.org/abs/1911.09334)|DSNNLG19|ATT| | 

### 2018
Title|Venue|Type|Code|Star
:--:|:--:|:--:|:--:|:--:
[No Metrics Are Perfect: Adversarial Reward Learning for Visual Storytelling](https://www.aclweb.org/anthology/P18-1083/)|ACL18|RL|[Pytorch 0.3](https://github.com/eric-xw/AREL) | 117+
[Show, Reward and Tell: Automatic Generation of Narrative Paragraph From Photo Stream by Adversarial Training](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17049)|AAAI18|RL| | 
[Using Inter-Sentence Diverse Beam Search to Reduce Redundancy in Visual Storytelling](https://arxiv.org/abs/1805.11867)|NAACL18 StoryNLP workshop|BS| | 
[Adversarial Learning for Visual Storytelling with Sense Group Partition](https://link.springer.com/chapter/10.1007%2F978-3-030-20870-7_11)|ACCV18|RL| |
[GLAC Net: GLocal Attention Cascading Networks for Multi-image Cued Story Generation](https://arxiv.org/abs/1805.10973)|NAACL18 StoryNLP workshop|En\Decoder|[Pytorch1.0](https://github.com/tkim-snu/GLACNet)|34+
[Contextualize, Show and Tell: A Neural Visual Storyteller](https://arxiv.org/abs/1806.00738)|NAACL18 StoryNLP workshop|En\Decoder|[Tensorflow1.0](https://github.com/dianaglzrico/neural-visual-storyteller)|21+
[A Pipeline for Creative Visual Storytelling](https://arxiv.org/abs/1807.08077)|NAACL18 StoryNLP workshop|Other| | 
[Stories for Images-in-Sequence by using Visualand Narrative Components](https://arxiv.org/abs/1805.05622)| ICTI18|En\Decoder|[Tensorflow1.6](https://github.com/Pendulibrium/ai-visual-storytelling-seq2seq)|34+

### 2016-2017
Title|Venue|Type|Code|Star
:--:|:--:|:--:|:--:|:--:
[Let Your Photos Talk Generating Narrative Paragraph for Photo Stream](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14869)|AAAI17|ATT| | 
[Learning Deep Contextual Attention Network for Narrative Photo Stream Captioning](https://dl.acm.org/doi/10.1145/3126686.3126715)|ACM MM17 workshop|FasterRCNN+ATT|
[Hierarchically-Attentive RNN for Album Summarization and Storytelling](https://www.aclweb.org/anthology/D17-1101/)|EMNLP17|En\Decoder|[Python](https://github.com/lichengunc/vist_api)|26+
[Sort Story: Sorting Jumbled Images and Captions into Stories](https://www.aclweb.org/anthology/D16-1091/)|EMNLP16|Other| | 
