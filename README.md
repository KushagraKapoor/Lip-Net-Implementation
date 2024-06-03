
# LipNet: Cracking the Lipreading Code with Deep Learning

### Traditional Lipreading vs Deep Learning Revolution

* Traditionally, lipreading involved two steps:
    * Identifying visual features (what the mouth looks like)
    * Predicting words based on those features
* LipNet breaks away from this two-step process. It's trained entirely from scratch, learning both the visual aspects of lip movement and how those movements translate to language.

### Going Beyond Words

* Existing deep learning models for lipreading could only handle single words. LipNet tackles entire sentences, considering the flow of speech for better accuracy, similar to how humans lipread better with longer words.

### LipNet's Architecture

* **Spatiotemporal Convolutions:** Capture how the appearance of the mouth changes over time (both spatial - where things are - and temporal - how they move).
* **Recurrent Network:** Mimics how our brains process language, considering the sequence of lip movements to understand the full sentence.
* **Connectionist Temporal Classification Loss:** A training method that compares the model's guesses to the actual text, helping it improve over time.

### LipNet's Performance

* Tests show LipNet achieves an impressive 95.2% accuracy in converting full sentences from lip movements. This surpasses the abilities of experienced human lipreaders and previous deep learning models.

**LipNet represents a significant leap forward in automatic lipreading, paving the way for new applications that rely on understanding speech without needing audio.**





**Reference:** 
[Assael et al., 2016](https://arxiv.org/abs/1611.01599)
**Additional Resources:**

* A video tutorial on building a lip reading model with Tensorflow can be found on [YouTube](https://www.youtube.com/watch?v=uKyojQjbx4c&t=359s). In this video, Nicholas Renotte walks viewers through the process step-by-step.

