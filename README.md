# laughing-disco
python retrain.py — bottleneck_dir=tf_files/bottlenecks — how_many_training_steps=500 — model_dir=inception — summaries_dir=tf_files/training_summaries/basic — output_graph=tf_files/retrained_graph.pb — output_labels=tf_files/retrained_labels.txt — image_dir=training_dataset — eval_step_interval=100 & python classify.py image.jpg
