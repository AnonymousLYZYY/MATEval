# MATEval

In the Alipay business scenario, we need to assess open story texts generated by large models. For this specific business context, we have proposed a multi-agent evaluation framework called MATEval. Within this framework, we have integrated strategies of self-reflection and Chain-of-Thought (CoT), and we have also introduced a feedback mechanism at the end of each round of discussion. This mechanism evaluates the quality of each discussion round, facilitating consensus. Ultimately, we require a summarizer to consolidate the results of the entire discussion process. We provide two formats of output: one in the form of Q&A pairs, and the other as text reports that are easy for humans to read. Extensive experiments demonstrate that MATEval's evaluation results on two classic story datasets are more aligned with human preferences compared to existing methods.

<img width="855" alt="image" src="https://github.com/AnonymousLYZYY/MATEval/assets/157742453/946a381a-9d2a-4e7e-a73d-4c90eadf3441">
