# Git | Lista de Comandos 
Uma lista contendo os comandos mais utilizados e importantes do Git, elaborada utilizando materiais de referência que estão listados a seguir.

| Referência | Link |
| --- | --- |
| GitHub &#124; Git Cheat Sheet | [PDF](https://github.com/kunal-kushwaha/DSA-Bootcamp-Java/blob/main/lectures/01-git/git-cheat-sheet-education.pdf) |
| Git Documentation | [URL](https://git-scm.com/book/en/v2) |

## 🛠️ Configuração
Comandos utilizados para configurar informações de usuário. Lembre-se de utilizar o comando --global para que estas informações possam ser utilizadas em outros repositórios.

<dl>
<dt><strong>git config --global user.name "[nome sobrenome]"</strong></dt>
<dd>Define um nome para identificação do autor</dd>
<dt><strong>git config --global user.email “[email]”</strong></dt>
<dd>Define um email para identificação do autor</dd>
<dt><strong>git config --global color.ui</strong></dt>
<dd>Define a coloração do texto automaticamente para melhor visualização</dd>
</dl>

## 💻 Inicialização
Comandos utilizados para inicializar ou copiar um repositório.

<dl>
<dt><strong>git init</strong></dt>
<dd>Inicializa um diretório como repositório Git</dd>
<dt><strong>git clone [url]</strong></dt>
<dd>Clona um repositório hospedado em um URL para a máquina local</dd>
</dl>

## 📦 Preparação e Commit
Comandos utilizados para preparar versões do repositório e commitar posteriormente

<dl>
<dt><strong>git status</strong></dt>
<dd>Exibe estado atual de arquivos modificados no diretório</dd>
<dt><strong>git add [arquivo]</strong></dt>
<dd>Adiciona o arquivo modificado para o próximo commit, caso deseje adicionar todos, utilize um "." (ponto) no lugar do nome do arquivo</dd>
<dt><strong>git reset [arquivo]</strong></dt>
<dd>Remove arquivo adicionado enquanto mantém as alterações no diretório local</dd>
<dt><strong>git diff</strong></dt>
<dd>Exibe alterações realizadas do que foi alterado mas ainda não foi preparado para ser commitado</dd>
<dt><strong>git diff --staged</strong></dt>
<dd>Exibe alterações realizadas do que foi preparado mas ainda não foi commitado</dd>
<dt><strong>git commit -m “[mensagem]”</strong></dt>
<dd>Commita os arquivos adicionados como uma nova versão do repositório</dd>
</dl>

## 📦 Preparação e Commit
Comandos utilizados para preparar versões do repositório e commitar posteriormente

## 🔎 Inspeção e Comparação
Comandos utilizados para examinar logs, diffs e objetos.

<dt><strong>git log</strong></dt>
<dd>Lista histórico de commits da branch atual</dd>
<dt><strong>git log branchB..branchA</strong></dt>
<dd>Apresenta os commits que estão na branchA que não estão na branchB.</dd>
<dt><strong>git log --follow [file]</strong></dt>
<dd>Apresenta os commits que alteraram o arquivo, mesmo entre trocas de nome</dd>
<dt><strong>git diff branchB...branchA</strong></dt>
<dd>Apresenta as diferenças do que está na branchA e não está na branchB</dd>
</dl>

## 🚀 Compartilhando e Atualizando
Comandos utilizados para atualizar ou puxar updates de um repositório.

<dt><strong>git remote add [alias] [url]</strong></dt>
<dd>Adiciona repositório remoto</dd>
<dt><strong>git fetch [alias]</strong></dt>
<dd>Puxa todas as branches do repositório remoto</dd>
<dt><strong>git merge [alias]/[branch]</strong></dt>
<dd>Mescla uma branch remota com a branch local para atualizar.</dd>
<dt><strong>git push origin main</strong></dt>
<dd>Transmite os commits da branch local para o repositório remoto</dd>
<dt><strong>git pull</strong></dt>
<dd>Apresenta os commits que alteraram o arquivo, mesmo entre trocas de nome</dd>
<dt><strong>git diff branchB...branchA</strong></dt>
<dd>Apresenta as diferenças do que está na branchA e não está na branchB</dd>
</dl>

## 🌳 Criando Branches
Comandos utilizados para criar "branches" isolando o trabalho e posteriormente mesclando alterações.

<dt><strong>git branch</strong></dt>
<dd>Lista branches existentes, a branch atual será apresenta com um * ao lado do nome</dd>
<dt><strong>git branch [nome]</strong></dt>
<dd>Cria uma branch com o commit atual</dd>
<dt><strong>git checkout</strong></dt>
<dd>Muda para outra branch</dd>
<dt><strong>git merge [branch]</strong></dt>
<dd>Mescla as alterações de outra branch para a atual</dd>
</dl>

