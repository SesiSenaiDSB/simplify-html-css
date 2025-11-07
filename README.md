# 🚀 Simplify

> A porta de entrada para o desenvolvimento web

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge)

## 📋 Sobre o Projeto

**Simplify** é um site institucional fictício desenvolvido como projeto educacional no Senai/Sesi. O site apresenta uma empresa de desenvolvimento web Front-End, com páginas informativas sobre produtos, serviços e um formulário de contato totalmente funcional.

## ✨ Características

- 🎨 **Design Responsivo**: Layout adaptável para mobile, tablet e desktop
- 🎭 **Efeitos Parallax**: Imagens de fundo com rolagem diferenciada
- 📱 **Mobile First**: Desenvolvido pensando primeiro em dispositivos móveis
- 🎯 **SEO Otimizado**: Meta tags e estrutura semântica
- ✉️ **Formulário Funcional**: Integração com Formspree para receber mensagens

## 📁 Estrutura do Projeto

```
simplify/
│
├── index.html              # Página inicial
├── produtos.html           # Página de produtos
├── servicos.html          # Página de serviços
├── contato.html           # Página de contato
│
├── css/
│   ├── style.css          # Estilos globais
│   ├── index.css          # Estilos da home
│   ├── produtos.css       # Estilos da página de produtos
│   ├── servicos.css       # Estilos da página de serviços
│   └── contato.css        # Estilos do formulário
│
└── imagens/
    ├── favicon.png
    ├── linguagens.png
    └── [outras imagens]
```

## 📬 Integração com Formspree

### O que é o Formspree?

O **Formspree** é um serviço gratuito que permite que formulários HTML funcionem sem a necessidade de um backend próprio. Perfeito para sites estáticos! 🎉

### Como Configurar

1. **Crie uma conta gratuita** em [formspree.io](https://formspree.io/)

2. **Crie um novo formulário** no painel do Formspree

3. **Copie o endpoint** fornecido (será algo como `https://formspree.io/f/xXXXXXXX`)

4. **Substitua no arquivo `contato.html`**:
   ```html
   <form action="https://formspree.io/f/SEU_CODIGO_AQUI" method="post">
   ```

5. **Pronto!** Seu formulário já está funcional ✅


## 📝 Licença

Este é um projeto educacional desenvolvido no **Senai/Sesi** © 2025

---

<div align="center">

**Desenvolvido com ❤️ para fins educacionais**

[⬆ Voltar ao topo](#-simplify)

</div>