# Case Suno — Academy x Finance

Pipeline de IA baseado em grafo com estado (LangGraph) para adaptar documentos financeiros
densos (atas do Copom, fatos relevantes CVM, releases trimestrais B3) em 3 níveis de
sofisticação x 3 formatos, com um avaliador híbrido de rigor conceitual e fidelidade factual.

## Status
Fase 1 (Setup) em andamento.

## Stack
- Python + LangGraph
- Gemini API (google-genai) — tier gratuito
- spaCy, textstat, pytest
- Streamlit (interface)

## Estrutura
- `/pipeline` — grafo de geração (extração, adaptação por audiência, síntese de formato)
- `/evaluator` — avaliador híbrido (legibilidade, densidade de termos, factualidade)
- `/interface` — dashboard Streamlit
- `/docs` — documentação e relatório final
