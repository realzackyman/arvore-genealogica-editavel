# FAM TREE

Site estático para qualquer pessoa construir a sua própria árvore genealógica no navegador.

## Como usar

Abre `index.html` no browser ou usa a versão publicada no GitHub Pages.

Funcionalidades:

- adicionar e editar pessoas
- mostrar idade automaticamente a partir do ano/data de nascimento
- pesquisar dados públicos por nome via Wikidata
- arrastar cartões no ecrã
- ligar pai/mãe, irmãos e casal
- definir relações directamente no editor da pessoa
- organizar automaticamente
- procurar pessoas
- alternar entre modo claro e modo escuro
- exportar e importar JSON
- imprimir
- guardar automaticamente no navegador

## Privacidade

FAM TREE não tem servidor, login ou base de dados. Os dados de cada pessoa ficam guardados apenas no `localStorage` do browser dessa pessoa.

A pesquisa por nome consulta fontes públicas diretamente a partir do browser. Só costuma encontrar pessoas com presença em bases públicas como Wikidata/Wikipedia; familiares privados normalmente não aparecem.

Usa a opção `Exportar` para criar cópias de segurança em JSON. Quem limpar os dados do browser pode perder a árvore se não tiver exportado uma cópia.
