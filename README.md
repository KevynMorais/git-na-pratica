# Projeto 1 — Curso gratuito de Git e GitHub

Projeto de estudo criado para praticar os fundamentos de **Git** e **GitHub**: versionamento, commits, branches e pull requests. O conteúdo é uma página web simples, usada como base para exercitar o fluxo de trabalho com controle de versão.

## 📁 Estrutura do projeto

```
projeto-1/
├── .gitignore          # Arquivos e pastas ignorados pelo Git
├── index.html          # Página principal
├── estilo.css          # Estilos principais
├── estilo-fulano.css   # Estilos alternativos (usado em exercícios de branch/merge)
├── mercado-pago.js     # Script de integração com o Mercado Pago
└── whatsapp.js         # Script de integração com o WhatsApp
```

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript
- Git e GitHub

## 🚀 Como executar

Não é necessário instalar nada. Basta clonar o repositório e abrir o arquivo no navegador:

```bash
# Clone o repositório
git clone https://github.com/KevynMorais/projeto-1.git

# Acesse a pasta do projeto
cd projeto-1

# Abra o index.html no navegador (ou use a extensão Live Server do VS Code)
```

## 🌿 Fluxo de trabalho com Git

Comandos usados ao longo do projeto:

```bash
git status                      # Ver o estado dos arquivos
git add .                       # Adicionar alterações à área de stage
git commit -m "Sua mensagem"    # Registrar as alterações
git push origin master          # Enviar para o GitHub
git pull origin master          # Baixar as últimas alterações

git checkout -b minha-branch    # Criar e mudar para uma nova branch
git merge minha-branch          # Mesclar uma branch na atual
```

## 🤝 Como contribuir

1. Faça um **fork** do projeto
2. Crie uma branch para a sua alteração (`git checkout -b minha-feature`)
3. Faça o commit (`git commit -m "Adiciona minha feature"`)
4. Envie para o seu fork (`git push origin minha-feature`)
5. Abra um **Pull Request**

## 👤 Autor

**Kevyn Morais**

- GitHub: [@KevynMorais](https://github.com/KevynMorais)

## 📄 Licença

Este projeto ainda não possui uma licença definida. Caso queira disponibilizá-lo publicamente para reuso, considere adicionar uma, como a [MIT](https://choosealicense.com/licenses/mit/).
