Dialogue Summarization on *SAMSum dataset*. <br><br>


Pipeline workflow - 

Step 1: **Parameter Efficient Fine-Tuning (PEFT)** on *FLAN-T5 base model*. <br>
Step 2: The results are then aligned using **Reinforcement Learning from Human Feedback (RLHF)**. <br>
Step 3: **Retrieval Augmented Generation (RAG)** to augment the generation of summaries.


Link to deployed application - https://huggingface.co/spaces/raghav-gaggar/Text_Summarizer
