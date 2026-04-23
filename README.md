## 📚 Resources

### Code from Unsloth
- [Fine-tune Qwen (Unsloth Docs)](https://unsloth.ai/docs/models/qwen3.5/fine-tune)

### Tutorial
- [Unsloth Fine-tuning Tutorial](https://www.youtube.com/watch?v=Lt7KrFMcCis)

### Unsloth Official
- [Installation Guide (Google Colab)](https://unsloth.ai/docs/get-started/install/google-colab)

---

## 🔧 When to use LoRA?

**Best for:**
- Strict output formats (JSON, SQL, templates)
- Tone/style control (brand voice, concise answers)
- Domain-specific reasoning patterns (how to interpret inputs)
- Reducing prompt complexity (shorter prompts, stable outputs)
- Latency/cost constraints (less context → cheaper/faster)

**Example**

You want:
- Always-valid JSON responses  
- Specific field names and ordering  
- Consistent handling of edge cases  

👉 LoRA helps enforce consistent and reliable behavior.

---

## 📚 When to use RAG?

Use RAG when the problem is **knowledge**, not behavior.

**Best for:**
- Large or changing corpora (docs, wikis, tickets)
- Up-to-date information (policies, prices, releases)
- Citations / grounding (show sources)
- Easy updates (re-index instead of retrain)

**Example**

You want:
- Answers from your company documents  
- With citations  
- Updated daily  

👉 RAG wins — no retraining needed.


## 🎯 Output Format Reliability with LoRA

close, but not 100%.


## 🧠 What LoRA actually gives you

With a well-trained LoRA:
- ✅ Very high consistency (often 95–99%)
- ✅ Much better than prompt-only approaches
- ❌ Not a hard guarantee

---

## ⚠️ Why it’s not 100%

Even with LoRA, the model is still:
- Probabilistic
- Influenced by input phrasing
- Sensitive to edge cases

So occasionally you may see:
- Extra text
- Missing fields
- Slight format drift

---

LoRA → generate → validate → retry if needed



## 📝 Credit

Content summarized with assistance from ChatGPT.
