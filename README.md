# Minha Dashboard

Uma dashboard personalizada e moderna para acessar rapidamente os links que fazem parte da sua rotina: trabalho, finanças, estudos, infraestrutura e projetos pessoais.

## 🚀 Características

- **Interface Moderna**: Design limpo e elegante com suporte a tema claro e escuro
- **Organização por Grupos**: Organize seus links em grupos personalizados
- **Busca Rápida**: Busque links por nome ou URL
- **Filtros por Grupo**: Filtre links por categoria
- **Drag & Drop**: Reordene grupos e links arrastando e soltando
- **Armazenamento Local**: Links adicionados são salvos no navegador (localStorage)
- **Exportar/Importar**: Exporte e importe sua configuração completa
- **Responsivo**: Funciona perfeitamente em desktop e mobile

## 📋 Funcionalidades

### Grupos de Links
- Organize seus links em grupos personalizados
- Cada grupo pode ter um título, descrição e múltiplos links
- Abra todos os links de um grupo de uma vez

### Gerenciamento de Links
- Adicione novos links a qualquer grupo
- Remova links adicionados pelo usuário
- Reordene links arrastando e soltando
- Tags para categorizar seus links

### Personalização
- Tema claro e escuro
- Reordenação de grupos via drag & drop
- Exporte sua configuração para backup
- Importe configurações anteriores

## 🛠️ Tecnologias

- HTML5
- CSS3 (com variáveis CSS e gradientes)
- JavaScript Vanilla (sem dependências)
- LocalStorage para persistência

## 📦 Instalação

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/my-dash-web.git
cd my-dash-web
```

2. Abra o arquivo `index.html` no seu navegador

Ou use um servidor local:
```bash
# Python 3
python -m http.server 8000

# Node.js (com http-server)
npx http-server
```

## 🎨 Personalização

### Adicionar Links Iniciais

Edite o arquivo `index.html` e modifique o objeto JSON dentro da tag `<script id="links-config">`:

```json
{
  "groups": [
    {
      "id": "meu-grupo",
      "label": "Meu Grupo",
      "title": "Título do Grupo",
      "description": "Descrição do grupo",
      "openWithMain": true,
      "links": [
        {
          "title": "Nome do Link",
          "url": "https://exemplo.com",
          "tags": ["Tag1", "Tag2"],
          "accent": true
        }
      ]
    }
  ]
}
```

### Estrutura de um Link

- `title`: Nome do link
- `url`: URL completa do site
- `tags`: Array de tags (opcional)
- `accent`: Boolean para destacar o link (opcional)

## 📱 Uso

1. **Buscar Links**: Digite no campo de busca para filtrar links
2. **Filtrar por Grupo**: Clique nos chips de grupo para filtrar
3. **Adicionar Link**: Clique em "Adicionar link" em qualquer grupo
4. **Remover Link**: Passe o mouse sobre um link adicionado e clique no "×"
5. **Reordenar**: Arraste grupos ou links para reorganizar
6. **Abrir Todos**: Clique em "Abrir todos" para abrir todos os links de um grupo
7. **Exportar**: Clique em "Exportar" para baixar sua configuração
8. **Importar**: Clique em "Importar" para restaurar uma configuração

## 🔧 Estrutura do Projeto

```
my-dash-web/
├── index.html          # Arquivo principal (HTML, CSS e JS)
└── README.md           # Este arquivo
```

## 📝 Notas

- Links definidos no HTML são permanentes
- Links adicionados pelo usuário são salvos no localStorage do navegador
- A configuração exportada inclui: links do usuário, ordem dos grupos, ordem dos links e tema

## 🌐 Compatibilidade

- Chrome/Edge (últimas versões)
- Firefox (últimas versões)
- Safari (últimas versões)

## 📄 Licença

Este projeto é de código aberto e está disponível sob a licença MIT.

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

---

Desenvolvido com ❤️ para facilitar o acesso aos seus links favoritos.

