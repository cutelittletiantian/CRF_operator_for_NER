# CRF_operator_for_NER
This is a self-defined CRF (Conditional Random Field) Operator specifically designed for Named Entity Recognition problem.

适用于命名实体识别问题的条件随机场(CRF)算子。

You don't have to use a START_TAG or STOP_TAG (like how PyTorch does in its NER Tutorial document), so it will be easier to integrate in other DL models.

该算子不同于PyTorch官方提供的NER教学文档里面那样，需要用到START_TAG和STOP_TAG，也因此该算子可以更方便地集成到各种深度学习模型中。

## References

* PyTorch LSTM-CRF for NER (Official Demo)
  * [PyTorch基于LSTM-CRF的NER示例](https://pytorch.org/tutorials/beginner/nlp/advanced_tutorial.html?highlight=ner)
* Algorithm Ralated to CRF
  * [手撕 BiLSTM-CRF](https://zhuanlan.zhihu.com/p/97676647)
  * [通俗易懂！BiLSTM上的CRF，用命名实体识别任务来解释CRF（一）](https://zhuanlan.zhihu.com/p/119254570)
  * [通俗易懂！BiLSTM上的CRF，用命名实体识别任务来解释CRF（二）](https://zhuanlan.zhihu.com/p/121499333)
  * You can also search for other materials for deeper understanding :)