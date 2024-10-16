# Aula 04- Para Casa: Testes de Hipóteses e Intervalos de Confiança

Chegou a hora de você praticar o que foi visto em aula. Neste repositório você terá:

- Na pasta `exercicios`: uma lista de exercícios mais teóricos para você praticar e testar o que aprendeu.

- Na pasta `data`: encontrará um arquivo `csv`que vai ser base para o desafio da aula.

- Na pasta `notebook`: o gabarito do desafio proposto para você resolver.

___

## INSTRUÇÕES PARA RESOLUÇÃO DO DESAFIO 

Somos uma ong de animais e queremos incentivar a adoção de pets. Para isso, vamos mostrar um vídeo de animais para as pessoas. Porém, não sabemos o que é mais efetivo: **um vídeo de cachorros ou um vídeo de gatos**.

Por isso, resolvemos rodar um experimento: vamos criar 2 vídeos, um de cachorro e outro de gato. Depois, vamos perguntar as pessoas a probabilidade de que ela adote um animal.

- As pessoas desse experimento só verão 1 vídeo cada

- Ao final do vídeo perguntamos a elas a probabilidade de que elas adotem um animal

- As amostras são aleatorias e sem viéses sistematicos

**Objetivo:** Avaliar qual animal (cachorro ou gato) deve estar em um vídeo de campanha de adoção.

**Experimento**: 500 pessoas que não possuem animais de estimação assistem aos vídeos de campanha de adoção. Os vídeos são idênticos com exceção dos animais mostrados:

- 250 pessoas aleatorizadas para o vídeo com gato
- 250 pessoas aleatorizadas para o vídeo com cachorro

**Resposta: "Qual a chance de adotar um pet? (0-100)" depois do vídeo
A média de probabilidade de quem ve o vídeo de gato é igual a de cachorro?**

___

## INSTRUÇÕES PARA O USO DESTE REPOSITÓRIO:

### **Como utilizar este repositório?**

Este repositório contém os arquivos e códigos necessários para a aula de Estatística Descritiva. Abaixo estão as instruções simplificadas para configurar o ambiente com Pyenv e Poetry.

- **Passo a Passo para Configuração do Ambiente:**

1. **Clonar o Repositório:**

No terminal, clone este repositório:

```bash
git clone https://github.com/EbaPed/EBA-aula04-ParaCasa.git
cd EBA_aula01_EstatisticaDescritiva
```

2. **Configurar a versão do Python com Pyenv**

Defina a versão do Python para o projeto. Para esta aula, vamos usar o Python 3.10.11 (ou outra versão compatível):

```bash
pyenv local 3.10.11
```

3. **Ativar o Ambiente Virtual Poetry**

Agora, ative o ambiente virtual:

```bash
poetry shell
```

4. **Instale as dependências do projeto usando Poetry:**

```bash
poetry install
```

Isso criará automaticamente um ambiente virtual isolado.


5. **Configurar o Kernel do Jupyter Notebook**

Se você for usar Jupyter Notebook, instale o ipykernel:

```bash
poetry add ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)
```

No Jupyter Notebook, escolha o kernel "Python (venv)" ao iniciar ou criar um novo notebook.


6. **Desativar o Ambiente Virtual**

Para sair do ambiente virtual, basta usar:

```bash
exit
```

7. **Executar o Código**

Agora que o ambiente está configurado, você pode executar os códigos Python fornecidos no repositório.

### **Comandos úteis**

- Ativar o ambiente virtual Poetry:

```bash
poetry shell
```

- Rodar um script com Poetry:

```bash
poetry run python script.py
```

- Adicionar bibliotecas:

 ```bash
poetry add nome_da_biblioteca
```

- Remover Bibliotecas:

 ```bash
poetry remove nome_da_biblioteca
```



