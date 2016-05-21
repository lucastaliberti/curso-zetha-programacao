Intro Steps Para Pagina:

Baixar Ruby (Ruby intaller for windows)

Em seguida usar comando gem para instalar o bundler

"gem install bundler"

Em seguida criamos o repositório no github

Clonar o repositório no github

"git clone usuário.github.io.git"

Criação do arquivo index

" echo "Hello World" >> index.html "

Verificar se foi criado o arquivo:
" pwd "

Adicionar arquivos à area index do git:
" git add . "

Em seguida realizar o commit:
" git commit -m "Info sobre o commit" "

Enviar as alterações locais ao repositório:
"git push"

Segue demonstração

raph_@DESKTOP-M09DN2G MINGW64 ~
$ ruby -v
ruby 2.3.0p0 (2015-12-25 revision 53290) [x64-mingw32]

raph_@DESKTOP-M09DN2G MINGW64 ~
$ gem install bundler
Successfully installed bundler-1.12.4
Parsing documentation for bundler-1.12.4
Installing ri documentation for bundler-1.12.4
Done installing documentation for bundler after 22 seconds
1 gem installed

raph_@DESKTOP-M09DN2G MINGW64 ~
$ bundler -v
Bundler version 1.12.4

raph_@DESKTOP-M09DN2G MINGW64 ~
$ git clone https://github.com/raphaelcfa/raphaelcfa.git
Cloning into 'raphaelcfa'...
warning: You appear to have cloned an empty repository.
Checking connectivity... done.

raph_@DESKTOP-M09DN2G MINGW64 ~
$ rm -rf raphaelcfa/

raph_@DESKTOP-M09DN2G MINGW64 ~
$ git clone https://github.com/raphaelcfa/raphaelcfa.github.io.git
Cloning into 'raphaelcfa.github.io'...
warning: You appear to have cloned an empty repository.
Checking connectivity... done.

raph_@DESKTOP-M09DN2G MINGW64 ~
$ cd raphaelcfa.github.io/

raph_@DESKTOP-M09DN2G MINGW64 ~/raphaelcfa.github.io (master)
$ echo "Hello World!"
Hello World!

raph_@DESKTOP-M09DN2G MINGW64 ~/raphaelcfa.github.io (master)
$ echo "Hello World!" >> index.html

raph_@DESKTOP-M09DN2G MINGW64 ~/raphaelcfa.github.io (master)
$ pwd
/c/Users/raph_/raphaelcfa.github.io

raph_@DESKTOP-M09DN2G MINGW64 ~/raphaelcfa.github.io (master)
$ ^C

raph_@DESKTOP-M09DN2G MINGW64 ~/raphaelcfa.github.io (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

Did you mean this?
        add

raph_@DESKTOP-M09DN2G MINGW64 ~/raphaelcfa.github.io (master)
$ git add .
warning: LF will be replaced by CRLF in index.html.
The file will have its original line endings in your working directory.

raph_@DESKTOP-M09DN2G MINGW64 ~/raphaelcfa.github.io (master)
$ git commit -m "Commit inicial"
[master (root-commit) b67b8aa] Commit inicial
warning: LF will be replaced by CRLF in index.html.
The file will have its original line endings in your working directory.
 1 file changed, 1 insertion(+)
 create mode 100644 index.html

raph_@DESKTOP-M09DN2G MINGW64 ~/raphaelcfa.github.io (master)
$ git push
Counting objects: 3, done.
Writing objects: 100% (3/3), 231 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/raphaelcfa/raphaelcfa.github.io.git
 * [new branch]      master -> master
