# Hi, I’m Russell

I’m a data science student at Pitt. I design experiments and build agents that gather and analyze data.

[Current work](#current-work-and-whats-next) · [Study notebooks and reflections](#study-notebooks-and-reflections)

## Applied data science

- **Data-visualization agent evaluation (CMU 11-768 A2).** In this independent course adaptation, I used human labels and an error taxonomy to diagnose the evaluator’s mistakes. The final evaluator scored 0.8726 macro-MCC on 110 public seed runs, up from 0.5235 at baseline. [Repository](https://github.com/xqzr2000/cmu-11-768-assignment-2) · [Final report](https://github.com/xqzr2000/cmu-11-768-assignment-2/blob/main/report.pdf) · [Walkthrough](https://github.com/xqzr2000/cmu-11-768-assignment-2/blob/main/notebooks/CMU_11_768_Assignment_2_Project_Walkthrough.ipynb)
- **YouTube-SideKick.** A recommendation engine with hand-labeled data, offline ranking experiments, and a Chrome side panel. In a seven-video comparison, 66% of SideKick’s top-ten suggestions and 49% of YouTube’s were labeled good. [Repository](https://github.com/xqzr2000/YouTube-SideKick) · [Ranking experiments](https://github.com/xqzr2000/YouTube-SideKick/blob/main/reports/E4-ranker.md)
- **Russell’s Scout.** A scheduled pipeline that collects, deduplicates, and scores Vancouver job postings and stores them in PostgreSQL. It completed 14 sweeps, seven digests, and seven backups in a week of unattended operation. [Repository](https://github.com/xqzr2000/russells-scout) · [Walkthrough](https://github.com/xqzr2000/russells-scout/blob/main/notebooks/Russells_Scout_Project_Walkthrough.ipynb) · [Run results](https://github.com/xqzr2000/russells-scout/blob/main/docs/phase2-results.md)

## Current work and what's next

- I’m finishing the 124.7M-parameter language model and the SST-5 sentiment experiment. I’m also reworking the three CMU 11-768 walkthrough notebooks, starting with A2, and adding the cloud-walker notebook. The GPT-2 XL-scale run is on hold.
- My next project is a data-analysis agent that can find relevant information and answer questions about real datasets. I’m considering DABStep and the SQLite tasks in Spider 2.0-Lite, with deployment, monitoring, and an A/B test of two harness versions to follow.

## Agent systems and model training

- **Russell’s BaseAgent.** A reusable Python ReAct framework with a data science agent that explores CSVs in Jupyter and returns a summary and a runnable notebook. [Repository](https://github.com/xqzr2000/Russells_BaseAgent)
- **Agent harness (CMU 11-768 A1).** An independent course adaptation using a Docker sandbox to study tool design, context compaction, and token usage. [Repository](https://github.com/xqzr2000/cmu-11-768-assignment-1)
- **Language modeling from scratch (CS336 adaptation).** I trained a 22.7M-parameter Transformer on TinyStories and completed the first training stage of a 124.7M-parameter Llama-style model on FineWeb-Edu. [Repository](https://github.com/xqzr2000/Stanford-CS336-Llama-Adaptation) · [Training results](https://github.com/xqzr2000/Stanford-CS336-Llama-Adaptation/blob/main/CS336_Colab/README.md)
- **Agent reinforcement learning (CMU 11-768 A3).** An independent course adaptation that post-trained Qwen3.5-4B on Modal H100s. On 50 TextCraft tasks, pass@4 went from 14% for the base model to 68% for the step-41 adapter. [Repository](https://github.com/xqzr2000/cmu-11-768-assignment-3) · [Final report](https://github.com/xqzr2000/cmu-11-768-assignment-3/blob/main/docs/Report.md)
- **Mario Ops.** Cloud experiments with Double DQN in Colab, Codespaces, and AWS, plus a vision model that plays from screenshots. [Repository](https://github.com/xqzr2000/Mario_Ops)

## Product prototypes

- **WiseShelf.** A Pitt Blitz prototype for a unified shopping cart with AI-assisted budgeting. [Repository and demo](https://github.com/xqzr2000/Side_Cart_Blitz)
- **SideBuySide.** A Chrome side-panel shopping shelf that collects product cards from retailer pages. [Repository and demo](https://github.com/xqzr2000/SideBuySide_Blitz)
- **Vibe Coded Shopper.** A terminal-based shopping group chat that experiments with different agent personalities. [Repository](https://github.com/xqzr2000/Vibe_Coded_Shopper)
- **Focus Room.** An educational two-agent chat prototype for ADHD screening conversations and researching attention-training resources. [Repository](https://github.com/xqzr2000/Vibe_Coded_ADHD_Game_Room)

## Study notebooks and reflections

My study repository collects the notebooks and longer notes on what I’ve learned and what I’m working to improve. [Notebook index](https://github.com/xqzr2000/Russell-Study-ML/blob/main/README.md#study-notes) · [Learning gaps](https://github.com/xqzr2000/Russell-Study-ML/blob/main/README.md#1-what-im-missing) · [Reflection on AI-assisted development](https://github.com/xqzr2000/Russell-Study-ML/blob/main/README.md#3-no-seriously-did-you-write-the-code)
