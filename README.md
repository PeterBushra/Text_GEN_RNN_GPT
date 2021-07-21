# Text_GEN_RNN_GPT
Text Generation Using RNN and GPT2

* RNN
  - Building The Model
  - Learning Rate Scheduler From TF
  - Custom Learning Rate Scheduler
  - Generation Function

* GPT
* GPT2
  - BEAM SEARCH
  - N_gram for Prevent Repetation = 3
    - prevents the model from generating any 3-grams or
      triplets of tokens more than once. 
  - Temperature
    - can be used to adjust the
      predictability of the generated text.
      Once probabilities for all characters are predicted, dividing the probabilities by the
      temperature changes the distribution of the generated characters. Smaller values of
      the temperature generate text that is closer to the original text. Larger values of the
      temperature generate more creative text.
  - Early Stopping
    - The early_stopping parameter signals generation to stop when
      all beams reach the EOS token
  - TOP-K Sampling
    -  at every step, it picks a token
        from the top K highest probability tokens. If K is set to 1, then this algorithm is
        identical to the greedy search.In the code example above, the model looks at the 25 top tokens out of the 50,000+
        tokens while generating text.
 
