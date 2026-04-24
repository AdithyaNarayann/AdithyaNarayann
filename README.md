<div align="center">

## ᴀɪ sʏsᴛᴇᴍs · ʟʟᴍ ᴘɪᴘᴇʟɪɴᴇs · ʙᴀᴄᴋᴇɴᴅ ᴅᴇᴄɪsɪᴏɴ ʟᴏɢɪᴄ

<p align="center">
  <img src="https://img.shields.io/badge/1st%20Place-State%20Level%20%C2%B7%20Industry%205.0%20Hackathon%20%C2%B7%20%E2%82%B925K-334155?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Selected-State%20Level%20%C2%B7%20IEDC%20Startup%20Summit%20'26-334155?style=for-the-badge"/>
</p>

</div>

---

I build AI systems that make decisions, not just generate text — structured LLM pipelines, multi-agent orchestration, and backend decision logic where state persists, failures are handled, and outputs are deterministic.

## Engineering

<table>
<tr><td>

**[Prompta](https://github.com/AdithyaNarayann/prompta-public)** &nbsp;—&nbsp; LLM Prompt Diagnostics Engine

Multi-label DeBERTa classifier detecting five failure modes — Instruction Conflict, Format Pressure, Context Starvation, Scope Ambiguity, Role Collapse — with per-mode thresholds and threshold-gated routing to expensive LLM reasoning. Intent extraction decouples user goal from prompt text before classification. Targeted, traceable rewrites per failure mode. Treats prompts as systems with failure modes, not strings to rephrase.

`DeBERTa` `FastAPI` `Sentence-Transformers` `OpenRouter` `React` `AsyncIO`

</td></tr>

<tr><td>

**[TradeMind](#)** &nbsp;—&nbsp; Negotiation Intelligence API

Replaces black-box LLM negotiation with fully deterministic pricing logic. Bayesian WTP estimation with real-time posterior updates. Phase-gated concession curves across opening, active, and closing phases. Session-aware buyer archetype memory that persists across the full negotiation lifecycle. LLM stays entirely out of the pricing path — structured JSON outputs, zero hallucination.

`FastAPI` `PostgreSQL` `Bayesian Engine` `OpenRouter` `React`

</td></tr>
<tr><td>

**[Spot Difference](https://github.com/AdithyaNarayann/Spot-Difference)** &nbsp;—&nbsp; Visual Change Detection Pipeline

SAM v1 (ViT-H, 4B params) for automatic instance segmentation — no manual annotations. Multi-signal similarity fusion: OpenCLIP 512-dim embeddings, IoU, shape descriptors, and color histograms via a weighted score matrix. Hungarian algorithm for globally optimal object-pair assignment — not greedy. Confidence-stratified JSON reports, pipeline-integration ready.

`SAM` `OpenCLIP` `PyTorch` `OpenCV` `Hungarian Algorithm`

</td></tr>
<tr><td>

**[Pragati](https://github.com/AdithyaNarayann/pragati)** &nbsp;—&nbsp; AI DPR Analysis Platform &nbsp;·&nbsp; *3rd Place, SIH Internal*

Full pipeline: OCR → PDF parse → TF-IDF extraction → XGBoost classifier with confidence scoring. 91% accuracy on feasibility classification. Governance compliance dashboard with real-time scoring and structured report output.

`XGBoost` `pytesseract` `scikit-learn` `Flask` `React`

</td></tr>
</table>

## Built With

```yaml
stack:
  backend:  [Python, FastAPI, PostgreSQL, SQLAlchemy, Pydantic, Redis, AsyncIO, httpx]
  ai_ml:    [PyTorch, Hugging Face Transformers, scikit-learn]
  cv:       [OpenCV, Tesseract OCR, SAM, OpenCLIP]
```

## Reach Me

[Email](mailto:adithyanarayanvs@gmail.com) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/adithyanarayanvs) &nbsp;·&nbsp; [X](https://x.com/adithyanarayanv) <img src="https://komarev.com/ghpvc/?username=AdithyaNarayann&color=6e7681&style=flat-square&label=views" align="right" />
