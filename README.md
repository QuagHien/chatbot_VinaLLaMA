## Fine-tuned VinaLLaMA
Vietnamese Language Chatbot that can converse in daily conversations, so in the following we will perform VinaLLaMA finetuning on the conversation data 'alespalla/chatbot instruction prompts'.
# Customizing Code
Initializing the model: "vilm/vinallama-7b-chat" - a model trained by a Vietnamese research group on a predominantly Vietnamese dataset.
Our goal is to build a chatbot that can conduct daily conversations. To improve answer quality, we will fine-tune VinaLLaMA on the conversation dataset named 'alespalla/chatbot_instruction_prompts'.
*Building a fine-tuning dataset using the DatasetDict data type.
*Train model.
