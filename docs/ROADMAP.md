# Roadmap

O roadmap descreve critérios de conclusão, não datas prometidas.

## Fase 0: Preparação

**Em andamento.**

- estruturar o repositório público;
- definir escopo, autoria e critérios de segurança;
- preparar identidade visual e documentação;
- estabelecer PC como primeira plataforma de implementação.

## Fase 1: Mapeamento do cliente de PC

- registrar a versão oficial instalada e os hashes relevantes;
- identificar formatos, bancos, pacotes, fontes e cadeia de carregamento;
- separar dados proprietários de ferramentas e metadados que podem ser publicados;
- testar extração e reconstrução somente em cópias;
- documentar o comportamento de atualização do cliente.

## Fase 2: Catálogo técnico

- extrair textos com IDs e contexto disponível;
- preservar placeholders, marcações, quebras e relações entre registros;
- classificar duplicatas, nomes próprios, músicas e conteúdo não traduzível;
- criar importação e exportação reversíveis;
- validar round-trip antes da primeira tradução.

## Fase 3: Tradução integral

- traduzir o catálogo em lotes contextuais;
- registrar origem e estágio de revisão de cada entrada;
- manter glossário e terminologia do projeto;
- executar auditorias estruturais e linguísticas a cada lote;
- publicar métricas reproduzíveis de cobertura.

## Fase 4: Build de PC

- produzir um pacote que não inclua arquivos proprietários;
- documentar instalação, atualização, remoção e recuperação;
- validar inicialização, narrativa, interface, combate e eventos;
- medir desempenho e comportamento após atualização do cliente;
- falhar de forma segura em versões não reconhecidas.

## Fase 5: Adaptação Android

- confirmar quais dados e ferramentas podem ser compartilhados com a versão de PC;
- adaptar empacotamento e instalação ao Android sem exigir a instalação de PC;
- validar permissões, armazenamento, atualização e remoção;
- repetir auditoria estrutural, desempenho e QA na plataforma móvel.

## Fase 6: Candidato estável

- cobertura textual integral do conteúdo mapeado;
- instalação e remoção reproduzíveis nas plataformas declaradas;
- zero falha estrutural conhecida;
- compatibilidade informada por versão de cliente;
- documentação, hashes e notas de versão completos.

Uma versão `1.0.0` exigirá, além da cobertura técnica, revisão manual contextual completa, consistência editorial, formatação e validação no jogo. Esse marco não possui prazo definido.
