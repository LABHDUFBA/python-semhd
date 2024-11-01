# Dia 0: antes de começar

## Preparando o ambiente de trabalho

Antes de iniciarmos o curso, é importante que você prepare seu computador com alguns programas e ferramentas que utilizaremos.

Nessa página, você encontrará instruções para instalar o Python no Windows, macOS e Linux, o VSCode (assim como a extensão do Python e o pacote de idioma Português) e o GitBash (para Windows).

### Como instalar o Python?

#### Instalando o Python no Windows:

Veja o vídeo de instalação, também [disponível no YouTube](https://youtu.be/QPmIsKgdifI):

https://github.com/ericbrasiln/python-puc/assets/58128421/be860402-a1e9-4557-b1a6-1ff277cb65fd

#### Instalando o Python no Linux:

Nas distribuições Linux baseadas em Debian, como o Ubuntu, o Python já vem instalado por padrão. Para verificar se o Python está instalado, abra o terminal e digite:

```bash
python3 --version
```

Caso o Python não esteja instalado, digite:

```bash
sudo apt install python3
```

#### Instalando o Python no Mac:

Para instalar o Python no Mac, você pode utilizar algum gerenciador de pacotes, como Homebrew ou MacPorts. Para instalar o Python utilizando o Homebrew, digite no terminal:

```bash
brew install python3
```

Para instalar o Python utilizando o MacPorts, digite no terminal:

```bash
sudo port install python3
```

Para informações sobre Homebrew, acesse https://brew.sh/pt-br/ e para informações sobre MacPorts, acesse https://www.macports.org/install.php

### Ambiente de trabalho no VSCode

Instale o VSCode e as extensões Python, e o pacote de idioma Português (Brasil).

Veja o vídeo de instalação, também [disponível no YouTube](https://youtu.be/VyY1xDSl6wU):

https://github.com/ericbrasiln/python-puc/assets/58128421/7bc71a5d-0f3b-4062-9e2a-9ba036ffb3dc

### O temido Terminal

#### No macOS e Linux

Para abrir o terminal no macOS, basta pressionar as teclas `Command + Espaço` e digitar `terminal`. Na maioria das distribuições Linux, pressione `Ctrl + Alt + T`. Ou busque por `terminal` no menu de aplicativos.

#### E no Windows?

Duas opções: usar o app Terminal do Windows, ou instalar o GitBash.

##### Usando o app Terminal do Windows

O app Terminal do Windows é uma ferramenta poderosa e que vem sendo aprimorada a cada versão do Windows 10. Para abri-lo, basta buscar por `terminal` no menu de aplicativos.

##### Instalando o GitBash

O GitBash é uma ferramenta que traz um terminal mais poderoso e com mais funcionalidades que o app Terminal do Windows. Além disso ele é compatível com os comandos do terminal do macOS e Linux, e é instalado junto com o Git. Git é uma ferramenta de controle de versão de código fonte. Para saber mais sobre o Git, ver a [lição do Programming Historian, Git como ferramenta metodológica em projetos de História (parte 1)](https://programminghistorian.org/pt/licoes/git-ferramenta-metodologica-projetos-historia-1).

Veja o vídeo de instalação, também [disponível no YouTube](https://youtu.be/PGIuYvkctj0):

https://github.com/ericbrasiln/python-puc/assets/58128421/de51310c-c074-49e0-9b21-909543a67483

Com ele poderemos usar os mesmos comandos do terminal do macOS e Linux.

###### Executando o python no GitBash

Para executarmos o python no GitBash precisamos executar mais um comando. Ele incluirá um alias (apelido) na configuração do bash para que todas vez que executarmos `python`, o GitBash execute o executável correto:

```
echo "alias python='winpty python.exe'" >> ~/.bashrc
```

Para uma explicação completa desse comando, ver esta [resposta no StackOverflow](https://stackoverflow.com/a/36530750/12751702).

Reinicie o GitBash, e execute `python`!

## Opcionais mas muito recomendados

- Crie um conta no GitHub: [https://github.com/signup](https://github.com/signup)
- Leia a lição "Introdução à Linha de Comando Bash" de Ian Milligan e James Baker no [The Programming Historian](https://programminghistorian.org/en/lessons/intro-to-bash). A versão em português da lição está em faze de revisão e sua pré-visualização pode ser acessada [aqui](http://programminghistorian.github.io/ph-submissions/pt/esbocos/traducoes/introducao-linha-comando-bash)

---

[Próximo →](dia1.ipynb)

[← Anterior](README.md)

[↑ Início](#dia-0-antes-de-começar)
