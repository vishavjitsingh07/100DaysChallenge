# 100-Day LLM Engineering Challenge — Detailed 2-Hour Planner

## Fixed daily schedule
- [ ] **00:00–00:10 — Recall:** no notes; answer yesterday's 3 questions.
- [ ] **00:10–00:45 — YouTube:** 30–35 minutes on today's exact topic.
- [ ] **00:45–01:00 — Active recall:** close the video; redraw/explain the concept.
- [ ] **01:00–01:50 — Build:** implement today's artifact.
- [ ] **01:50–02:00 — Ship:** test, commit, and write Learned / Built / Blocked.

## Recall yesterday — 5-step method
1. Blurt for 3 minutes.
2. Answer yesterday's questions without notes.
3. Teach one concept for 60 seconds.
4. Open notes and correct the gaps.
5. Write one memory hook for tomorrow.

## Completion rule
**Video watched ≠ day completed.** A day is complete only when Learn + Build + Ship + Definition of Done are checked.

## Day 001 — LLM mental model
**Phase 1 — LLM Foundations**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R3/R4 → LLM mental model**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Draw the inference pipeline and explain it aloud; then make a tiny tokenizer/inference notebook.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **LLM mental model**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=LLM+mental+model+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] tokens → logits → probabilities → next token
- [ ] training vs inference
- [ ] parameters vs weights vs activations
- [ ] context window and why it matters

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Draw the inference pipeline and explain it aloud; then make a tiny tokenizer/inference notebook.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Use Feynman: explain why the model cannot 'look up' the next token unless you give it a retrieval/tool path.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 002 — Tokenization
**Phase 1 — LLM Foundations**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R3/R4 → Tokenization**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Write a tokenizer comparison script for 10 prompts and print token counts.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Tokenization**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Tokenization+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] BPE/subwords
- [ ] token IDs and special tokens
- [ ] token count vs characters/words
- [ ] why code/JSON can be token-expensive

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Write a tokenizer comparison script for 10 prompts and print token counts.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Always check token counts before designing context windows or cost estimates.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 003 — Embeddings
**Phase 1 — LLM Foundations**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R3/R4 → Embeddings**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Embed the corpus with two models and compare retrieval quality.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Embeddings**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Embeddings+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] bi-encoder idea
- [ ] model selection
- [ ] normalization
- [ ] embedding evaluation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Embed the corpus with two models and compare retrieval quality.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Use your own evaluation set to choose a model.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 004 — Attention
**Phase 1 — LLM Foundations**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R3/R4 → Attention**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Implement scaled dot-product attention in PyTorch and print tensor shapes.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Attention**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Attention+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] Q/K/V roles
- [ ] scaled dot-product attention
- [ ] causal masking
- [ ] multi-head attention

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Implement scaled dot-product attention in PyTorch and print tensor shapes.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Write Q, K and V on paper. Then trace one token through attention.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 005 — Decoder Transformers
**Phase 1 — LLM Foundations**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R3/R4 → Decoder Transformers**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Draw one decoder block and annotate every tensor entering/leaving it.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Decoder Transformers**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Decoder+Transformers+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] residual stream
- [ ] layer normalization
- [ ] MLP block
- [ ] decoder-only autoregressive architecture

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Draw one decoder block and annotate every tensor entering/leaving it.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Keep tensor shapes visible; shape confusion causes most beginner transformer confusion.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 006 — Decoding
**Phase 1 — LLM Foundations**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R3/R4 → Decoding**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Run one prompt with greedy, temperature, top-k and top-p; compare outputs.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Decoding**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Decoding+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] greedy vs sampling
- [ ] temperature
- [ ] top-k/top-p
- [ ] repetition penalties

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Run one prompt with greedy, temperature, top-k and top-p; compare outputs.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Compare outputs with the same seed/settings where possible.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 007 — LLM APIs
**Phase 1 — LLM Foundations**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R3/R4 → LLM APIs**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build a streaming CLI chatbot with environment-based API keys.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **LLM APIs**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=LLM+APIs+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] messages/roles
- [ ] streaming
- [ ] structured outputs
- [ ] tool/function calls

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build a streaming CLI chatbot with environment-based API keys.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Treat API responses as untrusted external data and validate structured outputs.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 008 — Prompt engineering
**Phase 1 — LLM Foundations**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R3/R4 → Prompt engineering**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Create 5 prompt variants and evaluate them on 20 fixed inputs.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Prompt engineering**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Prompt+engineering+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] instruction hierarchy
- [ ] few-shot examples
- [ ] delimiters
- [ ] output contracts

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Create 5 prompt variants and evaluate them on 20 fixed inputs.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
A good prompt has an explicit task, constraints, evidence boundary and output contract.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 009 — Context engineering
**Phase 1 — LLM Foundations**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R3/R4 → Context engineering**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build a token-budgeted context builder that trims and ranks snippets.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Context engineering**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Context+engineering+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] relevant context selection
- [ ] token budgets
- [ ] compression
- [ ] prompt-injection boundary

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build a token-budgeted context builder that trims and ranks snippets.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
More context can reduce quality. Optimize relevance per token.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 010 — Checkpoint 1
**Phase 1 — LLM Foundations**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R3/R4 → Checkpoint 1**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Ship Mini Project 1: streaming research assistant + README + architecture diagram.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Checkpoint 1**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Checkpoint+1+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] explain the phase concept
- [ ] know the main components
- [ ] know one failure mode
- [ ] connect it to production

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Ship Mini Project 1: streaming research assistant + README + architecture diagram.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Checkpoint rule: do not move forward because the calendar says so. Move forward when you can demo the artifact, explain the architecture without notes, and name the main failure modes.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

### 🏁 PHASE CHECKPOINT
- [ ] 5-minute no-notes explanation
- [ ] Demo the artifact
- [ ] Write 3 weaknesses to revisit
- [ ] Do not start the next phase until the artifact works

## Day 011 — Python project structure
**Phase 2 — LLM Application Engineering**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R9 → Python project structure**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Create a clean Python package with config, logging, tests and a CLI entry point.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Python project structure**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_RmvZ41tjbKB2ZnwchfniNsMuQ
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Python+project+structure+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] venv/uv
- [ ] typing + Pydantic
- [ ] configuration
- [ ] logging/package structure

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Create a clean Python package with config, logging, tests and a CLI entry point.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
If importing your own code feels messy, fix the package structure before adding features.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 012 — Schemas
**Phase 2 — LLM Application Engineering**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R9 → Schemas**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Create Pydantic schemas for Query, Citation, Answer and ToolCall; validate bad inputs.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Schemas**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_RmvZ41tjbKB2ZnwchfniNsMuQ
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Schemas+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] request/response models
- [ ] nested validation
- [ ] JSON Schema
- [ ] structured output validation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Create Pydantic schemas for Query, Citation, Answer and ToolCall; validate bad inputs.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Validate at boundaries: API input, model output and tool arguments.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 013 — FastAPI basics
**Phase 2 — LLM Application Engineering**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R9 → FastAPI basics**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build /health, /chat and /models endpoints with typed request/response models.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **FastAPI basics**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_RmvZ41tjbKB2ZnwchfniNsMuQ
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=FastAPI+basics+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] routes
- [ ] dependency injection
- [ ] request/response models
- [ ] health/error handling

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build /health, /chat and /models endpoints with typed request/response models.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Keep model calls out of route spaghetti; use services/modules.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 014 — Async
**Phase 2 — LLM Application Engineering**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R9 → Async**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Call five independent model tasks concurrently and compare sequential vs async latency.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Async**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_RmvZ41tjbKB2ZnwchfniNsMuQ
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Async+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] async/await
- [ ] concurrency vs parallelism
- [ ] connection reuse
- [ ] when not to parallelize

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Call five independent model tasks concurrently and compare sequential vs async latency.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Only parallelize independent work. Dependencies still need sequencing.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 015 — Streaming
**Phase 2 — LLM Application Engineering**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R9 → Streaming**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Add SSE token streaming to your FastAPI /chat endpoint.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Streaming**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_RmvZ41tjbKB2ZnwchfniNsMuQ
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Streaming+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] SSE
- [ ] incremental tokens
- [ ] disconnects
- [ ] cancellation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Add SSE token streaming to your FastAPI /chat endpoint.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Streaming improves perceived latency but does not reduce total compute.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 016 — Reliability
**Phase 2 — LLM Application Engineering**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R9 → Reliability**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Simulate provider/model/vector DB failures and implement graceful degradation.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Reliability**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_RmvZ41tjbKB2ZnwchfniNsMuQ
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Reliability+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] rate limits
- [ ] queues
- [ ] circuit breakers
- [ ] graceful degradation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Simulate provider/model/vector DB failures and implement graceful degradation.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Design failure paths before users discover them.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 017 — Caching
**Phase 2 — LLM Application Engineering**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R9 → Caching**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Add a cache layer and report hit rate, latency and cache-key behaviour.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Caching**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_RmvZ41tjbKB2ZnwchfniNsMuQ
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Caching+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] cache keys
- [ ] exact cache
- [ ] semantic cache
- [ ] privacy/invalidation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Add a cache layer and report hit rate, latency and cache-key behaviour.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Measure cache hit rate before celebrating a cache.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 018 — Testing
**Phase 2 — LLM Application Engineering**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R9 → Testing**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Write 20 tests for prompt formatting, parsing, schemas and tool routing.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Testing**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_RmvZ41tjbKB2ZnwchfniNsMuQ
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Testing+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] unit tests
- [ ] mocks
- [ ] golden datasets
- [ ] contract tests

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Write 20 tests for prompt formatting, parsing, schemas and tool routing.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Assert contracts and outcomes, not exact generated prose.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 019 — Cost & latency
**Phase 2 — LLM Application Engineering**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R9 → Cost & latency**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Instrument tokens, latency p50/p95 and estimated cost per request.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Cost & latency**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_RmvZ41tjbKB2ZnwchfniNsMuQ
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Cost+%26+latency+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] input/output tokens
- [ ] p50/p95
- [ ] throughput
- [ ] cost per successful task

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Instrument tokens, latency p50/p95 and estimated cost per request.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Track p95; the slowest users experience the tail, not the average.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 020 — Checkpoint 2
**Phase 2 — LLM Application Engineering**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R9 → Checkpoint 2**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Ship Mini Project 2: tested, streaming FastAPI LLM service.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Checkpoint 2**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_RmvZ41tjbKB2ZnwchfniNsMuQ
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Checkpoint+2+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] explain the phase concept
- [ ] know the main components
- [ ] know one failure mode
- [ ] connect it to production

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Ship Mini Project 2: tested, streaming FastAPI LLM service.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Checkpoint rule: do not move forward because the calendar says so. Move forward when you can demo the artifact, explain the architecture without notes, and name the main failure modes.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

### 🏁 PHASE CHECKPOINT
- [ ] 5-minute no-notes explanation
- [ ] Demo the artifact
- [ ] Write 3 weaknesses to revisit
- [ ] Do not start the next phase until the artifact works

## Day 021 — Why RAG
**Phase 3 — RAG Fundamentals**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Why RAG**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Create a 20-document corpus and 15 questions; label which questions require retrieval.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Why RAG**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Why+RAG+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] knowledge freshness
- [ ] grounding
- [ ] retrieval vs generation
- [ ] when RAG is a bad fit

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Create a 20-document corpus and 15 questions; label which questions require retrieval.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
First prove that retrieval adds evidence; don't start with an agent.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 022 — Ingestion
**Phase 3 — RAG Fundamentals**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Ingestion**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build file → text → clean → metadata → chunks as a repeatable pipeline.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Ingestion**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Ingestion+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] PDF/text/HTML extraction
- [ ] cleaning
- [ ] metadata
- [ ] repeatable indexing

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build file → text → clean → metadata → chunks as a repeatable pipeline.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Metadata becomes extremely valuable during debugging and citations.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 023 — Chunking
**Phase 3 — RAG Fundamentals**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Chunking**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Implement and compare fixed, recursive and semantic-ish chunking.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Chunking**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Chunking+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] fixed vs recursive
- [ ] overlap
- [ ] semantic boundaries
- [ ] chunk experiments

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Implement and compare fixed, recursive and semantic-ish chunking.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Evaluate chunking using retrieval results, not a universal token number.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 024 — Embeddings
**Phase 3 — RAG Fundamentals**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Embeddings**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Embed the corpus with two models and compare retrieval quality.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Embeddings**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Embeddings+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] bi-encoder idea
- [ ] model selection
- [ ] normalization
- [ ] embedding evaluation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Embed the corpus with two models and compare retrieval quality.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Use your own evaluation set to choose a model.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 025 — Vector search
**Phase 3 — RAG Fundamentals**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Vector search**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build local vector search and return top-k passages with scores.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Vector search**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Vector+search+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] similarity metrics
- [ ] ANN intuition
- [ ] HNSW
- [ ] top-k retrieval

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build local vector search and return top-k passages with scores.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Inspect the top-k passages manually before tuning the generator.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 026 — First RAG
**Phase 3 — RAG Fundamentals**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → First RAG**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build retrieve → prompt → generate → cite end-to-end.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **First RAG**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=First+RAG+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] retrieve
- [ ] evidence prompt
- [ ] generate
- [ ] cite sources

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build retrieve → prompt → generate → cite end-to-end.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
If the retrieved evidence is wrong, prompting cannot magically fix retrieval.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 027 — Eval dataset
**Phase 3 — RAG Fundamentals**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Eval dataset**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Create a 30-query RAG golden set including unanswerable cases.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Eval dataset**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Eval+dataset+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] answerable/unanswerable
- [ ] hard questions
- [ ] expected evidence
- [ ] dataset versioning

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Create a 30-query RAG golden set including unanswerable cases.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Your evaluation set is a product asset; version it like code.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 028 — Retrieval metrics
**Phase 3 — RAG Fundamentals**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Retrieval metrics**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Calculate Recall@k, Precision@k, MRR and hit rate.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Retrieval metrics**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Retrieval+metrics+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] Recall@k
- [ ] Precision@k
- [ ] MRR
- [ ] hit rate

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Calculate Recall@k, Precision@k, MRR and hit rate.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Recall answers 'did we retrieve evidence?' before answer quality asks 'did we use it?'

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 029 — Grounded generation
**Phase 3 — RAG Fundamentals**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Grounded generation**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Force source citations and refuse unsupported questions.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Grounded generation**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Grounded+generation+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] citation enforcement
- [ ] no-answer behavior
- [ ] evidence constraints
- [ ] hallucination analysis

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Force source citations and refuse unsupported questions.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Make 'I don't know' a successful outcome for unsupported questions.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 030 — Checkpoint 3
**Phase 3 — RAG Fundamentals**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Checkpoint 3**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Ship Mini Project 3: cited document Q&A + evaluation script.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Checkpoint 3**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Checkpoint+3+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] explain the phase concept
- [ ] know the main components
- [ ] know one failure mode
- [ ] connect it to production

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Ship Mini Project 3: cited document Q&A + evaluation script.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Checkpoint rule: do not move forward because the calendar says so. Move forward when you can demo the artifact, explain the architecture without notes, and name the main failure modes.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

### 🏁 PHASE CHECKPOINT
- [ ] 5-minute no-notes explanation
- [ ] Demo the artifact
- [ ] Write 3 weaknesses to revisit
- [ ] Do not start the next phase until the artifact works

## Day 031 — Hybrid retrieval
**Phase 4 — Advanced RAG**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Hybrid retrieval**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Combine BM25/lexical and dense retrieval using score fusion.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Hybrid retrieval**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Hybrid+retrieval+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] BM25
- [ ] dense retrieval
- [ ] score fusion
- [ ] exact-term retrieval

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Combine BM25/lexical and dense retrieval using score fusion.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Exact names, IDs and error strings are often lexical-search strengths.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 032 — Reranking
**Phase 4 — Advanced RAG**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Reranking**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Retrieve 20 passages, rerank them to 5 and benchmark latency/quality.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Reranking**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Reranking+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] cross-encoder intuition
- [ ] broad retrieval then rerank
- [ ] top-N trade-off
- [ ] latency impact

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Retrieve 20 passages, rerank them to 5 and benchmark latency/quality.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Retrieve broad cheaply, rerank narrowly expensively.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 033 — Query rewriting
**Phase 4 — Advanced RAG**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Query rewriting**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Generate alternate queries and compare retrieval recall.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Query rewriting**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Query+rewriting+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] query expansion
- [ ] decomposition
- [ ] HyDE intuition
- [ ] when rewriting hurts

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Generate alternate queries and compare retrieval recall.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Don't add rewriting latency unless the benchmark shows a gain.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 034 — Metadata filters
**Phase 4 — Advanced RAG**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Metadata filters**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Add source/date/type filters and test wrong-document leakage.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Metadata filters**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Metadata+filters+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] date/type/source filters
- [ ] permissions
- [ ] pre-retrieval filtering
- [ ] wrong-document leakage

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Add source/date/type filters and test wrong-document leakage.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Security/authorization filtering should happen before the model sees data.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 035 — Multi-query
**Phase 4 — Advanced RAG**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Multi-query**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Retrieve using multiple query perspectives and deduplicate results.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Multi-query**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Multi-query+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] multiple perspectives
- [ ] fusion
- [ ] recall vs latency
- [ ] duplicate removal

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Retrieve using multiple query perspectives and deduplicate results.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Deduplicate aggressively; multiple queries can create repeated context.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 036 — Parent-child retrieval
**Phase 4 — Advanced RAG**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Parent-child retrieval**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Retrieve small child chunks but pass the linked parent context.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Parent-child retrieval**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Parent-child+retrieval+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] small retrieval chunks
- [ ] larger parent context
- [ ] metadata linkage
- [ ] context quality

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Retrieve small child chunks but pass the linked parent context.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Retrieve precisely but give the model enough surrounding meaning.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 037 — Long-context packing
**Phase 4 — Advanced RAG**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Long-context packing**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build a context packer with token budget, deduplication and ordering.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Long-context packing**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Long-context+packing+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] token budget
- [ ] deduplication
- [ ] ordering
- [ ] lost-in-the-middle

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build a context packer with token budget, deduplication and ordering.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Context ordering matters; test it.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 038 — Failure analysis
**Phase 4 — Advanced RAG**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Failure analysis**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Label 30 RAG failures as retrieval, source, synthesis or citation failures.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Failure analysis**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Failure+analysis+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] retrieval miss
- [ ] wrong chunk
- [ ] stale source
- [ ] bad synthesis/citation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Label 30 RAG failures as retrieval, source, synthesis or citation failures.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Name the failure before changing the system.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 039 — Framework comparison
**Phase 4 — Advanced RAG**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Framework comparison**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Rebuild one retrieval component with a second framework and document trade-offs.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Framework comparison**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Framework+comparison+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] LangChain
- [ ] LlamaIndex
- [ ] RAGFlow/Haystack/Pathway
- [ ] framework vs primitives

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Rebuild one retrieval component with a second framework and document trade-offs.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Understand the primitive pipeline before comparing frameworks.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 040 — Checkpoint 4
**Phase 4 — Advanced RAG**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R16 → Checkpoint 4**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Ship RAG v2: hybrid retrieval + reranker + citations + evals.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Checkpoint 4**
- Playlist: https://florinelchis.medium.com/top-10-rag-frameworks-on-github-by-stars-january-2026-e6edff1e0d91
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Checkpoint+4+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] explain the phase concept
- [ ] know the main components
- [ ] know one failure mode
- [ ] connect it to production

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Ship RAG v2: hybrid retrieval + reranker + citations + evals.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Checkpoint rule: do not move forward because the calendar says so. Move forward when you can demo the artifact, explain the architecture without notes, and name the main failure modes.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

### 🏁 PHASE CHECKPOINT
- [ ] 5-minute no-notes explanation
- [ ] Demo the artifact
- [ ] Write 3 weaknesses to revisit
- [ ] Do not start the next phase until the artifact works

## Day 041 — LLM evaluation
**Phase 5 — Evaluation & Observability**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R5 → LLM evaluation**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build an evaluator that runs the golden set and stores scores.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **LLM evaluation**
- Playlist: https://www.youtube.com/playlist?list=PL86ARIu_ElO6Ngb7ubZru8C0dzzsFHAJX
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=LLM+evaluation+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] offline vs online evaluation
- [ ] task metrics
- [ ] human evaluation
- [ ] regression datasets

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build an evaluator that runs the golden set and stores scores.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
No benchmark means no reliable claim.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 042 — LLM-as-judge
**Phase 5 — Evaluation & Observability**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R5 → LLM-as-judge**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Create a rubric-based judge and manually audit five judged answers.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **LLM-as-judge**
- Playlist: https://www.youtube.com/playlist?list=PL86ARIu_ElO6Ngb7ubZru8C0dzzsFHAJX
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=LLM-as-judge+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] rubrics
- [ ] pairwise grading
- [ ] judge bias
- [ ] manual audit

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Create a rubric-based judge and manually audit five judged answers.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Use judges as measurement tools, not absolute truth.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 043 — Tracing
**Phase 5 — Evaluation & Observability**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R5 → Tracing**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Instrument request → retrieval → model → tool/output spans.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Tracing**
- Playlist: https://www.youtube.com/playlist?list=PL86ARIu_ElO6Ngb7ubZru8C0dzzsFHAJX
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Tracing+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] trace/span hierarchy
- [ ] retrieval spans
- [ ] LLM spans
- [ ] tool spans

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Instrument request → retrieval → model → tool/output spans.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
A trace should answer 'what happened and where did time go?'

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 044 — Production metrics
**Phase 5 — Evaluation & Observability**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R5 → Production metrics**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Create a report for latency, tokens, cost, errors and quality.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Production metrics**
- Playlist: https://www.youtube.com/playlist?list=PL86ARIu_ElO6Ngb7ubZru8C0dzzsFHAJX
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Production+metrics+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] latency
- [ ] tokens
- [ ] cost
- [ ] quality/error rate

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Create a report for latency, tokens, cost, errors and quality.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Track quality next to latency and cost.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 045 — Experiments
**Phase 5 — Evaluation & Observability**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R5 → Experiments**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Run controlled A/B tests across two prompts and two retrieval configurations.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Experiments**
- Playlist: https://www.youtube.com/playlist?list=PL86ARIu_ElO6Ngb7ubZru8C0dzzsFHAJX
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Experiments+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] version prompts/models/retrievers
- [ ] A/B comparison
- [ ] controlled variables
- [ ] reproducibility

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Run controlled A/B tests across two prompts and two retrieval configurations.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Change one major variable at a time.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 046 — Security
**Phase 5 — Evaluation & Observability**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R5 → Security**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Create 20 prompt-injection/tool-abuse tests and add defenses.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Security**
- Playlist: https://www.youtube.com/playlist?list=PL86ARIu_ElO6Ngb7ubZru8C0dzzsFHAJX
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Security+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] direct/indirect prompt injection
- [ ] tool abuse
- [ ] data exfiltration
- [ ] output validation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Create 20 prompt-injection/tool-abuse tests and add defenses.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Treat retrieved content and tool outputs as untrusted.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 047 — PII & secrets
**Phase 5 — Evaluation & Observability**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R5 → PII & secrets**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Add PII redaction and secret-safe structured logging.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **PII & secrets**
- Playlist: https://www.youtube.com/playlist?list=PL86ARIu_ElO6Ngb7ubZru8C0dzzsFHAJX
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=PII+%26+secrets+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] redaction
- [ ] secret handling
- [ ] safe logs
- [ ] retention

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Add PII redaction and secret-safe structured logging.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Logs are data stores; protect them accordingly.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 048 — Regression CI
**Phase 5 — Evaluation & Observability**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R5 → Regression CI**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Make CI fail when retrieval/answer quality falls below a threshold.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Regression CI**
- Playlist: https://www.youtube.com/playlist?list=PL86ARIu_ElO6Ngb7ubZru8C0dzzsFHAJX
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Regression+CI+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] golden tests
- [ ] quality thresholds
- [ ] CI gates
- [ ] failure artifacts

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Make CI fail when retrieval/answer quality falls below a threshold.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
A quality regression should be as visible as a unit-test failure.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 049 — Optimization sprint
**Phase 5 — Evaluation & Observability**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R5 → Optimization sprint**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Use measurements to improve one quality metric by ≥10% without unacceptable cost.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Optimization sprint**
- Playlist: https://www.youtube.com/playlist?list=PL86ARIu_ElO6Ngb7ubZru8C0dzzsFHAJX
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Optimization+sprint+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] identify bottleneck
- [ ] change one variable
- [ ] measure
- [ ] keep/revert

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Use measurements to improve one quality metric by ≥10% without unacceptable cost.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Optimize the bottleneck, not the component you happen to enjoy.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 050 — Checkpoint 5
**Phase 5 — Evaluation & Observability**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R5 → Checkpoint 5**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Ship Mini Project 4: evaluated + traced + secured RAG service.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Checkpoint 5**
- Playlist: https://www.youtube.com/playlist?list=PL86ARIu_ElO6Ngb7ubZru8C0dzzsFHAJX
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Checkpoint+5+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] explain the phase concept
- [ ] know the main components
- [ ] know one failure mode
- [ ] connect it to production

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Ship Mini Project 4: evaluated + traced + secured RAG service.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Checkpoint rule: do not move forward because the calendar says so. Move forward when you can demo the artifact, explain the architecture without notes, and name the main failure modes.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

### 🏁 PHASE CHECKPOINT
- [ ] 5-minute no-notes explanation
- [ ] Demo the artifact
- [ ] Write 3 weaknesses to revisit
- [ ] Do not start the next phase until the artifact works

## Day 051 — Tools vs agents
**Phase 6 — Tool Use & Agents**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Tools vs agents**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build calculator/search/file tools and define where deterministic workflow beats an agent.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Tools vs agents**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Tools+vs+agents+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] tool calling
- [ ] deterministic workflows
- [ ] agent autonomy
- [ ] decision boundaries

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build calculator/search/file tools and define where deterministic workflow beats an agent.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Use deterministic code when the path is known.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 052 — Tool calling
**Phase 6 — Tool Use & Agents**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Tool calling**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build a three-tool assistant with typed schemas and validation.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Tool calling**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Tool+calling+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] tool schema
- [ ] argument validation
- [ ] tool result format
- [ ] errors

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build a three-tool assistant with typed schemas and validation.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Never execute raw model arguments without validation.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 053 — Agent loop
**Phase 6 — Tool Use & Agents**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Agent loop**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Implement a framework-free plan → act → observe → stop loop.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Agent loop**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Agent+loop+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] plan/act/observe
- [ ] state
- [ ] stop conditions
- [ ] max steps

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Implement a framework-free plan → act → observe → stop loop.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Every agent needs a clear stop condition.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 054 — LangChain
**Phase 6 — Tool Use & Agents**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → LangChain**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Port the tool assistant to LangChain and compare abstraction vs raw code.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **LangChain**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=LangChain+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] models
- [ ] tools
- [ ] retrievers
- [ ] structured outputs

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Port the tool assistant to LangChain and compare abstraction vs raw code.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Know what the framework is doing underneath the abstraction.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 055 — LangGraph
**Phase 6 — Tool Use & Agents**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → LangGraph**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build a three-node stateful workflow with explicit state.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **LangGraph**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=LangGraph+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] state
- [ ] nodes
- [ ] edges
- [ ] checkpoints

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build a three-node stateful workflow with explicit state.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Explicit state makes complex agent workflows easier to debug.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 056 — Memory
**Phase 6 — Tool Use & Agents**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Memory**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Add short-term conversation state and a small persistent preference store.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Memory**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Memory+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] short-term state
- [ ] long-term memory
- [ ] knowledge/RAG distinction
- [ ] privacy

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Add short-term conversation state and a small persistent preference store.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Memory is not a second name for RAG.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 057 — Human approval
**Phase 6 — Tool Use & Agents**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Human approval**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Require approval before an externally visible or risky tool action.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Human approval**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Human+approval+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] approval gates
- [ ] risky actions
- [ ] escalation
- [ ] audit trail

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Require approval before an externally visible or risky tool action.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Give agents authority only where the business case requires it.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 058 — Multi-agent
**Phase 6 — Tool Use & Agents**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Multi-agent**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Compare one agent against a supervisor + two specialists on the same tasks.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Multi-agent**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Multi-agent+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] router
- [ ] specialists
- [ ] supervisor
- [ ] cost/quality comparison

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Compare one agent against a supervisor + two specialists on the same tasks.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Benchmark against a single agent; complexity has a cost.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 059 — Agent evals
**Phase 6 — Tool Use & Agents**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Agent evals**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Create 15 tasks and measure success, tool accuracy, steps, latency and cost.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Agent evals**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Agent+evals+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] task success
- [ ] tool accuracy
- [ ] step count
- [ ] cost/latency

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Create 15 tasks and measure success, tool accuracy, steps, latency and cost.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Count unnecessary tool calls and steps.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 060 — Checkpoint 6
**Phase 6 — Tool Use & Agents**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Checkpoint 6**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Ship Mini Project 5: bounded research agent with tools, state and evals.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Checkpoint 6**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Checkpoint+6+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] explain the phase concept
- [ ] know the main components
- [ ] know one failure mode
- [ ] connect it to production

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Ship Mini Project 5: bounded research agent with tools, state and evals.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Checkpoint rule: do not move forward because the calendar says so. Move forward when you can demo the artifact, explain the architecture without notes, and name the main failure modes.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

### 🏁 PHASE CHECKPOINT
- [ ] 5-minute no-notes explanation
- [ ] Demo the artifact
- [ ] Write 3 weaknesses to revisit
- [ ] Do not start the next phase until the artifact works

## Day 061 — MCP concepts
**Phase 7 — MCP & Integration**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → MCP concepts**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Map your existing tools to MCP tools/resources/prompts and draw the client-server flow.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **MCP concepts**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=MCP+concepts+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] MCP client/server
- [ ] tools
- [ ] resources
- [ ] prompts

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Map your existing tools to MCP tools/resources/prompts and draw the client-server flow.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
MCP is an integration protocol, not a substitute for system design.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 062 — MCP server
**Phase 7 — MCP & Integration**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → MCP server**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Expose two safe typed developer tools through a local MCP server.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **MCP server**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=MCP+server+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] tool definitions
- [ ] input schemas
- [ ] safe execution
- [ ] local testing

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Expose two safe typed developer tools through a local MCP server.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Keep tools narrow and permission-aware.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 063 — MCP client
**Phase 7 — MCP & Integration**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → MCP client**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Connect your agent to the MCP server and trace discovery/execution.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **MCP client**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=MCP+client+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] tool discovery
- [ ] execution flow
- [ ] tracing
- [ ] failure handling

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Connect your agent to the MCP server and trace discovery/execution.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Trace tool discovery and execution like an API call.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 064 — Tool security
**Phase 7 — MCP & Integration**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Tool security**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Add tool allow-lists, validation and confirmation for dangerous operations.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Tool security**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Tool+security+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] allow-lists
- [ ] authentication
- [ ] sandboxing
- [ ] confirmation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Add tool allow-lists, validation and confirmation for dangerous operations.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Least privilege is the central agent security principle.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 065 — Agent + RAG
**Phase 7 — MCP & Integration**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Agent + RAG**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build routing that chooses retrieval vs tool calls.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Agent + RAG**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Agent+%2B+RAG+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] retrieve vs tool routing
- [ ] shared context
- [ ] citations
- [ ] tool limits

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build routing that chooses retrieval vs tool calls.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Keep the tool set small enough that routing is testable.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 066 — Research agent
**Phase 7 — MCP & Integration**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Research agent**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build search → retrieve → verify → synthesize → cite.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Research agent**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Research+agent+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] discover
- [ ] retrieve
- [ ] verify
- [ ] synthesize/cite

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build search → retrieve → verify → synthesize → cite.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Separate discovery from verification.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 067 — Data/code agent
**Phase 7 — MCP & Integration**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Data/code agent**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Build a sandboxed CSV analysis agent.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Data/code agent**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Data%2Fcode+agent+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] file inspection
- [ ] safe Python
- [ ] structured results
- [ ] sandbox boundary

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Build a sandboxed CSV analysis agent.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Sandbox execution; never trust arbitrary generated code.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 068 — Agent UX
**Phase 7 — MCP & Integration**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Agent UX**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Add progress events, intermediate status, citations and useful errors.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Agent UX**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Agent+UX+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] progress events
- [ ] intermediate status
- [ ] citations
- [ ] useful errors

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Add progress events, intermediate status, citations and useful errors.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Users need visibility into long-running agent work.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 069 — Reliability sprint
**Phase 7 — MCP & Integration**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Reliability sprint**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Intentionally break the agent and add timeouts, step limits and recovery.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Reliability sprint**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Reliability+sprint+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] timeouts
- [ ] loop limits
- [ ] checkpoint/recovery
- [ ] fallback

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Intentionally break the agent and add timeouts, step limits and recovery.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
A reliable agent knows when to stop.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 070 — Checkpoint 7
**Phase 7 — MCP & Integration**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R13 → Checkpoint 7**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Ship Mini Project 6: RAG + tools + MCP + evaluation + threat model.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Checkpoint 7**
- Playlist: https://www.youtube.com/playlist?list=PLj0jSMWhCsdnsI6Pklh9Igru9dmUrHIxl
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Checkpoint+7+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] explain the phase concept
- [ ] know the main components
- [ ] know one failure mode
- [ ] connect it to production

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Ship Mini Project 6: RAG + tools + MCP + evaluation + threat model.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Checkpoint rule: do not move forward because the calendar says so. Move forward when you can demo the artifact, explain the architecture without notes, and name the main failure modes.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

### 🏁 PHASE CHECKPOINT
- [ ] 5-minute no-notes explanation
- [ ] Demo the artifact
- [ ] Write 3 weaknesses to revisit
- [ ] Do not start the next phase until the artifact works

## Day 071 — When to fine-tune
**Phase 8 — Fine-Tuning**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R15 → When to fine-tune**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Choose one narrow task and justify prompt vs RAG vs fine-tuning.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **When to fine-tune**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=When+to+fine-tune+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] prompting vs RAG vs tuning
- [ ] task adaptation
- [ ] data requirements
- [ ] maintenance cost

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Choose one narrow task and justify prompt vs RAG vs fine-tuning.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Don't fine-tune changing facts; use retrieval for knowledge.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 072 — Dataset design
**Phase 8 — Fine-Tuning**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R15 → Dataset design**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Create a small high-quality instruction dataset with train/validation split.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Dataset design**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Dataset+design+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] instruction examples
- [ ] chat template
- [ ] train/validation split
- [ ] contamination

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Create a small high-quality instruction dataset with train/validation split.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Consistency and correctness beat a huge noisy dataset.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 073 — Transformers workflow
**Phase 8 — Fine-Tuning**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R15 → Transformers workflow**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Fine-tune a tiny open model and inspect tokenizer/model/training flow.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Transformers workflow**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Transformers+workflow+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] tokenizer
- [ ] model
- [ ] dataset
- [ ] training loop

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Fine-tune a tiny open model and inspect tokenizer/model/training flow.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Start tiny so you can iterate quickly.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 074 — LoRA
**Phase 8 — Fine-Tuning**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R15 → LoRA**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Run LoRA and compare trainable vs total parameters.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **LoRA**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=LoRA+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] adapter layers
- [ ] rank/alpha
- [ ] trainable parameters
- [ ] merge vs adapter serving

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Run LoRA and compare trainable vs total parameters.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Always compare trainable parameters and memory footprint.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 075 — QLoRA
**Phase 8 — Fine-Tuning**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R15 → QLoRA**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Run a small QLoRA experiment if hardware allows; record memory usage.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **QLoRA**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=QLoRA+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] 4/8-bit quantization
- [ ] memory trade-offs
- [ ] compute dtype
- [ ] hardware constraints

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Run a small QLoRA experiment if hardware allows; record memory usage.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Measure memory, not just whether training finished.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 076 — SFT
**Phase 8 — Fine-Tuning**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R15 → SFT**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Train an SFT adapter with a correct chat template and evaluation set.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **SFT**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=SFT+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] supervised objective
- [ ] chat formatting
- [ ] packing
- [ ] evaluation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Train an SFT adapter with a correct chat template and evaluation set.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Bad examples often teach the model bad habits.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 077 — Fine-tuning eval
**Phase 8 — Fine-Tuning**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R15 → Fine-tuning eval**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Compare base vs fine-tuned model on the same held-out examples.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Fine-tuning eval**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Fine-tuning+eval+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] held-out set
- [ ] base baseline
- [ ] qualitative failures
- [ ] regression checks

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Compare base vs fine-tuned model on the same held-out examples.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Always compare against the base model.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 078 — DPO
**Phase 8 — Fine-Tuning**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R15 → DPO**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Understand preference pairs and run/read a tiny DPO experiment.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **DPO**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=DPO+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] preference pairs
- [ ] reference policy
- [ ] DPO intuition
- [ ] when to use

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Understand preference pairs and run/read a tiny DPO experiment.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Master SFT + evaluation before spending time on preference optimization.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 079 — Distillation
**Phase 8 — Fine-Tuning**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R15 → Distillation**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Generate teacher examples and train/evaluate a smaller student model.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Distillation**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Distillation+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] teacher/student
- [ ] synthetic data
- [ ] quality-cost trade-off
- [ ] student evaluation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Generate teacher examples and train/evaluate a smaller student model.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
The useful question is quality per dollar, not model size alone.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 080 — Checkpoint 8
**Phase 8 — Fine-Tuning**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R15 → Checkpoint 8**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Ship Mini Project 7: LoRA/QLoRA adapter + evaluation report.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Checkpoint 8**
- Playlist: https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Checkpoint+8+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] explain the phase concept
- [ ] know the main components
- [ ] know one failure mode
- [ ] connect it to production

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Ship Mini Project 7: LoRA/QLoRA adapter + evaluation report.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Checkpoint rule: do not move forward because the calendar says so. Move forward when you can demo the artifact, explain the architecture without notes, and name the main failure modes.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

### 🏁 PHASE CHECKPOINT
- [ ] 5-minute no-notes explanation
- [ ] Demo the artifact
- [ ] Write 3 weaknesses to revisit
- [ ] Do not start the next phase until the artifact works

## Day 081 — Model serving
**Phase 9 — Serving & LLM Systems**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R1/R5 → Model serving**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Serve an open model and separate model-server concerns from application code.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Model serving**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvLNOxX0RfndiYSt1Le9azze
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Model+serving+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] model server vs app
- [ ] GPU memory
- [ ] batching
- [ ] API boundary

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Serve an open model and separate model-server concerns from application code.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Treat the model server as an internal dependency.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 082 — vLLM
**Phase 9 — Serving & LLM Systems**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R1/R5 → vLLM**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Run a model with vLLM and call it from your FastAPI service.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **vLLM**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvLNOxX0RfndiYSt1Le9azze
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=vLLM+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] OpenAI-compatible server
- [ ] continuous batching
- [ ] throughput
- [ ] deployment shape

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Run a model with vLLM and call it from your FastAPI service.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Benchmark throughput under realistic concurrency.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 083 — Quantization/KV cache
**Phase 9 — Serving & LLM Systems**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R1/R5 → Quantization/KV cache**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Benchmark two memory/throughput configurations and explain the trade-off.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Quantization/KV cache**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvLNOxX0RfndiYSt1Le9azze
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Quantization%2FKV+cache+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] weights memory
- [ ] KV cache memory
- [ ] context length
- [ ] batch trade-offs

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Benchmark two memory/throughput configurations and explain the trade-off.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Long context can become a memory problem before a quality problem.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 084 — Load testing
**Phase 9 — Serving & LLM Systems**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R1/R5 → Load testing**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Load-test the model endpoint and record p50/p95, throughput and saturation.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Load testing**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvLNOxX0RfndiYSt1Le9azze
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Load+testing+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] concurrency
- [ ] requests/sec
- [ ] p50/p95
- [ ] saturation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Load-test the model endpoint and record p50/p95, throughput and saturation.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Find the saturation point, not just a single fast request.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 085 — Docker
**Phase 9 — Serving & LLM Systems**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R1/R5 → Docker**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Containerize the application with pinned dependencies and a health check.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Docker**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvLNOxX0RfndiYSt1Le9azze
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Docker+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] Dockerfile
- [ ] dependency pinning
- [ ] health checks
- [ ] environment variables

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Containerize the application with pinned dependencies and a health check.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Reproducibility is an engineering feature.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 086 — AWS basics
**Phase 9 — Serving & LLM Systems**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R1/R5 → AWS basics**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Deploy a lightweight service/supporting component and practise IAM-safe access.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **AWS basics**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvLNOxX0RfndiYSt1Le9azze
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=AWS+basics+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] EC2
- [ ] IAM
- [ ] networking
- [ ] logs/secrets

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Deploy a lightweight service/supporting component and practise IAM-safe access.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Learn the cloud primitives your architecture actually needs.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 087 — Cloud architecture
**Phase 9 — Serving & LLM Systems**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R1/R5 → Cloud architecture**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Draw and cost an API → app → model → vector DB → observability architecture.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Cloud architecture**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvLNOxX0RfndiYSt1Le9azze
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Cloud+architecture+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] API/app/model/vector DB
- [ ] network boundaries
- [ ] scaling
- [ ] cost trade-offs

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Draw and cost an API → app → model → vector DB → observability architecture.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Architecture interviews reward trade-offs, not service memorization.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 088 — Production observability
**Phase 9 — Serving & LLM Systems**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R1/R5 → Production observability**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Add end-to-end logs, metrics, traces and cost attribution.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Production observability**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvLNOxX0RfndiYSt1Le9azze
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Production+observability+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] logs
- [ ] metrics
- [ ] traces
- [ ] alerts/cost attribution

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Add end-to-end logs, metrics, traces and cost attribution.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Every request should be traceable end-to-end.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 089 — Reliability
**Phase 9 — Serving & LLM Systems**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R1/R5 → Reliability**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Simulate provider/model/vector DB failures and implement graceful degradation.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Reliability**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvLNOxX0RfndiYSt1Le9azze
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Reliability+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] rate limits
- [ ] queues
- [ ] circuit breakers
- [ ] graceful degradation

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Simulate provider/model/vector DB failures and implement graceful degradation.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Design failure paths before users discover them.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 090 — Checkpoint 9
**Phase 9 — Serving & LLM Systems**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **R1/R5 → Checkpoint 9**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Ship deployed observable LLM service + load-test report + one-page system design.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Checkpoint 9**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvLNOxX0RfndiYSt1Le9azze
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Checkpoint+9+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] explain the phase concept
- [ ] know the main components
- [ ] know one failure mode
- [ ] connect it to production

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Ship deployed observable LLM service + load-test report + one-page system design.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Checkpoint rule: do not move forward because the calendar says so. Move forward when you can demo the artifact, explain the architecture without notes, and name the main failure modes.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

### 🏁 PHASE CHECKPOINT
- [ ] 5-minute no-notes explanation
- [ ] Demo the artifact
- [ ] Write 3 weaknesses to revisit
- [ ] Do not start the next phase until the artifact works

## Day 091 — Architecture
**Phase 10 — Capstone**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **All → Architecture**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Choose a real capstone problem and write requirements, metrics and threat model.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Architecture**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Architecture+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] requirements
- [ ] success metrics
- [ ] threat model
- [ ] component boundaries

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Choose a real capstone problem and write requirements, metrics and threat model.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Choose a real problem, not another generic chatbot.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 092 — Data layer
**Phase 10 — Capstone**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **All → Data layer**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Implement repeatable ingestion, metadata, chunking and indexing.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Data layer**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Data+layer+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] ingestion
- [ ] metadata
- [ ] chunking
- [ ] indexing

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Implement repeatable ingestion, metadata, chunking and indexing.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Make ingestion repeatable from a clean command.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 093 — Intelligence layer
**Phase 10 — Capstone**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **All → Intelligence layer**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Implement RAG + routing + structured outputs + citations.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Intelligence layer**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Intelligence+layer+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] RAG
- [ ] routing
- [ ] structured output
- [ ] citations

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Implement RAG + routing + structured outputs + citations.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Keep the happy path simple before adding autonomy.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 094 — API layer
**Phase 10 — Capstone**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **All → API layer**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Expose the complete system with FastAPI, streaming and schemas.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **API layer**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=API+layer+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] FastAPI
- [ ] streaming
- [ ] schemas
- [ ] auth boundary

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Expose the complete system with FastAPI, streaming and schemas.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Document request/response examples.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 095 — Evaluation
**Phase 10 — Capstone**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **All → Evaluation**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Run a full golden-set evaluation and save baseline numbers.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Evaluation**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Evaluation+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] golden set
- [ ] retrieval metrics
- [ ] answer metrics
- [ ] baseline

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Run a full golden-set evaluation and save baseline numbers.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Never call a system production-ready without numbers.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 096 — Observability
**Phase 10 — Capstone**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **All → Observability**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Add traces, latency, cost and failure diagnostics.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Observability**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Observability+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] traces
- [ ] cost
- [ ] latency
- [ ] failure diagnostics

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Add traces, latency, cost and failure diagnostics.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Show what happened, not just that something happened.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 097 — Performance
**Phase 10 — Capstone**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **All → Performance**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Improve one quality metric and one performance metric using measurements.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Performance**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Performance+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] caching
- [ ] reranking
- [ ] concurrency
- [ ] model selection

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Improve one quality metric and one performance metric using measurements.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Measure before optimizing.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 098 — Deployment
**Phase 10 — Capstone**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **All → Deployment**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Deploy a reproducible Dockerized version with CI.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Deployment**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Deployment+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] Docker
- [ ] model serving
- [ ] CI
- [ ] reproducibility

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Deploy a reproducible Dockerized version with CI.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
One-command reproducibility is a strong portfolio signal.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 099 — Portfolio
**Phase 10 — Capstone**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **All → Portfolio**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Write README, architecture diagram, demo script and 10 interview questions.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Portfolio**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Portfolio+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] README
- [ ] architecture diagram
- [ ] demo
- [ ] interview questions

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Write README, architecture diagram, demo script and 10 interview questions.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
Your README should let a stranger understand the system in five minutes.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

## Day 100 — Final demo
**Phase 10 — Capstone**

### ⏱ 2-hour schedule
- [ ] 00:00–00:10 Recall yesterday
- [ ] 00:10–00:45 YouTube — **All → Final demo**
- [ ] 00:45–01:00 Active recall / notes
- [ ] 01:00–01:50 Build — Record a 5–10 minute demo and write the next 90-day specialization roadmap.
- [ ] 01:50–02:00 Test + Git commit + 3-line log

### 🎥 Video checkpoint
- [ ] Watch **30–35 min** on: **Final demo**
- Playlist: https://www.youtube.com/playlist?list=PLdpzxOOAlwvL4VhhpTiIUr-i_djrXGB22
- Exact-topic YouTube search: https://www.youtube.com/results?search_query=Final+demo+LLM+engineering+tutorial

### 📚 What to learn in detail
- [ ] retrospective
- [ ] architecture explanation
- [ ] trade-offs
- [ ] next specialization

### 🧠 Recall checklist
- [ ] Explain the main concept without notes.
- [ ] Explain one failure mode / trade-off.
- [ ] Explain where this appears in a production LLM system.

### 🛠 Build checklist
- [ ] Record a 5–10 minute demo and write the next 90-day specialization roadmap.
- [ ] Add a test / sanity check.
- [ ] Save artifact to Git.

### 💡 Tip
The goal is not finishing 100 checkboxes; it is becoming able to ship LLM systems.

### ✅ Definition of Done
- [ ] I can explain it without the video.
- [ ] The artifact runs / expected result exists.
- [ ] Git commit + 3-line learning log completed.

### 🏁 PHASE CHECKPOINT
- [ ] 5-minute no-notes explanation
- [ ] Demo the artifact
- [ ] Write 3 weaknesses to revisit
- [ ] Do not start the next phase until the artifact works
