# Instructions

Last updated: Sep 27th 2022

Checkpoints are available here: https://drive.google.com/drive/u/0/folders/1Z9WmhoMdgk-_DRY5QMhVhX_EtMJH2RvU  <br />
pytorch_model.bin - fine-tuned CodeT5 for NL2Py  <br />
student.zip - student model for inference with distillation  <br />

Results: <br />
codebleu = 29 <br />
bleu = 20 <br />

Inference done on initial model, taken from https://github.com/salesforce/CodeT5 and used for finetuning model for NL2Py benchmark. <br />

For inference distillation and 8bit mutiplication were used. Results are probided in the notebook. 
