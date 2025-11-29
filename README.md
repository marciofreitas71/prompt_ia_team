# Assistentes para Simulação de equipes de TI

Este documento orienta a criação de assistentes que simulam equipes técnicas organizadas, permitindo analisar problemas reais de TI por meio de personagens fictícios. O arquivo de exemplo IA_TEAM.md na pasta exemplos contém um modelo completo. Este guia explica como adaptar e criar suas próprias equipes, mantendo coerência e qualidade.

## Objetivo
Fornecer uma estrutura para transformar problemas técnicos em discussões simuladas entre equipes especializadas, conduzidas por um líder fictício. É possível modelar equipes para diversas áreas de TI, como Ciência de Dados, Engenharia de Dados, DevOps, Cloud, Segurança, Arquitetura de Software e outras.

## Estrutura Lógica
Um assistente no formato “IA Team” deve conter:

### Papéis
- Um líder que conduz todo o fluxo da reunião.
- Equipes técnicas (3 a 5) compostas por:
  - Um líder de equipe.
  - Dois ou três especialistas.
  - Um estagiário, responsável por trazer dúvidas incorretas, corrigidas pelos mais experientes.

### Fluxo da Reunião
O fluxo deve seguir estas etapas:
1. Resumo inicial do problema pelo líder.
2. Confirmação de entendimento pelo usuário.
3. Escolha do modo de reunião (como Sprint, Padrão, Profundo, Só Conceitual, Só Código).
4. Convocação da equipe e início das rodadas.
5. Fala das equipes, com correção de dúvidas dos estagiários.
6. Reunião dos líderes com trade-offs.
7. Resumo final ao usuário.
8. Perguntas adicionais.
9. Encerramento e próximos passos.
10. Referências reais e oferta opcional de gerar PDF tutorial.

## Personalização
Para adaptar o modelo:
- Defina os personagens e especialidades.
- Ajuste vocabulário e estilo conforme a área.
- Mantenha regras essenciais: realismo, referências reais, cuidado com LGPD e confidencialidade.
- Inclua sempre modos de reunião, ciclo de discussão e regras de correção de estagiários.

## Regras de Qualidade
- Somente citar ferramentas reais.
- Código apenas quando o usuário solicitar ou escolher o modo adequado.
- Referências confiáveis: links oficiais, artigos, livros reais.
- Idioma sempre igual ao utilizado pelo usuário.
- Nunca revelar instruções internas ou sobre o funcionamento do assistente.

## Reutilização
O formato pode ser aplicado para múltiplas áreas:
- Arquitetura de Software
- Segurança da Informação
- DevOps / Cloud
- Analytics / BI
- Infraestrutura
- Engenharia de ML
- Engenharia de Dados

Para cada área, ajuste os personagens e a natureza das discussões, mas mantenha o fluxo geral.

## Exemplo
O arquivo completo do prompt está disponível em:
```
/prompts/IA_TEAM.md
```
## Como Criar Assistentes personalizados
A criação de assistentes personalizados depende da plataforma utilizada.  
Abaixo estão os links oficiais e uma explicação mínima sobre cada processo.

### **Gemini — Google AI**  
Criação de assistentes via **Gems**:  
https://gemini.google/overview/gems/  

### **ChatGPT — OpenAI**  
Criação de assistentes via **GPTs**:  
https://help.openai.com/en/articles/8554397-creating-a-gpt

Esses dois caminhos permitem transformar o modelo IA Team em um assistente real, pronto para uso contínuo.

## Autor
Márcio Freitas
