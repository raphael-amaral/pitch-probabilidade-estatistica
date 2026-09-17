# Handoff — pitch do curso de extensão

## Estado atual

A proposta é um curso de extensão optativo chamado **Laboratório de Programação com Python**, voltado à prática de programação e ao acompanhamento da confiança dos participantes.

A apresentação final está em:

- `output/presentation/pitch-curso-extensao-python-final.pptx`

Ela contém 5 slides e um roteiro de fala nas notas do apresentador. O antigo slide “O número que decide a proposta” foi removido conforme a orientação do professor. O tempo estimado do roteiro é de aproximadamente **4 minutos e 10 segundos**, deixando margem dentro do limite de 5 minutos.

## Dados utilizados

Arquivo principal:

- `censo-turma-es-corrigido.csv`

Tratamento realizado:

- remoção do registro `ABC12`, pois o professor informou que era a resposta dele;
- remoção de `SCJ28`, respondido depois da data normal;
- manutenção somente da resposta mais recente de `RLS18`.

Resultado do censo corrigido:

- 44 respostas válidas e identificadores únicos;
- confiança 1: 1 aluno;
- confiança 2: 5 alunos;
- confiança 3: 29 alunos;
- confiança 4: 8 alunos;
- confiança 5: 1 aluno;
- 35 de 44 alunos marcaram de 1 a 3: **79,5%**;
- entre esses 35 alunos, 27 usam principalmente Python: **77,1%**;
- Java aparece em 4 respostas e outras linguagens em 4 respostas.

Usar a expressão **“não declararam confiança alta”** para os níveis de 1 a 3. Evitar afirmar que todos possuem “baixa confiança”, pois o nível 3 é intermediário.

## Estrutura da apresentação

1. **Laboratório de Programação com Python** — apresentação da proposta e do dado de 35 em 44 alunos.
2. **A confiança está concentrada no nível 3** — distribuição das respostas e recorte de 1 a 3.
3. **Python atende 77,1% do público-alvo** — escolha da linguagem com base nos 27 de 35 alunos.
4. **Evasão em cursos brasileiros de Computação** — estudo de Duran et al. com 3.193 estudantes e ressalva de causalidade.
5. **Curso de extensão** — objetivo, formato, conteúdos, avaliação e fechamento.

O fechamento está nas notas do slide 5. A conclusão recomendada é que os dados justificam um **projeto piloto para esta turma**, e não uma política para todo o campus.

## Referência externa do slide 4

### Evasão e permanência em cursos brasileiros de Computação

DURAN, Rodrigo et al. *Potential Factors for Retention and Intent to Drop-out in Brazilian Computing Programs*. ACM Transactions on Computing Education, v. 23, n. 3, 2023.

- DOI: <https://doi.org/10.1145/3607537>
- Página da ACM: <https://dl.acm.org/doi/10.1145/3607537>
- Registro no repositório da UNESP: <https://repositorio.unesp.br/entities/publication/ef807a05-13d6-48d5-a1e6-904f72d734ca>

### De onde saíram os dados do slide

- **3.193 estudantes** é o total informado pelo artigo para a pesquisa online. Todos estavam matriculados em cursos brasileiros de Computação, distribuídos por várias instituições do país.
- Os autores utilizaram respostas em **escala Likert de importância**. Os participantes avaliaram fatores que poderiam influenciar a permanência ou a decisão de abandonar o curso.
- A figura do artigo dedicada aos fatores de evasão utiliza **3.003 respostas**. Portanto, o slide pode informar 3.193 participantes no estudo e, se houver espaço, esclarecer que 3.003 responderam ao bloco específico sobre evasão.
- A pergunta do bloco de evasão era, em tradução livre: “Qual é a importância destas afirmações para sua decisão de abandonar ou considerar abandonar o curso?”.
- O artigo estudou estudantes que **ainda estavam matriculados**. Portanto, mediu intenção e fatores potenciais de evasão, não casos confirmados de abandono.

### Resultados que podem fortalecer o slide

- “O curso possui disciplinas teóricas demais” foi o único item com mais respostas no espectro de **importante** do que no espectro de **não importante**.
- Dificuldade em Matemática, dificuldade em Programação e dificuldade geral do curso ficaram entre os fatores mais bem posicionados no ranking de intenção de evasão.
- Na análise por gênero, o excesso de disciplinas teóricas foi indicado por **44% dos homens e 42% das mulheres** como um fator relevante.
- O artigo também encontrou que mulheres atribuíram maior importância à dificuldade das disciplinas de Programação do que homens, embora o tamanho do efeito tenha sido pequeno.

Não apresentar esses percentuais como “taxa de evasão”. Eles representam respostas sobre a importância de possíveis fatores de evasão.

### Sugestão de reestruturação do slide 4 — ainda não aplicada

Título sugerido: **Como Duran et al. estudaram a intenção de evasão**

Bloco “Método”:

- survey online;
- 3.193 estudantes ainda matriculados;
- várias instituições brasileiras;
- 3.003 respostas no bloco sobre evasão;
- escala de importância.

Bloco “Principais resultados”:

- excesso de disciplinas teóricas: 44% dos homens e 42% das mulheres;
- dificuldade em Matemática e Programação entre os fatores mais bem posicionados.

Rodapé sugerido:

> O estudo mede intenção de evasão, não abandono observado, e não estabelece causalidade.

Fala sugerida:

> O número de 3.193 corresponde ao total de estudantes ainda matriculados que participaram de uma pesquisa online em várias instituições brasileiras. No bloco específico sobre evasão, analisado com 3.003 respostas, os alunos avaliaram a importância de diferentes motivos para abandonar ou considerar abandonar o curso. O excesso de disciplinas teóricas foi o único item com predominância de respostas no espectro de importante. Ele foi apontado por 44% dos homens e 42% das mulheres. Dificuldades em Matemática e Programação também ficaram entre os fatores mais bem posicionados. Como os participantes ainda estavam matriculados, o estudo mede intenção e fatores potenciais, não evasão efetivamente ocorrida.

Limite da afirmação: o trabalho não demonstra que confiança baixa cause evasão nem que o curso de extensão proposto reduzirá a evasão.

## Gráficos

Os gráficos estão nos slides 2 e 3 e foram reconstruídos como gráficos verticais editáveis, com planilhas incorporadas ao PowerPoint:

- slide 2: eixo X “Nível de confiança” e eixo Y “Número de alunos”;
- slide 3: eixo X “Linguagem mais utilizada” e eixo Y “Número de alunos”.

Caso eles não apareçam na pré-visualização do navegador ou do repositório, abrir o arquivo no PowerPoint ou no LibreOffice. Os números principais também estão escritos nos slides, então a apresentação continua compreensível mesmo se houver algum problema no visualizador.

## Limitações que devem ser faladas

- O censo representa somente a turma de Engenharia de Software da disciplina de Probabilidade e Estatística, no segundo semestre de 2026.
- Os resultados não representam o campus, o curso inteiro ou outras turmas.
- Confiança é uma autoavaliação em uma única pergunta, não uma medida direta de competência.
- O censo não perguntou quem efetivamente se matricularia no curso de extensão.
- A pesquisa externa fortalece a relevância do tema, mas não prova causalidade para esta turma.

## Próximos passos em casa

1. Substituir `[nomes do grupo]` no primeiro slide.
2. Abrir a apresentação final e conferir os gráficos nos slides 2 e 3.
3. Reestruturar o slide 4 usando a seção “Sugestão de reestruturação do slide 4 — ainda não aplicada”.
4. Ler as notas de cada slide e ajustar a fala para o estilo do grupo.
5. Fazer pelo menos um ensaio cronometrado. O roteiro atual dura cerca de 4 minutos e 10 segundos.
6. Se necessário, exportar uma cópia em PDF para evitar diferenças entre computadores.
7. Versionar pelo menos o CSV corrigido, este handoff e a apresentação final.

Sugestão de arquivos para o commit:

```text
censo-turma-es-corrigido.csv
censo-turma-es-confiancaAteTres.csv
handoff.md
output/presentation/pitch-curso-extensao-python-final.pptx
```
