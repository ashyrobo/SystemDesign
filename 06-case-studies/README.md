# ML System Design Case Studies

This directory contains comprehensive case studies of real-world ML systems at FAANG scale, designed for Senior→Staff Applied ML interview preparation.

## Case Studies

### [Netflix Recommendation Ranking System](./netflix-recommendation-ranking.md)
**Scale**: 200M+ users, 80% content consumption through recommendations  
**Challenge**: Personalized ranking with diversity, business objectives, real-time constraints  
**Key Focus**: Two-tower architecture, cold start, position bias, A/B testing

### [Meta Fraud Detection System](./meta-fraud-detection.md) 
**Scale**: Billions of daily transactions, <100ms real-time decisioning  
**Challenge**: Adversarial environment, class imbalance, evolving attack patterns  
**Key Focus**: Ensemble methods, feature engineering, adversarial ML, cost-sensitive learning

### [Google Search Relevance System](./google-search-relevance.md)
**Scale**: 8+ billion queries daily, sub-200ms global latency  
**Challenge**: Query understanding, massive index retrieval, multi-objective ranking  
**Key Focus**: BERT integration, learning-to-rank, distributed systems, evaluation metrics

## What Each Case Study Covers

Following the repo's established format, each case study includes:

1. **Problem Statement** - Business context and technical challenges at FAANG scale
2. **Success Metrics** - Primary KPIs, offline evaluation, online A/B testing considerations  
3. **Data Strategy** - Sources, quality, labeling, feature engineering approaches
4. **Model Architecture** - Algorithm choices, training pipelines, offline/online alignment
5. **Serving Infrastructure** - Latency requirements, caching, fallback systems
6. **Monitoring & Debugging** - Drift detection, incident response, performance tracking
7. **Failure Modes** - Common pitfalls, edge cases, business impact scenarios
8. **Launch Strategy** - Rollout plans, guardrails, risk mitigation
9. **Interview Questions** - 10 rapid-fire Q&A covering system design + Applied ML
10. **Related Topics** - Cross-links to foundational concepts

## Interview Preparation Focus

**System Design Aspects:**
- Architecture scalability and latency optimization
- Data pipeline design and feature stores  
- Monitoring, alerting, and incident response
- A/B testing and gradual rollout strategies

**Applied ML Aspects:**
- Model selection rationale and trade-offs
- Evaluation methodology and metric selection
- Debugging approaches for model performance issues
- Business impact measurement and optimization

**Senior+ Level Considerations:**
- Cross-functional impact (legal, privacy, cost)
- Technical debt and maintenance implications  
- Team scaling and organizational challenges
- Long-term architecture evolution

Each case study balances technical depth with practical implementation details that commonly arise in Staff+ ML engineering interviews.