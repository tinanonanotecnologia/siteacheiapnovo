# ACHEI! Macapá — cópia integral

Origem autorizada pelo proprietário: https://site-achei.vercel.app/

Captura em 29/09/2026. A pasta `dist/` contém os 37 arquivos públicos necessários ao site, preservados byte a byte: HTML, CSS, JavaScript, favicon, 11 imagens JPG e 22 arquivos de fontes WOFF/WOFF2.

Nenhuma alteração de design, conteúdo, formatos, dimensões de imagens, tipografia, SVGs ou animações foi aplicada. Os links e comportamentos são os mesmos da origem. Não há dependência do servidor original para carregar os recursos visuais copiados.

`CLONE-MANIFEST.json` registra os endereços de origem, tamanhos e hashes SHA-256 de todos os arquivos. Antes da publicação foram verificadas a integridade dos 37 arquivos, as referências de recursos e a sintaxe JavaScript.

Site estático, sem etapa de compilação. A configuração de publicação está em `.openai/hosting.json`.

O projeto anterior `achei-macapa` retornou `project_not_found` e não consta entre os Sites acessíveis. Por isso, esta cópia foi registrada como um projeto independente, preservando o checkout anterior.

## Importação na Vercel

O repositório inclui `vercel.json` com `dist` definido como diretório de saída e sem comando de build. O conteúdo público também está espelhado na raiz (`index.html`, `assets/`, `img/` e `favicon.svg`) para compatibilidade com importações que usam a configuração padrão da Vercel. Ao importar, mantenha o Framework Preset como `Other` e deixe o Build Command vazio.
