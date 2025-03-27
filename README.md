# My Personal Website

Welcome to my personal website! Use the links below to navigate quickly:

- [About Me](#about-me)
- [Research](#research)
- [Projects](#projects)
- [Industry Intern](#industry-intern)

---

## About Me

I am currently pursuing a **B.S. in Mathematics & Statistics** at the University of Michigan. My research interest lies in NLP, LLMs, and machine learning, with a particular focus on pre-training LLMs and analyzing advanced self-improving transformer frameworks.

### Education

**University of Michigan, Ann Arbor**  
*Expected Dec 2025*

- **Program**: B.S in Statistics & Mathematics  
- **Core Coursework**: Machine Learning, Optimization, Experimental Design, Deep Learning, Real Analysis, Numerical Method, Linear Algebra, C/C++ Programming, Data Structure, Probability Theory.  
- **GPA**: Mathematics(3.745), Statistics(3.920)

---

## Research

**Research Assistant, University of Michigan**  
*Dec. 2024 - Present*

- Designed and trained a decoder-only transformer from scratch in PyTorch, adapting architectures from nanoGPT and Llama-3, achieving 99% accuracy on 1-10-digit reverse addition and string copying.
- Built a self-improvement pipeline generating 50K high-confidence examples per round using unsupervised length filtering and 5-model majority voting, achieving 94% verification accuracy via confusion matrix analysis.
- Scaled task difficulty from 10-digit to 20-digit operations over 10 self-improvement rounds, retaining 99% accuracy on extended tasks with no performance degradation.
- Optimized model architecture via A/B testing (tracked in Weights & Biases), identifying reverse addition formatting for a 30% reduction in next-token prediction error. Selected NoPE over rotary embeddings for optimal memory-accuracy tradeoffs.
- Gratefully advised by Professor [Yixin Wang](https://yixinwang.github.io/) and [Zhiwei Xu](https://zhiweixx.github.io/)

---

## Projects

### Netflix Prize
- Processed 180,000 recent [ratings](https://drive.google.com/drive/folders/1XHeYTwgp9M4-V3shLd2loemdaoQGhi6d) with time-based splitting.
- Implemented neighborhood-based methods (NB-CORR and NB-LS) from scratch to compute similarity scores and leverage user-item correlations, achieving a test RMSE of 0.9751 and 0.9583 respectively.
- Developed an ensemble model using linear regression to combine predictions from matrix factorization and neighborhood-based models, boosting overall accuracy. Achieved a test RMSE of 0.9262.
- Performed EDA and visualized the relationships between hyperparameters and RMSE to evaluate model performance.

View project on [GitHub](https://github.com/4everXYZ/netflix-project.git) and download [paper](https://drive.google.com/file/d/15OHwAAsIauEN8Wv1goT5aCmYXwBS2_5T/view?usp=drive_link)

---

### Recipe Ratings Prediction
- Cleaned datasets from [Food.com](https://www.food.com/) and performed feature engineering (polynomial transformations, one-hot encoding, scaling).
- Implemented Ridge Regression with fine-tuned hyperparameters using GridSearchCV, achieving a test RMSE of 0.4906.
- Developed a Jekyll-based website with integrated Plotly graphs and tables to enhance data visualization and user engagement.

View [website](https://fangyua666.github.io/recipe-rating-prediction/)

---

### Deep Facial Expression Recognition
- Processed an imbalanced dataset of 35,352 images, including manual correction of mislabeled samples to improve accuracy.
- Leveraged ResNet34 architecture with transfer learning, increasing accuracy from 64% to 70%.
- Fine-tuned model by adjusting learning rate and applying class balancing techniques, reducing error by 6%.

Download [paper](https://drive.google.com/file/d/1MI1U6uFKZotpC2txwIrAS9-EJPCK_Ppl/view?usp=sharing)

---

## Industry Intern

**Data Analyst - Business Intelligence, AstraZeneca**  
*Jun. 2023 - Aug. 2023*

- Analyzed product performance using SQL and Excel, handling data from 80K+ local system entries.
- Developed and monitored interactive Power BI dashboards to track KPIs.
- Coordinated with Deloitte's supplier team daily, identifying bugs and improving accuracy by 25%.
- Collaborated with BISO team in publishing sales reports for June, July, and August.

---

## Technical Skills

- **Languages**: Python, R, C/C++, SQL  
- **Libraries**: pandas, NumPy, Scikit-learn, PyTorch, TensorFlow  
- **Developer Tools**: Tableau, Git, Jekyll  
- **Communication Skills**: English (professional), Mandarin (native)

---

> **Tip**: You can further customize this README by adding more details, relevant links, or using Markdown badges for your skills/tools.
