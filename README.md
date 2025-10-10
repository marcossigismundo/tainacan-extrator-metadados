# Tainacan ChatGPT

Plugin WordPress para extração automatizada de metadados no Tainacan utilizando a API do ChatGPT.

## Descrição

O Tainacan ChatGPT é um plugin que integra o poder da Inteligência Artificial do ChatGPT ao Tainacan, permitindo a extração automática de metadados a partir de documentos e imagens associados aos itens do acervo.

### Recursos

- Extração automática de metadados de imagens (obras de arte, fotografias, artefatos)
- Extração automática de metadados de documentos (PDFs, textos, artigos)
- Interface intuitiva integrada ao painel de edição do Tainacan
- Configuração flexível de prompts específicos por tipo de conteúdo
- Cache de resultados para otimizar custos e desempenho
- Painel de estatísticas de uso da API OpenAI

## Instalação

1. Faça o upload da pasta `tainacan-chatgpt` para o diretório `/wp-content/plugins/`
2. Ative o plugin na tela de plugins do WordPress
3. Acesse o menu "Tainacan ChatGPT" no painel administrativo para configurar sua chave da API OpenAI

## Requisitos

- WordPress 5.6 ou superior
- PHP 7.4 ou superior
- Plugin Tainacan ativo
- Chave de API da OpenAI

## Uso

1. Configure sua chave da API OpenAI nas configurações do plugin
2. Edite um item no Tainacan que contenha uma imagem ou documento anexado
3. Clique no botão "Analisar com ChatGPT" ao lado do documento
4. Os metadados extraídos serão exibidos em uma sidebar lateral
5. Você pode copiar cada valor para os campos correspondentes no Tainacan

## Frequently Asked Questions

### Quais formatos de arquivos são suportados?

O plugin suporta análise de:
- Imagens: JPG, PNG, GIF, WebP
- Documentos: PDF, TXT, DOCX, HTML

### Como personalizar os prompts?

Acesse o menu Tainacan ChatGPT > Configurações para editar os prompts usados para analisar cada tipo de documento.

### Os documentos são enviados para a OpenAI?

Sim, para realizar a análise os documentos precisam ser enviados para a API da OpenAI. Recomendamos verificar as políticas de privacidade da OpenAI antes de usar o plugin com documentos sensíveis.

## Changelog

### 1.0.0
* Versão inicial

## Suporte

Para suporte e solicitações de recursos, entre em contato com [seu-email@exemplo.com].

## Licença

Este plugin é licenciado sob a licença GPL v2 ou posterior.
