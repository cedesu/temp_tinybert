# temp_tnybert

python ./examples/run_classifier_realt.py --data_dir ~/suguinan/glue_data/SST-2 --bert_model bert-base-uncased --task_name sst-2 --do_train --do_eval --num_train_epochs 100 --do_lower_case --learning_rate 2e-5 --train_batch_size 32 --eval_batch_size 32 --output_dir ~/maoyh/test0_1 --distill_dir ~/maoyh/sst_distill_weight
