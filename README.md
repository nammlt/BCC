# Comparative EEG Responses to Reward and Loss in  Three armed bandit Gambling Tasks
## About the project
I found that 77% of Thai people have reported engaging in gambling at least once in their lives, with one of the most popular forms being the lottery, commonly known as “หวย” in Thai. Additionally, some Thai people are addicted to playing the lottery every round. It make me curious about how the brain works when playing gambling and what makes people addicted. 

So this project explores how the brain responds differently to reward (winning) and loss outcomes (losing), focusing on specific brain wave responses known as event-related potentials (ERPs), such as Feedback-Related Negativity (FRN) and Reward Positivity (Rew-P).  

## Getting Started
I did this project in Google Colab https://colab.research.google.com/?utm_source=scs-index. I downloaded the dataset and put it in my Google Drive.  

### Installation
I used MNE to visualize graphs that compare these responses.  
```
!pip install mne
```

### Repository Structure
`EEG_Three_armed_bandit_gambling_task.ipynb`: Google Colab was used for all processes in this project.
- Exploratory Data Analysis (EDA)
- Preprocessing
- Analysis
- Visualization

### Three armed bandit gambling task
Dataset: [ds003458](https://openneuro.org/datasets/ds003458/versions/1.1.0)
( Cavanagh, J. F. (2021). EEG: Three armed bandit gambling task. Open Neuro )
![image](https://github.com/user-attachments/assets/db50c364-4a53-4d08-a659-a4bf68a29f55)
- State: The three slot machines represent the available states.
- Action: The agent’s choice to select any one of the slot machines.
- Reward: The outcome or prize each slot machine randomly provides upon being played.

## Acknowledgements
Thank you for the opportunities and knowledge to implement this project. It couldn’t have been successful without my TAs, Sirapakit Limtragooltongchai (P'Pung) and Korrawiz Chotayapa (P'Ong), especially during Brain Code Camp.

You can explore more on my Medium page.
https://medium.com/@fansssexo/comparative-eeg-responses-to-reward-and-loss-in-three-armed-bandit-gambling-tasks-39283d879e68
