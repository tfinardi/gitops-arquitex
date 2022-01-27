# Gitops-Arquitex #24

Repositório utilizado na apresentação da 24ª edição do Arquitex na Ambev Tech.

## Arquivos

Para fins didáticos e simplificação, os arquivos estão distribuídos no repositório da seguinte maneira:

| Path        | Conteúdo |
|-------------|----------|
| /app        | Manifesto com a configuração da aplicação contendo as informações implantação. |
| /manifests  | Manifestos de todos os microserviços da aplicação (Na vida real, cada microsserviço teria seus respectivos manifestos em seu repositório) |
| /helm-chart | Helm Chart contendo os templates necessários para fazer o deploy da aplicação usando o Helm |
