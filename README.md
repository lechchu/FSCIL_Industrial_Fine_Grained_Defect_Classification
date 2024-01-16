
### 少樣本增量學習應用於工業細粒度缺陷分類
### Few-Shot Class Incremental Learning for Industrial Fine-Grained Defect Classification
****
### 摘要
在生產線上，產品的手動視覺檢測是一個耗時且容易出錯的過程，導致成本增加且結果不一致。為了應對這些挑戰，使用人工智慧模型進行自動化缺陷分類具有顯著的優勢。然而，生產線上的缺陷分類任務面臨著多個挑戰，包括數量有限的標記資料、缺陷類別差異小之細粒度資料集以及不斷發現新的缺陷類別。同時，儘管目前已有部分方法致力於解決少量資料以及不斷出現的新類別，然而多數方法忽略掉新類別部分的準確率，這導致平均準確率上表現優良，實際上卻是透過優異的舊類別與表現不盡理想的新類別平均下的狀況。

在這項研究中，我們旨在開發一個專門針對生產線缺陷分類的人工智慧模型，並具備克服少樣本數據集、細粒度數據集和增量學習的挑戰。我們對此採用了少樣本增量學習方法，結合少樣本學習和增量學習技術，以應對不斷變化的缺陷分類需求。
我們的研究透過解決新的缺陷類別的分類能力較低以及整合細粒度數據集挑戰，提升了現有架構的性能。我們提出了新的技術，以增強少樣本增量學習架構在少樣本和細粒度缺陷分類方面的表現，並旨在實現對新缺陷類別的分類的平均準確率從現有的15\%提升至超過60\%，從而提高生產線上的缺陷檢測效率和準確性。

透過在現實生產線場景中推進缺陷分類技術，我們的研究對於改善質量控制流程、降低檢測成本以及提高整體生產力在製造業中具有實際意義。這項研究的成果為克服標記資料的有限性、新缺陷類別的出現以及細粒度區分所面臨的挑戰提供了有價值的見解，最終將造福整個製造業。

### Abstract
The manual visual inspection of products on production lines is a labor-intensive and error-prone process, resulting in increased costs and inconsistencies. To address these challenges, the utilization of AI models for automated defect classification presents substantial benefits. However, the defect classification task within production lines confronts multiple obstacles, including the scarcity of labeled data, the existence of fine-grained datasets, and the ongoing emergence of new defect categories.

While a few-shot class incremental approach achieves commendable performance, its efficacy is rooted in strong performance on base data, yet it exhibits diminished performance on new data. This disparity highlights the need for novel solutions to address these limitations and ensure robust performance across different scenarios.

In this research, we aim to develop an AI model specifically designed for defect classification in the production line, overcoming the challenges of few-shot datasets, fine-grained datasets, and incremental learning. We adopt the few-shot class incremental learning (FSCIL) approach, which combines few-shot learning and incremental learning techniques to handle evolving defect classification requirements.

Our research contributes to improving the existing FSCIL framework by addressing the lower classification ability for new defect categories and integrating fine-grained dataset challenges. We propose novel techniques to enhance the FSCIL framework's performance in handling few-shot and fine-grained defect classification in an incremental learning setting. The goal is to achieve an average accuracy of over 60\% for the classification of new defect classes, thereby enhancing defect inspection efficiency and accuracy in the production line.

By advancing defect classification techniques in real-world production line scenarios, our study has practical implications for improving quality control processes, reducing inspection costs, and enhancing overall productivity in manufacturing industries. The outcomes of this research provide valuable insights for overcoming the challenges associated with limited labeled data, new defect categories, and fine-grained distinctions, ultimately benefiting whole manufacturing industry.
