CoNLL 2010 shared task 2 on hedge cue/scope detection


python3 data/converter.py train cuescope conll10_task2_rev2.cuescope.train.tsv conll10_task2_rev2.cuescope.dev.tsv data/task2_train_bio_abstracts_rev2.xml data/task2_train_bio_fullarticles_rev2.xml
python3 data/converter.py test cuescope conll10_task2_rev2.cuescope.test.tsv data/task2_eval_rev.xml

python3 data/converter.py train cue conll10_task2_rev2.cue.train.tsv conll10_task2_rev2.cue.dev.tsv data/task2_train_bio_abstracts_rev2.xml data/task2_train_bio_fullarticles_rev2.xml
python3 data/converter.py test cue conll10_task2_rev2.cue.test.tsv data/task2_eval_rev.xml

python3 data/converter.py train scope conll10_task2_rev2.scope.train.tsv conll10_task2_rev2.scope.dev.tsv data/task2_train_bio_abstracts_rev2.xml data/task2_train_bio_fullarticles_rev2.xml
python3 data/converter.py test scope conll10_task2_rev2.scope.test.tsv data/task2_eval_rev.xml


yucatan:conll10$ python convert_to_sentencelevel.py O conll10_task2_rev2.cue.train.tsv > conll10_task2_rev2.cue.train.tsv_sentencelevel
yucatan:conll10$ python convert_to_sentencelevel.py O conll10_task2_rev2.cue.dev.tsv > conll10_task2_rev2.cue.dev.tsv_sentencelevel


