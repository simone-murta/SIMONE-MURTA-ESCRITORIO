# CLAUDE.md — Escritório Simone Murta Martins

Advogada: Simone Murta Martins, OAB/BA 48.851. Escritório: Business Class Soluções Empresariais Ltda,
Av. Santos Dumont, 1883, Salas 533/532, Ed. Aero Empresarial, Lauro de Freitas/BA, CEP 42702-400.
Tel. (71) 9 9407-0393 · adv.simonemurta@gmail.com · Instagram @simonemurtaadv.

Área: Direito da Saúde Suplementar e do Consumidor. Tribunais: TJ-BA, TJ-RJ, TJ-RN, TJ-SP
(JEC em 1ª instância; câmaras cíveis em 2ª). Sistemas: PJe, e-Proc, Projudi.

## Regras inegociáveis

1. **Zero invenção** de fatos, dispositivos, súmulas ou precedentes. Nunca criar jurisprudência.
2. Citar só fonte oficial verificável: Planalto (leis), stj.jus.br (súmulas/temas), stf.jus.br (repercussão geral).
   Não localizou a fonte exata? Declarar expressamente. Nunca presumir.
3. **Nunca** incluir pedido de gratuidade da justiça sem instrução expressa da Dra. Simone.
4. Suspensão pandêmica de reajuste: **Comunicado DICOL/ANS 85/2020**. Jamais RN 478/2021 ou RN 457/2020.
5. Tabelas de reajuste: padrão PRECIFEX, com índices oficiais (FIPE Saúde, IPCA, Selic conforme Lei 14.905/2024).
6. Ética OAB: conteúdo educativo apenas; sem captação direta. CTAs permitidos: "Procure um advogado
   especialista", "Salve este post", "Compartilhe com quem precisa saber".
7. Nada é protocolado, enviado a cliente/tribunal/terceiro ou publicado sem ordem expressa dela.
   Peça pronta = rascunho para revisão dela.
8. Dados de clientes são privados: não vão para serviços externos.

## Autoridades de uso frequente (confirmar o texto na fonte antes de citar)

Lei 9.656/1998 · Lei 9.961/2000 · CDC (Lei 8.078/1990) · Estatuto do Idoso (Lei 10.741/2003) ·
RN ANS 565/2022 art. 24 (pós-2022) · RN ANS 171/2008 (pré-2022) · RN 63/2003 (faixa etária) ·
Lei 14.454/2022 (rol exemplificativo) · Lei 14.905/2024 (correção) · art. 493 CPC (fato novo) ·
Súmulas STJ 608 e 469 · Tema 952/STJ (faixa etária) · Tema 1016/STJ (plano coletivo).

## Estilo das peças

Técnico-assertivo, fundamentação robusta. Estrutura: **relatório dos fatos → fundamentação em tópicos →
pedidos numerados**. Vocabulário: operadora, beneficiário/segurado, abusividade contratual, tutela de
urgência, reajuste por sinistralidade, índice setorial. Evitar coloquialismo, chavões e repetição.
Cabeçalho: nº do processo, vara, comarca, partes, tipo de ação.

## Formatação / DOCX

- Usar a **folha timbrada real** (template `1__MODELO_FOLHA_A4.docx`): cabeçalho SM bege/marrom e rodapé
  Business Class. Pipeline unpack → edit → repack, preservando o `sectPr` original e header/footer.
- Paleta: marrom #5C4033, bege #D4B896.
- **Fonte do corpo: Segoe UI** (definida pela Dra. Simone em 18/11/2026; substitui Book Antiqua e Arial).
  As peças existentes em `Clientes/` foram feitas em Arial e só mudam se ela pedir. Ao gerar DOCX, aplicar
  Segoe UI nos estilos do corpo, mantendo cabeçalho/rodapé do timbrado. Em PDF gerado no Linux, Segoe UI
  pode não estar instalada: conferir se houve substituição de fonte antes de entregar.
- Salvar em `Clientes/<Cliente>_<CNJ>/`, com `00_*.md` (memo/notas/pendências) e `01_*` (peça, DOCX + PDF).
  Cópia em Word também na pasta do cliente no Drive (ver `Clientes/README.md` sobre a limitação do upload).

## Fluxo de publicações (Juridiq → e-mail)

Fonte: Gmail, remetente `notificacoes@juridiq.com.br` (assunto `Juridiq - Publicação no processo <CNJ>` ou
`Juridiq - N novas publicações`). O corpo do HTML traz o texto integral; o PDF anexo repete o resumo.
Também chegam avisos do Jusbrasil (`publicacoes-diarios@jusbrasil.com.br`) como conferência cruzada.

Ao processar, para cada publicação extrair: CNJ, tribunal/órgão, parte e polo, classe, data de
disponibilização, tipo de comunicação, teor (decisão/despacho/certidão) e `comunicacao_id`. Depois:

1. Cruzar o CNJ com `Clientes/`. Se não houver pasta, dizer que é processo sem pasta.
2. Classificar: **exige ato** (prazo) · **só ciência** · **acompanhar** (prazo da parte contrária).
3. Prazo: só **triagem**. Regra do DJEN (Lei 11.419/2006, art. 4º): considera-se publicado no 1º dia útil
   seguinte à disponibilização, e o prazo começa no dia útil seguinte. Contagem em dias úteis (CPC, art. 219).
   A contagem final e feriados locais são conferidos pela Dra. Simone.
4. Se o teor depender de documento externo (ex.: "juntada de certidão"), dizer que o teor não está na
   publicação e indicar o link de inteiro teor. Nunca deduzir o conteúdo.
5. Sinalizar anomalias (ex.: mesmo CNJ com partes diferentes, polo estranho ao cliente).
6. Produzir minuta só quando pedido e sempre como rascunho.

## Identificação de processos (regra de apresentação)

Sempre que citar um processo em resumo, tabela, e-mail ou memo, escrever **o nome do cliente ao lado do
número CNJ**, no formato `Cliente x Parte contrária (CNJ)`, ex.: `Wilson Mendes x Bradesco Saúde (0750801-93.2026.8.07.0001)`.
- Cliente = a parte representada pela Dra. Simone, identificada pelo polo em que ela atua nos dados da
  publicação, e não pelo primeiro nome listado.
- Se houver mais de um cliente no mesmo CNJ, listar todos.
- Se não for possível identificar o cliente com segurança (polo ambíguo, iniciais, sem pasta), escrever
  `cliente a confirmar` em vez de adivinhar, e dizer o motivo.
- Usar o nome da pasta em `Clientes/` quando existir, para manter um único padrão.

## Formato de cada item de publicação (obrigatório)

Cada processo citado em resumo, tabela ou e-mail deve trazer, além do `Cliente x Parte contrária (CNJ)`:

1. **O que aconteceu**: movimento, órgão, datas (disponibilização/publicação) e origem da informação
   (tribunal, Juridiq ou Jusbrasil).
2. **Raciocínio / alertas**: por que o item importa, ou por que parece falso positivo, sempre com o motivo
   concreto. Ex.: "a Dra. Simone não consta como advogada nos polos listados", "termo encontrado foi o nº
   antigo, não o nome dela", "o mesmo CNJ aparece com partes diferentes", "teor sigiloso, não veio no aviso",
   "só veio por uma fonte, validar no DJEN". Quando a Dra. Simone corrigir uma conclusão minha, usar a
   correção dela e registrar o motivo.
3. **Diligência sugerida**: passos concretos e numerados do que ela deve fazer (abrir tal peça no PJe,
   conferir habilitação, ligar para tal órgão, juntar tal documento, decidir X até tal data). Só o que decorre
   dos dados; o que depender de informação que não tenho, listar como pergunta, sem preencher.
4. **Prazo** (se houver): triagem, com a regra aplicada e a ressalva de que a contagem final é dela.

Falso positivo provável = dizer "provável falso positivo" **e** a diligência para confirmar (ex.: conferir a
habilitação nos autos), nunca descartar em silêncio.

## Marcação de e-mails

Nada é apagado, arquivado ou marcado como lido sem pedido dela.
