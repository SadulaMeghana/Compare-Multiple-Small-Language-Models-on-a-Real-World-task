# Compare-Multiple-Small-Language-Models-on-a-Real-World-task
This project compares multiple Small Language Models (SLMs) — Qwen 3:1.7B, Llama 3.2:1B, and Phi 3:3.8B — on a real-world resume analysis task to evaluate their reasoning, accuracy, speed, and practical usefulness.


````markdown
# Compare Multiple SLMs on a Real-World Task

## Project Title
Compare Multiple Small Language Models (SLMs) on a Real-World Task

---

# Objective

The goal of this project is to compare multiple Small Language Models (SLMs) on a real-world task and evaluate their performance based on quality, speed, reasoning ability, instruction following, hallucination handling, and practical usefulness.

This project helps understand how different SLMs behave in realistic scenarios and how benchmark reputation compares with actual human experience.

---

# Models Compared

| Model | Size | Type |
|---|---|---|
| Qwen 3 | 1.7B | Small Language Model |
| Llama 3.2 | 1B | Small Language Model |
| Phi 3 | 3.8B | Small Language Model |

---

# Tools & Environment

- Ollama
- Local System Testing
- Prompt-based Evaluation
- Manual Human Evaluation

---

# Real-World Task Used

## Task:
Resume Analysis for an AI Engineer Role

The models were asked to:
- Analyze a resume
- Identify strengths and weaknesses
- Suggest improvements
- Evaluate ATS friendliness
- Provide real-world hiring feedback

---

# Evaluation Criteria

The models were compared based on:

- Response clarity
- Instruction following
- Reasoning quality
- Hallucination tendency
- Accuracy
- Practical usefulness
- Response speed
- Handling ambiguity
- Human-like understanding

---

# Test Prompt

```text
Analyze this resume for an AI Engineer role.
Provide:
1. Strengths
2. Weaknesses
3. ATS score estimation
4. Missing skills
5. Improvement suggestions
6. Final hiring recommendation
```

---

# Model Comparison

## 1. Qwen 3 : 1.7B

### Strengths
- Fast response generation
- Good instruction following
- Decent reasoning for a small model
- Structured output formatting

### Weaknesses
- Sometimes generic responses
- Limited deep technical analysis
- May repeat points

### Overall Performance
Qwen 3 performed well for lightweight tasks and gave balanced responses with good formatting.

---

## 2. Llama 3.2 : 1B

### Strengths
- Very lightweight and fast
- Simple and easy-to-understand responses
- Good for basic tasks

### Weaknesses
- Less detailed analysis
- Weak reasoning depth
- Lower contextual understanding
- More generic suggestions

### Overall Performance
Llama 3.2 handled basic resume analysis but struggled with deeper evaluation and nuanced reasoning.

---

## 3. Phi 3 : 3.8B

### Strengths
- Strong reasoning ability
- Better contextual understanding
- More practical real-world feedback
- Detailed analysis

### Weaknesses
- Slightly slower than smaller models
- Occasionally overconfident

### Overall Performance
Phi 3 delivered the most useful and realistic analysis among the tested SLMs.

---

# Comparison Summary

| Criteria | Qwen 3:1.7B | Llama 3.2:1B | Phi 3:3.8B |
|---|---|---|---|
| Speed | High | Very High | Medium |
| Reasoning | Medium | Low | High |
| Instruction Following | Good | Average | Very Good |
| Detail Level | Medium | Low | High |
| Hallucination Risk | Medium | Medium | Low |
| Practical Usefulness | Good | Basic | Excellent |

---

# Observations

- Larger SLMs generally provided better reasoning and contextual understanding.
- Smaller models were faster but less detailed.
- Benchmark popularity did not always match real-world usefulness.
- Phi 3 showed the strongest balance between reasoning and practical output.
- Llama 3.2 was useful for lightweight tasks but weaker in complex evaluation.

---

# Final Recommendation

| Use Case | Recommended Model |
|---|---|
| Fast lightweight tasks | Llama 3.2:1B |
| Balanced everyday usage | Qwen 3:1.7B |
| Best real-world reasoning | Phi 3:3.8B |

### Best Overall Model
**Phi 3:3.8B**

Reason:
It provided the clearest, most practical, and most context-aware responses during testing.

---

# Key Learnings

- Human evaluation is important alongside benchmarks.
- Smaller models can still perform well for focused tasks.
- Real-world testing reveals strengths not visible in leaderboard rankings.
- Model size impacts reasoning depth and contextual understanding.

---

# Future Improvements

- Test on multiple task categories
- Add coding and reasoning benchmarks
- Include latency and memory usage metrics
- Compare cloud-hosted vs local inference

---

# Conclusion

This project successfully compared multiple Small Language Models on a practical real-world task. The experiment showed that different SLMs have different strengths depending on the use case. While lightweight models provide speed and efficiency, larger SLMs offer stronger reasoning and more reliable outputs.

The comparison demonstrated that selecting the best model depends on the actual application requirements rather than benchmark rankings alone.

---

# References

- Ollama
- Qwen Model Family
- Llama Model Family
- Phi Model Family
- OpenRouter Rankings

---
````
