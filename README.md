# Melodia no MeloThing

Landing page e protótipo interativo da assistente de aprendizagem musical do MeloThing.

## Abrir

Veja por aqui: https://andsoq.github.io/MeloThing/

## Conteúdo

- Identidade da Melodia e cinco funcionalidades.
- Cinco fluxos de conversa com respostas preparadas, alternativas e recuperação.
- Atividade demonstrativa de pulsação com áudio sintetizado no navegador.
- Galeria dos cinco mockups aprovados.
- Apresentação guiada em cinco telas.
- Documentação técnica e fluxos disponíveis em `docs`.

## Estado atual

O chatbot é uma simulação baseada em estados e respostas locais. Não há IA generativa conectada, banco de dados, contas, matrícula, publicação de trilhas ou transações. A integração com IA permanece uma etapa necessária para cumprir o requisito técnico da atividade adaptada.

Não há coleta, envio ou armazenamento persistente das mensagens. A atividade de pulsação não usa microfone nem avalia a execução de instrumentos.

## Arquivos

```text
index.html
styles.css
app.js
assets/
  melodia.png
  personagem-original.png
  favicon.svg
  mockups/
docs/
  projeto-melodia.md
  fluxos-conversacionais.md
  roteiro-demonstracao.md
design/
  mockups-v1/
```

## Origem visual

A personagem original foi fornecida em `melodia_apresentacao_IA.pptx`. A ilustração transparente da landing page foi gerada pela ferramenta de imagens a partir dessa ficha. Os cinco mockups foram aprovados como direção visual. Os prompts estão preservados em `design`.

A aplicação usa fontes do sistema e não depende de bibliotecas, CDNs ou imagens remotas.
