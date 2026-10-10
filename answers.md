# Answers

- Why did you get -inf log-probability for OOV words above? How can you fix it? What do -unk and -addsmooth 0 signify?
    - We have got -inf log-probability beacuse the model assigned probability 0 to some words or word sequence. In log space  
     $$
     log(0) = −∞
     $$     