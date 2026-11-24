# Иванова Елизавета, ФИТ-1-2025. П06. Деплой веб-сервера с помощью role Ansible

## ЧАСТЬ 1
Структура файлов 

<img width="570" height="292" alt="image" src="https://github.com/user-attachments/assets/6c4fdfea-7ed1-43a2-a13a-019ea97774b4" />


Заполняем файлы: 

inventory.ini

<img width="412" height="77" alt="image" src="https://github.com/user-attachments/assets/17482337-2cd2-4126-b226-b54e9abdb4a2" />

---

playbook.yml

<img width="410" height="331" alt="image" src="https://github.com/user-attachments/assets/716234e9-7584-43e5-bc38-04e748b81f07" />

---

run_playbook.sh

<img width="745" height="77" alt="image" src="https://github.com/user-attachments/assets/988c1314-7962-48df-94f3-64c35184c8d1" />

---

roles/nginx-vhosts/handlers/main.yml

<img width="739" height="151" alt="image" src="https://github.com/user-attachments/assets/41457212-7f38-4c9d-ab1c-86612d458341" />

---

roles/nginx-vhosts/tasks/main.yml

<img width="822" height="675" alt="image" src="https://github.com/user-attachments/assets/2959a169-bab6-4598-982b-2fa7c4aaa6b3" />

---

roles/nginx-vhosts/templates/index.html.j2

<img width="825" height="138" alt="image" src="https://github.com/user-attachments/assets/498129a9-be52-4e2e-baa9-cc3908ae31ac" />

---

roles/nginx-vhosts/templates/site.conf.j2

<img width="813" height="278" alt="image" src="https://github.com/user-attachments/assets/f80cb2f8-7567-485a-97c8-9b9e981f999b" />

---

Проверяем 

<img width="680" height="326" alt="image" src="https://github.com/user-attachments/assets/4d578687-77b7-48bd-8897-d4d00a199163" />

## ЧАСТЬ 2

Создаем репозиторий и переносим файлы командами 

```

git clone https://github.com/lisssassaa/Devops_lab6.git
cp -r ~/devops5_nginx_vhosts/* .

```
Добавляем .github/workflows/devops_course_pipeline.yml

<img width="458" height="284" alt="image" src="https://github.com/user-attachments/assets/c9e605e1-1cd7-4b58-9fea-dcf48398255a" />

.github/workflows/lint.yml

<img width="425" height="289" alt="image" src="https://github.com/user-attachments/assets/d3f806c1-57af-4709-b3b6-aeb8509b2a4c" />

Проверяем 

<img width="1040" height="370" alt="image" src="https://github.com/user-attachments/assets/462bfa62-f889-46be-83c8-4e40bcff1fcc" />


