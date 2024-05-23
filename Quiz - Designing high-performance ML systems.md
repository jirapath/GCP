# Designing high-performance ML systems
If each of your examples is large in terms of size and requires parsing, and your model is relatively simple and shallow, your model is likely to be:
>Latency-bound, so you should use faster hardware </br>
✔ I/O bound, so you should look for ways to store data more efficiently and ways to parallelize the reads. </br>
CPU-bound, so you should use GPUs or TPUs.
---
For the fastest I/O performance in TensorFlow… (check all that apply)
>✔ Read in parallel threads. </br>
✔ Optimize TensorFlow performance using the Profiler. </br>
✔ Prefetch the data </br>
✔ Read TF records into your model.
---
Which of the following indicates that ML training is CPU bound?
>If you are running a model on powered hardware. </br>
✔ If I/O is simple, but the model involves lots of complex/expensive computations. </br>
If you are running a model on accelerated hardware. </br>
If I/O is complex, but the model involves lots of complex/expensive computations.
---
What does high-performance machine learning determine?
>Deploying a model </br>
✔ Time taken to train a model </br>
Reliability of a model </br>
Training a model
---
