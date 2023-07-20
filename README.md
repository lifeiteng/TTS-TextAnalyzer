# TTS-TextAnalyzer

受 [Introducing Unified Neural Text Analyzer: an innovation for Neural Text-to-Speech pronunciation accuracy improvement](https://techcommunity.microsoft.com/t5/azure-ai-services-blog/unified-neural-text-analyzer-an-innovation-to-improve-neural-tts/ba-p/2102187) 启发，可在 BERT 模型基础上构建多个任务的 heads 来统一语音合成文本分析的任务，包括：分词，词性预测、文本归一化、多音词消歧等。这个项目用来收集适用于各任务的数据集信息。

Inspired by [Introducing Unified Neural Text Analyzer: an innovation for Neural Text-to-Speech pronunciation accuracy improvement](https://techcommunity.microsoft.com/t5/azure-ai-services-blog/unified-neural-text-analyzer-an-innovation-to-improve-neural-tts/ba-p/2102187), Different tasks of speech synthesis text analysis can be built on the BERT model, including: Word Segmentation, Part-of-Speech Tagging, Text Normalization, Polyphone Disambiguation and etc. This project is used to collect dataset information suitable for each task.

# Pretrained BERT
* [bert-base-chinese](https://huggingface.co/bert-base-chinese)
* [bert-base-multilingual-cased](https://huggingface.co/bert-base-multilingual-cased)
* [xlm-roberta-base](https://huggingface.co/xlm-roberta-base)


# Word Segmentation
| datasets | code |
| ----  | ------ |
| TODO | |

# Part-of-Speech Tagging
| datasets | code |
| ----  | ------ |
| TODO | |

# Text Normalization
| datasets / rules | code |
| ----  | ------ |
| rules | [WeTextProcessing](https://github.com/wenet-e2e/WeTextProcessing) |
| Text normalization covering grammars | [TextNormalizationCoveringGrammars](https://github.com/google-research-datasets/TextNormalizationCoveringGrammars) |
| TODO | |

# Polyphone Disambiguation
| datasets | code |
| ----  | ------ |
| g2PL | [https://github.com/whzikaros/g2pL](https://github.com/whzikaros/g2pL) |
| CPP (g2pM) | [https://github.com/kakaobrain/g2pm](https://github.com/kakaobrain/g2pm) |
| TODO | |
