# Estratégia de plataformas

## Plataformas-alvo

O projeto pretende atender:

- **PC/Windows**, pela distribuição oficial disponível no Google Play Games;
- **Android**, pela distribuição oficial do Google Play.

Referências oficiais: [Arknights no Google Play](https://play.google.com/store/apps/details?id=com.YoStarEN.Arknights) e [Google Play Games para PC](https://play.google.com/googleplaygames/exploregames).

## Por que o PC vem primeiro

O PC oferece um ambiente mais controlável para inventário, cópias de segurança, comparação de arquivos, logs, reconstrução e recuperação. Isso permite confirmar os formatos reais e construir o catálogo com menos risco antes de adaptar qualquer instalação móvel.

Essa prioridade não significa que a versão Android receberá uma tradução inferior. Ela significa que a base técnica será comprovada primeiro onde é mais fácil diagnosticar e reverter alterações.

## Distribuição no Windows

A primeira build para PC será entregue como um único instalador gráfico. Ele
deverá localizar ou receber a pasta do cliente, validar a compatibilidade antes
de gravar, preparar mudanças fora da instalação ativa, criar backup com
manifesto e executar rollback automático em caso de falha. A mesma interface
reunirá instalação, atualização, reparo, verificação e remoção.

O arquivo final será publicado somente depois de passar por matriz automatizada
e ciclo completo em cliente limpo, incluindo inicialização do jogo, inspeção do
log e restauração do estado original. A Release informará SHA-256, manifesto e
versão exata do cliente testado.

## Condição para iniciar o Android

A adaptação móvel começa depois que o projeto souber:

- quais textos e identificadores são compartilhados entre as plataformas;
- quais arquivos ou bancos diferem;
- como cada cliente valida e atualiza seus dados;
- como instalar e remover o mod sem incluir conteúdo proprietário;
- como preservar dados do usuário e recuperar o cliente original.

O pacote de Android será versionado e testado separadamente. Compatibilidade no PC nunca será usada como prova automática de compatibilidade no Android.

O instalador gráfico de Windows não será reutilizado como solução móvel. O
método de distribuição para Android será definido apenas depois que permissões,
armazenamento, atualização e reversão forem comprovados na plataforma.

## Atualizações futuras

O objetivo é que uma atualização desconhecida não quebre nem bloqueie o jogo. A implementação deverá reconhecer o que foi validado e interromper a aplicação da tradução com uma mensagem clara quando a estrutura mudar de forma incompatível. Conteúdo novo pode aparecer sem tradução até ser catalogado; isso é diferente de permitir que o mod danifique o cliente.
