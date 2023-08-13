# Casa de Temporada - API REST e Aplicação Angular

Este é o repositório principal do projeto "Reservas", que contém dois submódulos importantes: "reservas" e "reservas-frontend". Esses submódulos são repositórios separados que trabalham em conjunto para fornecer funcionalidades completas para o sistema de reservas.

## Tecnologias Utilizadas

![Angular](https://img.shields.io/badge/angular-0D1117.svg?style=for-the-badge&logo=angular&logoColor=DD0031&labelColor=0D1117)
![TypeScript](https://img.shields.io/badge/typescript-0D1117.svg?style=for-the-badge&logo=typescript&logoColor=23007ACC&labelColor=0D1117)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-0D1117.svg?style=for-the-badge&logo=tailwind-css&logoColor=2338B2AC&labelColor=0D1117)
![Spring](https://img.shields.io/badge/spring-0D1117.svg?style=for-the-badge&logo=spring&logoColor=236DB33F&labelColor=0D1117)
![Java](https://img.shields.io/badge/Java-0D1117?logo=openjdk&logoColor=ED8B00&style=for-the-badge)


## Como Executar

1. Clone este repositório e todos os submódulos, com o seguinte comando:

	```bash
		git clone --recursive https://github.com/Major2571/CasaDeTemporadaIBM.git
	```
Isso garantirá que você tenha os submódulos "reservas" e "reservas-frontend" incluídos e atualizados em seu repositório local.

#### Backend
1. Navegue até o diretório do projeto backend:

	```bash
		cd reservas
	```
3.  Certifique-se de que você possui o Java Spring Boot e o H2 Database configurados em seu ambiente de desenvolvimento.
4.  Execute a aplicação.

A API REST de Reservas estará em execução em [http://localhost:8080](http://localhost:8080/). Certifique-se de que a API esteja em execução antes de iniciar o frontend.

#### Frontend

1. Navegue até o diretório do projeto frontend:
 
	```bash
		cd reservas-front
	```
3.  Certifique-se de que você possui o Node.js e o Angular CLI instalados em sua máquina.
    
4.  Instale as dependências do projeto frontend:
	```bash
		npm i
	```
    
5.  Execute o projeto frontend:
	```bash
		ng serve
	```

A aplicação Angular estará em execução em [http://localhost:4200](http://localhost:4200/).

**Observação:** Certifique-se de que o servidor da API backend também esteja em execução para que a aplicação frontend possa consumir os dados corretamente.

Esta seção fornece as instruções necessárias para executar os projetos backend e frontend localmente em seu ambiente de desenvolvimento. Certifique-se de seguir as etapas acima para iniciar ambos os projetos com sucesso.

## Saiba Mais

Se você deseja explorar mais detalhes sobre cada uma das partes deste projeto, você pode acessar os repositórios correspondentes:
<div align="center">
  <a href="https://github.com/Major2571/reservas"><img height="130" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=Major2571&repo=reservas&show_icons=true&count_private=true&hide_border=true&title_color=FD6767&icon_color=9A1A27&text_color=c9d1d9&bg_color=0d1117" alt="github-readme-streak-stats"></a>
  <a href="https://github.com/Major2571/reservas-front"><img height="130" src="https://denvercoder1-github-readme-stats.vercel.app/api/pin/?username=Major2571&repo=reservas-front&show_icons=true&count_private=true&hide_border=true&title_color=FD6767&icon_color=9A1A27&text_color=c9d1d9&bg_color=0d1117" alt="github-readme-streak-stats"></a>
</div>
