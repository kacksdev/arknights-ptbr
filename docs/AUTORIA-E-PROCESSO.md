# Autoria, ferramentas e processo

## Direção do projeto

**Arknights PT-BR é um projeto criado, dirigido, mantido e validado por Kacks.** O escopo, as prioridades, as decisões técnicas e editoriais, os testes nas plataformas, a compatibilidade declarada e a decisão de publicar permanecem sob responsabilidade do mantenedor.

## Uso do OpenAI Codex

O OpenAI Codex participa como ferramenta auxiliar. Ele pode ser usado para:

- inventariar e comparar estruturas técnicas;
- desenvolver automações e validadores;
- produzir traduções PT-BR em escala a partir do catálogo preparado pelo projeto;
- aplicar correções orientadas pelo mantenedor;
- organizar auditorias, métricas e documentação;
- acelerar tarefas repetitivas de engenharia e controle de qualidade.

O uso da ferramenta não transfere a direção nem a responsabilidade do projeto. Requisitos, problemas observados no uso real, aprovação dos resultados, testes e publicação continuam sendo conduzidos pelo mantenedor.

## Estado atual

Na versão `0.0.1-dev`, o trabalho é apenas preparatório. **Nenhum arquivo do cliente foi inventariado dentro deste projeto, nenhum catálogo foi extraído e nenhum texto de Arknights foi traduzido.** Essa informação será atualizada somente quando houver evidência reproduzível.

## Tradução e revisão

Quando o catálogo existir, cada entrada deverá registrar ao menos:

- texto de origem e tradução aplicada;
- identificador ou chave técnica;
- lote de processamento;
- estado de revisão;
- regras de preservação relevantes;
- validações estruturais executadas.

A cobertura de tradução e a revisão manual serão métricas separadas. Uma entrada traduzida por ferramenta não será apresentada como revisão humana independente. Correções manuais e decisões editoriais serão registradas como tal.

## Versões

- versões de desenvolvimento podem ter cobertura parcial e nenhuma build pública;
- versões públicas precisam declarar cliente e plataforma testados;
- notas de mudança pertencem à respectiva Release;
- `1.0.0` fica reservado para cobertura, revisão manual, consistência, formatação e validação completas.
