# Criando-Seu-Curr-culo-Online-Com-HTML-e-GitHub-Pages

# Vamos agora, no passo a passo, para criar um Currículo Online Com HTML e GitHub Pages

**Módulo 1: Introdução ao Desenvolvimento Front-end**
Antes de mergulhar na criação do currículo, é essencial entender os fundamentos do desenvolvimento front-end. HTML (HyperText Markup Language) e CSS (Cascading Style Sheets) são as pedras angulares que permitem criar e estilizar páginas web.

**Exemplo Prático:**
```html
<!DOCTYPE html>
<html>
<head>
    <title>Meu Currículo Online</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <h1>João da Silva</h1>
        <p>Desenvolvedor Front-end</p>
    </header>
    <!-- Mais conteúdo aqui -->
</body>
</html>
```

**Módulo 2: Estruturando o Currículo com HTML**
A estrutura do currículo deve ser clara e organizada. Utilize tags semânticas do HTML para definir as seções do currículo, como `<header>`, `<section>`, `<article>`, e `<footer>`.

**Exemplo Prático:**
```html
<section>
    <h2>Experiência Profissional</h2>
    <article>
        <h3>Empresa X</h3>
        <p>Desenvolvedor Web - Janeiro 2020 a Dezembro 2021</p>
        <!-- Descrição das atividades -->
    </article>
    <!-- Mais experiências aqui -->
</section>
```

**Módulo 3: Estilizando com CSS**
O CSS é utilizado para adicionar estilo ao seu currículo. Cores, fontes e layout são definidos aqui para tornar o documento visualmente atraente.

**Exemplo Prático:**
```css
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
}

section article h3 {
    color: #333;
}
```

**Módulo 4: Publicando com GitHub Pages**
O GitHub Pages é uma plataforma gratuita que permite publicar sites diretamente de um repositório no GitHub. Basta ativar a funcionalidade no repositório onde seu currículo está armazenado.

**Exemplo Prático:**
1. Crie um repositório no GitHub.
2. Suba os arquivos do seu currículo para o repositório.
3. Acesse as configurações do repositório.
4. Na seção "GitHub Pages", selecione a branch e o diretório onde seu site está localizado.
5. Clique em "Save" e seu site estará no ar!

**Módulo 5: CI/CD com GitHub Actions**
CI/CD são práticas de integração contínua e entrega contínua. No GitHub, as Actions permitem automatizar workflows, incluindo a publicação de sites com o GitHub Pages.

**Exemplo Prático:**
- Crie um arquivo `.github/workflows/main.yml`.
- Configure o workflow para instalar dependências, construir o projeto e publicar no GitHub Pages.

**Módulo 6: Dicas para o Perfil Pessoal na DIO**
A plataforma DIO oferece oportunidades para destacar seu perfil profissional. Preencha todas as informações relevantes, participe de bootcamps e atualize seu portfólio com projetos concluídos.

**Exemplo Prático:**
- Complete seu perfil com experiências e formações.
- Engaje-se com a comunidade.
- Compartilhe seus projetos e conquistas.

Espero que esses módulos ajudem a quem precisar criar um currículo online impressionante e a aproveitar ao máximo as ferramentas disponíveis para desenvolvedores front-end!
