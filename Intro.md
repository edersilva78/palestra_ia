# INTRO
Ⓜ️...

> Este encontro marca o início da nossa jornada de transformação digital, com a IA como ferramenta para melhorar o dia a dia de todos. A colaboração e o diálogo serão essenciais para identificar as melhores soluções, e este é só o primeiro passo de um processo contínuo. Estamos aqui para transformar, juntos, nosso ambiente de trabalho de forma positiva e eficiente.
<!-- element style="font-size:34px"-->
Notes: 
- **Contextualize a Modernização**: **transformação digital**. A IA já está impactando várias áreas, e este é o momento de se adaptar e integrar essas ferramentas no dia a dia.
    
- **Foco na Colaboração**: Essa modernização não será imposta de cima para baixo. Ao contrário, é um processo **colaborativo**, onde cada setor pode identificar suas necessidades específicas e como a IA pode ser aplicada para melhorar suas operações.
    
- **Expectativa de Continuidade**: Este é o **primeiro passo em nossa jornada**. Cada setor terá a oportunidade de explorar mais a fundo suas demandas, e a empresa está comprometida em oferecer suporte contínuo.
    
- **Positividade**: Enfatize que a IA não vem para substituir, mas para **facilitar** e **potencializar** o trabalho de todos, permitindo foco em atividades de maior valor.


---
>Assim como o computador e a internet, a IA vai permitir que os trabalhadores se concentrem em tarefas de **maior valor** e deixem as rotineiras para as máquinas. Profissionais que adotarem a IA como uma ferramenta terão uma **vantagem competitiva** no futuro, pois a tecnologia virá para **potencializar o trabalho** e não substituí-lo.
><!-- element style="font-size:34px"-->

>**Datilógrafos** passaram a processadores de texto e, em seguida, por pessoas capazes de operar softwares de edição e colaboração.
<!-- element style="font-size:34px"-->


---

### O que é Inteligência Artificial?


![[openai-logo.png|200]]

Ⓜ️
---

Inteligência Artificial (IA, ou AI) é uma tecnologia que permite que computadores e máquinas "pensem" e aprendam como seres humanos. É uma área da ciência da computação


>"É como se fosse um assistente virtual que entende linguagem humana e pode ajudar com tarefas variadas, desde responder perguntas até gerar conteúdo."
Nós vamos focar no ChatGPT durante essa apresentação e usar AI, IA e ChatGPT como sinônimos. 
> <!-- element style="font-size:24px" -->
---


> [!WARNING] ATENÇÃO
> Essa apresentação foi feita com a ajuda do ChatGPT.

<!-- element style="width:60%;font-size:34px" rotate="0"-->

---

### 1. Como as IA funcionam

O ChatGPT (e demais LLMs) aprende ao reconhecer padrões e relações nos dados de linguagem aos quais foi exposto (praticamente a Internet), sem "entender" o mundo da mesma forma que humanos, mas sendo capaz de gerar respostas coerentes com base nesses padrões.

---

### 2. Como as IA não funcionam

- O ChatGPT **não aprende individualmente** com suas interações.
- Ele **mantém o contexto** dentro da sessão atual.
- A função de **memória persistente** é algo futuro, mas opcional.
- Dados "podem" ser usados de forma agregada para **melhorias gerais**. 💀

---
### 3. Armadilhas da IA

Embora a IA seja extremamente poderosa, ela pode gerar respostas incorretas ou _'alucinações'_ 😵‍💫, onde a resposta parece certa, mas é totalmente inventada.

Outro risco é o plágio 📝, onde a IA pode usar conteúdos inteiramente gerados por outros autores :copyright:. 

---
> [!WARNING] É importante sempre revisar criticamente o que a IA gera.
> Se o assunto não é familiar, podemos pedir para o GPT explicar melhor, citar exemplos ou analogias.

---
### 4. Melhores Práticas para Prompts

+ Para obter melhores respostas da IA, é crucial usar **prompts claros e diretos**. 
+ Você pode escrever como se estivesse mandando um chat para um especialista, ou um colega.
+ Isso vale tanto para o ChatGPT quanto para outras ferramentas de IA.
+ _Bonus_: Solicitar a fonte
+ _Bonus_: Pedir para ele se comportar como um ... (_Programando_)
---
> [!TIP] Uma boa prática é solicitar que a IA melhore ou refine uma resposta anterior

> [!TIP] Ou pedir sugestões de como criar um prompt mais eficaz para uma questão. 

---

### 5.Exemplos e Ferramentas 🧰

--

##### Reconhecimento de Texto


![[ocr.png|480]]
[OCR GPT Tool](https://chatgpt.com/g/g-kQB8VsRDz-ocr-tool/)<!-- element style="width:20%;font-size:14px"-->

--
#### Compreensão de texto
```txt
Explique em poucas palavras o texto acima.

Cite 2 exemplos de impactos positivos e negativos. Mantenha o texto simples e curto.
```
--
#### Melhoria de texto
```txt
Reescreva este parágrafo para torná-lo mais formal: 'A gente fez um bom trabalho, mas podemos melhorar ainda mais. E importante voce quere fazer melor'
```

--
#### Geração de Prompt

```Prompt
Gere um prompt para o chatGPT que eu possa usar para extrair informacoes relevantes (com graficos) sobre os dados abaixo:
Mês;Quantidade Produzida;Custo por Unidade (Reais);Valor de Venda por Unidade (Reais) Janeiro;480;10,0;20,0 Fevereiro;630;10,0;20,0 Março;694;9,5;19,5 Abril;782;9,5;19,5 Maio;980;9,0;19,0 Junho;1095;9,0;19,0 Julho;1228;8,5;18,5 Agosto;1564;8,5;18,5 Setembro;930;9,0;19,0 Outubro;1820;8,0;18,0 Novembro;2140;7,5;17,5 Dezembro;2331;7,5;17,5
```


```Resultado
"Eu tenho os seguintes dados de produção de um ano:

Mês;Quantidade Produzida;Custo por Unidade (Reais);Valor de Venda por Unidade (Reais) Janeiro;480;10,0;20,0 Fevereiro;630;10,0;20,0 Março;694;9,5;19,5 Abril;782;9,5;19,5 Maio;980;9,0;19,0 Junho;1095;9,0;19,0 Julho;1228;8,5;18,5 Agosto;1564;8,5;18,5 Setembro;930;9,0;19,0 Outubro;1820;8,0;18,0 Novembro;2140;7,5;17,5 Dezembro;2331;7,5;17,5

Por favor, faça as seguintes análises:

1. Crie gráficos que mostrem a evolução da **quantidade produzida** e do **lucro total mensal** (considerando o lucro como a diferença entre o valor de venda por unidade e o custo por unidade, multiplicado pela quantidade produzida).
2. Calcule a **margem de lucro por unidade** e mostre sua evolução ao longo do ano em um gráfico.
3. Determine o **crescimento percentual da produção mês a mês** e mostre esse crescimento em um gráfico.
4. Faça uma **previsão para o próximo mês** com base no crescimento médio da produção ao longo do ano.
5. Crie um gráfico que mostre a **comparação entre custo por unidade e valor de venda por unidade** ao longo dos meses.
6. Baseado na previsão de produção para o próximo mês, estime o **lucro total** e inclua essa previsão na análise.
7. Por fim, extraia insights relevantes sobre os dados, apontando tendências, sazonalidade, e possíveis estratégias comerciais que podem estar em jogo."
```
Em nosso próximo exemplo vamos executar esse prompt
<!-- element style="width:50%;font-size:14px"-->

--
#### Análise de dados

:fas_copy: Utilizando o resultado do prompt anterior
Ⓜ️

--

#### Suporte a cliente

```PROMPT
 Analise o seguinte feedback de clientes e me diga se o sentimento geral é positivo, negativo ou neutro: 'O produto chegou no prazo, mas a embalagem estava danificada. Funcionou bem, mas esperava mais.'
```

```
Crie uma resposta para esse cliente (e potenciais clientes que lerem) que o satisfaça e nos deixe bem na foto
```
--
### Outras ferramentas

> Vamos explorar alguns exemplos de outras ferramentas de IA que podem nos auxiliar nas tarefas do dia a dia.
> 
--
![[scooby.png]]
--
[Tradução](https://www.deepl.com/en/translator)
```plain text
The corporate world witnesses the increasing gap between executive leadership and technical teams, particularly technologists. This can be attributed to differences in perspective and expertise. C-suite executives focus on creating strategic goals and motivating their teams toward large-scale objectives. Meanwhile, the latter is typically more concerned with executing these visions. 

Edward Hamilton, a seasoned consultant, has made it his mission to address this disconnect that leads to failed projects, misaligned goals, and underutilized technological potential. He has navigated both worlds for over 15 years, gaining insights that have positioned him as a conduit between the C-suite and the technologists. 

Hamilton has always been interested in technology, prompting him to start his career young, selling tech products while pursuing his bachelor’s degree in Politics and Philosophy at The University of Manchester. His passion for technology soon found a professional outlet when he joined Apple Retail as a business consultant. He advised businesses on integrating Apple’s tools, technology, and software into their operations, expanding his tech expertise and understanding of business needs. 

The experienced professional moved into management consulting to hone his skills in software development and testing at a small firm. Seeking more challenges in global consulting, he worked at Ernst & Young (EY) as a senior consultant and manager in financial services technology advisory.  

```

--
[Slides](https://gamma.app/)

```prompt
Gere um prompt para o gamma.app, em ptbr, para criar uma apresentação sobre o institutomix (procure em https://institutomix.com.br e em outras fontes)
```

```Result
**Título**: Apresentação sobre o Instituto Mix de Profissões

**Descrição**: Crie uma apresentação detalhada sobre o Instituto Mix de Profissões, uma das maiores redes de ensino profissionalizante no Brasil. A apresentação deve abordar os seguintes tópicos:

1. **Introdução**: Visão geral do Instituto Mix, destacando sua missão de transformar vidas por meio da educação profissional.
    
2. **Cursos Oferecidos**: Apresentar as principais áreas de atuação, como beleza, gastronomia, tecnologia, saúde, administração, entre outros. Incluir exemplos de cursos populares, como Design Gráfico, Técnicas Administrativas e Elétrica Automotiva.
    
3. **Inovação e Diferenciais**: Focar em iniciativas inovadoras, como a **plataforma Gerencia AI**, que oferece aos alunos ferramentas para gerenciar seus próprios negócios, além da **Comunidade de Negócios**, com suporte para empreendedores.
    
4. **Modelo de Franquia**: Explicar o modelo de franquias do Instituto Mix, seu crescimento em todo o Brasil e as vantagens de se tornar um franqueado.
    
5. **Impacto Social**: Enfatizar como o Instituto Mix promove a empregabilidade e o empreendedorismo, ajudando alunos a ingressar no mercado de trabalho ou abrir seus próprios negócios.
    
6. **Depoimentos e Resultados**: Compartilhar histórias de sucesso de alunos que se formaram e transformaram suas carreiras, mostrando o impacto da educação oferecida.
    

**Conclusão**: Reforçar o compromisso do Instituto Mix com a educação de qualidade e o sucesso dos alunos, além de destacar as oportunidades de crescimento pessoal e profissional através dos cursos.

```

--
Minuta de Reuniões

- https://otter.ai/ 
- https://tldv.io/

> Não tem demo, devido ao tempo.

--

> [!TIP] Dica final
> Pedir para o GPT indicar ferramentas para a sua necessidade

---

#### Tarefa de casa

Pense em uma tarefa do seu dia a dia no trabalho que poderia ser **automatizada ou melhorada** usando ferramentas de **Inteligência Artificial (IA)**. Pode ser algo simples, como responder e-mails ou WhatsApp, criar relatórios de forma mais eficiente, ou mesmo melhorar processos como agendamentos, transcrição de reuniões ou análise de dados.

---
### Obrigado

☕ 🍞 🥝