+++
date = "2015-03-18"

title = "HeteroSpark: A Heterogeneous CPU/GPU Spark Platform for Deep Learning Algorithms"

abstract = "Various deep learning networks such as deep autoencoders, convolutional deep neural networks, and deep belief network have been widely applied to current state-of-the-art technologies. As recent technology advances in GPU lead superior performance over CPUs, GPUs have been increasingly used in a broad area of applications, such as machine learning, image processing and bioinformatics, etc.. However, single-GPU or GPU-only cluster face the challenge of dealing with large scale datasets or non-trivial development effort. Spark, as a CPU-only computing platform, provides fast in-memory computing capability, which is ideal for iterative computation such as machine learning applications. However, Spark slave nodes can achieve better performance and energy efficiency if with GPU acceleration. In this context, we propose HeteroSpark, a GPU-accelerated heterogeneous architecture integrated with Spark, which combines the power of GPU and scalability of Spark. We make the following contributions to the Spark community: (1) we integrate the GPU accelerator into current Spark platform to achieve further data parallelism and algorithm acceleration; (2) we provide a plugin for Spark platform so that current Spark applications can choose to enable/disable GPU acceleration; (3) accelerators are transparent to developers, therefore existing Spark applications can be easily ported to the heterogeneous platform without code modifications."

abstract_short = ""
event = "Spark Summit 2015"

event_url = "https://spark-summit.org/east-2015/heterospark-a-heterogeneous-cpugpu-spark-platform-for-deep-learning-algorithms-2/"

location = "New York, NY"

selected = true
math = true

url_pdf = "http://ieeexplore.ieee.org/document/7255222/"

url_slides = "https://spark-summit.org/2015-east/wp-content/uploads/2015/03/SSE15-28-Peilong-Li-Yan-Luo.pdf"

url_video = "https://www.youtube.com/watch?v=jpQxWcmXKyU"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
caption = "HeteroSpark: A Heterogeneous CPU/GPU Spark Platform for Deep Learning Algorithms"

+++

{{< youtube jpQxWcmXKyU >}}
