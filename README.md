# UNEMAT-TeX

O UNEMAT-TeX é um modelo baseado no [abnTeX2](http://www.abntex.net.br/) desenvolvido para auxiliar os alunos da Universidade do Estado de Mato Grosso (UNEMAT) em seus trabalhos de conclusão de curso. O UNEMAT-TeX é configurável e adaptável para ser utilizado em praticamente todos os cursos da UNEMAT. Espera-se que o projeto seja um modelo de trabalho acadêmico que implemente todas as exigências das normas da ABNT sem a necessidade de se preocupar com o estilo ou formatação do documento.

## Modelos disponíveis

O UNEMAT-TeX procura implementar o Regulamento de Trabalho de Conclusão de Curso (TCC) dos Cursos de Graduação Presenciais da UNEMAT. Ele inclui os modelos:

* Pré-projeto do TCC
* Trabalho de Conclusão de Curso (TCC)

## Por onde começo?

Siga os seguintes passos:

1. [Clique aqui](https://github.com/lkaranl/PRE-PROJETO-TCC-LATEX/archive/master.zip) para baixar o modelo UNEMAT-TeX;
2. Descompacte o arquivo no diretório onde você deseja guardar os arquivos do seu trabalho;
3. Crie o seu texto a partir do arquivo **tcc.tex** (ou **pre-projexo.tex**) distribuído no arquivo baixado. O arquivo possui comentários explicativos.

> Se você é iniciante em LaTeX ou em abnTex2, dê uma conferida nos [manuais do abnTex2](https://github.com/abntex/abntex2/wiki/PorOndeComecar).


> Consulte o [manual de referências](http://get-software.net/macros/latex/contrib/abntex2/doc/abntex2cite-alf.pdf) para entender como manter a bibliografia e fazer citações no seu documento.

## Como instalar editor e bibliotecas?
* Para usar o Latex você precisa ter instalado na sua máquina um editor de texto Latex, compilador Latex e algumas bibliotecas para o uso de pacotes específicos, como o da ABNT.<br/>
1. Para instalar o editor Latex TexStudio no Windows 10:<br/>
Texstudio (Editor de texto) [Clique aqui](https://github.com/texstudio-org/texstudio/releases/download/2.12.14/texstudio-2.12.14-win-qt5.exe)<br/>
MikTex (Compilador) [Clique aqui](https://miktex.org/download/ctan/systems/win32/miktex/setup/windows-x64/basic-miktex-2.9.7031-x64.exe)<br/>
> Observacao: Quando compilado pela primeira vez, no windows, geralmente demora um pouco, pois ele está pesquisando e instalando as bibliotecas faltantes. 

2. Para instalar o Latex TexStudio no Manjaro:<br/>
`sudo pacman -S texstudio`<br/>
> Bibliotecas<br/>
`$sudo pacman -S texlive-publishers texlive-latexextra`<br/>
`$yaourt -S abntex2 `<br/>

3. Para instalar o editor Latex TexStudio no Ubuntu ou Mint: (testado no Xubunto 19.04)<br/>
`$sudo apt install texstudio`<br/>
> Bibliotecas<br/>
`$sudo apt install texlive-publishers texlive-lang-portuguese texlive-latex-extra texlive-fonts-recommended`


## Observações

O UNEMAT-TeX é fornecido gratuitamente e sem garantias e pode ser redistribuído livremente para fins acadêmicos. Trata-se de um produto extra-oficial e não está oficialmente vinculado a UNEMAT.
