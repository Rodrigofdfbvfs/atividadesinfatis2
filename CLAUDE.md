# Kit Habilidades Motoras — Landing Page

Landing page estática de venda (HTML único, CSS e JS inline) em [index.html](index.html).

## Workflow de git (importante)

**Sempre commitar e dar push ao concluir uma alteração.** Não é preciso pedir
autorização a cada vez — essa permissão é permanente.

- **Granularidade:** um commit por tarefa concluída, não por arquivo editado.
  Terminou o que o usuário pediu, commita.
- **Push:** sempre `git push` para o `origin` após o commit. O GitHub deve
  refletir o estado local.
- **Remote:** `origin` → https://github.com/Rodrigofdfbvfs/atividadesinfatis2
  (`origin-antigo` aponta para um repo anterior; não usar)
- Mensagens de commit em inglês, no imperativo.

## Notas do projeto

- As imagens da página são carregadas do `i.ibb.co` (hospedadas externamente).
  Os PNGs locais (`foto1/2/3.png`) são apenas os arquivos-fonte e estão no
  `.gitignore`.
- Links de checkout apontam para `pay.lowify.com.br`. Um script no fim do
  `index.html` propaga parâmetros UTM da URL para todos esses links.
- Servidor local para testes: não há Python instalado; usar um servidor
  estático em Node (porta 3000 costuma estar ocupada, usar 8080).

## Pendências

- O botão "Quero o Premium com desconto" do modal de upsell (R$ 11,90) ainda
  aponta para o checkout de R$ 15,90 (`product_id=LhQBNG`). Trocar quando o
  link do checkout de R$ 11,90 existir.
