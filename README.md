# dialogsum_llm
# DialogSum (Text) Summarization using Large Language Model


1. Conducted comparative analysis b/w PEFT (LoRA) and fully-ne tuned variants of FLAN-T5 model witnessing only ~5% reduction in ROUGE-1 metric while ~98% reduction in number of parameters; used AWS SageMaker
2. Decreased toxicity score by ~25% by ne-tuning FLAN-T5 model with RL (proximal policy optimization) & PEFT
