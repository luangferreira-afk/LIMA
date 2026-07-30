# LIMA
S1_AT2_R1_LIMA
# Exercícios Práticos de XML – Identificação e Correção de Erros
# Objetivo
### O objetivo destes exercícios é desenvolver a habilidade de identificar e corrigir
### erros de sintaxe em documentos XML.

# EXERCICIO 01 Cadastro de Livro

<?xml version="1.0" encoding="UTF-8"?>

<livro>
<titulo>Banco de Dados       ⬅️ O Erro está aqui, está faltando o seguinte código " </titulo>" Este código fecha o "<titulo>Banco de Dados" para que ele funcione                                     devidamente.
<autor>Maria Oliveira</autor>
<ano>2025</ano>
</livro> 
<?xml version="1.0" encoding="UTF-8"?>

<livro>
<titulo>Banco de Dados </titulo>
<autor>Maria Oliveira</autor>
<ano>2025</ano>
</livro>
