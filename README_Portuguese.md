# Variáveis_no_experimento
Dados experimentais de galvanoplastia para previsão de espessura de zinco em aço SAE 1008, utilizados na dissertação &amp; artigo (Revista: Química Nova). Tabelas com variáveis de entrada/resposta, promovendo transparência &amp; reprodutibilidade.

# Descrição do Repositório de Dados

Este repositório contém os dados experimentais utilizados na dissertação de mestrado intitulada “AVANÇOS EM ELECTROPLATAÇÃO: PREDIÇÃO INTELIGENTE DA ESPESSURA DO REVESTIMENTO DE ZINCO EM AÇOS SAE 1008”, e no artigo científico publicado na Revista Química Nova, (ISSN 1678-7064), volume 48, número 4, páginas 1-10, em São Paulo/SP, em 4 de fevereiro de 2025. DOI: http://dx.doi.org/10.21577/0100-4042.20250103.

Os dados aqui apresentados foram coletados durante experimentos de galvanoplastia com o objetivo de analisar e prever a espessura do revestimento de zinco em aços SAE 1008. O conjunto de dados está dividido em duas tabelas principais, conforme descrito no artigo:

### Tabela 1: Variáveis de entrada e de resposta na experiência (Tabela 4 do artigo)

Descrição: Esta tabela apresenta as variáveis de entrada (parâmetros do processo de galvanoplastia) e a variável de resposta (espessura do revestimento de zinco) utilizadas na experiência inicial.
Conteúdo: Detalhes específicos sobre as variáveis de entrada e de resposta, incluindo as suas unidades de medida e os valores medidos.

### Tabela 2: Variáveis de entrada e de resposta na experiência (Tabela 8 do artigo)

Descrição: Esta tabela apresenta um conjunto alargado de variáveis de entrada e resposta, possivelmente incluindo dados adicionais ou refinamentos em relação à Tabela 1.
Conteúdo: Detalhes específicos sobre as variáveis de entrada e de resposta, incluindo as suas unidades de medida e os valores medidos.

---
Importância: Este repositório tem como objetivo fornecer acesso aberto aos dados experimentais, promovendo a transparência e a reprodutibilidade da investigação. Os dados podem ser utilizados para:
Verificação e validação: Outros investigadores podem utilizar os dados para verificar os resultados obtidos na dissertação e no artigo.
Desenvolvimento de novos modelos: Os dados podem servir de base para o desenvolvimento de novos modelos de previsão de espessura de revestimento de zinco em galvanoplastia.
Análises comparativas: Os dados podem ser comparados com resultados de outros estudos na área da galvanoplastia.

Estrutura do repositório:

README.md: Este ficheiro, que contém a descrição do repositório.
Tabela_4_Artigo.csv: Ficheiro CSV contendo os dados da Tabela 1 (Tabela 4 do artigo).
Tabela_8_Artigo.csv: Arquivo CSV contendo os dados da Tabela 2 (Tabela 8 do artigo).

Contribuição:

Contribuições para este repositório são bem-vindas, incluindo correcções de erros, sugestões de melhorias e análises de dados adicionais.

---

# 📌 Aplicação prática do modelo de aprendizagem automática

Este repositório contém um exemplo de uma aplicação prática do modelo desenvolvido na tese de mestrado intitulada:

**"AVANÇOS NA GALVANOPLASTIA: PREVISÃO INTELIGENTE DA ESPESSURA DO REVESTIMENTO DE ZINCO EM AÇOS SAE 1008"**


📌 **Nota de aplicação:** [Python_Application.ipynb](https://github.com/LucianoMLO/variables_in_the_experiment/blob/main/Python_Aplication.ipynb)

---

## 📌 Sobre o Projeto

Este caderno apresenta uma versão **demonstrativa**, com algumas limitações, mas que ilustra uma **implementação prática de Machine Learning** usando o **Gradio**. O objetivo é permitir que os utilizadores interajam facilmente com o modelo e façam previsões sem terem de lidar com código.

O modelo foi treinado para prever a **espessura do revestimento de zinco** no aço SAE 1008 com base em variáveis experimentais.

---

## Como executar o Notebook

1. **Acessar o Google Colab:**
   - Clicar [aqui](https://colab.research.google.com/) para abrir o Google Colab.

2. **Abrir o bloco de notas no Colab:
   - No menu “Ficheiro” > “Abrir bloco de notas” > “GitHub”.
   - Colar o link do repositório: `https://github.com/LucianoMLO/variables_in_the_experiment`
   - Selecionar o notebook `Python_Application.ipynb`.

3. **Executar todas as células**:
   - No Colab, clicar em **Executar tudo** (`Ctrl + F9`).

4. **Interagir com o modelo via Gradio:
   - Ao executar o notebook, será gerada uma ligação para uma interface interactiva onde poderá introduzir parâmetros e visualizar previsões.

---

## 🔹 O que é o Gradio e para que serve?

**O Gradio é uma ferramenta que facilita a criação de interfaces web para modelos de Machine Learning. No contexto deste projeto, permite a qualquer utilizador introduzir os valores das variáveis da experiência e obter previsões sem ter de programar.

**Vantagens do Gradio: **
Simplicidade: Interface acessível sem a necessidade de conhecimentos técnicos avançados.
Facilidade de implantação: Permite partilhar modelos rapidamente sem ter de configurar servidores complexos.
Interatividade: Os utilizadores podem testar diferentes entradas e ver os resultados instantaneamente.

---

## Conclusão

Este notebook demonstra a aplicabilidade do Machine Learning na **indústria** para prever a espessura do revestimento em processos de galvanoplastia. Apesar de ser uma versão de demonstração, exemplifica o potencial de modelos preditivos para otimizar processos industriais.

✉️ **Dúvidas ou sugestões?** Sinta-se à vontade para abrir um *issue* no repositório!
🚀 **Vamos avançar juntos na aplicação da IA na indústria!**
