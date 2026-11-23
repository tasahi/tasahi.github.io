# Deep Learning Model Inference in Mojo

Most of modern computing is focused on the paradigm of fast computation: this leads a an ever increasing race for speed and resources.

What if we look for a different paradigm: Is it possible to run a process with a smaller footprint? 

Of course you have embedded devices and there are certain tools devoted to these category. This is more about running some of these processes in the edge: processing in the edge.

For that purpose, [Mojo](https://mojolang.org/) is a relative new language and toolchain that can be used to achive this edge computation.

A first challenge: implement a llama.cpp alternative in mojo. On the spirit of using already implemented aspects such as in the [llama.mojo](https://github.com/tairov/llama2.mojo) project, the [llamojo](https://github.com/tasahi/llamojo) project is able to load many models and do inference.
