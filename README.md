# 🚀 Desafio de Projeto - Análise de Sentimentos com Language Studio no Azure AI

Repositório de informações sobre Análise de Sentimentos com Language Studio no Azure AI.

💬 💡 Como não disponho de uma conta no Azure AI que me possibilite testar os recursos do Language Studio, fiz um resumo do conteúdo abordado no curso.

## 1. Visão Geral da IA Generativa

A utilização da inteligência artificial tem crescido exponencialmente, otimizando tanto o uso pessoal quanto o empresarial em diversas áreas, como pesquisa acadêmica, desenvolvimento de código e validação de documentos. A IA Generativa é alimentada por Modelos de Linguagem Grandes (LLMs), que "precisam ser alimentados" com vastos volumes de dados para "trabalhar e testar essas informações". O objetivo é processar a linguagem de forma "mais natural possível, ou seja, tornando isso mais próximo de, literalmente se passar por uma pessoa.".

## 2. Fundamentos dos Modelos de Linguagem Grandes (LLMs)

Os LLMs (do inglês Large Language Model) são a base da IA Generativa, atuando na leitura e processamento de dados para executar tarefas de Processamento de Linguagem Natural (PLN). As principais capacidades dos LLMs incluem:

- Determinar sentimento ou classificar texto em linguagem natural: "Hoje as pessoas costumam compartilhar tuuddo por redes sociais." Os LLMs podem analisar esses dados para identificar sentimentos, o que é crucial para detecção precoce de ameaças;
- Resumir um texto: Essencial para otimização do tempo, especialmente em áreas como o direito, onde "o processo é enorme." Um LLM pode "fazer a leitura para mim e trazer os pontos-chave importantes";
- Comparar múltiplas fontes de texto para similaridade semântica: Permite análises mais profundas e a resolução de problemas complexos, como "troubleshooting de problemas técnicos"; e
- Geração de nova linguagem natural: A capacidade de criar "frases, textos inteiros, que a gente olhe e, gente do céu, é sério que não foi uma pessoa que escreveu isso?" é uma das mais impressionantes da IA Generativa.

### 2.1. Arquitetura do Modelo Transformador

A arquitetura do transformador é fundamental para os LLMs e consiste em dois componentes principais:

Bloco Codificador: "cria essas representações do vocabulário no cenário de treinamento." Requer "o máximo possível de dados" para garantir resultados assertivos.

Bloco Decodificador: "vai gerar aí essas sequências prováveis com base nas informações ali que ele conseguiu fazer essa leitura." É responsável por prever a próxima palavra ou sequência de tokens de forma coerente.

### 2.2. Tokenização

A tokenização é a "etapa do meu modelo onde eu estou particionando" o texto em "blocos" ou "tokens numéricos exclusivos", atribuindo um "valor de importância, digamos assim, para cada palavra que existisse." Isso permite que a máquina processe e entenda as palavras como dados numéricos. Por exemplo, a frase "Eu ouvi um cachorro latir alto para um gato" é representada por uma sequência numérica.

### 2.3. Inserções (Embeddings)

As inserções, ou embeddings, são valores de vetor multidimensionais atribuídos aos tokens. Elas capturam "as relações entre tokens" de forma semântica, garantindo que as palavras relacionadas fiquem "mais perto" em um modelo multidimensional. Isso assegura que o texto gerado "faça sentido na questão de conjugação de verbos ou até mesmo se encaixe um texto, não fique aquela coisa, nossa, por que foi colocar essa palavra aqui se isso não tem nada a ver com o contexto?".

### 2.4. Camadas de Atenção

As camadas de atenção são uma "técnica que a gente vai utilizar para examinar essa sequência de tokens", determinando a "probabilidade de uma palavra aparecer depois da outra" e se "aquilo faz sentido." Elas atribuem "mais peso" aos tokens mais relevantes dentro de uma frase para prever a próxima palavra mais provável. O treinamento da máquina visa "trazer a resposta que faça sentido", minimizando erros. Por exemplo, após "cachorro", a palavra "latir" é mais provável do que "miar" com base no treinamento.

## 3. Engenharia de Prompts: A Nova Profissão

A "engenharia de prompt" é uma nova área que se concentra em "quem faz as melhores perguntas" para as ferramentas de IA, pois "a qualidade das respostas de um aplicativo de inteligência artificial hoje, não depende apenas de todos os modelos que a gente estava falando.", mas sim das perguntas e comandos que são submetidos por nós, humanos.

As estratégias para aprimorar as respostas da IA Generativa incluem:

- Linguagem Direta: Ser explícito sobre o que se deseja. Exemplo: "Crie uma lista de 10 coisas para fazer em Edimburgo durante o mês de agosto.";
- Exemplos: Fornecer exemplos para guiar a IA. Exemplo: "Visite o castelo pela manhã, antes que as multidões cheguem", que a IA pode usar para oferecer conselhos úteis; e
- Dados Básicos (Grounding Data): Incluir dados de fundamentação para treinar um modelo personalizado. Exemplo: "incluindo texto de e-mail com a mensagem: Resumir meu e-mail".

## 4. Aplicações e Impacto da IA Generativa

A IA Generativa já transformou diversas áreas:

- Geração de Linguagem Natural: Ferramentas como o ChatGPT auxiliam na criação e aprimoramento de textos, desde posts para LinkedIn até e-mails e traduções. "Me ajude a melhorar tal texto e coloca ali ele já traz tudo com outras ideias ou até mesmo trazendo com algumas palavras diferentes e tudo mais e de fato muitas das vezes fica realmente muito bom";
- Geração de Código: O GitHub Copilot é um exemplo de como a IA auxilia desenvolvedores, ajudando na "validação do código", em "testar aquele código" e "autocompletar", acelerando o aprendizado e a produtividade, especialmente diante do déficit de profissionais na área de tecnologia;
- Geração de Imagem: Permite criar imagens personalizadas, como avatares no estilo Pixar ou Funko, a partir de instruções textuais detalhadas. "A questão é o quanto de instruções você vai passar.";
- Otimização de Tarefas e Resolução de Problemas: Ferramentas como o Bing com IA podem fazer "comparativos" e "troubleshooting de problemas técnicos", fornecendo respostas e fontes rapidamente, o que "ajuda demais a questão de produtividade e chega a ser alarmante".

## 5. IA Responsável e Desafios

Com o crescente uso da IA, surgem desafios e a necessidade de "IA Responsável". Questões como "Quem é responsável pelas decisões baseadas na IA?" são cruciais, especialmente em cenários sensíveis como condenações baseadas em reconhecimento facial.

A segurança dos dados é uma preocupação primordial. "As empresas prezam muito por isso, seja por questões legais ou até mesmo pela questão da imagem." É fundamental "garantir que os dados vão ser utilizados dentro da aplicação, mas não podem ser acessados por terceiros." A falha na segurança pode resultar em perda de credibilidade e fuga de clientes.

Apesar dos avanços, é importante entender que a IA "não vai pegar o meu emprego" no curto prazo, mas "precisamos entender como a inteligência artificial trabalha. Como nós podemos aplicá-lo no nosso dia a dia para tirar o melhor disso, o melhor proveito possível.". A otimização de tarefas e a curva de aprendizado acelerada são benefícios claros, mas "não podemos nos esquecer que ainda somos humanos.".

## 6. Serviços de IA do Azure

A Microsoft Azure oferece uma plataforma de nuvem escalável e confiável que fornece serviços de IA, incluindo:

- Azure Machine Learning: Uma plataforma para "treinar, implantar e gerenciar modelos de aprendizado de máquina"; e
- Azure AI Services: Um conjunto abrangente de serviços que cobrem "visão, fala, linguagem, decisão e IA generativa". A utilização do serviço OpenAI dentro do Azure é destacada como uma forma de explorar a IA Generativa de forma responsável.

Em resumo, a IA Generativa, impulsionada pelos Modelos de Linguagem Grandes e aprimorada pela engenharia de prompts, está se tornando uma ferramenta indispensável para otimização de processos, criação de conteúdo e resolução de problemas, ao mesmo tempo em que exige um foco contínuo na segurança e responsabilidade.

## 📚 Referências

- [Digital Inovation One - DIO](https://web.dio.me/)
- [Documentação da Linguagem de IA do Azure](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/)
- [Explore Speech Studio - Laboratório no Microsoft Learning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)
- [Analyze text with Language Studio - Laboratório no Microsoft Learning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
