 <div align="justify"> 

Collaborative learning is a method of education in which a group of learners solves a particular task. A collaborative setting encourages learners to take a more active role in knowledge construction. However, when they communicate on a virtual platform such as a chat 
platform, it is important that they can refer to each other correctly
so that they can improve their learning activities with the help of
each other, but learners can be sidetracked, which retards their
learning progress. To address this issue, this thesis practiced text
classification approaches to regularize the conversation between
learners so they could refer to each other correctly. The dataset
was collected from a focus group experiment designed for students
in the Educational Technology Department at Saarland University.
The report gives a clear idea of how the collected dataset has been

coded and validated with the help of intercoder reliability measure-
ments. After data preprocessing, state-of-the-art data augmentation

techniques such as spelling, insertion, substitution, and synonym

augmentation are applied. The thesis examines various neural net-
work models to identify the best model for the dataset. Among

them, Bidirectional Encoder Representations from Transformers
(BERT) provides the best performance with an accuracy of 0.94 and
a 0.17 loss value for the augmented preprocessed dataset, where
recurrent neural network models tend to overfit. In the evaluation
part, a summary of performance matrices is shown, and to evaluate
the model, a new dataset with similar data is generated with the
help of the OpenAI API Key. The BERT model is able to classify
960 responses out of 1005, where both recurrent neural networks
are classified less than 200. The thesis also discussed the issue of
model poisoning so that when the model is updated, it can tackle
the unclassified responses. Finally, a simple demo of how this
BERT model is used to regularize the discourse of two collaborative
learners is presented with the help of the Jupyter interface.
</div>
