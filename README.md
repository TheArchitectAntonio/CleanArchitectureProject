# CleanArchitectureProject
𝐇𝐨𝐰 𝐈 𝐒𝐭𝐫𝐮𝐜𝐭𝐮𝐫𝐞 𝐌𝐲 𝐂𝐥𝐞𝐚𝐧 𝐀𝐫𝐜𝐡𝐢𝐭𝐞𝐜𝐭𝐮𝐫𝐞 𝐏𝐫𝐨𝐣𝐞𝐜𝐭𝐬 (𝐅𝐨𝐥𝐝𝐞𝐫 𝐛𝐲 𝐅𝐨𝐥𝐝𝐞𝐫)
Clean Architecture isn’t just about principles, it’s about clarity. A well-structured folder setup keeps your code scalable, testable, and easy to navigate.

![How I Structure My Clean Architecture Projects](https://github.com/user-attachments/assets/1cb17dc0-f874-431d-823f-8fde5b901c17)

This project follows a clean architecture, dividing responsibilities into well-defined layers. The structure of the project is detailed below.

## 1.- Domain Layer
This is the core of the system, 100% pure C#.

![Captura de pantalla 2025-05-15 a la(s) 2 28 29 a m](https://github.com/user-attachments/assets/e1b59f9d-fdc1-4583-b82f-c2ded0580bb9)

## 2.- Application Layer
This layer defines what your system should do.
![Captura de pantalla 2025-05-15 a la(s) 2 28 51 a m](https://github.com/user-attachments/assets/83d50b5e-4180-4c98-bf6d-6d6de55b2550)

## 3.- Infrastructure Layer
This is where tech details live. It implements all the abstractions.
![Captura de pantalla 2025-05-15 a la(s) 2 29 08 a m](https://github.com/user-attachments/assets/e6a7993b-b379-4009-8130-64e1b4a6d45f)

## 4.- Presentation Layer
This is the entry point: Controllers, Endpoints.
![Captura de pantalla 2025-05-15 a la(s) 2 29 26 a m](https://github.com/user-attachments/assets/853599bf-a104-4c49-b79e-fe8ea447dbb7)


### Technologies Used
.NET 6/7/8/9/10 (depending on the project)
- MediatR
- FluentValidation
- Entity Framework Core
- RabbitMQ / Azure Service Bus (si aplica)
- Swagger
- Serilog / ILogger
- Automapper

### Contributions
Want to contribute? Great! Please:
- Create a fork of the repository.
- Create a branch (git checkout -b feature/name).
- Make your changes.
- Create a Pull Request.

### License
This project is licensed under the MIT license. See the LICENSE file for more information.
