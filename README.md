# Site — emanuellemonteiro.adv.br

Repositório privado criado para dar suporte aos ajustes no site da Monteiro Advocacia Tributária (www.emanuellemonteiro.adv.br).

## Importante: o que este repositório contém (e o que não contém)

O site atual roda em WordPress. O código-fonte real de um site WordPress (arquivos de tema PHP, plugins, banco de dados) fica hospedado no servidor de hospedagem — ele não pode ser obtido apenas visitando as páginas públicas do site, nem por mim nem por qualquer ferramenta de "cópia" de página.

Por isso, este repositório foi iniciado com:

- Este README, explicando o cenário;
- - CONTEUDO-REFERENCIA.md, um resumo do conteúdo textual das páginas do site (capturado a partir das páginas publicadas), útil como referência enquanto o código de verdade não é importado.
 
  - ## Como trazer o código real do site para cá
 
  - Para o seu dev (ou "vibe coder") conseguir editar o site de verdade, o caminho correto é:
 
  - 1. Acesso ao provedor de hospedagem (FTP/SFTP ou o "Gerenciador de Arquivos" do painel de hospedagem) — de lá dá para baixar a pasta do tema em wp-content/themes/... e, se houver, plugins customizados em wp-content/plugins/...
    2. 2. Ou um plugin de exportação/migração, como All-in-One WP Migration ou Duplicator, que gera um pacote completo do site (tema + plugins + banco de dados) para importar em outro ambiente ou versionar.
       3. 3. Depois de ter esses arquivos (no computador ou numa pasta conectada), é só avisar que dá para organizar e enviar tudo para este repositório.
         
          4. ## Páginas do site (mapa atual)
         
          5. - / — Início
             - - /sobre/ — Sobre
               - - /areas-de-atuacao/ — Áreas de Atuação
                 - - /blog/ — Blog
                   - - /contato/ — Contato
                     - - 3 posts publicados no blog (ver CONTEUDO-REFERENCIA.md)
                       - 
