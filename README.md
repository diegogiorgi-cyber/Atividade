# WIKI-LINUX-Guia-FACULDADE
# Aluno: 
Artur Trindade Saraiva Da Silva RGM:11261105700

  # 📘 Wiki de Comandos Linux

Contem 30 comandos Linux importantes e relacionados a Bioinformática e Engenharia Biomédica.

## 1 COMANDO - ls
**Para que serve:**  Lista os arquivos e diretórios presentes no diretório atual. Pode ser usado com opções para mostrar detalhes, arquivos ocultos, etc.

**Exemplo:**
```bash
ls
ls -l
```
Usado quando você quer ver o que tem dentro de uma pasta.

---

## 2 COMANDO - cd
**Para que serve:**  Muda o diretório atual para outro especificado pelo usuário. Exemplo: cd /home/usuario.


**Exemplo:**
```bash
cd Documentos
cd ..
```
Serve para navegar entre as pastas do sistema.

---

## 3 COMANDO - pwd
**Para que serve:**  Exibe o caminho completo do diretório atual em que você está trabalhando


**Exemplo:**
```bash
pwd
```
Útil para saber exatamente onde você está.

---

## 4 COMANDO - mkdir
**Para que serve:** Cria um novo diretório (pasta) com o nome especificado.

**Exemplo:**
```bash
mkdir projetos
```
Usado para organizar arquivos criando diretórios.

---

## 5 COMANDO - rmdir
**Para que serve:** Remove um diretório vazio. Não funciona se o diretório contiver arquivos ou outras pastas

**Exemplo:**
```bash
rmdir pasta_vazia
```
Só funciona se a pasta não tiver arquivos dentro.

---

## 6 COMANDO - rm
**Para que serve:**   Remove arquivos ou diretórios (com a opção -r para recursivo), porem , tem que ter cuidado pois e um comando destrutivo

**Exemplo:**
```bash
rm arquivo.txt
rm -r pasta
```
Muito usado para apagar coisas do sistema.

---

## 7 COMANDO - cp
**Para que serve:** Copia arquivos ou diretórios de um local para outro.

**Exemplo:**
```bash
cp arquivo.txt copia.txt
```
Serve para duplicar arquivos.

---

## 8 COMANDO - mv
**Para que serve:** Move ou renomeia arquivos e pastas.

**Exemplo:**
```bash
mv arquivo.txt pasta/
mv velho.txt novo.txt
```
Usado para organizar ou renomear arquivos.

---

## 9 COMANDO - touch
**Para que serve:** Cria um arquivo vazio ou atualiza a data de modificação de um arquivo existente.

**Exemplo:**
```bash
touch arquivo.txt
```
Muito usado para iniciar arquivos rapidamente.

---

## 10 COMANDO - cat
**Para que serve:**  Exibe o conteúdo de um arquivo no terminal.

**Exemplo:**
```bash
cat arquivo.txt
```
Bom para visualizar arquivos pequenos.

---

## 11 COMANDO - less
**Para que serve:** Permite visualizar o conteúdo de um arquivo de forma paginada, facilitando a leitura de arquivos grande

**Exemplo:**
```bash
less arquivo.txt
```
Facilita a leitura de arquivos longos.

---

## 12 COMANDO - head
**Para que serve:**  Mostra as primeiras linhas de um arquivo (por padrão, as 10 primeiras)

**Exemplo:**
```bash
head arquivo.txt
```
Útil para ver o começo de arquivos grandes.

---

## 13 COMANDO - tail
**Para que serve:** Mostra as últimas linhas de um arquivo (por padrão, as 10 últimas).

**Exemplo:**
```bash
tail arquivo.txt
tail -f log.txt
```
Muito usado para acompanhar logs.

---

## 14 COMANDO - clear
**Para que serve:**  Limpa a tela do terminal, removendo todo o texto exibido anteriormente.

**Exemplo:**
```bash
clear
```
Deixa o terminal mais organizado.

---

## 15 COMANDO - echo
**Para que serve:** Imprime texto ou variáveis no terminal. Muito usado para exibir mensagens ou resultados.

**Exemplo:**
```bash
echo "Olá mundo"
echo "texto" > arquivo.txt
```
Usado para exibir ou salvar mensagens.

---

## 16 COMANDO - whoami
**Para que serve:** Exibe o nome do usuário atualmente logado no sistema.

**Exemplo:**
```bash
whoami
```
Indica quem está logado no sistema.

---

## 17 COMANDO - uname
**Para que serve:** Mostra informações sobre o sistema operacional, como nome do kernel, versão, arquitetura, etc.

**Exemplo:**
```bash
uname -a
```
Exibe detalhes do sistema operacional.

---

## 18 COMANDO - history
**Para que serve:** Exibe o histórico dos comandos digitados no terminal.

**Exemplo:**
```bash
history
```
Ajuda a lembrar comandos anteriores.

---

## 19 COMANDO - man
**Para que serve:**  Abre o manual de um comando, mostrando sua descrição, opções e uso.

**Exemplo:**
```bash
man ls
```
Usado para aprender mais sobre comandos.

---

## 20 COMANDO - chmod
**Para que serve:** Altera as permissões de arquivos e diretórios (leitura, escrita, execução).

**Exemplo:**
```bash
chmod 755 script.sh
```
Controla quem pode ler, escrever ou executar.

---

## 21 COMANDO - chown
**Para que serve:** Altera o proprietário (dono) de um arquivo ou diretório.

**Exemplo:**
```bash
chown usuario arquivo.txt
```
Usado principalmente por administradores.

---

## 22 COMANDO - df
**Para que serve:** Mostra o uso do espaço em disco das partições montadas.

**Exemplo:**
```bash
df -h
```
Indica espaço livre e ocupado.

---

## 23 COMANDO - du
**Para que serve:**  Exibe o tamanho de arquivos e diretórios, útil para verificar o espaço ocupado.

**Exemplo:**
```bash
du -h pasta/
```
Ajuda a ver o que está ocupando espaço.

---

## 24 COMANDO - top
**Para que serve:**  Exibe em tempo real os processos em execução, uso de CPU, memória e outras informações do sistema.

**Exemplo:**
```bash
top
```
Exibe uso de CPU e memória.

---

## 25 COMANDO - ps
**Para que serve:** Lista os processos em execução no momento, com detalhes como PID, usuário e estado.

**Exemplo:**
```bash
ps aux
```
Mostra detalhes dos processos ativos.

---

## 26 COMANDO - kill
**Para que serve:** Encerra um processo especificado pelo seu PID (identificador do processo)

**Exemplo:**
```bash
kill 1234
```
Finaliza processos usando o PID.

---

## 27 COMANDO - ping
**Para que serve:** Testa a conectividade com outro host na rede, enviando pacotes ICMP e mostrando o tempo de resposta

**Exemplo:**
```bash
ping google.com
```
Verifica se há conexão de rede.

---

## 28 COMANDO - ifconfig
**Para que serve:** Exibe informações sobre as interfaces de rede configuradas no sistema.

**Exemplo:**
```bash
ifconfig
```
Exibe IP e configurações de rede.

---

## 29 COMANDO - wget
**Para que serve:** Baixa arquivos da internet via linha de comando.

**Exemplo:**
```bash
wget https://site.com/arquivo.zip
```
Usado para downloads diretos.

---

## 30 COMANDO - curl
**Para que serve:**   Realiza requisições web, podendo baixar conteúdo, enviar dados, testar APIs, entre outros.

**Exemplo:**
```bash
curl https://api.site.com
