# Desafio Final Iniciativa She Lovelace

Neste repositório você encontra o enunciado do Desafio Final da _primeira turma_ da 
[Iniciativa She Lovelace](https://br.linkedin.com/company/iniciativashelovelace)! 

## O problema

Você foi encarregada de desenvolver um sistema de registro de vendas que permite o armazenamento e a análise de dados de vendas de produtos. Este sistema deve ser capaz de registrar cada venda realizada, armazenar essas informações em um arquivo CSV (banco de dados), e gerar relatórios que ofereçam insights sobre o desempenho das vendas.

## Requisitos do sistema
1. Registro de Vendas: O sistema deve permitir o registro de vendas, capturando informações como data da venda, produto vendido, quantidade e valor total.
2. Armazenamento de Dados: As informações das vendas devem ser armazenadas em arquivos CSV para fácil acesso e manipulação futura.
3. Geração de Relatórios: O sistema deve gerar relatórios que incluam:
- Vendas por produto.
- Vendas por data.
- Identificação do produto mais vendido.
4. Visualização Gráfica: O sistema deve fornecer representações gráficas simples dos dados de vendas para facilitar a visualização dos resultados.

## Solução

A solução deve ser implementada utilizando a linguagem Python, com bibliotecas como `csv` para manipulação de arquivos e `matplotlib` ou `seaborn` para a criação de gráficos. O sistema consistirá em um conjunto de scripts Python que, ao serem executados, permitirão registrar vendas, atualizar os arquivos CSV e gerar relatórios e gráficos.

### Funcionalidades esperadas:

- Interface de linha de comando (CLI) para registrar vendas.
- Armazenamento automático dos dados em arquivos CSV.
- Geração de relatórios em formato de texto e gráficos.

## Sugestão de Esqueleto

O projeto poderá seguir a seguinte sugestão de estrutura de diretórios:

```
/desafio-final-she-lovelace
│
├── README.md               # Documentação do projeto
├── main.py                 # Arquivo principal para execução do sistema
├── vendas/
│   ├── registro.py         # Script para registrar vendas
│   ├── relatorios.py       # Script para gerar relatórios
│   └── dados/              
│       └── vendas.csv      # Arquivo CSV para armazenar os dados das vendas
├── graficos/
│   └── gerar_graficos.py   # Script para gerar gráficos de vendas
└── requirements.txt        # Dependências do projeto
```

## Avaliação
A avaliação do desafio será baseada nos seguintes critérios:

- Correção Funcional: O sistema deve atender a pelo menos 70% dos requisitos funcionais mencionados na seção "O Problema".
- Qualidade do Código: O código deve ser bem estruturado, legível e seguir boas práticas de desenvolvimento exercitando o que foi aprendito durante as aulas.
- Documentação: O projeto deve conter uma documentação clara que explique como configurar, executar o sistema e interpretar os relatórios.
- Criatividade: Soluções criativas para a visualização dos dados e a apresentação dos relatórios serão valorizadas.

### Como Será Avaliado

1. **Criação do Repositório**
   - Acesse [GitHub](https://github.com) e faça login.
   - Clique em **"New repository"**.
   - Dê um nome ao repositório (ex.: `desafio-final-she-lovelace`).
   - Defina a visibilidade como **pública**.
   - Marque a opção **"Add a README file"** para incluir um README inicial.
   - Clique em **"Create repository"**.

2. **Clone o Repositório para o Seu Computador**
   - Abra o terminal ou prompt de comando.
   - Clone o repositório com o comando:
     ```bash
     git clone https://github.com/SEU-USUARIO/desafio-final-she-lovelace.git
     ```
   - Substitua `SEU-USUARIO` pelo seu nome de usuário no GitHub.

3. **Desenvolva o Código da Implementação**
   - Navegue até o diretório clonado:
     ```bash
     cd desafio-final-she-lovelace
     ```
   - Adicione os arquivos do projeto ao diretório.

4. **Commitando e Enviando o Código**
   - Adicione os arquivos ao controle de versão:
     ```bash
     git add .
     ```
   - Faça um commit das alterações:
     ```bash
     git commit -m "Adicionar solução do desafio final"
     ```
   - Envie as alterações para o GitHub:
     ```bash
     git push origin main
     ```

5. **Compartilhe o Link Até a Data Limite no Canal do Discord**
   - Após enviar o código, acesse o repositório no GitHub.
   - Copie a URL do repositório (ex.: `https://github.com/SEU-USUARIO/desafio-final-she-lovelace`).
   - Envie o link do repositório público para a iniciativa conforme orientado.

## Recomendações Finais
- Documentação: Certifique-se de que o README contém instruções claras sobre como configurar e utilizar o sistema.
- Tratamento de Erros: Implemente verificações e tratativas para possíveis erros, como dados inválidos ou falhas no acesso ao arquivo CSV.
- Entrega: Certifique-se de que todo o código está devidamente organizado e que todos os arquivos necessários estão incluídos no repositório.
- Prazo: Respeite o prazo de entrega definido para o desafio.

Boa sorte! Estamos ansiosas para ver sua solução.