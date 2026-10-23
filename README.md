# Eclipse MOBA — nuvem

PC: /pc.html. Celular: /mobile44.html. Ate dez jogadores com bots nas vagas livres.

Build: `node bootstrap.cjs`. Start: `node app/cloud-server.cjs`.

Os arquivos source.partNNN sao partes do pacote completo das fontes e assets. O build verifica SHA-256, reconstroi e extrai as fontes em app/. A divisao permite enviar os modelos 3D pelo limite de upload do GitHub. Nao sao executaveis nativos. O jogo fonte completo esta dentro do pacote, sem tokens, sessoes ou dados de jogadores.

Plano preparado: Render gratuito. Pode adormecer apos 15 minutos sem uso; um novo acesso reativa o servico. Pontuacao local do servidor nao e persistente nesse plano. A partida ainda e simulada pelo navegador do lider, que pode ser o celular; nao precisa do PC do criador ligado.
