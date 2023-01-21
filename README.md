## Neural knowledge transfer (distillation) for improved Sentiment Analysis in texts with figurative language

</br>

### Overview

The goal of this project was to improve the performance of a neural network when analyzing the sentiment of texts with figurative language. Sarcasm, irony and metaphors usually revert the actual meaning of a sentence, since positive words are used with negative attitude and vice versa.

To this end, a student-teacher architecture was adopted to transfer/distill the knowledge of teacher about figurative language detection to the student model which performs sentiment analysis on figurative texts.

The idea was implemented and evaluated on the SemEval workshop 2015 Task 11 data where we manage to surpass all existing approaches.

Specifically, we recreated the state-of-the-art model (student) found in - - and improved its performance via knowledge distillation from a teacher model. The teacher architecture was found in - - and was trained by us to detect figurative language.

More details about the implementation can be found in the published paper linked below 


------------

### Project Organization

1. student - ROBERTA - Potamias - It contains the files used to recreate the student architecture from the respective source paper mentioned above.

2. teacher - Tweets with sarcasm and irony - Binary - It contains the teacher model.

3. novelty saves - It contains the improved student model.

4. Evaluation for S15-T11 - It contains the files for getting the SemEval workshop's metrics for comparing with previous approaches.

5. distillation training - alpha.ipynb - It's the final notebook used to get the best performing student model.


</br>
----------------

This project was part of my diploma thesis - - and was published in the 2022 IEEE 32nd International Workshop on Machine Learning for Signal Processing (MLSP) - https://ieeexplore.ieee.org/abstract/document/9943314.



