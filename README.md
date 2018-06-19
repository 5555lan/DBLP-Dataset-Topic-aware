# DBLP-Dataset-Topic-aware

Xiangyu KE, Nanyang Technological University

Contact: xiangyu001@e.ntu.edu.sg OR xiangyke@gmail.com

All Rights Reserved

----------------------------------------------------------------------------------------------------------------------------------------

Dataset Description:

This dataset is based on the well-known DPLP collaboration data (March 31, 2017). Each node is an author and edges denote their co-author relations. The tags (topics) are extracted from all paper titles, e.g., database system, neural network, FPGA, etc, based on both their frequency and how well they can represent various sub-areas of computer science. In total we select 230 tags. Only the authors who have at least one paper containing at least one of these tags will present in this dataset. Finally we have 704266 nodes and 4727290 edges. The probability of tag c on edge (u,v) was given by P((u,v)|c)=1-e^(-t/a), where t is the frequency of tag c to appear in the titles of all papers collaborated by author u and v and a is a constant (set as 5 here).

----------------------------------------------------------------------------------------------------------------------------------------

Format:

(1) DBLP.txt

Author1 Author2 Probability1 Tag1 Probability2 Tag2 ... ProbabilityN TagN

(2) AuthorHash.txt

Index : Author Name

(3) TopicHash.txt

Index : Topic(s)

----------------------------------------------------------------------------------------------------------------------------------------

We encourage you to cite our works if you have used our datasets.

(1) Xiangyu Ke, Arijit Khan, and Gao Cong. Finding Seeds and Relevant Tags Jointly: For Targeted Influence Maximization in Social Networks. In SIGMOD 2018.

BibTeX
@article{KKC18,   
  title={Finding Seeds and Relevant Tags Jointly: For Targeted Influence Maximization in Social Networks},   
  author={Ke, Xiangyu and Khan, Arijit and Cong, Gao},  
  booktitle={Proceedings of the 2018 International Conference on Management of Data},  
  series={SIGMOD'18},  
  year={2018},   
  pages={1097-1111},  
  publisher={ACM}
}


(2) Arijit Khan, Francesco Bonchi, Francesco Gullo, and Andreas Nufer. Conditional Reliability in Uncertain Graphs. In TKDE 2018.

BibTeX
@article{KBGN18,   
  title={Conditional Reliability in Uncertain Graphs},   
  author={Khan, Arijit and Bonchi, Francesco and Gullo, Francesco and Nufer, Andreas},
  journal={IEEE Transactions on Knowledge and Data Engineering (TKDE)},  
  year={2018},   
  publisher={IEEE}
}
