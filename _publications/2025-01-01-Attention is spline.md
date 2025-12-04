---
title: "Attention is a smoothed cubic spline"
collection: publications
permalink: /publications/2025-01-01-attention-is-spline/
excerpt: 'Splines are important in transformers.'
venue: 'arXiv'
date: 2025-01-01
paperurl: 'https://www.arxiv.org/pdf/2408.09624'
citation: 'Zehua Lai, Lek-Heng Lim, and Yucong Liu. &quot;Attention is a smoothed cubic spline.&quot; arXiv e-prints (2024): arXiv-2408.09624'
---
We highlight a perhaps important but hitherto unobserved insight: The attention module in a transformer is a smoothed cubic spline. Viewed in this manner, this mysterious but critical component of a transformer becomes a natural development of an old notion deeply entrenched in classical approximation theory. More precisely, we show that with ReLU-activation, attention, masked attention, encoder-decoder attention are all cubic splines. As every component in a transformer is constructed out of compositions of various attention modules (= cubic splines) and feed forward neural networks (= linear splines), all its components -- encoder, decoder, and encoder-decoder blocks; multilayered encoders and decoders; the transformer itself -- are cubic or higher-order splines. If we assume the Pierce-Birkhoff conjecture, then the converse also holds, i.e., every spline is a ReLU-activated encoder. This insight sheds light on the nature of the transformer by casting it entirely in terms of splines, one of the best known and thoroughly understood objects in applied mathematics.
