
# Laravel Migration

Aprendendo a usar uma Migration

## Instalação

Instalação do Projeto

```bash
  git clone https://github.com/fantasma1234/Laravel-Migration
  cd nome-projeto
  composer install
  npm install
  npm run build
  copy .env.example .env
  php artisan key:generate
  php artisan migrate
  php aritisan serve
```

## Fotos do Processo de Instalação do Laravel
Primeiro instale o composer e o xampp, depois abre o terminal e digite <br>
<img width="478" height="95" alt="1" src="https://github.com/user-attachments/assets/a89bad50-f958-4257-a3e8-a6cbc55968fa" />

Com o Laravel pronto digite para criar o projeto <br>
Obs: Alunos é o nome do meu projeto, coloque o nome que você quiser <br>
<img width="447" height="63" alt="2" src="https://github.com/user-attachments/assets/604d48cb-3d80-4326-ac21-3ee3e47566ff" />

<img width="750" height="413" alt="3" src="https://github.com/user-attachments/assets/e581b26a-3ac2-4ae2-a994-e5caf4cfa10c" />

<img width="747" height="205" alt="4" src="https://github.com/user-attachments/assets/3d3e8ac4-c849-4042-a60c-73d747a27780" />

Obs: Antes do yes ligue o XAMPP<br>
<img width="751" height="36" alt="5" src="https://github.com/user-attachments/assets/acf831d8-6639-476e-9ca5-dd2bbbd248f7" />

<img width="752" height="52" alt="6" src="https://github.com/user-attachments/assets/06096777-ef67-44cf-9702-008084e58170" />

<img width="750" height="192" alt="7" src="https://github.com/user-attachments/assets/3c29e95b-e10c-4bcc-a15a-66e511f09afe" />

## Fotos do Processo de Execução da Migration
Use o comando <code>php artisan make:migration create_(Insira o nome da sua tabela)_table</code> <br>
Isso cria uma migration <br>
<img width="747" height="121" alt="8" src="https://github.com/user-attachments/assets/9716c29d-8ee8-47ca-bb70-f89487c88418" />

Crie alguns campos na sua migration <br>
<img width="1264" height="900" alt="code" src="https://github.com/user-attachments/assets/d3b78c26-ff9a-4cf3-bcab-7e92e9bed4b0" />

Agora digite <code>php artisan migrate:refresh</code> <br>
reseta todas as migrations e as executa automaticamente <br>
<img width="752" height="246" alt="9" src="https://github.com/user-attachments/assets/f4a87252-304d-40f1-8479-426c85d57998" />
