# 📘 README.md — Pesquisa

## ✅ O que é o `README.md`?

O `README.md` é um arquivo de texto escrito em **Markdown**, um formato simples de linguagem de marcação que permite adicionar títulos, listas, links, imagens, entre outros elementos de formatação.

## ✅ Para que ele serve?

Esse arquivo é usado para **apresentar um projeto**, explicando do que se trata, como instalar, usar e contribuir. Ele é o **primeiro contato** que as pessoas terão com o repositório no GitHub.

## ✅ Em quais contextos ele é mais usado?

   
O `README.md` é amplamente utilizado em:

- Projetos de **programação** (repositórios no GitHub)
- Documentação de **softwares** e **bibliotecas**
- Trabalhos colaborativos e open-source
- Apresentações de **projetos escolares** ou **profissionais**
- Tutoriais ou instruções técnicas
Comandos CMD úteis para técnicos de hardware



Comandos CMD úteis para técnicos de hardware
   
### 1. `systeminfo`

- **O que ele faz:**  
  Exibe informações detalhadas sobre o sistema operacional, hardware e configurações do computador, como nome do PC, fabricante, versão do Windows, memória RAM, etc.

- **Quando pode ser útil:**  
  Ao fazer um diagnóstico inicial de um computador, verificando informações de hardware e sistema.

- **Exemplo de uso:**  
systeminfo

yaml
Copiar código

---

### 2. `wmic cpu get name`

- **O que ele faz:**  
Mostra o nome e modelo do processador instalado no computador.

- **Quando pode ser útil:**  
Ao verificar a compatibilidade de software ou desempenho com base no tipo de CPU.

- **Exemplo de uso:**  
wmic cpu get name

yaml
Copiar código

---

### 3. `chkdsk`

- **O que ele faz:**  
Verifica e corrige erros no disco rígido (HD ou SSD).

- **Quando pode ser útil:**  
Quando o computador está lento, travando ou apresentando mensagens de erro relacionadas ao disco.

- **Exemplo de uso:**  
chkdsk C: /f

yaml
Copiar código
(O `/f` tenta corrigir os erros encontrados)

---

### 4. `sfc /scannow`

- **O que ele faz:**  
Verifica e repara arquivos de sistema corrompidos ou alterados do Windows.

- **Quando pode ser útil:**  
Se o sistema estiver com comportamentos estranhos ou apresentando falhas.

- **Exemplo de uso:**  
sfc /scannow

yaml
Copiar código

---

### 5. **wmic diskdrive get status**

- **O que ele faz:**  
Mostra o status dos discos conectados (HDs e SSDs), indicando se há falhas físicas detectadas.

- **Quando pode ser útil:**  
Para avaliar se o disco está saudável ou começando a falhar.

- **Exemplo de uso:**  
wmic diskdrive get status

yaml
Copiar código

## 🛠️ Parte 3: Criação do Repositório no GitHub

Para organizar os arquivos da atividade, foi criado um repositório no GitHub com os seguintes passos:

1. Acessar o site [https://github.com](https://github.com)
2. Fazer login na conta criada
3. Clicar em **"New repository"** no canto superior direito
4. Definir um nome para o repositório (ex: `atividade-readme-cmd`)
5. Marcar a opção **"Add a README file"**
6. Clicar no botão **"Create repository"**

Após isso, o repositório foi criado com sucesso e o arquivo `README.md` foi editado com as informações da atividade.


## 💻 Comandos CMD voltados para hardware

1. **Comando:** `systeminfo`  
   **Função:** Mostra informações detalhadas sobre o sistema operacional e o hardware.  
   **Uso:** Diagnóstico geral do computador.

2. **Comando:** `wmic cpu get name`  
   **Função:** Exibe o nome e modelo do processador.  
   **Uso:** Verificar o tipo de CPU para diagnóstico ou compatibilidade.

3. **Comando:** `chkdsk`  
   **Função:** Verifica e corrige erros no disco rígido.  
   **Uso:** Detectar e reparar problemas no HD ou SSD.

4. **Comando:** `sfc /scannow`  
   **Função:** Verifica e repara arquivos protegidos do sistema Windows.  
   **Uso:** Corrigir arquivos corrompidos que podem causar instabilidade.

5. **Comando:** `wmic diskdrive get status`  
   **Função:** Mostra o status dos discos conectados, indicando se estão saudáveis.  
   **Uso:** Avaliar a integridade do disco rígido.

## 👤 Autor  
Luis Gustavo Giacometo de Souza

## 📅 Data  
19/09/2025

## 📧 Contato  
denisegiacometo51@gmail.com

## 🧠 O que aprendi?  
Nesta atividade, aprendi a importância do arquivo README.md para organizar e apresentar informações sobre projetos no GitHub.  
Também entendi como alguns comandos do CMD  são úteis para técnicos de hardware, essas ferramentas são fundamentais para manter o funcionamento correto do hardware e do sistema operacional.

