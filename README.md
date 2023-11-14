# Machine translation (English --> Finnish)
Seq-to-seq model with attention for machine translation

1. Dataset : A English-Finnish bilingual dataset from http://www.manythings.org/anki/
   
2. Task
- A machine translation task
- Input (source): English sentence
- Output (target): Finnish sentence

3. Specification
- Constructed data iterators
- Contained python class for Encoder, Decoder, and the Seq2Seq model (no transformers architecture included)
- Decoder included the process of calculating attention scores (weights) over the encoder hidden states
- Contained training, evaluation processes
- Printed the (average) BLEU score(s) as well as the loss values during model evaluation
- Conducted inference for the following test sentence : “It will be raining tomorrow.”
