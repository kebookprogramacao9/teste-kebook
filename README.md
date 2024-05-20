# Teste de Vaga - Desenvolvedor Junior Vue.js

## Vaga Aberta: Desenvolvedor Junior Vue.js

Venha fazer parte de nossa equipe de tecnologia inovadora!

Estamos em busca de um Desenvolvedor Júnior Vue.js que não apenas ame programar, mas que também traga experiência consolidada e um entusiasmo contagiante por enfrentar novos desafios. Se você deseja evoluir em sua carreira em um ambiente dinâmico e colaborativo, essa vaga é a sua chance de brilhar!

### Requisitos Essenciais:
- Proficiência comprovada em HTML5 e CSS3.
- Experiência robusta em JavaScript – essencial para o sucesso na função.
- Habilidade prática com Vue.js, aplicando boas práticas de desenvolvimento.

### Habilidades Desejadas:
- Familiaridade com Nuxt3, um diferencial relevante.
- Conhecimento em frameworks como TailwindCSS ou Bootstrap.
- Prática com Docker, valorizamos conhecimento em containers.
- Git básico.

### Suas Responsabilidades:
- Desenvolver, testar e manter aplicações web integradas.
- Trabalhar em conjunto com designers e outros desenvolvedores para garantir interfaces que sejam não apenas atraentes, mas também funcionais e eficientes.
- Implementar novas funcionalidades e otimizar as existentes, sempre visando a melhor experiência do usuário.

Se você é movido por tecnologia e inovação e busca uma oportunidade para alavancar suas habilidades em um ambiente que fomenta o crescimento profissional, nós queremos conhecer você! Envie seu currículo e venha discutir como pode contribuir para nossa jornada de sucesso.

---

## Sobre o Teste

O teste consiste em criar uma página de listagem de produtos com paginação.

### Descrição do Projeto

Você deve desenvolver uma aplicação Vue.js que consuma uma API para listar produtos em uma página. Cada produto possui detalhes como nome, imagem, link de venda e informações sobre o especialista. A listagem deve incluir paginação para navegar entre as páginas de produtos.

### Endpoints da API

- **Página 1:** [https://raw.githubusercontent.com/kebookprogramacao9/teste-kebook/main/pages/1.json](https://raw.githubusercontent.com/kebookprogramacao9/teste-kebook/main/pages/1.json)
- **Página 2:** [https://raw.githubusercontent.com/kebookprogramacao9/teste-kebook/main/pages/1.json](https://raw.githubusercontent.com/kebookprogramacao9/teste-kebook/main/pages/2.json)
- **Demais páginas:** [https://raw.githubusercontent.com/kebookprogramacao9/teste-kebook/main/pages/1.json](https://raw.githubusercontent.com/kebookprogramacao9/teste-kebook/main/pages/[...].json)

### Estrutura de Dados

Cada arquivo JSON possui a seguinte estrutura:
```json
{
	"data": {
		"products": [
			{
				"id": "2511",
				"productName": "Nome do Produto",
				"thumbmail": {
					"filename_disk": "nome-do-arquivo.png"
				},
				"sellingLink": "url-do-produto",
				"expert": {
					"first_name": "Nome do Especialista",
					"avatar": {
						"filename_disk": "nome-do-arquivo-avatar.jpg"
					}
				}
			},
			...
		]
	}
}
```

### Requisitos do Projeto

1. **Interface de Usuário:**
   - Crie uma interface visualmente agradável para listar os produtos.
   - Exiba o nome do produto, a imagem do produto, o nome do especialista e o avatar do especialista.
   - Cada item da lista deve ter um link que redireciona para o `sellingLink` do produto.

2. **Paginação:**
   - Implemente a paginação para navegar entre as diferentes páginas de produtos.
   - A navegação deve ser intuitiva e permitir ao usuário mudar de página facilmente.

3. **Boas Práticas:**
   - Utilize componentes Vue.js para uma melhor organização do código.
   - Aplique boas práticas de CSS, preferencialmente utilizando um framework como TailwindCSS ou Bootstrap.
   - Escreva um código limpo e documentado.

### Como Enviar o Teste

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/kebookprogramacao9/teste-kebook.git
   ```

2. **Crie uma nova branch com seu nome:**
   ```bash
   git checkout -b seu-nome
   ```

3. **Implemente sua solução e faça commit das mudanças:**
   ```bash
   git add .
   git commit -m "Minha solução para o teste de desenvolvedor junior Vue.js"
   ```

4. **Envie sua branch para o repositório:**
   ```bash
   git push origin seu-nome
   ```

5. **Crie um Pull Request:**
   - Vá até a página do repositório no GitHub e crie um Pull Request da sua branch.

### Prazo de Submissão

O prazo para a submissão do teste é de 7 dias a partir do recebimento deste documento. Caso tenha alguma dúvida ou precise de mais informações, não hesite em nos contatar.

Estamos ansiosos para ver sua solução e conhecer mais sobre suas habilidades!

Boa sorte! 🚀
