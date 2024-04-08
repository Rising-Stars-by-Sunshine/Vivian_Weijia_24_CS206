
## Question One

In the realm of experimental economics, oTree has served as a valuable tool for conducting strategic interaction studies, yet certain pain points persist, hindering the seamless execution of behavioral game theory research. Through a thorough analysis of my experiences with oTree, supplemented by literature reviews and class discussions, I have identified critical areas for improvement and proposed a software solution that not only addresses these limitations but also enhances strategic interaction studies in experimental economics.

Firstly, a notable pain point in using oTree lies in the management of game details, particularly evident in scenarios such as the trust game. In my experience, discrepancies in instruction details arose when editing the game parameters, leading to confusion among participants (fig.1). Since the oTree tutorial video (2021) states that the oTree consists of HTML, CSS, and Python, to mitigate this issue, the proposed software solution should feature user-friendly interfaces with aligned changes across all relevant instructions by adjusting the CSS part or editing HTML part. By synchronizing changes in game parameters to corresponding instructions, the likelihood of contradictory information decreases, thus enhancing the overall user experience and data integrity.

Secondly, to effectively test users' rationality across different game sequences, the software should facilitate enhanced connections between games. In my experiments, altering the order of games elicited varying participant responses, underscoring the importance of understanding the impact of game sequencing on decision-making behavior. The proposed solution should incorporate visual cues or reminders at the onset of each game, indicating the treatment condition and prompting participants to recall previous interactions. By fostering cognitive continuity between games, researchers can elicit more consistent and insightful responses, thus enriching the validity of experimental outcomes.

Thirdly, to deepen participant engagement and facilitate comprehensive data collection, the software should include post-game explanations and feedback mechanisms. Incorporating brief explanations of game logic at the experiment's conclusion can enhance participants' understanding of the study's objectives and foster reflective thinking. Additionally, providing space for participants to share their feelings or insights can yield qualitative data that complements quantitative analyses, offering valuable insights into decision-making processes and behavioral dynamics.

The proposed software solution aims to outperform oTree in three key aspects: enhancing the user experience through synchronized instructions, fostering cognitive continuity between games, and facilitating comprehensive data collection. These advancements are crucial for advancing experimental economics research by promoting methodological rigor, improving participant engagement, and generating nuanced insights into strategic decision-making behaviors.

In conclusion, by addressing the identified pain points and integrating innovative features, the proposed software solution holds the potential to significantly enhance strategic interaction studies in experimental economics. By leveraging technology to streamline experimental procedures and enhance participant experiences, researchers can advance our understanding of economic behavior and contribute to the development of robust theoretical frameworks and empirical findings in the field (fig.2).

<img width="468" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/Vivian_Weijia_24_CS206/assets/141093064/15253d07-f78e-45a6-a841-de2ea1584ef5">

Fig. 1. The user interface of Otree trust game where exists contradictory instructions.

<img width="298" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/Vivian_Weijia_24_CS206/assets/141093064/61d91e1d-ef05-4972-b78c-6f7bf808bde6">

Fig. 2. The mind map for the proposed Otree improvements.

## Question Two

Current multi-agent reinforcement learning (MARL) frameworks face limitations concerning environment constraints and agent algorithm customizations, which can hinder the effective development of MARL agents.

Illustrating these limitations with the Trust Game, we encounter challenges in defining states, actions, and rewards. In the Trust Game, two players decide whether to trust each other or not, affecting their payoffs. However, existing MARL frameworks struggle to represent the complex social dynamics inherent in trust-based interactions accurately due to the inherent complexity of AI models and the lack of transparency in their decision-making processes (Zhang et al., 2023).

The development process of a MARL agent for the Trust Game involves defining states based on the players' past interactions and current beliefs about their counterpart's trustworthiness. However, existing MARL frameworks may struggle to capture the nuances of trust dynamics, leading to oversimplified representations of the game's complexity. Environment constraints, such as limited communication or observation capabilities, further impede the agent's ability to learn optimal strategies in trust-based interactions.

Addressing these limitations may apply explainable AI (XAI) in scenarios like the Trust Game. We might use Large Language Models (LLMs) to generate natural language explanations for agent behavior in the Trust Game. By leveraging LLMs, AI agents can provide textual explanations that offer insights into the reasoning behind their decisions and actions (Zhang et al., 2023). Additionally, we may integrate Theory of Mind (ToM) into AI agents to address the difficulty of collaboration and communication with each other. ToM allows agents to attribute mental states to themselves and others, enabling them to understand and predict behavior based on these attributions (Li et al., 2023).

Compared with my personal experience, I ran the 2048 game in PettingZoo API, a MARL, I encountered difficulty of understanding the “reward” state and “action” state. Therefore, if XAI can explain the behaviors of AI agent in those two states, it is much easier to comprehend the logic of the game.

<img width="214" alt="image" src="https://github.com/Rising-Stars-by-Sunshine/Vivian_Weijia_24_CS206/assets/141093064/b450e61b-f6c7-44d2-95ab-44e8af2aedf2">

Fig. 3. Using PettingZoo API (MARL) to run 2048 game. 

<img width="859" alt="Screen Shot 2024-04-09 at 01 13 43" src="https://github.com/Rising-Stars-by-Sunshine/Vivian_Weijia_24_CS206/assets/141093064/2856211a-a2ac-4e48-9fe6-e74736cf4d19">

Fig. 4. The mind map of the answer to question two.

## Question Three

1. Summary of the Paper
   
The core research questions revolve around developing mechanisms that encourage clients to truthfully report their data updates without biasing the federated learning process.

The paper proposes methodologies to achieve this objective by introducing randomized client participation and designing appropriate incentive mechanisms.

The paper outlines application scenarios in which federated learning is applied, such as healthcare, finance, and smart cities, highlighting the potential real-world impact of the proposed solutions.

2. Critique of the Research Question
   
While the paper effectively addresses the challenges of unbiased federated learning: Challenge 1 involves massive and unstable client populations, making it impossible for all clients to participate fully in every training round. Challenge 2 relates to unbalanced and non-i.i.d. data, where deterministic subsets of clients can cause severe bias and hinder convergence when training on the full client set. Challenge 3 revolves around the efficient evaluation of client contributions for payment design, considering the dynamic and distributed nature of FL systems. Lastly, Challenge 4 explores the impact of clients' intrinsic value on payment design, highlighting the need to incentivize client participation while ensuring fairness and model quality, there may be additional research questions that could enhance its relevance and impact.

For instance, exploring the scalability of incentive mechanisms across different scales of federated learning systems or investigating the impact of heterogeneous client populations on incentive design could offer valuable insights into the practical deployment of federated learning in diverse contexts. Additionally, it might clearly state that there still exist the security issues in the proposed methods but the future research may investigate into it.

3. Critique of the Methodology
   
The paper's methodology assumes rational behavior from participating clients and does not fully account for potential deviations from rationality or strategic interactions. To address this, the methodology could incorporate behavioral economics principles to model clients' bounded rationality more accurately. Behavioral economics principles such as loss aversion, social preferences, prospect theory, and mental accounting can offer insights into clients' decision-making behavior in federated learning systems. These principles can inform the design of incentive mechanisms by addressing concerns related to risk perception, fairness, framing effects, and subjective valuation of data contributions. Integrating these principles into the methodology can enhance the accuracy and effectiveness of incentive designs, ultimately promoting cooperation and trust among participating clients in federated learning environments.
Additionally, exploring alternative incentive mechanisms beyond randomized participation, such as mechanism design inspired by cooperative game theory or multi-agent reinforcement learning, could provide a more robust framework for incentivizing truthful reporting in federated learning.

5. Critique of the Application Scenario
   
The application scenarios presented in the paper demonstrate the relevance of federated learning (FL) in various domains. However, with the rapid advancement in technology, there exist more modern and advanced scenarios where FL can be applied to address emerging challenges and opportunities.

One such scenario involves exploring applications of FL in blockchain-based systems for decentralized data sharing. Blockchain technology offers a decentralized and immutable ledger for securely recording and sharing data across distributed networks. This approach enhances privacy and bias concerns by providing a transparent and tamper-proof framework for data sharing and model aggregation.

Another promising application scenario is leveraging generative AI techniques for privacy-preserving model training. Generative adversarial networks (GANs) and other generative models can generate synthetic data samples that mimic real data distributions while preserving privacy-sensitive information. This approach mitigates privacy concerns and reduces the risk of bias in model training by ensuring that sensitive information remains confidential while still enabling effective model learning and inference.

5. Beyond Computer Science and Economics
   
Incorporating bounded rationality considerations into both human and AI agents within the federated learning framework could significantly impact the study's findings. For instance, introducing AI agents with specific psychological heuristics or cognitive biases, such as loss aversion or overconfidence, could affect their decision-making and alter the effectiveness of incentive mechanisms. Furthermore, exploring the interaction between human participants and AI agents, such as ChatGPT, within federated learning environments could reveal insights into the dynamics of hybrid human-AI systems and inform the design of more robust and adaptive incentive mechanisms.

6. The mini-experiment with a Art and Humanity student
   
In the mini-experiment conducted with a student from the Arts and Humanities field, their perspective on the paper's scenario of resetting prices based on data was insightful. The student expressed skepticism towards the approach of initially providing a price and then adjusting it based on collected data. They interpreted this as a lack of trustworthiness on the part of the company implementing the pricing strategy.

This perspective sheds light on potential real-world implications of the paper's proposed incentive mechanisms for unbiased federated learning. If companies were to adopt such mechanisms, they might face challenges in gaining trust and acceptance from consumers, especially those who value transparency and fairness in pricing practices. The skepticism raised by the student suggests that the paper's conclusions may need to consider the broader socio-economic context and consumer perceptions surrounding data-driven pricing strategies.

<img width="993" alt="Screen Shot 2024-04-09 at 01 17 06" src="https://github.com/Rising-Stars-by-Sunshine/Vivian_Weijia_24_CS206/assets/141093064/8802c170-dfbb-43aa-a64e-6b221bf4d0c2">

Fig. 5. The mind map of the answer to question three. 

## Bibliography

Li, Huao, Yu Quan Chong, Simon Stepputtis, Joseph Campbell, Dana Hughes, Michael Lewis, and Katia Sycara. 2023. “Theory of Mind for Multi-Agent Collaboration via Large Language Models.” https://aclanthology.org/2023.emnlp-main.13.pdf.

Luo, Bing, Yutong Feng, Shiqiang Wang, Jianwei Huang, and Leandros Tassiulas. "Incentive Mechanism Design for Unbiased Federated Learning with Randomized Client Participation." In 2023 IEEE 43rd International Conference on Distributed Computing Systems (ICDCS), pp. 545-555. IEEE, 2023.

Tutorials, oTree. “oTree Tutorials Part 1: Introduction.” Youtube, 2021. https://www.youtube.com/watch?v=OzkFvVhoHr0&t=292s.

Zhang, Xijia, Yue Guo, Simon Stepputtis, Katia Sycara, and Joseph Campbell. 2023. “Explaining Agent Behavior with Large Language Models.” https://arxiv.org/pdf/2309.10346.pdf.











