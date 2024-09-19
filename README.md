

# CP-04 IA E MACHINE LEARNING

## Turma:2TDCF

- Defesa cibernetica - 2024

## grupo:Athens

- Eduardo Dos Santos Almeida
- Júlia Barboza Brunelli
- Vinícius Passeau de Sá
- Victoria Oliveira Ventrilho

## Introdução

Este repositório contém um notebook Jupyter que explora a geração de texto utilizando modelos de linguagem de grande escala (LLMs), com foco em:

- **Geração de tokens**: O processo passo a passo de como os modelos de linguagem geram novos tokens com base em entradas fornecidas.
- **Dispositivos de processamento**: Diferenças de execução em CPU e GPU e como verificar a disponibilidade de uma GPU.
- **Memória de conversa**: Como os modelos "lembram" o que foi dito em uma sequência de interação e como armazenam essas informações para gerar a próxima parte do texto.

### Principais tópicos abordados:

1. Verificação e utilização de **GPU** (se disponível) para aceleração do processamento.
2. Utilização da biblioteca **Transformers** da Hugging Face para carregar e executar modelos de linguagem.
3. Processo de geração de texto, **token a token**, com uma visualização detalhada dos tokens gerados e suas respectivas pontuações.
4. Movimentação de dados entre dispositivos (CPU e GPU) utilizando o método **.to(device)**.

## Estrutura do Notebook

O notebook está organizado da seguinte forma:

1. **Verificando a disponibilidade de GPU**: Um exemplo de como identificar o dispositivo disponível e escolher entre CPU e GPU.
2. **Carregando o modelo**: Utilizando a tarefa de geração de texto com o modelo TinyLlama.
3. **Analisando a geração de tokens**: Investigando o processo de geração de texto token a token, incluindo a obtenção de pontuações de cada token.
4. **Dispositivo e memória**: A importância de manter a consistência de dispositivos entre dados e modelos (CPU vs GPU) para evitar erros.

