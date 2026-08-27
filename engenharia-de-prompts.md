# 🧪 Engenharia de Prompts e "Cicatrizes"

Este documento registra as perguntas estratégicas feitas ao NotebookLM, as variações de prompt testadas, as respostas obtidas e as dificuldades encontradas no caminho. A ideia é deixar rastreável **o raciocínio**, não só o resultado.

Preencha cada bloco conforme for interagindo com o NotebookLM. Use o formato abaixo como padrão.

---

## Template de registro

### Pergunta estratégica #1: [ex.: "Quais cláusulas são obrigatórias em um contrato de locação residencial?"]

**Prompt inicial usado:**
```
[cole aqui o prompt exato que você digitou no NotebookLM]
```

**Resposta obtida (resumo):**
> [resuma a resposta da IA em 2-4 linhas, com a referência ao artigo da lei citado pela fonte]

**Problema encontrado:**
- [ex.: "a resposta ficou genérica demais, sem citar artigos específicos"]

**Prompt refinado:**
```
[cole aqui a versão melhorada do prompt]
```

**Resposta refinada (resumo):**
> [resuma o resultado melhor]

**Lição aprendida:**
- [ex.: "pedir explicitamente 'cite o número do artigo' melhora muito a precisão"]

---

## Perguntas estratégicas sugeridas para começar

1. Quais são as cláusulas essenciais que um contrato de locação residencial deve conter, segundo a Lei 8.245/91?
2. Quais são as garantias locatícias previstas em lei (caução, fiador, seguro-fiança, cessão fiduciária) e quais as diferenças entre elas?
3. Qual o limite legal para o valor da caução e como ela deve ser devolvida ao final do contrato?
4. Em quais situações o locador pode retomar o imóvel antes do fim do contrato (denúncia, uso próprio, infração contratual)?
5. Como funciona o reajuste anual do aluguel e quais índices são aceitos?
6. O que a lei diz sobre benfeitorias feitas pelo locatário (quem paga, quem tem direito a indenização)?
7. Quais são as regras para rescisão antecipada do contrato pelo locatário (multa proporcional, art. 4º)?
8. Quais mudanças a Lei 12.112/2009 trouxe para o processo de despejo?
9. O que caracteriza infração contratual grave o suficiente para justificar despejo?
10. Quais cláusulas costumam ser consideradas abusivas ou nulas pela jurisprudência, mesmo que não estejam explicitamente na lei?

## Dicas de troubleshooting (preencher com sua experiência)
- [ ] O NotebookLM às vezes responde sem citar a fonte exata — pedir "cite a fonte e o número do artigo" resolve?
- [ ] Perguntas muito amplas geram respostas rasas — funciona melhor quebrar em sub-perguntas?
- [ ] Ao pedir comparações (ex.: caução vs. fiador vs. seguro-fiança), a IA mistura informações? Testar prompt em formato de tabela.
