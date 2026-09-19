# Checklist de Qualidade dos Modelos — SubEquipe_03
### Entrega 2 · Modelagem UML

Documento de rastro metodológico. Usado para conferir cada artefato antes de considerá-lo fechado para o relatório final.

---

## Diagrama de Classes

- [ ] Toda classe tem os três compartimentos: nome, atributos, operações
- [ ] Atributos e operações têm visibilidade marcada (`-` privado, `+` público)
- [ ] Toda associação tem multiplicidade nas duas pontas
- [ ] Composição usada apenas onde a parte realmente não sobrevive sem o todo
- [ ] Nenhuma relação foi copiada sem verificar se o tipo (associação/composição/agregação) está correto para o caso
- [ ] Toda classe tem rastreabilidade explícita a um achado da Entrega 1

## Diagrama de Objetos

- [ ] Nenhum objeto, atributo ou relação aparece aqui sem existir primeiro no Diagrama de Classes
- [ ] Cabeçalho de cada objeto segue a notação `instancia : Classe`, sublinhado
- [ ] Nenhum dado pessoal real foi usado — todos os valores são fictícios
- [ ] O cenário instanciado está descrito em texto no relatório, não apenas no diagrama

## Diagrama de Sequência

- [ ] Toda mensagem síncrona tem seta cheia; todo retorno, seta tracejada
- [ ] Barra de ativação presente enquanto o objeto processa
- [ ] Fragmentos combinados (`alt`, `opt`, `loop`) usados corretamente, com condição de guarda entre colchetes
- [ ] Nenhuma etapa não observada na Entrega 1 foi representada como comportamento confirmado

## Máquinas de Estado

- [ ] Um único estado inicial
- [ ] Todo estado final está identificado
- [ ] Nome do estado descreve uma condição ("Vinculado"), não uma ação ("Vincular")
- [ ] Toda transição tem o evento que a dispara; condições de guarda entre colchetes quando houver

## Geral

- [ ] Cada artefato tem o arquivo-fonte (`.drawio`) commitado junto com o `.svg`
- [ ] Cada artefato tem uma tabela de responsáveis por agrupamento/autor
- [ ] Nenhum diagrama foi aceito sem comparação com os achados reais da Entrega 1


**Relacionado:** [Ata da reunião de divisão](ata-reuniao-sub03.md)
