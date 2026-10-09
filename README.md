# Explorando Práticas de Teste

Neste exercício, vamos explorar práticas de teste em sistemas reais utilizando a ferramenta [TestMiner](https://andrehora.github.io/testminer).

O TestMiner permite visualizar e analisar testes de software em repositórios do GitHub, fornecendo dados sobre como os projetos organizam seus testes, como eles evoluem entre versões e quais bibliotecas de teste são utilizadas.
Explore a ferramenta antes de começar para se familiarizar com seu funcionamento.

Mais detalhes no GitHub da ferramenta: https://github.com/andrehora/testminer.

---

## Passo 1: Selecionar um repositório

Escolha um repositório real que possua testes de software.
Abaixo estão alguns links para ajudá-lo a encontrar projetos interessantes:

- Python: https://github.com/topics/python?l=python
- JavaScript: https://github.com/topics/javascript?l=javascript
- TypeScript: https://github.com/topics/typescript?l=typescript
- Java: https://github.com/topics/java?l=java

- Tópicos: [ai](https://andrehora.github.io/testminer/#topic:ai), [llm](https://andrehora.github.io/testminer/#topic:llm), [api](https://andrehora.github.io/testminer/#topic:api), [nodejs](https://andrehora.github.io/testminer/#topic:nodejs), [android](https://andrehora.github.io/testminer/#topic:android)

- Por organização: [Google](https://andrehora.github.io/testminer/#google), [Microsoft](https://andrehora.github.io/testminer/#microsoft), [Apple](https://andrehora.github.io/testminer/#apple), [Facebook](https://andrehora.github.io/testminer/#facebook), [Netflix](https://andrehora.github.io/testminer/#netflix), 
[GitHub](https://andrehora.github.io/testminer/#github), [Apache](https://andrehora.github.io/testminer/#apache), [HuggingFace](https://andrehora.github.io/testminer/#huggingface)

## Passo 2: Explorar o repositório selecionado

Busque o repositório escolhido no [TestMiner](https://andrehora.github.io/testminer) e analise os dados de teste gerados pela ferramenta.

## Passo 3: Explicar uma prática de teste

Escolha uma prática ou dado de teste relevante e explique com suas próprias palavras.

---

## Instruções de entrega

1. Faça um `fork` deste repositório (saiba mais sobre forks [aqui](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)).
2. Responda às questões abaixo diretamente neste arquivo `README.md` do seu fork. Pode adicionar imagens para enriquecer sua explicação.
3. No Moodle, submeta apenas a URL do seu fork.

---

## Respostas

Repositório: https://github.com/juice-shop/juice-shop

URL TestMiner: https://andrehora.github.io/testminer/#juice-shop/juice-shop

Explicação: Achei interessante que foi feita uma documentação de instruções/recomendações(prioritariamente para agentes de inteligência artificial, apesar de ser muito útil também para seres humanos) de como estão organizados os testes na aplicação, dividos em quatro suítes de testes(frontend, server unit, api integration e E2E), além de instruções claras de boas práticas e o que NÃO deve ser feito. Isso facilita todo o processo de criação de testes pois padroniza como deve ser realizado o processo, permitindo criação/validação de testes de forma mais rápida e com mais qualidade, em projetos grandes como este isso é essencial, já que reduz trabalho repetitivo

Há todo um workflow automatizado que foi construído para agilizar o trabalho dos desenvolvedores com testes, a quantidade de tempo investido por desenvolvedores em testes é bastante considerável, automatizar parte do processo moroso e focar mais na parte de validação/gerenciamento dá liberdade para que o desenvolvedor possa focar em outras atividades para que a menor quantidade possível de bugs chegue em produção, eles até citam "instructions for writing automated tests that keep code coverage high for new functionality and close existing coverage gaps found in lvoc.iinfo files"

É possível visualizar o arquivo a que me refiro aqui: https://github.com/juice-shop/juice-shop/blob/master/.ai/skills/write-tests/SKILL.md

Também foi interessante visualizar a crescente na quantidade de testes, pois permite atestar a importância que foi sendo dada aos testes conforme o crescimento do sistema, o TestMiner fez com que fosse extremamente fácil visualizar isso.