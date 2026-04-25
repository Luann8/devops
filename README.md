<h1 align="center">Mastering DevOps</h1>

<p align="center">
Automação com Vagrant, Ansible e Orquestração com Docker
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Vagrant-1868F2?style=for-the-badge&logo=vagrant&logoColor=white">
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
</p>

<hr>

<h2>Sobre o Projeto</h2>

<p>
Este projeto demonstra a evolução de um ambiente de desenvolvimento tradicional para uma arquitetura moderna baseada em containers e microserviços, aplicando práticas de DevOps como automação, padronização e orquestração.
</p>

<hr>

<h2>1. Provisionamento e Automação</h2>

<p>
A base do projeto é a criação automatizada de ambientes utilizando:
</p>

<ul>
  <li><strong>:contentReference[oaicite:0]{index=0}</strong>: criação de máquinas virtuais</li>
  <li><strong>:contentReference[oaicite:1]{index=1}</strong>: configuração automática dos nós</li>
</ul>

<p><strong>Principais automações:</strong></p>

<ul>
  <li>Instalação do Docker (<code>installdocker.yml</code>)</li>
  <li>Configuração de banco de dados (<code>installdb.yml</code>)</li>
</ul>

<hr>

<h2>2. Conteinerização</h2>

<p>
A aplicação foi modularizada em containers independentes, garantindo isolamento e escalabilidade.
</p>

<ul>
  <li><strong>:contentReference[oaicite:2]{index=2}</strong>: plataforma de conteinerização</li>
</ul>

<p><strong>Estrutura dos serviços:</strong></p>

<ul>
  <li><strong>Dockerfileweb</strong>: aplicação (lógica de negócio / frontend)</li>
  <li><strong>Dockerfiledb</strong>: banco de dados</li>
  <li><strong>Dockerfilenginx</strong>: proxy reverso</li>
</ul>

<hr>

<h2>3. Orquestração</h2>

<p>
A integração dos serviços é realizada por meio do Docker Compose, permitindo subir todo o ambiente com um único comando.
</p>

<ul>
  <li><strong>:contentReference[oaicite:3]{index=3}</strong>: orquestração dos containers</li>
</ul>

<p><strong>Arquitetura da aplicação:</strong></p>

<ul>
  <li><strong>Nginx</strong>: entrada da aplicação</li>
  <li><strong>Web</strong>: processamento das requisições</li>
  <li><strong>DB</strong>: persistência de dados</li>
</ul>

<hr>

<h2>Extras</h2>

<ul>
  <li>Script de backup (<code>backup.php</code>)</li>
  <li>Organização baseada em separação de responsabilidades</li>
</ul>

<hr>

<h2>Objetivo</h2>

<p>
Aplicar na prática conceitos fundamentais de DevOps, incluindo:
</p>

<ul>
  <li>Automação de infraestrutura</li>
  <li>Conteinerização</li>
  <li>Orquestração de serviços</li>
  <li>Reprodutibilidade de ambientes</li>
</ul>

<hr>

<p align="center">
Projeto com foco em boas práticas de engenharia de software e DevOps.
</p>
