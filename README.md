# GenAI Delivery Support Router

## 🎯 Propósito do Projeto
Este projeto tem como objetivo desenvolver um sistema de **classificação de intenções** para mensagens de usuários em um contexto de atendimento ao cliente (delivery/restaurantes). O foco é criar um modelo pequeno, específico e avaliável que possa rotear mensagens para fluxos de resposta apropriados.

**Cenário de Uso:**
Classificar mensagens de usuários em categorias como:
- Atraso no pedido
- Pedido cancelado
- Item faltante
- Cobrança indevida
- Alteração de endereço
- Dúvida geral

## 🛠️ Stack Técnica (Planejada)
- **Linguagem:** Python
- **Modelagem:** Modelos pré-treinados (Hugging Face) com ajuste fino leve (LoRA/QLoRA).
- **Baseline:** Classificação por similaridade ou modelo zero-shot.
- **Avaliação:** Acurácia, Macro-F1, Matriz de Confusão.
- **API:** FastAPI (para inferência).

## 📂 Estrutura do Repositório (Futuro)
- `data/`: Dataset pequeno e documentado.
- `notebooks/`: Exploração e treinamento.
- `src/`: Código fonte (treinamento, inferência, API).
- `tests/`: Testes unitários.

## 🚀 Como Executar (Em breve)
Instruções de instalação e uso serão adicionadas após o desenvolvimento do pipeline.
