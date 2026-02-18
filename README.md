TITLE: AN ADAPTIVE PREPROCESSING PIPELINE SYSTEM FOR ENHANCED OCR ACCURACY ON SCANNED DOCUMENTS
Authors: Suman Gorkhali (Student), Jicheng Fu (Faculty Mentor)
Institution: University of Central Oklahoma
This project investigate the ways that specific algorithms that enhance the outcome of extracting user-required information from scanned documents. 
It is hypothesized that web-based Large Language Models (LLM) can extract less than 63.33% of the needed information accurately. 
The digitization of old documents is challenging due to poor scan quality, including skew, warping, low contrast and noise. 
Traditional OCR employs fixed enhancement sequences that struggle to address diverse quality degradations encountered in real-world document collections, 
necessitating an intelligent, adaptive approach. To address these limitations, the project presents an automated framework designed to dynamically evaluate
multiple preprocessing combinations to identify optimal image enhancement strategies for each page. The system integrates eight distinct image enhancement primitives, 
including deskewing, page dewarping, grayscale conversion, adaptive binarization, noise reduction, and morphological operations, which are organized into 13 pipeline 
architectures to maximize OCR accuracy. The framework employs a systematic optimization routine wherein each page is processed through the entire ensemble of 
pipeline configurations. Selection of the optimal image state is governed by a multi-parameter objective function, including confidence scores and character density 
metrics. The system then automatically selects the best-performing configuration based on these criteria. The technical implementation utilizes computer vision 
techniques that model pages as curved 3D surfaces and apply inverse transformations to flatten warped documents. A significant contribution is the integration of a 
local LLM to perform context- and content-aware data extraction. Unlike traditional pattern-matching techniques, it leverages semantic understanding to distill 
unstructured OCR text into user-defined schemas. Multi-page experimental validation demonstrates significant advantages, with performance across pipelines ranging 
from 41% to 101% confidence scores, confirming no single preprocessing trajectory is universally effective. The system achieved overall accuracy averaging 92.72% 
confidence scores. These results demonstrate that individual pages within a single collection require distinct enhancement strategies, a critical 
factor in high-fidelity digitization. This research demonstrates that the synergy of adaptive preprocessing automation and local LLM-driven semantic 
extraction significantly elevates OCR performance metrics.
