# Prometheus

Prometheus is a FastAPI-based backend system designed for intelligent codebase-level operations, including answering technical questions, resolving issues, and reviewing pull requests. It employs a **multi-agent framework governed by a state machine**, enabling structured and scalable coordination for tasks such as:

* Automated code review
* Continuous build and test verification
* Intelligent patch generation and validation
* Multi-turn reasoning over complex software repositories

Prometheus is built to support research in **automatic program repair**, **agent collaboration**, and **retrieval-augmented code understanding**.

If you find Prometheus useful for your research or development, please consider citing:

```
@article{chen2025prometheus,
  author = {Chen, Zimin* and Pan, Yue* and Xu, Jiayi and Lu, Siyu and Monperrus, Martin and Ye, He},
  title  = {Prometheus: A Multi-Agent Framework for Intelligent Codebase-Level Operations},
  year   = {2025},
  note   = {Manuscript in preparation},
}
```

## Core Features

* 🔁 **Multi-Agent Loop**: LLM-based agents operate in coordination via an event-driven state machine
* 📦 **FastAPI Backend**: Clean API interface for integration and deployment
* 🧠 **LLM + RAG**: Supports retrieval-augmented generation for complex context understanding
* ✅ **Task Benchmarks**: Integrated with SWE-bench-lite and custom benchmarks for evaluating patch correctness and reasoning ability

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
  <img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
</a><br />
This work is licensed under a
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
Creative Commons Attribution-ShareAlike 4.0 International License
</a>.

