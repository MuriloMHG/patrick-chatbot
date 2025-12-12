# Projeto Patrick Estrela Chatbot 🪸

## 💻Ambiente de Execução

Este projeto foi desenvolvido em **Python** e utiliza bibliotecas modernas de **Inteligência Artificial**,
como **PyTorch** e **Transformers**.

O sistema pode ser executado localmente ou no Google Colab.  
Entretanto, devido ao uso de modelos de linguagem de grande porte, recomenda-se fortemente
a execução no **Google Colab com GPU**, para melhor desempenho.

O notebook principal foi testado e validado no ambiente do [Google Colab](https://colab.google/).


## 🔑 Configuração do Hugging Face (necessário para rodar o modelo)

Este projeto utiliza um modelo de linguagem hospedado no Hugging Face.
Para executá-lo, é necessário criar uma chave de acesso gratuita.

Por motivos de segurança, o token **não é incluído no código ou no repositório**.

Instruções detalhadas para criação e configuração do token estão descritas abaixo.

### Passo a passo:

1. Crie uma conta em: https://huggingface.co
2. Vá em: Settings → Access Tokens
3. Crie um token do tipo "Read"
4. Salve o token em um local seguro
4. Copie o token

### No notebook:
- Em Configurações Inicias
- Na primeira célula
- Atualize a string `"SeuToken"` pelo token gerado


### No [Google Colab](https://colab.google/):
- Abra o notebook
- Clique em "Secrets" (ícone 🔒 na lateral)
- Crie uma variável chamada `HF_TOKEN`
- Cole sua chave como valor

### Execução:
Após configurar o token, execute todas as células do notebook normalmente.
