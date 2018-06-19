# DBLP-Dataset-Topic-aware

Xiangyu KE, Nanyang Technological University

Contact: xiangyu001@e.ntu.edu.sg OR xiangyke@gmail.com

All Rights Reserved

-------------------------------------------------------------------------------------------------------------------------------------------

Dataset Description:
This dataset is based on the well-known DPLP collaboration data (March 31, 2017). Each node is an author and edges denote their co-author relations. The tags (topics) are extracted from all paper titles, e.g., database system, neural network, FPGA, etc, based on both their frequency and how well they can represent various sub-areas of computer science. In total we select 230 tags. Only the authors who have at least one paper containing at least one of these tags will present in this dataset. Finally we have 704266 nodes and 4727290 edges. The probability of tag c on edge (u,v) was given by P((u,v)|c)=1-e^(-t/a), where t is the frequency of tag c to appear in the titles of all papers collaborated by author u and v and a is a constant (set as 5 here).

-------------------------------------------------------------------------------------------------------------------------------------------

Format:
(1)	DBLP.txt
	Author1 Author2 Probability1 Tag1 Probability2 Tag2 ... ProbabilityN TagN
(2) AuthorHash.txt
	Index : Author Name
(3) TopicHash.txt
	Index : Topic(s)

