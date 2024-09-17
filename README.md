![Logo](/util/logo.png)
![waving](https://capsule-render.vercel.app/api?type=waving&height=100&color=7913EE&textBg=false&section=header&reversal=false)

# InsightWise

InsightWise é uma plataforma de análise de produtividade projetada para otimizar o uso de software corporativo desenvolvido pela Plusoft. Ao coletar dados sobre as interações dos funcionários com esses sistemas, a plataforma oferece insights valiosos sobre o desempenho e a eficiência da equipe.

## Visão Geral do Projeto

O InsightWise visa fornecer aos gerentes uma visão clara de como os recursos disponíveis estão sendo utilizados, identificando padrões de comportamento e sugerindo melhorias. Ele serve como uma ferramenta estratégica para a transformação digital, focada em aumentar a produtividade e maximizar o retorno sobre o investimento em tecnologia.

## Membros da Equipe

- Breno Lemes Santiago - RM: 552270
- Felipe Guedes Gonçalves - RM: 550906
- Luiz Felipe Soares de Sousa Lucena - RM: 551365
- Nina Rebello Francisco - RM: 99509
- Vitória Maria de Camargo - RM: 552344

## Vídeos de Demonstração

- [Demonstração da Arquitetura de IA](https://youtu.be/CFcAKTyG8kE)
- [Demonstração da Aplicação Web](https://www.youtube.com/watch?v=SWA94V1H_Y0)

## Repositórios

- [Aplicação de IA](https://github.com/nina-rebello/ollama)
- [Frontend](https://github.com/Santlago/docinsightwise)
- [Backend](https://github.com/Santlago/docinsightwise)

## Principais Funcionalidades

1. Análise de Produtividade
2. Geração de Insights
3. Otimização Contínua

## Ferramentas e Bibliotecas Utilizadas

- Streamlit (para criação de dashboards)
- Ollama (modelo de IA)

## Arquitetura de IA

O projeto incorpora IA para analisar interações de usuários e gerar insights. O componente de IA é crucial para:

- Comparar fluxos de referência com os fluxos atuais dos usuários
- Identificar discrepâncias no comportamento dos usuários
- Gerar insights e recomendações acionáveis

## Detalhes da Implementação

O sistema inclui:

- Um dashboard para comparar interações
- Comparações visuais da duração de diferentes etapas no fluxo do usuário
- Análise detalhada de dados JSON, destacando semelhanças e discrepâncias
- Geração de insights e recomendações acionáveis

## Como Executar

### Executando o Frontend Next.js

O código do frontend está disponível em [http://github.com/Santlago/insightwise](http://github.com/Santlago/insightwise).

1. **Clone o repositório**: Abra seu terminal e clone o repositório do frontend.

    ```sh
    git clone https://github.com/Santlago/insightwise.git
    ```

2. **Instale Node.js e npm**: Certifique-se de ter o Node.js e o npm instalados. Você pode baixá-los em [nodejs.org](https://nodejs.org/).

3. **Navegue até o diretório do frontend**: Abra seu terminal e navegue até o diretório onde seu projeto Next.js está localizado.

    ```sh
    cd caminho/para/insightwise
    ```

4. **Instale as dependências**: Execute o seguinte comando para instalar todas as dependências necessárias.

    ```sh
    npm install
    ```

5. **Execute o servidor de desenvolvimento**: Inicie o servidor de desenvolvimento do Next.js com o seguinte comando.

    ```sh
    npm run dev
    ```

6. **Abra seu navegador**: Abra seu navegador e vá para `http://localhost:3000`. Você deve ver a aplicação Next.js em execução.

### Executando o Backend Spring Boot

O código do backend está disponível em [http://github.com/Santlago/apiinsightwise](http://github.com/Santlago/apiinsightwise).

1. **Clone o repositório**: Abra seu terminal e clone o repositório do backend.

    ```sh
    git clone https://github.com/Santlago/apiinsightwise.git
    ```

2. **Instale Java e Maven**: Certifique-se de ter o Java (JDK) e o Maven instalados. Você pode baixar o JDK em [oracle.com](https://www.oracle.com/java/technologies/javase-downloads.html) e o Maven em [maven.apache.org](https://maven.apache.org/download.cgi).

3. **Navegue até o diretório do backend**: Abra seu terminal e navegue até o diretório onde seu projeto Spring Boot está localizado.

    ```sh
    cd caminho/para/apiinsightwise
    ```

4. **Construa o projeto**: Execute o seguinte comando para construir seu projeto Spring Boot.

    ```sh
    mvn clean install
    ```

5. **Execute a aplicação**: Inicie a aplicação Spring Boot com o seguinte comando.

    ```sh
    mvn spring-boot:run
    ```

6. **Verifique o backend**: A aplicação Spring Boot deve estar em execução em `http://localhost:8080`.


## Contribuindo

Nós aceitamos contribuições para o InsightWise! Sinta-se à vontade para enviar pull requests ou abrir issues nos respectivos repositórios.

## Agradecimentos

Este projeto foi desenvolvido como parte do Challenge proposto pela [FIAP](https://www.fiap.com.br/) em parceria com a [Plusoft](https://plusoft.com/)