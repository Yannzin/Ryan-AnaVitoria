<div align="center">

<img src="https://www.opovo.com.br/_midias/png/2025/02/07/logo_cor_2-32749727.png" alt="Faculdade Multiversa" width="300"/>

# Computação na Nuvem

**Professor:** Rodrigo Viana  
**Semestre:** 2026.1

</div>

---

## Identificação

**Exercício: Simulando Escalabilidade com Docker** <!-- ex: Exercício 2 - Simulando Escalabilidade com Docker -->

**Integrantes da equipe:**

| Nome completo | Matrícula |
|---|---|
|Ana Vitória Lima da Silva |25000013 |
|Ryan Xavier Feitosa | 25000024 |
|| ||

---

## Desenvolvimento

<!-- Descreva aqui o que foi feito, passo a passo. Use sub-seções se necessário. -->
1 - Primeiramente tentamos resolver o problema de acesso na conta da amazon. Alguns dias atrás, um email de validação de identidade nos passou despercepido e por isso a conta foi suspensa, sem sucesso recorremos ao LocalStack.

2 - Em seguida, Baixamos o AWS CLI para Windows e por ultimo LocalStack.

3 - Por ultimo, fizemos as configurações necessárias no ambiente e criamos os arquivos/pastas e acrescentamos os arquivos.



---

## Evidências

<!-- Insira os prints/capturas de tela solicitados. -->
<!-- Para imagens hospedadas (ex: GitHub Issues, Imgur): -->
<!-- ![descrição](https://link da imagem...) -->


## Arquivos Utilizados

<a href="Como elogiar o rodrigo/PrimeiroPasso.pdf">Primeiro Passo</a>

<a href="Como elogiar o rodrigo/SegundoPasso.pdf">Segundo Passo</a>

<a href="Como passar na prova do rodrigo/ultimopassogoatdasarea.pdf">Como passar na prova do rodrigo</a>


### Passo 1 — Abrindo um novo LocalStack3:

<img src="imagens/Abrindo um novo LocalStack3.png">

### Passo 2 — Configurando Credenciais Temporárias:

<img src="imagens/Configurando Credenciais Temporárias.png">

### Passo 3 — Criação do Bucket:

<img src="imagens/Criação do Bucket.png">

### Passo 4 — Criar os arquivos teste:

<img src="imagens/Criar os arquivos teste.png">

### Passo 5 — Gerar o Presigned URL:

<img src="imagens/Gerar o Presigned URL3.png">

```bash
http://localhost:4566/ryan-cloud-aula04/ComoPassarNaProvadoRodrigo/GuiaDefinitivo.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=TEST%2F20260601%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20260601T174001Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=ec4085ef70b16abe80b5a26a7aa0bd5ece0af2aae2091610cea9d2cb2b132ab1
```

### Passo 6 — Listagem dos arquivos2:

<img src="imagens/Listagem dos arquivos2.png">

---

## Respostas

<!-- Responda as perguntas do exercício abaixo. -->



**1. Qual a diferença entre S3 e EBS? ?**  

O S3 é usado para armazenar arquivos, como fotos, vídeos e documentos. Já o EBS funciona como um HD virtual que fica conectado a uma máquina na AWS.

**2. Por que o nome do bucket é único globalmente?**  

Porque não podem existir dois buckets com o mesmo nome na AWS. Isso ajuda a identificar cada bucket de forma única.

**3. O link temporário expira? Por quê?**  

Sim. O link expira depois do tempo definido quando ele é criado. Isso é importante para evitar que outras pessoas tenham acesso ao arquivo para sempre.

---

## Conclusão

Com essa atividade, foi possível aprender como criar e gerenciar um bucket no S3, fazer o upload de arquivos, organizar as pastas e gerar links temporários para compartilhamento. Além disso, o uso do LocalStack permitiu praticar esses conceitos sem precisar utilizar diretamente a AWS. Já que por algum motico, não conseguimos ter acesso á conta criada na aws por causa da falha que aconteceu em nossa conta.
Por não conseguirem validar a identidade da nossa conta, ela foi suspensa e abrimos um caso no suporte para fazer a exclusão da conta e evitar cobranças futuras. 



<!-- Com as palavras de vocês, o que voc~es concluíram nesse exercício? -->
