# **Project Documentation**  

## **Index**  
1. [Introduction](#introduction)  
2. [Project Structure](#project-structure)  
3. [Description of Files and Folders](#description-of-files-and-folders)  
4. [Code Explanation](#code-explanation)  
   - [Module/File 1](#modulefile-1)  
   - [Module/File 2](#modulefile-2)
   - [Module/File 1](#modulefile-1)
   - [Module/File 1](#modulefile-1)   
5. [Implementation Examples](#implementation-examples)  
6. [Evidence](#evidence)  
7. [References](#references)
---

## **Introduction**  
Proporciona un resumen general del propósito de este documento.  
- ¿Qué busca explicar?  
- ¿Qué nivel de detalle se proporciona?  
- ¿A quién está dirigido (desarrolladores, usuarios finales, etc.)?  

> Este documento describe la funcionalidad y estructura del código fuente incluido en este repositorio. Su objetivo es ayudar a los desarrolladores a entender las partes clave del proyecto y cómo estas interactúan entre sí.  

---

## **Project Structure**  
Incluye una vista general de la estructura de archivos y carpetas del repositorio, con una breve explicación de su contenido.  

```plaintext
├── carpeta1/  
│   ├── archivo1.py  # Breve descripción  
│   ├── archivo2.py  # Breve descripción  
├── carpeta2/  
│   ├── archivo3.py  # Breve descripción  
├── README.md         # Instrucciones generales  
├── documentation.md  # Documentación detallada  
---
```
## **Description of Files and Folders**  
Explicación:
- **Module 1: User Authentication**: Este módulo se encarga de autenticar a un usuario usando las credenciales proporcionadas.
- **Module 2: Session Creation**: Crea una sesión para un usuario autenticado, guardando el nombre de usuario y la hora de inicio.
- **Module 3: Database Connection**: Conecta a la base de datos utilizando `sqlite3`.
- **Module 4: Execute Database Queries**: Ejecuta una consulta SQL proporcionada a la base de datos.
- **Module 5: Close Database Connection**: Cierra la conexión a la base de datos cuando ya no es necesaria.

## **Code Explanation**  
**Ports declaration**
```vhdl
port(
        RST : in std_logic;
        Clock : in std_logic;
        dir: in std_logic;
        pos : out std_logic_vector(3 downto 0);
        player_1_point: out std_logic_vector(3 downto 0);
        player_2_point: out std_logic_vector(3 downto 0);
        reset_speed: out std_logic := '0'
    );
```
For this block we use 3 inputs, in this case it gives the logic for adding points to each player
### **LED_Loop: User Authentication**  
```plaintext
#Codigoooooooo 
# Module 1: User Authentication
def authenticate_user(username, password):
    if username in users_db and users_db[username] == password:
### **Module 1: User Authentication**  
```
### **GameLogicLED: User Authentication**  
```plaintext
#Codigoooooooo 
# Module 1: User Authentication
def authenticate_user(username, password):
    if username in users_db and users_db[username] == password:
### **Module 1: User Authentication**  
```
### **Game: User Authentication**  
```plaintext
#Codigoooooooo 
# Module 1: User Authentication
def authenticate_user(username, password):
    if username in users_db and users_db[username] == password:
### **Module 1: User Authentication**  
```
### **DisplayDecoder: User Authentication**  
```plaintext
#Codigoooooooo 
# Module 1: User Authentication
def authenticate_user(username, password):
    if username in users_db and users_db[username] == password:
### **Module 1: User Authentication**  
```
### **Basys3: User Authentication**  
```plaintext
#Codigoooooooo 
# Module 6: User Authentication
def authenticate_user(username, password):
    if username in users_db and users_db[username] == password:
### **Module 1: User Authentication**  
```

