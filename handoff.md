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
4. **O problema aparece além desta turma** — duas pesquisas externas e ressalva de causalidade.
5. **Curso de extensão** — objetivo, formato, conteúdos, avaliação e fechamento.

O fechamento está nas notas do slide 5. A conclusão recomendada é que os dados justificam um **projeto piloto para esta turma**, e não uma política para todo o campus.

## Referências externas do slide 4

### 1. Evasão e permanência em cursos brasileiros de Computação

DURAN, Rodrigo et al. *Potential Factors for Retention and Intent to Drop-out in Brazilian Computing Programs*. ACM Transactions on Computing Education, v. 23, n. 3, 2023.

- DOI: <https://doi.org/10.1145/3607537>
- Página da ACM: <https://dl.acm.org/doi/10.1145/3607537>
- Registro no repositório da UNESP: <https://repositorio.unesp.br/entities/publication/ef807a05-13d6-48d5-a1e6-904f72d734ca>

O estudo analisou respostas de **3.193 estudantes matriculados em cursos brasileiros de Computação**. A dificuldade das disciplinas de programação e matemática apareceu entre os fatores mais importantes associados à intenção de abandonar o curso.

Limite da afirmação: o trabalho trata de fatores potenciais e intenção de evasão. Ele não demonstra que confiança baixa cause evasão nem que o curso proposto reduzirá a evasão.

### 2. Autoeficácia em programação introdutória

RAMALINGAM, Vennila; WIEDENBECK, Susan. *Development and Validation of Scores on a Computer Programming Self-Efficacy Scale and Group Analyses of Novice Programmer Self-Efficacy*. Journal of Educational Computing Research, v. 19, n. 4, p. 367–381, 1998.

- DOI: <https://doi.org/10.2190/C670-Y3C8-LTJ1-CT3P>
- Página da editora SAGE: <https://journals.sagepub.com/doi/10.2190/C670-Y3C8-LTJ1-CT3P>

A escala foi aplicada a **421 estudantes** de uma disciplina introdutória de programação em C++, no início e no final de 12 semanas. A autoeficácia aumentou, principalmente entre quem começou com níveis mais baixos.

Limite da afirmação: o estudo sustenta que a autoeficácia pode mudar durante uma experiência de aprendizagem. Ele não prova que o nosso curso produzirá o mesmo efeito nem estabelece uma relação causal com evasão.

## Gráficos

Os gráficos estão nos slides 2 e 3 e foram reconstruídos como gráficos editáveis com planilhas incorporadas ao PowerPoint:

- slide 2: quantidade de alunos em cada nível de confiança;
- slide 3: linguagem utilizada entre os alunos com confiança de 1 a 3.

Caso eles não apareçam na pré-visualização do navegador ou do repositório, abrir o arquivo no PowerPoint ou no LibreOffice. Os números principais também estão escritos nos slides, então a apresentação continua compreensível mesmo se houver algum problema no visualizador.

## Limitações que devem ser faladas

- O censo representa somente a turma de Engenharia de Software da disciplina de Probabilidade e Estatística, no segundo semestre de 2026.
- Os resultados não representam o campus, o curso inteiro ou outras turmas.
- Confiança é uma autoavaliação em uma única pergunta, não uma medida direta de competência.
- O censo não perguntou quem efetivamente se matricularia no curso de extensão.
- As pesquisas externas fortalecem a relevância do tema, mas não provam causalidade para esta turma.

## Próximos passos em casa

1. Substituir `[nomes do grupo]` no primeiro slide.
2. Abrir a apresentação final e conferir os gráficos nos slides 2 e 3.
3. Ler as notas de cada slide e ajustar a fala para o estilo do grupo.
4. Fazer pelo menos um ensaio cronometrado. O roteiro atual dura cerca de 4 minutos e 10 segundos.
5. Se necessário, exportar uma cópia em PDF para evitar diferenças entre computadores.
6. Versionar pelo menos o CSV corrigido, este handoff e a apresentação final.

Sugestão de arquivos para o commit:

```text
censo-turma-es-corrigido.csv
censo-turma-es-confiancaAteTres.csv
handoff.md
output/presentation/pitch-curso-extensao-python-final.pptx
```
