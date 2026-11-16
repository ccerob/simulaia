# SimulaIA — Protótipo acadêmico v2.0

## Contexto

A SimulaIA foi elaborada como protótipo demonstrativo associado ao Trabalho de Conclusão da Pós-Graduação Lato Sensu em Práticas Pedagógicas do Instituto Federal do Espírito Santo (Ifes), de **Carlos Eduardo Rodrigues Pinheiro**, sob orientação do **Prof. Me. José Mario Costa Junior**.

Título do trabalho: *Proposta de prática pedagógica com simulação empresarial e inteligência artificial para o ensino de Gestão Estratégica na graduação em Administração* (Vitória, 2026).

O software apresenta as escolhas didáticas descritas no trabalho, mas não é um produto oficial do Ifes, não foi testado em uma turma e não comprova eficácia pedagógica.

## Como iniciar

1. Abra `index.html` em um navegador atual (Chrome, Edge, Firefox etc.). Não é necessário instalar bibliotecas, criar conta, hospedar em servidor ou fornecer internet para executar a simulação.
2. A primeira página, **Sobre a pesquisa**, apresenta a origem acadêmica, a autoria e as limitações do projeto.
3. Em **Como usar**, há instruções navegáveis para cada uma das páginas. Os cartões abrem as etapas correspondentes.
4. Na seção **Empresa**, os campos com contorno amarelo-claro e etiqueta `EDITAR` podem ser alterados. Clique em **Salvar parâmetros**. Se você alterar o cenário que possui rodadas registradas, será solicitada confirmação para reiniciar o histórico.
5. Em **Decisões**, altere preço, quantidade ofertada e marketing; observe a DRE e clique em **Executar rodada**.
6. Em **Gestão de crise**, selecione um evento após a primeira rodada normal, clique em **Ativar e decidir** e execute a próxima rodada em **Decisões**.
7. Em **Resultados**, compare as rodadas e exporte dados, se desejar.
8. O **Guia docente** traz os detalhes técnicos, as fórmulas e as funções de importação e exportação.

O protótipo apresenta, inicialmente, duas rodadas ilustrativas. Para criar uma simulação própria, configure e salve os dados de **Empresa** ou utilize **Guia docente → Iniciar projeto limpo**.

## Autonomia do arquivo

O arquivo `index.html` é autocontido, incluindo estilos, código, configurações e fotografia embutida. O aplicativo calcula resultados localmente. Não há comunicação automática com provedores de IA; os prompts disponíveis podem ser copiados para uma ferramenta externa, por decisão do docente.

A gravação automática no navegador (`localStorage`) pode variar conforme as políticas de segurança do dispositivo, especialmente quando o arquivo é aberto diretamente. Use a exportação JSON para preservar seu projeto independentemente do armazenamento do navegador. Ao importar um JSON válido do próprio aplicativo, os cálculos são reprocessados.

## Premissas e limites

Modelo de demanda, elasticidade hipotética, marketing e custos para fins didáticos. Sem tributos, juros, estoques, depreciação, capital de giro, integração empresarial ou disputa simultânea de múltiplas equipes. Sem validação empírica. Os nomes, empresas e valores dos cenários são fictícios.

A fotografia incorporada foi fornecida na conversa para representar o autor. Antes de publicar publicamente o site, confirme que existe autorização para divulgar a imagem e os dados de identificação.

## Publicação opcional

O pacote foi preparado para hospedar o arquivo `index.html` em um serviço de páginas estáticas. A publicação não é necessária para executar a simulação localmente.
