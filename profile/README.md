# Adventists AI

**Open voice models that hear *how* you speak.**

We build the listening and speaking layers for full-duplex voice agents: knowing when a person has finished, when they want to cut in, and what their tone, stress and laughter mean. Our voice stack already runs in 300+ AI hardware products.

## Projects

| | What it is | Status |
|---|---|---|
| [**DuplexJev**](https://github.com/adventists-ai/duplexjev) | Speech decision model for voice agents: turn-taking, barge-in, emotion, stress, laughter and more, read from audio in one forward pass (10 decisions in ~0.09 s). #1 on public paralinguistic benchmarks (LISTEN, StressTest, MSPB). 32B and 4B, served with vLLM. | Open weights · [paper](https://arxiv.org/abs/2610.02638) · [demo](https://huggingface.co/spaces/BitKnight/DuplexJev) |
| [**Sophon-Realtime**](https://github.com/adventists-ai/sophon-realtime) | Open full-duplex voice model that hears your tone and speaks with one: laughs, sighs and stresses words when the conversation calls for it. #1 among open full-duplex models on VoiceBench (82.8) and Big Bench Audio (81.8%). Tag and Flash builds run on one GPU with vLLM-Omni; OpenAI GPT-Live compatible Live mode. | Open weights · [HF](https://huggingface.co/adventists-ai/Sophon-Realtime-32B-Tag) · [ModelScope](https://www.modelscope.cn/models/AdventistsAI/Sophon-Realtime-v1) · `pip install sophon-realtime` |
| [**heteronym-bench**](https://github.com/adventists-ai/heteronym-bench) | TTS heteronym reading benchmark (English / Japanese): test sets, automatic judges and baselines. | Open |

## Links

- Models: [huggingface.co/adventists-ai](https://huggingface.co/adventists-ai)
- Website: [adventists.cn](https://adventists.cn)
- Questions: [DuplexJev Discussions](https://github.com/adventists-ai/duplexjev/discussions)
- Contact: jiejin@adventists.ai

DuplexJev is joint work with Zhejiang University and the University of Virginia.
