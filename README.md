# dio-metodo-transfer-learning-

# Cálculo de Métricas de Avaliação (Classificação Binária)

Projeto didático para calcular as métricas clássicas a partir de **matriz de confusão** (VP, VN, FP, FN) ou de vetores `y_true` e `y_pred`:

- **Acurácia** = (VP + VN) / N  
- **Sensibilidade (Recall)** = VP / (VP + FN)  
- **Especificidade** = VN / (VN + FP)  
- **Precisão (Precision)** = VP / (VP + FP)  
- **F1-score** = 2 × (Precisão × Recall) / (Precisão + Recall)

> N = VP + VN + FP + FN

---

## Como rodar

### Opção 1 — Google Colab (mais simples)
1. Abra o Colab e crie um notebook.
2. Cole o conteúdo de `metrics.py` em uma célula **ou** use:
   ```python
   %%writefile metrics.py
   # (cole aqui o conteúdo do arquivo)

   !python metrics.py
