# Sobre esse repositório

Esse repositório contém artefatos de simulações numéricas para o trabalho 4 que fazia parte dos requisitos para aprovação na disciplina  Modelamento Térmico e Fluidodinâmico aplicado a sistemas metalúrgicos, oferecida pelo [Departamento de Engenharia de Metalúrgica e de Materiais](https://demet.eng.ufmg.br/) da [Universidade Federal de Minas Gerais](https://ufmg.br/) durante o segundo semestre de 2017 pelo [professor Roberto Parreiras Tavares](https://www.linkedin.com/in/roberto-tavares-4374598).

# About this repository

This repository contains numerical simulation artifacts made for Assignment #4, which was partial requirement for approval in course Thermal and Fluidodynamics Modelling applied to metallurgical systems, offered by [Metallurgical and Materials Engineering Department](https://demet.eng.ufmg.br/) from [Federal University of Minas Gerais](https://ufmg.br/) during second semester of 2017 by [professor Roberto Parreiras Tavares](https://www.linkedin.com/in/roberto-tavares-4374598).

# Sobre o problema estudado

O escoamento e transferência de calor em tubo cilíndrico foram simulados através do método dos volumes finitos por meio do software Ansys R18.1 / Solver Fluent. O caso base foi apresentado pelo [professor Rajesh Bhaskaran](https://www.engineering.cornell.edu/people/rajesh-bhaskaran/) em vídeos do curso [A Hands-on Introduction to Engineering Simulations](https://learning.edx.org/course/course-v1:CornellX+ENGR2000X+1T2017/home), disponível na plataforma edX, e consistiu da seguinte geometria, propriedades do fluido e condições de contorno:

- Geometria: tubo cilíndrico reto, diâmetro de $20\ cm$ e comprimento de $3\ m$. Paredes lisas.
- Regime de escoamento laminar
- Fluido de densidade igual a $1\ kg/m³$, viscosidade igual a $0,002\ kg/m.s$, calor específico igual a $1006,43\ J/kg.K$ e condutividade térmica igual a $0,0242\ W/m.K$.
- Velocidade e temperatura do fluido constantes na entrada do tubo e iguais a $1\ m/s$ e $373,15\ K$, respectivamente.
- Pressão na saída do tubo igual a $1\ atm$.
- Fluxo de calor na parede do tubo igual a $100\ W/m²$ e dirigido para fora (ou seja, promovendo o resfriamento do fluido).

As condições de contorno térmicas são exclusivas desse trabalho e não estavam presentes no problema inicial, que consistia somente do escoamento laminar no tubo.


# About the analyzed problem

The fluid flow and heat transfer in a cylindrical tube were simulated through finite volume method using Ansys R18.1 and Fluent solver. The base case was presented by [professor Rajesh Bhaskaran](https://www.engineering.cornell.edu/people/rajesh-bhaskaran/) in videos from the course [A Hands-on Introduction to Engineering Simulations](https://learning.edx.org/course/course-v1:CornellX+ENGR2000X+1T2017/home), available in edX platform, and consisted of the following geometry, fluid properties and boundary conditions:

- Geometry: straight cylindrical tube, diameter of $20\ cm$ and length of $3\ m$. Smooth walls.
- Laminar flow regime - Fluid with a density of $1\ kg/m³$, viscosity of $0.002\ kg/m.s$, specific heat of $1006.43\ J/kg.K$, and thermal conductivity of $0.0242\ W/m.K$.
- Fluid speed and temperature at the entrance of the tube are constant at $1\ m/s$ and $373.15\ K$, respectively.
- Pressure at the exit of the tube is equal to $1\ atm$. - Heat flux at the wall of the tube is equal to $100\ W/m²$ and directed outward (i.e., promoting the cooling of the fluid).

The thermal boundary conditions are exclusive to this work and were not present in the initial problem, which consisted only of the laminar flow in the tube.