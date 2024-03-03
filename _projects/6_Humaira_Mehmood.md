---
layout: page
title: An End-to-End Speech Translation System
description: A comprehensive overview of an end-to-end speech translation system for English to Urdu language direction, with a focus on overcoming data scarcity issues.
img: 
importance: 7
category: work
---

<div class="container text-justify">
<div class="row justify-content-center">
        <div class="text-justify">
            <p>This project aims to develop an end-to-end speech translation system for the English-Urdu language pair, using state-of-the-art conformer models and discrete unit techniques. The system is designed to overcome the challenges of data scarcity and language complexity in low-resource languages like Urdu and to provide natural and fluent speech-to-speech translation.</p>

 <h2>Introduction</h2>
            <p>Speech-to-speech translation (S2ST) is a fascinating and challenging research area that has the potential to enable seamless communication across languages and cultures. However, most of the existing S2ST systems are limited to high-resource languages, and face difficulties in dealing with low-resource languages like Urdu, which is the official language of Pakistan and one of the top 10 languages spoken in the world. Urdu is a complex and rich language that has multiple dialects and speech styles, posing significant challenges for developing effective S2ST systems for the Urdu-English language pair. </p>
                 <p>In this project, we present our approach to address these challenges and develop an end-to-end S2ST system for the English-Urdu language pair, using the Fairseq library. We leverage advanced techniques and innovative model architectures, such as conformer models and discrete unit techniques, to achieve high-quality and natural-sounding speech translation, even with limited training data.
</p>
            <h2>Direct Speech-to-Speech Translation:A Novel and Superior Method </h2>
            <p>This project presents an end-to-end speech translation system for English to Urdu language direction. The system leverages conformer models and the most recent discrete unit technique using the Fairseq library. It is specifically designed to address the challenges of data scarcity in low-resource languages like Urdu.</p>
 <p>In this section, we explain how our system implements a direct speech-to-speech translation approach, and how it outperforms traditional approaches that rely on merging machine translation (MT) and speech recognition. We also discuss the advantages and challenges of this novel and superior method.
</p>
            
            <h2>Traditional Approaches vs. Direct Speech-to-Speech Translation</h2> <p>Traditional approaches to speech-to-speech translation consist of two separate components: a speech recognition module that converts the source language speech to text, and a machine translation module that translates the text to the target language. These approaches have several drawbacks, such as:</p> <ul> <li><strong>Error propagation:</strong> The errors in the speech recognition module can affect the quality of the machine translation module, and vice versa. This can result in inaccurate and unnatural translations.</li> <li><strong>Latency:</strong> The two modules have to work sequentially, which adds to the delay in the translation process. This can affect the user experience and the interactivity of the communication.</li> <li><strong>Unnaturalness:</strong> The two modules do not share any information about the prosody, intonation, and emotion of the original speech, which can affect the naturalness and fluency of the translation.</li> </ul> <p>In contrast, our system implements a direct speech-to-speech translation approach, which directly maps the source language speech to the target language speech, without any intermediate text representation. This approach has several advantages, such as:</p> <ul> <li><strong>Accuracy:</strong> The system does not suffer from error propagation, as it does not rely on any intermediate text representation. This can improve the accuracy and quality of the translation.</li> <li><strong>Speed:</strong> The system works in an end-to-end manner, which reduces the latency in the translation process. This can improve the user experience and the interactivity of the communication.</li> <li><strong>Naturalness:</strong> The system preserves the prosody, intonation, and emotion of the original speech, and generates them in the target language speech. This can improve the naturalness and fluency of the translation.</li> </ul>

<h2>Advantages and Challenges of Direct Speech-to-Speech Translation</h2> <p>Our system leverages state-of-the-art techniques and innovative model architectures, such as conformer models and discrete unit techniques, to achieve high-quality and natural-sounding speech translation, even with limited training data. These techniques and architectures have shown superior performance in speech recognition and synthesis tasks and can capture both local and global dependencies in speech signals.</p> <p>However, direct speech-to-speech translation also poses some challenges, such as:</p> <ul> <li><strong>Data scarcity:</strong> The system requires parallel speech-to-speech data for effective training, which is scarce for low-resource languages like Urdu. To overcome this challenge, we have created a novel dataset for this project, which is the first of its kind parallel speech-to-speech data for the English-Urdu language pair.</li> <li><strong>Model complexity:</strong> The system involves complex and large models, which require high computational resources and memory for training and inference. To overcome this challenge, we have used discrete unit techniques, which reduce the vocabulary size and the computational complexity of the system.</li> <li><strong>Evaluation difficulty:</strong> The system requires multiple metrics and criteria to evaluate its performance, such as translation quality, speech quality, and user satisfaction. To overcome this challenge, we have used both objective and subjective methods to evaluate our system, such as BLEU, MOS, and human evaluation.</li> </ul>
            <h2>Addressing Data Scarcity and Dataset Utilization 
</h2>
            <p>One of the major obstacles to developing S2ST systems for low-resource languages like Urdu is the scarcity of open-source parallel datasets for effective training. To overcome this issue, we have created a novel dataset for this project, which is the first of its kind parallel speech-to-speech data for the English-Urdu language pair. This dataset can enable natural and fluent communication between speakers of these languages, and can also serve as a valuable resource for future research in this domain. Our dataset consists of 10,000 parallel speech utterances, covering various topics and domains, such as news, education, entertainment, and health. The speech utterances are recorded by native speakers of both languages and are manually transcribed and translated. The dataset is split into training, validation, and test sets, with a ratio of 80:10:10. We have also ensured the quality and diversity of the data by applying various criteria, such as length, gender, accent, and noise level.
Direct Speech-to-Speech Translation Unlike traditional systems that rely on merging machine translation (MT) and speech recognition, this project implements a direct speech-to-speech translation approach.

 This eliminates many of the issues associated with previous techniques, such as error propagation, latency, and unnaturalness. Our system directly maps the source language speech to the target language speech, without any intermediate text representation. This allows the system to preserve the prosody, intonation, and emotion of the original speech, and to generate more natural and fluent translations. To achieve this, we use state-of-the-art conformer models and discrete unit techniques, which have shown superior performance in speech recognition and synthesis tasks. Conformer models are a hybrid of convolutional and transformer models, which can capture both local and global dependencies in speech signals. Discrete unit techniques are methods of representing speech as a sequence of discrete units, such as phonemes, graphemes, or subwords, which can reduce the vocabulary size and the computational complexity of the system.
</p>
            <h2>Addressing the Challenges </h2>
            <p>The complexities of the Urdu language, with its multiple dialects and speech styles, present unique challenges for S2ST systems. To address these challenges, we have applied various techniques and strategies, such as data augmentation, and dialect identification. Data augmentation is a technique of increasing the amount and diversity of the training data by applying transformations, such as noise injection, speed perturbation, and pitch shifting. This can improve the robustness and generalization of the system, especially in noisy and low-resource scenarios. Dialect identification is a technique of identifying the dialect or speech style of the source language speech, such as formal or informal, and adjusting the translation accordingly. This can improve the naturalness and fluency of the translations, especially in cross-dialect scenarios.
</p>
            <h2>Motivation and Background of the Project</h2>
            <p>The communication gap between speakers of different languages can be reduced by leveraging S2ST. Despite the high demand, the majority of the work in S2ST is for high-resource languages. However, there are several barriers to speech translation of low-resource languages, such as Urdu. Urdu is not only the official language of Pakistan but also one of the top 10 languages spoken in the world. Therefore, there is a need to develop a translating system capable of bridging the communication barrier by instantly converting Urdu speech into English, and vice versa.</p>
            <h2>Corpus Creation</h2>
           <p>We present the methodology and the dataset that we have developed for a speech-to-speech translation system for the English-Urdu language pair. This dataset is the first of its kind parallel speech-to-speech data for this language pair, which can enable natural and fluent communication between speakers of these languages.</p>
<h3>Data Processing</h3>
<p>Data processing is a crucial step for building a S2ST system, as it prepares the data for training and inference. In this section, we describe the steps and tools that we used for converting the data to .wav format, translating the transcripts to the target languages, and generating speech from the translated texts.</p>
<h3>Audio Conversion</h3> <p>The first step of data processing is to convert the audio files from different formats and sources to a standard .wav format. This ensures that the data is consistent and compatible with our speech-to-speech system. We used the FFmpeg tool to perform the audio conversion, which is a fast and versatile tool for handling multimedia files.</p>
<h3>Data Translation</h3> <p>The second step of data processing is to translate the transcripts from one language to another. This enables us to create parallel data for both directions of our speech-to-speech system: English to Urdu (En-UR) and Urdu to English (Ur-En). We used the Fairseq library to perform the data translation, which is a framework for sequence-to-sequence modeling. We trained transformer-based models on the text-to-text corpus, and evaluated them using the BLEU metric. The models achieved high translation quality and accuracy on the data.</p>
<h3>Post-Processing of Translated Texts</h3> <p>To improve the quality and consistency of the translated texts, we performed post-processing on the text-to-text corpus. This involved manual inspection to evaluate the accuracy of the translations. We also used human evaluators to check the translations for fluency, adequacy, and grammatical correctness. Any discrepancies or errors in the translated texts were corrected to improve their overall quality.</p>
<h3>Speech Generation</h3> <p>The third step of data processing is to generate speech from the translated texts. This allows us to create synthetic speech data in the target languages for our speech-to-speech system. We used the Tacotron 2 model to perform the speech generation, which is a neural network-based model for text-to-speech synthesis. We trained the model on the translated texts, and evaluated it using the MOS metric. The model produced natural and clear speech outputs from the data.</p>
<h3>Speech Preprocessing</h3> <p>Preprocessing of the speech data was necessary to ensure the quality and compatibility of the generated corpus. We applied various techniques, such as audio normalization, noise reduction, and segmentation of speech into smaller units, such as sentences or phrases. These preprocessing steps were essential for subsequent analysis and modeling.</p>
<h3>Data Filtering and Augmentation</h3> <p>To eliminate noisy or low-quality samples, we applied data filtering techniques to the corpus. This helped in removing problematic instances that could potentially affect the performance of the speech-to-speech translation system. Additionally, we employed data augmentation techniques, such as speed perturbation or noise injection, to enhance the diversity and quantity of the corpus.</p>
<h2>Potential of the Project</h2> <p>The potential of this project is immense. By providing accurate and natural-sounding translations for low-resource languages, it can help break down language barriers and facilitate better communication. Furthermore, the techniques and approaches used in this project could be applied to other low-resource languages, further expanding its impact.</p>

<h3>Possible Applications</h3> <p>Some of the possible applications or scenarios where our system could be useful are:</p> <ul> <li><strong>Education:</strong> Our system could enable students and teachers to access educational materials and courses in different languages, and to interact with each other across linguistic boundaries.</li> <li><strong>Tourism:</strong> Our system could enable travelers and tourists to explore new places and cultures, and to communicate with local people and guides in their native languages.</li> <li><strong>Business:</strong> Our system could enable business professionals and entrepreneurs to conduct meetings and negotiations with foreign partners and clients, and to access global markets and opportunities.</li> </ul>

<h2>Future Directions</h2> <p>Future work on this project will focus on further improving the system’s performance, expanding its capabilities, and making it more accessible and user-friendly. This includes exploring new model architectures, developing more effective training techniques, and creating a user-friendly interface for the system.</p>




        </div>
    </div>
</div>