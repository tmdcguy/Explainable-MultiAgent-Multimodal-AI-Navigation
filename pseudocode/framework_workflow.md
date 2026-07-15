# Algorithm 1: Multi-Agent Navigation Workflow

Input:
Xt = {It, Gt, Mt, Qt, St}

Output:
Yt = {dt*, Et}

1. Acquire multimodal inputs Xt
2. Ft ← PerceptionAgent(Xt)
3. Ct ← ContextReasoningAgent(Ft, Ht−1)
4. Pt ← PlanningAgent(Ct)
5. dt* ← DecisionAgent(Pt, Ct)
6. Et ← ExplainabilityAgent(Ft, dt*)
7. Deliver navigation guidance
8. Update navigation memory
9. Store feedback for continual learning

Return Yt
