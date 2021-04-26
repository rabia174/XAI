# XAI


# Open source tools
* [DALEX](https://dalex.drwhy.ai/python/)
* [AIX360](https://github.com/Trusted-AI/AIX360)


## Papers and code of Explainable AI esp. w.r.t. Image classificiation


### 2013 Conference Papers
| Title | Paper Title                                                                                                 | Source Link                                                                                                                                                                                            | Code                                                                                          | Tags                                                                              |
| ------------ | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **Visualization of CNN** | Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps | [CVPR2013](https://arxiv.org/pdf/1312.6034v2.pdf) | [PyTorch](https://github.com/idiap/fullgrad-saliency) | `Visualization gradient-based saliency maps`  |



### 2016 Conference Papers
| Title | Paper Title                                                                                                 | Source Link                                                                                                                                                                                            | Code                                                                                          | Tags                                                                              |
| ------------ | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **CAM** | [Learning Deep Features for Discriminative Localization](http://cnnlocalization.csail.mit.edu/) | [CVPR2016](https://arxiv.org/pdf/1512.04150v1.pdf) | [PyTorch (Official)](https://github.com/zhoubolei/CAM) | `class activation mapping`  |
| **LIME** | [“Why Should I Trust You?”Explaining the Predictions of Any Classifier](https://homes.cs.washington.edu/~marcotcr/blog/lime/) | [KDD2016](https://www.kdd.org/kdd2016/papers/files/rfp0573-ribeiroA.pdf) | [PyTorch (Official)](https://github.com/marcotcr/lime-experiments) | `trust a prediction`  |



### 2017 Conference Papers
| Title | Paper Title                                                                                                 | Source Link                                                                                                                                                                                            | Code                                                                                          | Tags                                                                              |
| ------------ | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **Grad-CAM** | Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization | [ICCV2017, CVPR2016 (original)](https://arxiv.org/pdf/1610.02391.pdf) | [PyTorch](https://github.com/jacobgil/pytorch-grad-cam) | `Visualization gradient-based saliency maps`  |
| **Network Dissection** | [Network Dissection: Quantifying Interpretability of Deep Visual Representations](http://netdissect.csail.mit.edu/) | [CVPR2017](https://arxiv.org/pdf/1704.05796.pdf) | [PyTorch (Official)](https://github.com/CSAILVision/NetDissect) | `Visualization`  |


### 2018 Conference Papers
| Title | Paper Title                                                                                                 | Source Link                                                                                                                                                                                            | Code                                                                                          | Tags                                                                              |
| ------------ | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **TCAV** | [Interpretability Beyond Feature Attribution:Quantitative Testing with Concept Activation Vectors (TCAV)](https://beenkim.github.io/) | [ICML 2018](https://arxiv.org/pdf/1711.11279.pdf) | [Tensorflow 1.15.2](https://github.com/tensorflow/tcav) | `interpretability method`  |
| **Interpretable CNN** | [Interpretable Convolutional Neural Networks](http://qszhang.com/index.php/icnn/) | [CVPR 2018](https://arxiv.org/pdf/1710.00935.pdf) | [Tensorflow 1.x](https://github.com/andrehuang/InterpretableCNN) | `explainability by design`  |
| **Anchors** | Anchors: High-Precision Model-Agnostic Explanations | [AAAI 2018](https://homes.cs.washington.edu/~marcotcr/aaai18.pdf) | [sklearn (Official)](https://github.com/marcotcr/anchor-experiments) | `model-agnostic`  |
| **Sanity Checks** | [Sanity checks for saliency maps](http://papers.nips.cc/paper/8160-sanity-checks-for-saliency-maps) | [NeurIPS 2018](https://papers.nips.cc/paper/8160-sanity-checks-for-saliency-maps.pdf) | [PyTorch](https://github.com/jendawkins/saliencySanity) | `saliency methods vs edge detector`  |
| **Grad Cam++** | [Grad Cam++:Improved Visual Explanations forDeep Convolutional Networks](https://ieeexplore.ieee.org/document/8354201) | [WACV 2018](https://arxiv.org/pdf/1710.11063.pdf) | [PyTorch](https://github.com/1Konny/gradcam_plus_plus-pytorch) | `saliency maps`  |
|**Interpretable Basis**|Interpretable Basis Decomposition for Visual Explanation|[ECCV 2018](https://openaccess.thecvf.com/content_ECCV_2018/papers/Antonio_Torralba_Interpretable_Basis_Decomposition_ECCV_2018_paper.pdf)|[PyTorch](https://github.com/CSAILVision/IBD)|`ibd`|

### 2019 Conference Papers
| Title | Paper Title                                                                                                 | Source Link                                                                                                                                                                                            | Code                                                                                          | Tags                                                                              |
| ------------ | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **Full-grad** | [Full-Gradient Representation for Neural Network Visualization](https://www.idiap.ch/workshop/smld2019/slides/smld2019_suraj_srinivas.pdf) | [NeurIPS2019](https://arxiv.org/pdf/1905.00780.pdf) | [PyTorch (Official)](https://github.com/idiap/fullgrad-saliency) [Tensorflow](https://github.com/vk1996/fullgradsaliency_tf) | `saliency map representation`  |
| **This looks like that** | [This Looks Like That: Deep Learning for Interpretable Image Recognition](https://papers.nips.cc/paper/9095-this-looks-like-that-deep-learning-for-interpretable-image-recognition) | [NeurIPS2019](https://papers.nips.cc/paper/9095-this-looks-like-that-deep-learning-for-interpretable-image-recognition.pdf) | [PyTorch (Official)](https://github.com/cfchen-duke/ProtoPNet) | `object`  |
| **Counterfactual visual explanations** | Counterfactual visual explanations | [ICML2019](https://arxiv.org/pdf/1904.07451v2.pdf) |  | `interpretability`  |
|**concept with contribution interpretable cnn**|Explaining Neural Networks Semantically and Quantitatively|[ICCV 2019](https://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Explaining_Neural_Networks_Semantically_and_Quantitatively_ICCV_2019_paper.pdf)|||
|**SIS**|[What made you do this? Understanding black-box decisions with sufficient input subsets](http://proceedings.mlr.press/v89/carter19a/carter19a.pdf)|[AISTATS 2019 - Supplementary Material](http://proceedings.mlr.press/v89/carter19a/carter19a-supp.pdf)|[Tensorflow 1.x](https://github.com/b-carter/SufficientInputSubsets)||
|**Filter as concept detector**|Filters in Convolutional Neural Networks as Independent Detectors of Visual Concepts|[ACM](https://dl.acm.org/doi/10.1145/3345252.3345294)|||

### 2020 Papers
| Title | Paper Title                                                                                                 | Source Link                                                                                                                                                                                            | Code                                                                                          | Tags                                                             |
| ------------ | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **INN** | [Making Sense of CNNs: Interpreting Deep Representations & Their Invariances with INNs](https://compvis.github.io/invariances/)  | [ECCV 2020](https://arxiv.org/pdf/2008.01777.pdf) | [PyTorch](https://github.com/CompVis/invariances) | `explainability by design` |
| **X-Grad CAM** | [Axiom-based Grad-CAM: Towards Accurate Visualization and Explanation of CNNs ](https://arxiv.org/pdf/2008.02312.pdf) | | [PyTorch](https://github.com/Fu0511/XGrad-CAM) | |
| **Revisiting BP saliency** | [There and Back Again: Revisiting Backpropagation Saliency Methods](https://arxiv.org/pdf/2004.02866.pdf)| [CVPR 2020](https://openaccess.thecvf.com/content_CVPR_2020/papers/Rebuffi_There_and_Back_Again_Revisiting_Backpropagation_Saliency_Methods_CVPR_2020_paper.pdf)| [PyTorch](https://github.com/srebuffi/revisiting_saliency)|`grad cam failure noted`|
|**Interacting with explanation**| [Making deep neural networks right for the right scientific reasons by interacting with their explanations](https://arxiv.org/pdf/2001.05371.pdf)| [Nature Machine Intelligence](https://www.nature.com/articles/s42256-020-0212-3)|[sklearn](https://codeocean.com/capsule/7818629/tree/v1)||
|**Class specific Filters**|[Training Interpretable Convolutional Neural Networks by Differentiating Class-specific Filters](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470613.pdf)|[ECCV Supplementary Material](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470613-supp.pdf)|[Code - not yet updated](https://github.com/hyliang96/CSGCNN)|[ICLR rejected version with reviews](https://openreview.net/forum?id=r1ltnp4KwS)|
|**Interpretable Decoupling**|Interpretable Neural Network Decoupling|[ECCV 2020](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600647.pdf)|||
|**iCaps**|[iCaps: An Interpretable Classifier via Disentangled Capsule Networks](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123640307.pdf)|[ECCV Supplementary Material](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123640307-supp.pdf)|||
|**VQA**|Interpretable Visual Reasoning via Probabilistic Formulation under Natural Supervision|[ECCV 2020](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540528.pdf)|[PyTorch](https://github.com/GeraldHan/TRN)||
|**When explanations lie**|When Explanations Lie: Why Many Modified BP Attributions Fail|[ICML 2020](https://arxiv.org/pdf/1912.09818v6.pdf)|[PyTorch](https://github.com/berleon/when-explanations-lie)||
|**Similarity models**|Towards Visually Explaining Similarity Models| [Arxiv](https://arxiv.org/pdf/2008.06035.pdf)|||
|**Quantify trust**|How Much Should I Trust You? Modeling Uncertainty of Black Box Explanations|[NeurIPS 2020 submission](https://arxiv.org/pdf/2008.05030.pdf)||`hima_lakkaraju`,`sameer_singh`,`model-agnostic`|
|**Concepts for segmentation task**|ABSTRACTING DEEP NEURAL NETWORKS INTO CONCEPT GRAPHS FOR CONCEPT LEVEL INTERPRETABILITY| [Arxiv](https://arxiv.org/pdf/2008.06457.pdf)|[Tensorflow 1.14](https://github.com/koriavinash1/BioExp)|`brain tumour segmentation`|
|**Deep Lift based Network Pruning**|Utilizing Explainable AI for Quantization and Pruning of Deep Neural Networks|[Arxiv NeurIPS format](https://arxiv.org/pdf/2008.09072.pdf)||`nas`,`deep_lift`|
|**Unifed Attribution Framework**|A Unified Taylor Framework for Revisiting Attribution Methods|[Arxiv](https://arxiv.org/pdf/2008.09695.pdf)||`taylor`,`attribution_framework`|
|**Global Cocept Attribution**|Towards Global Explanations of Convolutional Neural Networks with Concept Attribution|[CVPR 2020](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Towards_Global_Explanations_of_Convolutional_Neural_Networks_With_Concept_Attribution_CVPR_2020_paper.pdf)|||
|**relevance estimation**|Determining the Relevance of Features for Deep Neural Networks|[ECCV 2020](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710324.pdf)|||
|**localized concept maps**|Explaining AI-based Decision Support Systems using Concept Localization Maps|[Arxiv](https://arxiv.org/pdf/2005.01399.pdf)|[Just repository created](https://github.com/adriano-lucieri/SCDB)||
|**quantify saliency**|Quantifying Explainability of Saliency Methods in Deep Neural Networks|[Arxiv](https://arxiv.org/pdf/2009.02899.pdf)|[PyTorch](https://github.com/etjoa003/explainable_ai/tree/master/xai_basic)||
|**generalization of LIME - MeLIME**|MeLIME: Meaningful Local Explanation for Machine Learning Models|[Arxiv](https://arxiv.org/pdf/2009.05818.pdf)|[Tensorflow 1.15](https://github.com/tiagobotari/melime)||
|**global counterfactual explanations**|Interpretable and Interactive Summaries of Actionable Recourses|[Arxiv](https://arxiv.org/pdf/2009.07165.pdf)|||
|**fine grained counterfactual heatmaps**|SCOUTER: Slot Attention-based Classifier for Explainable Image Recognition|[Arxiv](https://arxiv.org/pdf/2009.06138.pdf)|[PyTorch](https://github.com/wbw520/scouter)|`scouter`|
|**quantify trust**|How Much Can We Really Trust You? Towards Simple, Interpretable Trust Quantification Metrics for Deep Neural Networks|[Arxiv](https://arxiv.org/pdf/2009.05835.pdf)|||
|**Non-negative concept activation vectors**|IMPROVING INTERPRETABILITY OF CNN MODELS USING NON-NEGATIVE CONCEPT ACTIVATION VECTORS|[Arxiv](https://arxiv.org/pdf/2006.15417.pdf)|||
|**different layer activations**|Explaining Neural Networks by Decoding Layer Activations|[Arxiv](https://arxiv.org/pdf/2005.13630.pdf)|||
|**concept bottleneck networks**|Concept Bottleneck Models|[ICML 2020](https://arxiv.org/pdf/2007.04612.pdf)|[PyTorch](https://github.com/yewsiang/ConceptBottleneck)||
|**attribution**|Visualizing the Impact of Feature Attribution Baselines|[Distill](https://distill.pub/2020/attribution-baselines/)|||
|**CSI**|Contextual Semantic Interpretability|[Arxiv](https://arxiv.org/pdf/2009.08720.pdf)||`explainable_by_design`|
|**Improve black box via explanation**|Introspective Learning by Distilling Knowledge from Online Self-explanation|[Arxiv](https://arxiv.org/pdf/2009.09140.pdf)||`kowledge_distillation`|
|**Patch explanations**|Information-Theoretic Visual Explanation for Black-Box Classifiers|[Arxiv](https://arxiv.org/pdf/2009.11150.pdf)|[Tensorflow 1.13.1](https://github.com/nuclearboy95/XAI-Information-Theoretic-Explanation)|`patch_sampling`,`information_theory`|
|**Causality**|Long-Tailed Classification by Keeping the Good and Removing the Bad Momentum Causal Effect|[NeurIPS 2020](https://arxiv.org/pdf/2009.12991.pdf)|[PyTorch](https://github.com/KaihuaTang/Long-Tailed-Recognition.pytorch)||
|**Concept in Time series data**|Conceptual Explanations of Neural Network Prediction for Time Series|[IJCNN 2020](https://ieeexplore.ieee.org/abstract/document/9207341)||`time series`, see if useful someway|
|**Explainable by Design**|Trustworthy Convolutional Neural Networks:A Gradient Penalized-based Approach|[Arxiv](https://arxiv.org/pdf/2009.14260.pdf)|||
|**Colorwise Saliency**|Visualizing Color-wise Saliency of Black-Box Image Classification Models|[Arxiv](https://arxiv.org/pdf/2010.02468.pdf)|||
|**concept based**|Concept Discovery for The Interpretation of Landscape Scenicness|[Downloadable File](http://scholar.google.com/scholar_url?url=https://www.mdpi.com/2504-4990/2/4/22/pdf&hl=en&sa=X&d=12192174510919644222&ei=vaqAX7fnGI_0mQGm8I2ICA&scisig=AAGBfm09-RfHy9jYkScMc35gIka4QNGK2g&nossl=1&oi=scholaralrt&hist=BCMO2BgAAAAJ:4701032511550201990:AAGBfm0MkjlI8LZjYB7rSwLsWyRhGrltyg&html=)|||If file not downloadable, search title in Google Scholar `cites TCAV`|
|**Integrated Score CAM**|IS-CAM: Integrated Score-CAM for axiomatic-based explanations|[Arxiv](https://arxiv.org/pdf/2010.03023.pdf)|||
|**Grad LAM**|Grad-LAM: Visualization of Deep Neural Networks for Unsupervised Learning|[EURASIP 2020](https://www.eurasip.org/Proceedings/Eusipco/Eusipco2020/pdfs/0001407.pdf)|||
|**Cites TCAV**|Integrating Intrinsic and Extrinsic Explainability: The Relevance of Understanding Neural Networks for Human-Robot Interaction|[AAAI 2020](https://arxiv.org/pdf/2010.04602.pdf)|||
|**Attribution**|Learning Propagation Rules for Attribution Map Generation|[Arxiv](https://arxiv.org/pdf/2010.07210.pdf)|||
|**Zoom CAM**|Zoom-CAM: Generating Fine-grained Pixel Annotations from Image Labels|[Arxiv](https://arxiv.org/pdf/2010.08644.pdf)||`must read before modularity proposal`|
|**Masking based saliency maps investigation**|INVESTIGATING AND SIMPLIFYING MASKING-BASED SALIENCY MAP METHODS FOR MODEL INTERPRETABILITY|[Arxiv](https://arxiv.org/pdf/2010.09750.pdf)|[PyTorch](https://github.com/zphang/saliency_investigation)||
|**Evaluation**|Evaluating Attribution Methods using White-Box LSTMs|[EMNLP Workshop](https://arxiv.org/pdf/2010.08606.pdf)|[PyTorch](https://github.com/yidinghao/whitebox-lstm)|`cites TCAV`, `says all explanations fail their test`|
|**Interpretable Bayesian Neural Networks**|Incorporating Interpretable Output Constraints in Bayesian Neural Networks|[NeurIPS 2020](https://arxiv.org/pdf/2010.10969.pdf)|[PyTorch](https://github.com/dtak/ocbnn-public)||
|**Survey - Counterfactual explanations**|Counterfactual Explanations for Machine Learning: A Review|[Arxiv](https://arxiv.org/pdf/2010.10596.pdf)|||
|**Standardised Explainability**|The Need for Standardised Explainability|[ICML 2020 Workshop](https://arxiv.org/pdf/2010.11273.pdf)|||
|**CME**|Now You See Me (CME): Concept-based Model Extraction|[CIKM 2020 workshop](https://arxiv.org/pdf/2010.13233.pdf)|[sklearn](https://github.com/dmitrykazhdan/CME)||
|**Q FIT**|Q-FIT: The Quantifiable Feature Importance Technique for Explainable Machine Learning|[Arxiv](https://arxiv.org/pdf/2010.13872.pdf)|||
|**Outside black box**|Learning outside the Black-Box: The pursuit of interpretable models|[NeurIPS 2020](https://vanderschaar-lab.com/papers/NeurIPS2020_Symbolic_Pursuit.pdf)|[sklearn](https://github.com/JonathanCrabbe/Symbolic-Pursuit)||
|**Discrete Mask**|Interpreting Image Classifiers by Generating Discrete Masks|[IEEE - PAMI](https://ieeexplore.ieee.org/abstract/document/9214476)|||
|**Contrastive explanations**|Learning Global Transparent Models Consistent with Local Contrastive Explanations|[NeurIPS 2020](https://proceedings.neurips.cc/paper/2020/file/24aef8cb3281a2422a59b51659f1ad2e-Paper.pdf)|||
|**Empirical study of Ideal Explanations**|How Can I Explain This to You? An Empirical Study of Deep Neural Network Explanation Methods|[NeurIPS 2020](https://proceedings.neurips.cc/paper/2020/file/2c29d89cc56cdb191c60db2f0bae796b-Paper.pdf)|[tensorflow 1.15](https://github.com/nesl/Explainability-Study)|[Example based matching library](https://github.com/nesl/ExMatchina)|
|**This Looks Like That + Relevance**|This Looks Like That, Because ... Explaining Prototypes for Interpretable Image Recognition|[Arxiv](https://arxiv.org/pdf/2011.02863.pdf)|[PyTorch](https://github.com/M-Nauta/Explaining_Prototypes)|`must read before relevance`|
|**Concept based posthoc**|ProtoViewer: Visual Interpretation and Diagnostics of Deep Neural Networks with Factorized Prototypes|[Paper](https://ieeevis.b-cdn.net/vis_2020/pdfs/s-short-1226.pdf)||`refer human subject experiments`|
|**Shapley Flow**|Shapley Flow: A Graph-based Approach to Interpreting Model Predictions|[Arxiv](https://arxiv.org/pdf/2010.14592.pdf)|||
|**Attention Vs Saliency and Beyond**|The elephant in the interpretability room: Why use attention as explanation when we have saliency methods?|[Arxiv](https://arxiv.org/pdf/2010.05607.pdf)|||
|**Unification of removal methods**|Feature Removal Is A Unifying Principle For Model Explanation Methods|[NeurIPS 2020 workshop](https://arxiv.org/pdf/2011.03623.pdf)|[PyTorch](https://github.com/iancovert/removal-explanations)|`from the authors of SHAP`[Extended Arxiv version](https://arxiv.org/pdf/2011.14878.pdf)|
|**Robust and Stable Black Box Explanations**|Robust and Stable Black Box Explanations|[ICML 2020](https://arxiv.org/pdf/2011.06169.pdf)||`hima lakkaraju`|
|**Debugging test**|Debugging Tests for Model Explanations|[Arxiv](https://arxiv.org/pdf/2011.05429.pdf)|||
|**AISTATS 2020 submission**|Ensuring Actionable Recourse via Adversarial Training|[Arxiv](https://arxiv.org/pdf/2011.06146.pdf)||`hima lakkaraju`|
|**Layer wise explanation**|Investigating Learning in Deep Neural Networks using Layer-Wise Weight Change|[ResearchGate](https://www.researchgate.net/profile/Ayush_Manish_Agrawal2/publication/345788270_Investigating_Learning_in_Deep_Neural_Networks_using_Layer-Wise_Weight_Change/links/5fadf74d4585150781136ac6/Investigating-Learning-in-Deep-Neural-Networks-using-Layer-Wise-Weight-Change.pdf)|||
|**cites TCAV**|Debiasing Convolutional Neural Networks via Meta Orthogonalization|[Arxiv](https://arxiv.org/pdf/2011.07453.pdf)|Code page not found||
|**Introducing concepts**|SeXAI: Introducing Concepts into Black Boxes for Explainable Artificial Intelligence|[Paper](http://ceur-ws.org/Vol-2742/paper4.pdf)|[Tensorflow 1.4](https://github.com/ivanDonadello/Food-Categories-Classification)||
|**Additive explainers**|Learning simplified functions to understand|[Paper](http://ceur-ws.org/Vol-2742/paper2.pdf)|||
|**BIN**|Born Identity Network: Multi-way Counterfactual Map Generation to Explain a Classifier’s Decision|[Arxiv](https://arxiv.org/pdf/2011.10381.pdf)|[Tensorflow 2.2](https://github.com/ksoh97/BIN)|`counterfactual explanations`|
|**Explantion using Generative models**|Explaining image classifiers by removing input features using generative models|[ACCV 2020](https://openaccess.thecvf.com/content/ACCV2020/papers/Agarwal_Explaining_image_classifiers_by_removing_input_features_using_generative_models_ACCV_2020_paper.pdf)|[Tensorflow 1.12 & Pytorch 1.1](https://github.com/anguyen8/generative-attribution-methods)|Nguyen's paper|
|**Action Recognition Explanation**|Play Fair: Frame Attributions in Video Models|[ACCV 2020](https://openaccess.thecvf.com/content/ACCV2020/papers/Price_Play_Fair_Frame_Contributions_in_Video_Models_ACCV_2020_paper.pdf)|[PyTorch](https://github.com/willprice/play-fair)||
|**Concepts in VQA**|Interpretable Visual Reasoning via Induced Symbolic Space|[Arxiv](https://arxiv.org/pdf/2011.11603.pdf)|[Code not yet updated, just repository created](https://github.com/SHI-Labs/Interpretable-Visual-Reasoning)||
|**Recourses**|Beyond Individualized Recourse: Interpretable and Interactive Summaries of Actionable Recourses|[NeurIPS 2020](https://proceedings.neurips.cc//paper/2020/file/8ee7730e97c67473a424ccfeff49ab20-Paper.pdf)||`hima lakkaraju`|
|**Feature Importance of CNN**|Measuring Feature Importance of Convolutional Neural Networks|[IEEE](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9244164)|||
|**Causal Inference**|Causal inference using deep neural networks|[Arxiv](https://arxiv.org/pdf/2011.12508.pdf)|[Keras](https://github.com/xyvivian/causal_discovery_with_CNN)||
|**Match up**|Match Them Up: Visually Explainable Few-shot Image Classification|[Arxiv](https://arxiv.org/pdf/2011.12527.pdf)|[PyTorch](https://github.com/wbw520/MTUNet)||
|**Right for the Right Concept**|Right for the Right Concept: Revising Neuro-Symbolic Concepts by Interacting with their Explanations|[Arxiv](https://arxiv.org/pdf/2011.12854.pdf)||
|**MALC**|Transparency Promotion with Model-Agnostic Linear Competitors|[ICML 2020](http://proceedings.mlr.press/v119/rafique20a/rafique20a.pdf)|||
|**Shapley Taylor Index**|The Shapley Taylor Interaction Index|[ICML 2020](http://proceedings.mlr.press/v119/sundararajan20a/sundararajan20a.pdf)|||
|**Concept based explanation + user feedback**|Teaching the Machine to Explain Itself using Domain Knowledge|[Openreview](https://openreview.net/pdf/47341095c0d591a6b8c51da0e9dab58076b003c6.pdf)|||
|**Counterfactual produces Adversarial**|Semantics and explanation: why counterfactual explanations produce adversarial examples in deep neural networks|[AIJ submission](https://kieranbrowne.com/publications/semantics_and_explanation.pdf)|||
|**MEME**|MEME: Generating RNN Model Explanations via Model Extraction|[OpenReview](https://openreview.net/pdf/541a2c924c4a5736c60425d247e64ce2c0b3041b.pdf)|[Keras](https://github.com/dmitrykazhdan/MEME-RNN-XAI)|RNN specific LIME, see if any improvisations for MACE comes from here|
|**ProtoPShare**|ProtoPShare: Prototype Sharing for Interpretable Image Classification and Similarity Discovery|[Arxiv](https://arxiv.org/pdf/2011.14340.pdf)||Improved ProtoPNet (This looks like that)|
|**RANCC**|RANCC: Rationalizing Neural Networks via Concept Clustering|[ACL](https://www.aclweb.org/anthology/2020.coling-main.286.pdf)|[Tensorflow 1.x](https://www.aclweb.org/anthology/2020.coling-main.286.pdf)||
|**EAN**|Efficient Attention Network: Accelerate Attention by Searching Where to Plug|[Arxiv](https://arxiv.org/pdf/2011.14058.pdf)|[PyTorch](https://github.com/gbup-group/EAN-efficient-attention-network)||
|**LIME Analysis**|Why model why? Assessing the strengths and limitations of LIME|[Arxiv](https://arxiv.org/pdf/2012.00093.pdf)|[sklearn](https://github.com/jdieber/WhyModelWhy)||
|**Rethink positive aggregation**|Rethinking Positive Aggregation and Propagation of Gradients in Gradient-based Saliency Methods|[ICML 2020 workshop WHI](https://arxiv.org/pdf/2012.00362.pdf)|||
|**Pixel wise interpretation metric**|A Metric to Compare Pixel-wise Interpretation Methods for Neural Networks|[IEEE](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9268152)|||
|**Latent space debiasing**|Fair Attribute Classification through Latent Space De-biasing|[Arxiv](https://arxiv.org/pdf/2012.01469.pdf)|[PyTorch](https://github.com/princetonvisualai/gan-debiasing)||
|**Explanation - Teacher Student**|Evaluating Explanations: How much do explanations from the teacher aid students?|[Arxiv](https://arxiv.org/pdf/2012.00893.pdf)|||
|**Neural Prototype Trees**|Neural Prototype Trees for Interpretable Fine-grained Image Recognition|[Arxiv](https://arxiv.org/pdf/2012.02046.pdf)|[PyTorch](https://github.com/M-Nauta/ProtoTree)|same group of This looks like that + relevance|
|**FixOut**|FixOut: an ensemble approach to fairer models|[Paper](https://hal.archives-ouvertes.fr/hal-03033181/file/_shared__IDA_2021___FixOut__an_ensemble_approach_to_fairer_models%20%281%29.pdf)|||
|**Concepts on Tabular data**|Learning Interpretable Concept-Based Models with Human Feedback|[Arxiv](https://arxiv.org/pdf/2012.02898.pdf)|||
|**BayLIME**|BayLIME: Bayesian Local Interpretable Model-Agnostic Explanations|[Arxiv](https://arxiv.org/pdf/2012.03058.pdf)|[Keras](https://github.com/x-y-zhao/BayLime)||
|**PPI**|Proactive Pseudo-Intervention: Causally Informed Contrastive Learning For Interpretable Vision Models|[Arxiv](https://arxiv.org/pdf/2012.03369.pdf)|Anonymous PyTorch code link given||
|**Generalized distillation**|Understanding Interpretability by generalized distillation in Supervised Classification|[AAAI 2021 submission](https://arxiv.org/pdf/2012.03089.pdf)|Code will be public upon acceptance||
|**RIG**|A Singular Value Perspective on Model Robustness|[Arxiv](https://arxiv.org/pdf/2012.03516.pdf)|||
|**Activation analysis**|Explaining Predictions of Deep Neural Classifier via Activation Analysis|[Arxiv](https://arxiv.org/pdf/2012.02248.pdf)|||
|**Evaluation metrics**|Evaluating Explainable Methods for Predictive Process Analytics: A Functionally-Grounded Approach|[Arxiv](https://arxiv.org/pdf/2012.04218.pdf)|[sklearn](https://github.com/Mythreyi-V/PPA_Evaluation)||
|**Explanations based on train set**|Explainable Artificial Intelligence: How Subsets of the Training Data Affect a Prediction|[Arxiv](https://arxiv.org/pdf/2012.03625.pdf)|||
|**DAX**|DAX: Deep Argumentative eXplanation for Neural Networks|[Arxiv](https://arxiv.org/pdf/2012.05766.pdf)|||
|**Debiased CAM**|Debiased-CAM for bias-agnostic faithful visual explanations of deep convolutional networks|[Arxiv](https://arxiv.org/pdf/2012.05567.pdf)|[Tensorflow 2.1.0](https://github.com/nus-ubicomplab/debiased-cam)|lot of human subject experiments found|
|**Bias via explanation**|Investigating Bias in Image Classification using Model Explanations|[ICML WHI 2020](https://arxiv.org/pdf/2012.05463.pdf)|||
|**Shapley Credit Allocation**|On Shapley Credit Allocation for Interpretability|[Arxiv](https://arxiv.org/pdf/2012.05506.pdf)|||
|**Dependency Decomposition**|Dependency Decomposition and a Reject Option for Explainable Models|[Arxiv](https://arxiv.org/pdf/2012.06523.pdf)|||
|**Interpretation Network**|xRAI: Explainable Representations through AI|[Arxiv](https://arxiv.org/pdf/2012.06006.pdf)|||
|**Explainable by Design**|Evolutionary Generative Contribution Mappings|[IEEE](https://ieeexplore.ieee.org/abstract/document/9283014)||`explainable by design`|
|**Transformer Explanation**|Transformer Interpretability Beyond Attention Visualization|[Arxiv CVPR format](https://arxiv.org/pdf/2012.09838.pdf)|[PyTorch](https://github.com/hila-chefer/Transformer-Explainability)||
|**MANE**|MANE: Model-Agnostic Non-linear Explanations for Deep Learning Model|[IEEE](https://ieeexplore.ieee.org/abstract/document/9283900)||`see how similar to MAIRE`|
|**Why and Why Not Explanations**|On Relating ‘Why?’ and ‘Why Not?’ Explanations|[Arxiv](https://arxiv.org/pdf/2012.11067.pdf)|[sklearn](https://github.com/alexeyignatiev/xdual)|gives theoretical relationship between feature importance and counterfactual techniques|
|**cites ACE**|Analyzing Representations inside Convolutional Neural Networks|[Arxiv](https://arxiv.org/pdf/2012.12516.pdf)|[PyTorch](https://github.com/23Uday/Project1CodeSDM2021)||
|**CEN**|CEN: Concept Evolution Network for Image Classification Tasks|[ACM RICAI 2020](https://dl.acm.org/doi/abs/10.1145/3438872.3439080)||`explainable by design`|
|**Quantitative evaluation metrics**|Quantitative Evaluations on Saliency Methods: An Experimental Study|[Arxiv](https://arxiv.org/pdf/2012.15616.pdf)|||
|**Integrating black box and Interpretable model**|IB-M: A Flexible Framework to Align an Interpretable Model and a Black-box Model|[IEEE - BIBM 2020](https://ieeexplore.ieee.org/abstract/document/9313119)|||
|**X-GradCAM**|Axiom-based Grad-CAM: Towards Accurate Visualization and Explanation of CNNs|[BMVC 2020](https://www.bmvc2020-conference.com/assets/papers/0631.pdf)|||
|**RCAV**|Robust Semantic Interpretability: Revisiting Concept Activation Vectors|[ICML WHI 2020](https://arxiv.org/pdf/2104.02768.pdf)|[PyTorch](https://github.com/keiserlab/rcav)||

### 2021 Papers
| Title | Paper Title                                                                                                 | Source Link                                                                                                                                                                                            | Code                                                                                          | Tags      
| ------------ | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
|**Debiasing concepts** | Debiasing Concept Bottleneck Models with Instrumental Variables|[ICLR 2021 submissions page - Accepted as Poster](https://openreview.net/forum?id=6puUoArESGp)| |`causality`|
|**Prototype Trajectory**|Interpretable Sequence Classification Via Prototype Trajectory|[ICLR 2021 submissions page](https://openreview.net/forum?id=KwgQn_Aws3_)| |`this looks like that styled RNN`|
|**Shapley dependence assumption**|Shapley explainability on the data manifold|[ICLR 2021 submissions page](https://openreview.net/forum?id=OPyWRrcjVQw)|||
|**High dimension Shapley**|Human-interpretable model explainability on high-dimensional data|[ICLR 2021 submissions page](https://openreview.net/forum?id=VlRqY4sV9FO)|||
|**L2x like paper**|A Learning Theoretic Perspective on Local Explainability|[ICLR 2021 submissions page](https://openreview.net/forum?id=7aL-OtQrBWD)|||
|**Evaluation**|Evaluation of Similarity-based Explanations|[ICLR 2021 submissions page](https://openreview.net/forum?id=9uvhpyQwzM_)||`like adebayo paper for this looks like that styled methods`|
|**Model correction**|Defuse: Debugging Classifiers Through Distilling Unrestricted Adversarial Examples|[ICLR 2021 submissions page](https://openreview.net/pdf?id=3R--2TdxMps)|||
|**Subspace explanation**|Constraint-Driven Explanations of Black-Box ML Models|[ICLR 2021 submissions page](https://openreview.net/forum?id=kVZ6WBYazFq)||`to see how close to MUSE by Hima Lakkaraju 2019`|
|**Catastrophic forgetting**|Remembering for the Right Reasons: Explanations Reduce Catastrophic Forgetting|[ICLR 2021 submissions page](https://openreview.net/forum?id=tHgJoMfy6nI)|Code available in their Supplementary zip file||
|**Non trivial counterfactual explanations**|Beyond Trivial Counterfactual Generations with Diverse Valuable Explanations|[ICLR 2021 submissions page](https://openreview.net/forum?id=KWToR-Phbrz)|||
|**Explainable by Design**|Interpretability Through Invertibility: A Deep Convolutional Network With Ideal Counterfactuals And Isosurfaces|[ICLR 2021 submissions page](https://openreview.net/forum?id=8YFhXYe1Ps)|||
|**Gradient attribution**|Rethinking the Role of Gradient-based Attribution Methods for Model Interpretability|[ICLR 2021 submissions page](https://openreview.net/forum?id=dYeAHXnpWJ4)||`looks like extension of Sixt et al paper`|
|**Mask based Explainable by Design**|Investigating and Simplifying Masking-based Saliency Methods for Model Interpretability|[ICLR 2021 submissions page](https://openreview.net/forum?id=eyXknI5scWu)|||
|**NBDT - Explainable by Design**|NBDT: Neural-Backed Decision Tree|[ICLR 2021 submissions page](https://openreview.net/forum?id=mCLVeEpplNE)|||
|**Variational Saliency Maps**|Variational saliency maps for explaining model's behavior|[ICLR 2021 submissions page](https://openreview.net/forum?id=x2ywTOFM4xt)|||
|**Network dissection with coherency or stability metric**|Importance and Coherence: Methods for Evaluating Modularity in Neural Networks|[ICLR 2021 submissions page](https://openreview.net/forum?id=4qgEGwOtxU)|||
|**Modularity**|Are Neural Nets Modular? Inspecting Functional Modularity Through Differentiable Weight Masks|[ICLR 2021 submissions page](https://openreview.net/forum?id=7uVcpu-gMD)|Code made anonymous for review, link given in paper||
|**Explainable by design**|A self-explanatory method for the black problem on discrimination part of CNN|[ICLR 2021 submissions page](https://openreview.net/forum?id=oweBPxtma_i)||`seems concepts of game theory applied`|
|**Attention not Explanation**|Why is Attention Not So Interpretable?|[ICLR 2021 submissions page](https://openreview.net/forum?id=pQhnag-dIt)|||
|**Ablation Saliency**|Ablation Path Saliency|[ICLR 2021 submissions page](https://openreview.net/forum?id=0gfSzsRDZFw)|||
|**Explainable Outlier Detection**|Explainable Deep One-Class Classification|[ICLR 2021 submissions page](https://openreview.net/forum?id=A5VV3UyIQz)|||
|**XAI without approximation**|Explainable AI Wthout Interpretable Model|[Arxiv](https://arxiv.org/pdf/2009.13996.pdf)|||
|**Learning theoretic Local Interpretability**|A LEARNING THEORETIC PERSPECTIVE ON LOCAL EXPLAINABILITY|[Arxiv](https://arxiv.org/pdf/2011.01205.pdf)|||
|**GANMEX**|GANMEX: ONE-VS-ONE ATTRIBUTIONS USING GAN-BASED MODEL EXPLAINABILITY|[Arxiv](https://arxiv.org/pdf/2011.06015.pdf)|||
|**Evaluating Local Explanations**|Evaluating local explanation methods on ground truth|[Artificial Intelligence Journal Elsevier](https://www.sciencedirect.com/science/article/pii/S0004370220301776)|[sklearn](https://github.com/riccotti/SyntheticExplanationGenerator)||
|**Structured Attention Graphs**|Structured Attention Graphs for Understanding Deep Image Classifications|[AAAI 2021](https://arxiv.org/pdf/2011.06733.pdf)||see how close to MACE|
|**Ground truth explanations**|Data Representing Ground-Truth Explanations to Evaluate XAI Methods|[AAAI 2021](https://arxiv.org/pdf/2011.09892.pdf)|[sklearn](https://github.com/Rosinaweber/DataRepresentingGroundTruthExplanations)|trained models available in their github repository|
|**AGF**|Visualization of Supervised and Self-Supervised Neural Networks via Attribution Guided Factorization|[AAAI 2021](https://arxiv.org/pdf/2012.02166.pdf)|[PyTorch](https://github.com/shirgur/AGFVisualization)||
|**RSP**|Interpreting Deep Neural Networks with Relative Sectional Propagation by Analyzing Comparative Gradients and Hostile Activations|[AAAI 2021](https://arxiv.org/pdf/2012.03434.pdf)|||
|**HyDRA**|HYDRA: Hypergradient Data Relevance Analysis for Interpreting Deep Neural Networks|[AAAI 2021](http://www.boyangli.org/paper/Yuanyuan-Chen-AAAI-2021.pdf)|[PyTorch](https://github.com/cyyever/aaai_hydra_8686)||
|**SWAG**|SWAG: Superpixels Weighted by Average Gradients for Explanations of CNNs|[WACV 2021](https://openaccess.thecvf.com/content/WACV2021/papers/Hartley_SWAG_Superpixels_Weighted_by_Average_Gradients_for_Explanations_of_CNNs_WACV_2021_paper.pdf)|||
|**FastIF**|FASTIF: Scalable Influence Functions for Efficient Model Interpretation and Debugging|[Arxiv](https://arxiv.org/pdf/2012.15781.pdf)|[PyTorch](https://github.com/salesforce/fast-influence-functions)||
|**EVET**|EVET: Enhancing Visual Explanations of Deep Neural Networks Using Image Transformations|[WACV 2021](https://openaccess.thecvf.com/content/WACV2021/papers/Oh_EVET_Enhancing_Visual_Explanations_of_Deep_Neural_Networks_Using_Image_WACV_2021_paper.pdf)|||
|**Local Attribution Baselines**|On Baselines for Local Feature Attributions|[AAAI 2021](https://arxiv.org/pdf/2101.00905.pdf)|[PyTorch](https://github.com/ITZuern/On-Baselines-for-Local-Feature-Attributions)||
|**Differentiated Explanations**|Differentiated Explanation of Deep Neural Networks with Skewed Distributions|[IEEE - TPAMI journal](https://ieeexplore.ieee.org/document/9316988)|[PyTorch](https://github.com/fuweijie/DRE)||
|**Human game based survey**|Explainable AI and Adoption of Algorithmic Advisors: an Experimental Study|[Arxiv](https://arxiv.org/pdf/2101.02555.pdf)|||
|**Explainable by design**|Learning Semantically Meaningful Features for Interpretable Classifications|[Arxiv](https://arxiv.org/pdf/2101.03919.pdf)|||
|**Expred**|Explain and Predict, and then Predict again|[ACM WSDM 2021](https://arxiv.org/pdf/2101.04109.pdf)|[PyTorch](https://github.com/JoshuaGhost/expred)||
|**Progressive Interpretation**|An Information-theoretic Progressive Framework for Interpretation|[Arxiv](https://arxiv.org/pdf/2101.02879.pdf)|[PyTorch](https://github.com/hezq06/progressive_interpretation)||
|**UCAM**|Uncertainty Class Activation Map (U-CAM) using Gradient Certainty method|[IEEE - TIP](https://purehost.bath.ac.uk/ws/portalfiles/portal/217611876/UCAM_TIP.pdf)|[Project Page](https://delta-lab-iitk.github.io/U-CAM/)|[PyTorch](https://github.com/DelTA-Lab-IITK/U-CAM)|
|**progressive GAN explainability- smiling dataset- ICLR 2020 group**|Explaining the Black-box Smoothly - A Counterfactual Approach|[Arxiv](https://arxiv.org/pdf/2101.04230.pdf)|||
|**Head pasted in another image - experimented**|WHAT DO DEEP NETS LEARN? CLASS-WISE PATTERNS REVEALED IN THE INPUT SPACE|[Arxiv](https://arxiv.org/pdf/2101.06898.pdf)|||
|**Model correction**|ExplOrs Explanation Oracles and the architecture of explainability|[Paper](https://nbviewer.jupyter.org/github/rpappu/pdf-publications/blob/master/Pappu-ExplOrs-Final-2020.pdf)|||
|**Explanations - Knowledge Representation**|A Basic Framework for Explanations in Argumentation|[IEEE](http://www.florisbex.com/papers/BorgIEEE-explanations.pdf)|||
|**Eigen CAM**|Eigen-CAM: Visual Explanations for Deep Convolutional Neural Networks|[Springer](https://link.springer.com/article/10.1007/s42979-021-00449-3#Sec3)|||
|**Evaluation of Posthoc**|How can I choose an explainer? An Application-grounded Evaluation of Post-hoc Explanations|[ACM](https://arxiv.org/pdf/2101.08758.pdf)|||
|**GLocalX**|GLocalX - From Local to Global Explanations of Black Box AI Models|[Arxiv](https://arxiv.org/pdf/2101.07685.pdf)|||
|**Consistent Interpretations**|Explainable Models with Consistent Interpretations|[AAAI 2021](https://www.csee.umbc.edu/~hpirsiav/papers/gc_aaai21.pdf)|||
|**SIDU**|Introducing and assessing the explainable AI (XAI) method: SIDU|[Arxiv](https://arxiv.org/pdf/2101.10710.pdf)|||
|**cites This looks like that**|Explaining black-box classifiers using post-hoc explanations-by-example: The effect of explanations and error-rates in XAI user studies|[AIJ](https://www.sciencedirect.com/science/article/pii/S0004370221000102)|||
|**i-Algebra**|i-Algebra: Towards Interactive Interpretability of Deep Neural Networks|[AAAI 2021](https://arxiv.org/pdf/2101.09301.pdf)|||
|**Shape texture bias**|SHAPE OR TEXTURE: UNDERSTANDING DISCRIMINATIVE FEATURES IN CNNS|[ICLR 2021](https://arxiv.org/pdf/2101.11604.pdf)|||
|**Class agnostic features**|THE MIND’S EYE: VISUALIZING CLASS-AGNOSTIC FEATURES OF CNNS|[Arxiv](https://arxiv.org/pdf/2101.12447.pdf)|||
|**IBEX**|A Multi-layered Approach for Tailored Black-box Explanations|[Paper](https://hal.inria.fr/hal-03127926/document)|[Code](https://gitlab.inria.fr/chenin/ibex)||
|**Relevant explanations**|Learning Relevant Explanations|[Paper](https://www.researchgate.net/profile/Chris_Russell17/publication/348817770_Learning_Relevant_Explanations/links/6011b0c0299bf1b33e2d33ec/Learning-Relevant-Explanations.pdf)|||
|**Guided Zoom**|Guided Zoom: Zooming into Network Evidence to Refine Fine-grained Model Decisions|[IEEE](https://ieeexplore.ieee.org/abstract/document/9335497)|||
|**XAI survey**|A Survey on Understanding, Visualizations, and Explanation of Deep Neural Networks|[Arxiv](https://arxiv.org/pdf/2102.01792.pdf)|||
|**Pattern theory**|Convolutional Neural Network Interpretability with General Pattern Theory|[Arxiv](https://arxiv.org/pdf/2102.04247.pdf)|[PyTorch](https://github.com/etjoa003/gpt)||
|**Gaussian Process based explanations**|Bandits for Learning to Explain from Explanations|[AAAI 2021](https://arxiv.org/pdf/2102.03815.pdf)|[sklearn](https://github.com/stefanoteso/explearner-simpler)||
|**LIFT CAM**|LIFT-CAM: Towards Better Explanations for Class Activation Mapping|[Arxiv](https://arxiv.org/pdf/2102.05228.pdf)|||
|**ObAIEx**|Right for the Right Reasons: Making Image Classification Intuitively Explainable|[Paper](https://www.researchgate.net/profile/Anna_Nguyen54/publication/343179118_Right_for_the_Right_Reasons_Making_Image_Classification_Intuitively_Explainable/links/601972b0299bf1cc269901c0/Right-for-the-Right-Reasons-Making-Image-Classification-Intuitively-Explainable.pdf)|[tensorflow](https://github.com/annugyen/ObAlEx)||
|**VAE based explainer**|Combining an Autoencoder and a Variational Autoencoder for Explaining the Machine Learning Model Predictions|[IEEE](https://ieeexplore.ieee.org/abstract/document/9347612)|||
|**Segmentation based explanation**|Deep Co-Attention Network for Multi-View Subspace Learning|[Arxiv](https://arxiv.org/pdf/2102.07751.pdf)|[PyTorch](https://github.com/Leo02016/ANTS)||
|**Integrated CAM**|INTEGRATED GRAD-CAM: SENSITIVITY-AWARE VISUAL EXPLANATION OF DEEP CONVOLUTIONAL NETWORKS VIA INTEGRATED GRADIENT-BASED SCORING|[ICASSP 2021](https://arxiv.org/pdf/2102.07805.pdf)|[PyTorch](https://github.com/smstrzd/IntegratedGradCAM)||
|**Human study**|VitrAI - Applying Explainable AI in the Real World|[Arxiv](https://arxiv.org/pdf/2102.06518.pdf)|||
|**Attribution Mask**|Attribution Mask: Filtering Out Irrelevant Features By Recursively Focusing Attention on Inputs of DNNs|[Arxiv](https://arxiv.org/pdf/2102.07332.pdf)|[PyTorch](https://github.com/j-pong/AttentionMask)||
|**LIME faithfulness**|What does LIME really see in images?|[Arxiv](https://arxiv.org/pdf/2102.06307.pdf)|[Tensorflow 1.x](https://github.com/dgarreau/image_lime_theory)||
|**Assess model reliability**|Intuitively Assessing ML Model Reliability through Example-Based Explanations and Editing Model Inputs|[Arxiv](https://arxiv.org/pdf/2102.08540.pdf)|||
|**Perturbation + Gradient unification**|Towards the Unification and Robustness of Perturbation and Gradient Based Explanations|[Arxiv](https://arxiv.org/pdf/2102.10618.pdf)||`hima lakkaraju`|
|**Gradients faithful?**|Do Input Gradients Highlight Discriminative Features?|[Arxiv](https://arxiv.org/pdf/2102.12781.pdf)|[PyTorch](https://github.com/harshays/inputgradients)||
|**Untrustworthy predictions**|Identifying Untrustworthy Predictions in Neural Networks by Geometric Gradient Analysis|[Arxiv](https://arxiv.org/pdf/2102.12196.pdf)|||
|**Explaining misclassification**|Explaining Inaccurate Predictions of Models through k-Nearest Neighbors|[Paper](https://www.scitepress.org/Papers/2021/102579/102579.pdf)||cites Oscar Li AAAI 2018 prototypes paper|
|**Explanations inside predictions**|Have We Learned to Explain?: How Interpretability Methods Can Learn to Encode Predictions in their Interpretations|[AISTATS 2021](https://arxiv.org/pdf/2103.01890.pdf)|||
|**Layerwise interpretation**|LAYER-WISE INTERPRETATION OF DEEP NEURAL NETWORKS USING IDENTITY INITIALIZATION|[Arxiv](https://arxiv.org/pdf/2102.13333.pdf)|||
|**Visualizing Rule Sets**|Visualizing Rule Sets: Exploration and Validation of a Design Space|[Arxiv](https://arxiv.org/pdf/2103.01022.pdf)|[PyTorch](https://github.com/nyuvis/rule_empirical_study)||
|**Human experiments**|Are Explanations Helpful? A Comparative Study of the Effects of Explanations in AI-Assisted Decision-Making|[IUI 2021](https://mingyin.org/paper/IUI-21/iui21.pdf)|||
|**Attention fine-grained classification**|Interpretable Attention Guided Network for Fine-grained Visual Classification|[Arxiv](https://arxiv.org/pdf/2103.04701.pdf)|||
|**Concept construction**|Explaining Classifiers by Constructing Familiar Concepts|[Paper](https://www.researchgate.net/profile/Johannes-Schneider-5/publication/349833788_Explaining_Classifiers_by_Constructing_Familiar_Concepts/links/6043196d92851c077f1c8b42/Explaining-Classifiers-by-Constructing-Familiar-Concepts.pdf)|[PyTorch](https://github.com/JohnTailor/ClaDec)||
|**EbD**|Human-Understandable Decision Making for Visual Recognition|[Arxiv](https://arxiv.org/pdf/2103.03429.pdf)|||
|**Bridging XAI algorithm , Human needs**|Towards Connecting Use Cases and Methods in Interpretable Machine Learning|[Arxiv](https://arxiv.org/pdf/2103.06254.pdf)|||
|**Generative trustworthy classifiers**|Generative Classifiers as a Basis for Trustworthy Image Classification|[Paper](https://www.researchgate.net/profile/Radek-Mackowiak/publication/343333849_Generative_Classifiers_as_a_Basis_for_Trustworthy_Image_Classification/links/604893124585154e8c8b43c7/Generative-Classifiers-as-a-Basis-for-Trustworthy-Image-Classification.pdf)|[Github](https://github.com/VLL-HD/trustworthy_GCs)||
|**Counterfactual explanations**|Generating Interpretable Counterfactual Explanations By Implicit Minimisation of Epistemic and Aleatoric Uncertainties|[AISTATS 2021](https://arxiv.org/pdf/2103.08951.pdf)|[PyTorch](https://github.com/oscarkey/explanations-by-minimizing-uncertainty)||
|**Role categorization of CNN units**|Quantitative Effectiveness Assessment and Role Categorization of Individual Units in Convolutional Neural Networks|[ICML 2021](https://arxiv.org/pdf/2103.09716.pdf)|||
|**Non-trivial counterfactual explanations**|Beyond Trivial Counterfactual Explanations with Diverse Valuable Explanations|[Arxiv](https://arxiv.org/pdf/2103.10226.pdf)|||
|**NP-ProtoPNet**|These do not Look Like Those: An Interpretable Deep Learning Model for Image Recognition|[IEEE](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9373404)|||
|**Correcting neural networks based on explanations**|Refining Neural Networks with Compositional Explanations|[Arxiv](https://arxiv.org/pdf/2103.10415.pdf)|Code link given in paper, but page not found||
|**Contrastive reasoning**|Contrastive Reasoning in Neural Networks|[Arxiv](https://arxiv.org/pdf/2103.12329.pdf)|||
|**Concept based**|Intersection Regularization for Extracting Semantic Attributes|[Arxiv](https://arxiv.org/pdf/2103.11888.pdf)|||
|**Boundary explanations**|Boundary Attributions Provide Normal (Vector) Explanations|[Arxiv](https://arxiv.org/pdf/2103.11257.pdf)|[PyTorch](https://github.com/zifanw/boundary)||
|**Generative Counterfactuals**|ECINN: Efficient Counterfactuals from Invertible Neural Networks|[Arxiv](https://arxiv.org/pdf/2103.13701.pdf)|||
|**ICE**|Invertible Concept-based Explanations for CNN Models with Non-negative Concept Activation Vectors|[AAAI 2021](https://www.aaai.org/AAAI21Papers/AAAI-10193.ZhangR.pdf)|||
|**Group CAM**|Group-CAM: Group Score-Weighted Visual Explanations for Deep Convolutional Networks|[Arxiv](https://arxiv.org/pdf/2103.13859.pdf)|[PyTorch](https://github.com/wofmanaf/Group-CAM)||
|**HMM interpretability**|Towards interpretability of Mixtures of Hidden Markov Models|[AAAI 2021](https://arxiv.org/pdf/2103.12576.pdf)|[sklearn](https://github.com/negar7918/iMHMM)||
|**Empirical Explainers**|Efficient Explanations from Empirical Explainers|[Arxiv](https://arxiv.org/pdf/2103.15429.pdf)|[PyTorch](https://github.com/dfki-nlp/emp-exp)||
|**FixNorm**|FIXNORM: DISSECTING WEIGHT DECAY FOR TRAINING DEEP NEURAL NETWORKS|[Arxiv](https://arxiv.org/pdf/2103.15345.pdf)|||
|**CoDA-Net**|Convolutional Dynamic Alignment Networks for Interpretable Classifications|[CVPR 2021](https://arxiv.org/pdf/2104.00032.pdf)|Code link given in paper. Repository not yet created||
|**Like Dr. Chandru sir's (IITPKD) XAI work**|Neural Response Interpretation through the Lens of Critical Pathways|[Arxiv](https://arxiv.org/pdf/2103.16886.pdf)|[PyTorch- Pathway Grad](https://github.com/CAMP-eXplain-AI/PathwayGrad)[PyTorch - ROAR](https://github.com/CAMP-eXplain-AI/RoarTorch/tree/master/src/roar)||
|**Inaugment**|InAugment: Improving Classifiers via Internal Augmentation|[Arxiv](https://arxiv.org/pdf/2104.03843.pdf)|[Code yet to be updated](https://github.com/moabarar/inaugment)||
|**Gradual Grad CAM**|Enhancing Deep Neural Network Saliency Visualizations with Gradual Extrapolation|[Arxiv](https://arxiv.org/pdf/2104.04945.pdf)|
[PyTorch](https://github.com/szandala/gradual-extrapolation)|| 
