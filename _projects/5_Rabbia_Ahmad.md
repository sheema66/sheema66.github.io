---
layout: page
title: Context-Aware Financial Sentiment Analysis
description: The detailed overview of Financial Domain Sentiment Analysis
img: assets/img/sentiment.png
importance: 5
category: work
---

<div class="container text-justify">
<div class="row justify-content-center">
        <div class="text-justify">
            <p> The aim of this project is to develop a context-aware financial sentiment analyzer using state-of-the-art large language models and prompting techniques. The goal is to predict sentiment of a company based on its annual report to help investors and financial forcasters to make informed financial decisions.</p>

 <h2>Introduction</h2>
 <p>Specific to the domain of finance and economics Financial Sentiment Analysis (FSA) is used to predict financial market sentiment for financial forecasting and stock market predictions. It plays a significant role in the domian of Natural Language Financial Forcasting (NLFF) in influencing factor like financial market decisions, price fluctuation, trading, and information flow in the market.</p>
 
 <p>Our goal with this project is to create a domain-specific analyzer that provide sentiment of the company by analyzing its annual report and incorporate local and global context to make informed decision. Local context is the context from specific pint-of-view e.g product price, sales of the year of the report and global context looks at the broader scope of the document. We leverage advanced techniques and AI model, such as LLMs and instruct-tuning techniques, to predict sentiment of the financial reports.</p>
 

<h2>Context-Awareness </h2>
<p>Context-aware sentiment analysis takes into account the context of the text being analyzed for predicting sentiment. This approach can provide a more accurate and nuanced understanding of sentiment by considering contextual information. Contextual information includes local and global context. Local context is the context from a certain aspect or perspective such as the company's sentiment derived from the Chairman's Review and Directors' review section. On the other hand, the global context focuses on the larger context such as the sector of the company; Pharmaceuticals, Baking, Textile, etc.
</p>
       

<h2>Sentiment from Fianacial Reports</h2>
<p>Financial reports are complex PDF documents containing hundreds of pages, with different sections contributing to different kinds of sentiment for various audiences. The Director's review section provides insights from the company's leadership, often highlighting strategic decisions and future directions. The Chairman's review section offers an overarching perspective on company performance, focusing on long-term vision and stakeholder relations. The Auditor's review section delivers an objective assessment of the company's financial health and compliance, crucial for investors and regulatory bodies. Each section provides a unique outlook on the company's performance, catering to a diverse audience, including investors, analysts, regulators, and stakeholders.</p>

<h2>Financial Reports</h2>
<p>The data of this project are financial reports of Pakistani Comapnies. These are available in .pdf fromt on Pakistan Stock Exchange <a href="https://financials.psx.com.pk/">website</a>. The quateraly and annual reports of each registered comapny is uploaded at the end of a quater. The reports contains multiple sections and not all are relevant for FSA.</p>

<ul>          
<li>There is not standard formt the companies follow. Each company have its own format for their reports.</li>
<li>The reports are mix of textual, tabular and graphical data.</li>        
<li>Quality of some images is not good enough for OCR to accurately convert it into text.</li>
</ul>         

These complexities are failing pdf-to-text libraries to extract quality data. Hence the majority work on data extraction has been manual by first coverting pdf files to docx and then extracting relevant sections such as Director, Chairman and Auitor reports.

<h2>Prompt Engineering</h2>
<p>Prompting has been showing impressive results on multiple Natural Language Uderstanding and Natural Language Generation tasks. With an advancemnt in AI, tools like Chatgpt and Bing Chat, Meta AI etc are taking over the internet by storm. However, to make the best of them a  careful prompt design is required with a considered format, length, style, and content of the prompts. It also requires proper evaluation methods that measure the quality, diversity, and consistency of the responses as well as dealing with potential errors, biases, and vulnerabilities of LLMs that can affect their performance and trustworthiness.</p>
 
 <p>Depending on the type and complexity of the task, the amount and quality of the available data, and the capabilities and limitations of the LLM, prompt engineering can be performed using different techniques. These techniques are categorized as zero-shot learning, few-shot learning, instruction tuning, and prompt tuning. We wanted to see how these tools and techniques would react for our data.</p>

<p>In light of this research, we are tested and analyzed how prompting perform context-aware financial sentiment analysis tasks for complex data such as financial reports of companies. The sub-research is titled <strong>Leveraging Large Language Models and Prompt Settings For Context-Aware Financial Sentiment Analysis</strong> and is accepted <strong>2024 5th International Conference on Advancements in Computational Sciences (ICACS)</strong> and published in <strong>IEEE Xplore Digital Library</strong>.</p>

<p>This paper explores the use of prompt engineering and large language models (LLMs) for context-aware financial sentiment analysis on Director review section in financial reports of Pakistani companies. Zero-shot and few-shot prompts were designed to extract sentiment and contextual information, with results compared against human evaluations. The study tested ChatGPT, Bing Chat, Cohere and BARD on same prompts for 10 different director review sections. Results showed varying performance and output quality among LLMs, influenced by prompt design, report content, and task complexity. BARD performed closest to human evaluators, especially in few-shot settings, while none matched human evaluation for global sentiment in zero-shot settings due to limited contextual information. The findings highlight the need for further research to refine prompts and improve LLM performance, suggesting future directions to enhance prompt design and context understanding.</p>

<h2>LLM Testing and Instruct Tuning</h2>
<p>With Prompt enginnering showing interesting results we have decided to go with large language models that utilize instruct-tuning for prompt-based model training. Upon studying these models the extracted reports will be preprocessed accordingly. Flan-t5 is being tested along with finGPT.</p>


<h2>Fine-tuned GPT-2 on FSA Dataset</h2>
<p>We also fine-tuned GPT-2 on the financial sentiment analysis corpus of the size of 30219 labeled sentences and returned an accuracy of 0.94.  To create the dataset, available datasets on Kaggle and HuggingFace were collected and concatenated. The Director review section of the reports are provided as an input sentence to find the sentiment. The results are a singular sentiment with 0.65 accuracy. Reports are too complex as an input for GPT-2.</p>


<h2>Potential of the Project</h2>
<p>The project holds immese potential in the domain of NLFF - Natural Language Financial Forecasting. It can be be used by investors and company owners alike to analyze the performance of the company for financial decsison making such as price fluctuation, trading, and stock market etc.

</p>

<h3>Applications</h3> <p>Few possible applications where our system could be useful:</p> 
<ul> 
<li><strong>Corporate Disclosures:</strong> Analyzing sentiment in company reports and disclosures to assess market impact.</li> 
<li><strong>Market Forecasting:</strong> Predicting market movements based on sentiment trends. </li> 
<li><strong>Investment Strategies:</strong> Enhancing investment decisions using sentiment insights.</li> 
<li><strong>Earnings Calls:</strong>Understanding investor sentiment during earnings announcements.</li> 
<li><strong>Financial News:</strong>Tracking market trends by analyzing sentiments in news articles.</li> 
 
<!-- <li><strong></strong></li> -->
 </ul>



<h2>Future Directions</h2> 
<p>Future work on this project will aim to further enhance the system’s performance, expand its capabilities. This will involve exploring new model and data appraches, developing more effective training methods, and creating more applictions.</p>




        </div>
    </div>
</div>
