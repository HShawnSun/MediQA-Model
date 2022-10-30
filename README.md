# Bert-like Models feasibility Exploration on Medical Short-Text Q&A Tasks

Explored the feasibility of Bert-like models for machine reading comprehension of small 
text in specialized areas; selected and blended different classes of Bert-like models to 
pursue better performance on small text data obtained from medical illustration videos; 
attempted to train field-specific MRC model for medical Q&A tasks, tuning parameters; 
tested and evaluated the performance; NLP skillsets increased by interacting with 
supervisor and Ph.D. students; attained a deeper understanding of DL & RL formulas; 
research contributed to Ningbo 2025 Sci & Tech Innovation Program.

### 预测步骤：
关黄母颗粒问答预测
sh test_bert_ghm.sh
丁苯酚问答预测
sh test_bert_dbf.sh   执行此脚本时，按照metrics.py 730行 提示 更改存放地址

### 参数：
--lm: 要加载的模型的文件夹名称
--do_train: 开启训练
--evaluate_during_training: 开启训练时的验证
--do_test: 开启预测
--version_2_with_negative: 开启适配于数据中有无答案数据
--threads: 数据处理所使用的线程数






