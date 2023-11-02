- Name: Hanyu Li

- Title: Characterizing Parametric and Convergence Stability in Nonconvex Nonsmooth Optimization

- Abstract: 
	In this talk, we introduce two notions of stability in minimizing continuous functions: parametric stability, which looks at how the local optima change in response to changes in the input parameters; and convergence stability, which looks at whether an iterative method started near a local optimum should be expected to stay near and eventually converge to this optimum.  We give several rather tight conditions of these two stability concepts for a wide range of functions and optimization algorithms considered in nonconvex nonsmooth optimization.
	We further present an application in optimization of deep neural networks. We prove that for an overparameterized smooth neural network trained with gradient descent and quadratic loss, all zero-loss points are not convergence-stable. This indicates that a slight difference in initialization (even sufficiently close to a global minimum point) can lead to qualitatively different trained parameters.
	
	This talk is based on joint work with Xiaotie Deng and Ningyuan Li.
	
 - Bio:
   Hanyu Li is an incoming PhD candidate at Peking University. He received his bachelor's degree in computer science from Peking University. His current works focus on computational game theory and continuous optimization.



 - Name: Xingjian Li
 - Title: On the Feasibility of Unclonable Encryption, and More
 - Abstract:
   Unclonable encryption, first introduced by Broadbent and Lord (TQC'20), is a one-time encryption scheme with the following security guarantee: any non-local adversary (A, B, C) cannot simultaneously distinguish encryptions of two equal length messages. This notion is termed as unclonable indistinguishability. Prior works focused on achieving a weaker notion of unclonable encryption, where we required that any non-local adversary (A, B, C) cannot simultaneously recover the entire message m. Seemingly innocuous, understanding the feasibility of encryption schemes satisfying unclonable indistinguishability (even for 1-bit messages) has remained elusive.
   We make progress towards establishing the feasibility of unclonable encryption. 
   - We show that encryption schemes satisfying unclonable indistinguishability exist unconditionally in the quantum random oracle model. 
   - Towards understanding the necessity of oracles, we present a negative result stipulating that a large class of encryption schemes cannot satisfy unclonable indistinguishability. 
   - Finally, we also establish the feasibility of another closely related primitive: copy-protection for single-bit output point functions. Prior works only established the feasibility of copy-protection for multi-bit output  point functions or they achieved constant security error for single-bit output point functions. 
 - Bio:
   Xingjian Li is a first year PhD candidate at Tsinghua University. He received his Bachelor's Degree in Computer Science from Institute for Interdisciplinary Information Sciences, Tsinghua University. He has broad interest on topics about quantum computing, especially in quantum complexity and quantum cryptography.



- Name: Hongxun Wu

- Title：Element Distinctness, Birthday Paradox, and 1-out Pseudorandom Graphs

- Abstract：

  Element Distinctness is a fundamental computational problem: given an array of n input integers with O(log n) bit-length, decide whether or not all elements are pairwise distinct. In comparision model, the optimal time space tradeoff was resolved in the 80s. Specifically, with only O(polylog n) bits of memory, Õ(n^2) time pairwise comparision is necessary. 

  In RAM model, surprisingly, Beame, Clifford, and Machmouchi gave a Õ(n^{1.5})-time randomized algorithm for Element Distinctness using only O(log n) bits of working space. However, their algorithm assumes a random oracle (in particular, read-only random access to polynomially many random bits), and it was asked as an open question whether this assumption can be removed.

  In this talk, we constructed a pseudorandom hash family based on iterative restrictions, which can replace this random oracle. This answers the open quesstion and makes the result by Beame et al. unconditional. This is joint work with Lijie Chen, Ce Jin, and Ryan Williams.

- Bio：

  Hongxun Wu recently recieved Bachelor's degree from Yao Class, Tsinghua. He is going to pursue PhD at UC Berkeley. His research interest is mainly in algorithm design and pseudorandomness. 



- Name: Baihe Huang

- Title: Towards Data Efficiency in Offline Reinforcement Learning

- Abstract: 

  Exploiting historical data to improve the decision-making strategies of intelligent systems, known as Offline reinforcement learning (RL), has offered a promising prospect for applying RL to many real-world problems where online access to the environment may be subject to high costs or risks. At the heart of such a method is how an agent should learn from fewer samples in order to maximize the expected outcomes while operating in a vast, dynamic environment. However, sample-efficiency guarantees for offline RL often rely on strong assumptions about the function approximation and the coverage of offline data. In this talk, I will discuss a simple algorithm based on the primal-dual formulation of Markov Decision Processes that enjoys polynomial sample complexity under relaxed conditions. The presented algorithm will be complemented by extensions and analyses that provide a deeper understanding of primal-dual algorithms in offline RL.

- Bio: 

  Baihe Huang is a fourth-year undergraduate student at Peking University. He will join UC Berkeley as a CS Ph.D. student in 2022 fall.



- Name: Xinyan Hu

- Title: Nash Convergence of Mean-Based Learning Algorithms in First Price Auctions

- Abstract: 

  Understanding the convergence properties of learning dynamics in repeated auctions is a timely and important question in the area of learning in auctions, with numerous applications in, e.g., online advertising markets. This work focuses on repeated first price auctions where bidders with fixed values for the item learn to bid using mean-based algorithms -- a large class of online learning algorithms that include popular no-regret algorithms such as Multiplicative Weights Update and Follow the Perturbed Leader. We completely characterize the learning dynamics of mean-based algorithms, in terms of convergence to a Nash equilibrium of the auction, in two senses: (1) time-average: the fraction of rounds where bidders play a Nash equilibrium approaches 1 in the limit; (2)last-iterate: the mixed strategy profile of bidders approaches a Nash equilibrium in the limit. Specifically, the results depend on the number of bidders with the highest value: 

  - If the number is at least three, the bidding dynamics almost surely converges to a Nash equilibrium of the auction, both in time-average and in last-iterate. 
  - If the number is two, the bidding dynamics almost surely converges to a Nash equilibrium in time-average but not necessarily in last-iterate. 
  - If the number is one, the bidding dynamics may not converge to a Nash equilibrium in time-average nor in last-iterate. 
  Our discovery opens up new possibilities in the study of convergence dynamics of learning algorithms.

- Bio:

  Xinyan Hu is a coming Ph.D. student in computer science at UC Berkeley in 2022 Fall. She received her bachelor degree in computer science from Peking University in 2022. Her research interest lies in the interface of machine learning and economics.

  

- Name: Shanda Li

- Title: Your Transformer May Not be as Powerful as You Expect

- Abstract:

  Relative Positional Encoding (RPE), which encodes the relative distance between any pair of tokens, is one of the most successful modifications to the original Transformer. As far as we know, theoretical understanding of the RPE-based Transformers is largely unexplored. In this work, we mathematically analyze the power of RPE-based Transformers regarding whether the model is capable of approximating any continuous sequence-to-sequence functions. One may naturally assume the answer is in the affirmative -- RPE-based Transformers are universal function approximators. However, we present a negative result by showing there exist continuous sequence-to-sequence functions that RPE-based Transformers cannot approximate no matter how deep and wide the neural network is. One key reason lies in that most RPEs are placed in the softmax attention that always generates a right stochastic matrix. This restricts the network from capturing positional information in the RPEs and limits its capacity. 

  To overcome the problem and make the model more powerful, we first present sufficient conditions for RPE-based Transformers to achieve universal function approximation. With the theoretical guidance, we develop a novel attention module, called Universal RPE-based (URPE) Attention, which satisfies the conditions. Therefore, the corresponding URPE-based Transformers become universal function approximators. Extensive experiments covering typical architectures and tasks demonstrate that our model is parameter-efficient and can achieve superior performance to strong baselines in a wide range of applications.

  This talk is based on joint work with Shengjie Luo, Shuxin Zheng, Tie-Yan Liu, Liwei Wang, and Di He.
- Bio:
  Shanda Li is an incoming PhD at Machine Learning Department, School of Computer Science, Carnegie Mellon University. He received his bachelor's degree from Peking University, majoring in computer science and minoring in mathematics.
