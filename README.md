# Projetos na 42sp
Todos os projetos desenvolvidos na escola 42 São Paulo.

[![roglopes's 42 stats](https://badge42.vercel.app/api/v2/clljwl4dk005408mn48ta77wy/stats?cursusId=21&coalitionId=piscine)](https://github.com/JaeSeoKim/badge42)

- [O que é a 42](#o-que-é-a-42)
- [Visão geral do currículo](#visão-geral-do-currículo)
	- [Fase 1](#fase-1)
	- [Fase 2](#fase-2)
	- [Fase 3](#fase-3)
- [Como clonar este repositório](#como-clonar-este-repositório)

# O que é a 42

> *"Sem aulas, sem professores, sem grade horária: acreditamos no poder de **botar a mão na massa**, na **excelência** de habilidades, em avaliações **entre pares** e num sistema de progressão como de **videogames** para fomentar o aprendizado. Os grandes marcos se expressam através de níveis de experiência ao invés de horas-aula. Sua experiência individual determina o seu ritmo de aprendizado."*
_[Adaptado de material promocional (em inglês).](https://www.42.us.org/wp-content/uploads/2020/01/42-Booklet-Spring-2020.pdf)_

![Galáxia da 42 - o santo gráfico](https://user-images.githubusercontent.com/49699403/209717594-ea05be2d-14d7-42e1-a4db-22ea612d251c.png)


O programa-constelação se divide em duas partes principais: o tronco principal de conhecimentos fundamentais (camadas internas, também chamado de **common core**), e as trilhas complementares de **especialização** (camada mais externa), ramificando rumo ao infinito e além.

O *common core* é composto de 16 projetos que cobrem conceitos fundamentais da Ciência da Computação, e a cada projeto entregue você ganha habilidades novas e XP (pontos de experiência) para passar de fases e avançar em direção ao chefão: o grande **Transcendence**.

![Visual representation of the 16 projects of the common core divided into 3 parts](https://user-images.githubusercontent.com/49699403/146021410-fdd95ceb-d3ce-436c-ba6f-c836d0d1a922.png)
_(Projetos sob o mesmo número são alternativas para aprender na prática determinado conceito, apenas um deve ser escolhido.)_

A partir deste ponto, tripulantes da nave mãe passam a orbitar os anéis mais distantes da galáxica, e estão livres para escolher um caminho para seguir se epecializando, ou até mesmo criar uma trilha de especialização para que outras pessoas tripulantes possam seguir depois de zerarem o *common core*.

# Visão geral do currículo

![image](https://user-images.githubusercontent.com/49699403/210290764-7fe036d4-cd88-482f-8a3d-77f5c5b403f7.png)

Fundamentalmente o grande objetivo de aprendizado da 42 é aprender a base e aprender a aprender, de maneira que a trilha básica de fundamentos forma pessoas capazes de aprender rápido qualquer linguagem, framework ou paradigma novo de programação, em um mundo em constante evolução.

Na 42 São Paulo, o *common core* se divide em 3 partes principais. As primeiras duas são desenvolvidas inteiramente em C e Shell Scripts. Na terceira parte há uma mudança para a linguagem C++ e o paradigma de Programação Orientada a Objetos (POO), e tecnologias complementares de front-end, back-end e containerização.

Todos os projetos da fase 1 são individuais. A partir da fase 2, tripulantes da nave-mãe devem se juntar para trabalhar em pares ou em grupos, para trabalhar, aprender e resolver problemas juntes. Os projetos em grupo estão sinalizados com um :restroom:.

## Fase 1

|   nome	|   assunto	|   resumo	|
|---	|---	|---	|
| **[libft](https://github.com/RogerioLS/Libft-42sp.git)**| Biblioteca estática, Makefile. 	| Construa sua própria biblioteca de funções básicas em C, que será utilizada por todo o resto do *common core*. Algumas funções ```ft_*``` são réplicas de funções tradicionais da libC, outras são personalizadas, e todas devem ser escritas usando no máximo ```write()``` e ```malloc()```.	|
| **[get_next_line](https://github.com/RogerioLS/Get_Next_Line-42sp.git)** 	| *File descriptors* e alocação estática/dinâmica de memória. 	| Escreva uma função que lê o conteúdo de um *file descriptor* e retorna uma linha, ou seja, uma sequência de caracteres terminada em ```\n```. Este projeto é subsequentemente incorporado à Libft.	|
| **[ft_printf](https://github.com/RogerioLS/Ft_Printf-42sp)** 	| String de formatação e funções variádicas. 	| Faça sua própria ```printf```! Este projeto é subsequentemente incorporado à Libft.	|
| **[Born2BeRoot]()** 	| Virtualização. 	| Monte um servidor SSH em Linux, com elementos fundamentais de administração de sistemas, regras de senha forte, criptografia e muito mais.	|
| **[So_Long]()** / fractol / fdf 	| Renderização de janelas e gerendiamento de eventos de mouse/teclado. 	| Aprendendo a desenhar visuais gráficos em janelas! Escolha entre desenhar fractais (`fractol`), projeção semi-3D isométrica (`fdf`) ou um videogame top-down em 2D (`so_long`). Projetos feitos utilizando a Minilibx, uma API do sistema X11. 	|
| **[pipex]()** / minitalk 	| Introdução a processos Unix. 	| Escolha entre construir um par de cliente e servidor conversando entre si (`minitalk`), ou simular o operador de *pipe* (`\|`) do Bash usando os conceitos de *pipes* e *forks* em C (`pipex`).	|


## Fase 2
|   nome	|   assunto	|   resumo	|
|---	|---	|---	|
| **[Push_Swap]()** 	| Algoritmos de ordenação e pilhas. 	| Uma lista de números desordenados deve ser ordenada, com um detalhe: para serem ordenados, devem-se utilizar exatamente `duas pilhas`, e 11 operações de pilhas pré-determinadas.	|
| **[Minishell]()** :restroom: 	| Uma versão mini de uma shell Bash escrita em C. 	| Inclui a análise léxica e semântica necessária para operar pipelines e redirecionamentos, determinados built-ins, e a estrutura necessária para executar comandos via `$PATH` ou caminhos absolutos.	|
| **[Philosophers]()** 	| Paralelismo com *threads* em C. 	| Resolva o famoso problema do Jantar de Filósofes proposto por Dijkstra, evitando concorrência de dados (*data racing*) e impasses (*deadlocks*).	|
| **Netpractice** 	| Redes e roteamento. 	| Uma série de problemas simulando LAN's e redes conectadas à internet. Para resolvê-los (em menos de 15 minutos!) é necessário conhecimento de *endereços IP* e *tabelas de roteamento*.	|
| **[Cub3d]()** / miniRT :restroom: 	| Renderização 3D 	| Estudo aprofundado sobre computação gráfica para construir um motor de renderização em janelas utilizando a Minilibx. Escolha entre a renderização de perspectivas 3D por meio de raios projetados (*raycasting*, projeto `cub3d`), ou de renderização de objetos 3D com a técnica de contorno por luz e sombra (*raycasting*, projeto `miniRT`).	|

## Fase 3
|   nome	|   assunto	|   resumo	|
|---	|---	|---	|
| **CPP**	| Programação Orientada a Objetos.	| 9 listas de exercícios para guiar o aprendizado mão-na-massa sobre conceitos clássicos da POO.	|
| **ft_containers**	| Estruturas de dados clássicas.	| Cosntrua sua própria réplica de alguns *containers* (estruturas de dados) da biblioteca padrão de C++: *vectors*, *maps*, *stacks* e árvore binária rubro-negra, implementando classes, iteradores, *overload* de operadores e mais.	|
| **inception**	| Containerização de uma aplicação web.	| Usando `docker-compose` e `Dockerfile`, configure uma rede de containers que contém os serviços necessários para rodar um servidor de Wordpress (servindo arquivos estáticos HTML e com banco de dados).	|
| **webserv / ft_irc** :restroom:	| Protocolos da Internet em C++.	| Escolha entre construir um servidor HTTP que recebe requisições e serve um arquivo estático (`webserv`) ou um serviço de bate-papo IRC que segue o protocolo TCP/IP (`ft_irc`). 	|
| **Transcendence** :restroom:	| Jogue o renomado *Pong* online com as amizades!	| Em time, faça a implantação de uma aplicação web em que qualquer tripulante da 42 pode logar e arranjar uma dupla para jogar uma partida de *Pong*. A aplicação deve ser capaz de transmitir partidas ao vivo, permitir que tripulantes se adicionem em listas de amizades, *achievements* e mais.	|


# Como clonar este repositório
Este repositótio contém submódulos git, ou seja, links para outros repositórios que guardam o código fonte de cada projeto separadamente. Se você apenas executar um `git clone`, a pasta baixada estará praticamente vazia. Caso deseje clonar esse repositório com todo o conteúdo de todos os submódulos, adicione a flag `--recurse-submodules` no seu `git clone`, desse jeito:

```
git clone --recurse-submodules https://github.com/RogerioLS/Projets_42_SP.git
```

Mas se quiser clonar apenas o código de um projeto específico, basta clicar no link do projeto desejado na página principal deste repositório, e cloná-lo.

<br><br>

---

<br><br>

### **Valeu!** :wink: