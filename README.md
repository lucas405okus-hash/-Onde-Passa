# Onde Passa?

Guia de transmissões oficiais de futebol, com agenda, busca e cadastro de canais/plataformas por partida.

## Estado atual

MVP estático publicado pelo GitHub Pages. A agenda é carregada sob demanda pela API [football-data.org](https://www.football-data.org/). A chave é inserida pelo usuário e fica armazenada apenas no navegador. A API de partidas **não fornece direitos de transmissão**: os canais devem ser confirmados e cadastrados manualmente no painel, com link oficial.

## Como usar

1. Abra o site.
2. Entre em **Configurar**.
3. Insira uma chave válida da football-data.org e salve.
4. Clique em **Buscar partidas**.
5. Em Cadastro de transmissão, escolha uma partida e informe canal/plataforma, acesso gratuito ou pago e o link oficial HTTPS.
6. A agenda exibe a transmissão cadastrada.

Os dados de transmissões ficam no armazenamento local do navegador. Use **Exportar dados** para guardar uma cópia. Limpar dados do navegador pode apagar esses registros.

## Publicação

O workflow em `.github/workflows/pages.yml` publica o conteúdo de `main` no GitHub Pages. Em repositório privado, a disponibilidade do Pages depende do plano e das configurações da conta. Se o deploy não iniciar, habilite Pages em Settings → Pages e selecione GitHub Actions.

## Limitações conhecidas do MVP

- Não há ainda uma base central compartilhada de canais: cada navegador mantém seus próprios cadastros.
- A disponibilidade de competições depende do plano da football-data.org.
- Os direitos de transmissão variam por país e temporada. Nenhum canal é presumido automaticamente.
- O site não hospeda nem retransmite vídeo; apenas direciona para páginas oficiais.
