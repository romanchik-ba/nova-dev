# **Локальная работа в Git (<i>через проводник</i>)**
## 1. Сначала установить следующее ПО:

🟠 <b>[Git](https://git-scm.com/)</b>

🟠 <b>[Node JS](https://nodejs.org/en)</b>

🟠 <b>[VS Code](https://code.visualstudio.com)</b>

## 2. Затем создать папку, в которой нажать ПКМ и выбрать <b><span style="color:#1dd126">Open GIT Bash here</span><b>

## 3. В открывшемся окне терминала вписать команду: 
```bash 
git clone https://github.com/NovaDevelopersCo/nova-learn-landing.git -b develop
```
<br>

# **Локальная работа в Git (<i>через VS Code</i>)**
## 1. Выполнить 1 шаг из прошлого раздела

## 2. Запустить VS Code, выбрать(создать) папку для клонирования проекта. Затем запустить терминал (`Ctrl` + `Shift` + `Ё`) 

## 3. В открывшемся окне терминала вписать команду: 
```bash 
git clone https://github.com/NovaDevelopersCo/nova-learn-landing.git -b develop
```
После окончания загрузки всех файлов, выполнить команду:

```bash 
npm i -g yarn
```

> <b><span style="color:#83dae6"> >  **Совет:** Если появляется ошибка <span style="color:#e6432e"> about_Execution_Policies at... ,</span> то нужно запустить <b>PowerShell</b> от имени администратора и вписать туда команду: 
    ```
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted
    ```</span></b>
