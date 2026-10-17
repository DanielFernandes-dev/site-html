# Site HTML

Coleção de páginas estáticas criada para praticar conceitos básicos de HTML. A página inicial reúne links para diferentes versões e abre alguns exemplos em iframes.

## Como executar

Não é necessário instalar dependências nem compilar o projeto. Na raiz do repositório, inicie um servidor HTTP local:

```bash
python3 -m http.server 8000
```

Depois, acesse [http://localhost:8000](http://localhost:8000). O servidor deve ser iniciado na raiz do repositório porque várias páginas usam caminhos absolutos, como `/fotos/...` e `/rotas/...`.

## Estrutura

| Caminho | Conteúdo |
| --- | --- |
| `index.html` | Página inicial com links para as versões e exemplos em iframes. |
| `rotas/` | Páginas de exercícios com texto, links, iframes, vídeo incorporado e formulários. |
| `auxilar/` | Exemplos de álbum com mapa de imagem, listas e tabelas. |
| `audios.html` e `instagram.html` | Páginas de teste das tags de áudio e vídeo. |
| `fotos/`, `audios/` e `videos/` | Arquivos de mídia usados pelas páginas. |

O projeto usa HTML e CSS embutido nas páginas. Alguns exemplos também incorporam conteúdo externo, que requer conexão com a internet.
