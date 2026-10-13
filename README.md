# Portfólio pessoal · Eduardo

Site pessoal estático com apresentação, conhecimentos e uma página dedicada aos projetos. Os textos biográficos e os destinos externos foram preservados, exceto correções de escrita e navegação interna.

## O que o projeto faz

- Layout mais fluido, cards arredondados e cores com contraste melhor.
- Links internos relativos, compatíveis com publicação em subdiretórios.
- Nomes acessíveis nos links de GitHub e LinkedIn, com proteção ao abrir nova aba.
- Link para pular conteúdo, foco visível e alvos de interação maiores.
- Links de projetos com nomes descritivos e retorno à página inicial.

## Executar

Abra `index.html` em um navegador moderno. Não há instalação de dependências, build ou servidor obrigatório. Para desenvolvimento, também é possível servir a pasta com qualquer servidor estático, por exemplo `python -m http.server 8000` e acessar `http://localhost:8000`.

## Estrutura

- `index.html`: estrutura e conteúdo.
- `style.css`: apresentação.
- `assets/`: foto de perfil.
- `projetos/`: página de projetos e seus estilos.

## Limites e cuidados

- A biografia e os projetos refletem o conteúdo original do repositório e podem precisar de atualização pessoal.
- Não há formulário de contato, backend ou integração de dados.
- Font Awesome é carregado via CDN para os ícones; nomes acessíveis continuam disponíveis.
- Os links de portfólio e projetos externos foram preservados; disponibilidade externa não foi validada.

## Roteiro de verificação manual

1. Abra a página inicial e navegue até Projetos e de volta.
2. Confira layout em 320, 768 e 1440 pixels e zoom de 200%.
3. Use Tab para acessar redes sociais e projetos.
4. Verifique a foto e os links externos antes de divulgar.

Não há suíte de testes de navegador configurada no repositório. O roteiro acima deve ser executado antes de publicar alterações. Nenhum deploy é feito por estes arquivos.
