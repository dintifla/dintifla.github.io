---
title: "Advancing STT for Low-Resource Real-World Speech"
collection: publications
category: conferences
permalink: /publication/2025-04-30-Advancing-STT-for-Low-Resource-Real-World-Speech
excerpt: "This paper is about a real-world speech to text for low-resource languages, like Swiss German"
date: 2025-05-30
venue: "HCI International 2025, Gothenburg"
paperurl: "https://link.springer.com/chapter/10.1007/978-3-031-93429-2_20"
citation: "D’Intino, F., Hutter, HP. (2025). Advancing STT for Low-Resource Real-World Speech. In: Degen, H., Ntoa, S. (eds) Artificial Intelligence in HCI. HCII 2025. Lecture Notes in Computer Science(), vol 15822. Springer, Cham. https://doi.org/10.1007/978-3-031-93429-2_20"
---

Swiss German is a low-resource language represented by diverse dialects that differ significantly from Standard German and from each other, lacking a standardized written form. As a result, transcribing Swiss German involves translating into Standard German. Existing datasets have been collected in controlled environments, yielding effective speech-to-text (STT) models, but these models struggle with spontaneous conversational speech.

This paper, therefore, introduces the new SRB-300 dataset, a 300-h annotated speech corpus featuring real-world long-audio recordings from 39 Swiss German radio and TV stations. It captures spontaneous speech across all major Swiss dialects recorded in various realistic environments and overcomes the limitation of prior sentence-level corpora.

We fine-tuned multiple OpenAI Whisper models on the SRB-300 dataset, achieving notable enhancements over previous zero-shot performance metrics. Improvements in word error rate (WER) ranged from 19% to 33%, while BLEU scores increased between 8% and 40%. The best fine-tuned model, large-v3, achieved a WER of 17.1% and a BLEU score of 74.8. This advancement is crucial for developing effective and robust STT systems for Swiss German and other low-resource languages in real-world contexts.
