### Git e Github

**Git** pronuncia-se [[git\]](https://pt.wikipedia.org/wiki/Wikipédia:AFI_para_português_e_galego) (ou /ɡɪt/ em inglês britânico[[1\]](https://pt.wikipedia.org/wiki/Git#cite_note-1)[[2\]](https://pt.wikipedia.org/wiki/Git#cite_note-2)) é um [sistema de controle de versões](https://pt.wikipedia.org/wiki/Sistema_de_controle_de_versões) distribuído, usado principalmente no [desenvolvimento de software](https://pt.wikipedia.org/wiki/Desenvolvimento_de_software), mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo (Exemplo: alguns livros digitais são disponibilizados no [GitHub](https://pt.wikipedia.org/wiki/GitHub) e escrito aos poucos publicamente). O Git foi inicialmente projetado e desenvolvido por [Linus Torvalds](https://pt.wikipedia.org/wiki/Linus_Torvalds) para o desenvolvimento do [kernel Linux](https://pt.wikipedia.org/wiki/Linux_(núcleo)), mas foi adotado por muitos outros projetos.

**GitHub**  é uma plataforma de hospedagem de código-fonte e arquivos com [controle de versão](https://pt.wikipedia.org/wiki/Sistema_de_controle_de_versões) usando o [Git](https://pt.wikipedia.org/wiki/Git). Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou [Open Source](https://pt.wikipedia.org/wiki/Open-source) de qualquer lugar do mundo. GitHub é amplamente utilizado por programadores para divulgação de seus trabalhos ou para que outros programadores contribuam com o projeto, além de promover fácil comunicação através de recursos que relatam problemas ou mesclam [repositórios](https://pt.wikipedia.org/wiki/Repositório) remotos (*issues, pull request*).

O GitHub é mundialmente usado e chega a ter mais de 36 milhões de usuários ativos mundialmente contribuindo em projetos comerciais ou pessoais. Hoje o GitHub abriga mais de 100 milhões de projetos,[[2\]](https://pt.wikipedia.org/wiki/GitHub#cite_note-about-github-2) alguns deles que são conhecidos mundialmente. [WordPress](https://pt.wikipedia.org/wiki/WordPress.com), [GNU/Linux](https://pt.wikipedia.org/wiki/GNU/Linux), [Atom](https://pt.wikipedia.org/wiki/Atom), Electron. GitHub também oferece suporte ao recurso de organização que é amplamente utilizado por aqueles que querem uma escala maior para seus projetos. Na maioria das vezes, o recurso é usado por empresas já existentes como a [Google](https://pt.wikipedia.org/wiki/Google), [Microsoft](https://pt.wikipedia.org/wiki/Microsoft) e [WordPress](https://pt.wikipedia.org/wiki/WordPress.com).

Diferença de Git e Github:Em suma, o **Git** é um software de controle de versão, já o **GitHub** é como se fosse uma rede social de pessoas desenvolvedoras, ou seja, uma plataforma na qual podem compartilhar projetos.

### Comandos básicos do Git:

-Cd-mudar de pasta;                -Cd-mudar de pasta, Linux;

-Dir-listar pastas;                      -Ls-listar pasta ,Linux;

-Mkdir-criar pastas;                  -Mkdir-criar pastas,Linux;

-Del/rmdir-deletar pastas;      -Rm-rf-deletar pastas,Linux.

### Git bach

O **Git Bash** é o aplicativo para ambientes do Microsoft **Windows** que oferece a camada de emulação para a experiência de linha de comando **Git**. **Bash** é acrônico para "Bourne Again Shell".

### Sha1

Em [criptografia](https://pt.wikipedia.org/wiki/Criptografia), **SHA-1** é uma [função de dispersão criptográfica](https://pt.wikipedia.org/wiki/Função_hash_criptográfica) (ou função hash criptográfica) projetada pela [Agência de Segurança Nacional](https://pt.wikipedia.org/wiki/Agência_de_Segurança_Nacional) dos Estados Unidos e é um [Padrão Federal de Processamento de Informação](https://pt.wikipedia.org/wiki/Federal_Information_Processing_Standard) dos Estados Unidos publicado pelo [Instituto Nacional de Padrões e Tecnologia](https://pt.wikipedia.org/wiki/National_Institute_of_Standards_and_Technology) (NIST).[[2\]](https://pt.wikipedia.org/wiki/SHA-1#cite_note-2)

SHA-1 produz um valor de dispersão de 160 [bits](https://pt.wikipedia.org/wiki/Bit) (20 [bytes](https://pt.wikipedia.org/wiki/Byte)) conhecido como resumo da mensagem. Um valor de dispersão SHA-1 é normalmente tratado como um número [hexadecimal](https://pt.wikipedia.org/wiki/Hexadecimal) de 40 dígitos.

### Blobs

Um blob, é uma coleção de dados binários armazenados como uma única entidade em um sistema de gerenciamento de banco de dados. Blobs geralmente são objetos de imagem, áudio ou outro objetos multimedia, apesar de algumas vezes código binário executável ser armazenado como um blob.

### Trees

Cada arquivo no **Git é** armazenado como um objeto **blob**, por exemplo, a partir do conteúdo do arquivo logo. png ele gera um hash que será armazenado em algum lugar endereçável como aa1b2fb696a831c89c53f787e03d863691d2b671 . O mesmo ocorre com o arquivo app.

### Commits

Os **commits** são as unidades estruturais de um cronograma de projeto **Git**. Podem ser considerados instantâneos ou marcos ao longo do cronograma de um projeto **Git**. São criados com o comando **git commit** para capturar o estado de um projeto naquele momento.

### SSH e Tokens

O **SSH** é um protocolo de rede que permite que a conexão com determinados servidores por meio de uma comunicação criptografada, trazendo mais segurança para as transações de dados.

O que é esse **Token** de Acesso? Um **token** de acesso, de forma simplificada, seria uma chave em um formato como e962e591092e9830f8ec6c2a4166e8655b768e88 que te permite ter acesso a algo. No caso do **Github** você usaria uma chave assim no lugar da senha da sua conta ao executar operações pela linha de comando ou na API.

### Git init

**Git init** é um comando único que você usa durante a configuração inicial de um novo repositório. A execução desse comando cria um novo subdiretório . **git** no diretório de trabalho atual. Essa ação também vai criar uma ramificação principal.

```
git init
```

### Git add

O comando **git add** adiciona uma alteração no diretório ativo à área de staging. Ele diz ao **Git** que você quer incluir atualizações a um arquivo específico no próximo commit. No entanto, **git add** não tem efeito real e significativo no repositório — as alterações não são gravadas mesmo até você executar **git** commit .Ex:

```
git add temp.txt
```

### Git commit

O comando **git commit** captura um instantâneo das mudanças preparadas do projeto no momento. Os instantâneos com **commit** podem ser considerados versões "seguras" de um projeto, o **Git** nunca os altera, a menos que você peça a ele.

```
git commit –m “coloque sua mensagem aqui”
```

### Git clone

O **git clone** é um utilitário de linha de comando que é usado para selecionar um repositório existente e criar um **clone** ou cópia do repositório de destino. Nesta página, vamos discutir opções de configuração estendidas e casos de uso comuns do **git clone** .

```
git clone alex@93.188.160.58:/path/to/repository
```

```
git clone /path/to/repository
```

### Git config

Um dos comandos git mais usados é o **git config** que pode ser usado para definir valores de configuração específicos do usuário como e-mail, algoritmo preferido para diff, nome de usuário e formato de arquivo etc. Por exemplo, o seguinte comando pode ser usado para definir o email:

```
git config --global user.email sam@google.com
```

###  Git push

O comando **git push** é usado para enviar o conteúdo do repositório local para um repositório remoto. O comando **push** transfere commits do repositório local a um repositório remoto. É o oposto do comando **git** fetch , que importa commits para branches locais, enquanto o comando **push** exporta commits para branches remotos.

```
git push <remote> <nome-do-branch>
```

### Git pull

O comando **git pull** é usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais. Fazer o merge de alterações upstream remotas no repositório local é algo comum em fluxos de trabalho de colaboração baseados em **Git**.

git pull <remote>

### Git branch

O comando **git branch** permite criar, listar, renomear e excluir ramificações. Ele não permite alternar entre as ramificações ou reunir um histórico bifurcado de novo. Por esse motivo, o comando **git branch** é muito integrado com os comandos **git** checkout e **git** merge.

git branch <nome-da-branch>
