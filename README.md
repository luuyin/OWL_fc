####    TEST for FC-layerwise sparsity


python main.py \
  --model baffo32/decapoda-research-llama-7B-hf \
  --model_name_or_path baffo32/decapoda-research-llama-7B-hf \
  --Lamda 0.08 --Hyper_m 5 \
  --prune_method wanda_owl_fc \
  --sparsity_ratio 0.7 --sparsity_type unstructured 
