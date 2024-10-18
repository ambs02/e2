# Reinforcement learning increasingly shapes memory specificity from childhood to adulthood
Tasks, anonymized data, and analysis code for: Reinforcement learning increasingly shapes memory specificity from childhood to adulthood

# Tasks

We conducted two multi-session online experiments. In the first session of each experiment, participants completed a reinforcement-learning task in which either specific exemplars or broader stimulus categories determined the rewards associated with different actions. In the second session, which was administered one week later, participants completed a memory test in which we probed the specificity of their memories for the stimuli encountered during learning.


# Data
Cleaned data and parameter estimates from our fitted reinforcement-learning models can be found in the data folders within each experiment.
Found on OpenCogData: https://nimh-dsst.github.io/OpenCogData/nussenbaum-hartley-2023/


# Instructions for use
1. git clone https://github.com/ambs02/e2 && cd e2
2. sudo chmod -R 777 nbs/
3. docker-compose up -d 
4. docker exec <namenode> hdfs dfs -put /home/nbs/e2_learning_data.csv /e2_learning_data.csv
5. docker exec <namenode> hdfs dfs -put /home/nbs/e2_memory_data.csv /e2_memory_data.csv
6. docker exec <namenode> hdfs dfs -put /home/nbs/e2_rl_data.csv /e2_rl_data.csv
8. docker exec <namenode> hdfs dfs -put /home/nbs/e2_suba_ages.csv /e2_sub_ages.csv


