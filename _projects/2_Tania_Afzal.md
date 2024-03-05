---
layout: page
title: Creation of Corpora and Analysis of Semantic Distance Between Sentence Translation in Various Languages
description: A comprehensive overview oevaluates the semantic similarity between multilingual translations of the Holy Quran and its original Arabic version, employing Large Language Models (LLMs) and cosine similarity distance calculations.
img: assets/img/semantic-diff.jpg
importance: 7
category: work
---

<div class="container text-justify">
<div class="row justify-content-center">
        <div class="text-justify">
            <h2>Introduction</h2>
            <p>This study explores semantic similarity in multilingual translations of the Holy Quran, leveraging Large Language Models (LLMs) and cosine similarity distances. It aims to gauge how faithfully translations capture the core meaning of the original Arabic text. Recent advancements in the field of semantic similarity, such as the Semantic Textual Similarity (STS) task, have witnessed significant progress, offering diverse applications in NLP. By employing transformer models like BERT, GPT, and RoBERTa, this research explores the nuanced interpretations introduced by different translators across languages, shedding light on both similarities and variations in translations. Through comprehensive experiments, it seeks to understand how these models handle meaning in different languages and interpret the semantic relationships between Quranic verses.</p>
            <p>Existing research focuses on monolingual approaches in Quranic translations, lacking comprehensive insights into multilingual semantic similarity. Our research delves into the intricacies of semantics in Holy Quran translations, considering variations introduced by authors. By comparing translations from distinct language families, we aim to quantify semantic similarity, addressing challenges posed by the dominance of Indo-European languages in existing models. The study also investigates semantic relationships between surah pairs and explores verse-level semantics using the Qursim dataset.</p>
            <h2>Preprocessing and Training</h2>
            <p>For the multilingual training strategy, translations from Tanzil.net were preprocessed using regex to eliminate stopwords, Surah, and Ayah numbers. Verses were converted into lists for compatibility with Large Language Models (LLMs). The dataset was then encoded using the paraphrase-multilingual-MiniLM-L12-v2 and paraphrase-multilingual-mpnet-base-v2 models from sentence transformer libraries, converting the text into numerical representations.</p>
            <p>In the fine-tuning process, we employed a comprehensive training approach. The model underwent 50 epochs of training with a batch size of 16. Two monolingual language models, AraBERTv02 and Camelbert, were incorporated for fine-tuning, along with a multilingual sentence-transformers/paraphrase-MiniLM-L12-v2 model. The learning rate was set at 2e-5, and the Adam optimizer facilitated the updating of model parameters during training. This strategy ensured the effective adaptation of the model to the multilingual nuances of the Qursim dataset, enhancing its capability to accurately capture semantic relationships between verses in various languages.</p>
            <div class="row">
                <div class="col-sm mt-3 mt-md-0">
             {% include figure.html path="assets/img/zero-shot.png" title="example image" class="img-fluid rounded z-depth-1" %}
                </div>
            </div>  
            <h2>Evaluation and Performance</h2>
            <p>Exploring surah pair similarity offers a promising direction for future research. By leveraging advanced NLP techniques and large pre-trained language models like BERT and GPT, researchers can analyze thematic and structural resemblances between pairs of surahs in the Holy Quran. Integrating linguistic and theological insights, along with collaboration with Islamic studies experts, could enhance the understanding of surah pairs' significance. Developing tailored methodologies for measuring semantic textual similarity in religious texts may further improve analysis accuracy. Overall, investigating surah pair similarity could unveil deeper layers of meaning in the Quran, enriching its theological and literary understanding.</p>
            <h2>Future Directions</h2>
            <p>Future research in zero-shot NMT for low-resource languages should focus on improving translation quality, scalability, and resource efficiency. Techniques such as semi-supervised learning, active learning, and zero-resource translation hold promise for enhancing model performance with limited data. Additionally, efforts to build larger and more diverse multilingual corpora can further empower zero-shot NMT systems to bridge language barriers effectively.</p>
            <h2>Conclusion</h2>
            <p>This study highlights the efficacy of Large Language Models (LLMs) in discerning semantic nuances across multilingual translations of the Holy Quran. Through comprehensive analysis, it identifies translations closely aligned with the original text and reveals language family alignments, with Slavic and Indo-Iranian languages exhibiting notable adherence. By quantifying semantic similarity using the Qursim dataset, our findings underscore the invaluable role of LLMs in ensuring semantic consistency across diverse translations.</p>
        </div>
    </div>
</div>
