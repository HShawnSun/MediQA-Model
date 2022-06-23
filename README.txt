预测步骤：
关黄母颗粒问答预测
sh test_bert_ghm.sh
丁苯酚问答预测
sh test_bert_dbf.sh   执行此脚本时，按照metrics.py 730行 提示 更改存放地址


参数：
--lm: 要加载的模型的文件夹名称
--do_train: 开启训练
--evaluate_during_training: 开启训练时的验证
--do_test: 开启预测
--version_2_with_negative: 开启适配于数据中有无答案数据
--threads: 数据处理所使用的线程数






