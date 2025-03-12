# DIO | Resumos Git/Github

## Versionamento de código:

Possibilita a contribuição de um mesmo projeto por diferentes desenvolvedores, bem como sua manutenção ao longo do tempo.
Uma versão muito conhecida e ultilizada pelo mercardo é o o (DVCS) ou distribuição DVS, com ele é realizado o clone do projeto para cada local de contribuição, onde cada desenvolver terá uma versão atualizada, assim como manter todo histórico de modificações e updates contendo informações de (autor, data, tipo de alteração). Ele salva todo histórico, além de possibilitar o trabalho offline no projeto e a sua contribuição feita somente no final do processo, ou de acordo com a necessidade de update do projeto final.

## Git:

É um tipo de programa usada para versionamento de código, ele é um distribuidor DVS, desenvolvido pelo Linus Torvalds, o mesmo desenvolvedor do sistema Linux. Ele disponibiliza essa distribuição open source, que possibilida desenvolvedores trabalhar de diferentes espaços fisicos e contribuir para um mesmo projeto.

## GitHub:

É o hospedor do seu projeto, onde será feito todos as contribuições e atualizações de versionamentos. Junto com o Git "comando usados para essa criação de pull de projeto possibilitando a integração com o local de hospedagem, GitHub."
Instalação do git =>

- 1.add-apt-repository ppa:git-core/ppa
- 2.apt update;
- 3.apt install git

Para config. --global(para todos os processos de commit futuros serem feitos pelo nome do usuário).
Usando o --local essas aplicações seriam feitas apenas para os commits locais

- 4.git config --global user.name ""
- 5.git config --global user.email ...
- 6.git config --global --list (permite verificar as configurações setadas)

---

## git add arquivo.name
