<p align="center">
  <img src="src/images/icon.png" width="128"/>
  <p align="center"><b>Livro sobre a construção do Android</b></p>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white"/><br>
<img src="https://img.shields.io/badge/lineageos-167C80?style=for-the-badge&logo=lineageos&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/><br>
<img src="https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff&style=for-the-badge"/>
<img src="https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white"/>
</p>

## Introdução

Este livro é um guia "completo" para construir o sistema operacional Android a partir do código-fonte utilizando o Linux e assim entender como esse sistema operacional Android funciona em um nível baixo. Escrito em um estilo acessível e compreensível, o guia oferece aos leitores uma oportunidade única de se aprofundar no funcionamento interno do Android e obter uma compreensão "completa" de como funciona essa popular plataforma móvel.

# ❓ Quero acrescentar/corrigir algo, como posso fazer isso corretamente?

* Se você é um contribuidor deste repositório, crie um branch separado com um nome adequado às suas alterações, faça alterações nele e faça uma solicitação de mesclagem. 
* Se você não é contribuidor, o procedimento é o mesmo para você, apenas você faz uma solicitação de mesclagem a partir do seu fork ou de outra forma.

# 🌎 Quero contribuir na tradução, como posso fazer isso?
Leia [`Translations_pt.md`](Translations_pt.md) e faça uma tradução de acordo com essas instruções e envie-nos um Pull Request. Verificaremos sua tradução e se estiver correta, a aceitaremos.

# 🔨 Preparação
Para gerar um livro, usamos o utilitário [`mdbook`](https://github.com/rust-lang/mdBook).
1. <b>🦀 Instalação</b>

	```
	cargo install mdbook mdbook-i18n-helpers mdbook-epub mdbook-external-links
	```
2. <b>🔨 Disposição</b><br>
As páginas HTML serão geradas no diretório `book/`, que pode ser hospedado via nginx ou usando GitHub Actions.
	```
	mdbook build
	```
3. <b>🚀 Finalização</b><br>
Para ver o resultado, execute este comando
	```
	mdbook serve
	```
   O utilitário iniciará um servidor Web local em `localhost` na porta 3000.
